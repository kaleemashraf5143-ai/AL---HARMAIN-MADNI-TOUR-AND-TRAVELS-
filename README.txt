AL-HARMAIN Tour & Travel app — v4 progress package

Demo additions:
- Payment entry validation prevents amount above remaining balance.
- CSV ledger includes paid total, balance due and payment history.
- Package manager can add, edit, and delete packages.
- Document checklist statuses only (passport checked/photo/visa/ticket); no scans.
- Receipt notes payment must be independently verified.
- Capacitor Android dependency explicitly included; APK build workflow.

Limitations: browser-local data only; no sync/server; demo PIN 1234 is not secure;
never store passport scans, sensitive data or payment credentials. Example prices ₹40,000/₹45,000
must be confirmed. No real payment gateway, deployment, signed APK or Play Store release.

APK test build steps: Upload all project files to a GitHub repository on main. Enable Actions,
run “Build AL-HARMAIN Android APK”, download artifact AL-HARMAIN-debug-APK and extract app-debug.apk.
Debug APK is for testing only; Play Store release requires signing and policy/legal preparation.
