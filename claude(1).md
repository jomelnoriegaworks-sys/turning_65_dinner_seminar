# Turning 65 Dinner Seminar — Claude Build Spec

## Goal
Build a short, polished, conversion-focused landing page for Tracy Davis Insurance promoting a Turning 65 Medicare dinner seminar. Primary goal: get qualified prospects to register.

Build in VS Code with plain HTML/CSS, then move into GoHighLevel (GHL).

Keep it short, informational, trustworthy, intentional, mobile-first, accessible, and Medicare-compliant. Do not overbuild.

## Event
**Turning 65 Dinner Seminar**

Dates:
- Tuesday, September 8, 2026 — 5:30 PM
- Thursday, September 17, 2026 — 5:30 PM

Location:
**Arni's Crawfordsville**
114 W Wabash Ave
Crawfordsville, IN 47933

No maximum attendee limit specified.
No registration deadline specified.

## Form Fields
Collect only:
1. Full Name
2. Phone Number
3. Email Address
4. Preferred Seminar Date

Date choices:
- Tuesday, September 8
- Thursday, September 17

After signup:
- Show a simple thank-you/confirmation page or state.
- Send SMS confirmation through GHL.
- Use a GHL-ready form. Do not hardcode a third-party form provider.

## Page Structure

### 1. Hero
Answer immediately: what, who, when, where, and what to do.

Suggested headline:
**Turning 65? Get Ready for Medicare With Confidence.**

Supporting copy:
Join us for a complimentary dinner seminar designed to help people approaching Medicare understand their options and prepare for the decisions ahead.

Show:
- September 8 or September 17
- 5:30 PM
- Arni's Crawfordsville

Primary CTA:
**Reserve My Seat**

CTA should scroll to the registration form.

### 2. Why Attend
Keep concise:
- Understand the Medicare enrollment process
- Learn about different types of Medicare coverage
- Understand important decisions to consider when approaching 65
- Get questions answered in a relaxed dinner setting

Do not promise savings, specific benefits, or guaranteed outcomes.

### 3. Event Details
Clearly display:
- Turning 65 Dinner Seminar
- Tuesday, September 8 — 5:30 PM
- Thursday, September 17 — 5:30 PM
- Arni's Crawfordsville
- 114 W Wabash Ave, Crawfordsville, IN 47933

### 4. Registration
Heading: **Reserve Your Seat**

Copy:
Choose the date that works best for you and we'll confirm your registration by text.

Fields:
- Full Name
- Phone Number
- Email Address
- Preferred Seminar Date

Button:
**Reserve My Seat**

### 5. Reassurance
Keep short:
**Clear information. No pressure.**

The seminar is designed to provide educational information to help people better understand Medicare as they approach age 65.

Do not invent credentials, testimonials, ratings, awards, carrier relationships, or legal claims.

### 6. Final CTA
**Ready to take the next step toward understanding Medicare?**

Choose your seminar date and reserve your seat.

CTA: **Reserve My Seat**

### 7. Footer
Minimal. Use Tracy Davis Insurance branding if available. Leave a clear area for any compliance disclaimer Tracy later provides.

## Brand / Visual Direction
Reference the existing website when accessible:
https://www.tracy-davis-insurance.com/

If the project contains the actual logo, inspect it and derive the color palette from it. Do not invent brand colors when actual assets are available.

Design should feel:
- Professional
- Trustworthy
- Warm
- Local
- Modern
- Clean

Avoid:
- Loud gradients
- Neon colors
- Excessive blue
- Excessive shadows
- Glassmorphism
- Generic insurance-template styling
- Heavy animation

Use a restrained palette with one strong primary CTA color and accessible contrast.

## Typography
Use a polished modern sans-serif system:
- Strong heading font
- Highly readable body font
- Semibold CTA text

Prefer no more than two font families. Use system fonts if that makes GHL integration simpler.

Prioritize clear hierarchy, comfortable line-height, large mobile-friendly type, short paragraphs, and intentional spacing.

## UI / UX
- Mobile-first
- Content width around 1100–1200px
- Generous whitespace
- Clear visual hierarchy
- Registration form visually prominent
- Large mobile-friendly CTA
- Visible focus states
- Proper form labels
- Keyboard accessible
- Sufficient color contrast
- No reliance on color alone
- Respect reduced-motion preferences

Conversion principle: every section should naturally move the visitor toward **Reserve My Seat**.

## GHL Compatibility
Use only:
- Semantic HTML
- Plain CSS
- Vanilla JS only if genuinely necessary

Do NOT use React, Next.js, Vue, Angular, Tailwind runtime, npm packages, UI frameworks, or build tools.

Code must work with GHL Custom HTML and Custom CSS.

Add a clear placeholder:

<!-- GHL FORM EMBED / FORM ELEMENT GOES HERE -->

Do not build a fake form that appears functional but is not connected to GHL.

Keep CSS organized and namespaced where practical to reduce GHL conflicts.

## Content / Compliance Rules
Tone: friendly, calm, professional, educational, helpful, local.

Avoid fear-based Medicare marketing.

Do not claim:
- Guaranteed savings
- Guaranteed benefits
- Guaranteed eligibility
- Guaranteed approval
- Specific plan superiority
- "Best plan"
- Unverified "free Medicare" claims
- Fake urgency

Do not create fake testimonials, trust badges, statistics, awards, or credentials.

The goal is to make registration feel like an easy, useful next step.

## Funnel
Facebook Ad
→ Landing Page
→ Visitor selects seminar date
→ Form: Name / Phone / Email / Preferred Date
→ GHL contact created or updated
→ SMS confirmation
→ Thank-you page

Existing GHL domain:
**solutions.tracydavisinsurance.com**

Recommended path:
**/turning-65-dinner**

Target URL:
https://solutions.tracydavisinsurance.com/turning-65-dinner

## Deliverables
Create:
- index.html
- styles.css
- script.js only if genuinely necessary

The page should look complete in VS Code and require minimal changes when moved into GHL.

## Final Review
Before finishing, verify:
- Visitor understands the offer within 5 seconds
- Dates/time are obvious
- Location is obvious
- CTA is prominent and convincing
- Form is low-friction
- Mobile layout is intentional
- Typography and spacing are polished
- Colors match/complement the actual logo
- No unsupported claims
- No unnecessary sections
- No fake testimonials or trust signals
- No excessive animation
- GHL form placeholder is clear
- HTML/CSS transfers cleanly to GHL
- Accessibility basics are covered
- Page feels like a real local Medicare seminar, not a generic template

## Final Principle
**Clarity over complexity.**
Every section should help the visitor understand the seminar, trust the offer, and confidently reserve a seat.
