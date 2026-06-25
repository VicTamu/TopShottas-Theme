# Top$hottas — Website Revamp Checklist

Goal: turn the store from "good paint on a thin frame" into a convincing,
converting storefront that mirrors the app. Everything below stays
Shopify/Dawn-native (theme sections, settings, metafields, first-party apps)
so the theme editor and future updates never fight us.

Priority key: **P0** = launch blocker · **P1** = high impact · **P2** = nice-to-have

---

## 1. Brand & design (this project's design passes)

- [ ] **P1 — Rebuild the hero.** Replace the tee photo (which collides the
      wordmark 3×) with the smoke background (`TS-Smoky1.mp4` / `thick-white-smoke.jpg`).
      One strong headline, one CTA. Dawn: Image/Video banner section + our glass overlay.
- [ ] **P1 — Make the glass material pay off.** Once smoke sits behind sections,
      `.ts-glass` cards/blocks finally read as glass. Apply `.ts-glass` to hero meta,
      featured cards, newsletter.
- [ ] **P1 — Kill the duplicate tagline.** Hero and "Loud presence." currently say
      the same thing. Keep one, rewrite the other (or cut it).
- [ ] **P2 — Editorial hero meta** (eyebrow pill + stat chip) to match app `heroCard`.
      Use `.ts-pill`. Small custom section or Dawn banner blocks.
- [ ] **P2 — Confirm corner radius / button strength** (16px corners, translucent CTA)
      read the way you want vs. the app.
- [ ] **P2 — Custom 404 + cart-empty states** styled like the app's info cards.

## 2. Content density (the store looks empty)

- [ ] **P0 — Add real products.** One product reads as "not open." Even 4–8 SKUs
      (or variants/colorways) changes perception. Shopify: Products admin.
- [ ] **P1 — Featured collection as a carousel/grid** instead of a single product.
      Dawn: Featured collection section (slider mode).
- [ ] **P1 — Collections** (e.g. Tees, Hoodies, New, Sale) for browsing + nav.
      Shopify: Collections (smart/manual) → add to header menu.
- [ ] **P2 — "Lookbook"/collage section** for lifestyle imagery. Dawn: Collage / Multicolumn.
- [ ] **P2 — Brand story / About section** (the app has voice; the site has none).

## 3. Conversion (CRO)

- [ ] **P0 — Strong, visible primary CTA** above the fold ("Shop the drop" → collection).
- [ ] **P1 — Product page essentials:** multiple images, size guide, clear variants,
      sticky/obvious Add-to-Cart. Dawn: product media gallery + blocks.
- [ ] **P1 — Trust signals near ATC:** shipping/returns blurb, secure-checkout note.
      Dawn: product "collapsible content" + icon-with-text blocks.
- [ ] **P1 — Product reviews / social proof.** App: **Judge.me** (free tier) or
      **Shopify Product Reviews** alternative; shows stars on cards + PDP.
- [ ] **P1 — Cart drawer with progress to free-shipping threshold.** Dawn cart drawer +
      a shipping-bar (free apps) or manual goal text.
- [ ] **P1 — Enable Shop Pay / Accelerated checkouts + express buttons.**
      Shopify: Settings → Payments.
- [ ] **P2 — Product recommendations** ("You may also like"). Dawn has this natively
      via Shopify **Search & Discovery** app (free, first-party).
- [ ] **P2 — Urgency/scarcity** done tastefully (low-stock text, drop countdown).
- [ ] **P2 — Quick-add to cart** from collection cards. Dawn: card quick-add setting.

## 4. Retention (bring them back)

- [ ] **P1 — Email capture that works.** Footer signup already there; wire it to
      **Shopify Forms** (free) + a welcome offer (e.g. 10% first order).
- [ ] **P1 — Abandoned-checkout + welcome automations.** Shopify: **Marketing →
      Automations** (free templates) and **Shopify Email** (free up to 10k/mo).
- [ ] **P1 — Customer accounts on.** Shopify: Settings → Customer accounts (new
      passwordless accounts). Enables order history + faster repeat checkout.
- [ ] **P2 — Post-purchase email flow** (thank-you, shipping, "rate your fit").
- [ ] **P2 — Loyalty / referral** once volume justifies (Smile.io free tier, etc.).
- [ ] **P2 — Back-in-stock alerts** for sold-out drops (free app tiers exist).

## 5. Traffic & acquisition

- [ ] **P1 — On-page SEO.** Per product/collection: title tag, meta description,
      descriptive alt text on all images. Shopify: each resource's "Search engine listing."
- [ ] **P1 — Social links wired** (Instagram/TikTok) in theme settings + footer.
      Shopify: Theme settings → Social media. (Currently all blank.)
- [ ] **P1 — Performance pass.** Compress hero video/images (smoke .mp4 is large),
      keep Lighthouse/Shopify speed score healthy. Lazy-load is already on in Dawn.
- [ ] **P2 — Blog / drops journal** for SEO + storytelling. Shopify: Blog posts.
- [ ] **P2 — Meta/TikTok pixel + sales channels** (Shopify: Settings → Apps and
      sales channels → Facebook & Instagram, TikTok) for retargeting.
- [ ] **P2 — Shareable preview / Open Graph image** so links look good when shared.

## 6. Operational / launch-blockers (must-do before publishing)

- [ ] **P0 — Payments configured & test order placed.** Settings → Payments.
- [ ] **P0 — Shipping rates set** (zones, rates, free-ship threshold). Settings → Shipping.
- [ ] **P0 — Taxes configured.** Settings → Taxes and duties.
- [ ] **P0 — Legal policies** (Refund, Privacy, Terms, Shipping). Settings → Policies
      (Shopify can generate templates) → link in footer.
- [ ] **P0 — Contact method** (working Contact Us page / form + a real email).
- [ ] **P0 — Custom domain connected** + remove storefront password when ready to launch.
- [ ] **P1 — Notifications branded** (order/shipping emails). Settings → Notifications.
- [ ] **P1 — Favicon + social share image set** in theme settings.

## 7. Measurement (so we know it's working)

- [ ] **P1 — Shopify Analytics baseline** (sessions, conversion rate, AOV) reviewed.
- [ ] **P1 — Google Analytics 4** connected (Shopify: Google & YouTube channel).
- [ ] **P2 — Track funnel** (add-to-cart → checkout → purchase) to spot drop-off.

---

### Suggested sequencing
1. **P0 content + operational** (products, payments, shipping, policies) — without these,
   design improvements convert nobody.
2. **Hero rebuild + content density** (P1 design) — fixes the worst first impression.
3. **Conversion essentials** (reviews, trust, Shop Pay, recommendations).
4. **Retention + acquisition** (email automations, SEO, social, pixels).
5. **Measurement** running throughout.
