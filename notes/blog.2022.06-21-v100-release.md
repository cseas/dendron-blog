---
id: 8jp5brp2m2arrps7a5w9fk9
title: Dendron v100
desc: ''
updated: 1655825494046
created: 1655678177671
image:
  url: https://ik.imagekit.io/fpjzhqpv1/pexels-malte-luk-1234390_dNRq0_ZwI.jpg?ik-sdk-version=javascript-1.4.3&updatedAt=1655678748917
  alt: "Celebrating Dendron's 100th release"
date: '2022-06-21'
excerpt: 'Celebrating 100 releases of Dendron'
author: 'Kevin S Lin'
published: true
---

> Dendron is launching on product hunt today. If Dendron has been of use to you, please leave feedback on our [launch page](https://www.producthunt.com/posts/dendron-v100) - this would help us out a lot! 🙏

![Celebrating Dendron's 100th release](https://ik.imagekit.io/fpjzhqpv1/pexels-malte-luk-1234390_dNRq0_ZwI.jpg?ik-sdk-version=javascript-1.4.3&updatedAt=1655678748917)

### Context
Two years ago, we launched Dendron because we believed there was a [better way of managing knowledge](https://www.kevinslin.com/notes/e1455752-b052-4212-ac6e-cc054659f2bb.html).

The problem - we are all drowning in information! Existing tools try to make it easy to get knowledge in but fail at getting that information back out when needed.

Dendron is a developer-focused, open-source, note-taking tool.  It combines the simplicity of markdown with the power of VSCode.  To manage information at scale, Dendron applies the insights we've learned from five decades of developer tooling and brings it to general knowledge. 

Since 2020, we've been iterating on this thesis with weekly releases to make Dendron better, faster and stronger! With the v100 release, we'll take a moment to go over some highlights.

### Better

In a well-designed system, easy things should be easy and hard things possible. 

This hasn't always been the case at Dendron and it's something we've put in a lot of effort addressing through improved documentation, feature work, and better defaults.

Besides creating a catalog of [[talks|dendron://dendron.dendron-site/community.events.greenhouse.2022-02-25-gtd-bullet-journals-task-management-workflow-demos]] and [[guides|dendron://dendron.dendron-site/dendron.guides.workflows]] of how Dendron is used in the wild, we've also kicked off a [[standardization effort|dendron://dendron.handbook/leaflet.journal.2022.05.10.standard-documentation]] across all our docs so that any feature, command, or config is just a [[lookup|dendron://dendron.dendron-site/dendron.topic.lookup]] away!

Feature wise, the following are some areas we've invested in to make common workflows easy:
- the [[Dendron Sidebar|dendron://dendron.dendron-site/dendron.topic.sidebar#summary]] provides one click access to most frequently used features like backlinks and the tree view
- the [[Import Obsidian Vault|dendron://dendron.dendron-site/dendron.ref.commands#import-obsidian-vault]] command provides a one click method for importing your notes
- the [[Help and Feedback|dendron://dendron.dendron-site/dendron.topic.sidebar.help-and-feedback]] panel provides a cheatsheet of useful resources and docs
- the [[Tip of the Day|dendron://dendron.dendron-site/dendron.topic.sidebar.tip-of-the-day]] panel highlights new features and enhancements

Finally, many of Dendron's core use cases now come with better defaults. For example, [[daily journals|dendron://dendron.dendron-site/dendron.topic.daily-journal-note]] and [[meeting notes|dendron://dendron.dendron-site/dendron.topic.special-notes#meeting-note]] have built-in [[templates|dendron://dendron.dendron-site/dendron.topic.templates]] that get created the first time these commands are invoked. 

### Faster

Life is too short to wait for your notes to load. 

Dendron has always been fast - much of this we get for free because your notes are just local plaintext files stored in your computer. 
Over the past year, we've optimized all the parts of Dendron's lifecycle, which include initialization, lookup, publishing, and autocomplete just to name a few. 

These changes resulted in orders of magnitude better performance across the board and <100ms of latency for the most common actions in Dendron   🚀 🚀 🚀

### Stronger

Our goal is to make Dendron an IDE for knowledge. 
Since 2020, we've released **over 600 features** to augment what you can do with plaintext.

Some highlights:
- [[Handlebar Templates|dendron://dendron.dendron-site/dendron.topic.templates.handlebars]] that allow augmentation of your templates with conditions, variables, and for loops
- [[Hovers|dendron://dendron.dendron-site/dendron.topic.workbench.contextual-ui]] over links and backlinks
- [[Note Traits|dendron://dendron.dendron-site/dendron.topic.traits]] that allow you to create notes with custom behavior
- [[Publishing using NextJS|dendron://dendron.dendron-site/dendron.topic.publish]] with selective publishing

For the full changelog of all features, see the [[release notes|dendron://dendron.dendron-site/changelog.release]]. 

### Conclusion

Prior to Dendron, I worked at Amazon for over half a decade. 
Something that stuck with me from my time there is that it's always [day one](https://aws.amazon.com/executive-insights/content/how-amazon-defines-and-operationalizes-a-day-1-culture/).

This is especially relevant when dealing with knowledge management today because how humans manage information in the age of the internet is fundamentally an unsolved problem.
With Dendron, we think we have something that works. 
Whether you are an individual managing a handful of notes or a team with tens of thousands of notes, Dendron helps you stay organized and on top of it all.

We've spent the past 100 releases iterating on our [[hierarchy first approach to note taking|dendron://dendron.blog/blog.2020.2020-08-24-a-hierarchy-first-approach-to-note-taking]] and we'll spend a few hundred more building on top of this foundation.  On behalf of the entire Dendron team, I would like to say thanks to everyone that helped make this happen - chiefly our wonderful community and our steadfast investors.  Here's to the next 100 releases!

Sincerely, <br/>
\- Kevin
