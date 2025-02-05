# The Vulpesk Project
<br/>

## Owners, Collaborators, Honorable Mentions
- inchfox : Organization Owner
- AJ (aangar) : Organization Owner, Lead Developer, Project Manager

## What is the Vulpesk Project?
The Vulpesk Project is an open-source, extensible, abstract security interface. It does not aim to replace any
sort of existing authentication mechanism(s) such as 2FA, U2F, or other sources (that cannot be generically named).
<br/>
Vulpesk aims to allow any sort of developer, organization, or interested individual to build a customize authentication
mechanism that best suits their needs. From the community we have seen anything from simple signing mechanisms, even
to workflows that layer multiple authentication mechanisms for lock-down security.
<br/>
The Vulpesk Project contains a suite of projects that provide a simple interface to integrate as you please. While we have
made a few ourselves such as [Theia](https://github.com/Vulpesk/Theia) (requires [Nyx](https://github.com/Vulpesk/Nyx)),
the suite all relies on [Nomos](https://github.com/Vulpesk/Nomos). Nomos, once configured, will hold your authentication mechanism.
<br/>

## Why?
Well, things like U2F and MFA are often using RFC standards, which is brilliant by all means; but it provides developers and
individuals little leniency or abstractability when making their own visions into reality. Plus, RFC documentation does sorta
suck to read, all things considered (but, some people get it).
<br/>
We set out with the mission to make something simple and portable for the everyday user. While we don't provide the Swiss Army Knife
of tools to give you everything you need, we provide the framework. Nomos is the starting point and your vision is the end.
<br/>

## Disclaimers and Responsibilities of the Vulpesk Project
**We do not guarantee perfect security of this project.** Since the project is open-source and depends on external crates,
packages, and other information; we make **zero guarantees that using this framework is flawless.**
<br/>

Members of the Vulpesk Project will not be legally held responsible for any sort of data leak, compromise, or issue(s) that come
from misuse of any product in our suite. If a vulnerability or CVE related to the project is found our team will strive to address
it as soon as possible, but make no zero-day guarantees. Any of these should be submitted as issues and provide clear methods of replication.
<br/>

**Please use this project at your own risk and convenience.**
