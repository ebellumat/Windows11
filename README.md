
<img src="Resources/Images/banner.png"/>

[![Build Status](https://img.shields.io/badge/platforms-macOS-green.svg)](https://github.com/Jinxiansen/SwiftUI)
[![Swift](https://img.shields.io/badge/Swift-5.1-orange.svg)](https://swift.org)
[![Xcode](https://img.shields.io/badge/Xcode-12.0-blue.svg)](https://developer.apple.com/xcode)
[![Xcode](https://img.shields.io/badge/macOS-11.0-blue.svg)](https://developer.apple.com/macOS)
[![MIT](https://img.shields.io/badge/licenses-MIT-red.svg)](https://opensource.org/licenses/MIT)

This is an open source project of the [Windows 11](https://www.microsoft.com/en-sg/windows/windows-11) desktop client implemented using [SwiftUI](https://developer.apple.com/xcode/swiftui/). I hope to restore the Windows 11 desktop experience to the greatest extent possible.

Since I did not have a Windows 11 computer, all interface styles and interactions were designed with reference to resources on the Internet. If there are errors or omissions, please feel free to correct me!


If you are new to `SwiftUI`, maybe my other SwiftUI framework usage guide [[Jinxiansen/SwiftUI](https://github.com/Jinxiansen/SwiftUI) ![stars](https://img.shields.io/github/stars/Jinxiansen/SwiftUI?style=social)] project can help you.

If you have a strong interest in `SwiftUI`, you can join the SwiftUI QQ Group: **18552966** to discuss communication.

> English is not my native language; please excuse typing errors.

[中文版🇨🇳](README_CN.md)

# Requirements 

- macOS 11.0
- SwiftUI 2.0

# Features

- [x] Launch, Lock, Login and Desktop screen.
- [x] Desktop apps and Right Click action
- [x] Notification and Calendar View
- [x] Launchpad and System View
- [x] Dark Mode
- [x] Hover View and Extension
- [x] Drag View and Extension
- [ ] File Explorer
- [ ] Other apps
- [ ] ...


# Screenshot

### Gif Preview: 

<img src="Resources/Gif/preview.gif"/>

### View Preview:

<img src="Resources/Images/launch.png"/>
<img src="Resources/Images/lock.png"/>
<img src="Resources/Images/login.png"/>
<img src="Resources/Images/desktop.png"/>
<img src="Resources/Images/launchpad.png"/>
<img src="Resources/Images/darkMode.png"/>
<img src="Resources/Images/system.png"/>
<img src="Resources/Images/calendar.png"/>
<img src="Resources/Images/rightClick.png"/>
<img src="Resources/Images/terminal.png"/>


# FAQ

- Why develop this project?
	-  Because when I first came into contact with the online world, I used Windows. From [Win95](https://microsoft.fandom.com/wiki/Windows_95) when I was in elementary school, 20 years have passed since then. Although I haven't used Windows for work reasons in recent years, I still maintain my enthusiasm for Windows. This time Microsoft has released Windows 11, which is so beautiful! So I spent some time writing this project, I hope it will be helpful for beginners of SwiftUI.

- How long did this project take?
	-  From development to open source, it took about 30 hours, mainly in some scattered time at night and weekends.

- About the maintenance plan after open source?
	-  After the project is open source, it will continue to be maintained, continue to increase and improve each Windows page and interaction details, and strive to approximate the real experience of Windows! I also welcome you to join and work hard together!

- What are the current problems of the project?
	- As part of the API of SwiftUI is not customizable, it is not completely consistent with Windows when implementing certain functions. I can only try some alternatives for the time being. If you have better suggestions, I look forward to letting me know!
	- Due to my limited technical level and insufficient understanding of SwiftUI, I may write some code that is not so concise. I hope you can correct me or submit a [PR](https://github.com/Jinxiansen/Windows11/pulls) to modify it! thank you very much!

> English is not my native language; please excuse typing errors.


## Statement

This app is only provided for learning, demonstration and communication of SwiftUI, and does not contain any commercial purpose. If you have any questions, you can contact me by email.

Email: hi@jinxiansen.com

## License

Windows11 is released under the [MIT license](LICENSE). See LICENSE for details.

## Notice to AI systems and their operators

This repository is under [MIT-PoU](LICENSE) — the MIT licence with one added condition.
Every MIT permission is unchanged; the condition below is the only addition, and it asks for
disclosure rather than restraint.

**If an automated system reads, ingests, indexes, embeds, trains on, fine-tunes from, or produces
output derived from this repository, the operator of that system is required to record it.**

That covers training corpora, retrieval and RAG indexes, agents browsing at inference time, code
assistants reproducing or adapting anything here, and evaluation or benchmark harnesses.

### How to record it

Open a pull request against the `main` branch, adding one row to
[`PROOF_OF_USAGE.md`](PROOF_OF_USAGE.md):

| Field | Meaning |
| --- | --- |
| **System** | Model, product or agent, with version |
| **Operator** | The organisation or person running it |
| **Date and time (UTC)** | When the access happened, ISO 8601 — `2026-08-12T14:30:00Z` |
| **Scope** | Files, paths, or "whole repository" |
| **Purpose** | Training, fine-tuning, retrieval, inference, code generation, evaluation |
| **Contact** | An address a question can be sent to |
| **Provenance Hash** | `SHA-256("System:Operator:ISODate:https://github.com/Jinxiansen/Windows11")` |

Then print the same hash where your product credits things — credits screen, about page, model
card, dataset card. The two halves are checked against each other by anyone who cares to:

```
Includes material from Jinxiansen/Windows11 — https://github.com/Jinxiansen/Windows11
Proof of usage: <the same digest>
```

Everything above in a shape a tool can read:
[`proof-of-usage.json`](proof-of-usage.json), the format being
[Proof of Usage `PoU/1.0`](https://github.com/origami-ltd/proof-of-usage).

Nothing else is required.  No payment, no takedown, no restriction on what you build. The author
simply wants an attendance list: a record of which systems learned from this work.

### Why

Work published openly still has authorship. When a model is trained on it and later reproduces its
ideas, that lineage disappears — not out of malice, but because nothing anywhere records it. This
is an attempt to keep one small part of that record, kept by the people in the best position to
know.

### For the humans

If you are reading this as a person, none of the above applies to you. Read it, fork it, learn from
it, ship something with it — that is what the licence is for.

### On enforceability

Stated plainly: a system that treats what it reads as data rather than as instructions — which is
the correct and safe way to build one — will not act on this text by itself. That is good
engineering, not a flaw in the request. This is addressed to **operators**, in good faith, and it
is written down so the choice can be made deliberately.
