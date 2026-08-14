# alexanderpaulat.de
This repository contains the source code for my personal cybersecurity portfolio and technical blog https://alexanderpaulat.de.

The site documents my work, learning, experiments, and research in cybersecurity, with focus on penetration testing and offensive security.

## About
I am Alexander Paulat, a developer and aspiring penetration tester with a strong interest in cybersecurity research and offensive security.

This portfolio serves several purposes:
- Documenting my learning and practical experience
- Publishing penetration testing and CTF writeups
- Documenting security-related projects and homelab work
- Sharing technical notes and research
- Maintaining practical cybersecurity cheat sheets
- Demonstrating my software development and infrastructure skills
- Providing a technical reference for my own work

The content assumes that readers have a basic understanding of IT and cybersecurity concepts. I generally do not explain common penetration-testing tools or terminology unless they are directly relevant to the topic.

## Content
The website will contain several types of content:

### Writeups
Practical walkthroughs of intentionally vulnerable and authorized environments, including:
- TryHackMe Rooms
- CTFs
- Security labs
- Other authorized training environments

Writeups document my methodology, reasoning, experiments, failed attempts, and lessons learned.

### Projects
Technical projects related to cybersecurity, software development, infrastructure, and my homelab.

Examples may include:
- Cybersecurity labs
- Penetration-testing tooling
- Security automation
- Cloud security projects
- Infrastructure projects
- This website itself

### Notes
Short technical articles about concepts, techniques, tools, and interesting things I encounter while learning and working in cybersecurity.

### Cheat Sheets
Practical reference material that I can use  during penetration testing and security research.

The Pentest Cheat Sheet will be maintained as a living reference rather than a one-time article.

## Technical Stacm
This website is built with:
- Astro
- TypeScript
- Markdown/MDX
- Svelte for selected interactive components
- GitHub
- GitHub Actions
- Azure Static Web Apps
- Visual Studio Code
- npm

The site is designed to be predominantly static. Client-side JavaScript is used only where it provides meaningful functionality.

## Desing Goals
The project is intentionally designed around the following principles:
### Security
Minimize the attack surface by avoiding unnecessary backend services, databases, user accounts, uploads, and user-generated content.

### Privacy

The site does not require advertising, tracking, analytics, or third-party social-media integrations.

### Performance

Content should be delivered primarily as static HTML with minimal client-side JavaScript.

### Reproducibility

The website should be reproducible from its source repository and deployable through an automated pipeline.

### Maintainability

The content structure, infrastructure, and deployment process should remain understandable and manageable over time.

### Accessibility

The site should remain usable across different devices and accessible to as many users as reasonably possible.

## Security

Security is an explicit part of this project.

The site is designed to have a small attack surface and to avoid storing unnecessary sensitive information.

For information about reporting security issues, see SECURITY.md.

## Development

The site is developed locally and version-controlled with Git.

The intended workflow is:

Research / Ideas
       ↓
Content creation
       ↓
Local development
       ↓
Testing
       ↓
Git
       ↓
GitHub
       ↓
CI/CD
       ↓
Azure Static Web Apps
       ↓
alexanderpaulat.de

Technical claims and experiments published on the site are verified where practical using controlled environments.

## Offensive Security Disclaimer

All security testing documented in this project is intended for systems and environments that I own, have explicit permission to test, or that are intentionally provided for security training.

I do not intend this project to encourage unauthorized access, exploitation, or other illegal activity.

New vulnerabilities are not currently a focus of this project. If vulnerability research becomes part of the portfolio in the future, disclosure will be handled with appropriate consideration for affected parties.

## License

For information about licensing, see LICENSE.