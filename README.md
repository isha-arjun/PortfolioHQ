
# Portfolio HQ

**Your work, achievements, and growth — documented in one place.**

Portfolio HQ is a browser-based personal portfolio archive for documenting projects, achievements, activities, certificates, and learning milestones. It helps you preserve evidence of your work over time and makes it easier to prepare for future applications, opportunities, and personal reviews.

## ✨ Features

- **Project portfolio** — Document apps, games, websites, experiments, and research with descriptions, links, and status.
- **Achievement tracker** — Record awards, milestones, competition results, and other accomplishments.
- **Activities & leadership** — Keep track of team roles, responsibilities, volunteering, and contributions.
- **Certificates & evidence** — Attach supporting documents, images, and other files.
- **Growth journal** — Build a timeline of what you worked on, what you learned, and what you want to improve.
- **Dashboard overview** — See entry counts, recent updates, and portfolio-section coverage.
- **Search and filtering** — Find documented projects and other records.
- **GitHub import** — Import metadata from public GitHub repositories into project entries.
- **Backup and restore** — Export your archive as JSON, restore a backup, or merge entries while skipping detected duplicates.
- **Responsive interface** — Use the dashboard on desktop or mobile-sized screens.
- **Light and dark appearance** — Supports the browser's color-scheme preference.

## 🎯 Why Portfolio HQ?

Projects and achievements are easy to forget about when you're busy building new things. Links change, details get lost, and it becomes harder to remember the decisions and lessons behind a finished project.

Portfolio HQ provides a single place to record:

- What you created or contributed to
- The tools and skills you used
- The problems you encountered
- The results and feedback you received
- Evidence that supports your work
- What you learned and what you would do next

The goal is not simply to collect impressive-looking entries. It is to build an accurate, useful record of your development over time.

## 🚀 Getting Started

### Option 1: Use the hosted version

If a live deployment is available, open it in your browser:

**Live demo:** https://isha-arjun.github.io/PortfolioHQ/

### Option 2: Run locally

1. Download or clone this repository.
2. Open the project folder.
3. Open `index.html` in a modern web browser.
4. Add a project or another entry to get started.

No package manager, build process, or backend server is required for the current standalone version.

## 📖 How to Use

### 1. Add an entry

Choose **Add entry** or use one of the quick-capture shortcuts on the overview page.

Select the appropriate entry type:

- Project
- Achievement
- Activity / leadership
- Certificate / evidence file
- Growth journal reflection

### 2. Document the details

Give the entry a descriptive title and explain what you actually did. Add dates, categories, relevant links, supporting files, and lessons learned where applicable.

For collaborative projects, distinguish your own contribution from the work completed by others.

### 3. Import public GitHub projects

Enter a public GitHub profile or repository URL in the import section. Portfolio HQ retrieves available public repository metadata and creates project entries.

Review imported entries afterward. Repository metadata alone does not establish your personal contribution, project impact, or completion status.

### 4. Edit or organize entries

Use the relevant section to search, filter, review, edit, or delete records.

### 5. Export backups

Use **Export backup** to download a JSON file containing your portfolio entries. Keep backups somewhere safe and export them regularly.

To restore a backup, select the JSON file or drag it into the backup import area. The importer can merge entries into the current archive and skip detected duplicates.

## 🧰 Built With

- **HTML5** — Page structure
- **CSS3** — Styling, responsive layouts, and interface design
- **Vanilla JavaScript** — Application logic and interactions
- **Web Storage API (`localStorage`)** — Browser-local persistence
- **File API** — Reading and attaching supported files
- **GitHub REST API** — Importing public repository metadata

## 🏗️ Project Structure

The current standalone version is intentionally simple:

```text
portfolio-hq/
└── index.html
```

The HTML file contains the interface, styles, and JavaScript needed to run the application.

## 🔒 Privacy & Data Storage

**Important: Portfolio HQ is currently a browser-local prototype, not a cloud-synced account system.**

- Entries are stored in the browser's local storage on the current device and browser profile.
- Data is not automatically synchronized across devices.
- Clearing browser data or losing access to the browser profile may remove saved entries.
- Uploaded files are stored as data within the local browser archive.
- The current prototype limits individual attachments to approximately 1.5 MB.
- GitHub importing requires an internet connection and access to the public GitHub API.
- Private GitHub repositories are not supported by the importer.

### Recommended precautions

1. Export backups regularly.
2. Keep original certificates and important documents in a separate, backed-up folder.
3. Test backup restoration before relying on a backup as your only copy.
4. Avoid storing passwords, private credentials, or unnecessary sensitive information.
5. Be careful when sharing screenshots or public portfolio links containing personal information.

## ⚠️ Current Limitations

- No user accounts or authentication
- No cloud database or automatic cross-device sync
- No automatic cloud backup
- No private-repository import
- Browser storage capacity varies by browser and device
- Large attachments may exceed available storage
- Portfolio coverage is a documentation reminder, not a measure of ability or application readiness

## 🗺️ Roadmap

Potential future improvements include:

- [ ] Cloud synchronization and secure account-based storage
- [ ] Automatic backup reminders
- [ ] Export a selected portfolio as a shareable PDF
- [ ] Public portfolio pages with privacy controls
- [ ] Tags, custom fields, and more advanced filtering
- [ ] Project milestones and progress history
- [ ] Evidence previews and improved attachment management
- [ ] Automated validation and broader browser testing
- [ ] Accessibility improvements and usability testing

These are ideas for future development, not claims about features already implemented.

## 🤝 Contributing

Contributions, suggestions, bug reports, and usability feedback are welcome.

1. Open an issue describing the problem or proposed improvement.
2. For code changes, create a branch and make a focused change.
3. Test the affected functionality in a browser.
4. Submit a pull request with a clear explanation of the change.

Please do not include private certificates, personal records, credentials, or other sensitive information in public issues or pull requests.

## 📄 License

MIT License.

## 👤 Author

Created by **isha-arjun**.

If you find Portfolio HQ useful, consider starring the repository, reporting issues, or suggesting improvements.
