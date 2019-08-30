# Welcome to Jomnius Continuous Learning Study Notes

```
The secret of getting ahead
is getting started.

-- Mark Twain
```

I read somewhere how this (non-student) person was studying 15-30 minutes a day, about 5 times a week. She didn't have detailed long-term plans, just general idea for the next few weeks. When you start reading something and check references or additional info, you're suddenly on a completely different path.

TODO: Insert [link](https://google.com) when I find it again.

So I decided to try similar system. Here are some notes for some of the bigger, more concentrated, studies I've done. Missing the daily quick blog reads or manual checks.

Now experimenting with the online format, my real study notes are in a physical big black notebook (using real paper and real pen). Most of my notes are just titles and subtitles from original article or video, exact quotes of important text and also source code, there is no point copying it here, too.

The value of physically writing things down is to make it easier for me to remember something afterwards. I'm not planning to read them ever afterwards - however I have checked my notes a few times, mainly to find out which of the many similar articles did I actually read.

Now I'm thinking that I could put here tags and summary, maybe the key discovery or why I read the thing in the first place. That would be kind of meta notes of study notes.

...work in progress, just thinking aloud. Btw direct link to this as a webpage https://jomnius.github.io/study-notes

## Inspiration
My most common sources for non-work related study inspiration are:
- [iOS Dev Weekly](https://iosdevweekly.com) by Dave Verwer. Delightful collection of the best in mobile development this week (Friday). If you check anything, this is the one!
- [Ray Wenderlich](https://www.raywenderlich.com), massive site for all mobile development related training. Videos, articles, books, podcasts. High quality material.
- [Daily Medium Digest](https://medium.com), personalized for me based on... something. There is some criticism against Medium, but it does have lots of quality diverse content. What I like most is that it proposes me articles outside of my main areas of interest, probably because it doesn't know me as well as it would like to. Which is just fine.
- [iOS Goodies](ios-goodies.com), interesting weekly list of links.

Overall, these sources are overlapping more or less.

## Disclaimer
- I have a personal, paid by myself, auto-renewing annual account to [RayWenderlich](https://www.raywenderlich.com). Therefore some of the links might point to non-free content. But since this is **my study notes**, I do have access.
- Btw you can always use "New Private Window" with Safari browser.

---

## 2019 August

### [I test in prod](https://increment.com/testing/i-test-in-production/)
Charity Majors August 2019
- Management, testing, development

Brilliant article about why we need to test in production. This is a conference quality speech, top of the class.

```
Could we have ironed out all the bugs before running it in prod? No.
You can never, ever guarantee that you have ironed out all the bugs.
```

Covers technical, cultural and managerial aspects about the bigger picture of testing (also) in production.

### [Why software projects take longer than you think – a statistical model](https://erikbern.com/2019/04/15/why-software-projects-take-longer-than-you-think-a-statistical-model.html)
Erik Bernhardsson 15 April 2019
- statistics, development, estimations

Some math about why estimations are (always) wrong. To simplify a lot, it looks like 80-20 rule: 80% of estimations are right, but the rest 20% can seriously mess up everything.

Or like Erik wrote here:

```
Tasks with the most uncertainty (rather the biggest size) can
often dominate the mean time it takes to complete all tasks.

The mean time to complete a task we know nothing about is
actually infinite.
```

### [Things You Should Never Do, Part I](https://www.joelonsoftware.com/2000/04/06/things-you-should-never-do-part-i/)
Joel Spolsky 6 April 2000
- Development, management

Refactoring (yes) vs rewriting (never). Classic.

### [The five types of communication problems that destroy company morale](https://qz.com/work/1587170/the-five-types-of-communication-problems-that-destroy-company-morale/)
Cate Huston 4 April 2019
- Communication

I've seen all these happen in real life, for better of worse. Cate has good and clear examples, you better read them by yourself. Here's just the subtitles as a reminder:

- Lack of depth
- Conflicting context
- Missing empathy
- Communication that triggers anxiety
- Assuming unearned trust

### [4 Simple Tips To Promote Continuous Learning At Work](https://medium.com/manager-mint/4-simple-tips-to-promote-continuous-learning-at-work-e0a4813b83d9)
Rohia Munavar 10 May 2019
- Learning, management

Really good article, so I'll just copy the titles!

Challenges:
- Time management
- Lack of relevance
- Fear of change
- Bad communication
- Fear of losing control

Possibilities:
- Make learning easily accessible
- Integrate learning with business goals
- The feedback culture
- Reward and recognize

### [MVC without the C: What will SwiftUI change in app architecture?](https://blog.thefuntasty.com/mvc-without-the-c-what-will-swiftui-change-in-app-architecture-c9ce3f49d256)
Matěj Kašpar Jirásek 22 Jul 2019
- swiftUI, architecture

Speculation about SwiftUI having no controller, but state: what does this mean for future (mobile, iOS, macOS) app development?

Possibly uni-directional data flow, immutable app state, massive state (instead of massive view controller), maybe new architectures inspired by web like [ELM](https://guide.elm-lang.org/architecture/), [Redux](https://redux.js.org) or [Flux](https://facebook.github.io/flux/) in swift. Things are getting exciting!

### [How do you recognize a 10x team?](https://medium.com/metrify/how-do-you-recognize-a-10x-team-294d0e15a757)
Osma Ahvenlampi 15 Jul 2019
- development, teamwork

Inspired by the infamous "10x developer", what qualities might a true **"10x team"** have: small, focused, balance, autonomous, welcome diversity, support each others, teach, learn, trust, innovate.

Some of those things can be achieved only with management support, no matter what kind of people are in the team.

### [The Flawed Reasoning Behind the Replication Crisis](http://nautil.us/issue/74/networks/the-flawed-reasoning-behind-the-replication-crisis)
Aubrey Clayton 1 Aug 2019
- analytics, statistics

Interesting article about problems of **statistical analysis**, especially about getting different results when replicating tests, vs. **Bayesian inference**.

You hear "statistically significant" a lot with A/B testing. This might explain some curious test results.

### [The Art of Communication](https://medium.com/swlh/the-art-of-communication-5faf111a89d)
Jordan Fraser 12 Aug 2019
- communication

Intro to transactional analysis in communication: parent (experience), adult (reason), child (emotion) - match with a complimentary style.

### [How to Maintain Transparency in Your Business at Different Levels](https://medium.com/swlh/how-to-maintain-transparency-in-your-business-at-different-levels-125da17097a)
Shane Barker 13 Aug 2019
- business, management

Transparency and communication are part of a good working environment. But it all starts from the top.

Some good ideas here, with comments. Mixed feelings about open office, though. For me, semi-open offices have worked best.

### [A Smarter Way Move Forward When You’re Stuck](https://medium.com/swlh/how-to-move-forward-when-youre-stuck-21d10c7fa90a)
Shannon Hennig 12 AUg 2019
- productivity

Always remember the basics:  take time to breathe, evaluate your options, keep moving forward.

### [Functional Programming? Don’t Even Bother, It’s a Silly Toy](https://medium.com/better-programming/fp-toy-7f52ea0a947e)
Ilya Suzdalnitski 29 Jul 2019
- technology, humour

Looking at functional programming from seriously large and complex enterprise software point of view. Or vice versa.

Comes with a disclaimer, just in case.

### [The Differences Between a Junior, Mid-Level, and Senior Developer](https://medium.com/better-programming/the-differences-between-a-junior-mid-level-and-senior-developer-bb2cb2eb000d)
Daan 2 Aug 2019
- engineering, technology

I've seen over the years a lot of brilliant developers write most complicated code and I keep asking: why! Since this article has (currently) "12.8K claps", I guess I'm not the only one wondering about this kind of things.

```
“Any fool can write code that a computer can understand.
Good programmers write code that humans can understand.”
--Martin Fowler
```

### [UITable​View​Header​Footer​View](https://nshipster.com/uitableviewheaderfooterview/)
Mattt 8 APr 2019
- swift, UI

Just realized I haven't linked to **[NSHipster](https://nshipster.com/)** yet, even thought it's one of my favorite reference websites. I even bought the first book (long time ago)!

This article is a clear and helpful discussion about UITableView section headers. Not table header, which I was looking for, but section headers. So rewrote that code, too!

### [How to Kill a To-Do List](https://medium.com/swlh/how-to-kill-a-to-do-list-89fbeb710a09)
L Kingsleigh 6 Aug 2019
- todo

Free-flowing short story about going from todo lists to done list. Worth reading, makes you think.

### [6 books every designer should read](https://uxdesign.cc/6-books-every-designer-should-read-524888647c43)
Ryan Gonzales 30 Jul 2019
- books, design

Interesting list of books, not the ones you see everywhere (yet). I firmly believe that everyone is a designer: some professionally, but all of us at least in small everyday things in our own lives.

Also if you commute, grab a book. Read a book. Listen to a book. Reflect on books.

### [The Many Offline Options for iOS Apps](https://medium.com/device-blogs/the-many-offline-options-for-ios-apps-2922c9b3bff3)
Peter Livesey 9 Jan 2019
- offline, cache, database, event bus

Thorough article about pros and cons of some offline strategies, considering both download and upload use cases.

### [Getting Started With the Combine Framework in Swift](https://medium.com/better-programming/getting-started-with-the-combine-framework-in-swift-36fe4ff6e568)
Antoine van der lee 25 Jun 2019
- Swift, Combine, RxSwift, MVVM

Introduction with small code samples to Apple's new [Combine framework](https://developer.apple.com/documentation/combine), comparing it to **RxSwift** terms.

### [Making a Real World Application With SwiftUI](https://medium.com/better-programming/making-a-real-world-application-with-swiftui-54e71d9e6042)
Thomas Ricouard 22 July 2019
- swiftUI, Instruments, debug

Lessons learned while developing **[MovieSwiftUI](https://github.com/Dimillian/MovieSwiftUI)**. Personally I prefer this kind of articles, highlighting the problems and possible solutions,

Bonus points for using the word: **gracefully**.

### [SwiftUI and Redux — Clean Code and Small, Independent Components](https://medium.com/better-programming/swiftui-and-redux-clean-code-and-small-independent-components-6f46a5eb46b3)
Thomas Ricouard 26 July 2019
- swiftUI, redux

One of the very few positive things I stumbled on during React Native experiment was Redux. So combining SwiftUI and Redux got to be interesting, right?

Well, this article doesn't talk about that - it shows all about how to use (author's implementation) of Redux with SwiftUI! It's part of pretty good looking open source **[MovieSwiftUI](https://github.com/Dimillian/MovieSwiftUI)** iOS/iPad/macOS app.

## 2019 July

Summer vacation in Finland, the whole country is closed down. It's a bliss.

## 2019 June

### [Swift Property Wrappers](https://nshipster.com/propertywrapper/)
Mattt 24 June 2019
- swift

Swift 5.1 comes with `property wrappers`, which enable writing interesting code. In best case the rest of your code will be much more safe and readable, in worst case you got magical hard to debug behaviour.

For example you can define property constraints (e.g. min and max) and automatic value cleanup (e.g. remove invalid characters) to well defined and known values.

To see the proposal details and current status: [SE-0258: Property Wrappers](https://github.com/apple/swift-evolution/blob/master/proposals/0258-property-wrappers.md)

### [isEmpty vs. count == 0](https://medium.com/better-programming/strings-comparison-isempty-vs-count-0-be80d701901b)
Matias Jurfest 25 May 2019
- swift

**TL;DR**: `count` needs to count everything until it can say whether count is zero or not, while `isEmpty` doesn't. So in general better use `isEmpty`, if it fits your use case.

### [WWDC 2019 Viewing Guide](https://useyourloaf.com/blog/wwdc-2019-viewing-guide/)
Keith Harrison (Use Your Loaf) 10 Jun 2019
- wwdc2019

Another interesting list of "Best of WWDC", been checking his lists in previous yours, too. Recommended!

### [WWDC 2019 - The Things You May Have Missed](https://patrickbalestra.com/blog/2019/06/07/wwdc-2019-the-things-you-may-have-missed.html)
Patrick Balestra 7 Jun 2019
- wwdc2019

Good list of Apple SDK changes, updates and new things, which might have been missed in all the SwiftUI excitement. Keep checking, the list will be updated.

### [SwiftUI Essentials](https://developer.apple.com/videos/play/wwdc2019/216/)
Apple 5 Jun 2019
- wwdc2019, iOS, macOS, tvOS, watchOS

SwiftUI intro, the declarative language. Looks amazing, wonder how much this will change in coming years. Looking at swift history of evolvement. But yes, want to try this out.

### [WWDC 2019 Platforms State of the Union](https://developer.apple.com/videos/play/wwdc2019/103/)
Apple, 3 Jun 2019
- wwdc2019, iOS, macOS, tvOS, watchOS

Something I watch live, even though it starts half past midnight and lasts couple hours. Worth every time, especially this year!

### [WWDC 2019 Keynote](https://developer.apple.com/videos/play/wwdc2019/101/)
Apple, 3 Jun 2019
- wwdc2019, iOS, macOS, tvOS, watchOS, ipadOS

Oh. Wow. What! WOW! Shut up and take my... no wait, HOW MUCH for the stand?

The Best Apple WWDC keynote for many years. Classic. Surprising. Delightful.

### [Swift: () -> () vs () -> Void](https://ericasadun.com/2015/05/11/swift-vs-void/)
Erica Sadun 11 May 2015
- Swift

Needed a verification and a reminder, when I was looking at some older code (maintenance task). Use () -> Void.

### [Swift CoreNFC as quick as possible](https://blog.usejournal.com/swift-corenfc-as-quick-as-possible-79544796cd0a)
Myrick Chow 27 Dec 2018
- NFC, iOS

Near Field Communication for iOS has been available since iPhone7 hardware was released 2016. It can be used, when compatible device or tag is within 4 cm distance.

**Setup**: enable "NFC Tag Reading" for app ID at Developer Console as well as at app target Capabilities. Also you MUST define `com.apple.developer.nfc.readersession.formats` at info.plist file. Finally add "CoreNFC" framework, as optional unless your app doesn't work without NFC at all.

Finally some sample code, especially about interpreting NFC related data and comments about UI handling.

## 2019 May

### [The Time of Day Has a Significant Effect on Your Productivity](https://benoitpasquier.com/how-to-bootstrap-ios-app-to-iterate-faster/)
Thomas Oppong 22 April 2019
- productivity

Sometimes less is more, if you know yourself. Studies says human body and mind work in cycles and you should choose what kind of things to do at what time to improve your productivity.

Cycles are 90 - 120 minute waves, but everybody is different based on internal and external factors. In general many are most alert at 9-11 and least productive in the afternoon: do complex tasks in the morning and meetings and brainstorming in the evening. Surprisingly creativity and innovation increases, when you're tired.

Follows with instructions how to find your own personal productivity trends, in 3 weeks to months.

### [An overview of the MVVM design pattern in Swift](https://medium.freecodecamp.org/an-overview-of-the-mvvm-design-pattern-in-swift-fb815ea5da40)
Azhar 12 April 2019
- iOS, architecture, MVVM, Playground

Short introduction to MVVM architecture: layer of abstraction between network (model) and UI (view). There's a lot more to this, as comments rightly say, but this is the basics.

The most interesting part for me was that this was done using `Xcode Playground`, defining and displaying a UIViewController. Comes with full source code.

### [Why I don’t use PDFs for iOS assets](https://bjango.com/articles/idontusepdfs/)
bjango (company) 29 Nov 2017
- iOS, design

Oldie but goldie about using PDF image assets in iOS apps. Very thorough and balanced analysis, pointing out also the good sides. Worth checking out as a reminder, so you can make informed decisions which format to use.

### [Improving asset catalogs](https://bjango.com/articles/assetcatalogs)
bjango (company) 1 May 2019
- iOS, Xcode

Critique of Apple's Xcode asset catalogs, but in a constructive way. Lists current problems in ways of working and suggests some automation improvements. You really don't want to update 100s or 1000s of images manually and then test that everything went ok.

The best part, however, are the documentation links to e.g. `watchOS Complication` images sizes, `asset catalog format` and tool to inspect `.car` files.

### [Xcode Build Locations](https://pewpewthespells.com/blog/xcode_build_locations.html)
Samantha Demi 21 July 2016
- iOS, Xcode

Detailed description of all Xcode build types (Unique, Shared, Custom, DeterminedByTargets) and their build folder locations. Also how to find more info from `com.apple.dt.Xcode` using command line `defaults` command.

The default build location is `Unique`.

### [The iOS Application Lifecycle](https://hackernoon.com/application-life-cycle-in-ios-12b6ba6af78b)
Leela Prasad Penumutchu 15 Jul 2018
- iOS

Concise summary of key points of iOS application lifecycle: app states, transition flow between them, delegate calls and what do they all mean.

For details, read Apple developer documentation e.g. [Strategies for Handling App State Transitions](https://developer.apple.com/library/archive/documentation/iPhone/Conceptual/iPhoneOSProgrammingGuide/StrategiesforHandlingAppStateTransitions/StrategiesforHandlingAppStateTransitions.html#//apple_ref/doc/uid/TP40007072-CH8-SW1).

---

## 2019 April

### [Higher order functions in Swift: Filter, Map, Reduce, flatmap, compactMap](https://medium.com/@abhimuralidharan/higher-order-functions-in-swift-filter-map-reduce-flatmap-1837646a63e8)
Abhimuralidharan 22 Jul 2017
- swift, ios

General description of what are higher order functions and how to use them, followed by detailed description of swift methods (map, filter, reduce, flatmap, compactMap) with multiple samples using collection types (array, dictionary, set).

### [What is Scrum Poker and Why You Should Use It](https://medium.cobeisfresh.com/new-scrum-poker-app-available-for-download-ae804ceb966d)
COBE Team 25 Jan 2017
- agile

The article is about COBE Team experiences with Scrum Poker (aka Planning Poker) and story point estimations - and the iOS/Android ScrumFaces app that they made. The company seems to be in UX design, so the app looks great.

### [Coordinators](https://www.raywenderlich.com/6399-coordinators)
- swift, ios

### [Coordinator Design Pattern: Overview](https://www.raywenderlich.com/1876397-coordinator-design-pattern-overview)
- swift, ios

### [Migrating to Unified Logging: Console and Instruments](https://www.raywenderlich.com/605079-migrating-to-unified-logging-console-and-instruments)
Keegan Rush 1 April 2019 (RayWenderlich)
- swift, iOS, debug, logging

How to debug iOS apps using Apple's `Unified Logging` system with the Console and Instruments apps. Summary: use `os_log` instead of `print`, but otherwise it's similar.

More info at WWDC 2016 video 721 [Unified Logging and Activity Tracing](https://developer.apple.com/videos/play/wwdc2016/721/) and WWDC 2018 video 405 [Measuring Performance Using Logging](https://developer.apple.com/videos/play/wwdc2018/405).

### [Building Simple Async API Request With Swift 5 Result Type](https://medium.com/@alfianlosari/building-simple-async-api-request-with-swift-5-result-type-alfian-losari-e92f4e9ab412)
- swift, iOS, networking

---

## 2019 March

### [Linux and Unix comm command tutorial with examples](https://shapeshed.com/unix-comm/)
- utility

### [What’s new in Swift 5.0](https://www.hackingwithswift.com/articles/126/whats-new-in-swift-5-0)
- swift, ios

### [What’s new in Swift 5.1](https://www.hackingwithswift.com/articles/182/whats-new-in-swift-5-1)
- swift, ios

### [How to Use Psychology to Solve the Procrastination Puzzle](https://medium.com/s/the-complete-guide-to-beating-procrastination/how-to-use-psychology-to-solve-the-procrastination-puzzle-6e6a56cdd535)
- study

### [Lightning Talk: Dear Interviewee: What Your Interviewer Would Like You to Know, But Can’t Tell You](https://skillsmatter.com/skillscasts/13297-lightning-talk-dear-interviewee-what-your-interviewer-would-like-you-to-know-but-can-t-tell-you)
- recruit, interview

### [Lightning Talk: Use Sourcery to Make Your iOS Code Write Itself](https://skillsmatter.com/skillscasts/13308-lightning-talk-use-sourcery-to-make-your-ios-code-write-itself)
- utility, ios

### [Parsing Formal Languages with Swift](https://skillsmatter.com/skillscasts/13298-parsing-formal-languages-with-swift)
- swift

### [How to load and save a struct in UserDefaults using Codable](https://www.hackingwithswift.com/example-code/system/how-to-load-and-save-a-struct-in-userdefaults-using-codable)
- swift, ios

### [Reading and writing basics: UserDefaults](https://www.hackingwithswift.com/read/12/2/reading-and-writing-basics-userdefaults)
- swift, ios

### [iOS Snapshot Test Case: Testing the UI](https://www.raywenderlich.com/5043-ios-snapshot-test-case-testing-the-ui)
- swift, iOS, testing

### [Build performance analysing in Xcode 10](https://www.avanderlee.com/optimization/analysing-build-performance-xcode-10/)
- swift, iOS, Xcode

### [try! Swift Tokyo 2018 - Introducing Charles for iOS](https://www.youtube.com/watch?v=RWotEyTeJhc)
- iOS, debug, networking

History trip of Charles proxy, all the things that can go wrong in networking. Created Charles proxy as solution (for own problems) 18 years ago! Now intro Charles for iOS:

- no more proxy settings
- no more need for computer
- wifi and mobile data connection --> better performance
- share the session recording, check timeline at desktop
  - Parallel networking calls
  - "Times" section and "Latency" row
  - Install Charles certificates (2 steps)
- Check also Latency Debug and Network Performance Analysis

### [Charles Proxy Tutorial for iOS](https://www.raywenderlich.com/641-charles-proxy-tutorial-for-ios)
- iOS, debug, networking

Proxy sits between your app and internet, all requests / responses go through the proxy.

### [Self-sizing Table View Cells](https://www.raywenderlich.com/8549-self-sizing-table-view-cells)
- iOS, swift, testing

- Tutorial app overview
- Settings - General - Accessibility - Larger Text --> check the app

---
HOX: the following is just copy & paste from the original automatically generated template, here as a reference for me.

### Markdown

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/jomnius/study-notes/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
