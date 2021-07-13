# Security Best Practices for GitHub
It is good to be aware of security risks when you start using version control on online platforms such as GitHub. When you use version control on a project with a few R scripts for analyses, the risks are typically small and minimal effort is needed to keep things secure. When projects become more complicated (e.g. when working with sensitive data, or setting up automated data processing pipelines), more emphasis on security best practices is needed. 
Find below a list of some general best practices for secure coding. They are loosely categorized as beginner (analysis scripts, non-sensitive data), intermediate (sensitive data, data processing pipelines) and advanced (developing high quality software packages).

## General
- [Set a strong password](https://intranet.uu.nl/en/news/news-items/set-a-strong-password-to-protect-your-personal-data) (beginner)
- [Secure your GitHub account with two-factor authentication (2FA)](https://docs.github.com/en/github/authenticating-to-github/securing-your-account-with-two-factor-authentication-2fa) (beginner)

## Best practices
- Use a `.gitignore` file to make sure secrets, dependencies and local configuration files are not tracked by GitHub (beginner)
- Regularly maintain permissions of members of your repositories (e.g. remove inactive members) (beginner)
- Keep software dependencies up to date (intermediate)
- Create a [security policy file](https://docs.github.com/en/code-security/getting-started/adding-a-security-policy-to-your-repository) (`SECURITY.md`) and add this to your repository (intermediate, when applicable)
- Read about and use GitHub conventions as much as possible (e.g. for using branches, branch naming and commit messages) (intermediate)
- Read about and use coding style guides and conventions as much as possible (intermediate/advanced)
- Be aware of secure coding practices (intermediate/advanced)

## Further reading:
- [GitHub Security Best Practices](https://www.datree.io/resources/github-best-practices)
- [Top 8 security issues](https://spectralops.io/blog/8-top-git-security-issues-what-to-do-about-them/)
- [Github Security Online Course](https://docs.microsoft.com/en-us/learn/modules/maintain-secure-repository-github/) (1 hour)
