# Bitwarden Vault Dedupe 🗂️

A simple, privacy-focused tool to clean up duplicate entries in your Bitwarden vault. Built as a single HTML file with no external dependencies or data uploads.

## ✨ Features

- **Duplicate Detection** 🔍 - Find duplicate entries based on name, username, and URI combinations
- **Email Duplicate Detection** 📧 - Specifically identify accounts with the same email but different passwords
- **URI Matching Modes** 🌐 - Choose between full URI, hostname, or main domain matching
- **Password Generator** 🔐 - Built-in secure password generator with customization options
- **Data Privacy** 🔒 - All processing happens locally in your browser, no data leaves your computer
- **Light/Dark Mode** 🌙 - Automatic theme switching based on your system preference
- **Export Options** 💾 - Export cleaned vault in Bitwarden JSON or Google CSV format
- **File Merging** 🔄 - Merge multiple vault files together

## 🚀 Usage

1. Open `index.html` in your browser (Chrome, Firefox, Safari, Edge all work)
2. Click "Upload JSON" and select your Bitwarden export file
3. Choose your duplicate detection criteria from the dropdown:
   - `Name + Username + URI` - Matches entries with same name, username, and URI
   - `Name + URI` - Matches entries with same name and URI
   - `Exact JSON Match` - Matches entries that are identical in every way
4. Select URI matching mode (if needed):
   - Full URI - Match the complete URI
   - Hostname Only - Match only the domain name
   - Main Domain Only - Match only the main domain (e.g., github.com from subdomain.github.com)
5. Click "Detect duplicates" to identify potential duplicates
6. Review the highlighted entries in the table
7. Select which entries to keep/ignore using checkboxes
8. Click "Remove Selected" to clean your vault
9. Export your cleaned vault using the export button

## 🛠️ Development

This is a single-file application with no build process required:

- HTML, CSS, and JavaScript in one file
- No external dependencies
- Works offline
- No server required

## 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you'd like to change.

## 📄 License

MIT

## ⚠️ Disclaimer

- Always backup your Bitwarden vault before using this tool
- All data processing happens locally in your browser
- No data is sent to any server
- Use at your own risk

## 🐛 Issues

If you encounter any problems, please open an issue on GitHub.