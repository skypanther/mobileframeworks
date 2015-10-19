# Cross-platform Mobile Tools Compared

The following compares three "native" cross-platform mobile development tools: Appcelerator Titanium, Telerik NativeScript, and Facebook ReactNative. Each of these tools promises the features needed to let you build a native, cross-platform mobile app with JavaScript. 

It is **not**:

* a comprehensive review of these tools.
* a comparison of all tools available.
* an endorsement of any one tool vs another.
* a tutorial.
* a comparison of web wrapper (e.g. Cordova-type) tools.

## Comparison Table

**Key:**

* &#x2705; - yes, supports
* &#x274e; = mostly yes, some missing features
* &#x26d4; - mostly no
* &#x274c; - no / not at all
* &#x2753; - unknown
* &#x2757; - yes, warning

|Feature      |<a href="http://www.appcelerator.com" target="_blank">Titanium</a>  |<a href="https://www.nativescript.org/" target="_blank">NativeScript</a>|<a href="https://facebook.github.io/react-native/" target="_blank">ReactNative</a> |
|-------------|----------|------------|------------|
| License     | Apache / Proprietary   | Apache   | BSD   |
| Code repo     | <a href="https://github.com/appcelerator/titanium_mobile/" target="_blank">titanium-mobile</a>   | <a href="https://github.com/NativeScript/NativeScript" target="_blank">NativeScript</a>   | <a href="https://github.com/facebook/react-native" target="_blank">react</a>   |
| iOS apps       | &#x2705; | &#x2705;   | &#x2705;   |
| Android apps   | &#x2705; | &#x2705;   | &#x274e; &#x1f130;   |
| Windows apps   | &#x2705; | &#x274c; &#x1f131;  | &#x274c;   |
| Apple Watch apps   |  &#x274e; | &#x2705;  | &#x2753;   |
| tvOS apps   | &#x274c; | &#x2705;  | &#x26d4; |
| Unified x-platform UI &#x1f132; | &#x274e; | &#x274c; | &#x274c; |
| Direct access<br/>to native APIs | &#x26d4; &#x1f133; | &#x2705; |&#x2705; |
| Module-based<br/>extensibility | &#x2705; | &#x2705; | n/a |
| Reusable UI<br/>components | Alloy Widgets | Plugins | &#x2753; |
| Styling | TSS (proprietary<br/>CSS-like) | CSS subset | Flexbox |
| Debugging | Via Studio IDE | Chrome debug tools | Chrome debug tools |
| Hot reload  | &#x274e;&#x1f134; | &#x2705; |&#x2705; |
| Code encryption | &#x274e; | &#x274c; | &#x274c; |
| Compile-time license<br/>checks | &#x2757; | &#x274c; | &#x274c; |
| Run-time license<br/>checks | &#x2757; | &#x274c; | &#x274c; |
| Testing / crash<br/>reporting | Subscribers | Subscribers | Parse |
| Analytics | Subscribers | Paid add-on | Parse |
| IDE | Appcelerator Studio &#x1f135; | &#x26d4; &#x1f136; | &#x274c; &#x1f137; |
| Framework | Alloy (MVC-like)| &#x2753; | &#x2753; &#x1f138; |
| Biz model   | Enterprise, MBaaS,<br/>Paid subscriptions | Enterprise, MBaaS,<br/>Paid add-ons | &#x2753; |
| MBaaS companion | Arrow Cloud | DevCloud | Parse |
| Subscriptions/cost | OSS: Free &#x1f139;<br/>Indie: $39/mo<br/>Team: $259/seat/mo<br/>Enterprise: call | OSS: Free<br/>Seat: $39/mo<br/>Add-ons: vary<br/>Enterprise: call | Free |


**Footnotes**

* &#x1f130; - Just released and somewhat at an alpha state
* &#x1f131; - "Coming soon" per their web site
* &#x1f132; - Meaning, a single means for creating basic UI components that masks basic differences in the native APIs
* &#x1f133; - The closed-source Hyperloop module enables direct access on iOS and Windows, though has limitations currently. Otherwise, you can create a "native module" to expose the native APIs to the Titanium layer.
* &#x1f134; - LiveView (from Appcelerator) and TiShadow (community) offers whole-app-reload rather than live reload of the "current screen"
* &#x1f135; - Eclipsed-based IDE available to subscribers only; community-created options to support Sublime, Atom, TextMate, etc.
* &#x1f136; - Telerik offers plug-ins for Visual Studio and Sublime. They also offer an online code editor and build tools.
* &#x1f137; - Atom-based IDE is reported to be in development; community-created plug-ins available.
* &#x1f138; - In essence, ReactNative is just the "V" of MVC
* &#x1f139; - Appcelerator publishes their current SDK to only subscribers. OSS/community members have access to one-prior releases (so if current version is 5.1.0.GA, OSS members get access to 5.0.0.GA). OSS users can compile the current SDK from source or use a <a href="http://builds.appcelerator.com.s3.amazonaws.com/index.html#master" target="_blank">CI build</a>.



### Support mechanisms
|Customer type      |Titanium  |NativeScript|ReactNative |
|-------------|----------|------------|------------|
| Docs     | <a href="http://docs.appcelerator.com/platform/latest/" target="_blank">link</a> | <a href="http://docs.nativescript.org/" target="_blank">link</a>   |  <a href="https://facebook.github.io/react-native/docs/getting-started.html" target="_blank">link</a>  |
| Issues/Tickets     | <a href="https://jira.appcelerator.org/" target="_blank">Jira</a>  | <a href="https://github.com/NativeScript/NativeScript/issues" target="_blank">GitHub</a>   |  <a href="https://github.com/facebook/react-native/issues" target="_blank">GitHub</a>  |
| Enterprise     | Varies:<br/>Jira, SLA, phone  | Varies: contact-us   |  n/a  |
| Subscriber     | Jira, self-serve forums  | Google group, partners   |   n/a |
| OSS/Community     | <a href="https://community.appcelerator.com/" target="_blank">Self-serve forums</a>   | <a href="https://groups.google.com/forum/#!forum/nativescript" target="_blank">Google group</a>  |  n/a  |

### Metrics

|Metric      |Titanium  |NativeScript|ReactNative |
|-------------|----------|------------|------------|
| Open tickets     | 36,936  | 182  | 497   |
| Age of oldest ticket     | 12 Dec 2003  | 25 Mar 2015  | 4 Feb 2015   |
| Open pull requests    | 89  | 9  | 196   |
| Age of oldest PR    | ~3 yrs  | ~4 mo  |  ~6 mo  |

*(Snapshot as of 29 Sep 2015 -- please, no PRs to update this. Visit the actual vendor repos/sites for current data.)*

## Discrepencies? Missing Info?

Submit a pull request!

## More info / references

* Most of this info comes from the vendor sites, GitHub repos, blogs, and other vendor-provided resources
* Josh Jensen's *<a href="http://www.slideshare.net/joshcjensen/connectjs-2015-building-native-mobile-applications-with-javascript">Connect.js 2015 - Building Native Mobile Applications with Javascript</a>*  slide deck compares the three frameworks 
* http://mobilejs.io/ is a reference ToDo app in all three frameworks, from Josh Jensen
* http://jolicode.com/blog/crossing-the-native-bridge-to-build-apps-with-javascript

##Disclosure

I used to work for Appcelerator (as lead trainer and later as an engineer). In part, I prepared this chart to help me overcome the natural bias and myopia that comes from working for a company for four years. The info here is as unbiased as I can make it, given my background. It is not meant to endorse or promote any of these tools over another. Please make your own *informed* choice.



<!-- And &#x1f37a; just because I wanted to keep the unicode char for beer handy. -->
