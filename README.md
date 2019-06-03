# Welcome to Jomnius Lifelong Learning Study Notes

```
The secret of getting ahead
is getting started.

-- Mark Twain
```

Read somewhere how this (non-student) person was studying 15-30 minutes a day, about 5 times a week. She didn't have detailed long-term plans, just general idea for the next few weeks, even when following a book or video series. When you start reading something and check references or additional info, you're suddenly somewhere completely different place.

TODO: Insert [link](https://google.com) when I find it again.

So I decided to try similar system. Here are some notes for some of the bigger, more concentrated, studies I've done. Missing the daily quick blog reads or manual checks.

Now experimenting with the online format, my real study notes are in a physical big black notebook (using real paper and real pen). Most of my notes are just titles and subtitles from original article or video, exact quotes of important text and also source code, there is no point copying it here, too.

The value of physically writing things down is to make it easier for me to remember something afterwards. I'm not planning to read them ever afterwards - however I have checked my notes a few times, mainly to find out which of the many similar articles did I actually read.

Now I'm thinking that I could put here tags and summary, maybe the key discovery or why I read the thing in the first place. That would be kind of meta notes of study notes.

...work in progress, just thinking aloud. Btw direct link to this as a webpage https://jomnius.github.io/study-notes

## Inspiration
My most usual sources for random study inspiration are:
- [iOS Dev Weekly](https://iosdevweekly.com) by Dave Verwer. Delightful collection of the best in mobile development this week (Friday). If you check anything, this is the one.
- [Ray Wenderlich](https://www.raywenderlich.com), massive site for all mobile development related training. Videos, articles, books, podcasts. Good, when you know what you want.
- [Daily Medium Digest](https://medium.com), personalized for me based on... something. There is some criticism against Medium, but it does have lots of quality diverse content. What I like most is that it proposes me articles outside of my main areas of interest, propably because it doesn't know me as well as it would like to. Which is just fine.
- [iOS Goodies](ios-goodies.com), interesting weekly list of links.

Overall, these sources are overlapping more or less.

## Disclaimer
- I have a personal, paid by myself, auto-renewing annual account to [RayWenderlich](https://www.raywenderlich.com). Therefore some of the links might point to non-free content. But since this is **my study notes**, I do have access.

---

## 2019 June

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
