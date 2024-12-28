# Q-Sar

Q-Sar (pronounced like Quasar) is a powerful Headless CMS written in Rust. Q-Sar offers users features beyond the normal Headless CMS capabilities. Using the latest and greatest technologies, and best practices, makes this Headless CMS like a true Quasar... an extremly luminous power!

But what makes it different from other Headless CMS out there? What features does it offer? Well...

## Features

- Content Management (Default)
- AI Powered Content Writing
- AI Powered SEO
- Process Automation
- Built-in Security
    - Monitoring
    - Logging
    - Firewall
    - ...
- Analytics
- Plugin Market

## Tech Stack

As stated earlier, this project is (mostly) written in Rust. The following crates (more might be added soon) are being used:

- Axum (Has Tokio, Hyper and Tower included)
- Hyper
- Serde
- Tokio
- Tower
- Tracer

By default this project uses **SurrealDB** as its database. SurrealDB is a multi-model database written in... Rust! The reason for choosing it is to see if a complete Rust based backend has benefits in performance and security. However, support for other databases (PostgreSQL, MySQL, MongoDB, ...) will be added as well over time.

For the UI the decission was made to use **Dioxus**. How was this decission made? After carefully considering the options of using full-stack Rust or using a JavaScript framework, the decission was made to support the growing full-stack Rust domain. However... since the backend and frontend are developed separately, one can always program a frontend for Q-Sar using a JavaScript framework. Feel free to fork and who knows... we might come back on our decission if it seems that a JavaScript framework is the better way to go for this project.

## Installation

More information coming soon...

## License

This project falls under the protection of a GNU AGPLv3 license. Please, read it carefully in order to avoid violations.