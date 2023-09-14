As a researcher you might be interested in this GitHub thing you have been hearing so much about.
This article outlines what benefits you might get in the short and long term, what challenges you may face, and what to expect from the adoption of GitHub.
While primarily used for code storage and version control, GitHub offers many more features.
Based on both the experiences of other researchers and people in industry, you might be able to draw inspiration on how you might incorporate github into your research workflow.

# Table of contents

- [Table of contents](#table-of-contents)
- [What is GitHub](#what-is-github)
- [Basic adoption](#basic-adoption)
  - [For you](#for-you)
  - [For your team](#for-your-team)
  - [For the scientific community](#for-the-scientific-community)
- [Advanced adoption](#advanced-adoption)
- [Misconceptions, worries, and problems](#misconceptions-worries-and-problems)
  - [*My code is not good enough to be public*](#my-code-is-not-good-enough-to-be-public)
  - [*People will point out mistakes in my code*](#people-will-point-out-mistakes-in-my-code)
  - [*Company X won't let me*](#company-x-wont-let-me)
  - [*It is too hard for me*](#it-is-too-hard-for-me)
  - [*There is no time to learn*](#there-is-no-time-to-learn)
  - [*Nobody does it this way*](#nobody-does-it-this-way)
  - [*I have no time to maintain code*](#i-have-no-time-to-maintain-code)
- [How to get started](#how-to-get-started)
- [Resources](#resources)


# What is GitHub
To understand GitHub, first the underlying technology `git` must be explained.
`git` is a version control system.
What `git` does, is provide a way to save files and preserve version information (hence version control).
Consider you are writing a document and you have a version before review and after review, you might have 2 documents:

- `paper_pre_review.doc`
- `paper_post_review.doc`

What `git` will afford you is the possibility to have a single filename `paper.doc` that it has 2 versions of: `pre_review` and `post_review`.
You will be able to view any version and retrieve it at any time.
Additionally you can provide information about the version to make it easier to find.
Also, depending on the document type you can inspect the exact changes between the documents.

`git` works locally, meaning on your own computer and is a useful tool in itself.
Essentially `git` adds an additional dimension to how you save your files.
Not only is it stored in a place on your computer, but also in time.

`GitHub` is like a dropbox for files that you manage with `git`.
What this facilitates you is to collaborate with other people by authoring different versions of documents that build on top of each other.
For instance, you might write an introduction chapter and put the document on github.
Then your colleague will take that document, and write the methods section and publish a new version with the methods section.
Then you might extend the introduction with something you read in the methods section and create yet another more recent version of the document.

While this works relatively well with text, it works especially well with code.
Imagine your team works with a machine that generates a CSV file for an experiment that all of you run frequently.
You might have a colleague that writes and initial script that interprets the data and generates a boxplot.
For your research you might need a linear plot.
Instead of asking your colleague for his or her code and modifying it, you would check it out of github, add your code for generating a linear plot, and then re-upload it to github so that another colleague can use it too. 

The sharing however is not limited to just your colleagues.
You can share the code with the entire world and the entire world can contribute to your code too!
You can also easily reference it in papers and articles that you publish, specifying exactly which version you used to facilitate reusability.

GitHub offers many more features and their use will be explained alter in this document, but at the core it is just a place to store files.

# Basic adoption
`git` and `GitHub` have many features that can improve your workflow in many different ways, but not all time investments are equally rewarding.
The initial gains of adopting the bare minimal set of feature of `git` and `GitHub` are already very significant.
By basic adoption the following things are meant:

- [ ] You create a `GitHub` account
- [ ] You join a team of `Utrecht University` on `GitHub`
- [ ] You download `Github Desktop` 
- [ ] Once in a blue moon you put code on `GitHub` using the `Github Desktop` application

This would be an investment of at most 30 minutes for the first 3 steps, and 5 minutes per time that you put code on github and for it you will benefit individually, you will help your team, and you will increase your impact and reputation in the science community.

## For you
The most basic benefit is that you will have **backups** of your code.
By having it stored in the cloud, you will be always able to retrieve your code.
Not only the most recent version, but **every version** you have ever written.
You will be able to search through the versions you have submitted to `GitHub` and retrieve it at any time. 

By having your code on `GitHub` you will be able to refer to it in your research.
Just like a citation of literature, you can **cite a `GitHub` repository** in your paper.
You can cite your own code, but if you find other software on `GitHub` that you end up using, then you can cite that too!

Using `GitHub` also helps you **find useful software** for your research project.
You will not need to re-invent the wheel every time and figure out how to parse a CSV file. 

Just like publications in science journals, your **code is also a publication**.
Especially if you have ambitions of working with IT in the future, your shared code is a **portfolio** that you can show off to other employers.
You can see how many people like and use your software and you can expand it to be more useful to yourself and fellow researchers.

## For your team
Because you put your code on `GitHub`, your **colleagues can easily access your code** without having to ask you for it.
Not only that, but they can also expand upon the code to make it even better and more usable. 

Because you are part of a team, the **code does not disappear** when a colleague leaves to a new place.
Additionally, you can track bugs and request features through the `GitHub` interface that you might dedicate time to as a team to implement in the software.


## For the scientific community
By publishing your code on `GitHub`, you are contributing to tools for the scientific community as a whole.
You are **providing building blocks** for other researchers to do better, and more reliable research.
Additionally, you are improving your **reputation** by complying to `Open Science` and `FAIR` standards. 
This reputation can be a contributing factor for attracting **funding** opportunities from external investors.
You also provide a **public interface** for a part of your work.
A software engineer could contribute to your scientific pursuits by improving your code without being part of your research group.
Because you are part of the `Utrecht University` organization, your work will be showcased in frequently visited places making it more discoverable.
By having hte code on `GitHub`, you also make it much easier for other people to reproduce and verify your results, which in the long-term yields **higher quality research**. 

# Advanced adoption
The more you embrace features of `GitHub`, the more benefits you reap.
Because there is not really a `GitHub`-like model for science yet, it is mostly speculative what long-term benefits you may actually see.
<!-- TODO: Add references -->
But from experiences of other scientists[^gh-for-science-banks] [^gh-for-science-marcio] [^j-bryan] and the software industry, we can make some predictions.

- Using `GitHub Actions` you can automatically run code every time something on `GitHub` changes
  - You can publish pre-prints with every new version as a form of dynamic publishing
  - You can verify and test software with every new version and assess if newer versions break old functionality
  - You can have AI evaluate the code you want to publish and make suggestions on how to improve it
- Using `GitHub Issues` you can track future development of software or content you make
  - You can generate to-do lists for different members of your team
  - External users can submit bugs and issues they are having
  - You can request features for software that you like using
- Using `GitHub Pull Requests` you can conduct peer review
  - You can inspect only the changes made
  - You can track all comments and suggestions
- Using `devcontainers` you can have virtual workspaces that allow you to code from github regardless of your computer configuration
- Using `GitHub Discussions` you can collaborate within and outside your team in a long-form text format
- With your code publicly accessible, you can create increasingly useable software with collaborators all across the globe
- The amount of times you get cited increases with the amount of `GitHub` contributions you have

Overall, the quality of science improves by having everything accessible publicly.
This is a proven concept in the software world where open source is a huge driving force in high-quality software.


# Misconceptions, worries, and problems
This section attempts to address common arguments against using `GitHub`.
Depending on your level of adoption, familiarity with code, and other non-technical factors, you may have reservations about using `GitHub`.
If your concerns are not (fully) addressed in this section, we invite you to open an issue for this repository explaining it further, and we will try to expand this section.

## *My code is not good enough to be public*
If your code is good enough to draw scientific conclusions, then it is good enough to be published.
One might even argue that especially in that case it should be published.
Generally speaking, some crappy code is still better than no code at all.
Unlike editorial boards, your code does not need to meet certain quality standards.
There's plenty of undocumented code with mistakes that gets used all the time because it does what it needs to do.
In your case, the code should reproduce your results with the same data.
As long as it does that, it is perfect.
Any extras are just bonus.

## *People will point out mistakes in my code*
While that is true, it is not something to fear, but welcome.
Bugs in code can mean that incorrect conclusions are drawn.
The sooner they are caught, the better.
There might be a worry of having to make retractions in your research and that is indeed a very real risk.
Evidence[^fallibility] suggests however that self-retraction does not harm your reputation and actually can improve it within a science community.
Unlike retraction because of obscuring of facts, or in this case, code. 

## *Company X won't let me*
Companies might have some influence over the publishing of data, but most of the time they will not care about the tools used to process the data.
When using `GitHub`, it is primarily about the code and not the data on which that code works.
Even however if a company insists on not having the code be open, you can still use `GitHub`.
You can set the visibility of a code repository to **private** and still reap all the benefits for working on the code within your team.

## *It is too hard for me*
Without a doubt you will have to invest some time into learning the tools around `git` and `GitHub`.
Depending on your level of technical proficiency it might be easier or it might be more difficult.
Regardless, the investment is always worth it.
And in the modern technological landscape, there are many tools that make using `GitHub` easier.
Also, there is a great deal of resources online to learn `GitHub` in different ways, ranging from text and videos, to video games that teach you `git`. 

## *There is no time to learn*
The time you win by not having to re-invent software every few months, is much greater than the time you will have to invest into using the most basic parts of `GitHub`.
Just having a centralized place for code within your team alone and not having to share zipfiles through chats and e-mail alone will save you this time.
This is not taking into account the amount of time you can win by incrementally improving the software over many weeks, months, and years.

## *Nobody does it this way*
While indeed not many academic institutions are using such a model, increasingly more are.
Consider Stanford University that published open-source versions of Alpaca.
Additionally, if the desire is to remain working in the same traditional ways for the next 100 years, then that is a problem in itself.
Looking at the open-source community there is a lot of living proof that this model is highly effective in innovation and as a researcher you should at the very least give it a shot.

## *I have no time to maintain code*
Nobody is entitled to demand technical support for freely provided code: if the feedback is unhelpful, ignore it.

# How to get started
The best way to get started is to put some code on to github as fast as possible.
First, head on over to [UU Getting Started](https://github.com/UtrechtUniversity/getting-started) and follow the instructions to make an account, download GitHub Desktop, and join the UU organization.
Then pick some code you have recently used and put it on `GitHub`.
And that's it - you have officially started.

From this point onward, you can play around in the `GitHub` interface. Some resources to help you get started:
- [A brief explanation of the web interface](web-interface.md).
- [How to create and manage a team under the Utrecht University organization](managing-your-team.md)

# Resources

- [GitHub Desktop Documentation](https://docs.github.com/en/desktop)
- [Object Model](https://tom.preston-werner.com/2009/05/19/the-git-parable.html)
- [Git Game](https://ohmygit.org/)
- [Terminal Tutorial](https://docs.github.com/en/get-started/quickstart/set-up-git)
- [Walk-in Hours on Monday](https://www.uu.nl/en/research/research-data-management/walk-in-hours-workshops/walk-in-hours-research-data-software)

<!-- # Advanced Features
## Issues
## Projects
## Discussions
## Actions
## Branches
## Pull requests
## GitHub search -->

[^fallibility]: https://journals.sagepub.com/doi/pdf/10.1177/2515245918776632
[^gh-for-science-marcio]: https://marciovm.com/i-want-a-github-of-science
[^gh-for-science-banks]: https://marciovm.com/i-want-a-github-of-science
[^j-bryan]: https://peerj.com/preprints/3159v2/
