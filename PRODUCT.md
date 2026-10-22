# Product

<!-- impeccable:product-schema 1 -->

## Platform

web

## Users

Egyptians buying a home or an investment unit inside Egypt, from Greater Cairo (New Cairo, the New Capital, Sheikh Zayed, 6th of October, Maadi, Mostakbal City) to the coast (North Coast, Ain Sokhna). They are comparing compounds, developers, prices and payment plans, usually on a phone, often in Egyptian Arabic, and they want a person they can trust before they commit a down payment. The site is buyer-only: there is no seller or listing-owner side.

## Product Purpose

Lynkers Real Estate Consultancy helps a buyer find the right unit and buy it with confidence. The site lets them search in their own words, browse areas and compounds down to individual units, compare up to three units, check what their budget can buy, see newly launched projects at launch prices, and reach a consultant on WhatsApp or by phone at any point. Success is a qualified conversation with a Lynkers consultant that ends in a viewing and a purchase.

## Positioning

A real Lynkers consultant stays with the buyer from the first search to handover, backed by tools that do the homework: natural-language search, side-by-side comparison, a live budget calculator, area guides and launch price lists. Listing portals give inventory; Lynkers gives inventory plus a named advisor and the reasoning behind each recommendation.

## Operating Context

- Buyers move between the site and WhatsApp; every unit, compound, launch and lead form hands off to a WhatsApp message or a phone call.
- The path mirrors how Egyptian buyers shop: area → sub-area → compound → unit, with launches as a separate track.
- Linky, the site's chatbot character, suggests units, answers simple questions and nudges the visitor toward a consultant.

## Capabilities and Constraints

- Single static page (`index.html`), Arabic right-to-left, no build step. Pages are hash routes: `#about`, `#blog`, `#area/<id>`, `#project/<name>`, `#releases`, `#releases/<developer>`.
- Features: AI-style search, unit filters and sorting, favorites, recently viewed, compare (up to 3), budget calculator, map with a globe intro, area pages, compound pages, launches page, blog, about page, sign-in/sign-up with a one-time code, lead forms.
- Accounts, one-time codes, favorites and leads are demo-only and live in the browser's localStorage; the code is shown on screen. A real backend (SMS provider, lead storage, CRM) is still to be decided.
- Contact: WhatsApp and phone +20 110 332 2887, info@lynkers.net, Facebook page facebook.com/lynkers.realestate.

## Brand Commitments

- Name: Lynkers Real Estate Consultancy (لينكرز). The mark is the white Lynkers check-mark cut from the Facebook logo (`assets/logo-mark.png`); the wordmark is set in Cormorant Garamond.
- Brand colors come from the logo: navy #13294b, sage #cfd9d5, coral #e8604c, sand #e6dcae.
- Voice: friendly, plain Egyptian Arabic in the interface ("لاقي بيتك", "كلّم مستشار"), never salesy or loud.
- Linky the robot (port of the 404 Creative bot, recolored to Lynkers) is part of the brand; it stays mostly still and calm.
- Inspired by the layout of Nawy and The Village Investment, but must not copy their content, images or logos.

## Evidence on Hand

- Real: company name, logo mark, phone/WhatsApp number, email, Facebook page.
- Demo only, clearly labeled in the footer: all units, compounds, launches, prices, payment plans, developer names, presenter videos (Mixkit) and photos (Unsplash).
- Area guides list real Egyptian places (hospitals, malls, universities, roads) written from general knowledge; they are marked as guidance and need review.
- Not available yet, must not be invented: board member names and photos, Instagram/TikTok/LinkedIn links, real developer logos, testimonials, sales figures.

## Product Principles

1. The consultant is the product; every screen should make reaching one a single tap away.
2. Show the numbers honestly: price, down payment, years and monthly installment are always visible together, and demo or estimated values say so.
3. Follow the buyer's own path (area, sub-area, compound, unit) instead of forcing a search form first.
4. Calm beats loud: trust comes from clarity and restraint, not from urgency tricks.

## Accessibility & Inclusion

Arabic-first and right-to-left throughout. Text must meet WCAG AA contrast (4.5:1 for body text), motion respects `prefers-reduced-motion`, and the site must work fully at phone width (375px) without horizontal scrolling.
