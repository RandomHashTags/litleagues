# litleagues
A league scheduling &amp; hosting service.

The actual code is not publicly available at this time.

View service at https://litleagues.com

View updates and progress at https://litleagues.com/newsroom

## Tech Stack
- Language: [Swift](https://www.swift.org) 6.0
- IDE:
  - [Visual Studio Code](https://code.visualstudio.com)
  - [Xcode](https://developer.apple.com/xcode/) (rarely)
- Website:
  - HTML, JavaScript, CSS
  - [Swift HTMLKit](https://github.com/RandomHashTags/swift-htmlkit)
- Networking:
  - [Vapor](https://github.com/vapor/vapor) (switching to [Destiny](https://github.com/RandomHashTags/destiny) when stable)
  - [nginx](https://nginx.org) (only for reverse proxy)
- TLS/SSL:
  - [Certbot](https://certbot.eff.org)
  - [Let's Encrypt](https://letsencrypt.org)
- DNS: [Porkbun](https://porkbun.com/) (previously [Google Domains](https://domains.google/) and [Squarespace](https://www.squarespace.com))
- Database:
  - [Fluent](https://github.com/vapor/fluent) + [Fluent PostgreSQL](https://github.com/vapor/fluent-postgres-driver) (switching to [swift-database](https://github.com/RandomHashTags/swift-database) when stable)
  - [PostgreSQL](https://www.postgresql.org)
- Mail Server: [Postfix](https://en.wikipedia.org/wiki/Postfix_(software))
- Physical Server: Locally hosted [AMD Threadripper](https://www.techpowerup.com/cpu-specs/ryzen-threadripper-1900x.c1912) running [Arch Linux](https://en.wikipedia.org/wiki/Arch_Linux)

Some custom written stuff include [macros](https://docs.swift.org/swift-book/documentation/the-swift-programming-language/macros/), advanced caching system via [actors](https://docs.swift.org/swift-book/documentation/the-swift-programming-language/concurrency/#Actors), localization system to support multiple languages, and minification logic for JavaScript & CSS files for production.

## Features
- Generates league schedules and tournament brackets in seconds
- Many league and tournament settings to tailor your schedules exactly how you want
- Export as PDF
- [coming soon] Database features (creating accounts, joining teams, organizing leagues & tournaments, saving schedules & schedule settings)

## Update Frequency
Usually the first Friday of every month (so, once a month). Sometimes more if the updates are necessary (bug fixes, security patches) or I get notable stuff done.
