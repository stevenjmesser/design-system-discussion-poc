# What is this?

A proof-of-concept for using GitHub Discussions as the backend for comments on GOV.‌UK Design System backlog items.

![](/src/images/design-system-discussion-poc.gif)

## Why?

Many digital specialists across government, apart from developers, are uncomfortable with using GitHub as they believe it’s ‘not for them’. A significant percentage of GOV.UK Design System’s community don’t engage in discussions about components and patterns on GitHub, which is a problem this attempted to solve. This proof-of-concept was to show that it’s possible to design around that while still keeping existing comments and discussion stored on GitHub.

# Notes

This is a super hacky proof-of-concept that took me, like, 90 minutes on a Thursday morning. After sharing it with the team, a next step would have been taking it to users to test their reactions to the prototype.

One risk to have mitigated down the line was implementing this with a moderation policy. If this were implemented on any `.gov.uk` domain _without_ a moderation policy, SEO farms would add comments including links to their websites. It’d give them a lot of Google juice.

# Installation

1. Clone the repo using `https://github.com/stevenjmesser/design-system-discussion-poc.git`
2. Navigate to the `design-system-discussion-poc` folder in your terminal
3. Run `npm install`
4. Run `npm start`
5. Visit <http://localhost:3001> to view the proof-of-concept
