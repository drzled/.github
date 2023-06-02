<!-- Drzl README.md -->

## 🚀 Welcome to Drzl!

Drzl (pronounced `/dri·zl/` , like "drizzle") enables effortless deployment of web apps anywhere, leveraging Docker and Traefik for seamless transitions and zero downtime. Compatible with your preferred hosting environments, Drzl works flawlessly across multiple hosts, supporting any containerized web applications.

## 🌐 Find Us

Explore the Drzl documentation and find more resources to kickstart your deployment journey:

- 📚 Documentation: [Drzl Documentation](https://drzl.dev/docs)
- 🐦 Twitter: [@drzled](https://twitter.com/drzled)
- 🌟 GitHub Organization: [Drzl](https://github.com/drzled)

## 🙌 Get Involved

Drzl is an open-source project and we welcome contributions from the community. If you're interested in getting involved, here's how you can contribute:

- 🎯 Check out our Contribution Guidelines: [Contributing to Drzl](https://github.com/drzled/.github/blob/main/CONTRIBUTING.md)
- 🐛 Report issues or request features: [Drzl Issues](https://github.com/drzled/drzled/issues)
- 🌟 Star the project on GitHub: [Drzl](https://github.com/drzled/drzl)

## 🚀 Quick Start

To get started with Drzl, follow these steps:

1. Install Drzl on your local machine using the following command:

```bash
composer global require "drzled/drzl"
```

2. Make sure Composer's global bin directory is added to your system's PATH variable, so you can run Drzl from anywhere:

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

Did you know that the Drzl team starts their mornings with a cup of virtual coffee while coding away? ☕️

Enjoy using Dzl and happy deploying! 🚀
