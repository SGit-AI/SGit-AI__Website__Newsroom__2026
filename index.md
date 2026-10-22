# 2026, one story at a time

The SGit Newsroom's year: one site per month, one site per story that matters, each built from captured evidence. October 2026 is live with the PHP flaws; the other months are placeholders until a story opens them.

The SGit Newsroom · the year as stories

# 2026, one story at a time

The [newsroom](https://newsroom.sgit.ai/) publishes articles and a daily wire. This site is the other axis: time. Each month has a site, each story that is big enough gets a site of its own, and every one of them is built the same way, from sources captured, dated and hashed into a vault, with a status word on every claim. Start at a month, go down to a story, and come back up the same way.

## The months

January 2026 planned

### January

No story site has opened this month yet.

February 2026 planned

### February

No story site has opened this month yet.

March 2026 planned

### March

No story site has opened this month yet.

April 2026 planned

### April

No story site has opened this month yet.

May 2026 planned

### May

No story site has opened this month yet.

June 2026 planned

### June

No story site has opened this month yet.

July 2026 planned

### July

No story site has opened this month yet.

August 2026 planned

### August

No story site has opened this month yet.

September 2026 planned

### September

No story site has opened this month yet.

October 2026 live

### October: the PHP flaws

The month's site, with the story of CVE-2026-109618 and CVE-2026-109619 as its lead.
- [php2shell: the two PHP flaws, tracked as evidence](https://php.oct.2026.newsroom.sgit.ai/) claims with a status, a timeline, the code, the agencies, the impact, every source hashed

November 2026 planned

### November

No story site has opened this month yet.

December 2026 planned

### December

No story site has opened this month yet.

## Where this sits

Three levels, each a site with its own repository, version and release history: the newsroom, the year, the month, the story. Every level links up and down; nothing is reachable from only one direction.

### Up
- [newsroom.sgit.ai](https://newsroom.sgit.ai/): the SGit Newsroom: articles, the desks, the wire, the reading meter

### Down
- [October 2026](https://oct.2026.newsroom.sgit.ai/): the month's stories, with the PHP flaws as the lead
- [php2shell](https://php.oct.2026.newsroom.sgit.ai/): the two PHP flaws of October 2026, tracked as evidence

## How this site works

A hub site is one JSON file rendered by one script with no clock in it: the same data gives byte-identical pages. The gate checks links, twins, llms.txt, determinism and credential shapes before every release, and the release script refuses to call a release done until the live site serves the new version. The method is the one the story sites use, at the smallest size that still follows it.

---
site v0.0.2 · https://2026.newsroom.sgit.ai/index.html
