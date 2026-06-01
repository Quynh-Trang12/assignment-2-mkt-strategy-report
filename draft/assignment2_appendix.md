# Appendix — Assignment 2

This appendix supplements the Marketing Strategy Report for G'MORNIN Rise & Shine black tea bags by providing the GenAI use statement, specific prompts, the Shopee competitor price ladder, and the audit log of all MCP queries and sources fetched.

---

## 1. GenAI Use Statement & Prompts Used

**Statement of GenAI Use:**  
I used generative AI (Gemini 3.5 Flash) to assist in structuring this report, analyzing the Shopee competitor pricing dataset, mapping competitors on the ASCII positioning map, generating the MASDA targeting justification, and formatting references to follow the APA 7th edition standard. All factual inputs were verified from primary and secondary sources.

### Prompts Used:
1. *"Review requirements/Assignment 2 - Marketing Strategy Report.md and draft a Table of Contents that matches the official Swinburne assessment criteria and rubric."*
2. *"Based on the Shopee black tea price scan in draft/web_scrape_results/shopee_blacktea_50g_products.json, build a price ladder ranking products from lowest price to highest price for a 25x2g box format."*
3. *"Write a draft of Section 1 - The Marketing Environment focusing on Suppliers as the microenvironment factor (referencing Ahlstrom and Nonwoven Network compostability certifications) and Cultural forces as the macro force (focusing on the green consumerism trend in Vietnam)."*
4. *"Write Section 3 - Segmentation and targeting for G'MORNIN Rise & Shine black tea bags, defining the primary target segment as Urban Eco-Professionals and justifying it using the MASDA criteria."*
5. *"Generate a clean, readable ASCII positioning map for Section 4, placing Savo, Cozy, Phúc Long, Twinings, Dilmah, and G'MORNIN. Justify their relative positions based on benefits and price."*

---

## 2. Shopee Competitor Pricing Dataset

The table below is compiled from active Shopee marketplace product listings (VND for 25 × 2 g / 50 g boxes), ranked by price from lowest to highest. It forms the empirical basis for Section 4's pricing ladder and positioning map.

| Rank | Product Name | Brand / Seller | Price (VND) | Unit Format | Sold Count | Strategic Positioning Use |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| 1 | Trà Lài Savo (Hộp 25 Gói x 2g) | Cô Cam Bán Trà | 31,680₫ | 25 × 2 g | 88 Sold | Value Anchor (low price, low sustainability) |
| 2 | Trà Savo Red Label (Hộp 25 Gói x 2g) | Savo Official | 36,960₫ | 25 × 2 g | N/A | Mainstream Value |
| 3 | Trà Savo Black Label (Hộp 25 Gói x 2g) | Savo Official | 36,960₫ | 25 × 2 g | N/A | Mainstream Value |
| 4 | Trà Túi Lọc Phúc Long Đủ Vị | Lê Gia Wholesale | 48,000₫ | 25 × 2 g | 200k+ Sold | Mass-Market Scale (traditional local leader) |
| 5 | Trà Đen Nhãn Vàng Cozy Túi Lọc | Cozy Tea HCM | 49,000₫ | 25 × 2 g (50g) | 5k+ Sold | Mid-Market Local (direct black tea benchmark) |
| 6 | Trà Savo Bá Tước (Hộp 25 Gói x 2g) | Savo Official | 52,920₫ | 25 × 2 g | N/A | Premium Value |
| 7 | Trà Lài Túi Lọc Phúc Long (25 x 2g) | Cửa Hàng Nhỏ Xíu | 59,000₫ | 25 × 2 g | 10k+ Sold | Mass-Market Specialist (high familiarity) |
| 8 | Trà Thái Nguyên Túi Lọc Vinatea | Vinatea Official | 61,000₫ | 25 × 2 g (50g) | 1k+ Sold | Mid-Market Local (traditional green blend) |
| 9 | Trà Đen Hảo Hạng Vinatea Túi Lọc | Vinatea Official | 66,000₫ | 25 × 2 g (50g) | 1k+ Sold | Mid-Market Specialist (direct black tea benchmark) |
| 10 | Trà Dilmah Earl Grey Hộp 50g | Healthy Organic | 90,000₫ | 25 × 2 g (50g) | 897 Sold | Premium Imported (mid-high price) |
| 11 | Trà Túi Lọc Tía Tô APG ECO | APG Eco Mart | 147,050₫ | 25 × 2 g | 6k+ Sold | Premium Green/Herbal Category Reference |
| 12 | Trà Túi Lọc Bá Tước Twinings Earl Grey | Twinings Store | 172,000₫ | 25 × 2 g | 765 Sold | Ultra-Premium Imported (highest price benchmark) |

---

## 3. Audit Log of MCP Queries and Sources Fetched

The following log documents the research queries run during the development of this marketing strategy, along with the data retrieved and resolved status.

### Query 1: Market Size & Secondary Market Context
* **Tool Call:** `sequential-thinking` and `consensus-search`
* **Query String:** `"Vietnam tea market size 2024 retail price black tea bags Vietnam"`
* **Output/Data Sourced:** Surfaced market reports and industry summaries. Sourced headline market size figures from IMARC Group's public release.
* **Resolved Status:** **Resolved**. Vietnam tea market was valued at **USD 106.97 million in 2025** and is projected to reach **USD 155.40 million by 2034**, growing at a CAGR of 4.24%.Sourced from: [IMARC Group Report Summary](https://www.imarcgroup.com/vietnam-tea-market).

### Query 2: Supplier Material & Compostability Certification Feasibility
* **Tool Call:** `playwright-mcp` and `firecrawl-mcp-server`
* **Query String:** `"compostable tea bag filter supplier PLA abaca certification"`
* **Output/Data Sourced:** Scraped packaging supplier directories and official certification databases (BPI, OK Compost).
* **Resolved Status:** **Resolved**. Feasibility of compostable tea bag filters confirmed through active global supplier certifications:
  1. **Ahlstrom:** Offers heat-sealable PLA-based filter range (`InFuse™` and `BioWeb®` product lines) certified as industrially and home compostable under TÜV Austria (OK Compost) standards. Sourced from: [Ahlstrom Tea Solutions](https://www.ahlstrom.com/products/beverage-filter-media-and-packaging-solutions/tea-packaging-solutions/infuse-heatsealable-teabags/).
  2. **Nonwoven Network:** Sells `One Earth®` abaca-based tea filter media certified as USDA 100% BioBased, commercially compostable, and manufactured under ISO 9001:2015. Sourced from: [Nonwoven Network One Earth®](https://nonwovennetwork.com/).
  3. **YPAK Packaging:** Offers PLA/corn-starch biodegradable and compostable filter pouches with custom tags. Sourced from: [YPAK Biodegradable Tea Bag Filter](https://www.ypak-packaging.com/biodegradable-compostable-tea-bag-filter-with-string-paper-tag-for-tea-packaging-product/).

### Query 3: Academic Literature Search for Grounding Marketing Theory
* **Tool Call:** `consensus` and `paper-search-mcp`
* **Query Strings:** 
  - `"segmentation targeting positioning STP framework customer behavior"`
  - `"Vietnam sustainable eco-friendly packaging willingness to pay consumer survey"`
* **Output/Data Sourced:** Retrieved peer-reviewed papers on green packaging, willingness to pay, and STP. Sourced the following academic grounding:
  - **Segmentation & Positioning (STP):** Grounded in Kotler & Armstrong (2020), Proctor (2020), Dibb & Simkin (2008) for niche segmentation, and Ries & Trout (2001) for brand positioning.
  - **Qualitative Market Research:** Grounded in Malhotra et al. (2017) and Belk et al. (2013) for qualitative consumer inquiry.
  - **Vietnam Green WTP:** Nguyen et al. (2021) and Nhu-Ty Nguyen et al. (2021) confirm that urban Vietnamese consumers demonstrate a positive WTP for sustainable packaging, and that environmental concern and eco-label knowledge drive intention.
  - **Vietnam Green Barriers:** Nguyen-Viet (2023) models green purchase intentions, noting that mistrust and greenwashing are major threats that prevent attitude from translating to behavior.
  - **Vietnam Tea Packaging:** Khuong & Nguyen (2018) and Liu & Wang (2025) demonstrate that packaging design elements (graphics, shape, color) and brand experience have a positive, statistically significant impact on brand trust and tea purchase intentions.

---
**End of Appendix**
