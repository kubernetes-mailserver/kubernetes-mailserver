[![GitHub Repo stars](https://img.shields.io/github/stars/kubernetes-mailserver/kubernetes-mailserver?style=flat)](https://github.com/kubernetes-mailserver/kubernetes-mailserver)
[![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)
[![](https://dcbadge.vercel.app/api/server/SxH6KUCGH7?style=flat)](https://discord.gg/SxH6KUCGH7)

<br>
<div align="center">
  <img src="https://github.com/kubernetes-mailserver/kubernetes-mailserver/assets/3041752/bb429c02-9950-46dc-8510-2881abd1ce97" alt="Kubernetes Mailserver" height="320">
</div>
<h3 align="center">Kubernetes Mailserver</h3>
<br>
<hr>


## 📦 What is Kubernetes Mailserver?

Kubernetes Mailserver is an email server based on [`docker-mailserver/docker-mailserver`](https://github.com/docker-mailserver/docker-mailserver)
packaged as a [`glasskube/glasskube`](https://github.com/glasskube/glasskube/) package.

## ⭐️ Why Kubernetes Mailserver?

Using **traditional package managers** or applying manifests directly can be **super confusing** and doesn't scale.
Therefore, a Glasskube package will help you to **install a mailserver** using the **Glasskube UI** for reduced complexity and increased transparency.
The **package is dependency aware** and will get automatic updates.

## ✨ Features
|                                                                                                   |                                                                                                                                       |
|---------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------|
| **Easy installation** <br> Easily install Kubernetes Mailserver via the Glasskube Package Manager | ![Overview](https://raw.githubusercontent.com/kubernetes-mailserver/.github/main/images/glasskube-kubernetes-mailserver-overview.png) |
| **UI Package configurations** <br> Configure Kubernetes Mailserver via a GUI.                     | ![GUI](https://raw.githubusercontent.com/kubernetes-mailserver/.github/main/images/glasskube-kubernetes-mailserver-detail.png)        |
| **CLI Package configurations** <br> Configure Kubernetes Mailserver via a CLI.                    | ![CLI](https://raw.githubusercontent.com/kubernetes-mailserver/.github/main/images/glasskube-kubernetes-mailserver-cli.png)           |



## 🚀 Quick Start

### 1. Install [Glasskube](https://glasskube.dev/)

You can install Glasskube via [Homebrew](https://brew.sh/):

```bash
brew install glasskube/tap/glasskube
```

### 2. Add the Kubernetes Mailserver Repo

```bash
glasskube repo add kubernetes-mailserver https://kubernetes-mailserver.github.io/glasskube-repo/packages
```

### 3. Install Kubernetes Mailserver

In order to use Kubernetes Mailserver you need to use a Domain and generate a [TLS Secret](https://kubernetes.io/docs/concepts/configuration/secret/#tls-secrets)
for it which you need to reference in the installation process.

You can install the Kubernetes Mailserver package either via the graphical user interface or the cli.

| GUI               | CLI                                       |
|-------------------|-------------------------------------------|
| `glasskube serve` | `glasskube install kubernetes-mailserver` |


## ☝️ Need Help or Want to Provide Feedback?

If you encounter any problems, we will be happy to support you wherever we can on our [Discord](https://discord.gg/SxH6KUCGH7).
For bugs, issues or feature requests fee free to [open an issue](https://github.com/kubernetes-mailserver/kubernetes-mailserver/issues/new).
We are happy to assist you with anything related to the project.

## 📎 Related Projects

- Glasskube Package Manager [`glasskube/glasskube`](https://github.com/glasskube/glasskube/)

## 🤝 How to Contribute to Kubernetes Mailserver

Your feedback is invaluable to us as we continue to improve Glasskube. If you'd like to contribute, consider trying out the beta version, reporting any issues, and sharing your suggestions. See [the contributing guide](CONTRIBUTING.md) for detailed instructions on how you can contribute.

## 🤩 Thanks to all our Contributors

Thanks to everyone, that is supporting this project. We are thankful, for evey contribution, no matter its size!

<a href="https://github.com/kubernetes-mailserver/kubernetes-mailserver/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=kubernetes-mailserver/kubernetes-mailserver" />
</a>

## 👾 Activity

![Kubernetes Mailserver Activity](https://repobeats.axiom.co/api/embed/1a4dc7b74b96c3cad7159a61ca227a6ddaca0c05.svg "Kubernetes Mailserver activity image")

## 📘 License

The Kubernetes Mailserver is licensed under the Apache 2.0 license. For more information check the [LICENSE](https://github.com/kubernetes-mailserver/kubernetes-mailserver/blob/main/LICENSE) file for details.
