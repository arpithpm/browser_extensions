# 🔧 Browser Extensions Collection

This repository contains a collection of useful browser extensions designed to automate and streamline various tasks on GitHub and job portals.

## 📁 Repository Structure

```
browser_extensions/
├── github pr approver/          # GitHub dependency PR auto-approver extension
└── job-referral-extension/      # Employee job referral automation extension
```

## 🚀 Extensions Overview

### 1. 🤖 [Dependency Auto Approver](https://github.com/arpithpm/extension.git)

A Chrome extension that automatically approves Dependabot and Renovate pull requests on GitHub while intelligently managing reviewers.

**Key Features:**
- ✅ **Auto-Approval**: Automatically approves dependency update PRs from Dependabot and Renovate
- 👥 **Smart Reviewer Management**: Adds configured reviewers/teams while avoiding duplicates
- 🔍 **User-Specific Detection**: Checks if you've already approved to prevent duplicate actions
- 🎯 **Repository Filtering**: Configure specific repositories or allow all
- 🛡️ **Safe Operation**: Only works on dependency bot PRs, ignores regular PRs

**Target Audience:** Developers who manage multiple repositories with dependency bots

**Installation:** Load as unpacked extension in Chrome Developer Mode

---

### 2. 💼 [Job Referral Assistant](https://github.com/arpithpm/job-referral-extension.git)

A Chrome extension that automates the process of referring friends and contacts to job opportunities through employee portals.

**Key Features:**
- 📝 **Contact Management**: Save and manage multiple referral contacts
- 🎯 **Smart Job Matching**: Auto-match jobs based on location and search terms
- 🔄 **Batch Processing**: Refer multiple contacts to matching jobs automatically
- 📊 **Load All Jobs**: Scroll through and load all available job postings
- 💾 **Form Auto-Fill**: Automatically fill referral forms with saved contact details
- 🌍 **Location Filtering**: Filter jobs by country code (e.g., US, UK, DE)
- 🔍 **Keyword Search**: Match jobs using flexible search terms (supports OR operators)

**Target Audience:** Employees who frequently refer candidates through company job portals

**Installation:** Load as unpacked extension in Chrome Developer Mode

## 🛠️ Development Setup

### Prerequisites
- Google Chrome or Chromium-based browser
- Developer mode enabled in Chrome extensions

### Installing Extensions

1. **Clone the repository:**
   ```bash
   git clone <repository-url>
   cd browser_extensions
   ```

2. **Open Chrome Extensions page:**
   - Navigate to `chrome://extensions/`
   - Enable "Developer mode" (toggle in top-right)

3. **Load extensions:**
   - Click "Load unpacked"
   - Select the specific extension folder:
     - For GitHub PR Approver: Select `github pr approver/` folder
     - For Job Referral Assistant: Select `job-referral-extension/` folder

4. **Pin extensions** to your toolbar for easy access

## 📋 Usage Instructions

### GitHub PR Approver
1. Click the extension icon to configure settings
2. Set your GitHub username
3. Add reviewers/teams to auto-assign
4. Enable/disable the extension as needed
5. Navigate to any GitHub PR - the extension works automatically

### Job Referral Assistant
1. Navigate to your company's job portal
2. Click the extension icon to open the popup
3. Enter referral contact details
4. Save contacts for future use
5. Use auto-referral features:
   - **Single Job**: Refer to currently viewed job
   - **Matching Jobs**: Auto-refer to all jobs matching criteria
   - **Load All**: Load all jobs and auto-refer in batches

## 🔧 Configuration

### GitHub PR Approver Configuration
- **Username**: Your GitHub username for duplicate detection
- **Reviewers**: List of users/teams to add as reviewers
- **Repository Filtering**: Optional repository restrictions

### Job Referral Assistant Configuration
- **Contact Details**: First name, last name, email, location
- **Search Terms**: Job keywords (supports OR operators)
- **Location Codes**: Country codes for job filtering (US, UK, DE, etc.)

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/new-feature`)
3. Make your changes
4. Test thoroughly with the target websites
5. Commit your changes (`git commit -am 'Add new feature'`)
6. Push to the branch (`git push origin feature/new-feature`)
7. Create a Pull Request

### Development Guidelines
- Follow existing code structure and naming conventions
- Test extensions with multiple scenarios
- Ensure error handling for edge cases
- Update documentation for new features
- Consider rate limiting and website performance impact

## 🐛 Troubleshooting

### Common Issues

**Extension not working:**
- Ensure you're on the correct website
- Check browser console for error messages
- Verify extension permissions are granted
- Try reloading the extension

**GitHub PR Approver not activating:**
- Verify you're on a GitHub PR page
- Check that PR is from Dependabot/Renovate
- Ensure your username is correctly configured

**Job Referral Assistant not finding jobs:**
- Verify you're on your company's job portal
- Check that job cards have expected HTML structure
- Try refreshing the page and reloading jobs

## 📄 License

This project is licensed under the MIT License - see individual extension folders for specific license details.

## 🔗 Links

- [GitHub PR Approver Repository](https://github.com/arpithpm/dependency-auto-approver)
- [Job Referral Assistant Repository](https://github.com/arpithpm/job-referral-extension)

## 📞 Support

For issues, feature requests, or questions:
1. Check the troubleshooting section above
2. Review individual extension documentation
3. Create an issue in the repository
4. Provide detailed error messages and steps to reproduce

---

**Note:** These extensions are designed for legitimate use cases and should be used responsibly. Always ensure compliance with your organization's policies and the terms of service of the websites you're automating.
