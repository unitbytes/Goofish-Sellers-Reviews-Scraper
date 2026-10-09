# 🐟 Goofish & Xianyu 闲鱼 Scraper: Search, Sellers & Reviews

<div align="center">

[![Available on Apify](https://img.shields.io/badge/Available_on-Apify-28B52A?style=for-the-badge&logo=apify&logoColor=white)](https://apify.com/unitbytes/goofish-scraper?fpr=939u3w&fp_sid=gh_goofish_scraper)
[![Bookmark on Apify](https://img.shields.io/badge/Apify%20Store-%E2%AD%90%20Bookmark%20Actor-orange?style=for-the-badge&logo=apify)](https://apify.com/unitbytes/goofish-scraper?fpr=939u3w&fp_sid=gh_goofish_scraper)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg?style=for-the-badge)](#)
[![Success Rate](https://img.shields.io/badge/Success_Rate-99%25+-brightgreen?style=for-the-badge)](#)
[![Zero Login](https://img.shields.io/badge/Account_Required-None-blue?style=for-the-badge)](#)
[![Pricing](https://img.shields.io/badge/Pricing-55%25_Lower_Cost-orange?style=for-the-badge)](#)
[![Free Compute](https://img.shields.io/badge/Compute_Fee-$0.00_Free-brightgreen?style=for-the-badge)](#)

**The most comprehensive, reliable, and cost-effective Goofish & Idlefish (闲鱼 / Xianyu) all-in-one scraper on Apify. Search live product listings, audit seller store credentials, extract Zhima Credit (芝麻信用) ratings, scrape full active & sold inventory catalogs, and analyze buyer reviews with real unboxing photos — 100% autonomously with Zero Login & Zero Chinese Phone Number Required.**

[**🚀 Try it Live on Apify**](https://apify.com/unitbytes/goofish-scraper?fpr=939u3w&fp_sid=gh_goofish_scraper) • [**⭐ Bookmark Actor**](https://apify.com/unitbytes/goofish-scraper?fpr=939u3w&fp_sid=gh_goofish_scraper) • [**📖 Documentation**](https://apify.com/unitbytes/goofish-scraper?fpr=939u3w&fp_sid=gh_goofish_scraper) • [**💬 Support**](https://apify.com/unitbytes/goofish-scraper/issues)

</div>

---

<p align="center">
  <a href="https://console.apify.com/actors/xma6AWAwibFiZHSqo/input" target="_blank">
    <img src="https://raw.githubusercontent.com/unitbytes/.github/main/assets/banners/unitbytes-goofish-xianyu-seller-inventory-reviews-scraper-banner.jpg" alt="Goofish Xianyu Seller & Reviews Scraper by UnitBytes" width="100%" />
  </a>
</p>

<p align="center">
  <a href="https://console.apify.com/actors/xma6AWAwibFiZHSqo/input" target="_blank">
    <img src="https://raw.githubusercontent.com/unitbytes/.github/main/assets/try-it-for-free.svg" width="240" height="48" alt="Try it for Free">
  </a>
  <br>
  <sub>⚡ <b>1-Click Free Trial:</b> Test live queries using Apify's $5 free monthly credit • No credit card required</sub>
</p>

---

## 📖 Overview

**Goofish (闲鱼 / Xianyu / Idle Fish)** is Alibaba's flagship C2C second-hand trading ecosystem with over **500 million registered users**. It represents the world's most dynamic marketplace for authentic pre-owned luxury, electronics, vintage fashion, anime figures, and rare collectibles.

However, gathering seller background intelligence, inventory history, and buyer feedback on Goofish is guarded by stringent anti-scraping barriers:
- Mandatory Chinese mobile (+86) SMS verification and QR code login screens.
- Dynamic Alibaba mtop encryption handshakes (`_m_h5_tk`, `tfstk`).
- Deeply nested mobile data structures that break typical spreadsheet exports.

**Goofish Sellers & Reviews Scraper by UnitBytes** solves these challenges permanently. Using an ultra-fast hybrid stealth engine with automated session reuse, this Actor extracts rich merchant profiles, active & historical listings, and buyer feedback at scale — **with zero login, zero cookies, and zero server compute fees ($0.00 compute)**.

<table>
  <tr>
    <td colspan="5" style="padding:10px 14px;background:#FF6A00;color:#FFFFFF;font-size:13px;font-weight:700;border-radius:6px 6px 0 0">
      ⚡ UnitBytes · Chinese E-Commerce & B2B Sourcing Ecosystem
    </td>
  </tr>
  <tr>
    <td style="padding:10px 12px;border:1px solid #E2E8F0;background:#FAFAFA;vertical-align:top;width:20%">
      <span style="white-space:nowrap">🌐 <b><a href="https://apify.com/unitbytes/alibaba-scraper?fpr=939u3w&fp_sid=ecosystem" style="color:#0F172A;text-decoration:none;font-size:13px">Alibaba Wholesale</a></b></span><br><span style="color:#2563EB;font-size:11px;font-weight:600">Global B2B & MOQ</span><br>
      <span style="color:#64748B;font-size:11px">Verified Suppliers & Audits</span>
    </td>
    <td style="padding:10px 12px;border:1px solid #E2E8F0;background:#FAFAFA;vertical-align:top;width:20%">
      <span style="white-space:nowrap">🇨🇳 <b><a href="https://apify.com/unitbytes/1688-scraper?fpr=939u3w&fp_sid=ecosystem" style="color:#0F172A;text-decoration:none;font-size:13px">1688 Factory Direct</a></b></span><br><span style="color:#2563EB;font-size:11px;font-weight:600">Domestic Factory Prices</span><br>
      <span style="color:#64748B;font-size:11px">SKU matrices & FBA specs</span>
    </td>
    <td style="padding:10px 12px;border:1px solid #E2E8F0;background:#FAFAFA;vertical-align:top;width:20%">
      <span style="white-space:nowrap">📕 <b><a href="https://apify.com/unitbytes/xiaohongshu-rednote-trend-scraper?fpr=939u3w&fp_sid=ecosystem" style="color:#0F172A;text-decoration:none;font-size:13px">Xiaohongshu Trends</a></b></span><br><span style="color:#2563EB;font-size:11px;font-weight:600">Social Commerce & KOL</span><br>
      <span style="color:#64748B;font-size:11px">Viral Posts & Buyer Intent</span>
    </td>
    <td style="padding:10px 12px;border:1px solid #E2E8F0;background:#FAFAFA;vertical-align:top;width:20%">
      <span style="white-space:nowrap">🐟 <b><a href="https://apify.com/unitbytes/goofish-xianyu-search-scraper?fpr=939u3w&fp_sid=ecosystem" style="color:#0F172A;text-decoration:none;font-size:13px">Goofish Products</a></b></span><br><span style="color:#2563EB;font-size:11px;font-weight:600">C2C Resale & Arbitrage</span><br>
      <span style="color:#64748B;font-size:11px">Zero-login search engine</span>
    </td>
    <td style="padding:10px 12px;border:1px solid #E2E8F0;background:#FFF4ED;vertical-align:top;width:20%">
      <span style="white-space:nowrap">⭐ <b><a href="https://apify.com/unitbytes/goofish-scraper?fpr=939u3w&fp_sid=ecosystem" style="color:#C2410C;text-decoration:none;font-size:13px">Goofish Sellers</a></b></span><br><span style="color:#EA580C;font-size:11px;font-weight:700">📍 You are here</span><br>
      <span style="color:#64748B;font-size:11px">Zhima credit & reviews</span>
    </td>
  </tr>
</table>

---

## 🌟 Why Choose This Scraper? (Head-to-Head Marketplace Comparison)

Unlike alternative Goofish scrapers that only extract shallow preview cards with broken CSV exports, **UnitBytes** extracts deep technical specifications, standardized condition grades, and verified unboxing reviews in clean, Excel-ready tables — at **more than 50% lower cost**.

| Feature / Metric | Other Goofish Scrapers (e.g. Zen Studio) | ⚡ UnitBytes Goofish & Idlefish Scraper |
| :--- | :--- | :--- |
| **Actor Start / Test Fee** | $0.05 – $0.10+ *(charges immediately on launch)* | 🆓 **$0.00001 (Virtually $0.00 · Zero-Risk Test Runs)** |
| **Product Listing Price** | $0.00799 – $0.00899 / item *(~$8.00–$9.00 per 1k)* | 💰 **$0.0035 / item (Save 55%–60%!)** |
| **Buyer Review Price** | $0.001 / review | 💰 **$0.001 / review (Best value on Apify)** |
| **Server Compute Fees** | Billed for platform RAM & container runtime | 🆓 **$0.00 (Zero compute fees · Pure HTTP)** |
| **Listing Extraction Depth** | Basic preview cards only (no specs, no condition) | 🚀 **Dual Modes (`summary` fast catalog vs `full` deep specs)** |
| **Product Specifications** | ❌ Omitted / Not extracted | 💎 **Structured Key-Value dictionary (`specs` brand, model, storage, CPU)** |
| **Physical Condition Grade** | ❌ Omitted / Not extracted | 🏷️ **Standardized grades (`全新` Brand New, `99新` Like New, `95新`)** |
| **Full Description Text** | ❌ Missing or truncated | 📝 **Complete seller item description, disclaimers & return notes** |
| **Bargain & Guarantee Flags** | ❌ Not available | 🛡️ **`allowBargain` & `tradeGuarantee` seller policy flags** |
| **Excel & CSV Usability** | ⚠️ Jagged & broken (mixed seller & item rows break columns) | 📊 **Native Tabular Mode (Clean rows with seller tags for instant pivot tables)** |
| **Inventory Status Filter** | ❌ No runtime filter (mixed active & sold) | 🎯 **`statusFilter`: Isolate `onsale` (active) vs `sold` (historical velocity)** |
| **Buyer Review Sentiment Filter** | ❌ None (must scrape thousands of 5-star reviews) | 🔍 **`reviewFilter`: Instantly isolate disputes (`negative_only`) or photo proofs** |
| **Buyer Review Unboxing Media** | Text only or low-res thumbnails | 📸 **Full HD buyer unboxing photos (`reviewImages`)** |
| **Item URL Auto-Resolution** | Manual seller numeric ID required | ✅ **Auto-resolves seller from product URLs, item IDs & mobile deeplinks** |
| **Zhima Credit Breakdown** | Single generic badge | 🛡️ **Distinct Seller & Buyer Zhima Credit levels (1–5)** |

<div align="center">
  <br>
  <a href="https://console.apify.com/actors/xma6AWAwibFiZHSqo/input">
    <img src="https://raw.githubusercontent.com/unitbytes/.github/main/assets/try-it-for-free.svg" width="240" height="48" alt="Try it for Free">
  </a>
  <p><sub>⚡ <b>Zero-Risk Testing:</b> Test any seller with Apify's $5 free monthly credit • No upfront commitment</sub></p>
</div>

---

## 💰 Transparent Pay-Per-Event (PPE) Pricing & Volume Tiers

Pay strictly for the results you collect — zero expensive monthly commitments or wasted compute fees ($0.00 compute). Volume discounts are applied automatically based on your Apify subscription tier:

| Chargeable Event | Event Scope | 🆓 Free Tier | 🚀 Starter Tier | 📈 Scale Tier | 🏢 Business Tier |
| :--- | :--- | :---: | :---: | :---: | :---: |
| **`search-item`** | Product Search Results | **$0.0020** / item | **$0.0019** / item | **$0.0017** / item | **$0.0015** / item |
| **`detail-item`** | Deep Product Specifications | **$0.0030** / item | **$0.0028** / item | **$0.0025** / item | **$0.0022** / item |
| **`seller-item`** ⭐ | Active & Sold Shop Listings | **$0.0035** / item | **$0.0033** / item | **$0.0030** / item | **$0.0028** / item |
| **`seller-profile`** | Store Profile & Zhima Credit | **$0.0040** / store | **$0.0038** / store | **$0.0035** / store | **$0.0032** / store |
| **`seller-review`** | Buyer Review & Unboxing Photos | **$0.0010** / review | **$0.00095** / review | **$0.0009** / review | **$0.00085** / review |
| **`apify-actor-start`** | Negligible Start Fee | **$0.00001** | **$0.00001** | **$0.00001** | **$0.00001** |

### 📊 Monthly Yield per Apify Subscription Plan

| Plan Tier | Monthly Apify Credit | Search Items Extracted | Seller Catalogs Extracted | Buyer Reviews Audited | Best For |
| :--- | :---: | :---: | :---: | :---: | :--- |
| 🆓 **Free** | **$5** / mo *(Free trial)* | **~2,500 items** | **~1,400 listings** | **~5,000 reviews** | Due diligence, one-off supplier checks |
| 🚀 **Starter** | **$19** / mo | **~10,000 items** | **~5,700 listings** | **~20,000 reviews** | Resellers, shopping agents, dropshippers |
| 📈 **Scale** | **$199** / mo | **~117,000 items** | **~66,000 listings** | **~221,000 reviews** | Growing e-commerce brands & agencies |
| 🏢 **Business** | **$999** / mo | **~666,000 items** | **~356,000 listings** | **~1,175,000 reviews** | Enterprise procurement & ERP catalog sync |

---

## 🧩 The Goofish Scraper Ecosystem

Combine our specialized scrapers to build complete market intelligence pipelines across Alibaba's secondhand marketplace:

| Scraper | Focus | Best For | Status |
| :--- | :--- | :--- | :--- |
| 🔍 **[Goofish Search & Deals Scraper](https://apify.com/unitbytes/goofish-xianyu-search-scraper?fpr=939u3w&fp_sid=gh_goofish)** | Keyword discovery, market price alerts, deals | Finding items by keyword, tracking category trends | 🟢 **Published** |
| 🏬 **[Goofish Sellers & Reviews Scraper](https://apify.com/unitbytes/goofish-scraper?fpr=939u3w&fp_sid=gh_goofish_seller)** | Profiles, shop inventory, buyer reviews, unboxing photos | Deep seller vetting, catalog extraction, supplier audits | 🌟 **You are here** |

---

## 🤖 Copy to Your AI Assistant (Apify Agent Prompt)

If you are using **Cursor**, **ChatGPT**, **Claude**, or autonomous agents, paste this snippet directly:

```text
Apify Actor UnitBytes/goofish-scraper. Extracts complete Goofish (闲鱼 / Xianyu / Idlefish) seller intelligence, product inventory catalogs, and buyer transaction reviews. Accepts seller profile URLs, product listing URLs (resolves seller automatically), fleamarket:// mobile deeplinks, or numeric seller IDs. Supports dual output formats: nested JSON (1 record per seller for APIs) or tabular flat rows (clean spreadsheets for Excel/CSV).
Call via ApifyClient:
client.actor("unitbytes/goofish-scraper").call(run_input={"sellerInputs":["https://www.goofish.com/personal?spm=a21ybx.item.itemHeader.1.740c3da6vQDa24&userId=2216555697343"],"includeListings":true,"includeReviews":true,"maxListings":20,"maxReviews":30,"outputFormat":"nested"})
```

---

## 🎯 Popular Use Cases

### 1. Cross-Border Supplier & Seller Due Diligence
Before wiring funds or purchasing high-ticket items through shopping agents (**Superbuy, Pandabuy, Sugargoo, CSSBuy, Mulebuy**), audit the seller's complete reputation:
- Verify Zhima Credit ratings (芝麻信用等级).
- Check real-name and real-person identity badges.
- Isolate negative buyer feedback (`reviewFilter: "negative_only"`) to identify fake goods, Bait-and-Switch tactics, or poor communication.

### 2. E-Commerce & Dropshipping Catalog Sourcing
Discover high-volume, reliable Chinese merchants. Export their complete active product listings (`statusFilter: "onsale"`), along with high-definition original product photos, descriptions, and structured specifications.

### 3. Competitor Tracking & Inventory Turnover Velocity
Track how fast items sell by comparing active listings against sold items (`statusFilter: "sold"`). Monitor historical selling prices, discount frequencies, and buyer review volume over time.

### 4. Brand Protection & Counterfeit Intelligence
Monitor unauthorized liquidations, grey-market imports, and replica sellers. Extract high-resolution buyer unboxing photos (`reviewImages`) to build verified evidence of intellectual property violations.

---

## 📥 Input Settings & Parameters

| Parameter | Type | Default | Description |
| :--- | :--- | :--- | :--- |
| `sellerInputs` | Array | `["2216555697343"]` | Target seller profile URLs (`https://www.goofish.com/personal?userId=...`), product listing URLs (`https://www.goofish.com/item?id=...`), mobile deeplinks (`fleamarket://...`), or numeric IDs. |
| `includeListings` | Boolean | `true` | Extract product listings and inventory catalog from target sellers. |
| `includeReviews` | Boolean | `true` | Extract buyer reviews, star ratings, and unboxing photos. |
| `maxListings` | Number | `20` | Maximum product listings to extract per seller (supports extracting complete shops with thousands of items; set `0` for unlimited complete catalog extraction). |
| `maxReviews` | Number | `30` | Maximum buyer reviews to extract per seller (supports extracting all historical reviews; set `0` for unlimited). |
| `detailLevel` | String | `"summary"` | Listing extraction depth: `"summary"` (ultra-fast card data) or `"full"` (deep specs, brand, model, condition grade, and full description). |
| `statusFilter` | String | `"all"` | Filter listings by status: `"all"` (everything), `"onsale"` (active stock only), or `"sold"` (completed sales only). |
| `reviewFilter` | String | `"all"` | Filter buyer reviews: `"all"`, `"negative_only"` (disputes & complaints), `"with_photos"` (unboxing images), or `"positive_only"`. |
| `outputFormat` | String | `"nested"` | Output structure: `"nested"` (1 unified JSON per seller for APIs) or `"tabular"` (flat rows optimized for Excel / CSV export). |
| `proxyConfiguration` | Object | `Residential Proxy` | Residential Proxy (HK / AP) is automatically enforced for maximum anti-bot stability. |

---

## 💻 Input Samples

### Sample 1: Comprehensive Seller Reputation & Catalog Audit
```json
{
  "sellerInputs": [
    "https://www.goofish.com/personal?spm=a21ybx.item.itemHeader.1.740c3da6vQDa24&userId=2216555697343"
  ],
  "includeListings": true,
  "includeReviews": true,
  "maxListings": 20,
  "maxReviews": 50,
  "detailLevel": "full",
  "statusFilter": "all",
  "reviewFilter": "all",
  "outputFormat": "nested"
}
```

### Sample 2: Direct Item Link Resolution (Auto-Detect Seller)
```json
{
  "sellerInputs": [
    "https://www.goofish.com/item?id=1084132717206"
  ],
  "includeListings": true,
  "includeReviews": true,
  "maxListings": 10,
  "maxReviews": 20,
  "detailLevel": "summary",
  "outputFormat": "nested"
}
```

### Sample 3: Excel & CSV Friendly Tabular Export
```json
{
  "sellerInputs": [
    "2212259311853"
  ],
  "includeListings": true,
  "includeReviews": false,
  "maxListings": 100,
  "statusFilter": "onsale",
  "detailLevel": "summary",
  "outputFormat": "tabular"
}
```

---

## 📤 Output Data Samples

### 1. Nested Output (`outputFormat: "nested"`)
*Delivers 1 consolidated JSON record per seller. Perfect for API backends, webhooks, and AI pipelines.*

```json
{
  "rowStatus": "ok",
  "recordType": "seller_complete",
  "id": "2217730303960",
  "displayName": "数码电玩玩家",
  "avatarUrl": "https://img.alicdn.com/sns_logo/i1/TB1xxx.jpg",
  "location": "广东深圳",
  "ipProvince": "广东",
  "verification": {
    "realName": true,
    "realPerson": true,
    "zhimaCredit": true,
    "verified": true
  },
  "creditBadge": {
    "role": "seller",
    "rating": "信用极好",
    "level": 5
  },
  "social": {
    "followers": 1420,
    "following": 86
  },
  "counts": {
    "activeListings": 48,
    "reviews": 312,
    "sold": 196
  },
  "responseRate": "98%",
  "listings": [
    {
      "id": "847291847192",
      "title": "任天堂 Switch OLED 日版 续航增强版 白色 99新",
      "price": 1450.0,
      "originalPrice": 2199.0,
      "status": "onsale",
      "freeShipping": true,
      "condition": "99新",
      "specs": {
        "品牌": "Nintendo/任天堂",
        "型号": "Switch OLED",
        "存储容量": "64GB",
        "包装": "原装全套"
      },
      "url": "https://www.goofish.com/item?id=847291847192"
    }
  ],
  "reviews": [
    {
      "reviewId": "918273645",
      "feedback": "成色非常新，顺丰很快，老板沟通很耐心，非常愉快的交易！",
      "rateType": "positive",
      "reviewerRole": "buyer",
      "reviewDate": "2026-03-15",
      "tradedItem": {
        "id": "847291847192",
        "title": "Switch 游戏卡带 塞尔达传说 王国之泪",
        "price": 280.0
      },
      "reviewImages": [
        "https://img.alicdn.com/bao/uploaded/i4/review_unboxing_1.jpg"
      ]
    }
  ]
}
```

### 2. Tabular Output (`outputFormat: "tabular"`)
*Delivers flat individual rows tagged with `recordType: "item"` or `"review"`. Exports directly to CSV, Google Sheets, or Excel without nested JSON formatting issues.*

```json
{
  "rowStatus": "ok",
  "recordType": "item",
  "sellerId": "2217730303960",
  "sellerName": "数码电玩玩家",
  "sellerCreditRating": "信用极好",
  "sellerLocation": "广东深圳",
  "itemId": "847291847192",
  "title": "任天堂 Switch OLED 日版 续航增强版 白色 99新",
  "price": 1450.0,
  "originalPrice": 2199.0,
  "status": "onsale",
  "freeShipping": true,
  "url": "https://www.goofish.com/item?id=847291847192"
}
```

---

## 🐍 Programmatic Integration

### Python (`apify-client`)
```python
from apify_client import ApifyClient

client = ApifyClient("YOUR_APIFY_API_TOKEN")

run_input = {
    "sellerInputs": ["https://www.goofish.com/personal?spm=a21ybx.item.itemHeader.1.740c3da6vQDa24&userId=2216555697343"],
    "includeListings": True,
    "includeReviews": True,
    "maxListings": 30,
    "maxReviews": 50,
    "detailLevel": "full",
    "outputFormat": "nested"
}

run = client.actor("unitbytes/goofish-scraper").call(run_input=run_input)

for item in client.dataset(run["defaultDatasetId"]).iterate_items():
    print(f"Seller: {item.get('displayName')} | Zhima: {item.get('creditBadge', {}).get('rating')}")
    print(f"Listings: {len(item.get('listings', []))} | Reviews: {len(item.get('reviews', []))}")
```

### JavaScript / Node.js (`apify-client`)
```javascript
import { ApifyClient } from 'apify-client';

const client = new ApifyClient({
    token: 'YOUR_APIFY_API_TOKEN',
});

const input = {
    sellerInputs: ['https://www.goofish.com/personal?spm=a21ybx.item.itemHeader.1.740c3da6vQDa24&userId=2216555697343'],
    includeListings: true,
    includeReviews: true,
    maxListings: 20,
    outputFormat: 'nested',
};

const run = await client.actor("unitbytes/goofish-scraper").call(input);
const { items } = await client.dataset(run.defaultDatasetId).listItems();

console.log(`Extracted ${items.length} seller profiles!`);
```

---


---

### 🔌 MCP Server Setup: Claude Code, Cursor & AI Agents

Connect this scraper directly to **Claude Code**, **Claude Desktop**, **Cursor**, or any MCP-compatible AI agent via the hosted Apify MCP server:

```json
{
  "mcpServers": {
    "apify": {
      "type": "http",
      "url": "https://mcp.apify.com/?tools=actors,docs,unitbytes/goofish-scraper"
    }
  }
}
```
*No manual API token required in configuration if your client supports Apify OAuth sign-in. Alternatively, pass your Apify API Token in the authorization header.*

---

### 🤖 Ask an AI Assistant About This Scraper

Open a ready-to-run prompt about Goofish Xianyu Seller & Reviews Scraper in your favorite AI assistant:

- 💬 [ChatGPT](https://chatgpt.com/?q=Using%20the%20Goofish%20Seller%20%26%20Reviews%20Scraper%20on%20Apify%20%28https%3A//apify.com/unitbytes/goofish-scraper%29%2C%20walk%20me%20through%20vetting%20a%20cross-border%20supplier%27s%20unboxing%20reviews%20and%20sold%20history.%20Show%20me%20the%20input%20JSON%20and%20Python%20code.)
- 🧠 [Claude](https://claude.ai/new?q=Using%20the%20Goofish%20Seller%20%26%20Reviews%20Scraper%20on%20Apify%20%28https%3A//apify.com/unitbytes/goofish-scraper%29%2C%20walk%20me%20through%20vetting%20a%20cross-border%20supplier%27s%20unboxing%20reviews%20and%20sold%20history.%20Show%20me%20the%20input%20JSON%20and%20Python%20code.)
- 🔍 [Perplexity](https://www.perplexity.ai/search?q=Using%20the%20Goofish%20Seller%20%26%20Reviews%20Scraper%20on%20Apify%20%28https%3A//apify.com/unitbytes/goofish-scraper%29%2C%20walk%20me%20through%20vetting%20a%20cross-border%20supplier%27s%20unboxing%20reviews%20and%20sold%20history.%20Show%20me%20the%20input%20JSON%20and%20Python%20code.)

---

## ❓ Frequently Asked Questions

### Do I need a Chinese mobile number (+86) or Goofish account?
**No.** The scraper operates entirely autonomously in guest mode with automated session harvesting. No login, SMS codes, or personal account credentials are required.

### Can I paste an item link instead of a seller profile?
**Yes.** The scraper features automatic item resolution. Paste any Goofish item link (e.g. `https://www.goofish.com/item?id=...`), and the actor will identify the seller and scrape their complete profile, inventory, and reviews.

### What is the difference between `summary` and `full` detail level?
- `summary`: Extremely fast and cost-efficient. Fetches product titles, prices, primary images, locations, and status tags.
- `full`: Performs deep product inspection. Extracts the complete description text, exact physical condition grade, and structured specification attributes (`specs`).

### How do I export to Excel or Google Sheets without broken columns?
Set `"outputFormat": "tabular"`. This produces flat, spreadsheet-ready rows where each listing or review is its own record with seller metadata attached.

---

## 🔍 Related Keywords & Search Terms (SEO Index)

`Goofish Scraper` • `Goofish API` • `Goofish Seller Scraper` • `Goofish Store Catalog` • `Goofish Reviews Scraper` • `Goofish Buyer Feedback` • `Goofish Unboxing Photos` • `Goofish Zhima Credit Check` • `Goofish Sesame Credit` • `Xianyu Scraper` • `Xianyu API` • `Xianyu Seller Profile` • `Xianyu Shop Scraper` • `Xianyu Reviews` • `Xianyu Dispute Scanner` • `Idlefish Scraper` • `Idle Fish API` • `Idlefish Seller Data` • `Alibaba Secondhand Scraper` • `Taobao Flea Market Scraper` • `闲鱼爬虫` • `闲鱼数据采集` • `闲鱼卖家信息采集` • `闲鱼评价采集` • `闲鱼店铺商品导出` • `闲鱼芝麻信用` • `闲鱼实名认证` • `闲鱼差评监控` • `Superbuy Goofish Check` • `Pandabuy Xianyu Seller Audit` • `Sugargoo Goofish Scraper` • `CSSBuy Seller Due Diligence` • `Mulebuy Xianyu Verification` • `CNfans Goofish` • `Kakobuy Goofish` • `Goofish Excel Export` • `Xianyu CSV Export` • `Goofish Google Sheets` • `Alibaba C2C Market Intelligence` • `Secondhand Luxury Scraper` • `Vintage Fashion Goofish` • `Used Electronics Wholesale Xianyu` • `Anime Figures Goofish Sourcing`

---

## 📄 License & Terms

This repository contains documentation, visual assets, and integration guides for the **Goofish Sellers & Reviews Scraper** hosted on the [Apify Platform](https://apify.com/unitbytes/goofish-scraper?fpr=939u3w&fp_sid=gh_goofish_seller). Distributed under the MIT License.

---

## 💬 Enterprise Support & Custom Pipelines
Need custom web data feeds, high-frequency scheduled runs, private cluster deployments, or dedicated SLAs?
- 📧 **Direct Email**: [contact@unitbytes.com](mailto:contact@unitbytes.com)
- 🌐 **Enterprise Platform**: [https://unitbytes.com](https://unitbytes.com)
- 💡 **Data Engine Specs & Live Docs**: [https://unitbytes.com/actors/goofish-scraper/](https://unitbytes.com/actors/goofish-scraper/)

---

## ⚖️ Disclaimer

This actor is an independent, third-party data extraction tool developed by **UnitBytes** for market research, price benchmarking, academic analysis, and e-commerce business intelligence.

- **Independent Tool:** This software is not affiliated with, authorized, maintained, sponsored, or endorsed by Goofish, Xianyu (闲鱼), Taobao, Alibaba Group, or any of their affiliates or subsidiaries.
- **Public Data Only:** This actor extracts only publicly accessible data available on the open web. It does not bypass private access restrictions or access authenticated personal account data.
- **Compliance & Fair Use:** Users are solely responsible for ensuring that their data collection activities comply with applicable local laws, regulations, and third-party terms of service. The developers assume no liability for misuse, policy violations, or actions taken based on data collected using this tool.
- **Trademarks:** "Goofish", "Xianyu", "闲鱼", "Taobao", and "Alibaba" are registered trademarks of Alibaba Group Holding Limited and/or their respective trademark holders. All trademarks, logos, and brand names referenced are the property of their respective owners and are used purely for identification and informational purposes.

