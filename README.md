[Facebook Search Pages](https://apify.com/patient_discovery/facebook-search-pages?fpr=data)

# **Facebook Page Search Results Scraper - No Login Required**

## **What does this scraper do?**

This actor extracts Facebook page search results based on keyword queries.

Enter a search term, run the actor, and receive structured data for Facebook pages matching your query.

No Facebook login, no cookies, no session handling required.

Cookieless architecture ensures stable, risk-free, and scalable automation.

## **Why scrape Facebook page search results?**

Facebook page search allows you to discover businesses, brands, and organizations by keyword. This helps marketers, analysts, and sales teams to:

- Build targeted prospect lists by niche or industry
- Identify competitor pages and emerging brands
- Discover verified business pages
- Enrich CRM systems with Facebook page data
- Generate qualified leads for outreach campaigns
- Analyze brand positioning within specific markets
- Build structured marketing and research databases

Its cookieless design fits scalable data pipelines without needing Facebook accounts.

## **How much will scraping cost?**

The pricing for this actor is **$2.50 per 1,000 scraped results**. Refer to the pricing page.

Because this actor does not require login or session management, it reduces operational complexity and lowers the risk associated with account-based scraping. This predictable architecture keeps your data pipelines highly stable.

## **How to use the scraper**

Here is a **step-by-step guide**:

**Step 1: Open the actor:** Go to your Apify Console and open the scraper.

**Step 2: Enter your input parameters:** In the input field, enter the keyword or search term (e.g., "digital marketing agency", "coffee shop", "fitness coaching").

**Step 3: Start the run:** Click Start to begin scraping. The actor will extract Facebook pages matching your search query.

**Step 4: Export or integrate:** Once complete, download the dataset in JSON, CSV, or connect it via API to your CRM, analytics platform, or marketing automation system.

## **Input parameters**

Below are the configuration options you can use to control the scraper.

**Input example**

```
{
  "query": "digital marketing agency"
}
```

| Field | Type | Description |
| --- | --- | --- |
| query | String | Search term or keyword used to find relevant Facebook pages |

## **What data does this scraper extract?**

**Formats**: JSON, CSV, Excel

**Key Fields Extracted**:

- `type` - Entity type (page)
- `profile_url` - Direct URL to the Facebook page
- `url` - Canonical page URL
- `name` - Page display name
- `facebook_id` - Unique Facebook page identifier
- `is_verified` - Verification status
- `image.uri` - Profile image URL
- `image.width` - Image width
- `image.height` - Image height
- `image.scale` - Image scale value

All data is returned as structured JSON with null-safe fields for reliable downstream processing.

## Sample Output

```
[
  {
    "type": "page",
    "profile_url": "https://www.facebook.com/techstartupshub",
    "url": "https://www.facebook.com/techstartupshub",
    "image": {
      "uri": "https://scontent.fknu1-3.fna.fbcdn.net/v/t39.30808-1/profile_image.jpg",
      "width": 120,
      "height": 120,
      "scale": 2
    },
    "name": "Tech Startups Hub",
    "facebook_id": "100075432198765",
    "is_verified": true
  }
]
```

All data is delivered in structured JSON format suitable for lead generation, competitive intelligence, and large-scale Facebook page discovery workflows.

## **Key Features:**

- 📈 Extract Facebook pages by keyword search
- 📊 Capture page names, URLs, and verification status
- ⚡ Structured JSON output ready for analytics and automation
- 📈 Build targeted lead generation databases
- 📊 Export-ready formats including JSON, CSV, and Excel
- ⚡ Scalable architecture for high-volume keyword searches
- 🔒 Fully cookieless architecture with no login required

## **FAQs**

**Does this scraper require Facebook login?** No. It is fully cookieless and does not require login credentials.

**Can it scrape private profiles?** No. Only publicly accessible Facebook pages can be extracted.

**Can I run multiple keyword searches?** Yes. Run separate executions for each query or integrate via API for bulk processing.

**Other Facebook scrapers that you may find useful:**

[Facebook Page Search Scraper](https://apify.com/patient_discovery/facebook-search-pages)

[Facebook Group Posts Scraper](https://apify.com/patient_discovery/facebook-group-posts)

[Facebook Search Events Scraper](https://apify.com/patient_discovery/facebook-search-events)

[Facebook Page Details Scraper](https://apify.com/patient_discovery/facebook-page-details)

[Facebook Marketplace Details Scraper](https://apify.com/patient_discovery/facebook-marketplace-details)

[Facebook Page Reviews Scraper](https://apify.com/patient_discovery/facebook-page-reviews)

[Facebook Page Posts Scraper](https://apify.com/patient_discovery/facebook-page-posts)

[Facebook Search People Scraper](https://apify.com/patient_discovery/facebook-search-people)