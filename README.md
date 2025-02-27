# BioCheats: Bioinformatics Cheatsheets

Welcome to **BioCheats**, a repository of cheatsheets designed specifically for bioinformaticians working with command-line tools. This project offers quick reference guides to streamline your analysis and data processing tasks using commonly used bioinformatics commands.

## 📂 Contents

The repository is organized by tool or language. The current tools include:

- **BLAST/** - Cheatsheet for BLAST commands and usage.
- **Perl/** - Cheatsheet for Perl, including common one-liners and scripts.
- **AWK/** - Cheatsheet for AWK, with examples tailored for bioinformatics data manipulation.

This is a very, *very* short subset from the universe of bioinformatics tools and is intended to grow over time. Have a tool you want added? Either open an issue stating the tool and what commands you want, or contribute it through a pull request. 

## 📝 Cheatsheet Format

Each cheatsheet follows the [Navi cheatsheet syntax](https://github.com/denisidoro/navi). In these `.cheat` files you'll find:

- **Command Descriptions**: Lines starting with `#` explain the purpose of the commands.
- **Executable Commands**: Actual command lines with variable placeholders (e.g., `<input_file>`).
- **Variable Suggestions**: Lines starting with `$` provide suggestions to autocomplete variable values.
- **Tags**: Lines starting with `%` denote the section tags, making it easy to filter and navigate within Navi.

For more details on the syntax and customization, please refer to the [Navi documentation](https://github.com/denisidoro/navi).

## 🚀 Getting Started

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/grenkoca/biocheats.git
   cd biocheats
   ```

2. **Install Navi:**

   If you haven't installed Navi yet, follow the instructions on the [Navi GitHub page](https://github.com/denisidoro/navi).

3. **Load the Cheatsheets:**

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

