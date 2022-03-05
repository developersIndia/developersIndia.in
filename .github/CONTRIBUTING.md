# Contributing to the Community Website

Each & every project we build and/or maintain has been a possibility due to the community member efforts. Without which the projects would've been a distant dream only! As such, while we welcome all sorts of contributions to developing our community website, we ask the contributors to abide by certain rules & guidelines. These guidelines help us ensure:

1. Development practices are uniform.
2. Bug reports follow a standard procedure which makes it easier to debug & resolve certain issues quicker.
3. Submitting bug fixes, patches, feature requests through [Pull Requests (PRs)](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests)
4. The details & examples to share when proposing a new feature.

As such this current document lists down such guidelines in complete detail which every contributor should follow while contributing to the project.

Do note, the statements detailed in this document aren't set in stone & individual contributors are expected to use their best judgement when developing and/or contributing to the project. And if you feel, certain portions of this document could use a rephrasing? Please do not hesitate to report it to us & open a PR referencing it!

## Code of Conduct

First of, our community welcomes people from all sorts of areas & expertise with varying years of experience. As such we ask you to be civil when interacting with another community be it on GitHub or elsewhere.

To enforce a civil & mature engagement among community members we drafted the [Code of Conduct](https://github.com/developersIndia/.github/blob/main/CODE_OF_CONDUCT.md). If you find anyone breaking the T&Cs of the aforementioned document please report us about the incident on over our email - contact.developersindia@gmail.com.

## Too Long, Didn't Read, But I've a Question

> **Note:** [Please don't file an issue to ask a question.](https://blog.atom.io/2016/04/19/managing-the-deluge-of-atom-issues.html) You'll get faster results by using the resources below.

- Check the [Issue](https://github.com/developersIndia/website/issues)/[Discussion](https://github.com/developersIndia/website/discussions) threads to see if your query already exists or not!
- If it's a quick short answer which you believe one of the admin/maintainers can respond to real quick, our DMs are open to you.
- Join our [Discord server](https://discord.gg/b4YYdyYBGH) & have a great chat there! (**Don't forget to read the rules & guidelines there as well!**)

## How to Contribute to the Project

### Report bugs using Github's issue tracker

We use GitHub issues to track public bugs, weird features, broken URLs & such. More specifically, any thing out of the ordinary which shouldn't really exist in a website is tracked on our bug tracker.

You can report a bug by [opening a new issue](https://github.com/developersIndia/website/issues/new/choose), it's that easy! But before reporting an issue, please put in some effort & identify if similar reports have already been created by a previous individual.

> **Note:** If you find a **Closed** issue that seems like it is the same thing that you're experiencing, open a new issue and include a link to the original issue in the body of your new one.

### Before Submitting a Bug Report

- Check if the content is being delivered to your browser. Sometimes a quick Hard Refresh(**Shift + Ctrl + R**) might resolve the issue.
- Determine if such a bug report has already been reported earlier or not.
- Take a screenshot of the bug if possible & take note of the Browser details.

### How to Submit a Good Bug Report

**Great Bug Reports** tend to have:

- **Use a clear & descriptive title** to identify the issue & for obvious SEO reasons.
- **Describe the exact steps which reproduce the problem** in as many details as possible.
- **Provide specific examples to demonstrate the steps**. Include links to files or GitHub projects, or copy/pasteable snippets, which you use in those examples. If you're providing snippets in the issue, use [Markdown code blocks](https://www.markdownguide.org/basic-syntax/#code).
- **Describe the behaviour you observed after following the steps** and point out what exactly is the problem with that behaviour.
- **Explain which behaviour you expected to see instead and why.**
- **Include screenshots and animated GIFs** which show you following the described steps and clearly demonstrate the problem. If you use the keyboard while following the steps, **record the GIF with this tool**: [ShareX](https://getsharex.com/).
- **If the problem wasn't triggered by a specific action**, describe what you were doing before the problem happened and share more information using the guidelines below.

Project maintainers & authors _love_ thorough bug reports!

### Suggesting Enhancements

All projects maintained under the [developersIndia](https://github.com/developersIndia) banner are FOSS & as such welcomes public opinion on features & enhancements! And this section of the document will help you understand how to draft a detailed enhancement suggestion. Following these guidelines helps maintainers and the community understand your suggestion :pencil: and find related suggestions :mag_right:.

Before creating enhancement suggestions, please check
[this list](#before-submitting-an-enhancement-suggestion) as you might find out
that you don't need to create one. When you are creating an enhancement
suggestion, please
[include as many details as possible](#how-do-i-submit-a-good-enhancement-suggestion).
Fill in [the template](https://github.com/developersIndia/website/issues/new?assignees=Jarmos-san%2CBhupesh-V&labels=enhancement&template=feature_request.yml&title=%5BFEATURE+REQUEST%5D%3A+), including the steps
that you imagine you would take if the feature you're requesting existed.

#### Before Submitting An Enhancement Suggestion

- **Discuss about it** by openning a [Discussion thread](https://github.com/developersIndia/website/discussions).
- **Check if there's already [an open issue](https://github.com/developersIndia/website/issues) which provides that enhancement.**
- **Perform a [cursory search](https://github.com/developersIndia/website/issues?q=is%3Aopen+is%3Aissue+label%3Aenhancement)** to see if the enhancement has already been suggested. If it has, add a comment to the existing issue instead of opening a new one.

### Your First Code Contribution

Unsure where to begin contributing to the project? You can start by looking through these `good-first-issues` and `help-wanted` issues:

- [Good First Issues](https://github.com/developersIndia/website/issues?q=is%3Aopen+is%3Aissue+label%3A%22good+first+issue%22) - issues which should only require a few lines of code, and a test or two.
- [Help Wanted Issues](https://github.com/developersIndia/website/issues?q=is%3Aopen+is%3Aissue+label%3A%22help+wanted%22) - issues which should be a bit more involved than `good-first-issues` issues.

Both issue lists are sorted by the total number of comments. While not perfect, the number of comments is a reasonable proxy for an impact a given change will have.

#### Local development

Before you can write your first ever contribution to the project, you need to have a development environment setup locally on your machine. As such this current section will document the steps & procedure you'll need to take for setting up the development environment.

**Prerequisite Tools Necessary for Local Development**:

You need to have a [Node.js](https://nodejs.org) installed which should also come pre-packaged with the `npm` CLI tool. It'll help you manage & install other development & runtime dependencies required for the project.

Along side Node.js, you would also need `git` which we use for version-control.

Once installed you can verify if the software are working properly or not by invoking the following commands;

```shell
# Verify the Node.js version installed on your system
node --version

# Verify npm works as expected
npm --version

# Verify git exists & works as expected
git --version
```

With the necessary prerequisite tools installed & verified, you should now fork the project. if you've never forked a GitHub project before, check the [official GitHub docs](https://docs.github.com/en/get-started/quickstart/fork-a-repo) or refer to [this YouTube video](https://youtu.be/f5grYMXbAV0).

**Downloading Dependencies**:

Once you've access to a fork of the project on your GitHub profile, you're free to update and/or change anything you wish to do! But if you would like to add the changes or enhancements to the original website, you need [to make a Pull Request](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request). This section of the document will help you do exactly that, hence follow the steps below:

- Clone your forked version of the project to your local machine by running:

  ```shell
  git clone git@github:<YOUR-USERNAME>/website
  ```

- Change working into the freshly cloned project:

  ```shell
  cd website
  ```

- Install dependencies (including the development dependencies).

  ```shell
  npm install
  ```

**Organizing the React Components for the Project**:

Next.js is opinionated about structuring the project files, as such it expects all React Components used in a project to be place inside a `src/components` directory.While it helps having a standard practice to be enforced by the framework itself, dumping all arbitrary components in one single place can clutter the project's source code. We would like to avoid such clutter & redundancy whereever possible.

On that note, each & every component of the project should be structured in the following manner:

1. Each functional aspects of the website will be it's own directory & the directory names should be in lowercase. For example, `forms`, `layout`, `navigation` & so on. That way the directories will give a general idea of what it's contents are for.
2. Keep aptly named sub-directories under the general top-level directories as mentioned above. For example, there can be a `newsletter` & `signup` sub-directories under the `forms` top-level directory.
3. The React Components has to be written in TypeScriptReact (i.e files with `.tsx` extensions) & not in pure JavaScript/JavaScriptReact (i.e `.js`/`.jsx` files). And the same components should be named in a [CamelCase](https://en.wikipedia.org/wiki/Camel_case) format. Here's an example React Component: `NavBar.tsx`.
4. Modules which are necessary to style or test a component like `NavBar.styles.ts`, `NavBar.stories.ts`, `NavBar.test.ts` should be clumped alongside it's component i.e `NavBar.tsx`.
5. To further clump functional components into it's own directory, the component, it's CSS modules, Storybook & testing files will be stored under it's own specific directory. So, all `NavBar.*`-related files will be under the `NavBar` directory.

On that note, this is what the typical `components` directory will look like if the above standard practice is followed:

```shell
.
└── /src
    └── /components
        ├── /forms
        │   ├── /TextField
        │   │   ├── TextField.tsx
        │   │   ├── TextField.styles.ts
        │   │   ├── TextField.test.ts
        │   │   └── TextField.stories.ts
        │   ├── /Select
        │   │   ├── Select.tsx
        │   │   ├── Select.styles.ts
        │   │   ├── Select.test.ts
        │   │   └── Select.stories.ts
        │   └── index.ts
        ├── /routing
        │   └── /PrivateRoute
        │       ├── /PrivateRoute.tsx
        │       └── /PrivateRoute.test.ts
        └── /layout
            └── /navigation
                └── /NavBar
                    ├── NavBar.tsx
                    ├── NavBar.styles.ts
                    ├── NavBar.test.ts
                    └── NavBar.stories.ts
```

The following resouces were used as a source of inspiration to develop the standard:

- [React Architecture: How to Structure and Organize a React Application](https://www.taniarascia.com/react-architecture-directory-structure/)
- [How I set up a Next.js project structure](https://flaviocopes.com/nextjs-project-structure/)

So, feel free to take a look at the resources above to gain more insights into structuring React Components for a typical Next.js project.

On that note, if you feel there's something missing or perhaps the standard requires a bit more refinement then please don't hesitate  to open an issue/discussion thread.

**Local Development & Pushing the Changes to `upstream`**:

Once you've downloaded the dependencies, you're ready to make the first changes/fixes for bug reports. So, go ahead & let your imaginations go wild!

But before that, we would like you to follow some standard guidelines for developing the project locally as well. And as such, the following section of the document will help you get an idea of things to keep in mind while developing the project locally;

- The project uses Next.js so in case you're confused about certain things in the source code, please refer to the official [Next.js docs](https://nextjs.org/docs).
- In addition to the [React.js](https://reactjs.org) framework, the project also used [TypeScript](https://www.typescriptlang.org) to ensure common JavaScript errors & bugs aren't introduced into production. So, if you need a reference to that as well, feel free to refer to the official [TypeScript docs](https://www.typescriptlang.org/docs).
- No two developers will have common preferences & as such it raises debates & arguments on who's right more often than not! For example, some prefer single quotes `' '` over double quotes `" "`, or `Spaces` over `Tabs` & such. A source code having a mix of both can be quite detrimental to the project's development & introduce hidden errors which are hard to identify & debug. As such we've configured [ESLint](https://eslint.org) & [Prettier](https://prettier.io) to deal with such inconsistencies before production code is deployed.
- Executing our configured linters & formatters each time after developing the project can become monotonous & boring. Hence, to automate this procedure we decided to make use of [githooks](https://git-scm.com/docs/githooks). So, each time you either commit or push changes to a remote repository, `git` will invoke ESLint & Prettier for you!
- Since the project is version-controlled-ed using `git`, we also follow the principles of [GitHub Glow](https://docs.github.com/en/get-started/quickstart/github-flow). So, whenever you want to work a specific feature/bug, create a branch from `master`. Once work on the feature/bug branch is complete, merge it into the `master` branch before sending a PR.

The aforementioned points were some things-to-be-noted before you started contributing to the project. A majority of the times you needn't worry about them since we've them configured to ensure each & every contributor to the project has an uniform development experience.

But there are things which we don't have control over & as such we can only recommend you follow our suggestions on these regards. If you do follow them, you can rest assured, your PR will be reviewed on a priority basis & we'll enjoy doing it as well. That said, following are some suggestions we recommend keeping in mind while writing actual code for the project:

1. Remember, code is always written for another human being to be read. So, ensure the source code is [self-documenting](https://en.wikipedia.org/wiki/Self-documenting_code).
2. Place proper comments wherever necessary. Some examples where you should definitely place comments are, complicated logic and/or blocks of code which requires further attention.
3. Name variables verbosely. For example, be comprehensive like `event` instead of `e`.
4. If you need a refresher on writing good, human-readable code, refer to the [Google Styleguide for TypeScript](https://google.github.io/styleguide/tsguide.html).
5. Although not enforceable, we would also prefer it if you could name you `git` branches aptly. Here are some naming conventions you could use: `feature/issue-##` or `bug-fix/issue-##`. In doing so, at first glance it's more obvious than not, the said branch is related to a "_feature_" which has been detailed in "_issue-##_" where `##` is a number.

So, with that concludes the section on "_How to contribute to the project?_". If you feel the section lacks something, please open an [Issue](https://github.com/developersIndia/website/issues/new/choose)/[Discussion](https://github.com/developersIndia/website/discussions) thread along with a referenced PR with the changes & updates.

## Managing Version Release for the Project

Versioning a software project isn't standard practice for no reason. It helps manage development goals in both, the long run & the short run. And if anything goes south because of a bug or a breaking change, we can revert to the previous working version of the project with much ease! Therefore versioning the project is a necessity.

And this section of the document details how we manage the version for the project. Do note, backward compatibility isn't a requirement for web-based projects such as this one, hence `SemVer` does not apply here. We did come up with a more viable option for versioning the project. But keep in mind, anything written here isn't set in stone. So, if you have got a better version management idea, then please feel free to share it with us.

That said, let's dive in to the intricate details of how we manage the project's versions.

### How Often Do We Release a New Version

The nature of the project makes it difficult to maintain a fixed release schedule, hence, it's suggested to instead release a new version (_or tag_) when there are "_important feature updates_" to the project. The said "_important feature updates_" could be say;

1. Developing the Hero section of the landing page.
2. Adding a "_info_" section with information about the community.
3. A new "_About Us_" tab in the navigation bar

....and so on.

Breaking down the [end goal (_figma template_)](https://www.figma.com/file/jxpIq8GzilqzgyLpFBySP2/Developers-India-%3C3?node-id=5%3A58734) into smaller components which should be developed individually will help manage public contributions more easily!

So, upon completion of each component, it would be advisable to perform a release. More about how each releases should be versioned & the procedure for releasing is detailed in the next few sections.

### How Do We Version the Project

Taking quite a lot of inspiration from [this comment](https://github.com/developersIndia/website/discussions/69#discussioncomment-2130963) & the parent thread, we follow a "**Year-Month**" versioning system instead.

For more context, assuming the Hero section of the landing page was complete & a release could be made on the month of February & in the year 2022, then a tag aptly named `v2022-02` could be released.

### What Procedure Should be Followed to Release a Version

Before releasing a new version of the project, certain assumptions has to be made, checked & verified. In case some of those checklist items are missing or are out-of-place, please report it to the maintainers of the project beforehand.

That said, following are the assumptions that has to checked each time before making a release:

1. Version numbers has been checked & updated as per the rules stated above in the "_Versioning Rules_" section. Also don't forget to the update the version entry in the `package.json` file of the project as well!
2. Make an entry in a `CHANGELOG.md` file with the specific details of what's changed & in which version was the change introduced.
3. All tests, linters, formatter & URL health checks pass both locally & in the CI/CD pipeline.
4. Release specific milestones has been updated on GitHub, completed & cleared upon tagging a commit.

Once the aforementioned steps has been taken care of it's now suggested to tag a new version using the [`git-tag`](https://git-scm.com/docs/git-tag) command. Once tagged, push the changes to the remote repository to GitHub & [perform a release](https://docs.github.com/en/repositories/releasing-projects-on-github/managing-releases-in-a-repository).

Do note, the contents shared above in this section documented the immediate short-term goals of the project. For a more broad long-term goal, refer to the [ROADMAP](../ROADMAP.md) to get an idea of our "_future_", "_next_" & "_current_" goals.

## Licensing Terms & Conditions

We welcome all sorts of contributions to the project, be it triaging issues, reporting bugs & breaking changes and/or even taking up maintenance responsibilities. And all contributions to the project are performed under a voluntary basis for the developersIndia community.

As such to protect the interests of the contributors of the project, we're distributing the project under the MIT License. To read & learn about the terms & conditions (T&Cs) of the license, please check the [LICENSE](../LICENSE) document.

That said, all contributions to the project will be distributed under the T&Cs of the MIT License as well. We also assume, by contributing to the project, you're then accepting the T&Cs of the open-source license we distribute our project under.

If you feel there's something missing and/or the T&Cs are too restricted (or otherwise) please report it to us & open a PR explaining your reasoning. We'll gladly welcome your PR as long as the changes to the T&Cs are justifiable enough.

## Triaging Issue/Discussion/Pull Requests

We maintain the project in this repository on a voluntary basis outside work hours. As such, we appreciate each & every helping hands our contributors provide us. One task we desparately need help with is triaging issues, discussions & PRs. And believe it or not, this is one task which is extremely appreciated by the maintainers, so if you can contribute responding and/or triaging it be a massive help for us!

That said, if you would like to contribute to the project by...

1. Triaging through issues & helping the maintainers identify the type of issue/PRs.
2. Respond to contributors with their queries & discussions.
3. Marking bad PRs as spam and/or duplicate issue threads as `duplicate`.

...then this section of the document will guide you through.

That said, we track:

- Bugs, feature requests & such through [Issue threads](https://github.com/developersIndia/website/issues).
- Discussions on breaking changes, enhancements & feature requests through [Discussion threads](https://github.com/developersIndia/website/discussions).
- And source code updates and/or changes through [Pull Requests](https://github.com/developersIndia/website/pulls).

Issue threads & PRs are categorized with the following labels:

| Issue Labels       | Desciption                                                                   |
| ------------------ | ---------------------------------------------------------------------------- |
| `bug`              | Something isn't working                                                      |
| `dependencies`     | Pull requests that update a dependency file                                  |
| `documentation`    | Improvements or additions to documentation                                   |
| `duplicate`        | This issue or pull request already exists                                    |
| `enhancement`      | New feature or request                                                       |
| `good first issue` | Good for newcomers                                                           |
| `help wanted`      | Extra attention is needed                                                    |
| `invalid`          | This doesn't seem right                                                      |
| `question`         | Further information is requested                                             |
| `wontfix`          | This will not be worked on                                                   |

More such labels will be added & updated as & when required.

You can triage through specific categories of issue threads or PRs if that's what you're looking for. For example, if you're a first-time contributor to the project, you could look into issue threads labeled with [`good first issue`](https://github.com/developersIndia/website/labels/good%20first%20issue) or [`help wanted`](https://github.com/developersIndia/website/labels/help%20wanted).

**NOTE**: If you notice we missed adding someone (which could include you as well) to [the list of contributors](https://github.com/developersIndia/website#-contributors), please add a comment on the lines of;

```text
<!-- remove the square brackets and choose appropriate words -->
@all-contributors please add @user for [code, design, bug, infra, doc, tool, ideas]
```

Additionally, please take a look the [All Contributors docs](https://allcontributors.org/docs/en/overview) for further information on how to use it.

## Git Commit Messages Style Guide

When your contributions to the project are ready & you're comfortable committing the changes, you need to pass an apt message to the `git commit` command. And this section of the document will guide you through on writing good & proper `git commit` messages.

As mentioned earlier, code should be self-documenting, we believe the same principle should apply to `git commit` messages as well. While perusing through version control history, a second person should be able to quickly grasp what that specific commit contains after reading it's message.

For more information on the `git commit` command, we recommend going through it's official documentations. You can find it at: [git-commit](https://git-scm.com/docs/git-commit).

That said, following is an example of a good `git-commit` message;

```shell
feat: send an email to the customer when a product is shipped
```

To ensure all contributors follow that standard, we use [`commitlint`](https://github.com/conventional-changelog/commitlint) to enforce it.

Additionally, you can give the following articles a thorough read to have a better idea on writing good commit messages;

- ["_How to Write a Git Commit Message_"](https://cbea.ms/git-commit)
- [_"Write Better Git Commit Messages To Increase Your Productivity"_](https://betterprogramming.pub/write-better-git-commit-messages-to-increase-your-productivity-89fa773e8375)

## References

The contributing guidelines detailed in this document pertains only to this one specific project which is hosted in this repository. More specifically, all the guidelines detailed in the document are only applicable towards development and/or maintenance of the [developersIndia website](https://github.com/developersIndia/website).

If you would like to read more about our community guidelines, please find them on the following resources:

- [r/developersIndia | Reddit](https://www.reddit.com/r/rdevelopersIndia)
- [developersIndia | Discord](https://discord.gg/b4YYdyYBGH)
- [developersIndia | GitHub](https://github.com/developersIndia/.github/blob/main/CODE_OF_CONDUCT.md)

_**HAPPY CONTRIBUTING!**_ 😄
