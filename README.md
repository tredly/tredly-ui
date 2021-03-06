# Tredly Command Center

Version 1.0.2
July 15 2016

This is a software package to provide UI to a Tredly host. You can find out more information about Tredly at **<http://tredly.com>**

## Installation

Requires Tredly 1.0.0 <https://github.com/tredly/tredly> or later

Checkout this repo and run `./install.sh [URL]` to install, where "URL" is the container url ("cc.example.com" by default). After that reboot Tredly Host or run `service tredlycc start`.

Tredly Command Center will be created as a container and will be accessible over HTTPS protocol.

Installation script will generate self-signed SSL certificate, which you need to accept in your web browser.
Please, change this certificate for better security.

## Usage

Tredly Command Center is a web application. Supported browsers: Chrome, Firefox.

## Development

1. Install **Node.js**
2. Install **npm**
3. Install **RubyGems**
4. `gem update --system`
5. `gem install compass`
6. `gem install ceaser-easing`
7. `gem install susy`
8. `gem install breakpoint`
9. `sudo npm install bower -g`
10. `bower install`
11. `npm install`
12. `npm run build`
13. `npm start`
14. Open http://localhost:8089/

## Contributing

We encourage you to contribute to Tredly. Please check out the [Contributing documentation](https://github.com/tredly/tredly-cc/blob/master/CONTRIBUTING.md) for guidelines about how to get involved.

## License

Tredly is released under the [MIT License](http://www.opensource.org/licenses/MIT).
