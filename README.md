<h1 align="center">Wajahat Hassan</h1>

<p align="center">
  Senior iOS Engineer · Indie iOS Maker · Full-Stack Contributor<br/>
  8+ years shipping mobile products across the UK, UAE, and Pakistan.
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/wajahat-hassan-ios/">LinkedIn</a> ·
  <a href="mailto:wajahathassan64@gmail.com">Email</a> ·
  <a href="https://api.whatsapp.com/send?phone=+923101015199">WhatsApp</a> ·
  <a href="https://www.spendmind.co">SpendMind</a> ·
  <a href="./assets/resume.pdf">Resume (PDF)</a>
</p>

---

## About

I'm a senior iOS engineer with 8+ years of experience shipping production apps used by **millions** of customers across fintech, digital banking, and consumer products. I've worked with **SadaPay**, **YAP**, **EDB Business Banking**, and now **Bazaar Technologies**, building features that move money, process transactions at scale, and make life simpler.

I'm deep in **Swift**, **SwiftUI**, and clean architectures (MVVM, MVVM-C, VIPER), with strong fundamentals in **TDD**, **CI/CD**, modular design, and **RxSwift**. At Bazaar, I've expanded into full-stack — contributing on **Android (Jetpack Compose)** and **backend** services alongside iOS.

In parallel, I ship my own indie product, **[SpendMind](https://www.spendmind.co)** — an AI-powered, voice-first expense tracker, built solo and live on the App Store.

**Core stack** · `Swift` `SwiftUI` `Objective-C` `RxSwift` `Combine` `Kotlin` `Jetpack Compose` `MVVM` `MVVM-C` `VIPER` `Modular Architecture` `TDD` `CI/CD` `GitHub Actions` `Bitrise` `Core ML` `CloudKit` `StoreKit 2` `WidgetKit`

---

## Featured Projects

### [SpendMind — AI Expense Tracker](https://apps.apple.com/us/app/spendmind-ai-expense-tracker/id6754249390)
**Solo indie build · Live on the App Store · [spendmind.co](https://www.spendmind.co)**

SpendMind is a voice-first, AI-powered expense tracker. Users speak naturally — *"Spent $12 on coffee today"* — and AI instantly extracts the amount, category, and date. Designed for busy professionals, freelancers, and anyone who wants to log expenses in seconds, not minutes.

<p align="center">
  <img src="https://github.com/wajahathassan64/portfolio/blob/main/assets/spendmind1.jpg" width="230" title="Voice-first home dashboard" />
  <img src="https://github.com/wajahathassan64/portfolio/blob/main/assets/spendmind2.jpg" width="230" title="AI-categorised onboarding" />
  <img src="https://github.com/wajahathassan64/portfolio/blob/main/assets/spendmind3.jpg" width="230" title="Expense analytics" />
</p>
<p align="center">
  <img src="https://github.com/wajahathassan64/portfolio/blob/main/assets/spendmind4.jpg" width="230" title="AI chat assistant" />
  <img src="https://github.com/wajahathassan64/portfolio/blob/main/assets/spendmind5.jpg" width="230" title="On-device receipt scanner" />
  <img src="https://github.com/wajahathassan64/portfolio/blob/main/assets/spendmind6.jpg" width="230" title="Recurring expenses" />
</p>

**My role — Solo founder & engineer**
- Designed, built, and shipped SpendMind end-to-end as a one-person team — from product design and onboarding flows to AI parsing, payments, and App Store launch.
- Built a **voice-to-expense pipeline** that captures speech, transcribes it, and uses LLM parsing to extract amount, category, and date with high accuracy across **50+ languages**.
- Shipped an **AI Chat Assistant** with continuous voice-conversation mode — users can ask "How much did I spend on food last month?" and get a spoken answer back.
- Built an **on-device Receipt Scanner** using VisionKit / Apple Vision OCR with multi-page document support and auto-capture — no internet required, no data leaves the device.
- Implemented **iCloud Sync via CloudKit** with runtime activation, account-state feedback, and seamless multi-device sync (iPhone, iPad, Mac).
- Built a **Home Screen Widget** with WidgetKit and a **subscription model** with StoreKit 2 (monthly $9.99 / yearly $69.99) with restore-purchase, free-trial logic, and entitlement enforcement.
- Set up **recurring expenses**, **localized onboarding**, **CSV export**, **daily reminder notifications**, and a **privacy-first architecture** with zero data collection.

**Stack** · `Swift` `SwiftUI` `Swift Concurrency` `CloudKit` `VisionKit` `Apple Speech` `StoreKit 2` `WidgetKit` `Core ML` `AI / LLM APIs`

**Highlights**
- Live on the **App Store** with paid subscriptions and active users.
- Supports **50+ languages** and **50+ currencies** out of the box.
- **Zero-data-collection** privacy posture, validated on the App Store privacy nutrition label.
- Universal app — works on iPhone, iPad, Apple Vision, and Mac.

---

### [Bazaar — Grocery Delivery](https://apps.apple.com/us/app/bazaar-grocery-delivery/id6741764524)
**Bazaar Technologies · Senior iOS Engineer with cross-platform & backend contributions**

Bazaar is Pakistan's leading online grocery delivery app, serving households and businesses across Karachi, Lahore, Islamabad, and more. **5,000+ products** across 30+ categories, next-day delivery, and a 4.5-star rating on the App Store.

<p align="center">
  <img src="https://is1-ssl.mzstatic.com/image/thumb/Purple211/v4/3d/e0/38/3de0380a-a20f-9a37-6021-ce2938fedcff/AppIcon-0-0-1x_U007ephone-0-1-0-85-220.jpeg/512x512bb.jpg" width="120" alt="Bazaar app icon" />
</p>

<!-- Add 3 screenshots here:
<p align="center">
  <img src="https://github.com/wajahathassan64/portfolio/blob/main/assets/bazaar1.png" width="230" />
  <img src="https://github.com/wajahathassan64/portfolio/blob/main/assets/bazaar2.png" width="230" />
  <img src="https://github.com/wajahathassan64/portfolio/blob/main/assets/bazaar3.png" width="230" />
</p>
-->

**My role — Senior iOS Engineer (hired) → Full-stack contributor**

I was hired as a Senior iOS Engineer to build Bazaar's consumer iOS app, and have since expanded into **Android** and **backend** contributions as the team has needed full-stack help shipping features end-to-end.

- **iOS app development** — built the consumer iOS app from the early stages, including the home, search, cart, checkout, order tracking, payments, loyalty, and wallet flows.
- **Payments integration** — integrated **JazzCash** and secure card-add via in-app web view, plus Apple Pay-style flows with session tracking and HTTPS hardening.
- **Loyalty & rewards** — shipped the loyalty linking/de-linking flow, OTP banner, points redemption, and the rewards list screen.
- **Cart & checkout** — multi-address management, delivery scheduling with on-time guarantee, voucher/discount engine (including free-delivery vouchers, percentage caps), and order rating with App Store review integration.
- **Discovery & personalization** — product tag filters, brand carousels, "People also bought" suggestions, saved shopping lists, recipe details with ingredients + how-to-make tabs, and seasonal/Ramzan campaigns (Lucky Draw, Eidi).
- **Back-in-stock + favorites** — built the back-in-stock notification flow and favorites carousel with category-aware tracking.
- **Cross-platform contributions** — pitched in on **Android (Jetpack Compose)** features as the team scaled, keeping parity with iOS.
- **Backend contributions** — extended **backend services** to support new client features (cart by ID, sponsored content tagging, voucher logic, device fingerprinting for security analytics).
- **Stability & analytics** — Braze analytics wiring, crash fixes (favorites, cart deeplinks, in-app updates), performance profiling, and shipping a v2.0 release with multi-address + notification hub.

**Stack** · `Swift` `SwiftUI` `UIKit` `Kotlin` `Jetpack Compose` `REST APIs` `Braze` `JazzCash SDK` `Google Places` `Modular Architecture`

**Highlights**
- **4.5 ★** on the App Store with **5,000+ SKUs** and growing user base across Karachi, Lahore, and Islamabad.
- Shipped a major **v2.0 release** with multiple-address management, notification hub, and a complete payments redesign.
- Owned cross-functional features that touched iOS, Android, and backend — true end-to-end shipping.

---

### [SadaPay — Money Made Simple](https://apps.apple.com/pk/app/sadapay-money-made-simple/id1543848524)
**Senior iOS Engineer · Card Squad**

SadaPay is a fee-free digital wallet and Mastercard virtual debit card, built for Pakistani consumers and freelancers. SadaBiz enables freelancers to receive international payments up to 900,000 PKR/month with competitive FX rates.

<p align="center">
  <img src="https://github.com/wajahathassan64/portfolio/blob/main/assets/sadapay1.PNG" width="230" />
  <img src="https://github.com/wajahathassan64/portfolio/blob/main/assets/sadapay2.PNG" width="230" />
  <img src="https://github.com/wajahathassan64/portfolio/blob/main/assets/sadapay3.PNG" width="230" />
</p>

**Key contributions**
- Built the **Card Ordering** flow end-to-end — a top revenue-generating feature for SadaPay.
- Designed and shipped **Transaction History** + improved **Transaction Details** with rich filtering and search.
- Customized the **main dashboard** with card tiles, transactions, and feature widgets.
- Automated **iOS CI/CD workflows** with GitHub Actions and Bitrise, introduced analytics event tracking, and streamlined API contracts across iOS/Android.
- Drove **extreme programming practices** on the squad — TDD, Trunk-Based Development, Ping Pong Programming, Mobbing.
- Migrated the iOS project to a **modular MVVM architecture** to unblock parallel squad development and stabilize the pipeline.

**Outcomes**
- **97% code coverage** via unit testing and **100% feature coverage** via UI testing.
- **35%** reduction in feature testing time with a micro-frontend approach.
- **20%** improvement in feature delivery time via CI/CD automation.
- **90%** reduction in QA dependency and **75%** faster delivery with structured UI test automation.
- **95%** reduction in iOS↔Android discrepancies; **100%** elimination of API contract mismatches.

**Stack** · `Swift` `MVVM` `Modular Architecture` `TDD` `Unit Testing` `UI Testing` `GitHub Actions` `Bitrise` `Kotlin Multiplatform (KMM)`

---

### [YAP — Your Digital Banking App](https://apps.apple.com/us/app/yap-your-digital-banking-app/id1498302242)
**Lead iOS Engineer — UAE**

YAP is a full-stack digital banking app in the UAE — 30-second signup, Mastercard debit, multi-currency, virtual cards, bill splitting, QR payments, and spending analytics.

<p align="center">
  <img src="https://github.com/wajahathassan64/portfolio/blob/main/assets/yap1.webp" width="230" />
  <img src="https://github.com/wajahathassan64/portfolio/blob/main/assets/yap3.webp" width="230" />
  <img src="https://github.com/wajahathassan64/portfolio/blob/main/assets/yap2.webp" width="230" />
</p>

**Key contributions**
- **Led the YAP iOS app** from inception — reached **1M+ customers** in year one, processing **millions of transactions** monthly.
- Designed the iOS project ground-up with **modular MVVM-C**, dependency containers, and **RxSwift** — enabling parallel feature development across teams.
- Built an **in-house KYC SDK** using iOS **Core ML** + Amazon ML, eliminating third-party fees and **reducing operational costs** significantly.
- Integrated **Promon Shielding SDK** for runtime app security and tamper detection.
- Led the **live support team**, clearing a **500-ticket backlog** in one week.

**Stack** · `Swift` `MVVM-C` `RxSwift` `Modular Architecture` `Core ML` `Amazon ML` `Promon`

---

### [EDB Business Banking](https://apps.apple.com/us/app/edb-business-banking/id1583562661)
**Senior iOS Engineer — UAE**

EDB's business banking app, serving multi-million businesses with multi-account management, transaction history, sub-accounts, local/international transfers, expense tracking, and role-based access.

<p align="center">
  <img src="https://github.com/wajahathassan64/portfolio/blob/main/assets/edb1.webp" width="230" />
  <img src="https://github.com/wajahathassan64/portfolio/blob/main/assets/edb2.webp" width="230" />
  <img src="https://github.com/wajahathassan64/portfolio/blob/main/assets/edb3.webp" width="230" />
</p>

**Key contributions**
- Led the iOS build of a business-banking app with **no minimum balance** account creation.
- Architected **modular MVVM-C** from the ground up for scalability and parallel team velocity.
- Integrated **Promon Shielding SDK** to harden app security.
- Shipped **local transfers**, **loan management**, **EID scanning** for onboarding, and **ATM/CDM map** support.
- Integrated **Core Data** for robust offline access to accounts and transaction history.

**Stack** · `Swift` `MVVM-C` `Coordinators` `RxSwift` `Modular Architecture` `Core Data` `EID Scanner`

---

### Revizer — ERP Financial Management
**iOS Engineer**

Revizer is a Financial Management module for an ERP system — real-time financial insights, budget management, expense tracking, AP/AR, GL management, and compliance-ready reporting.

<p align="center">
  <img src="https://github.com/wajahathassan64/portfolio/blob/main/assets/rv1.png" width="230" />
  <img src="https://github.com/wajahathassan64/portfolio/blob/main/assets/rv2.png" width="230" />
  <img src="https://github.com/wajahathassan64/portfolio/blob/main/assets/rv3.png" width="230" />
</p>

**Stack** · `Swift` `MVC`

---

## Contact

- **Email** — [wajahathassan64@gmail.com](mailto:wajahathassan64@gmail.com)
- **LinkedIn** — [Wajahat Hassan](https://www.linkedin.com/in/wajahat-hassan-ios/)
- **WhatsApp** — [+92 310 1015199](https://api.whatsapp.com/send?phone=+923101015199)
- **Indie product** — [spendmind.co](https://www.spendmind.co)

<p align="center">
  <img src="https://github.com/wajahathassan64/portfolio/blob/main/assets/qr-code.png" width="200" alt="WhatsApp QR Code">
</p>

<p align="center"><sub>Open to senior iOS / mobile engineering roles. Available for contract & remote work.</sub></p>
