# AirSight launch guide

Prepared 9 October 2026 for Apoorv Raj. Start with the actual prototype, publish a clear project page, configure your identity and apply using accurate facts.

## 1. Understand what the screenshot gets wrong

The current Claude Startups FAQ says the free Team and $1,000 API credit offers are over capacity and applications may be re-reviewed. It says bootstrapped founders can apply. An active repository and a domain do not guarantee admission or benefits. The official terms give Anthropic discretion over eligibility and evaluation. We did not verify the screenshot's claims that checks are primarily automated, that incorporation can always be omitted, or that every public-email applicant is immediately rejected. Follow the live form and current terms.

## 2. Know what has been prepared

The repository change adds a landing page, clearer simulation labels, a real local demo-packet download, direct links into the five demo views, a privacy note, a substantive README and application/implementation documentation. It preserves the original prototype as the canonical demo. A separate private review website uses the same files.

The new website is a presentation layer around your existing prototype. It does not add live pollution data, a trained model, a paid service or a Claude API integration.

## 3. Review and publish the repository version

Review the proposed branch and merge it only when satisfied. For public publication from this repository: open Settings > Pages, select Deploy from a branch, choose main and /(root), then save. Confirm the resulting site loads and its demo works before using the URL in an application. The expected project URL is https://apoorvraj429-design.github.io/AirSight/; it is not verified live by these instructions. No domain is needed for that initial review.

## 4. Choose a domain you intend to keep

A domain is the address you own; hosting is where the website lives; DNS connects them. Candidate name patterns are getairsight, airsightproject and airsightlab with an appropriate available extension. These are naming ideas, not availability, trademark or price checks. Check the full renewal price before purchase. Do not buy a domain solely for a promised credit offer.

Use one consistent name across the website, email, project description and application. Keep AirSight as a project name unless you have an actual registered legal entity. Account creation, billing and ownership verification must use your own details.

## 5. Connect the domain to GitHub Pages

Verify ownership in GitHub first. Add your chosen domain under repository Settings > Pages before setting DNS. For a root domain, use the four A records below. For www, point CNAME to your GitHub account host, without the repository path. Enable HTTPS once available; DNS/certificate changes may take up to 24 hours. Avoid wildcard records. Only replace conflicting website records, not unrelated email records.

| Type | Name | Value |
| --- | --- | --- |
| A | @ | 185.199.108.153 |
| A | @ | 185.199.109.153 |
| A | @ | 185.199.110.153 |
| A | @ | 185.199.111.153 |
| CNAME | www | apoorvraj429-design.github.io |

These records apply to the GitHub Pages publication route, not the private review site's generated address. Enter the actual owned domain in GitHub; no placeholder CNAME file has been committed.

## 6. Create a domain email

If using Cloudflare Email Routing, the domain must use Cloudflare DNS. Onboard it under Email Service > Email Routing, review its generated mail records, add and verify your destination inbox, then create an alias such as founder@YOUR_OWNED_DOMAIN. Test from a different email account and confirm delivery. Keep any existing mail service in mind before changing MX records.

Routing forwards incoming mail. It does not by itself configure your usual inbox to send replies from the custom address. Configure a sending service or mailbox separately if you need that. You can forward to Gmail while providing the verified domain address where the application requests a company email.

## 7. Finish the business facts

Record your real project start date, legal status, team, funding, users, revenue and prior Anthropic credits. If a mandatory form field cannot be answered truthfully, check eligibility through the program's official support route. A public repository without a licence is not yet licensed open source. Choose a licence only after checking rights to the code and assets.

## 8. Apply

Open https://claude.com/programs/startups and follow its Apply link to the official Console. Review the current benefits and requirements. Use the drafts in APPLICATION_COPY.md, adapt them to the actual fields and fill all factual gaps. Preview every answer, submit once when accurate, and retain the confirmation. No form was submitted as part of this work.

## 9. Build the promised next step

Use CLAUDE_PLAN.md to implement one evidence-linked briefing workflow. Measure it against approved records and review failures before introducing live operations. Update the website and application description only as those capabilities become real.

## Sources checked

- Current program: https://claude.com/programs/startups
- Terms: https://www.anthropic.com/startup-program-official-terms
- GitHub publication: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
- Custom domain: https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site
- Email routing: https://developers.cloudflare.com/email-service/get-started/route-emails/
- Email capabilities: https://developers.cloudflare.com/email-service/reference/faq/
