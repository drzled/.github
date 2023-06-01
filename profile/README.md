<!-- DRZL README.md -->

## 🚀 Welcome to DRZL!

DRZL is a powerful command-line interface (CLI) that empowers you to deploy web apps anywhere. With DRZL, you can effortlessly deploy your web applications, from bare metal to cloud virtual machines, using Docker. Say goodbye to downtime, as DRZL leverages the dynamic reverse-proxy Traefik to handle requests while seamlessly transitioning between old and new application containers. It works flawlessly across multiple hosts, utilizing SSH for executing commands. While initially built for PHP applications, DRZL can be used with any type of web app that can be containerized with Docker.

## 🌐 Find Us

Explore the DRZL documentation and find more resources to kickstart your deployment journey:

- 📚 Documentation: [DRZL Documentation](https://drzl.dev/docs)
- 🐦 Twitter: [@DRZLHQ](https://twitter.com/drzldev)
- 🌟 GitHub Organization: [DRZL](https://github.com/drl)

## 🙌 Get Involved

DRZL is an open-source project and we welcome contributions from the community. If you're interested in getting involved, here's how you can contribute:

- 🎯 Check out our Contribution Guidelines: [Contributing to DRZL](https://github.com/DRZL/.github/blob/main/CONTRIBUTING.md)
- 🐛 Report issues or request features: [DRZL Issues](https://github.com/drzled/drzl/issues)
- 🌟 Star the project on GitHub: [DRZL](https://github.com/drzled/drzl)

## 🚀 Quick Start

To get started with DRZL, follow these steps:

1. Install DRZL on your local machine using the following command:

```bash
composer global require "drzled/drzl"
```

2. Make sure Composer's global bin directory is added to your system's PATH variable, so you can run DRZL from anywhere:

- For Unix-like systems (Linux, macOS, etc.), add the following line to your `~/.bashrc`, `~/.zshrc`, or similar file:

```bash
export PATH="$PATH:$HOME/.composer/vendor/bin"
```

- For Windows systems, add the Composer's global bin directory to your PATH variable manually.

3. Configure the deployment options by running the following command from your project's root folder:

```bash
drzl init
```
The command will create a directory called `.drzl` which will contain a `manifest.yml` file with all the required settings that need to deploy your app.

4. Deploy your web app anywhere with a single command:

```bash
drzl deploy
```

That's it! Your web app will be deployed using Docker, ensuring zero downtime and hassle-free deployments.

## 🍿 Fun Fact

Did you know that the DRZL team starts their mornings with a cup of virtual coffee while coding away? ☕️

Enjoy using DRZL and happy deploying! 🚀
