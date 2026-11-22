# undigital-support

Static support and privacy pages for Undigital (the app and its Final Cut Pro effect live in
`~/Projects/undigital`). Served by GitHub Pages.

**The privacy policy is a legal document that Apple checks against the App Privacy answers in App
Store Connect.** Do not let it say something the app does not do, and do not let it go stale: if
the app or the effect gains an entitlement, an SDK or a network request, or changes what it
stores, update `privacy.html` in the same session. Current facts: app entitlements are sandbox, app
group, outgoing network (optional film-data download from GitHub only) and Movies read-write (to
install Motion templates); the effect has sandbox and app group only. The app also stores the signed receipt of an Undigital Pro
purchase (StoreKit) in the app group so the effect can drop its watermark; no personal data.

Public pages: no film-maker or rival names, and the matched film looks are "matched", never "measured" or "lab-accurate".
