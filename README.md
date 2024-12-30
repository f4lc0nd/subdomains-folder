# BugBounty Subdomains - Public Database
## Website: https://bugrecon.pro
### Link to Subdomain Enumeration : https://www.bugrecon.pro/tools/subdomain-finder

Welcome to the **BugBounty Subdomains** repository! This project is designed to help bug bounty hunters by providing a comprehensive and up-to-date collection of **subdomains** for legal bug bounty programs hosted on popular bug bounty platforms.

## About the Project

Bug bounty hunters often spend a significant amount of time discovering subdomains of target domains for their assessments. While many tools and methods exist for finding subdomains, **access to an up-to-date list** of subdomains can save valuable time and provide an essential starting point for recon and exploitation.

This repository contains **publicly available subdomain lists** for all bug bounty programs that are legally authorized for security testing. It is updated regularly to ensure bug bounty hunters have the most accurate and comprehensive data at their fingertips.

### Key Features:
- **Comprehensive Subdomain Data**: A curated list of subdomains across all major bug bounty platforms like HackerOne, Bugcrowd, Synack, and others.
- **Legal Programs Only**: All subdomains come from verified, legal bug bounty programs. We do not promote or endorse illegal activities.
- **Open-Source**: This repository is entirely open-source, meaning everyone can contribute and use it freely. Collaboration is highly encouraged!
- **Regular Updates**: The list is constantly maintained and updated to reflect changes and new programs.

## Supported Bug Bounty Platforms

This repository includes subdomains from the following platforms (and growing!):
- [HackerOne](https://www.hackerone.com)
- [Bugcrowd](https://www.bugcrowd.com)
- [Synack](https://www.synack.com)
- [Cobalt](https://cobalt.io)
- [YesWeHack](https://www.yeswehack.com)
- [Open Bug Bounty](https://www.openbugbounty.org)
- [Intigriti](https://www.intigriti.com)

## How to Use

1. **Clone the Repository**: Clone the repository to your local machine using the following command:

   ```bash
   git clone https://github.com/f4lc0nd/subdomains-folder.git
View Subdomains: Inside the repository, navigate to the subdomains directory to view a categorized list of subdomains:

```bash
cd bugbounty-subdomains/
```

Use the Subdomains for Recon: You can use the subdomain lists directly for recon tools such as sublist3r, amass, or subfinder, or simply run manual checks against your targets.

Update Your Subdomain List: Pull the latest updates from the repository to ensure you're always working with the freshest data:

```bash
git pull origin main
```
## Subdomain Format
The subdomains are stored in text files, organized by bug bounty platform and program. Each file contains subdomains in the following format:

```text
subdomain1.domain.com
subdomain2.domain.com
subdomain3.domain.com
...
```
Subdomains are listed in alphabetical order for easy access and search.

## How to Contribute
We welcome contributions! If you'd like to add new subdomains or update existing ones, please follow these steps:

Fork the repository.
Create a new branch for your changes.
Update the subdomain list or add new entries as necessary.
Open a Pull Request with a detailed description of your changes.
Please ensure that all contributions are from legal bug bounty programs only!

## Important Notes
Legality: Please note that this repository contains only subdomains from legally authorized bug bounty programs. You must not use this data for unauthorized security testing.
Responsible Disclosure: If you find any vulnerabilities while using this data, follow responsible disclosure guidelines.
No Warranty: This repository is provided "as is," and the maintainers are not responsible for any misuse or issues that arise.

## Disclaimer
This repository is intended for educational purposes and to support ethical security research. Using the data for unauthorized testing or any illegal activity is strictly prohibited.

By using this repository, you agree to adhere to ethical standards and comply with the terms and conditions of the respective bug bounty platforms.

## License
This repository is licensed under the GPL License.

## Contact
For any questions or concerns, feel free to open an issue in the repository or reach out to us at sofalcons@outlook.com.

Happy hunting, and may your findings improve the security of the internet! 🕵️‍♂️🔍
