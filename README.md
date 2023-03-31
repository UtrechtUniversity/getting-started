![banner.jpg](images/banner.jpg)

# Getting started

Welcome to the getting started with [Utrecht University GitHub organization page](https://github.com/UtrechtUniversity). A GitHub organization is a shared account where members can manage their projects using their personal GitHub account. The Utrecht University GitHub organization is meant for storing, managing and publishing research projects. Below you will find instructions for connecting to the organization and general usage instructions for the organization. See the bottom of the page for resources to get started with using Git for version control.

For best practices, see [Best Practices for Git @UtrechtUniversity](https://github.com/UtrechtUniversity/best-practices).

## First time connecting to the GitHub organization

Membership of the Utrecht University GitHub organization, including access to internal repositories, is restricted to employees of Utrecht University (UU). Become a member using your existing personal GitHub account; if you do not have an account yet, please create one. During this process, you will have to authenticate for this GitHub organization using your Solis-id. Your Solis-id is merely used to verify your employee status; all commits and actions performed in GitHub will be attributed to your personal GitHub account. By using one GitHub account, your GitHub profile page (which can be used as your curriculum vitae) will not only show your contributions in repositories belonging to this GitHub organization, but contributions in different GitHub organizations or personal repositories as well.

### Quick start

1. [Create a personal GitHub account](https://github.com/join) (not necessary if you already have a GitHub account)
2. Login to your personal GitHub account
3. [Configure two-factor authentication for your GitHub account](https://github.com/settings/security)  
   See [below](https://github.com/UtrechtUniversity/getting-started#command-line-and-rstudio-access) how to retain direct access to your repositories after switching on 2FA.
4. **[Connect to the organization](https://github.com/orgs/UtrechtUniversity/sso) (one-time only)**
5. Authenticate using your Solis-id. This will make you a member of the organization and grants you permission to create repositories and teams.
6. Go to [https://github.com/UtrechtUniversity](https://github.com/UtrechtUniversity) and start working!

### Command line and RStudio access
To get initial access to the organization, follow the steps above.

> :warning: After turning on two-factor authentication for your personal GitHub account, you cannot connect to your remote repositories using HTTPS URLs in combination with your GitHub password anymore. You will need to configure an 'SSH key' or a 'Personal Access Token' instead. This is a one-time action. After that your interaction with GitHub will be as before.

Use an SSH key or a Personal Access Token to access your resources from the command line or from RStudio, see [Using two-factor authentication with the command line](https://docs.github.com/en/enterprise-server@3.0/authentication/securing-your-account-with-two-factor-authentication-2fa/accessing-github-using-two-factor-authentication#using-two-factor-authentication-with-the-command-line). These keys have to be authorized to be used for [the GitHub organization UtrechtUniversity](https://github.com/UtrechtUniversity). When using an SSH key, you will need to change remote URLs in your repositories from HTTPS to SSH format. When using a PAT, you can continue using HTTPS URLs. See the following instructions:

- SSH access  
  [Creating an SSH key](https://docs.github.com/en/github/authenticating-to-github/connecting-to-github-with-ssh)  
  [Authorizing SSH key for usage in the UU organization](https://docs.github.com/en/github/authenticating-to-github/authorizing-an-ssh-key-for-use-with-saml-single-sign-on)  
  [Change the remote URLs of any existing repositories from HTTPS to SSH](https://docs.github.com/en/get-started/getting-started-with-git/managing-remote-repositories?platform=windows#switching-remote-urls-from-https-to-ssh)
- PAT access  
  [Authorizing Personal Access Token for usage in the UU organization](https://docs.github.com/en/github/authenticating-to-github/authorizing-a-personal-access-token-for-use-with-saml-single-sign-on)  
  [Personal Access Token for RStudio and GitHub](https://happygitwithr.com/https-pat.html)

## Usage

### Platform for research and UU projects 
Use this GitHub organization for research projects or other UU-related work. Do not use this organization for exercises or personal activities.

### Code and non-sensitive data
This GitHub organization is meant for managing source code. Using this GitHub organization is not recommended for storing datasets with personal or sensitive data (feel free to [contact Research Data Management Support](mailto:info.rdm@uu.nl) for advice). However, it may be used for version control of documents or small-sized non-sensitive datasets. For managing research data, make sure that you create a data management plan first and check the [Storage finder](https://www.uu.nl/en/research/research-data-management/tools-services/tools-for-storing-and-managing-data/storage-solutions) and [Tooladvisor](https://tools.uu.nl/tooladvisor/) for appropriate solutions. 

### Work responsibly
Be aware of the general university's [user regulations](https://intranet.uu.nl/en/security/information-security-policy-and-regulations) for ICT platforms, and [security best practices for GitHub](./docs/security-best-practices.md).
If you are a Git novice, make sure to learn the [basics of Git version control](#learning-git) first in order to manage your projects properly. Typical dangers include **publishing data that should not be published or publishing passwords**. Make sure you learn how to tell Git which files should and should not be tracked, especially if you work with any kind of sensitive data. Finally, be aware that if you (or any of your collaborators) have authorized any third-party applications, these applications may be able to view data in your private repositories. 
- Read the [security best practices](./docs/security-best-practices.md) for more tips.    
- The security (suitability) level for this GitHub organization can be found in the Service Description on Intranet.  
- More about GitHub and GDPR compliance: [GitHub Data Protection Agreement](https://docs.github.com/en/github/site-policy/github-data-protection-agreement#attachment3) and [GitHub Privacy Statement](https://docs.github.com/en/github/site-policy/github-privacy-statement).

### GitHub Pages
You can use GitHub Pages to promote research projects, for example, by publishing a project website. For design purposes, it is OK to use a UU logo. However, do not use any other design formats that relate to the university's corporate website ([uu.nl](https://www.uu.nl))

### Repository naming conventions
Use repository names that are descriptive for the project. Don't use names that are in some way ambiguous, especially when they relate to law or policy (e.g. repository names containing "policy" or "terms"). We reserve the right to rename repositories with ambiguous names. When in doubt, [contact us](https://github.com/UtrechtUniversity/getting-started#contact).

### Licensing and Copyrighted materials
Be sure to add a license to your work, since the license defines the rules for people who want to use your code/software. If you reuse licensed software, make sure that the license you choose is compatible with the license of the reused software. [Choosing a license](https://choosealicense.com/).

- Contact [Research Data Management Support](mailto:info.rdm@uu.nl) for questions regarding code and software licensing.
- Contact the [Copyright Information Office](https://www.uu.nl/en/organisation/copyright-information-office) if you have other questions regarding working with copyrighted contents.

## Resources

### Creating repositories
As soon as you have authenticated with your Solis-id using the steps outlined above, you are granted permission to create repositories in the [Utrecht University GitHub organization](https://github.com/UtrechtUniversity). View [GitHub documentation](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/creating-a-new-repository) for instructions on how to create a repository.

### Creating teams
Create teams to organize your team or project repositories. As soon as you have authenticated with your Solis-id using the steps outlined above, you will be able to create teams in the [Utrecht University GitHub organization](https://github.com/UtrechtUniversity). View [GitHub documentation](https://docs.github.com/en/organizations/organizing-members-into-teams) for instructions on how to create a team. Invite your team as a collaborator on a repository to make the repository appear on the Team overview page. 

### Inviting colleagues
When you create a repository or team, you will automatically have permission to invite collaborators. When you [invite](https://docs.github.com/en/organizations/organizing-members-into-teams/adding-organization-members-to-a-team) a colleague to a team, they will automatically receive an invitation to join the Utrecht University GitHub organization. When you want to invite a colleague to a repository without using GitHub teams, the colleague should first become a member of the GitHub organization via the Getting Started steps above. If your colleague is a member, you can invite your colleague to collaborate on repositories. 

### Inviting external collaborators
You can invite non-UU collaborators or students by adding them as external collaborator to repositories: [see GitHub documentation](https://docs.github.com/en/organizations/managing-access-to-your-organizations-repositories/adding-outside-collaborators-to-repositories-in-your-organization). Be responsible on inviting outside collaborators; only invite them to repositories they need access to. 

### Transferring an existing repository to this GitHub organization
Migrate a repository to the Utrecht University GitHub organization by [mirroring the repository](https://docs.github.com/en/repositories/creating-and-managing-repositories/duplicating-a-repository). 
> :warning: Do **not** use the "Transfer ownership" option in your repository settings to transfer a repository to this GitHub organization. You will lose admin rights for the repository. 

### GitHub Actions limits
GitHub Actions minutes and storage are unlimited for public repositories. Whenever possible, use __public__ repositories if you are using GitHub Actions. There are monthly limits for using GitHub actions in private repos on an organization level. **As soon as this limit has been reached, GitHub action minutes will be disabled for private repositories for the remaining part of the month**.

### GitHub applications and third-party access
The following applications are approved for usage in this GitHub organization:  

- [Zenodo](https://zenodo.org/)
- Codecov
- [Microsoft Teams](https://teams.github.com/)
- Slack
- Travis CI
- GitHub Desktop
- AllContributors

Activation of these applications for your repositories differs per application: [view instructions](docs/third-party-applications.md).

Submit an [issue](https://github.com/UtrechtUniversity/getting-started/issues/new) if you would like to use a new application.

## Learning Git

Using Git version control is key in the Open Science paradigm and helps managing versions of files, collaboration and publication.
A Git novice should invest some time to get familiar with the way of working. A one-day course will get you started.

Resources:
- [Software carpentries course documentation](https://swcarpentry.github.io/git-novice/)
- [GitHub Skills](https://skills.github.com)

Courses:  
- [Best practices for writing reproducible code](https://www.uu.nl/en/research/research-data-management/training-workshops/best-practices-for-writing-reproducible-code)

## Contributing
We are very happy with any suggestions or contributions to improve the contents. The aim of this Repository is to help UU employees getting started with the Utrecht University GitHub organization. Read the contributing [guidelines](/CONTRIBUTING.md).

## License
The content in this repository is licensed under the [Creative Commons Zero 1.0](/LICENSE) (release to the public domain).

## Contact
Do you need help or have any other requests? Submit an [issue](https://github.com/UtrechtUniversity/getting-started/issues/new) or send an email: its.ris@uu.nl
