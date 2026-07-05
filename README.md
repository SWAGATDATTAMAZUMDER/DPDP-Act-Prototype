# DPDP Act — Consent & Children's Data Prototype (YouTube India)

A clickable, happy-path prototype designed as part of the **Vedantu Product Management Intern** hiring assignment.

This prototype reimagines how **YouTube India** could handle **verifiable parental consent and data minimisation for under-18 users**, in line with India's **Digital Personal Data Protection (DPDP) Act, 2023**.

## 🔗 Links

- **Live prototype:** [Deployed App Link](https://dpdp-act-prototype.vercel.app/)
- **Product Thinking Deck:** [View Here](https://docs.google.com/presentation/d/1w0cazeMrf0Ii417DtERFW7bJJAXAIiJdJVLTLByG4QA/edit?slide=id.p1#slide=id.p1)

## 🧭 What this prototype covers

An end-to-end, happy-path walkthrough of:

1. **Signup** — user enters name, date of birth, and contact details
2. **Age detection** — if under 18, a parent/guardian is required
3. **Parent verification** — OTP-based verification of the parent
4. **Consent preferences** — granular, off-by-default toggles for personalised recommendations, watch history storage, and ad targeting
5. **Confirmation** — account activates in a safe, "Supervised" mode
6. **Family Dashboard** — parents can review or adjust consent anytime

Key product logic baked into the prototype:
- Users under 18 **cannot** have ad targeting enabled under any circumstance.
- Users 18 and older get ad targeting **on by default**, with the ability to turn it off.
- All entered details (name, consent choices, date) flow dynamically through the rest of the experience rather than being hardcoded.

## 🛠️ Tech

Single-file static prototype — plain **HTML, CSS, and JavaScript**, no build step or dependencies. Deployed on **Vercel**.

## ▶️ Running locally

Clone the repo and open `index.html` directly in any browser:

```bash
git clone https://github.com/SWAGATDATTAMAZUMDER/DPDP-Act-Prototype.git
cd DPDP-Act-Prototype
```

Then double-click `index.html`, or serve it locally:

```bash
npx serve.
```

## 📝 Note

This is a **conceptual, happy-path-only prototype** built for a product-thinking exercise; it is not affiliated with or representative of YouTube's actual product or policies. Edge cases (declined consent, consent expiry, erasure requests, etc.) are addressed in the accompanying deck but not built into this clickable flow.
