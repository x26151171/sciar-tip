1. Link:

https://x26151171.github.io/sciar-html/

https://github.com/x26151171/sciar-html/tree/main

2.My Question:

How can a mobile staff view surface hidden post-23:00 point rules and private concern traces while protecting individual colleague privacy and owner/visa sensitivities?

3. Parts 1 and 4a to 4c:

Part 1: The people

**Internal stakeholder (Aoife Rennick, Sciar CEO):** Needs a phone-first alpha for Friday's investors that avoids scaring off restaurant owners (`"Make it work on a phone"`, `"owners will run a mile"`, `04-aoife.md`).
**External stakeholder (Rafael, Halloran's kitchen porter):** Needs clear payout visibility and safe escalation without risking his job or visa support (`"i dont understand how they count it"`, `"he is good to me with my visa letter"`, `01-rafael.md`).
**Accessibility / language:** Plain English and simple mobile cards address Rafael's broken screen and non-native English (`"my phone screen is broken so i cannot read the page good"`, `01-rafael.md`), changing `app.html` to use large tap targets, short labels, and clear hour/point arithmetic.

Part 4a: Theory behind the build

Applying **French and Raven's (1959)** bases of power, Halloran's management holds legitimate, reward, and coercive power—including Declan's role in Rafael's `"visa letter"` (`01-rafael.md`) and control over the split formula (`02-declan.md`). This explains why Rafael accepted Niamh's reply (`"is the system, is fair for everybody"`, `01-rafael.md`) as his post-23:00 hours rose in weeks 9–12 (`payouts.csv`, `staff_id = "S12"`), though power theory misses how software defaults encode rules automatically.
Through **Schein's (2010)** levels of culture, Halloran's espoused value is `"100% of tips go to the team"` (`02-declan.md`), yet the underlying assumption is that `"tips are earned on the floor"` (`02-declan.md`), encoded via a 0.25 kitchen-porter weight and zero points after 23:00 (`README.md`). Meanwhile, **Morrison and Milliken's (2000)** organisational silence explains why Niamh saw zero complaints (`03-niamh.md`) while Rafael feared speaking up (`01-rafael.md`).
Surfacing each user's own counted versus post-23:00 hours in `app.html` exposes that hidden rule without a public complaints wall. For Sciar's competitive advantage, verifiable transparency differentiates Sciar from opaque legacy pools, though it creates friction with owners preferring hidden splits (`02-declan.md`, `04-aoife.md`). One limit of these theories is that neither models statutory employment law or SaaS pricing incentives.

Part 4b: Decision record

**Decision 1 — Changed request (hiding the split rule from staff, `02-declan.md`, `04-aoife.md`):**
- **Options:** Hide the rule completely; publish everyone's pay; show each user's own formula/post-23:00 breakdown plus role averages only for groups of three or more.
- **Criteria:** Data verifiability, individual privacy, and avoiding floor disputes.
- **What decided it:** Showing personal calculations plus three-plus-staff role averages answers Rafael's confusion (`01-rafael.md`) while serving Declan's underlying need to stop staff `"counting each other's hours"` (`02-declan.md`) by hiding peer pay and one- or two-person roles.
- **What would have changed my mind:** Verified evidence that showing personal formulas breaches privacy or causes documented harm.
**Decision 2 — Rejected AI suggestion (using `05-market-scan.md` claims on `index.html`):**
- **Options:** Include `"34% longer"` retention and `"only tip platform fully compliant"` (`05-market-scan.md`); use only figures reproducible from `data/`.
- **Criteria:** Auditability and zero unverified claims.
- **What decided it:** `05-market-scan.md` attached no sources, whereas `takings.csv` (`n = 72`) and `payouts.csv` (`n = 152`) verify the €31,754.13 pool.
- **What would have changed my mind:** Primary, verifiable sources supporting those statistics.
**Bias caught:** Early in the session, I showed automation bias by accepting an AI assumption that `payouts.csv` was empty and that external script paths would load automatically, until checking the files and browser screenshot forced direct verification.

Part 4c: The Struggle, without AI

In the beginning, I developed the two web pages in two repositories, but later put them into one repository named ‘sciar-html’ (commit `ed9cacd53b9c670940ecaff0571f71e6c03c44e9`). Also, while using Gemini to build the ‘app—html’ website, the web page failed to display staff names because it could not access ‘payouts.js’. I found the problem and asked Gemini to fix it first. Therefore, I plan to read the assignment instructions more carefully in the future to speed up my workflow. I spent quite of time setting up and uploading the files to GitHub this time (commit `908c16028d25135637ae8628befdde7970dbcbd2`); however, through this exercise, I am sure that I will be more confident and efficient in future tasks.




   
