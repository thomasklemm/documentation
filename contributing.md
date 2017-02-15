## Contributing to Libraries.io :heart:
Thanks for considering contributing. These guidelines outline how to contribute to the [Libraries.io](http://github.com/librariesio) project. 

## Table of Contents
[What is Libraries.io all about?](#whats-librariesio-about)
[What should I know Beofre I get started?](#what-should-i-know-before-i-get-started)
* [Code of conduct](#code-of-conduct)
* [Langauge](#langauge)
* [Installation and setup](#setup)

[How can I contribute?](#how-can-i-contribute)
* [Reporting bugs](#reporting-bugs)
* [Suggesting enhancements](#suggesting-enhancements)
* [Suggesting a new feature](#suggesting-new-features)
* [Your first contribution](#your-first-contribution)
* [Tackling something meatier](#tackling-something-meatier)

[How can I talk to other contributors?](#how-can-i-talk-to-other-contributors)
* [Chat](#chat)
* [Video](#video)
* [Social media](#twitter)

[Our workflow](#workflow)


## What's Libraries.io About?
_Our goal is to raise the quality of all software._ 

By outlining our [mission and strategy](/strategy.md) we hope to give you more power to make decisions and determine how best to spend your time. Specifically we tackle three distinct problems:

* Discovery: _Helping developers make faster, more informed decisions about the software that they use._
* Maintainability: _Helping maintainers understand more about the software they depend upon and the consumers of their software._
* Sustainability: _Supporting undervalued software by highlighting shortfalls in contribution and funneling support to them._

## What Should I Know Before I Get Started?

### Code of Conduct
Libraries.io is an open and inclusive [community of people](/contributors.md) working together. We expect contributors to abide by our [contributor code of conduct](CODE_OF_CONDUCT.md) which basically say 'be excellent to each other'. Please report unacceptable behavior to conduct@libraries.io

### Langauge
We communicate predominately in English. Contributions to the project should be made with English as the first language. We are happy for members of the community to communicate in a language other than English in chat, email and video but be aware that this might be considered exclusive by other members of the community. 

### Setup 
If you wish to make contributions to Libraries.io then you'll need a local version of the site to test. You can find instructions to install the correct Ruby version, Postgres, and to set up the database in our [README](https://github.com/librariesio/libraries.io/blob/master/README.md#getting-started).

## How Can I Contribute? 

### Reporting Bugs

The simplest thing that you can do to help us is by filing good bug reports, so here we go:

#### Before Submitting a Bug Report

* Double-check that the bug is persistent. The site is still in it's infancy and sometimes artifacts may appear and disappear. 
* Double-check the bug hasn't already been reported [on our issue tracker](https://github.com/issues?utf8=%E2%9C%93&q=is%3Aopen+is%3Aissue+org%3Alibrariesio), they *should* be labelled `bug` or `bugsnag`.

If something hasn't been raised, you can go ahead and create a new issue using [the template](/ISSUE_TEMPLATE.md). If you'd like to help investigate further or fix the bug just mention it in your issue and check out our [workflow](#workflow).

### Suggesting Enhancements

The next simplest thing you can do to help us is by telling us how we can improve the features we already support, here we go:

#### Before Submitting an Enhancement

* Check that the enhancement is not already [in our issue tracker](https://github.com/issues?utf8=%E2%9C%93&q=is%3Aopen+is%3Aissue+org%3Alibrariesio), they should be labelled 'enhancement'.

If there isn't already an issue for feature then go ahead and create a new issue for it using the [template](/ISSUE_TEMPLATE.md). If you'd like to work on the enhancement then just mention it in a comment and check out our [workflow](#workflow).

### Suggesting New Features

If you're into this zone then you need to understand a little more about what we're trying to achieve:

#### Before Suggesting a Feature

* Check that it aligns with [our strategy](strategy.md) and is specifically not in line with something we have said we will not do (for the moment this is anything to do with ranking *people*).
* Check that the feature is not already [in our issue tracker](https://github.com/issues?utf8=%E2%9C%93&q=is%3Aopen+is%3Aissue+org%3Alibrariesio), they should be tagged 'feature'.
* Specifically check that it is not already a [funded commitment](https://github.com/librariesio/supporters/issues).

If you're still thinking about that killer feature that no one else is thinking about then *please* create an issue for it using the [template](/ISSUE_TEMPLATE.md).

### Your First Contribution
You're in luck! We label issues that are ideal for first time contributors with [`first-pr`](https://github.com/issues?utf8=%E2%9C%93&q=is%3Aopen+is%3Aissue+user%3Alibrariesio+label%3A%22first-pr%22). For someone who wants something a little more meaty you might find an issue that needs some assistance with [`help wanted`](https://github.com/issues?utf8=%E2%9C%93&q=is%3Aopen+is%3Aissue+user%3Alibrariesio+label%3A%22help+wanted%22). Next you'll want to read our [workflow](#workflow).

### Tackling Something Meatier

Tickets are labeled by size, skills required and to indicate workflow. Details can be found in our [labelling policy](/labelling.md). 

To get you started you might want to check out issues concerning [documentation](https://github.com/librariesio/documentation/issues/), [user experience](https://github.com/librariesio/libraries.io/labels/ux), [visual design](https://github.com/librariesio/libraries.io/issues/labels/visual%20design) or perhaps something already [awaiting help](https://github.com/librariesio/libraries.io/labels/help%20wanted). You may find the following useful:

* Our [strategy](/strategy.md) which outlines what our goals are, how we are going to achieve those goals and what we are specifically going to avoid.
* A [techncial overview](/techoverview.md) of the components that make up the Libraries.io project and run the [https://libraries.io](https://libraries.io) site.

## How Can I Talk To Other Contributors?

### Chat
We use [Slack](http://slack.io) for chat. There's an open invitation avaialble to anyone who wishes to join the conversation at [http://slack.libraries.io](http://slack.libraries.io).

We try to use the following channels accordingly:

* `#general` channel is used for general, water cooler-type conversation, contributor updates and issue discusion.
* `#events` is used to share and discuss events that may be of interest to or attended by members of the community
* `#activity` contains notifications from the various platforms that we use to keep the Libraries.io project turning. Including notifications from GitHub, Twitter and our servers. 

Members are encouraged to openly discuss their work, their lives, share views and ask for help using chat. It should be considered a *safe space* in which there is *no such thing as a stupid question*. Conversely no one contributor should ever be expected to have read something said in a chat. If someone should know something then it should be written down as an issue and/or documented in an obvious place for others to find.  

### Video
[Google Hangouts](http://hangouts.google.com) is our preferred tool for video chat. We operate an [open hangout](http://bit.ly/2kWtYak) for anyone to jump into at any time to discuss issues face to face. 

### Regular updates
Contributors are encouraged to share what they're working on. We do this through daily or weekly updates in the `#general` channel on Slack. Updates should take the format 'currently working on X, expecting to move onto Y, blocked on Z' where x, y and z are issues in our [issue tracker](https://github.com/issues?utf8=%E2%9C%93&q=is%3Aopen+is%3Aissue+org%3Alibrariesio). 

Additionally we host an [open hangout](http://bit.ly/2kWtYak) for any contributor to join at *5pm UTC on a Tuesday* to discuss their work, the next week's priorities and to ask questions of other contributors regarding any aspect of the project. Again this is considered a *safe space* in which *there is no such thing as a stupid question*.

### Mail
The [core team](https://github.com/orgs/librariesio/teams/core) operate a mailing list for project updates. If you'd like to subscribe you'll find a form in the footer on [Libraries.io](http://libraries.io). 

### Twitter
We have an account on Twitter at [@librariesio](http://twitter.com/librariesio). This is predominately used to retweet news, events and musings by contributors rather than as a direct method of communication. Contributors are encouraged to use @librariesio in a tweet when talking about the project, so that we may retweet if appropriate. The account is moderated and protected by the [core team](https://github.com/orgs/librariesio/teams/core). 

### Facebook
We have a Facebook page at [@libraries.io](https://www.facebook.com/libraries.io). Again this is predominantly used to gather and reflect news, events and musings by contributors rather than as a direct method of communication. Contributors are encouraged to reference Libraries.io in a post when talking about the project, so that we may reflect this if appropriate. Again the account is moderated and protected by the [core team](https://github.com/orgs/librariesio/teams/core). 

### Medium
We have a Medium account at [@librariesio](https://medium.com/@librariesio) and once again it is used to reflect news, events and musings by contributors rather than a direct method of communication. Contributors are encouraged to reference @librariesio in a post when talking about the project, so that we may recommend it if appropriate. Again the account is moderated and protected by the [core team](https://github.com/orgs/librariesio/teams/core). 

## Workflow
In general we use [GitHub](https://help.github.com/) and [Git](https://git-scm.com/docs/gittutorial) to support our workflow. If you are unfamiliar with those tools then you should check them out until you feel you have a basic understanding of GitHub and a working understanding of Git. Specifically you should understand how forking, branching, committing, PRing and merging works. 

#### Forking
We prefer that contributors fork the project in order to contribute.

#### Branching 
We *try* to use principles of [GitHub-flow](https://lucamezzalira.com/2014/03/10/git-flow-vs-github-flow/) in our branching model. That is the `master` branch will always be deployable to the live site, and that every branch from that will be used to add a feature, fix a bug, improve something or otherwise represent an atomic unit of work. 

#### Ticketing
We *try* to create an issue for everything. That is any bug, feature or enhancement that is worth an open, focussed and documented discussion. 

#### Labelling 
We constrain labels as they are a key part of our workflow. Tickets will be labeled according to our [labelling policy](/labelling.md).

#### Templates
We use templates to guide contributors toward good practice in [filing bugs, requesting enhancements and features](/ISSUE_TEMPLATE.md) and in [issuing pull-requests](PULL_REQUEST_TEMPLATE.md).

#### Commenting
If it possible to comment your contribution — for instance if you are contributing code — then do so in a way that is simple, clear, concise and lowers the level of understanding necessary for others to comprehend what comes afterward does or achieves. If you are contributing code it is very likely it will be rejected if it does not contain sufficient comments. 

#### Committing
When committing to a branch be sure to use plain, simple language that describes the incremental changes made on the branch toward the overall goal. Avoid unnecessary complexity. Simplify whenever possible. Assume a reasonable but not comprehensive knowledge of the tools, techniques and context of your work. 

#### Testing 
When adding or fixing functionality, tests should be added to help reduce future regressions and breakage. All tests are ran automatically when new commits are pushed to a branch. Pull requests with broken/missing tests are not likely to be merged.

#### Submitting for Review
Once a piece of work (in a branch) is complete it should be readied for review. This is your last chance to ensure that your contribution is [properly tested](#testing). If you are contributing code it is likely your contribution will be rejected if it would lower the test-coverage. Once this is done you can submit a pull-request following the [template](/PULL_REQUEST_TEMPLATE.md).

It is likely that your contributions will need to be checked by at least one member of the [core team](https://github.com/orgs/librariesio/teams/core) prior to merging. It is also incredibly likely that your contribution may need some re-work in order to be accepted. Particularly if it lacks an appropriate level of comments, tests or it is difficult to understand your commits. Please do not take offense if this is the case. We understand that contributors give their time because they want to improve the project but please understand it is another's responsibility to ensure that the project is maintainable, and good practices like these are key to ensuring that is possible. 

#### Reviewing a PR
We appreciate that it may be difficult to offer constructive criticism, but it is a necessary part of ensuring the project is maintainable and successful. If it is difficult to understand something, request it is better commented. If you do not feel assured of the robustness of a contribution, request it is better tested. If it is unclear what the goal of the piece of work is and how it relates to the [strategy](/strategy.md), request a clarification in the corresponding issue. If a pull-request has no corresponding issue, decreases code coverage or otherwise decreases the quality of the project. Reject it. Otherwise, merge it. 

#### Merging
As we keep the `master` branch in a permanent state of 'deployment ready' once-merged your contribution will be live on the next deployment. 
#### Deploying 
Any member of the [deployers](https://github.com/orgs/librariesio/teams/deployers) team are able to redeploy the site. If you require a deployment then you might find one of them in our `#general` [chat channel on Slack](slack.libraries.io). 
