# Swaad Express — Project Tadka

A browser-based restaurant ordering demo for AIP³ Phase 2 Day 2. Fictional case data only.

## Completed feature implementation
- **F1 (21 pts):** Dal Bati Churma added under Thali at ₹299.
- **F2 (26 pts):** a maximum of 10 portions of any one dish per cart.
- **F3 (34 pts):** UPI and Card remain available; PayKaro reassurance line is shown.
- **CR1 (5 pts):** every menu dish has a Boolean `veg` tag and the existing renderer shows green/red dots. Non-veg: Chicken Biryani, Mutton Biryani, Chicken Seekh Kebab.
- **CR2 (8 pts):** bill summary returns food, gstRate (0.05), gst and total; GST is 5%.

## Run locally
Open `index.html` in a browser. No real payment or order is processed. To run automated checks, use Node.js 20+: `node tests/run.js`.

## CI/CD
`.github/workflows/checks.yml` runs the repository checks on pushes and pull requests and deploys GitHub Pages from the default branch after a successful check. Configure Pages source as **GitHub Actions**. For the assignment release gate, configure a branch ruleset requiring one pull-request approval and the `checks` status.

Student: **Moumita Barik** · Roll No. **12**
