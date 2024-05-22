# Brewfiles

[![Homebrew](https://img.shields.io/badge/homebrew-000000?style=for-the-badge&logo=homebrew&logoColor=white)](https://brew.sh/)
![GitHub forks](https://img.shields.io/github/forks/dansholds/brewfiles?style=for-the-badge)
![GitHub stars](https://img.shields.io/github/stars/dansholds/brewfiles?style=for-the-badge)
![GitHub issues](https://img.shields.io/github/issues/dansholds/brewfiles?style=for-the-badge)

Welcome to the **Brewfiles Repository**! This is a community-driven project where users can share their `Brewfile` configurations. By contributing to this repository, you can help others quickly set up their macOS or Linux environments with Homebrew.

---

## 🚀 What is a Brewfile?

A `Brewfile` is a convenient way to describe the setup of your Homebrew packages, casks, and taps. It allows you to install all your dependencies with a single command. This is particularly useful for setting up a new machine or sharing your development environment with others.

---

## 📦 How to Use a Brewfile

1. **Clone the Repository**:
   ```sh
   git clone https://github.com/dansholds/brewfiles.git
   cd brewfiles
   ```

2. **Choose a Brewfile**:
   Browse through the available `Brewfile`s in the repository and select one that suits your needs.

3. **Install Packages**:
   Use the `brew bundle` command to install the packages listed in the selected `Brewfile`:
   ```sh
   brew bundle --file=path/to/Brewfile
   ```

---

## 🤝 How to Contribute

We welcome contributions from the community! Follow these steps to add your `Brewfile` to the repository:

1. **Fork the Repository**:
   Click the "Fork" button at the top right of this page to create a copy of this repository under your GitHub account.

2. **Clone Your Fork**:
   ```sh
   git clone https://github.com/dansholds/brewfiles.git
   cd brewfiles
   ```

3. **Create a New Branch**:
   ```sh
   git checkout -b your-branch-name
   ```
4. **Create your Brewfile**
   ```sh
   brew bundle dump --file=Brewfile
   ```
5. **Add Your Brewfile**:
   Place your `Brewfile` in a new directory named after the main purpose or the environment it sets up, for example, `web-development/Brewfile` or `data-science/Brewfile`.
   If the purpose or environment already exists, use something that makes it unique.

6. **Commit Your Changes**:
   ```sh
   git add .
   git commit -m "Add Brewfile for [describe environment]"
   ```

7. **Push to Your Fork**:
   ```sh
   git push origin your-branch-name
   ```

8. **Create a Pull Request**:
   Go to your fork on GitHub, and you should see a "Compare & pull request" button. Click it and submit your pull request.

---

## 📁 Directory Structure

Please follow this directory structure when adding your Brewfile:

```
brewfiles/
├── README.md
├── <category>/
│   └── Brewfile
```

Examples of categories include:
- `web-development`
- `data-science`
- `machine-learning`
- `devops`
- `design`

---

## 📜 License

This repository is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

---

## 📞 Contact

If you have any questions or suggestions, feel free to open an issue or contact the repository maintainers.

Happy brewing! 🍻
