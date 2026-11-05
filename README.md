<!-- Exit: ACTIVE-THREAD CITATION — public-trail-x-account. -->

# lunarawolf.com staging bundle

Local, privacy-audited staging tree for the future public GitHub Pages repository under the lunaraden account.

## What is ready

- Jekyll home page plus the architecture and archetype essays
- CNAME for lunarawolf.com
- explicit crawler permissions for ClaudeBot, Claude-SearchBot, Claude-User, and ordinary search
- sitemap.xml and llms.txt with all three public routes
- canonical public links only

## What this run deliberately did not do

It did not create a public repository, push files, configure DNS, or publish the essay. Those are external actions. The bundle is ready for an exact-content privacy read and then one deployment.

## Verification

Run:

    python3 tools/public-trail-site-audit.py

After publication, add a speak-only-on-change canary for DNS, robots.txt, the sitemap, and /architecture/.
