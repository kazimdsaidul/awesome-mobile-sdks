# Awesome Mobile SDKs 📱

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated collection of **full SDKs** (not libraries) for mobile application developers across **Android**, **iOS**, **Flutter**, and **React Native** platforms — organized by industry category.

**Only full SDK-based solutions** are included here. If you're looking for lightweight wrappers or standalone libraries, this list may not be what you need.

---

## Contents

- [Audio & Video Calling](#audio--video-calling)
- [Chat & Messaging](#chat--messaging)
- [Payment & Fintech](#payment--fintech)
- [Maps & Location](#maps--location)
- [Authentication & Identity](#authentication--identity)
- [Push Notifications](#push-notifications)
- [Analytics & Crash Reporting](#analytics--crash-reporting)
- [Ads & Monetization](#ads--monetization)
- [Cloud & Backend-as-a-Service](#cloud--backend-as-a-service)
- [E-Commerce](#e-commerce)
- [CRM & Customer Engagement](#crm--customer-engagement)
- [AR & VR](#ar--vr)
- [IoT & Bluetooth](#iot--bluetooth)
- [Social & Sharing](#social--sharing)
- [CI/CD & App Distribution](#cicd--app-distribution)
- [Contributing](#contributing)

---

## Audio & Video Calling

Full SDKs for real-time voice, video, conferencing, and VoIP integration.

| SDK | Android | iOS | Flutter | React Native | Description |
|-----|---------|-----|---------|-------------|-------------|
| [Twilio Voice & Video](https://www.twilio.com/docs/voice/sdks) | ✅ | ✅ | ✅ | ✅ | Enterprise-grade WebRTC voice & video with PSTN, SIP, and recording |
| [Agora](https://www.agora.io/en/) | ✅ | ✅ | ✅ | ✅ | Real-time voice, video, interactive live streaming, and broadcast |
| [VideoSDK](https://github.com/videosdk-live) | ✅ | ✅ | ✅ | ✅ | Developer-friendly video & audio SDK with prebuilt UI and low latency |
| [Vonage (TokBox)](https://developer.vonage.com/en/video/overview) | ✅ | ✅ | ✅ | ✅ | Multi-party video, screen sharing, archiving (formerly OpenTok) |
| [Jitsi Meet SDK](https://jitsi.github.io/handbook/docs/dev-guide/dev-guide-android-sdk/) | ✅ | ✅ | ✅ | ✅ | Open-source video conferencing with end-to-end encryption |
| [Linphone (liblinphone)](https://www.linphone.org/en/liblinphone-voip-sdk/) | ✅ | ✅ | ❌ | ❌ | Open-source SIP-based VoIP SDK for voice & video calls |
| [MirrorFly](https://www.mirrorfly.com/) | ✅ | ✅ | ✅ | ✅ | Self-hosted or cloud video/voice/chat with 1000+ features |
| [Sinch](https://www.sinch.com/) | ✅ | ✅ | ❌ | ✅ | Voice, video, verification, and SMS on a single platform |
| [Infobip WebRTC](https://www.infobip.com/docs/voice-and-video/webrtc) | ✅ | ✅ | ❌ | ❌ | WebRTC voice & video with Calls API and push notification support |
| [Dolby.io (Millicast)](https://dolby.io/) | ✅ | ✅ | ✅ | ✅ | Ultra-low latency streaming and spatial audio |
| [PortSIP VoIP SDK](https://www.portsip.com/portsip-voip-sdk/) | ✅ | ✅ | ❌ | ❌ | SIP-based VoIP SDK with WebRTC, screen sharing, and file transfer |
| [Amazon Chime SDK](https://aws.amazon.com/chime/chime-sdk/) | ✅ | ✅ | ❌ | ✅ | AWS-powered real-time audio, video, and screen sharing |
| [Zoom Video SDK](https://developers.zoom.us/docs/video-sdk/) | ✅ | ✅ | ✅ | ✅ | Embed Zoom-quality video directly into custom applications |
| [Pexip SDK](https://developer.pexip.com/) | ✅ | ✅ | ❌ | ❌ | Enterprise video conferencing with interoperability (SIP, H.323, Teams) |
| [Daily.co](https://www.daily.co/) | ✅ | ✅ | ✅ | ✅ | WebRTC-based video/audio API with prebuilt and custom UI options |
| [100ms](https://www.100ms.live/) | ✅ | ✅ | ✅ | ✅ | Live video, audio rooms, and interactive live streaming |

---

## Chat & Messaging

Full SDKs for in-app text messaging, group chat, file sharing, and moderation.

| SDK | Android | iOS | Flutter | React Native | Description |
|-----|---------|-----|---------|-------------|-------------|
| [Sendbird](https://sendbird.com/) | ✅ | ✅ | ✅ | ✅ | Chat, voice/video, and AI chatbot SDK with UIKits and moderation |
| [CometChat](https://www.cometchat.com/) | ✅ | ✅ | ✅ | ✅ | In-app chat, voice & video with ready-to-use UI components |
| [Stream Chat](https://getstream.io/chat/) | ✅ | ✅ | ✅ | ✅ | Messaging API with activity feeds, moderation, and threaded messages |
| [PubNub](https://www.pubnub.com/) | ✅ | ✅ | ✅ | ✅ | Real-time messaging infrastructure with presence and signal APIs |
| [Twilio Conversations](https://www.twilio.com/docs/conversations) | ✅ | ✅ | ❌ | ✅ | Multi-channel messaging (SMS, WhatsApp, chat) unified API |
| [ConnectyCube](https://connectycube.com/) | ✅ | ✅ | ✅ | ✅ | Chat, video calling, and push notifications with cloud backend |
| [QuickBlox](https://quickblox.com/) | ✅ | ✅ | ✅ | ✅ | Chat, video, and push notification SDK with AI-assist features |
| [Applozic](https://www.applozic.com/) | ✅ | ✅ | ✅ | ✅ | In-app messaging with rich media, bots, and contextual chat |
| [MirrorFly Chat](https://www.mirrorfly.com/chat-api-solution.php) | ✅ | ✅ | ✅ | ✅ | Self-hosted or SaaS chat SDK with 100% UI customization |
| [Qiscus](https://www.qiscus.com/) | ✅ | ✅ | ✅ | ❌ | Multichannel messaging SDK for customer engagement |

---

## Payment & Fintech

Full SDKs for payment processing, gateways, in-app purchases, and financial services.

| SDK | Android | iOS | Flutter | React Native | Description |
|-----|---------|-----|---------|-------------|-------------|
| [Stripe](https://stripe.com/docs/mobile) | ✅ | ✅ | ✅ | ✅ | Global payments with cards, wallets, BNPL, subscriptions, and SCA |
| [Braintree (PayPal)](https://www.braintreepayments.com/) | ✅ | ✅ | ✅ | ✅ | Vault, subscriptions, and PayPal/Venmo integration |
| [Razorpay](https://razorpay.com/docs/) | ✅ | ✅ | ✅ | ✅ | Popular in India — cards, UPI, wallets, EMI, and subscriptions |
| [Square (In-App Payments)](https://developer.squareup.com/docs/in-app-payments-sdk) | ✅ | ✅ | ✅ | ✅ | Payments, POS terminal, and reader integration |
| [Adyen](https://docs.adyen.com/online-payments/build-your-integration/additional-use-cases/mobile/) | ✅ | ✅ | ✅ | ✅ | Enterprise payment platform for global commerce |
| [Paytm All-in-One SDK](https://developer.paytm.com/docs/) | ✅ | ✅ | ✅ | ✅ | India — UPI, cards, wallets, net banking, and EMI |
| [Flutterwave](https://developer.flutterwave.com/) | ✅ | ✅ | ✅ | ✅ | Africa — cards, mobile money, bank transfer, USSD |
| [RevenueCat](https://www.revenuecat.com/) | ✅ | ✅ | ✅ | ✅ | In-app subscriptions & purchases management across stores |
| [Cashfree Payments](https://www.cashfree.com/) | ✅ | ✅ | ✅ | ✅ | India — payouts, payment gateway, subscriptions |
| [PayTabs](https://site.paytabs.com/) | ✅ | ✅ | ✅ | ❌ | MENA region — cards, APMs, and tokenization |
| [SSLCommerz](https://developer.sslcommerz.com/) | ✅ | ✅ | ✅ | ❌ | Bangladesh — cards, mobile banking, and internet banking |
| [bKash](https://developer.bka.sh/) | ✅ | ✅ | ✅ | ❌ | Bangladesh — mobile financial services integration |
| [Plaid](https://plaid.com/) | ✅ | ✅ | ✅ | ✅ | Bank account linking, identity verification, and transaction data |
| [Checkout.com](https://www.checkout.com/) | ✅ | ✅ | ✅ | ✅ | Enterprise payment processing with global acquiring |
| [Apple Pay / Google Pay](https://developers.google.com/pay) | ✅ | ✅ | ✅ | ✅ | Native digital wallet integrations via platform SDKs |
| [HyperPay](https://www.hyperpay.com/) | ✅ | ✅ | ✅ | ❌ | MENA — end-to-end payment gateway for mobile |

---

## Maps & Location

Full SDKs for maps, navigation, geocoding, routing, and geofencing.

| SDK | Android | iOS | Flutter | React Native | Description |
|-----|---------|-----|---------|-------------|-------------|
| [Google Maps SDK](https://developers.google.com/maps/documentation) | ✅ | ✅ | ✅ | ✅ | Industry-standard maps with Places, Directions, and Street View |
| [Mapbox](https://www.mapbox.com/) | ✅ | ✅ | ✅ | ✅ | Highly customizable maps, offline mode, navigation, and AR |
| [HERE SDK](https://www.here.com/platform/mobile-sdk) | ✅ | ✅ | ✅ | ❌ | Navigation, traffic, transit, and fleet management (200+ countries) |
| [TomTom Maps SDK](https://developer.tomtom.com/) | ✅ | ✅ | ✅ | ❌ | Navigation, routing, traffic, and offline maps |
| [Apple MapKit](https://developer.apple.com/documentation/mapkit/) | ❌ | ✅ | ❌ | ❌ | Native iOS maps with Look Around and indoor mapping |
| [MapLibre Native](https://maplibre.org/) | ✅ | ✅ | ✅ | ✅ | Open-source fork of Mapbox GL — no vendor lock-in |
| [Radar](https://radar.com/) | ✅ | ✅ | ✅ | ✅ | Geofencing, trip tracking, store locators, and address validation |
| [Huawei Map Kit](https://developer.huawei.com/consumer/en/hms/huawei-MapKit/) | ✅ | ❌ | ✅ | ❌ | Maps for Huawei ecosystem with 3D buildings and clustering |
| [Baidu Maps SDK](https://lbsyun.baidu.com/) | ✅ | ✅ | ❌ | ❌ | Best-in-class maps for the Chinese market |
| [Yandex MapKit](https://yandex.com/dev/mapkit/) | ✅ | ✅ | ❌ | ❌ | Maps and navigation for Russia and CIS regions |
| [OpenStreetMap (via OSMDroid)](https://github.com/osmdroid/osmdroid) | ✅ | ❌ | ❌ | ❌ | Open-source map tiles for Android with offline support |
| [HyperTrack](https://hypertrack.com/) | ✅ | ✅ | ✅ | ✅ | Live location tracking, order tracking, and workforce management |

---

## Authentication & Identity

Full SDKs for user authentication, biometric verification, and identity management.

| SDK | Android | iOS | Flutter | React Native | Description |
|-----|---------|-----|---------|-------------|-------------|
| [Firebase Auth](https://firebase.google.com/docs/auth) | ✅ | ✅ | ✅ | ✅ | Email, phone, social login, and anonymous auth |
| [Auth0](https://auth0.com/) | ✅ | ✅ | ✅ | ✅ | Universal login, SSO, MFA, and social connections |
| [Okta](https://developer.okta.com/) | ✅ | ✅ | ❌ | ✅ | Enterprise identity management with adaptive MFA |
| [AWS Cognito](https://aws.amazon.com/cognito/) | ✅ | ✅ | ✅ | ✅ | User pools, federated identities, and OAuth 2.0 |
| [Supabase Auth](https://supabase.com/docs/guides/auth) | ✅ | ✅ | ✅ | ✅ | Open-source auth with social login and row-level security |
| [Onfido](https://onfido.com/) | ✅ | ✅ | ✅ | ✅ | AI-powered identity verification and document checks |
| [Jumio](https://www.jumio.com/) | ✅ | ✅ | ❌ | ✅ | ID verification, AML screening, and biometric authentication |
| [Twilio Verify](https://www.twilio.com/docs/verify) | ✅ | ✅ | ✅ | ✅ | Phone verification via SMS, voice, email, and TOTP |
| [Apple Sign In](https://developer.apple.com/sign-in-with-apple/) | ❌ | ✅ | ✅ | ✅ | Native Apple ID authentication (required for App Store apps) |
| [Google Identity Services](https://developers.google.com/identity) | ✅ | ✅ | ✅ | ✅ | Google Sign-In and One Tap sign-up/sign-in |

---

## Push Notifications

Full SDKs for push notification delivery, rich media, and engagement.

| SDK | Android | iOS | Flutter | React Native | Description |
|-----|---------|-----|---------|-------------|-------------|
| [Firebase Cloud Messaging (FCM)](https://firebase.google.com/docs/cloud-messaging) | ✅ | ✅ | ✅ | ✅ | Cross-platform push messaging (free, unlimited) |
| [OneSignal](https://onesignal.com/) | ✅ | ✅ | ✅ | ✅ | Push, in-app messaging, email, and SMS with audience segmentation |
| [Pusher Beams](https://pusher.com/beams/) | ✅ | ✅ | ✅ | ✅ | Pub/Sub push notifications with device-level targeting |
| [Airship](https://www.airship.com/) | ✅ | ✅ | ✅ | ✅ | Enterprise push, in-app messaging, and app inbox |
| [Huawei Push Kit](https://developer.huawei.com/consumer/en/hms/huawei-pushkit/) | ✅ | ❌ | ✅ | ❌ | Push notifications for Huawei/HMS ecosystem |
| [Braze](https://www.braze.com/) | ✅ | ✅ | ✅ | ✅ | Customer engagement with push, in-app, and content cards |
| [CleverTap](https://clevertap.com/) | ✅ | ✅ | ✅ | ✅ | Push, in-app, and omnichannel engagement with analytics |
| [Amazon SNS (Pinpoint)](https://aws.amazon.com/pinpoint/) | ✅ | ✅ | ✅ | ✅ | AWS-powered multi-channel messaging and push |

---

## Analytics & Crash Reporting

Full SDKs for product analytics, user behavior tracking, crash monitoring, and performance.

| SDK | Android | iOS | Flutter | React Native | Description |
|-----|---------|-----|---------|-------------|-------------|
| [Firebase Analytics + Crashlytics](https://firebase.google.com/docs/analytics) | ✅ | ✅ | ✅ | ✅ | Free unlimited analytics with integrated crash reporting |
| [Amplitude](https://amplitude.com/) | ✅ | ✅ | ✅ | ✅ | Behavioral analytics with cohort analysis and prediction |
| [Mixpanel](https://mixpanel.com/) | ✅ | ✅ | ✅ | ✅ | Event-based analytics with funnels, retention, and segmentation |
| [Sentry](https://sentry.io/) | ✅ | ✅ | ✅ | ✅ | Error tracking and performance monitoring with stack traces |
| [Bugsnag](https://www.bugsnag.com/) | ✅ | ✅ | ✅ | ✅ | Crash detection, stability scoring, and release health tracking |
| [Datadog Mobile](https://www.datadoghq.com/product/real-user-monitoring/) | ✅ | ✅ | ✅ | ✅ | Real User Monitoring (RUM), errors, and performance |
| [New Relic Mobile](https://newrelic.com/platform/mobile-monitoring) | ✅ | ✅ | ✅ | ✅ | Full-stack mobile monitoring and distributed tracing |
| [PostHog](https://posthog.com/) | ✅ | ✅ | ✅ | ✅ | Open-source product analytics, session replay, and feature flags |
| [AppsFlyer](https://www.appsflyer.com/) | ✅ | ✅ | ✅ | ✅ | Attribution, deep linking, and marketing analytics |
| [Adjust](https://www.adjust.com/) | ✅ | ✅ | ✅ | ✅ | Attribution, fraud prevention, and audience builder |
| [UXCam](https://uxcam.com/) | ✅ | ✅ | ✅ | ✅ | Session replay, heatmaps, and gesture analytics (mobile-first) |
| [Countly](https://count.ly/) | ✅ | ✅ | ✅ | ✅ | Self-hosted or cloud analytics with crash reporting and A/B testing |
| [Embrace](https://embrace.io/) | ✅ | ✅ | ✅ | ✅ | Mobile-first observability with session-level visibility |
| [Instabug](https://instabug.com/) | ✅ | ✅ | ✅ | ✅ | Bug reporting, crash analytics, and in-app surveys |
| [AppMetrica (Yandex)](https://appmetrica.io/) | ✅ | ✅ | ✅ | ✅ | Free analytics with attribution, push campaigns, and A/B testing |

---

## Ads & Monetization

Full SDKs for ad serving, mediation, and revenue optimization.

| SDK | Android | iOS | Flutter | React Native | Description |
|-----|---------|-----|---------|-------------|-------------|
| [Google AdMob](https://developers.google.com/admob/android/sdk) | ✅ | ✅ | ✅ | ✅ | Banner, interstitial, rewarded, and native ads by Google |
| [Meta Audience Network](https://developers.facebook.com/docs/audience-network/) | ✅ | ✅ | ✅ | ✅ | Facebook/Instagram ad demand for in-app monetization |
| [Unity Ads](https://unity.com/products/unity-ads) | ✅ | ✅ | ✅ | ✅ | Video and rewarded ads optimized for games |
| [AppLovin MAX](https://www.applovin.com/max/) | ✅ | ✅ | ✅ | ✅ | Ad mediation with real-time bidding across networks |
| [IronSource (Unity LevelPlay)](https://developers.is.com/) | ✅ | ✅ | ✅ | ✅ | In-app ad mediation and user acquisition platform |
| [Chartboost](https://www.chartboost.com/) | ✅ | ✅ | ❌ | ❌ | Ad exchange and mediation focused on gaming |
| [InMobi](https://www.inmobi.com/) | ✅ | ✅ | ✅ | ✅ | Mobile ads with native, video, and rewarded formats |
| [Mintegral](https://www.mintegral.com/) | ✅ | ✅ | ❌ | ❌ | Programmatic ad platform for global mobile publishers |
| [Huawei Ads Kit](https://developer.huawei.com/consumer/en/hms/huawei-adskit/) | ✅ | ❌ | ✅ | ❌ | Ad monetization for Huawei ecosystem |

---

## Cloud & Backend-as-a-Service

Full SDKs for cloud backend, real-time databases, serverless functions, and storage.

| SDK | Android | iOS | Flutter | React Native | Description |
|-----|---------|-----|---------|-------------|-------------|
| [Firebase](https://firebase.google.com/) | ✅ | ✅ | ✅ | ✅ | Full suite — Firestore, Realtime DB, Auth, Storage, Functions, ML |
| [AWS Amplify](https://docs.amplify.aws/) | ✅ | ✅ | ✅ | ✅ | Full-stack framework with Auth, API, Storage, Analytics on AWS |
| [Supabase](https://supabase.com/) | ✅ | ✅ | ✅ | ✅ | Open-source Firebase alternative with Postgres, Auth, and Storage |
| [Appwrite](https://appwrite.io/) | ✅ | ✅ | ✅ | ✅ | Open-source BaaS with Auth, DB, Storage, Functions, and Messaging |
| [Back4App (Parse)](https://www.back4app.com/) | ✅ | ✅ | ✅ | ✅ | Managed Parse Server with real-time queries and cloud functions |
| [Azure Mobile Apps](https://learn.microsoft.com/en-us/azure/developer/mobile-apps/) | ✅ | ✅ | ✅ | ✅ | Microsoft cloud backend with offline sync and auth |
| [Huawei AppGallery Connect](https://developer.huawei.com/consumer/en/service/josp/agc/index.html) | ✅ | ❌ | ✅ | ❌ | Cloud DB, Cloud Functions, Auth, and Remote Config for HMS |

---

## E-Commerce

Full SDKs for building commerce experiences, product catalogs, and checkout flows.

| SDK | Android | iOS | Flutter | React Native | Description |
|-----|---------|-----|---------|-------------|-------------|
| [Shopify Mobile Buy SDK](https://shopify.dev/docs/custom-storefronts/mobile-buy-sdk) | ✅ | ✅ | ✅ | ✅ | Build custom storefronts with Shopify's product & checkout APIs |
| [Instamojo](https://www.instamojo.com/) | ✅ | ✅ | ✅ | ❌ | India — payments, store links, and refund management |
| [Snipcart](https://snipcart.com/) | ❌ | ❌ | ❌ | ❌ | E-commerce cart SDK for web/mobile web apps |
| [CommerceTools](https://commercetools.com/) | ✅ | ✅ | ❌ | ✅ | Headless commerce platform with flexible APIs |
| [Salesforce Commerce Cloud](https://www.salesforce.com/products/commerce/) | ✅ | ✅ | ❌ | ✅ | Enterprise-grade B2C and B2B commerce |

---

## CRM & Customer Engagement

Full SDKs for customer relationship management, in-app support, and user engagement.

| SDK | Android | iOS | Flutter | React Native | Description |
|-----|---------|-----|---------|-------------|-------------|
| [Intercom](https://www.intercom.com/) | ✅ | ✅ | ✅ | ✅ | In-app messaging, support bots, product tours, and help center |
| [Zendesk SDK](https://developer.zendesk.com/documentation/classic-sdks/) | ✅ | ✅ | ✅ | ✅ | Ticketing, live chat, and knowledge base in-app |
| [Freshdesk (Freshchat)](https://www.freshworks.com/live-chat-software/) | ✅ | ✅ | ✅ | ✅ | Conversational support with bots and agent handoff |
| [Drift](https://www.drift.com/) | ✅ | ✅ | ❌ | ✅ | Conversational marketing and sales platform |
| [Braze](https://www.braze.com/) | ✅ | ✅ | ✅ | ✅ | Cross-channel engagement — push, email, in-app, and content cards |
| [CleverTap](https://clevertap.com/) | ✅ | ✅ | ✅ | ✅ | Analytics-driven engagement with push, in-app, and segmentation |
| [MoEngage](https://www.moengage.com/) | ✅ | ✅ | ✅ | ✅ | AI-powered engagement with push, in-app, and cards |

---

## AR & VR

Full SDKs for augmented reality, virtual reality, and 3D experiences.

| SDK | Android | iOS | Flutter | React Native | Description |
|-----|---------|-----|---------|-------------|-------------|
| [ARCore (Google)](https://developers.google.com/ar) | ✅ | ❌ | ✅ | ❌ | Motion tracking, environmental understanding, and light estimation |
| [ARKit (Apple)](https://developer.apple.com/augmented-reality/) | ❌ | ✅ | ✅ | ❌ | Face tracking, world tracking, and object detection on iOS |
| [Vuforia](https://developer.vuforia.com/) | ✅ | ✅ | ❌ | ❌ | Image/object recognition and AR experiences for enterprise |
| [8th Wall](https://www.8thwall.com/) | ✅ | ✅ | ❌ | ❌ | WebAR platform — no app download required |
| [Wikitude](https://www.wikitude.com/) | ✅ | ✅ | ✅ | ✅ | Image/object tracking, instant tracking, and geo-based AR |
| [Snap AR (Lens Studio)](https://ar.snap.com/) | ✅ | ✅ | ❌ | ❌ | Camera Kit and AR experiences powered by Snapchat's AR engine |
| [Niantic Lightship](https://lightship.dev/) | ✅ | ✅ | ❌ | ❌ | Real-world AR (from Pokémon GO creators) with VPS and meshing |

---

## IoT & Bluetooth

Full SDKs for Bluetooth Low Energy, IoT device communication, and smart hardware.

| SDK | Android | iOS | Flutter | React Native | Description |
|-----|---------|-----|---------|-------------|-------------|
| [Nordic Semiconductor SDK](https://www.nordicsemi.com/Products/Development-software) | ✅ | ✅ | ✅ | ✅ | BLE SDK for nRF chipset — DFU, mesh, and scanning |
| [Espressif ESP-IDF](https://github.com/espressif/esp-idf) | ✅ | ❌ | ❌ | ❌ | IoT SDK for ESP32/ESP8266 with Wi-Fi and BLE |
| [Particle IoT](https://www.particle.io/) | ✅ | ✅ | ❌ | ❌ | Cloud-connected IoT platform with device management |
| [AWS IoT SDK](https://aws.amazon.com/iot/) | ✅ | ✅ | ❌ | ✅ | Device connectivity, data collection, and edge computing |
| [Azure IoT Hub SDK](https://learn.microsoft.com/en-us/azure/iot-hub/) | ✅ | ✅ | ❌ | ❌ | Microsoft IoT platform for device-to-cloud communication |
| [HomeKit (Apple)](https://developer.apple.com/homekit/) | ❌ | ✅ | ❌ | ❌ | Smart home device control and automation on Apple ecosystem |
| [Google Home / Matter SDK](https://developers.home.google.com/) | ✅ | ✅ | ❌ | ❌ | Smart home integration with Matter protocol support |

---

## Social & Sharing

Full SDKs for social login, content sharing, and deep linking.

| SDK | Android | iOS | Flutter | React Native | Description |
|-----|---------|-----|---------|-------------|-------------|
| [Facebook SDK](https://developers.facebook.com/docs/android/) | ✅ | ✅ | ✅ | ✅ | Login, sharing, analytics, and App Events |
| [Branch.io](https://branch.io/) | ✅ | ✅ | ✅ | ✅ | Deep linking, attribution, and contextual cross-platform links |
| [Firebase Dynamic Links](https://firebase.google.com/docs/dynamic-links) | ✅ | ✅ | ✅ | ✅ | Smart URLs that work across platforms (deprecated — use App Links) |
| [ShareThis](https://sharethis.com/) | ✅ | ✅ | ❌ | ❌ | Social sharing buttons and engagement tools |
| [LINE SDK](https://developers.line.biz/) | ✅ | ✅ | ✅ | ❌ | Login, messaging, and sharing for LINE messenger |
| [WeChat SDK](https://developers.weixin.qq.com/) | ✅ | ✅ | ✅ | ❌ | Login, sharing, and payments for WeChat ecosystem |
| [Kakao SDK](https://developers.kakao.com/) | ✅ | ✅ | ✅ | ❌ | Login, sharing, and messaging for Kakao (Korea) |

---

## CI/CD & App Distribution

Full SDKs and tools for continuous integration, delivery, testing, and app distribution.

| SDK / Tool | Android | iOS | Flutter | React Native | Description |
|------------|---------|-----|---------|-------------|-------------|
| [Firebase App Distribution](https://firebase.google.com/docs/app-distribution) | ✅ | ✅ | ✅ | ✅ | Pre-release app distribution to testers |
| [Fastlane](https://fastlane.tools/) | ✅ | ✅ | ✅ | ✅ | Automated build, signing, screenshots, and store deployment |
| [CodePush (App Center)](https://learn.microsoft.com/en-us/appcenter/distribution/codepush/) | ❌ | ❌ | ❌ | ✅ | OTA JavaScript updates for React Native (migrating to Expo) |
| [Shorebird](https://shorebird.dev/) | ❌ | ❌ | ✅ | ❌ | Code push / OTA updates for Flutter apps |
| [Bitrise](https://www.bitrise.io/) | ✅ | ✅ | ✅ | ✅ | Mobile-first CI/CD with device testing and deployment |
| [Codemagic](https://codemagic.io/) | ✅ | ✅ | ✅ | ✅ | CI/CD built specifically for Flutter and mobile |
| [TestFlight (Apple)](https://developer.apple.com/testflight/) | ❌ | ✅ | ✅ | ✅ | Apple's official beta testing distribution |
| [Google Play Internal Testing](https://play.google.com/console/) | ✅ | ❌ | ✅ | ✅ | Google's official internal and closed testing tracks |

---

## Contributing

Contributions are welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first.

**Rules for inclusion:**
1. Must be a **full SDK** — not a standalone library, wrapper, or utility
2. Must provide **native mobile support** for at least one platform (Android/iOS/Flutter/React Native)
3. Must be **actively maintained** (last update within 12 months)
4. Must have **official documentation** and/or a dedicated developer portal

To submit a new SDK:
1. Fork this repository
2. Add the SDK to the appropriate category table
3. Ensure platform availability columns (✅/❌) are accurate
4. Submit a Pull Request with a brief description

---

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

This list is released under CC0 1.0 Universal. See [LICENSE](LICENSE) for details.

---

<p align="center">
  <b>⭐ If you find this useful, give it a star!</b><br>
  Maintained by <a href="https://github.com/kazimdsaidul">@kazimdsaidul</a>
</p>
