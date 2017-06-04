# .a miniRFC.
---
## Personal style and design convension.

### Abstract
This resource acts in part as 1.) a declaration of my currently observed coding style convensions, 2.) to serve as a personal and single evolving authority of these convensions and 3.) be a public [for what's it worth] undertaking by myself to use these convensions (where mum lets me). 

> **NOTES**
> > This resource tries to follow RFC style and defer to offical IETF resources where possible.

> > _This document occasionally uses terms that appear in capital letters.
   When the terms **"MUST"**, **"MUST NOT"**, **"SHOULD"**, **"SHOULD NOT"**, and **"MAY"**
   appear capitalized, they are being used to indicate particular
   requirements of this specification.  A discussion of the meanings of
   the terms **"MUST"**, **"SHOULD"**, and **"MAY"** appears in [RFC-1123](https://www.rfc-editor.org/info/rfc1123); the
   terms **"MUST NOT"** and **"SHOULD NOT"** are logical extensions of this
   usage._

### Sections

### Language specific conventions

#### PHP
1. [Namespace naming](sections/lang/php/php.root#Namespace%20naming)
1. [Class naming](sections/lang/php/php.root#Class%20naming)
1. [Method naming](sections/lang/php/php.root#Method%20naming)
1. [Attribute naming](sections/lang/php/php.root#Attribute%20naming)
> 1. [Private prefix](sections/lang/php/php.root#Attribute%20naming)
> 1. [Static prefix](sections/lang/php/php.root#Attribute%20naming)
> 1. [Pointer/Reference prefix](sections/lang/php/php.root#Attribute%20naming)
> 1. [Constant prefix](sections/lang/php/php.root#Attribute%20naming)

#### ~~JS~~
1. ~~[Namespace naming]()~~
1. ~~[Class naming]()~~
1. ~~[Method naming]()~~
1. ~~[Attribute naming]()~~
> 1. ~~[Private prefix]()~~
> 1. ~~[Static prefix]()~~
> 1. ~~[Pointer/Reference prefix]()~~
> 1. ~~[Constant prefix]()~~



#### Applied : Application Program Interface. (RPC Gateway)

1. ~~[Development / Lifecycle]()~~
> 1. ~~[Mocking]()~~
> 1. ~~[Developer sandboxing.]()~~
> 1. ~~[EOL and Support patterns]()~~
> 1. ~~Phases:~~
> > 1. ~~Playground/Adhoc~~
> > 1. ~~Local development~~
> > 1. ~~Development -> Hotfix / Feature~~
> > 1. ~~QA~~
> > 1. ~~Release candidate 1/2~~
> > 1. ~~Released -> Deployment tag.~~
1. ~~[Endpoint URI path design guide]()~~
> 1. ~~[Intro: Semantic Path / URI topology]()~~
> > 1. ~~[Recommended Semantic Path template]()~~
> > 1. Adding a versioning component -> Manifest busting -> Backwards compatibility.
> 1. [Lingistic / nomeniture convention]()
> > 1. [Gender and plurality](api-sg-genpla)
> > 1. ~~Localisation descussion~~
1. ~~:testtube:[Protocals]()~~
> 1. ~~Current preferences when selected a service protocal.~~
> 1. ~~Authentication bible~~
> 1. ~~HTTP[[S]]~~
> > 1. ~~Request verbs.~~
> > 1. ~~and Status codes.~~
> > > 1. ~~Status codes as rule based routing.~~
1. ~~:map:[Architectual concerns]()~~
> 1. ~~:computer:[Hosting]()~~
> > 1. ~~[within Geographics]()~~
> > 1. ~~[within an active Development context]()~~
> > 1. ~~[within a (horizontal) scale]()~~
> > 1. ~~Working within a multiworker / multiwrite conherit data dependence.~~
> > > 1. ~~Alternatives to Master / Master DB Replication.~~
1. ~~:ticket: [Security]()~~
> 1. ~~Authentication methology templates.~~
> 1. ~~Rate-limiting.~~
> 1. ~~API User best practices.~~
> 1. ~~API User within a Lifecycle context.~~
> 1. ~~TLS / Encryption / Signing~~
> > 1. ~~Making a company identity authority~~
> > > 1. ~~Using SMIME, HTTPS or Code Signing type CAs.~~
> > > 1. ~~Using a ROOT (self-signed) CA and when to.~~
> > > 1. ~~A few enterprise 3rd party CA alternatives~~
> > 1. Code signing:
> > > 1. ~~Developer certificates and commit signing.~~
> > > 1. ~~Atomic and crypographical signed releases.~~
> > > 1. ~~Forward end-point encryption. (MUST)~~
> > > 1. ~~**Inter-Tier/Node** communication guidelines.~~
> > > 1. ~~(howto:) Stateless crypographical signed sessions~~
> > 1. ~~Challenge based tokening.~~
> > 1. ~~Understanding PCI and scheduling stored user data.~~
> > 1. ~~Safe(r) Fault / Verbosity patterns.~~
> > 1. ~~Replay / Man-in-the-Middle / Service enumation overview.~~
> > > 1. ~~"NOOCE"? -> Learning from UDP Sequence field.~~
> > 1. ~~Proxying 3rd-party API dependencies in the development phases.~~
> > 1. ~~[DoS hardening](api-sec-nodos)~~
> > > 1. ~~Passive ->~~
> > > > 1. ~~[Understanding: Deterministic verse non-deterministic end points.]~~
> > > > 1. ~~[Understanding: Payloads (and Caching) -> Userbound verse Servicebound.]~~
> > > > 1. ~~! Defining a **tiered architecture.**~~
> > > > 1. ~~Tiering for a smart gateway layer~~
> > > > 1. ~~Tiering the process stack.~~
> > > > 1. ~~Methods for KV coherency ~~
> > > > 1. ~~Context derived path mapping.~~
> > > 1. ~~Active ->~~
> > > > 1. ~~IP and TCP state filtering.~~
> > > > 1. ~~Heuristic triggered filtering~~
1. ~~[Logging / Auditing]()~~
> 1. ~~Handling multi-host, OS-level events with services like syslogd.~~
> 1. ~~Levaging exception feedback loops for defensive and robust services. (COMING SOON)~~



### Support or Contact

####  Full Copyright Statement

> **Copyright (C) Kyle Younge (2017).  All Rights Reserved.**

> > This document and translations of it may be copied and furnished to
   others, and derivative works that comment on or otherwise explain it
   or assist in its implementation may be prepared, copied, published
   and distributed, in whole or in part, without restriction of any
   kind, provided that the above copyright notice and this paragraph are
   included on all such copies and derivative works. However, this
   document itself may not be modified in any way, such as by removing
   the copyright notice or disclaimers.

> > This document and the information contained herein is provided on an
   "**AS IS**" basis and the authors, ie. Kyle Younge or contributors, ie others
   **DISCLAIM ALL WARRANTIES, EXPRESS OR IMPLIED, INCLUDING
   BUT NOT LIMITED TO ANY WARRANTY THAT THE USE OF THE INFORMATION
   HEREIN WILL NOT INFRINGE ANY RIGHTS OR ANY IMPLIED WARRANTIES OF
   MERCHANTABILITY OR FITNESS FOR A PARTICULAR PURPOSE.**

#### Acknowledgement

> These guidelines are in part are an aggregation of every sensible developer and engineer I have worked with.
> > **THANK YOU!**
   
> Where I remember and can, all copy & pastes of other 3rd party resources will be itemised below:
   
> > - Countless [IETF](https://www.ietf.org) :heart:
