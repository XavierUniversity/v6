# V6 Development

V6 is a future environment when we decide to move forward with production level code. At this time, it is a holding ground for discussion, ideas and any preliminary code builds.

## Requirements

- [Lando](https://lando.dev)
  - [LEMP Stack](https://docs.lando.dev/config/lemp.html)
  - [NodeJS](https://docs.lando.dev/config/node.html#supported-versions)
    - Dev Dependencies:
      - Node-Sass
      - Browserify
      - Browsersync
      - NPM-Run-All
      - onchange

## Installation

Clone this repository and rename it for your project. Make sure to update the name in the `.lando.yml` and `package.json` file before 
running any of the commands below.

```bash
# Start up lando
lando start
# Start browsersync and the watch functions
lando npm start
```

## Contribution

Developers of Xavier University may contribute to the improvement through pull requests.
Please begin the process by opening an issue for internal discussions.
