# Orbit eSIM Browser prototype

A static, GitHub Pages-ready interface for an eSIM dashboard, browser launchpad, and sponsored-data rewards concept.

## Publish with GitHub Pages
1. Upload `index.html` and `README.md` to the repository root.
2. Open **Settings → Pages**.
3. Choose **Deploy from a branch**, select `main` and `/ (root)`, then save.

## Important limitations
- This is a UI prototype. It does not install an eSIM, supply mobile data, take payments, issue carrier top-ups, or connect an ad network.
- Browsing opens sites in separate tabs instead of using an iframe. A web page cannot become the system browser or route Safari/Google traffic through itself.
- Real provisioning and auto top-up require an eSIM provider/carrier API and a secure backend. Keep API secrets out of client-side JavaScript.
- Rewarded ads must be confirmed by the ad provider before rewards are credited; real data rewards need a funded carrier/provider integration.
