# Security Policy – Chiki加固

**This is for internal use only.**

If you’re not part of ridhoae303 team or an explicitly authorized partner, you shouldn’t even be looking at security details. But just in case something slips or you spot something weird while legitimately working with us, here’s the deal.

## Reporting a Bug or Vulnerability

We don’t run a public bug bounty. No outside rando gets to file reports.  
But if you’re **inside the team** or **got explicit permission** from ridhoae303, hit us up the right way.

a) Use the internal company channel (e.g., private Slack, Teams, or direct email to ridhoweb303@gmail.com).  
b) Encrypt anything sensitive with our PGP key – ask the team for it.  
c) Do **not** post issues in GitHub public issues, Discord, Telegram, or any other public space.  
d) Do **not** share proof-of-concept with outsiders. Keep it between you and the internal security crew.

## What We Expect From You

We keep things chill but professional.

1) Give a clear description of what you found – steps, environment, Android version, affected component.  
2) Let us know if it’s about native checks, runtime tamper detection, response logic, or docs mismatch.  
3) Don’t run tests on production apps without a sandbox or explicit go-ahead.  
4) Don’t leak, sell, or weaponize the info. That’s a fast way to get banned and possibly worse.

## What You Can Expect From Us

We take internal security seriously.

a) We’ll acknowledge your report within 3 business days (if you’re legit internal/approved).  
b) We’ll triage and confirm if it’s a real issue.  
c) We’ll fix it in a private commit – no public disclosure, no CVE fanfare, no writeups.  
d) If you reported in good faith, you get a solid “thanks” and maybe internal credit. No cash rewards, sorry.

## Scope

Only these things count as “in scope” for reporting:

- Actual security flaws in Chiki加固’s protection logic (bypasses, crashes that leak internal state, etc.)  
- Broken environment checks that give false negatives in hostile conditions  
- Memory corruption or native code bugs that affect integrity  
- Misconfiguration in build scripts that weakens protection

Not in scope:

- “Missing features” or feature requests  
- Performance whining without evidence  
- Anything related to root/magisk detection being too strict – that’s intentional  
- Normal app crashes that don’t expose security internals

## Out-of-Band Disclosure Policy

If someone dumps a vulnerability on Twitter, GitHub, or some forum without going through us first:

1) We won’t acknowledge it as a valid report.  
2) We’ll fix it internally in our own time.  
3) The person who leaked it gets no credit and may face legal consequences under our license.

We don’t negotiate with public disclosure clout chasers. Period.

## Contact (Internal Only)

For authorized people only:  
**ridhooffweb@gmail.com** – use PGP.  
No DMs on personal socials unless you’ve been told it’s okay.
