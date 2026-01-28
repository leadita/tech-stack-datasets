# Live Technographic Dataset

> 📊 Open-source dataset of 1M+ companies and their technology stacks, updated daily.

A comprehensive, freely accessible dataset containing real-world company data paired with their technology choices. Perfect for sales teams, marketers, data scientists, and product analysts.

## 📂 Browse by Technology

### E-Commerce Platforms
- [Companies using WooCommerce](./leads/companies-using-woocommerce) (359,633 companies)
- [Companies using WordPress](./leads/companies-using-wordpress) (2,725,173 companies)
- [Companies using Webflow](./leads/companies-using-webflow) (52,650 companies)
- [Companies using Adobe Commerce](./leads/companies-using-magento) (690,357 companies)
- [Companies using Shopify Plus](./leads/companies-using-shopify-plus) (2,228 companies)
- [Companies using BigCommerce](./leads/companies-using-bigcommerce) (5,370 companies)

### CRM & Marketing Automation
- [Companies using HubSpot](./leads/companies-using-hubspot) (114,251 companies)
- [Companies using ActiveCampaign](./leads/companies-using-activecampaign) (10,457 companies)
- [Companies using Marketo](./leads/companies-using-marketo) (1,218 companies)

### Customer Support
- [Companies using Intercom](./leads/companies-using-intercom) (21,002 companies)
- [Companies using Zendesk](./leads/companies-using-zendesk) (49,579 companies)
- [Companies using Drift](./leads/companies-using-drift) (2,413 companies)

### Analytics
- [Companies using Mixpanel](./leads/companies-using-mixpanel) (6,387 companies)
- [Companies using Amplitude](./leads/companies-using-amplitude) (5,974 companies)

### Forms & Lead Capture
- [Companies using Typeform](./leads/companies-using-typeform) (14,305 companies)
- [Companies using Formstack](./leads/companies-using-formstack) (2,579 companies)

### Payments
- [Companies using PayPal Business](./leads/companies-using-paypal) (95,874 companies)
- [Companies using Square](./leads/companies-using-square) (7,538 companies)

### Other
- [Companies using Statamic](./leads/companies-using-statamic) (2,258 companies)

## 🚀 Quick Start

1. **Browse**: Click any folder above to explore companies
2. **Download**: Use the CSV/JSON files to export data
3. **Integrate**: Use the free data to analyze tech trends
4. **Upgrade**: Get verified contact info for any company list

## 🛠️ How to Run This Project

You can run this project in two ways:

### Option A: GitHub Actions (Automated & Free)
The repository is pre-configured with GitHub Actions that run automatically every day.
1. Fork this repository.
2. Add your `LEADITA_API_KEY` to **Settings > Secrets and variables > Actions**.
3. Enable "Read and write permissions" for workflows in **Settings > Actions > General**.
4. The data will update automatically!

### Option B: Hosted VPS (Recommended for Power Users)
Running on a VPS allows for more control and bypasses GitHub Actions limitations.
1. Clone this repo to your VPS.
2. Install dependencies: `pip install requests`.
3. Set your API key: `export LEADITA_API_KEY="your_key"`.
4. Set up a cron job to run `scripts/fetch_and_update.py`.

> 📘 **Detailed Guide**: See [VPS_AND_TRAFFIC.md](./VPS_AND_TRAFFIC.md) for a full setup guide and traffic generation strategies.

## ✨ Features

- ✅ **Updated Daily**: Fresh data every 24 hours
- ✅ **Free to Use**: No registration required
- ✅ **Open Format**: CSV & JSON for easy integration
- ✅ **Verified Data**: Detected by our crawler, not scraped
- ✅ **Complete Records**: 10+ data fields per company
- ✅ **Downloadable**: Use offline or in your tools

## 📊 What's Included?

Each dataset contains:
- **Company Name** & Domain
- **Location** (Country, State)
- **Technology Stack** (detected tools & platforms)
- **Spending Score** (estimated tech budget)
- **Quality Score** (data verification score)
- **Service Type** (B2B, B2C, etc)
- **Decision-Maker Title** (when available)
- **Last Verified** (crawl date)

## 🔐 Contact Information

The datasets above show sample records **without emails or phone numbers**.

To unlock verified contact information for any company list:
👉 [Upgrade to Leadita Pro](https://leadita.com)

## 📈 Statistics

- **Total Companies Indexed**: 1M+
- **Total Technologies Tracked**: 20+
- **Data Update Frequency**: Daily
- **Last Mass Update**: [See individual folders]

## 🛠️ Use Cases

**Sales & Outreach**
- Build prospect lists by technology
- Find companies to pitch your product
- Identify decision-makers

**Marketing & Competitive Intelligence**
- Track competitor tech stacks
- Understand market adoption trends
- Benchmark against similar companies

**Product Teams**
- Analyze market adoption of your tools
- Find early adopters of new technologies
- Track tech trends over time

**Data Scientists & Analysts**
- Train ML models on tech adoption patterns
- Analyze market segmentation
- Study digital transformation trends

## 💡 API Access

Want to integrate this data programmatically? [Check out Leadita API](https://leadita.com/api)

## 📝 License

This dataset is provided as-is for informational purposes. Use of contact information requires explicit consent. See [LICENSE](./LICENSE) for details.

## 🤝 Contributing

Found an issue with the data? Have suggestions? [Open an issue](https://github.com/your-username/tech-stack-datasets/issues)

## 📧 Support

Questions? Feedback? [Contact us](https://leadita.com/contact-sales)

---

**Made with ❤️ by [Leadita](https://leadita.com)**
