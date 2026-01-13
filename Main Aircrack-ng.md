Main

### Table of Contents

## Introduction

[![The Aircrack-ng Suite](https://www.aircrack-ng.org/lib/exe/fetch.php?tok=25e9c1&media=https%3A%2F%2Faircrack-ng.org%2Fresources%2Faircrack-ng-new-logo.jpg "The Aircrack-ng Suite")](https://www.aircrack-ng.org/doku.php "https://www.aircrack-ng.org/doku.php")Aircrack-ng is a complete suite of tools to assess WiFi network security.

All tools are command line which allows for heavy scripting. A lot of GUIs have taken advantage of this feature. It works primarily on Linux but also Windows, macOS, FreeBSD, OpenBSD, NetBSD, as well as Solaris and even eComStation 2.

It focuses on different areas of WiFi security:

-   Monitoring: Packet capture and export of data to text files for further processing by third party tools.
    
-   Attacking: Replay attacks, deauthentication, fake access points and others via packet injection.
    
-   Testing: Checking WiFi cards and driver capabilities (capture and injection).
    
-   Cracking: WEP and WPA PSK (WPA 1 and 2).
    

We also maintain patches for:

-   Packet injection for Linux drivers
    
-   HostAPd and Freeradius, called WPE (Wireless Pawn Edition) patches, to attack WPA Enterprise.
    

## Tell me more about Aircrack-ng

If you are impatient and want to know how to get started, jump to the [Getting Started Tutorial](https://www.aircrack-ng.org/doku.php?id=getting_started "getting_started").

Aircrack-ng was started at the end of February 2006. It is the Next Generation of aircrack with lots of new features:

-   More cards/drivers supported
    
-   More OS and platforms supported
    

-   WEP dictionary attack
    
-   Fragmentation attack
    
-   WPA1/2 cracking with support for 802.11w captures and PMKID
    
-   WPA Migration mode
    
-   Improved cracking speed
    
-   Capture with multiple cards
    
-   Cracking session
    

-   Optimizations, other improvements and bug fixing
    
-   …
    

## News

|    Date     |              Title               |                                                                                                                                    Content                                                                                                                                     |
|-------------|----------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 6 Dec 2022  |   Now using GitHub Discussions   | We're moving from our old trusty forum to GitHub Discussions partly due to the maintenance burden, which means new posts should be opened in the Discussions tab of our repository.

The old forum will become a static archive so the links to the posts won't become 404. |
| 10 May 2022 |         Aircrack-ng 1.7          | After more than 2 years, we are making a release with a decently large amount of fixes, improvements, and additions. We also broke the 4000 commits barrier, and this release has more than 400 commits.

Read more in our detailed blog post or head to the download section. |
| 13 Apr 2022 | PackageCloud.io 'any/any' change |           Our packages are now compatible with any distribution that supports **.deb** or **.rpm** packages. If you are using them, due to this change, you will have to reinstall the repository to keep receiving updates. Head over to our blog post for all the details.           |

[More news...](https://www.aircrack-ng.org/doku.php?id=morenews "morenews")

## Download

## Current version

Latest version: 1.7

**IMPORTANT** Information Regarding Windows Version **IMPORTANT**  
The windows version requires you to develop your own DLLs to link aircrack-ng to your wireless card. The required DLLs are not provided in the download nor available anywhere on the Internet. Without these DLLs, the windows version will not function. Do NOT post questions or problems to the forum regarding the windows version. At present, there is no support provided.

### Changelog

-   Airmon-ng: Fix avahi killing
    
-   Airmon-ng: rewrite service stopping entirely
    
-   Airmon-ng: Codestyle fixes and code cleanup
    
-   Airmon-ng: Added a few Raspberry Pi hardware revisions
    
-   Airmon-ng: Fixes for 8812au driver
    
-   Airmon-ng: Fix iwlwifi firmware formatting
    
-   Airmon-ng: Remove broken KVM detection
    
-   Airmon-ng: Show regdomain in verbose mode
    
-   Airmon-ng: Updated Raspberry Pi hardware revisions
    
-   Airmon-ng: Document frequency usage
    
-   Airmon-ng: Add a sleep to help predictable names due to udev sometimes renaming interface
    
-   Airmon-ng: Added warning for broken radiotap headers in kernel 5.15 to 5.15.4
    
-   Airmon-ng: shellcheck fixes
    
-   Airmon-ng: support systemctl as some systems don't support 'service' anymore
    
-   Airmon-ng: Fixes for pciutils 3.8, backward compatible
    
-   Airbase-ng: use enum for frame type/subtype
    
-   Airbase-ng: remove a few IE in association responses
    
-   Besside-ng: Support and detect all channels in 5GHz in Auto-Channel mode
    
-   OSdep: Search additional IE for channel information
    
-   OSdep: Android macro fixes
    

-   Patches: Updated freeradius-wpe patch for v3.2.0
    
-   Patches: Updated hostapd-wpe patch for v2.10
    
-   Patches: Added docker containers to test WPE patches
    
-   Autotools: make dist now creates VERSION file
    
-   Autotools: Added maintainer mode
    
-   Autotools: Initial support for Link Time Optimization (LTO) builds
    
-   Integration tests: Added a new test, and improved some existing ones
    
-   Airgraph-ng: switch airodump-join to Python 3
    
-   Manpages: Fixes (typos, tools name, etc.) and improvements
    
-   README: Updated dependencies and their installation on various distros in README.md and INSTALLING
    
-   README: Fixed typos and spelling in README.md and INSTALLING
    
-   Packages: Packages on PackageCloud now support any distro using .deb and .rpm, however, it requires reinstalling repo (BREAKING CHANGE)
    
-   General: Fix compilation with LibreSSL 3.5
    
-   General: Fix issues reported by Infer
    
-   General: Updated buildbots
    
-   General: Add Linux uclibc support
    
-   General: Compilation fixes on macOS with the Apple M1 CPU
    
-   General: Removed TravisCI and AppVeyor
    
-   General: Use Github Actions for CI (Linux, Win, macOS, code style, and PVS-Studio)
    
-   General: Added vscode devcontainer and documentation
    
-   General: Fix warnings from PVS-Studio and build with pedantic (See PR2174)
    
-   General: Shell script fixes thanks to shellcheck
    
-   General: Fixes for GCC 10 and 11
    
-   General: Fixed cross-compilation
    
-   General: Code refactoring, deduplication, cleanup, and misc code improvements
    
-   General: Coverity Scan fixes, which includes memory leaks, race conditions, division by 0, and other issues
    
-   General: PVS Studio improvements,fixes and updates
    
-   General: Code formatting/style fixes
    
-   General: Various fixes and improvements (code, CI, integration tests, coverity)
    
-   General: Update bug reporting template and update the process
    

  
[The complete Changelog](https://www.aircrack-ng.org/doku.php?id=changelog "changelog")

## Git Repository

## Driver patches

They can be found [here...](https://patches.aircrack-ng.org/ "https://patches.aircrack-ng.org") and [this link](https://www.aircrack-ng.org/doku.php?id=install_drivers "install_drivers") explains how to install the driver(s) for your adapter(s).

## Installation

## Aircrack-ng Suite

## Drivers

## Support

Be sure to read the wiki. This wiki contains a vast amount of information to get you going and to resolve problems.

-   manpages: each tool has a manpage.
    
-   [Forum](http://forum.aircrack-ng.org/ "http://forum.aircrack-ng.org/") - DEPRECATED, GO TO GITHUB DISCUSSIONS
    

## Documentation

## Aircrack-ng suite

## Tutorials

## Other Documentation

## Links to Key Resources

## URLs

## Donations

If you have any question regarding this website (this wiki, forum, …), do not hesitate to contact us at [info@aircrack-ng.org](mailto:info@aircrack-ng.org "info@aircrack-ng.org").  

For information about vulnerability and other security issues, as well as reporting, go to the [dedicated page](https://aircrack-ng.org/security.html "https://aircrack-ng.org/security.html") about it.

Thanks to devine for the original work and to everyone who contributed to aircrack (You know who you are) ![;-)](https://www.aircrack-ng.org/lib/images/smileys/wink.svg)

main.txt

· Last modified: 2023/01/16 20:04 by

mister\_x

___