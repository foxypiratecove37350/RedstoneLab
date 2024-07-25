# Contributing to RedstoneLab

Thanks for taking the time to contribute!

The following is a set of guidelines for contributing to RedstoneLab. These are mostly guidelines, not rules. Use your best judgment, and feel free to propose changes to this document in a pull request. These guidelines have been adapted from [Atom](https://github.com/atom/atom/blob/master/CONTRIBUTING.md).

#### Table Of Contents

* [Code of Conduct](#code-of-conduct)

* [What should I know before I get started?](#what-should-i-know-before-i-get-started)
    * [RedstoneLab Architecture](#redstonelab-architecture)

* [How Can I Contribute?](#how-can-i-contribute)
    * [Reporting Bugs](#reporting-bugs)
    * [Suggesting Enhancements](#suggesting-enhancements)
    * [Your First Code Contribution](#your-first-code-contribution)
    * [Pull Requests](#pull-requests)
    * [Translations](#translations)

* [Styleguides](#styleguides)
    * [Git Commit Messages](#git-commit-messages)
    * [Python Styleguide](#python-styleguide)

* [Additional Notes](#additional-notes)
    * [Issue Labels](#issue-labels)

## Code of Conduct

See our [`CODE_OF_CONDUCT.md`](./CODE_OF_CONDUCT.md) file for details.

## What should I know before I get started?

### RedstoneLab Architecture



## How Can I Contribute?

### Reporting Bugs

This section guides you through submitting a bug report for RedstoneLab. Following these guidelines helps maintainers and the community understand your report, reproduce the behavior, and find related reports.

Before creating bug reports, please check [this list](#before-submitting-a-bug-report) as you might find out that you don't need to create one. When you are creating a bug report, please [include as many details as possible](#how-do-i-submit-a-good-bug-report). Fill out [the required template](./.github/ISSUE_TEMPLATE/BUG-REPORT.yml), the information it asks for helps us resolve issues faster.

> **Note:** If you find a **Closed** issue that seems like it is the same thing that you're experiencing, open a new issue and include a link to the original issue in the body of your new one.

#### Before Submitting A Bug Report

* **Try repairing your installation.** This can often fix issues with corrupted data files.
* **Perform a [search](https://github.com/foxypiratecove37350/RedstoneLab/issues)** to see if the problem has already been reported. If it has **and the issue is still open**, add a :+1: to the existing issue instead of opening a new one.

#### How Do I Submit A (Good) Bug Report?

Bugs are tracked as [GitHub issues](https://guides.github.com/features/issues/). After you've determined this is a new bug using the steps from above, create an issue and provide the following information by filling in [the template](./.github/ISSUE_TEMPLATE/BUG-REPORT.yml).

Explain the problem and include additional details to help maintainers reproduce the problem:

* **Use a clear and descriptive title** for the issue to identify the problem.
* **Describe the exact steps which reproduce the problem** in as many details as possible. For example, start by explaining how you started RedstoneLab, and what actions were taken. When listing steps, **don't just say what you did, but explain how you did it**. For example, if you opened a menu, explain if you used the mouse, or a keyboard shortcut or something else entirely.
* **Provide specific examples to demonstrate the steps**. Include links to files or GitHub projects, or copy/pasteable snippets, which you use in those examples. If you're providing snippets in the issue, use [Markdown code blocks](https://help.github.com/articles/markdown-basics/#multiple-lines).
* **Describe the behavior you observed after following the steps** and point out what exactly is the problem with that behavior.
* **Explain which behavior you expected to see instead and why.**
* **Include screenshots and animated GIFs** which show you following the described steps and clearly demonstrate the problem.
* **If you're reporting that RedstoneLab crashed**, include a crash report. The crash reports are generated in the `crash/` directory and are named byt the date in [ISO 8601](https://en.wikipedia.org/wiki/ISO_8601) format. Include the crash report in the issue in a [code block](https://help.github.com/articles/markdown-basics/#multiple-lines), a [file attachment](https://help.github.com/articles/file-attachments-on-issues-and-pull-requests/), a [gist](https://gist.github.com/) (and provide link to that gist), or even a screenshot of the error.
* **If the problem wasn't triggered by a specific action**, describe what you were doing before the problem happened and share more information using the guidelines below.

Provide more context by answering these questions:

* **Did the problem start happening recently** (e.g. after updating to a new version of RedstoneLab) or was this always a problem?
* If the problem started happening recently, what's the version and release channel as well as the versions of RedstoneLab?
* **Can you reliably reproduce the issue?** If not, provide details about how often the problem happens and under which conditions it normally happens.

Include details about your configuration and environment:

* **What's the name and version of the OS you're using**? Ideally there are no cross-compatibility issues, but it does happen.

### Suggesting Enhancements

This section guides you through submitting an enhancement suggestion for RedstoneLab, including completely new features and minor improvements to existing functionality. Following these guidelines helps maintainers and the community understand your suggestion and find related suggestions.

Before creating enhancement suggestions, please check [this list](#before-submitting-an-enhancement-suggestion) as you might find out that you don't need to create one. When you are creating an enhancement suggestion, please [include as many details as possible](#how-do-i-submit-a-good-enhancement-suggestion). Fill in [the template](./.github/ISSUE_TEMPLATE/FEATURE-REQUEST.yml), including the steps that you imagine you would take if the feature you're requesting existed.

#### Before Submitting An Enhancement Suggestion

* **Check if there's already a plugin which provides that enhancement.**
* **Perform a [cursory search](https://guides.github.com/features/issues/)** to see if the enhancement has already been suggested. If it has, add a :+1: to the existing issue instead of opening a new one.

#### How Do I Submit A (Good) Enhancement Suggestion?

Enhancement suggestions are tracked as [GitHub issues](https://guides.github.com/features/issues/). After you've determined this is a new suggestion using the steps from above, create an issue and provide the following information:

* **Use a clear and descriptive title** for the issue to identify the suggestion.
* **Provide a step-by-step description of the suggested enhancement** in as many details as possible.
* **Provide specific examples to demonstrate the steps**. Include copy/pasteable snippets which you use in those examples, as [Markdown code blocks](https://help.github.com/articles/markdown-basics/#multiple-lines).
* **Describe the current behavior** and **explain which behavior you expected to see instead** and why.
* **Include screenshots and animated GIFs** which help you demonstrate the steps or point out the part of RedstoneLab which the suggestion is related to.
* **Explain why this enhancement would be useful** to most RedstoneLab users and isn't something that can or should be implemented as a plugin.

### Your First Code Contribution

Unsure where to begin contributing? You can start by looking through `help-wanted` issues or any issues labelled `can't reproduce`.

#### Local development

RedstoneLab can be developed and tested locally. First, clone the repository and run `pip install -r requirements.txt` to install the required modules. Then, to start the program you can run `python src/main.py`.

### Pull Requests

Please follow these steps to have your contribution considered by the maintainers:

1. Use a pull request template, if one exists.
2. Follow the [styleguides](#styleguides)
3. After you submit your pull request, verify that all [status checks](https://help.github.com/articles/about-status-checks/) are passing <details><summary>What if the status checks are failing?</summary>If a status check is failing, and you believe that the failure is unrelated to your change, please leave a comment on the pull request explaining why you believe the failure is unrelated. A maintainer will re-run the status check for you. If we conclude that the failure was a false positive, then we will open an issue to track that problem with our status check suite.</details>

While the prerequisites above must be satisfied prior to having your pull request reviewed, the reviewer(s) may ask you to complete additional design work, tests, or other changes before your pull request can be ultimately accepted.

### Translations

RedstoneLab is currently not translated, but it will accept translation soon.

## Styleguides

### Git Commit Messages

* Use the present or past tense ("Add feature" or "Added feature")
* Use the imperative mood ("Move cursor to..." not "Moves cursor to...")
* Limit the first line to 72 characters or less
* Reference issues and pull requests liberally after the first line
* When only changing documentation, include `[ci skip]` in the commit title

### Python Styleguide

All Python must adhere to the standard PEP rules.

Some other style related points not covered by PEP:

* Use verbose variable names
* Use `snake_case` for variable names
* Use `PascalCase` for class names
* Use `UPPER_SNAKE_CASE` for constants
* Use type hinting
* Avoid using `lambda`s

## Additional Notes

### Issue Labels

This section lists the labels we use to help us track and manage issues. Please open an issue if you have suggestions for new labels.

[GitHub search](https://help.github.com/articles/searching-issues/) makes it easy to use labels for finding groups of issues or pull requests you're interested in. For example, you might be interested in [bugs that have not been able to be reproduced](https://github.com/foxypiratecove37350/RedstoneLab/issues?q=is%3Aopen+label%3A%22can%27t+reproduce%22+label%3A%22bug%22). To help you find issues, each label is listed with search links for finding open items with that label. We encourage you to read about [other search filters](https://help.github.com/articles/searching-issues/) which will help you write more focused queries.

#### Type of Issue and Issue State

| Label name | Description | View All |
| --- | --- | --- |
| `awaiting response` | Waiting for a response from the user, issues with this tag are prone to pruning. | [View All](https://github.com/foxypiratecove37350/RedstoneLab/labels/bug) |
| `bug` | Issue related to a bug report, may or may not be yet confirmed. | [View All](https://github.com/foxypiratecove37350/RedstoneLab/labels/awaiting%20response) |
| `can't fix` | Issues which are invalid or are a limitation of something else like Electron. | [View All](https://github.com/foxypiratecove37350/RedstoneLab/labels/can%27t%20fix) |
| `can't reproduce` | Reported bugs that could not be confirmed, help welcome. | [View All](https://github.com/foxypiratecove37350/RedstoneLab/labels/can%27t%20reproduce) |
| `confirmed` | Confirmed bugs to be actively worked. | [View All](https://github.com/foxypiratecove37350/RedstoneLab/labels/confirmed) |
| `duplicate` | Issues which are duplicates of other issues, i.e. they have been reported before. | [View All](https://github.com/foxypiratecove37350/RedstoneLab/labels/duplicate) |
| `enhancement` | Feature or improvement suggestion. | [View All](https://github.com/foxypiratecove37350/RedstoneLab/labels/enhancement) |
| `help wanted` | Help from the community appreciated. | [View All](https://github.com/foxypiratecove37350/RedstoneLab/labels/help%20wanted) |
| `needs info` | Issue did not supply enough information to take action on. | [View All](https://github.com/foxypiratecove37350/RedstoneLab/labels/needs%20info) |
| `question` | Questions more than bug reports or feature requests (e.g. how do I do X). | [View All](https://github.com/foxypiratecove37350/RedstoneLab/labels/question) |
| `wontfix` | Decision has been made not to fix these issues at least for now. | [View All](https://github.com/foxypiratecove37350/RedstoneLab/labels/wontfix) |