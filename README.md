[Facebook Search Pages](https://apify.com/data-slayer/facebook-search-pages?fpr=data)

Extract Facebook page search results without authentication or cookies. This scraper enables social media marketers to build comprehensive contact databases and identify potential leads through keyword-based page discovery, all without requiring a Facebook account.

## 📺 Video Tutorial: How it Works

[Video](https://www.youtube.com/embed/C3Nuibjmqq4?enablejsapi=1&rel=0)

---

## Key Features

🔒 **Cookieless / No Login Required** - Access public Facebook page search results without authentication, eliminating account suspension risks and simplifying your workflow.

📈 **Scalable Architecture** - Process multiple search queries simultaneously to build extensive lead databases efficiently.

✅ **Rich Profile Data** - Capture essential page information including profile URLs, page names, Facebook IDs, verification status, and profile images with full metadata.

⚡ **Fast & Reliable** - Optimized extraction engine delivers consistent results with minimal latency for time-sensitive marketing campaigns.

📊 **Export-Ready Formats** - Download data in JSON, CSV, or Excel formats for immediate integration with CRM systems and marketing automation tools.

## Use Cases

**Social Media Marketers**: Build targeted prospect lists by searching for pages in specific niches or industries. Export contact data directly into your outreach campaigns to connect with potential brand partners or advertising opportunities.

**Market Research Analysts**: Identify competitor pages and emerging players in your market segment. Analyze page verification patterns and profile characteristics to understand market positioning and brand presence.

**Sales Development Teams**: Generate qualified leads by discovering business pages matching your ideal customer profile. Enrich your sales pipeline with verified Facebook page data for multi-channel outreach strategies.

## Inputs

| Field | Type | Description |
| --- | --- | --- |
| query | String | Search term or keyword to find relevant Facebook pages (e.g., "digital marketing agency", "coffee shop") |

## Outputs

**Formats**: JSON, CSV, Excel

**Fields**:

- `type` - Entity type (page)
- `profile_url` - Direct URL to the Facebook page
- `url` - Canonical page URL
- `name` - Page display name
- `facebook_id` - Unique Facebook page identifier
- `is_verified` - Verification status (true/false)
- `image` - Profile image object containing URI, width, height, and scale properties

## How to Use

**Step 1**: Enter your target search query in the `query` field (e.g., "fitness coaching", "real estate agents", "restaurants").

**Step 2**: Run the scraper to begin extracting page search results.

**Step 3**: Download your results in JSON, CSV, or Excel format for immediate use in your marketing tools.

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

## 🧩 Other Facebook Actors by Data Slayer

| Actor | What it does | Link |
| --- | --- | --- |
| Facebook Page Details Scraper | Get full page profiles — followers, contact info, ratings | [Try it](https://apify.com/data-slayer/facebook-page-details) |
| Facebook Reviews Scraper | Extract customer reviews from any Facebook page | [Try it](https://apify.com/data-slayer/facebook-page-reviews) |
| Facebook Posts Scraper | Extract posts from any Facebook page | [Try it](https://apify.com/data-slayer/facebook-page-posts) |
| Facebook Group Posts Scraper | Extract posts from any public Facebook group | [Try it](https://apify.com/data-slayer/facebook-group-posts) |
| Facebook People Search Scraper | Search and find Facebook profiles by keyword | [Try it](https://apify.com/data-slayer/facebook-search-people) |
| Facebook Events Scraper | Discover Facebook events by keyword search | [Try it](https://apify.com/data-slayer/facebook-search-events) |
| Facebook Marketplace Listing Scraper | Extract detailed listing data from Facebook Marketplace | [Try it](https://apify.com/data-slayer/facebook-marketplace-details) |

**Powerful workflow:** Search for pages here → feed those page URLs into [Facebook Page Details Scraper](https://apify.com/data-slayer/facebook-page-details) to get full business profiles with phone, email, website, and ratings.

## 💬 Feedback and Support

We actively maintain this actor and ship improvements based on user feedback. If you run into any issues or have ideas for new features:

- Create an issue on the Actor's **Issues tab** in Apify Console
- Rate the actor if it helped you — it helps others find it too
We typically respond within 24 hours.