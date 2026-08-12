+++
title = "Home"
description = "Home"
date = "2025-03-01"
aliases = []
author = "Shinya Kato"
+++

<!--
This file is left intentionally empty by default to be backwards compatible with the initial theme setup.

Although the theme has advanced a little bit and it now allows to specify the content on the main page (even if the list of posts/articles is not intended).
This can be:
- with the list of posts/articles (default: `mainSections = ["post"]) or
- without the list of posts/articles (by setting `mainSections = [""]`)

Markdown supported, ie:

```
# Welcome

- Hugo :rocket:
- Hugo theme :rocket:

Don't forget to check the README.md file!
```

Remember that you can also specify a section header for the posts below by configuring the `mainSectionsTitle` parameter in the front matter of this file.
-->

# Home
## About me
I am a database engineer at the NTT DATA Group Corporation.
My primary responsibilities include support, research and development (R&D), and maintaining several extensions for PostgreSQL.
In the support team, we handle over 100 inquiries annually.
Our R&D work on PostgreSQL covers topics such as PostgreSQL on Kubernetes and Neon, a software solution for separating compute and storage in PostgreSQL.

## Interview
- [POSETTE 2025 Speaker Interview](https://posetteconf.com/speakers/shinya-kato/#interview)

## PostgreSQL Contribution
I have been contributing to PostgreSQL since 2020, and was recognized as a Significant Contributor in 2026.

- Full list of committed patches: [git.postgresql.org](https://git.postgresql.org/cgit/postgresql.git/log/?qt=grep&q=Shinya+Kato)
- Patches under development: [cfbot.cputube.org](https://cfbot.cputube.org/shinya-kato.html)

Selected contributions:

- [CVE-2026-14666](https://www.postgresql.org/support/security/CVE-2026-14666/) ([ffca23839](https://git.postgresql.org/cgit/postgresql.git/commit/?id=ffca23839ccaaf8aed5e0729cb041b53f981f04c))
- Vacuum observability ([48f11bfa0](https://git.postgresql.org/cgit/postgresql.git/commit/?id=48f11bfa06c6bc15369a2a0c89f7594392e02e2d), [e646450e6](https://git.postgresql.org/cgit/postgresql.git/commit/?id=e646450e609d690ced30d9e8e3fdc27ee6c3ff4c), [ab40db385](https://git.postgresql.org/cgit/postgresql.git/commit/?id=ab40db3852dfa093b64c9266dd372fee414e993f), [0d7895206](https://git.postgresql.org/cgit/postgresql.git/commit/?id=0d789520619803cf6629ebf980e116d733b6756f), [dd3ae3783](https://git.postgresql.org/cgit/postgresql.git/commit/?id=dd3ae378301f7e84c18f7a90f183c3cd4165c0da), [8c2d5d4f1](https://git.postgresql.org/cgit/postgresql.git/commit/?id=8c2d5d4f1195c6ea62557f5975d8794b52ab4e0f))
- WAL usage statistics (wal_fpi_bytes) ([ad25744f4](https://git.postgresql.org/cgit/postgresql.git/commit/?id=ad25744f436ed7809fc754e1a44630b087812fbc), [5ab0b6a24](https://git.postgresql.org/cgit/postgresql.git/commit/?id=5ab0b6a248076bf373a80bc7e83a5dfa4edf13aa), [f9a09aa29](https://git.postgresql.org/cgit/postgresql.git/commit/?id=f9a09aa2952039a9956b44d929b9df74d62a4cd4))
- Statistics and monitoring views ([2d4ead6f4](https://git.postgresql.org/cgit/postgresql.git/commit/?id=2d4ead6f4bd0e30df15dc0ae654c9ce573f41bed), [deb674454](https://git.postgresql.org/cgit/postgresql.git/commit/?id=deb674454c5cb7ecabecee2e04ca929eee570df4), [857df3cef](https://git.postgresql.org/cgit/postgresql.git/commit/?id=857df3cef7be93f7b9214c926e7af6f06a8cf23e), [235c09efb](https://git.postgresql.org/cgit/postgresql.git/commit/?id=235c09efbb306d6263e904e484abdf44866beb5e), [0a4db67b5](https://git.postgresql.org/cgit/postgresql.git/commit/?id=0a4db67b5ed05c4013ea968930af36853f088404))
- Replication ([422e54e30](https://git.postgresql.org/cgit/postgresql.git/commit/?id=422e54e3092afd09997d27cc7c99598f91075b0d), [400a790a4](https://git.postgresql.org/cgit/postgresql.git/commit/?id=400a790a48eb7a1e76f23f9f6d8a6f7159395f65), [eef1ba704](https://git.postgresql.org/cgit/postgresql.git/commit/?id=eef1ba704ddeb73633e40f8cab41ab7402952684), [e35add48c](https://git.postgresql.org/cgit/postgresql.git/commit/?id=e35add48ccc2e5aa94de360f1a43c6c150bda54a), [21c1125d6](https://git.postgresql.org/cgit/postgresql.git/commit/?id=21c1125d660617f71b20304150e4a8583299cf86), [5a4eba558](https://git.postgresql.org/cgit/postgresql.git/commit/?id=5a4eba558aa76c36ecf2aab7587b233c0e2003e2), [883a95646](https://git.postgresql.org/cgit/postgresql.git/commit/?id=883a95646a8e67a2d316f230712ed82b8ba58e28), [cb937e48f](https://git.postgresql.org/cgit/postgresql.git/commit/?id=cb937e48f01fa710d084694de8cc556223ba0967))
- COPY and file_fdw ([e0a3a3fd5](https://git.postgresql.org/cgit/postgresql.git/commit/?id=e0a3a3fd5361913502ff696ecf47770ca55975ae), [26cb14aea](https://git.postgresql.org/cgit/postgresql.git/commit/?id=26cb14aea12a0f0c2f9a49de3865721936b711a7), [f3da70a80](https://git.postgresql.org/cgit/postgresql.git/commit/?id=f3da70a805f9a9dd2deada728649b2cfbeae9cb3), [ad381d0d9](https://git.postgresql.org/cgit/postgresql.git/commit/?id=ad381d0d9244b1490efccca2126ba3f82e144605), [bc2f348e8](https://git.postgresql.org/cgit/postgresql.git/commit/?id=bc2f348e87c02de63647dbe290d64ff088880dbe))
- Client tools (psql, createuser, pg_checksums, pg_waldump) ([361499538](https://git.postgresql.org/cgit/postgresql.git/commit/?id=361499538c9d3640e1ed5522e08fdf81b08e76ae), [9a6915257](https://git.postgresql.org/cgit/postgresql.git/commit/?id=9a6915257d1d804ddba05331030b74d7426a4005), [6afcab6ac](https://git.postgresql.org/cgit/postgresql.git/commit/?id=6afcab6ac1e03975dc59d62c3ccaf98ed2831669), [4cbe57974](https://git.postgresql.org/cgit/postgresql.git/commit/?id=4cbe579746ea05898f2b0c7ba88e4015b781ff71), [08951a7c9](https://git.postgresql.org/cgit/postgresql.git/commit/?id=08951a7c93cf0dd791ee6ac8a8cf5e4b152528e5), [a5b336b8b](https://git.postgresql.org/cgit/postgresql.git/commit/?id=a5b336b8b9e04a93e7c8526302504d2e5201eb80), [0b0d277c3](https://git.postgresql.org/cgit/postgresql.git/commit/?id=0b0d277c35533baecc8d1a9356f71de5f2ee0bd8), [e2ce88b58](https://git.postgresql.org/cgit/postgresql.git/commit/?id=e2ce88b58f151753b094f28bc387cebae865927c), [2eb1fc8b1](https://git.postgresql.org/cgit/postgresql.git/commit/?id=2eb1fc8b1ae8b974007e85636fc7336a9b5d7222), [51893c846](https://git.postgresql.org/cgit/postgresql.git/commit/?id=51893c8463501fc9a38e39cc097773dbdfb9db82), [3f238b882](https://git.postgresql.org/cgit/postgresql.git/commit/?id=3f238b882c276a59f5d98224850e5aee2a3fec8c))
- Backend code cleanups ([e3481edfd](https://git.postgresql.org/cgit/postgresql.git/commit/?id=e3481edfd1b6b0a64fef8f43cfa3b48e94c01682), [59bae2343](https://git.postgresql.org/cgit/postgresql.git/commit/?id=59bae234352d10535da7e655bcd7bc8a1339f57f), [9181c870b](https://git.postgresql.org/cgit/postgresql.git/commit/?id=9181c870bada196711206f3a795bde6b8c43dcd3), [24cb3a08a](https://git.postgresql.org/cgit/postgresql.git/commit/?id=24cb3a08a43b5a48f5fba4a83d297218e2e748c5), [4c5e1d078](https://git.postgresql.org/cgit/postgresql.git/commit/?id=4c5e1d0785ce150c3e6c65b009ea56815acbc8cd))
- Documentation and configuration fixes ([3ef575e4f](https://git.postgresql.org/cgit/postgresql.git/commit/?id=3ef575e4f190a26e50e46f2f8584a53b524660d0), [2963ddeef](https://git.postgresql.org/cgit/postgresql.git/commit/?id=2963ddeef2be6d6e064cb9d382f67dcbf2c049a8), [9fcd4874e](https://git.postgresql.org/cgit/postgresql.git/commit/?id=9fcd4874ed50ee6c60dadd0f1146d8fea9ff0055), [d83a108c1](https://git.postgresql.org/cgit/postgresql.git/commit/?id=d83a108c10a3ec886a24c620a915aa2c5bc023aa), [0cf79a7f6](https://git.postgresql.org/cgit/postgresql.git/commit/?id=0cf79a7f6801d3e69de6450d585e385a4064b057), [d78b6cbb6](https://git.postgresql.org/cgit/postgresql.git/commit/?id=d78b6cbb602f5c36db3e267e2713b3aa22c815a5), [e5975c2da](https://git.postgresql.org/cgit/postgresql.git/commit/?id=e5975c2daad0327b9faa6b62bcfbf173680d14b9), [a73d6c87f](https://git.postgresql.org/cgit/postgresql.git/commit/?id=a73d6c87f2eb19681fe52d6d8bb7db38a7a7da2a), [fab54e6c1](https://git.postgresql.org/cgit/postgresql.git/commit/?id=fab54e6c1a3efd12bde22a24ebc2b08f6affcd04), [0b039e3a8](https://git.postgresql.org/cgit/postgresql.git/commit/?id=0b039e3a8489c08ec61b4d40382047c389af91ad), [61d599ede](https://git.postgresql.org/cgit/postgresql.git/commit/?id=61d599ede7424d88bbd4006b968bae366b6b9f5d))
