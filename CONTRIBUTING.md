Contributing to WISE
=======================

- [Contributing to WISE](#contributing-to-wise)
  - [Getting Involved](#getting-involved)
  - [Reporting Bugs](#reporting-bugs)
  - [Contributing Code](#contributing-code)
    - [Considerations for Accepting Patches](#considerations-for-accepting-patches)
    - [Setting up the Build System](#setting-up-the-build-system)
    - [Making Changes to WISE Source](#making-changes-to-wise-source)
  - [General](#general)
  - [Running the Tests](#running-the-tests)
  - [Improving Documentation](#improving-documentation)
    - [API documentation](#api-documentation)
  - [Code of Conduct](#code-of-conduct)
  - [Thank You](#thank-you)

## Getting Involved

Third-party patches are absolutely essential in our effort to create a bug-free modelling eƒleafngine.
However, they're not the only way to get involved with WISE development.
You can help the project tremendously by discovering and [reporting bugs](#reporting-bugs);
[improving documentation](#improving-documentation);
helping others on [Discord(WISE Community Support)](https://discord.com/channels/753976083053019216/754017869125386350),
[GitHub Discussions](https://github.com/PSaaS-Developers/Project_issues/discussions/11)
and [GitHub issues](https://github.com/PSaaS-Developers/Project_issues/issues);
and spreading the word about WISE among your colleagues and friends.

## Reporting Bugs

Before reporting a bug on the project's [issues page](https://github.com/PSaaS-Developers/Project_issues/issues),
using the [WISE Bug Reporting Template](https://github.com/PSaaS-Developers/Project_issues/issues/new?assignees=spydmobile&labels=bug%2Ctriage%2CW.I.S.E.&template=WISE_bug_report.yml&title=%5BWISE+Bug%5D%3A+)
first make sure that your issue is caused by WISE, not your application code
(e.g. passing incorrect arguments to methods, etc.).
Second, search the already reported issues for similar cases,
and if it's already reported, just add any additional details in the comments.

After you've made sure that you've found a new WISE bug,
here are some tips for creating a helpful report that will make fixing it much easier and quicker:

 * Write a **descriptive, specific title**. Bad: *Problem with patches*. Good: *Using a Landscape patch does not work*.
 * Include **browser, OS and WISE version** info in the description.
 * Create a **simple test case** that demonstrates the bug (Step-by-step point form process to reproduce the problem).
 * Indicate if the bug occurs in the Production version, Developer, or both.
 * *Bonus Nerd tip:* if the bug only appears in the Developer version but the Production version is fine,
   be a good nerd and use `git bisect` to find the exact commit that introduced the bug.

If you just want some help with your project,
try asking on [Discord(WISE Community Support)](https://discord.com/channels/753976083053019216/754017869125386350),
or [GitHub Discussions](https://github.com/PSaaS-Developers/Project_issues/discussions/11) instead.

## Contributing Code

### Considerations for Accepting Patches

While we happily accept patches, we're also committed to keeping WISE simple, lightweight and fast.
So bugfixes, performance optimizations and small improvements that don't add a lot of code
are much more likely to get accepted quickly.

Before sending a pull request with a new feature, check if it's been discussed before already
on [GitHub issues](https://github.com/PSaaS-Developers/Project_issues/issues);
and ask yourself two questions:

 1. Are you sure that this new feature is important enough to justify its presence in the WISE core?
    Or will it be better as a plugin/add-on in a separate repository?
 2. Is it written in a simple, concise way that doesn't add bulk to the codebase?

If your feature or API improvement did get merged in,
please consider submitting another pull request with the corresponding [documentation update](#improving-documentation).

### Setting up the Build System

The WISE build system is currently in flux so detailed instructions to set up the WISE build system, will be added here at a future date

### Making Changes to WISE Source

## General

If you're not yet familiar with the way GitHub works (forking, pull requests, etc.),
be sure to check out the awesome [article about forking](https://help.github.com/articles/fork-a-repo)
on the GitHub Help website &mdash; it will get you started quickly.

You should always write each batch of changes (feature, bugfix, etc.) in **its own topic branch**.
Please do not commit to the `main` branch of your fork — otherwise your unrelated changes will go into the same pull request.

You should also follow the code style and whitespace conventions of the original codebase.
In particular, use tabs for indentation and spaces for alignment.

WISE Specific Coding conventions and detailed instructions will be added here at a future date.

Also, please make sure that you have [line endings configured properly](https://help.github.com/articles/dealing-with-line-endings) in Git! Otherwise the diff will show that all lines of a file were changed even if you touched only one.

Happy coding!

## Running the Tests

To run the WISE tests detailed instructions will be added here at a future date.

## Improving Documentation


WISE Documentation will be housed in seperate repositry TBD at a future date

The easiest way to make little improvements such as fixing typos without even leaving the browser
is by editing one of the files with the online GitHub editor:
browse the Docs, choose a certain file for editing, click the Edit button, make changes and follow instructions from there.
Once it gets merged, the changes will immediately appear on the website & Documentaiton.

To work on the WISE documentation locally, detailed instructions will be added here at a future date.

### API documentation

The current(legacy) API Documentation is [here](https://wisedocs.intellifirenwt.com)
we are woking on new docs now.

## Code of Conduct

Everyone is invited to participate in the WISE community and related projects:
we want to create a welcoming and friendly environment.
Harassment of participants or other unethical and unprofessional behavior will not be tolerated in our spaces.
The [Contributor Covenant](CODE_OF_CONDUCT.md)
applies to all projects under the WISE organization.
Report any issues to spydmobile@gmail.com

## Thank You

Not only does your contribution to WISE and its community earn our gratitude, but it also makes you AWESOME.
Join [this approved list of awesome people](https://github.com/PSaaS-Developers/Project_issues/graphs/contributors)
and help us push the limits of what's possible with wildfire modelling!
