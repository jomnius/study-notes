# Welcome to Jomnius Lifelong Learning Study Notes

```
The secret of getting ahead
is getting started.

-- Mark Twain
```

Read somewhere how this non-student person was studying about 15-30 minutes a day, about 5 times a week. She didn't have any detailed long-term plans, just general idea for the next few weeks, because when you start reading something and check references or additional info, you're suddenly somewhere completely different subject.

Insert [link](https://google.com) when I find it again.

So I decided to try similar system. Here are some notes for some of the bigger, more concentrated, studies I've done. Missing the daily quick blog reads or manual checks.

Now experimenting with the online format, my real study notes are in a physical big black notebook (using real paper and real pen). Most of my notes are just titles and subtitles from original article or video, exact quotes of important text and also source code, there is no point copying it here, too.

The value of physically writing things down is to make it easier for me to remember something afterwards. I'm not planning to read them ever afterwards - however I have checked my notes a few times, mainly to find out which of the many similar articles did I actually read.

Now I'm thinking that I could put here tags and summary, maybe the key discovery or why I read the thing in the first place. That would be kind of meta notes of study notes.

...work in progress, just thinking aloud. Btw direct link to this webpage https://jomnius.github.io/study-notes

---

## 2019 May

### [Xcode Build Locations](https://pewpewthespells.com/blog/xcode_build_locations.html)
Samantha Demi 21 July 2016
- ios

Detailed description of all Xcode build types (Unique, Shared, Custom, DeterminedByTargets) and their build folder locations. Also how to find more info from `com.apple.dt.Xcode` using command line `defaults` command.

The default build location is `Unique`.

### [The iOS Application Lifecycle](https://hackernoon.com/application-life-cycle-in-ios-12b6ba6af78b)
Leela Prasad Penumutchu 15 Jul 2018
- ios

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
- swift, ios, debug

### [Building Simple Async API Request With Swift 5 Result Type](https://medium.com/@alfianlosari/building-simple-async-api-request-with-swift-5-result-type-alfian-losari-e92f4e9ab412)
- swift, ios, networking

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
- utility

### [Parsing Formal Languages with Swift](https://skillsmatter.com/skillscasts/13298-parsing-formal-languages-with-swift)
- swift

### [How to load and save a struct in UserDefaults using Codable](https://www.hackingwithswift.com/example-code/system/how-to-load-and-save-a-struct-in-userdefaults-using-codable)
- swift, ios

### [Reading and writing basics: UserDefaults](https://www.hackingwithswift.com/read/12/2/reading-and-writing-basics-userdefaults)
- swift, ios

### [iOS Snapshot Test Case: Testing the UI](https://www.raywenderlich.com/5043-ios-snapshot-test-case-testing-the-ui)
- swift, ios, testing

### [Build performance analysing in Xcode 10](https://www.avanderlee.com/optimization/analysing-build-performance-xcode-10/)
- swift, ios

### [try! Swift Tokyo 2018 - Introducing Charles for iOS](https://www.youtube.com/watch?v=RWotEyTeJhc)
- ios, debug, networking

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
- ios, debug, networking

Proxy sits between your app and internet, all requests / responses get through the proxy.

### [Self-sizing Table View Cells](https://www.raywenderlich.com/8549-self-sizing-table-view-cells)
- ios, swift, debug

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
