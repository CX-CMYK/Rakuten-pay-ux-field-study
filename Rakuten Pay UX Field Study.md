# Rakuten Pay in the Wild: A Field Observation Study

**Author:** Jingshi Xiao — Waseda University, MSc Architecture (expected Sept 2027)
**Date:** October 2026
**Status:** Independent, self-initiated study conducted as part of my application preparation. Not affiliated with or commissioned by Rakuten Group.

## 1. Why I Did This

I am trained as an architect, and my research method has always been the same: observe people on site, define the real problem, then design. Before applying to Rakuten Payment as a Product/Project Manager, I wanted to practice that method on the product itself rather than talk about it abstractly. Payment is the "last meter" of everyday behavior — so I went to the last meter and watched.

## 2. Method

- **Sites:** 4 retail locations around Waseda University, Tokyo (FamilyMart, Monster's Kitchen, Kodawari Shoten, AEON), plus the official Rakuten Pay store-coverage map and a first-person onboarding test of the Rakuten Pay app.
- **Approach:** Direct observation of checkout flows, photo/sketch notes, an informal conversation with a store owner, and a full self-observed onboarding attempt (credit-card linking) on a Xiaomi Android device.
- **Lens:** My own user profile — Chinese native, near-native English, weak Japanese, 158 cm tall. Where my profile shapes the finding, I say so explicitly.
- **Limitations:** Small sample, single observer, one evening. Findings are hypotheses for validation, not statistics.

## 3. Findings

### A. Brand visibility: strong in the list, weak in the noise (FamilyMart)

Rakuten's crimson and "R" logo are genuinely distinctive within the payment-method list (first row, clean and elegant). However, the Rakuten Pay sticker on the checkout screen's upper-right corner escaped my first-time notice: Japan's dense advertising text burying it, and the d-point logo's visual similarity (similar color family and typeface) made the two hard to distinguish at a glance.

**Insight:** Rakuten Pay's brand strength works inside a list but fails inside environmental noise.

### B. Checkout flow: the ecosystem gate (FamilyMart, AEON)

At FamilyMart, the first screen promotes FamilyPay (the retailer's own app); Rakuten Pay appears only on the second screen, after tapping "I don't have FamilyPay," alongside d-point and other point cards. At AEON, WeChat Pay and Alipay were discontinued this year while AEON Pay remains — and I had misremembered Rakuten Pay as accepted there. My own memory error is itself evidence: ecosystem walls create user confusion about what works where.

**Insight:** Before users meet Rakuten Pay, retail ecosystems intercept them once. The competition is not between payment apps but between walled ecosystems.

### C. Small merchants: the physical bottleneck of QR codes (Monster's Kitchen)

So many payment QR stands (Rakuten Pay, PayPay, WeChat Pay, etc.) crowd the counter that they overlap; the cashier had to physically dig out the Rakuten Pay stand before I could scan it.

**Insight:** The cost of payment-method abundance is transferred to the cashier's hands. This friction is invisible to surveys and analytics — it only shows up if you stand at the counter.

### D. A counterexample of good placement (Kodawari Shoten)

Here the Rakuten Pay QR code sits right beside the price display, at my natural eye level — no crouching, no stretching. The owner told me the store adopted Rakuten Pay five years ago, and that besides QR mode there is a terminal mode (in use at the diner across the street). Compare FamilyMart, where the Rakuten Cash card rack sits so low that at 158 cm I had to squat to see it, while PlayStation / Apple / Google top-up cards occupied the eye-level slots.

**Insight:** The difference between good and bad payment UX here is not technology — it is placement ergonomics.

### E. Onboarding for foreign users: failure at step one (self-test on the app)

- App language follows the OS only; no Chinese; the translation feature is marked beta. Switching my whole phone to English froze the device, after which the Rakuten Pay app rendered a blank homepage; only tab navigation partially worked.
- Flows that jump to external web pages lose the language context and revert to Japanese.
- Credit-card linking, as a foreign user, was troublesome enough that I gave up for the night.
- Positive note: screenshot blocking shows privacy protection is taken seriously.

**Insight:** For exactly the user profile Rakuten most wants to attract (international residents with limited Japanese), onboarding fails before the first payment. I could not complete card linking in one evening — that is a lost conversion, with a face on it.

### F. Coverage (reference)

From Rakuten Pay's official store map, roughly 40% of shops near the Waseda campus accept Rakuten Pay (my visual estimate, not a measured statistic).

## 4. From Observations to Proposals

| # | Observation | Proposal | Validation KPI |
|---|---|---|---|
| 1 | Placement ergonomics vary wildly (C vs D) | Placement guide for merchants: QR at 1.4–1.6 m eye height, adjacent to the price display | Scan completion time; cashier interventions |
| 2 | Overlapping QR stands at small merchants (C) | Consolidated multi-code stand / counter-top standard | Checkout duration per transaction |
| 3 | Sticker lost in ad noise; d-point similarity (A) | Visual differentiation from d-point + sticker placement guideline | First-time user identification rate |
| 4 | Foreign-user onboarding failure (E) | In-app language setting independent of OS; simplified foreign-card linking | Card-linking completion rate for foreign users |
| 5 | Ecosystem interception (B) | Not an "improvement item" — a strategic constraint. A PM must distinguish what we can change from what we cannot | — |

Item 5 is deliberate: FamilyMart prioritizing FamilyPay is their right. Maturity in product work includes knowing which friction is not ours to fix.

## 5. What I Would Do Next

- Repeat the observation at more store types (terminal-mode merchants, station kiosks).
- Recruit 3–5 other foreign students to reproduce the onboarding test; measure completion rate instead of relying on my single story.
- Interview one cashier about QR-stand handling as a daily workflow problem.

## 6. Closing Note

This study is my application of an architect's method — observe, define, design — to a payment product. The most valuable lesson: the biggest UX problems I found were not on any screen. They were at the height of a QR stand, in the reach of a cashier's hand, and in a sticker drowned by advertising. I solve problems by watching people first.
