+++
date = '2026-10-18T15:33:38Z'
draft = false
title = 'From Alpine Linux'
+++


This post was created on a Alpine Linux VM running in OpenBSD VMM.  I had to make some modes.:wq



This is after a purge of unneeded npm modules.  Does this show?

### HI

```mermaid
graph TD;
	A[OpenBSD vmm] -->|Hosts| B[Alpine Linux VM];
	B -->|Hugo Server| C[Local Preview];
	B -->|Git Push| D[GitHub];
	D -->|CI/CD Build| E[Cloudflare Pages];
```
