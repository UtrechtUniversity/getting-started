![banner.jpg](images/banner.jpg)

# Getting started

Welcome to the getting started with [Utrecht University GitHub organization page](https://github.com/UtrechtUniversity). A GitHub organization is a shared account where members (UU employees) can manage their projects using their personal GitHub account. The UtrechtUniversity Github organization is meant for storing, managing and publishing research projects. Below you will find instructions for connecting to the organization and general usage instructions for the organization. See the bottom of the page for resources to get started with using Git for version control.

For best practices, see [Best Practices for Git @UtrechtUniversity](https://github.com/UtrechtUniversity/best-practices).

## First time connecting to UtrechtUniversity GitHub

You can connect to the Utrecht University GitHub organization when you are an UU employee only. Connect using your personal existing GitHub account. During this proces you will have to authenticate via your SolisID. The aim of this is to get access to the organization, however after access you will still be working under your personal GitHub account. By using your personal GitHub account all your contributions in different organizations and personal repositories can be displayed on your personal profile page which is your Github CV.

### Quick start

1. [Create a personal GitHub account](https://github.com/join) (not necessary if you already have a GitHub account)
2. Login to your personal GitHub account
3. [Configure two-factor authentication for your GitHub account](https://docs.github.com/en/authentication/securing-your-account-with-two-factor-authentication-2fa/configuring-two-factor-authentication)
4. **[Connect to the organization](https://github.com/orgs/UtrechtUniversity/sso) (one time only)**
5. Authenticate using your Solis ID. This will make you a member of the organization and gives you permissions to create repositories and teams.
6. Go to [https://github.com/UtrechtUniversity](https://github.com/UtrechtUniversity) and start working. 

### Command line and RStudio access
To get initial access to the organization, follow the steps above.

> :warning: After switching on 2FA for your GitHub account, you cannot connect to your remote repositories using HTTPS URLs in combination with your GitHub password anymore. You will need to configure an SSH key or a Personal Access Token instead. These are one-time actions. After that your interaction with GitHub will be as before.

Use an SSH key or a Personal Access Token to access your resources from the command line or from Rstudio, see [Using two-factor authentication with the command line](https://docs.github.com/en/enterprise-server@3.0/authentication/securing-your-account-with-two-factor-authentication-2fa/accessing-github-using-two-factor-authentication#using-two-factor-authentication-with-the-command-line). These keys have to be authorized to be used for the GitHub organization UtrechtUniversity. See the following instructions:

- SSH access  
  [Creating an SSH key](https://docs.github.com/en/github/authenticating-to-github/connecting-to-github-with-ssh)  
  [Authorizing SSH key for usage in the UU organization](https://docs.github.com/en/github/authenticating-to-github/authorizing-an-ssh-key-for-use-with-saml-single-sign-on)
- PAT access  
  [Authorizing Personal Access Token for usage in the UU organization](https://docs.github.com/en/github/authenticating-to-github/authorizing-a-personal-access-token-for-use-with-saml-single-sign-on)  
  [Personal Access Token for Rstudio and GitHub](https://happygitwithr.com/https-pat.html)



## Usage

###  Platform for research and UU projects 
Use this organization for research projects (or other UU-related work). Don't use this organization for exercises or personal activities.

### Code and non-sensitive data
This GitHub organization is meant for managing source code. GitHub is not suited to store datasets with personal and/or sensitive data. However, it is sometimes used for version control of documents or small sized, non-sensitive datasets. For research data, make sure that you create a data management plan first, and choose an [appropriate storage solution](https://www.uu.nl/en/research/research-data-management/tools-services/tools-for-storing-and-managing-data/storage-solutions).

### Work responsible
Be aware of the general UU [user regulations](https://intranet.uu.nl/en/security/information-security-policy-and-regulations) for ICT platforms, and [security best practices for GitHub](./docs/security-best-practices.md).
If you are a Git novice make sure to learn the [basics of Git version control](#learning-git) first in order to manage your projects in a responsible way. Typical dangers include: **publishing data that should not be published or publishing passwords**. Make sure you learn how to tell Git which files should and should not be tracked, especially if you work with any kind of sensitive data. Besides, be aware that if you (or any of your collaborators) have authorized any third-party applications, these applications are probably able to view data in your private repositories. 
- Read the [security best practices](./docs/security-best-practices.md) for more tips.    
- The Suitability level for this GitHub organization can be found in the Service Description on Intranet.  
- More about GitHub and GDPR compliance: [GitHub Data Protection Agreement](https://docs.github.com/en/github/site-policy/github-data-protection-agreement#attachment3) and [GitHub Privacy Statement](https://docs.github.com/en/github/site-policy/github-privacy-statement).

### GitHub Pages
Use GitHub Pages to promote research projects, e.g. by publishing a project website. For design purposes, is OK to use a UU logo. However, do not use any other design formats that relate to the University website (uu.nl).

### Repository naming conventions
Use repository names that are descriptive for the project. Don't use names that are in some way ambiguous, especially when they relate to law or policy (so e.g. repository names containing "policy" or "terms"). We reserve the right to rename repositories with ambiguous names. When in doubt [contact us](https://github.com/UtrechtUniversity/getting-started#contact).

### Copyrighted materials
Contact the [Copyright Information Office](https://www.uu.nl/en/organisation/copyright-information-office) if you have questions regarding working with copyrighted contents.


## Resources

### Creating Repositories
As soon as you have authenticated with your SolisID using the steps outlined above you will have permission to create Repositories in the [UU GitHub organization](https://github.com/UtrechtUniversity). View [GitHub Documentation](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/creating-a-new-repository) for instructions on how to create a repository.

### Creating Teams
Create teams to organize your team or project repositories. As soon as you have authenticated with your SolisID using the steps outlined above you will have permission to create teams in the [UU GitHub organization](https://github.com/UtrechtUniversity). View [GitHub Documentation](https://docs.github.com/en/organizations/organizing-members-into-teams) for instructions on how to create a team. Invite your team as a collaborator on a repository to make the repository appear on the Team overview page. 

### Inviting colleagues
When you create a repository or team, you will automatically have permission to invite collaborators. When you [invite](https://docs.github.com/en/organizations/organizing-members-into-teams/adding-organization-members-to-a-team) a UU colleague to a team they will automatically receive an invitation to join the UU GitHub organization. When you want to invite a UU colleague to a repository without using GitHub teams, the colleague should first become a member of the organization via the Getting Started steps above. When your colleague is a member you can invite your colleague to collaborate on repositories. 

### Inviting external collaborators
Invite non-UU collaborators or UU students as outside collaborator to repositories: [GitHub Documentation](https://docs.github.com/en/organizations/managing-access-to-your-organizations-repositories/adding-outside-collaborators-to-repositories-in-your-organization). Be responsible on inviting outside collaborators. Only invite them to repositories they need access to. 

### Transferring existing repositories to UtrechtUniversity
Migrate a repository to the UU GitHub organization by mirroring the repository ([instructions](https://docs.github.com/en/enterprise-server@3.1/github/creating-cloning-and-archiving-repositories/creating-a-repository-on-github/duplicating-a-repository#mirroring-a-repository)). 
> :warning: Do NOT use the "Transfer ownership" option in your repository settings to transfer a repository to UtrechtUniversity as you will lose admin rights for the repository. 

### GitHub actions limits
GitHub Actions minutes and storage are unlimited for public repositories. Whenever possible, use public repositories if you are using GitHub Actions. There are monthly limits for using GitHub actions in private repos on an organization level. **If this limit is reached GitHub action minutes will be disabled for private repos for the remaining part of the month**.

### GitHub apps and Third-party access
The following applications are approved for usage in the Organization:  

- [Zenodo](https://zenodo.org/)
- Codecov
- [Microsoft Teams](https://teams.github.com/)
- Slack
- Travis CI
- GitHub Desktop
- AllContributors

Activation of these apps for your repositories differs per application. [View instructions](docs/third-party-applications.md).

If you need any other applications, submit a request via [Topdesk](https://uu.topdesk.net)

## Learning Git

Using Git version control is key in the Open Science paradigm and helps managing versions of files, collaboration and publication.
A Git novice should invest some time to get acquainted with the way of working. Typically a one day course will get you started.

Resources:  
[Software carpentries course documentation](http://swcarpentry.github.io/git-novice/)  

Courses:  
[Best practices for writing reproducible code](https://www.uu.nl/en/research/research-data-management/training-workshops/best-practices-for-writing-reproducible-code)

## Contributing
We are very happy with any suggestions or contributions to improve the contents. The aim of this Repository is to help UU employees getting started with the Utrecht University GitHub organization. Read the contributing [guidelines](/CONTRIBUTING.md).

## License

The content in this repository is licensed [CC0-1.0](/LICENSE) (release to the public domain).

## Contact
its.ris@uu.nl

