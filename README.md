# litleagues
A league scheduling &amp; hosting service.

The actual code is not publicly available at this time.

View service at https://litleagues.com

View updates and progress at https://litleagues.com/updates

## Tech Stack
- Language: [Swift](https://www.swift.org) 5.10 (will be 6.0 when publicly available)
- IDE: [Visual Studio Code](https://code.visualstudio.com), sometimes [Xcode](https://developer.apple.com/xcode/)
- Website: HTML, Javascript, CSS, [Leaf](https://github.com/vapor/leaf)
- Networking: [Vapor](https://github.com/vapor/vapor), [nginx](https://nginx.org) (only for reverse proxy)
- SSL: [Certbot](https://certbot.eff.org), [Let's Encrypt](https://letsencrypt.org)
- DNS: was Google Domains, now [Squarespace](https://www.squarespace.com)
- Database: [Fluent](https://github.com/vapor/fluent), [Fluent PostgreSQL](https://github.com/vapor/fluent-postgres-driver), [PostgreSQL](https://www.postgresql.org)
- Mail Server: [Postfix](https://en.wikipedia.org/wiki/Postfix_(software))
- Physical Server: Locally hosted [AMD Threadripper](https://www.techpowerup.com/cpu-specs/ryzen-threadripper-1900x.c1912) running [Arch Linux](https://en.wikipedia.org/wiki/Arch_Linux)

Some custom written stuff include Swift [Macros](https://docs.swift.org/swift-book/documentation/the-swift-programming-language/macros/), advanced caching system via Swift [Actors](https://docs.swift.org/swift-book/documentation/the-swift-programming-language/concurrency/#Actors), localization system to support other languages, and minification logic for javascript & css files for production.

## Features
- Generates league schedules and tournament brackets in seconds
- Many league and tournament settings to tailor your schedules exactly how you want
- Export as PDF
- [coming soon] Database features (creating accounts, joining teams, organizing leagues & tournaments, saving schedules & schedule settings)
