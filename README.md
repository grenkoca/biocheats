# BioCheats: Bioinformatics Cheatsheets

Welcome to **BioCheats**, a repository of cheatsheets designed specifically for bioinformaticians working with command-line tools. This project offers quick reference guides to streamline your analysis and data processing tasks using commonly used bioinformatics commands.

## What is Navi?

[Navi](https://github.com/denisidoro/navi) is an interactive cheatsheet tool for the command line that helps users quickly find and execute commands without memorizing complex syntax. It allows users to browse and run pre-written or custom command-line snippets, dynamically displaying suggested values for arguments.

[![Demo](https://asciinema.org/a/406461.svg)](https://asciinema.org/a/406461)

### Why Use Navi?
- **Saves Time** – No need to memorize CLI commands.
- **Reduces Errors** – Eliminates copy-pasting from intermediate commands.
- **Boosts Efficiency** – Minimizes typing and speeds up workflow.
- **Enhances Learning** – Helps users discover new and useful one-liners.

Cheatsheets are written in a simple format and can be shared or customized to suit individual needs. Learn more in the [official documentation](https://github.com/denisidoro/navi/blob/master/docs/cheatsheet_syntax.md). 🚀

**This project intends to create a centralized resource of Navi cheatsheets related to computational biology, bioinformatics, and the dry lab side of biomedical research.**

## 📂 Contents

The repository is organized by tool or language. The current tools include:

- **BLAST/** - Cheatsheet for BLAST commands and usage.
- **Perl/** - Cheatsheet for Perl, including common one-liners and scripts.
- **AWK/** - Cheatsheet for AWK, with examples tailored for bioinformatics data manipulation.

<ins>This is a very, *very* short subset from the universe of bioinformatics tools and is intended to grow over time.</ins>

Have a tool you want added? Either open an issue stating the tool and what commands you want, or contribute it through a pull request. 

## 📝 Cheatsheet Format

Each cheatsheet follows the [Navi cheatsheet syntax](https://github.com/denisidoro/navi). In these `.cheat` files you'll find:

- **Command Descriptions**: Lines starting with `#` explain the purpose of the commands.
- **Executable Commands**: Actual command lines with variable placeholders (e.g., `<input_file>`).
- **Variable Suggestions**: Lines starting with `$` provide suggestions to autocomplete variable values.
- **Tags**: Lines starting with `%` denote the section tags, making it easy to filter and navigate within Navi.

For more details on the syntax and customization, please refer to the [Navi documentation](https://github.com/denisidoro/navi).

## 🚀 Getting Started

1. **Install Navi:**

   If you haven't installed Navi yet, follow the instructions on the [Navi GitHub page](https://github.com/denisidoro/navi/blob/master/docs/installation.md).

   _Highest yield options:_
   - Using Homebrew: `brew install navi`
     
        _or_
   - Run install script: `bash <(curl -sL https://raw.githubusercontent.com/denisidoro/navi/master/scripts/install)`
     
        _or_ 
   - Build from source:
     ```
     git clone https://github.com/denisidoro/navi ~/.navi
     cd ~/.navi
     make install
     ```

   

3. **Clone BioCheats:**

   ```bash
   git clone https://github.com/grenkoca/biocheats.git
   cd biocheats
   ```

4. **Load the Cheatsheets:**

   ```bash
   navi --cheatsheets ./biocheats
   ```

## 🔍 Usage Examples

- **BLAST Cheatsheet** - Quickly reference commands for sequence similarity searches.
- **Perl Cheatsheet** - Discover Perl one-liners and script snippets for text processing.
- **AWK Cheatsheet** - Utilize AWK commands to filter, extract, and summarize data from various bioinformatics files.

## 🤝 Contributing

We welcome contributions to make **BioCheats** even more useful for the bioinformatics community! Here’s how you can help:

### 1️⃣ Fork the Repository
Click the **Fork** button on the top right corner of the GitHub page to create your own copy of the repository.

### 2️⃣ Create a New Branch
Develop your changes in a dedicated branch:
```bash
git checkout -b feature/your-feature-name
```

### 3️⃣ Make Your Changes
- Add or update cheatsheets following the [Navi cheatsheet syntax](https://github.com/denisidoro/navi).
- Update documentation if necessary.
- Ensure your cheatsheet commands are tested and working correctly.

### 4️⃣ Commit Your Changes
Commit your improvements with clear and descriptive commit messages:
```bash
git add .
git commit -m "Add/update cheatsheet for <tool/language>"
```

### 5️⃣ Push to Your Fork and Open a Pull Request
Push your branch to your fork and then open a pull request against the `main` branch:
```bash
git push origin feature/your-feature-name
```
Describe your changes and reference any related issues.

### 6️⃣ Code Review and Merge
Your pull request will be reviewed, and if everything looks good, it will be merged into the main branch.

## 🐛 Reporting Issues

If you encounter any issues or have suggestions for improvement, please open an [issue](https://github.com/grenkoca/biocheats/issues) on GitHub. We appreciate your feedback!

## 📜 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Happy analyzing! 🎉

