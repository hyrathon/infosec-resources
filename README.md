# List of InfoSec resources

I'm just going to put good stuff I find here. The list isn't comprehensive or exhaustive. This is mainly just a FAQ so I can just link people here for my own laziness.

# Where to start?

- [How to start hacking? The ultimate two path guide to information security. - /r/hacking](https://www.reddit.com/r/hacking/comments/a3oicn/how_to_start_hacking_the_ultimate_two_path_guide/)
- [LiveOverflow's YouTube channel](https://www.youtube.com/channel/UClcE-kVhqyiHCcjYwcpfj9w)
- [Advice for young hackers. How to teach yourself](https://www.youtube.com/watch?v=0Ejj2aBG5c8)

# CTFs

If you are new, you should start with high school level and eventually level up to college level.

- https://ctftime.org - Find CTFs and write-ups
- https://picoctf.com/ (high school level)
- NSA Codebreaker challenge
- CSAW RED (high school level) - Formerly known as CSAW HSF
- CSAW CTF (college level)
- HackTheBox - I never did this, but it's popular

# Binary Exploitation

- [Gatech Sslab CS 6265: InfoSec Lab](https://tc.gts3.org/cs6265/2021/) - GREAT resource on intro to binex.
- [how2heap](https://github.com/shellphish/how2heap) - intro to glibc heap exploitation
- [Dhaval Kapil's heap explotation guide](https://heap-exploitation.dhavalkapil.com/) - intro to glibc heap exploitation. slightly outdated but still good
- http://pwnable.kr/ - Great resource and created by my former colleague [Daehee87](https://daehee87.github.io/)
- http://pwnable.tw/ - more pwnables

# Game hacking and reversing

- [Pointers for REAL dummies](http://alumni.cs.ucr.edu/~pdiloren/C++_Pointers/) - This is how I finally understood pointers when I was 12 years old. GREAT guide and it will teach you about C and what is memory.
- [Fl33p's CS:S bunnyhop hack tutorial (YT)](https://www.youtube.com/watch?v=RiS-j_ecG0A) - A bit outdated but this is what helped me finally understand how to use a debugger and Cheat Engine and Visual Studio. The explanations are not 100% accurate but most importantly it is really beginner friendly for noobs
- [Reverse Engineering discord](https://discord.com/invite/weKN5wb)
- [godbolt.org Compiler Explorer](godbolt.org/) - Good to learn what code looks like when it gets compiled
- [Reverse Engineering Stack Exchange](reverseengineering.stackexchange.com/) - Good place to figure out how to do something in IDA Pro.

# Blogs (in no particular order)
- [Google Project Zero blog](googleprojectzero.blogspot.com) - Cutting-edge vulnerability research.
- [Secret Club](https://secret.club) - Syndication on various innovative research on reverse engineering, esp. game hacking.
- [Can Bölük's blog](https://can.ac) - Hypervisors, Windows internals, anticheats. He is a legendary reverse engineer
- [Derek Rynd and Aidan Khoury's blog (revers.engineering)](https://revers.engineering) - Hypervisors, Windows internals, Anticheats. They are a lot smarter than me
- [Sinaei's blog](https://rayanfam.com/) - Hypervisor from scratch
- [Orange Tsai's blog](https://blog.orange.tw/) - Lot of cutting-edge research on a broad range of topics. He is totally an infosec legend
- [Alex Ionescu and Yarden Shafir's blog](https://windows-internals.com/pages/internals-blog/) - Windows internals, systems, kernel.
- [Rolf Rolles' blog](https://www.msreverseengineering.com/blog/) - Reverse engineering, program analysis, (de)obfuscation, IDA Pro
- [lcamtuf's blog](https://lcamtuf.blogspot.com/) - Fuzzing and systems.
- [Halvarflake's blog](https://addxorrol.blogspot.com/) - Various topics in systems and security.
- [Trail of Bits blog](https://blog.trailofbits.com/) - State-of-the-art research on cryptography, program analysis, bug hunting
- [Bruce Dawson's blog](randomascii.wordpress.com) - Systems, compilers, and performance.
- [Travis Downs' blog](https://travisdowns.github.io/) - Systems, comppilers, and performance.
- [Krebs on Security](krebsonsecurity.com) - Mainstream InfoSec news.
- [Bruce Schneier's blog](www.schneier.com) - Cryptography and privacy news.
- [Hex-Rays blog](https://hex-rays.com/blog/), - Tips and tricks for IDA Pro

# Other InfoSec newsletters, zines, and publications

- [LWN](https://lwn.net/) - Linux internals
- [/r/securityCreators/](https://www.reddit.com/r/securityCreators/)
- [zSecurity Twitter](https://twitter.com/_zsecurity_)
- [phrack magazine](phrack.org/)

# Favorite Tools

I am a Windows user so I mainly use Windows tools. Sorry Linux users.

## Must-have, essential tools
- [Python 3](python.org) - hacker's best friend
- [x64dbg](https://github.com/x64dbg/x64dbg) - Windows userland debugger
- [Process Hacker](https://processhacker.sourceforge.io/)
- IDA Pro (or Ghidra) - disassembler
- [HxD](https://mh-nexus.de/en/hxd/) - hex editor
- [Cheat Engine](https://www.cheatengine.org/) - memory hacking tool
- [CFF explorer](https://ntcore.com/?page_id=388) - PE editor
- Windows Calculator, MSpaint, and notepad
- [diffchecker.com](https://www.diffchecker.com/)
- [cyberchef](https://www.cyberchef.in/) - data processing multitool
- [Sublime Text](https://www.sublimetext.com/)
- [Sysinternals suite](https://docs.microsoft.com/en-us/sysinternals/downloads/sysinternals-suite)
- [mitmproxy](https://mitmproxy.org/)

## Other handy tools
- [Wireshark](wireshark.org)
- [WinDbg](https://docs.microsoft.com/en-us/windows-hardware/drivers/debugger/debugger-download-tools) - for Windows kernel debugging
- [Pestudio](https://www.winitor.com/) - pe dissector and triage tool
- [ReClassEx](https://github.com/ajkhoury/ReClassEx) - in-memory struct dissector
- [010 hex editor](https://www.sweetscape.com/010editor/) - fancier, but paid, hex editor. I don't use this often but it's popular
- [JDA Java disassembler](https://github.com/LLVM-but-worse/java-disassembler) - for Java applications
- [dnSpy](https://github.com/dnSpy/dnSpy) - for .NET applications
- [apktool](https://ibotpeaches.github.io/Apktool/) - for Android shit
- [java-deobfuscator](https://github.com/java-deobfuscator/deobfuscator) - written by samczsun who is smart as hell
- [de4dot](https://github.com/de4dot/de4dot) - .NET deobfuscator
- [Detect It Easy (DIE)](https://github.com/horsicq/Detect-It-Easy) - detect compiler and packers. I don't often use this since I can usually recognize by experience
- [Sage](https://www.sagemath.org/) - for cryptography
- [Proxifier](https://www.proxifier.com/) - basically proxychains for Windows

## Hex-Rays plugins
- [HexRaysPyTools](https://github.com/igogo-x86/HexRaysPyTools) - must-have
- [ClassInformer](https://sourceforge.net/projects/classinformer/) - RTTI parser (for Win32)
- [ret-sync](https://github.com/bootleg/ret-sync)
- [Labelless](https://github.com/a1ext/labeless)
- [abyss](https://github.com/patois/abyss)

## x64dbg plugins
- [ScyllaHide](https://github.com/x64dbg/ScyllaHide) - Anti-anti-debug
- [xHotspots](https://github.com/ThunderCls/xHotSpots) - Sometimes useful for reversing GUI shit

# Lectures and slides

- [Gatech CS 8803: Compilers Theory and Practice](https://omscs.gatech.edu/cs-8803-o08-compilers-theory-and-practice-course-videos)
- [Gatech Sslab CS 3210: Operating Systems](https://tc.gts3.org/cs3210/)

# Reference materials

- [Intel Manual volume 3](https://www.intel.com/content/www/us/en/architecture-and-technology/64-ia-32-architectures-software-developer-system-programming-manual-325384.html) - they say that every question you have is answered somewhere in this book. the question is where to find it. and also how to understand it. since this shit is not easy nor fun to read. sometimes if you ask some stupid question people will tell you to go read the intel manual. it's an advanced way to tell people to fuck off.
- Hacker's Delight - bit hacking tricks, you see them used by compilers often. Division constants
- [Dragon Book](https://en.wikipedia.org/wiki/Compilers:_Principles,_Techniques,_and_Tools) - popular compilers textbook
- [SSA book](https://github.com/pfalcon/ssabook) - resource for advanced topics on single static assignment form in compilers