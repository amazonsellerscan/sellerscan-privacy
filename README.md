# Privacy Policy - SellerScan

**Last updated: January 2025**

## Overview

SellerScan is a browser extension that helps users discover Amazon seller storefronts from search results. This privacy policy explains how we handle your data.

## Data Collection

**SellerScan does NOT collect, store, or transmit any personal data.**

We do not:
- Collect personal information
- Track your browsing activity
- Send data to external servers
- Use analytics or tracking services
- Store any data outside your browser

## Data Processed Locally

The following data is processed **locally on your device only**:

| Data | Purpose | Storage |
|------|---------|---------|
| User preferences | Save your settings (max storefronts, overlay toggle) | chrome.storage.sync (local) |
| Product ASINs | Extract seller information from Amazon pages | Memory only (not persisted) |
| Seller IDs | Navigate between seller storefronts | chrome.storage.local (temporary) |

## Permissions Used

SellerScan requires the following permissions:

| Permission | Purpose |
|------------|---------|
| `tabs` | Open seller storefront tabs |
| `activeTab` | Access the current Amazon page to extract product data |
| `scripting` | Inject content scripts to analyze Amazon pages |
| `storage` | Save your preferences locally |

## Network Requests

The extension makes requests **only to amazon.com** domains to:
- Fetch product pages to identify sellers
- Load storefront pages for analysis

**No data is sent to third-party servers.**

## Data Sharing

We do not share any data with third parties because we do not collect any data.

## Children's Privacy

SellerScan does not knowingly collect information from children under 13.

## Changes to This Policy

We may update this privacy policy from time to time. Changes will be posted on this page with an updated revision date.

## Contact

For questions about this privacy policy, please contact:

**Email:** amazon.sellerscan@gmail.com

---

*This privacy policy applies to SellerScan version 1.0.0 and later.*
