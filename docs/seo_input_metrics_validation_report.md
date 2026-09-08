# SEO Input Metrics validation report

**Status:** PASS — append-ready

- Canonical template: August 2026 | SEO Input Metrics (https://docs.google.com/spreadsheets/d/1T6IbUsvldimwx-46hnRVfMiQxTXvvEqS-MaYEE5Cn7I/edit)
- Supplied Drive folder audit: 13/13 direct files accessible and 13/13 downloadable (checked 2026-09-08).
- Canonical header source: Site List Row 2 only; Row 1 was ignored.
- Canonical Row 2 fields: 64
- Output columns including derived and lineage fields: 76
- Output rows: 88,219
- Reporting months: 19
- Duplicate SITE_ID × REPORTING_MONTH keys: 0
- Rows with derived INSTALL_YEAR: 88,171
- Rows without INSTALL_YEAR because MONTH_ENROLLED is null: 48
- INSTALL_YEAR derivation mismatches: 0
- Preserved numeric zeros: 783,547
- Nullable canonical cells: 1,685,880
- CSV SHA-256: 14607fff2d7c6e5731cb6897238f645402c4ecec5faae28c2843d93e4158b17e

## Canonical Row 2 structure

| Position | Row 2 header | Snowflake column | Type |
|---:|---|---|---|
| 1 | Site | SITE | VARCHAR |
| 2 | Site ID | SITE_ID | VARCHAR |
| 3 | Month Enrolled | MONTH_ENROLLED | DATE |
| 4 | Service Level | SERVICE_LEVEL | VARCHAR |
| 5 | Vertical | VERTICAL | VARCHAR |
| 6 | GSC Status | GSC_STATUS | BOOLEAN |
| 7 | P6MA | P6MA | NUMBER(38,9) |
| 8 | Last Completed Mo | LAST_COMPLETED_MO | NUMBER(38,9) |
| 9 | Google PVs YTD | GOOGLE_PVS_YTD | NUMBER(38,9) |
| 10 | MoM% (Last 28 days) | MOM_PCT_LAST_28_DAYS | NUMBER(38,9) |
| 11 | YoY | YOY | NUMBER(38,9) |
| 12 | Yo2Y | YO2Y | NUMBER(38,9) |
| 13 | # of Total Wordpress Posts | TOTAL_WORDPRESS_POSTS | NUMBER(38,0) |
| 14 | Publishing Volume P3MA | PUBLISHING_VOLUME_P3MA | NUMBER(38,9) |
| 15 | Content Updates P3MA | CONTENT_UPDATES_P3MA | NUMBER(38,9) |
| 16 | Top 20% Content \| Median Age in Months | TOP_20_CONTENT_MEDIAN_AGE_MONTHS | NUMBER(38,9) |
| 17 | # Republishes \| Last Complete Month | REPUBLISHES_LAST_COMPLETE_MONTH | NUMBER(38,9) |
| 18 | Yield / publish (0-3 months) | YIELD_PUBLISH_0_3_MONTHS | NUMBER(38,9) |
| 19 | Yield / publish (3-6 months) | YIELD_PUBLISH_3_6_MONTHS | NUMBER(38,9) |
| 20 | Yield / publish (6-9 months) | YIELD_PUBLISH_6_9_MONTHS | NUMBER(38,9) |
| 21 | Yield / publish (9-12 months) | YIELD_PUBLISH_9_12_MONTHS | NUMBER(38,9) |
| 22 | Yield / publish (12+ months) | YIELD_PUBLISH_12_PLUS_MONTHS | NUMBER(38,9) |
| 23 | Yield / update (0-3 months) | YIELD_UPDATE_0_3_MONTHS | NUMBER(38,9) |
| 24 | Yield / update (3-6 months) | YIELD_UPDATE_3_6_MONTHS | NUMBER(38,9) |
| 25 | Yield / update (6-9 months) | YIELD_UPDATE_6_9_MONTHS | NUMBER(38,9) |
| 26 | Yield / update (9-12 months) | YIELD_UPDATE_9_12_MONTHS | NUMBER(38,9) |
| 27 | Yield / update (12+ months) | YIELD_UPDATE_12_PLUS_MONTHS | NUMBER(38,9) |
| 28 | Avg Word Count | AVG_WORD_COUNT | NUMBER(38,9) |
| 29 | # Pages < 500 words | PAGES_LT_500_WORDS | NUMBER(38,0) |
| 30 | % Pages < 500 words (Ratio of total WP Posts) | PCT_PAGES_LT_500_WORDS | NUMBER(38,9) |
| 31 | Authority Score (Semrush) | AUTHORITY_SCORE_SEMRUSH | NUMBER(38,9) |
| 32 | % Branded Search Volume | PCT_BRANDED_SEARCH_VOLUME | NUMBER(38,9) |
| 33 | Abs Branded Clicks | ABS_BRANDED_CLICKS | NUMBER(38,9) |
| 34 | % Branded Search Clicks | PCT_BRANDED_SEARCH_CLICKS | NUMBER(38,9) |
| 35 | Pageviews \| Email P3MA | PAGEVIEWS_EMAIL_P3MA | NUMBER(38,9) |
| 36 | Pageviews \| Pinterest P3MA | PAGEVIEWS_PINTEREST_P3MA | NUMBER(38,9) |
| 37 | Discover Clicks \| P3MA | DISCOVER_CLICKS_P3MA | NUMBER(38,9) |
| 38 | Discover Clicks \| Reporting Month | DISCOVER_CLICKS_REPORTING_MONTH | NUMBER(38,9) |
| 39 | Discover CTR \| P3MA | DISCOVER_CTR_P3MA | NUMBER(38,9) |
| 40 | Discover CTR \| Reporting Month | DISCOVER_CTR_REPORTING_MONTH | NUMBER(38,9) |
| 41 | GSC Clicks \| Reporting Month | GSC_CLICKS_REPORTING_MONTH | NUMBER(38,9) |
| 42 | Discover % \| Reporting Month | DISCOVER_PCT_REPORTING_MONTH | NUMBER(38,9) |
| 43 | GSC Clicks \| P3MA | GSC_CLICKS_P3MA | NUMBER(38,9) |
| 44 | Discover % \| P3MA | DISCOVER_PCT_P3MA | NUMBER(38,9) |
| 45 | Optimized OG Titles | OPTIMIZED_OG_TITLES | VARCHAR |
| 46 | Optimized OG Images | OPTIMIZED_OG_IMAGES | VARCHAR |
| 47 | Avg Ads-to-Content Ratio | AVG_ADS_TO_CONTENT_RATIO | NUMBER(38,9) |
| 48 | Mobile Ad Density | MOBILE_AD_DENSITY | NUMBER(38,9) |
| 49 | Avg Ads in View | AVG_ADS_IN_VIEW | NUMBER(38,9) |
| 50 | Avg Ad Refresh | AVG_AD_REFRESH | NUMBER(38,9) |
| 51 | Total Unique GPIDs | TOTAL_UNIQUE_GPIDS | NUMBER(38,0) |
| 52 | Avg Page Weight | AVG_PAGE_WEIGHT | NUMBER(38,9) |
| 53 | CLS | CLS | NUMBER(38,9) |
| 54 | INP | INP | NUMBER(38,9) |
| 55 | LCP | LCP | NUMBER(38,9) |
| 56 | Workbook Access? (Y/N) | WORKBOOK_ACCESS | BOOLEAN |
| 57 | Workbook Visits | WORKBOOK_VISITS | NUMBER(38,0) |
| 58 | PTU Recs Given | PTU_RECS_GIVEN | NUMBER(38,0) |
| 59 | AS BIN | AS_BIN | VARCHAR |
| 60 | Active Bin | ACTIVE_BIN | VARCHAR |
| 61 | YoY Bin | YOY_BIN | VARCHAR |
| 62 | A2C Bin | A2C_BIN | VARCHAR |
| 63 | 1M Club? | ONE_MILLION_CLUB | BOOLEAN |
| 64 | PV Status | PV_STATUS | VARCHAR |

## Monthly coverage

| Reporting month | Rows | Scope status |
|---|---:|---|
| 2025-02-01 | 70 | PARTIAL |
| 2025-03-01 | 1,505 | PARTIAL |
| 2025-04-01 | 4,317 | COMPLETE_PARTITIONED |
| 2025-05-01 | 4,317 | COMPLETE_PARTITIONED |
| 2025-06-01 | 4,262 | COMPLETE_PARTITIONED |
| 2025-07-01 | 4,462 | COMPLETE_CONSOLIDATED |
| 2025-08-01 | 4,842 | COMPLETE_CONSOLIDATED |
| 2025-09-01 | 4,918 | COMPLETE_CONSOLIDATED |
| 2025-10-01 | 4,980 | COMPLETE_CONSOLIDATED |
| 2025-11-01 | 5,028 | COMPLETE_CONSOLIDATED |
| 2025-12-01 | 5,216 | COMPLETE_CONSOLIDATED |
| 2026-01-01 | 5,229 | COMPLETE_CONSOLIDATED |
| 2026-02-01 | 5,468 | COMPLETE_CONSOLIDATED |
| 2026-03-01 | 5,496 | COMPLETE_CONSOLIDATED |
| 2026-04-01 | 5,496 | COMPLETE_CONSOLIDATED |
| 2026-05-01 | 5,579 | COMPLETE_CONSOLIDATED |
| 2026-06-01 | 5,635 | COMPLETE_CONSOLIDATED |
| 2026-07-01 | 5,631 | COMPLETE_CONSOLIDATED |
| 2026-08-01 | 5,768 | COMPLETE_CONSOLIDATED |

## Source validation

| File | Month | Scope | Rows | Canonical fields present | Blank Row 2 data columns | Quality flags |
|---|---|---|---:|---:|---|---|
| SEO Input Metrics \| Feb 2025 | 2025-02-01 | LEGACY_70_SITE_SUBSET | 70 | 26/64 | None | PARTIAL_70_SITE_LEGACY_SCORECARD |
| [All Food View] SEO Input Metrics \| March 2025 | 2025-03-01 | FOOD | 1,505 | 22/64 | AF, AG | FOOD_ONLY; FULL_NETWORK_FILE_MARKED_DO_NOT_USE |
| [Food] SEO Input Metrics \| April 2025 | 2025-04-01 | FOOD | 1,505 | 22/64 | AG, AH | PARTITIONED_MONTH |
| [Non-Food] SEO Input Metrics \| April 2025 | 2025-04-01 | NON_FOOD | 2,812 | 22/64 | AF, AH | PARTITIONED_MONTH |
| [Food] May 2025 \| SEO Input Metrics | 2025-05-01 | FOOD | 1,505 | 26/64 | AM | PARTITIONED_MONTH |
| [Non-Food] May 2025 \| SEO Input Metrics | 2025-05-01 | NON_FOOD | 2,812 | 22/64 | AF, AH | PARTITIONED_MONTH; MOST_METRIC_COLUMNS_POPULATED_FOR_ONE_ROW_ONLY |
| [Food] June 2025 \| SEO Input Metrics | 2025-06-01 | FOOD | 1,532 | 26/64 | AO | PARTITIONED_MONTH |
| [Non-Food] June 2025 \| SEO Input Metrics | 2025-06-01 | NON_FOOD | 2,730 | 26/64 | None | PARTITIONED_MONTH; ONE_ROW_SITE_NAME_LITERAL_SITE |
| 🟢 July 2025 \| SEO Input Metrics | 2025-07-01 | NETWORK | 4,462 | 47/64 | AX, AZ | HISTORICAL_QUERY_EXCLUDED_ENTERPRISE |
| 🟢 August 2025 \| SEO Input Metrics | 2025-08-01 | NETWORK | 4,842 | 48/64 | AY, AZ, BA, BB | HISTORICAL_QUERY_EXCLUDED_ENTERPRISE |
| 🟢 September 2025 \| SEO Input Metrics | 2025-09-01 | NETWORK | 4,918 | 52/64 | BD, BE, BF, BG, BH | HISTORICAL_QUERY_EXCLUDED_ENTERPRISE |
| 🟢 October 2025 \| SEO Input Metrics | 2025-10-01 | NETWORK | 4,980 | 52/64 | BD, BE, BF, BG | HISTORICAL_QUERY_EXCLUDED_ENTERPRISE |
| 🟢 November 2025 \| SEO Input Metrics | 2025-11-01 | NETWORK | 5,028 | 60/64 | None | HISTORICAL_QUERY_EXCLUDED_ENTERPRISE |
| 🟢 December 2025 \| SEO Input Metrics | 2025-12-01 | NETWORK | 5,216 | 60/64 | None | HISTORICAL_QUERY_EXCLUDED_ENTERPRISE |
| 🟢 January 2026 \| SEO Input Metrics | 2026-01-01 | NETWORK | 5,229 | 60/64 | None | HISTORICAL_QUERY_EXCLUDED_ENTERPRISE |
| 🟢 February 2026 \| SEO Input Metrics | 2026-02-01 | NETWORK | 5,468 | 61/64 | None | HISTORICAL_QUERY_EXCLUDED_ENTERPRISE |
| 🟢 March 2026 \| SEO Input Metrics | 2026-03-01 | NETWORK | 5,496 | 62/64 | None | HISTORICAL_QUERY_EXCLUDED_ENTERPRISE |
| 🟢 April 2026 \| SEO Input Metrics | 2026-04-01 | NETWORK | 5,496 | 62/64 | None | HISTORICAL_QUERY_EXCLUDED_ENTERPRISE |
| 🟢 May 2026 \| SEO Input Metrics | 2026-05-01 | NETWORK | 5,579 | 64/64 | None | HISTORICAL_QUERY_EXCLUDED_ENTERPRISE |
| 🟢 June 2026 \| SEO Input Metrics | 2026-06-01 | NETWORK | 5,635 | 64/64 | None | HISTORICAL_QUERY_EXCLUDED_ENTERPRISE; PARTIAL_REFRESH_CARRIED_FORWARD_METRICS |
| 🟢 July 2026 SEO Input Metrics | 2026-07-01 | NETWORK | 5,631 | 64/64 | None | HISTORICAL_QUERY_EXCLUDED_ENTERPRISE; ROUNDUPS_BLOCKED; WORD_COUNT_BLOCKED; DISCOVER_SHARE_P3MA_DEFINITION_CONFLICT |
| August 2026 \| SEO Input Metrics | 2026-08-01 | NETWORK | 5,768 | 64/64 | None | CANONICAL_ROW2_TEMPLATE |

## Missing canonical fields by source

### SEO Input Metrics | Feb 2025 (2025-02-01)

A2C_BIN, ABS_BRANDED_CLICKS, ACTIVE_BIN, AS_BIN, AVG_ADS_IN_VIEW, AVG_ADS_TO_CONTENT_RATIO, AVG_AD_REFRESH, AVG_PAGE_WEIGHT, CLS, DISCOVER_CTR_P3MA, DISCOVER_CTR_REPORTING_MONTH, GSC_STATUS, INP, LCP, MOBILE_AD_DENSITY, MOM_PCT_LAST_28_DAYS, ONE_MILLION_CLUB, OPTIMIZED_OG_IMAGES, OPTIMIZED_OG_TITLES, PCT_BRANDED_SEARCH_CLICKS, PCT_PAGES_LT_500_WORDS, PTU_RECS_GIVEN, PV_STATUS, REPUBLISHES_LAST_COMPLETE_MONTH, TOTAL_UNIQUE_GPIDS, WORKBOOK_ACCESS, WORKBOOK_VISITS, YIELD_PUBLISH_0_3_MONTHS, YIELD_PUBLISH_12_PLUS_MONTHS, YIELD_PUBLISH_3_6_MONTHS, YIELD_PUBLISH_6_9_MONTHS, YIELD_PUBLISH_9_12_MONTHS, YIELD_UPDATE_0_3_MONTHS, YIELD_UPDATE_12_PLUS_MONTHS, YIELD_UPDATE_3_6_MONTHS, YIELD_UPDATE_6_9_MONTHS, YIELD_UPDATE_9_12_MONTHS, YOY_BIN

### [All Food View] SEO Input Metrics | March 2025 (2025-03-01)

A2C_BIN, ABS_BRANDED_CLICKS, ACTIVE_BIN, AS_BIN, AVG_ADS_IN_VIEW, AVG_ADS_TO_CONTENT_RATIO, AVG_AD_REFRESH, AVG_PAGE_WEIGHT, CLS, DISCOVER_CTR_P3MA, DISCOVER_CTR_REPORTING_MONTH, DISCOVER_PCT_P3MA, DISCOVER_PCT_REPORTING_MONTH, GSC_CLICKS_P3MA, GSC_CLICKS_REPORTING_MONTH, GSC_STATUS, INP, LCP, MOBILE_AD_DENSITY, MOM_PCT_LAST_28_DAYS, ONE_MILLION_CLUB, OPTIMIZED_OG_IMAGES, OPTIMIZED_OG_TITLES, PCT_BRANDED_SEARCH_CLICKS, PCT_BRANDED_SEARCH_VOLUME, PTU_RECS_GIVEN, PV_STATUS, REPUBLISHES_LAST_COMPLETE_MONTH, TOTAL_UNIQUE_GPIDS, WORKBOOK_ACCESS, WORKBOOK_VISITS, YIELD_PUBLISH_0_3_MONTHS, YIELD_PUBLISH_12_PLUS_MONTHS, YIELD_PUBLISH_3_6_MONTHS, YIELD_PUBLISH_6_9_MONTHS, YIELD_PUBLISH_9_12_MONTHS, YIELD_UPDATE_0_3_MONTHS, YIELD_UPDATE_12_PLUS_MONTHS, YIELD_UPDATE_3_6_MONTHS, YIELD_UPDATE_6_9_MONTHS, YIELD_UPDATE_9_12_MONTHS, YOY_BIN

### [Food] SEO Input Metrics | April 2025 (2025-04-01)

A2C_BIN, ABS_BRANDED_CLICKS, ACTIVE_BIN, AS_BIN, AVG_ADS_IN_VIEW, AVG_ADS_TO_CONTENT_RATIO, AVG_AD_REFRESH, AVG_PAGE_WEIGHT, CLS, DISCOVER_CTR_P3MA, DISCOVER_CTR_REPORTING_MONTH, DISCOVER_PCT_P3MA, DISCOVER_PCT_REPORTING_MONTH, GSC_CLICKS_P3MA, GSC_CLICKS_REPORTING_MONTH, GSC_STATUS, INP, LCP, MOBILE_AD_DENSITY, MOM_PCT_LAST_28_DAYS, ONE_MILLION_CLUB, OPTIMIZED_OG_IMAGES, OPTIMIZED_OG_TITLES, PCT_BRANDED_SEARCH_CLICKS, PCT_BRANDED_SEARCH_VOLUME, PTU_RECS_GIVEN, PV_STATUS, REPUBLISHES_LAST_COMPLETE_MONTH, TOTAL_UNIQUE_GPIDS, WORKBOOK_ACCESS, WORKBOOK_VISITS, YIELD_PUBLISH_0_3_MONTHS, YIELD_PUBLISH_12_PLUS_MONTHS, YIELD_PUBLISH_3_6_MONTHS, YIELD_PUBLISH_6_9_MONTHS, YIELD_PUBLISH_9_12_MONTHS, YIELD_UPDATE_0_3_MONTHS, YIELD_UPDATE_12_PLUS_MONTHS, YIELD_UPDATE_3_6_MONTHS, YIELD_UPDATE_6_9_MONTHS, YIELD_UPDATE_9_12_MONTHS, YOY_BIN

### [Non-Food] SEO Input Metrics | April 2025 (2025-04-01)

A2C_BIN, ABS_BRANDED_CLICKS, ACTIVE_BIN, AS_BIN, AVG_ADS_IN_VIEW, AVG_ADS_TO_CONTENT_RATIO, AVG_AD_REFRESH, AVG_PAGE_WEIGHT, CLS, DISCOVER_CTR_P3MA, DISCOVER_CTR_REPORTING_MONTH, DISCOVER_PCT_P3MA, DISCOVER_PCT_REPORTING_MONTH, GSC_CLICKS_P3MA, GSC_CLICKS_REPORTING_MONTH, GSC_STATUS, INP, LCP, MOBILE_AD_DENSITY, MOM_PCT_LAST_28_DAYS, ONE_MILLION_CLUB, OPTIMIZED_OG_IMAGES, OPTIMIZED_OG_TITLES, PCT_BRANDED_SEARCH_CLICKS, PCT_BRANDED_SEARCH_VOLUME, PTU_RECS_GIVEN, PV_STATUS, REPUBLISHES_LAST_COMPLETE_MONTH, TOTAL_UNIQUE_GPIDS, WORKBOOK_ACCESS, WORKBOOK_VISITS, YIELD_PUBLISH_0_3_MONTHS, YIELD_PUBLISH_12_PLUS_MONTHS, YIELD_PUBLISH_3_6_MONTHS, YIELD_PUBLISH_6_9_MONTHS, YIELD_PUBLISH_9_12_MONTHS, YIELD_UPDATE_0_3_MONTHS, YIELD_UPDATE_12_PLUS_MONTHS, YIELD_UPDATE_3_6_MONTHS, YIELD_UPDATE_6_9_MONTHS, YIELD_UPDATE_9_12_MONTHS, YOY_BIN

### [Food] May 2025 | SEO Input Metrics (2025-05-01)

A2C_BIN, ABS_BRANDED_CLICKS, ACTIVE_BIN, AS_BIN, AVG_ADS_IN_VIEW, AVG_ADS_TO_CONTENT_RATIO, AVG_AD_REFRESH, AVG_PAGE_WEIGHT, DISCOVER_CTR_P3MA, DISCOVER_CTR_REPORTING_MONTH, DISCOVER_PCT_P3MA, DISCOVER_PCT_REPORTING_MONTH, GSC_CLICKS_P3MA, GSC_CLICKS_REPORTING_MONTH, GSC_STATUS, MOBILE_AD_DENSITY, ONE_MILLION_CLUB, OPTIMIZED_OG_IMAGES, OPTIMIZED_OG_TITLES, PCT_BRANDED_SEARCH_CLICKS, PCT_BRANDED_SEARCH_VOLUME, PTU_RECS_GIVEN, PV_STATUS, REPUBLISHES_LAST_COMPLETE_MONTH, TOTAL_UNIQUE_GPIDS, WORKBOOK_ACCESS, WORKBOOK_VISITS, YIELD_PUBLISH_0_3_MONTHS, YIELD_PUBLISH_12_PLUS_MONTHS, YIELD_PUBLISH_3_6_MONTHS, YIELD_PUBLISH_6_9_MONTHS, YIELD_PUBLISH_9_12_MONTHS, YIELD_UPDATE_0_3_MONTHS, YIELD_UPDATE_12_PLUS_MONTHS, YIELD_UPDATE_3_6_MONTHS, YIELD_UPDATE_6_9_MONTHS, YIELD_UPDATE_9_12_MONTHS, YOY_BIN

### [Non-Food] May 2025 | SEO Input Metrics (2025-05-01)

A2C_BIN, ABS_BRANDED_CLICKS, ACTIVE_BIN, AS_BIN, AVG_ADS_IN_VIEW, AVG_ADS_TO_CONTENT_RATIO, AVG_AD_REFRESH, AVG_PAGE_WEIGHT, CLS, DISCOVER_CTR_P3MA, DISCOVER_CTR_REPORTING_MONTH, DISCOVER_PCT_P3MA, DISCOVER_PCT_REPORTING_MONTH, GSC_CLICKS_P3MA, GSC_CLICKS_REPORTING_MONTH, GSC_STATUS, INP, LCP, MOBILE_AD_DENSITY, MOM_PCT_LAST_28_DAYS, ONE_MILLION_CLUB, OPTIMIZED_OG_IMAGES, OPTIMIZED_OG_TITLES, PCT_BRANDED_SEARCH_CLICKS, PCT_BRANDED_SEARCH_VOLUME, PTU_RECS_GIVEN, PV_STATUS, REPUBLISHES_LAST_COMPLETE_MONTH, TOTAL_UNIQUE_GPIDS, WORKBOOK_ACCESS, WORKBOOK_VISITS, YIELD_PUBLISH_0_3_MONTHS, YIELD_PUBLISH_12_PLUS_MONTHS, YIELD_PUBLISH_3_6_MONTHS, YIELD_PUBLISH_6_9_MONTHS, YIELD_PUBLISH_9_12_MONTHS, YIELD_UPDATE_0_3_MONTHS, YIELD_UPDATE_12_PLUS_MONTHS, YIELD_UPDATE_3_6_MONTHS, YIELD_UPDATE_6_9_MONTHS, YIELD_UPDATE_9_12_MONTHS, YOY_BIN

### [Food] June 2025 | SEO Input Metrics (2025-06-01)

A2C_BIN, ABS_BRANDED_CLICKS, ACTIVE_BIN, AS_BIN, AVG_ADS_IN_VIEW, AVG_ADS_TO_CONTENT_RATIO, AVG_AD_REFRESH, AVG_PAGE_WEIGHT, DISCOVER_CTR_P3MA, DISCOVER_CTR_REPORTING_MONTH, DISCOVER_PCT_P3MA, DISCOVER_PCT_REPORTING_MONTH, GSC_CLICKS_P3MA, GSC_CLICKS_REPORTING_MONTH, GSC_STATUS, MOBILE_AD_DENSITY, ONE_MILLION_CLUB, OPTIMIZED_OG_IMAGES, OPTIMIZED_OG_TITLES, PCT_BRANDED_SEARCH_CLICKS, PCT_BRANDED_SEARCH_VOLUME, PTU_RECS_GIVEN, PV_STATUS, REPUBLISHES_LAST_COMPLETE_MONTH, TOTAL_UNIQUE_GPIDS, WORKBOOK_ACCESS, WORKBOOK_VISITS, YIELD_PUBLISH_0_3_MONTHS, YIELD_PUBLISH_12_PLUS_MONTHS, YIELD_PUBLISH_3_6_MONTHS, YIELD_PUBLISH_6_9_MONTHS, YIELD_PUBLISH_9_12_MONTHS, YIELD_UPDATE_0_3_MONTHS, YIELD_UPDATE_12_PLUS_MONTHS, YIELD_UPDATE_3_6_MONTHS, YIELD_UPDATE_6_9_MONTHS, YIELD_UPDATE_9_12_MONTHS, YOY_BIN

### [Non-Food] June 2025 | SEO Input Metrics (2025-06-01)

A2C_BIN, ABS_BRANDED_CLICKS, ACTIVE_BIN, AS_BIN, AVG_ADS_IN_VIEW, AVG_ADS_TO_CONTENT_RATIO, AVG_AD_REFRESH, AVG_PAGE_WEIGHT, DISCOVER_CTR_P3MA, DISCOVER_CTR_REPORTING_MONTH, DISCOVER_PCT_P3MA, DISCOVER_PCT_REPORTING_MONTH, GSC_CLICKS_P3MA, GSC_CLICKS_REPORTING_MONTH, GSC_STATUS, MOBILE_AD_DENSITY, ONE_MILLION_CLUB, OPTIMIZED_OG_IMAGES, OPTIMIZED_OG_TITLES, PCT_BRANDED_SEARCH_CLICKS, PCT_BRANDED_SEARCH_VOLUME, PTU_RECS_GIVEN, PV_STATUS, REPUBLISHES_LAST_COMPLETE_MONTH, TOTAL_UNIQUE_GPIDS, WORKBOOK_ACCESS, WORKBOOK_VISITS, YIELD_PUBLISH_0_3_MONTHS, YIELD_PUBLISH_12_PLUS_MONTHS, YIELD_PUBLISH_3_6_MONTHS, YIELD_PUBLISH_6_9_MONTHS, YIELD_PUBLISH_9_12_MONTHS, YIELD_UPDATE_0_3_MONTHS, YIELD_UPDATE_12_PLUS_MONTHS, YIELD_UPDATE_3_6_MONTHS, YIELD_UPDATE_6_9_MONTHS, YIELD_UPDATE_9_12_MONTHS, YOY_BIN

### 🟢 July 2025 | SEO Input Metrics (2025-07-01)

A2C_BIN, ABS_BRANDED_CLICKS, ACTIVE_BIN, AS_BIN, DISCOVER_PCT_P3MA, DISCOVER_PCT_REPORTING_MONTH, GSC_CLICKS_P3MA, GSC_CLICKS_REPORTING_MONTH, MOBILE_AD_DENSITY, ONE_MILLION_CLUB, OPTIMIZED_OG_IMAGES, PTU_RECS_GIVEN, PV_STATUS, REPUBLISHES_LAST_COMPLETE_MONTH, WORKBOOK_ACCESS, WORKBOOK_VISITS, YOY_BIN

### 🟢 August 2025 | SEO Input Metrics (2025-08-01)

A2C_BIN, ACTIVE_BIN, AS_BIN, DISCOVER_PCT_P3MA, DISCOVER_PCT_REPORTING_MONTH, GSC_CLICKS_P3MA, GSC_CLICKS_REPORTING_MONTH, MOBILE_AD_DENSITY, ONE_MILLION_CLUB, OPTIMIZED_OG_IMAGES, PTU_RECS_GIVEN, PV_STATUS, REPUBLISHES_LAST_COMPLETE_MONTH, WORKBOOK_ACCESS, WORKBOOK_VISITS, YOY_BIN

### 🟢 September 2025 | SEO Input Metrics (2025-09-01)

A2C_BIN, ACTIVE_BIN, AS_BIN, MOBILE_AD_DENSITY, ONE_MILLION_CLUB, OPTIMIZED_OG_IMAGES, PTU_RECS_GIVEN, PV_STATUS, REPUBLISHES_LAST_COMPLETE_MONTH, WORKBOOK_ACCESS, WORKBOOK_VISITS, YOY_BIN

### 🟢 October 2025 | SEO Input Metrics (2025-10-01)

A2C_BIN, ACTIVE_BIN, AS_BIN, MOBILE_AD_DENSITY, ONE_MILLION_CLUB, OPTIMIZED_OG_IMAGES, PTU_RECS_GIVEN, PV_STATUS, REPUBLISHES_LAST_COMPLETE_MONTH, WORKBOOK_ACCESS, WORKBOOK_VISITS, YOY_BIN

### 🟢 November 2025 | SEO Input Metrics (2025-11-01)

MOBILE_AD_DENSITY, OPTIMIZED_OG_IMAGES, PTU_RECS_GIVEN, PV_STATUS

### 🟢 December 2025 | SEO Input Metrics (2025-12-01)

MOBILE_AD_DENSITY, OPTIMIZED_OG_IMAGES, PTU_RECS_GIVEN, PV_STATUS

### 🟢 January 2026 | SEO Input Metrics (2026-01-01)

MOBILE_AD_DENSITY, OPTIMIZED_OG_IMAGES, PTU_RECS_GIVEN, PV_STATUS

### 🟢 February 2026 | SEO Input Metrics (2026-02-01)

MOBILE_AD_DENSITY, OPTIMIZED_OG_IMAGES, PV_STATUS

### 🟢 March 2026 | SEO Input Metrics (2026-03-01)

MOBILE_AD_DENSITY, OPTIMIZED_OG_IMAGES

### 🟢 April 2026 | SEO Input Metrics (2026-04-01)

MOBILE_AD_DENSITY, OPTIMIZED_OG_IMAGES

### 🟢 May 2026 | SEO Input Metrics (2026-05-01)

None.

### 🟢 June 2026 | SEO Input Metrics (2026-06-01)

None.

### 🟢 July 2026 SEO Input Metrics (2026-07-01)

None.

### August 2026 | SEO Input Metrics (2026-08-01)

None.

## Excluded historical Row 2 fields

These populated historical columns are outside the August 2026 canonical structure or represent incompatible definitions. They were not added to the output schema.

| Reporting month | Row 2 header | Source files |
|---|---|---|
| 2025-02-01 | About Us Page Includes Achievements (notable mentions, awards, interviews etc) | SEO Input Metrics \| Feb 2025 |
| 2025-02-01 | About Us Page Includes Background Information (brand history, values, mission, philosophy) | SEO Input Metrics \| Feb 2025 |
| 2025-02-01 | Adjusted MoM | SEO Input Metrics \| Feb 2025 |
| 2025-02-01 | Are There Ads on the About Us/Author Page/ Homepage? 1= ads in 2 or more pages 2= ads in one page 3 = no ads | SEO Input Metrics \| Feb 2025 |
| 2025-02-01 | Are They a Published Author | SEO Input Metrics \| Feb 2025 |
| 2025-02-01 | "As Featured On" Banner Links to Verified Mentioned | SEO Input Metrics \| Feb 2025 |
| 2025-02-01 | Author Audit Score | SEO Input Metrics \| Feb 2025 |
| 2025-02-01 | Author Page Includes Social Media Links | SEO Input Metrics \| Feb 2025 |
| 2025-02-01 | Avg distance to recipe card (px) | SEO Input Metrics \| Feb 2025 |
| 2025-02-01 | Avg image height (px) | SEO Input Metrics \| Feb 2025 |
| 2025-02-01 | Can you easily find the creators Full Name (First & Last Name) | SEO Input Metrics \| Feb 2025 |
| 2025-02-01 | Category Page Description (Description Word Count) | SEO Input Metrics \| Feb 2025 |
| 2025-02-01 | Category Page PVs \| Last Completed Month | SEO Input Metrics \| Feb 2025 |
| 2025-02-01 | Category Page PVs \| P3MA | SEO Input Metrics \| Feb 2025 |
| 2025-02-01 | Category Page Schema (ItemList Schema) | SEO Input Metrics \| Feb 2025 |
| 2025-02-01 | Category Page Titles (# of Optimized Titles) | SEO Input Metrics \| Feb 2025 |
| 2025-02-01 | Consistent Profile Images Across Social Media | SEO Input Metrics \| Feb 2025 |
| 2025-02-01 | Content Quality Grade (Automated Grade) | SEO Input Metrics \| Feb 2025 |
| 2025-02-01 | Content Quality (Qualitative Score) (SEO Program grade) 0 = lowest quality 3 = highest quality | SEO Input Metrics \| Feb 2025 |
| 2025-02-01 | Content Quality (Quantitative Score) | SEO Input Metrics \| Feb 2025 |
| 2025-02-01 | Content Quality Rollup Score | SEO Input Metrics \| Feb 2025 |
| 2025-02-01 | Content Updates (3mo avg) Bad = <11 Needs Work = 11-21 Good = 21+ | SEO Input Metrics \| Feb 2025 |
| 2025-02-01 | Content Updates Last Completed Month | SEO Input Metrics \| Feb 2025 |
| 2025-02-01 | Discover Clicks % Grade | SEO Input Metrics \| Feb 2025 |
| 2025-02-01 | Discover Image Width Defined as Last 5 Posits with OG Image dimension meeting 1200px+ standard | SEO Input Metrics \| Feb 2025 |
| 2025-02-01 | Displays Creator's Full Name | SEO Input Metrics \| Feb 2025 |
| 2025-02-01 | EEAT Grade | SEO Input Metrics \| Feb 2025 |
| 2025-02-01 | EEAT Rollup Score | SEO Input Metrics \| Feb 2025 |
| 2025-02-01 | Google Discover | SEO Input Metrics \| Feb 2025 |
| 2025-02-01 | Has a Byline | SEO Input Metrics \| Feb 2025 |
| 2025-02-01 | Has an "As Featured On" Banner | SEO Input Metrics \| Feb 2025 |
| 2025-02-01 | Has an Author Knowledge Graph | SEO Input Metrics \| Feb 2025 |
| 2025-02-01 | Has an Author Page | SEO Input Metrics \| Feb 2025 |
| 2025-02-01 | Has an Author Photo in Byline | SEO Input Metrics \| Feb 2025 |
| 2025-02-01 | Has an Author Widget | SEO Input Metrics \| Feb 2025 |
| 2025-02-01 | Homepage Displays EEAT Elements | SEO Input Metrics \| Feb 2025 |
| 2025-02-01 | "Long" OG Titles Defined as Last 5 Posts with OG Titles > 50 characters in length | SEO Input Metrics \| Feb 2025 |
| 2025-02-01 | Mentions Link to Source (direct link to where the creator was featured) | SEO Input Metrics \| Feb 2025 |
| 2025-02-01 | MoM | SEO Input Metrics \| Feb 2025 |
| 2025-02-01 | # of Update Opportunities # Posts in Position 4-10, 12mo+ old, received 1K+ impressions in 12mo | SEO Input Metrics \| Feb 2025 |
| 2025-02-01 | On-Page EEAT Score | SEO Input Metrics \| Feb 2025 |
| 2025-02-01 | Person Schema Implemented | SEO Input Metrics \| Feb 2025 |
| 2025-02-01 | Publishing Freshness Grade of Top 20% of Content by PVs Bad = 36mo+ old Needs Improvement = 12-36mo old Good = <12mo old | SEO Input Metrics \| Feb 2025 |
| 2025-02-01 | Publishing Volume (3mo avg) | SEO Input Metrics \| Feb 2025 |
| 2025-02-01 | Publishing Volume Last Completed Month | SEO Input Metrics \| Feb 2025 |
| 2025-02-01 | Publishing Volume P6MA | SEO Input Metrics \| Feb 2025 |
| 2025-02-01 | Roundups Usage? (2024 sitewide) | SEO Input Metrics \| Feb 2025 |
| 2025-02-01 | Site Authority Grade (using Domain Authority) | SEO Input Metrics \| Feb 2025 |
| 2025-02-01 | Site Structure (Category Pages) | SEO Input Metrics \| Feb 2025 |
| 2025-02-01 | Sitewide EEAT Score | SEO Input Metrics \| Feb 2025 |
| 2025-02-01 | The Author Widgest Showcase EEAT Elements | SEO Input Metrics \| Feb 2025 |
| 2025-02-01 | The Name Links to the Author Page | SEO Input Metrics \| Feb 2025 |
| 2025-02-01 | Top 10 Posts \| Median Age in Months | SEO Input Metrics \| Feb 2025 |
| 2025-02-01 | "Unique" OG Titles Defined as Last 5 Posts with OG Titles <50% similar to Title | SEO Input Metrics \| Feb 2025 |
| 2025-02-01 | Uses 1-Date Logic (Only shows "Published" date for new URLs, "Updated" for revisions) | SEO Input Metrics \| Feb 2025 |
| 2025-02-01 | Yield / post (90 day sum of Pageviews for new content, since publish date) | SEO Input Metrics \| Feb 2025 |
| 2025-03-01 | Category Page Description (Description Word Count) | [All Food View] SEO Input Metrics \| March 2025 |
| 2025-03-01 | Category Page PVs \| Last Completed Month | [All Food View] SEO Input Metrics \| March 2025 |
| 2025-03-01 | Category Page PVs \| P3MA | [All Food View] SEO Input Metrics \| March 2025 |
| 2025-03-01 | Category Page Titles (# of Optimized Titles) | [All Food View] SEO Input Metrics \| March 2025 |
| 2025-03-01 | Domain Authority (Ahrefs) | [All Food View] SEO Input Metrics \| March 2025 |
| 2025-03-01 | MoM | [All Food View] SEO Input Metrics \| March 2025 |
| 2025-03-01 | # of Update Opportunities # Posts in Position 4-10, 12mo+ old, received 1K+ impressions in 12mo | [All Food View] SEO Input Metrics \| March 2025 |
| 2025-03-01 | "Unique" OG Titles Defined as Last 5 Posts with OG Titles <50% similar to Title" | [All Food View] SEO Input Metrics \| March 2025 |
| 2025-03-01 | Yield / post (90 day avg of Pageviews for new content, since publish date) | [All Food View] SEO Input Metrics \| March 2025 |
| 2025-04-01 | Category Page Description (Description Word Count) | [Food] SEO Input Metrics \| April 2025; [Non-Food] SEO Input Metrics \| April 2025 |
| 2025-04-01 | Category Page PVs \| Last Completed Month | [Food] SEO Input Metrics \| April 2025; [Non-Food] SEO Input Metrics \| April 2025 |
| 2025-04-01 | Category Page PVs \| P3MA | [Food] SEO Input Metrics \| April 2025; [Non-Food] SEO Input Metrics \| April 2025 |
| 2025-04-01 | Category Page Titles (# of Optimized Titles) | [Food] SEO Input Metrics \| April 2025; [Non-Food] SEO Input Metrics \| April 2025 |
| 2025-04-01 | Domain Authority (Ahrefs) | [Food] SEO Input Metrics \| April 2025; [Non-Food] SEO Input Metrics \| April 2025 |
| 2025-04-01 | MoM | [Food] SEO Input Metrics \| April 2025; [Non-Food] SEO Input Metrics \| April 2025 |
| 2025-04-01 | # of Update Opportunities # Posts in Position 4-10, 12mo+ old, received 1K+ impressions in 12mo | [Food] SEO Input Metrics \| April 2025; [Non-Food] SEO Input Metrics \| April 2025 |
| 2025-04-01 | SEO Program Status | [Food] SEO Input Metrics \| April 2025 |
| 2025-04-01 | "Unique" OG Titles Defined as Last 5 Posts with OG Titles <50% similar to Title" | [Food] SEO Input Metrics \| April 2025; [Non-Food] SEO Input Metrics \| April 2025 |
| 2025-04-01 | Yield / post (90 day avg of Pageviews for new content, since publish date) | [Food] SEO Input Metrics \| April 2025; [Non-Food] SEO Input Metrics \| April 2025 |
| 2025-05-01 | Average Overlay Area | [Food] May 2025 \| SEO Input Metrics |
| 2025-05-01 | Average Secondary Content Density | [Food] May 2025 \| SEO Input Metrics |
| 2025-05-01 | Average Viewport Area | [Food] May 2025 \| SEO Input Metrics |
| 2025-05-01 | Category Page Description (Description Word Count) | [Food] May 2025 \| SEO Input Metrics; [Non-Food] May 2025 \| SEO Input Metrics |
| 2025-05-01 | Category Page PVs \| Last Completed Month | [Food] May 2025 \| SEO Input Metrics; [Non-Food] May 2025 \| SEO Input Metrics |
| 2025-05-01 | Category Page PVs \| P3MA | [Food] May 2025 \| SEO Input Metrics; [Non-Food] May 2025 \| SEO Input Metrics |
| 2025-05-01 | Category Page Titles (# of Optimized Titles) | [Food] May 2025 \| SEO Input Metrics; [Non-Food] May 2025 \| SEO Input Metrics |
| 2025-05-01 | MoM | [Food] May 2025 \| SEO Input Metrics; [Non-Food] May 2025 \| SEO Input Metrics |
| 2025-05-01 | # of Update Opportunities # Posts in Position 4-10, 12mo+ old, received 1K+ impressions in 12mo | [Food] May 2025 \| SEO Input Metrics; [Non-Food] May 2025 \| SEO Input Metrics |
| 2025-05-01 | SEO Program Status | [Food] May 2025 \| SEO Input Metrics |
| 2025-05-01 | "Unique" OG Titles Defined as Last 5 Posts with OG Titles <50% similar to Title" | [Food] May 2025 \| SEO Input Metrics; [Non-Food] May 2025 \| SEO Input Metrics |
| 2025-05-01 | Yield / post (90 day avg of Pageviews for new content, since publish date) | [Food] May 2025 \| SEO Input Metrics; [Non-Food] May 2025 \| SEO Input Metrics |
| 2025-06-01 | Average Overlay Area | [Food] June 2025 \| SEO Input Metrics; [Non-Food] June 2025 \| SEO Input Metrics |
| 2025-06-01 | Average Secondary Content Density | [Food] June 2025 \| SEO Input Metrics; [Non-Food] June 2025 \| SEO Input Metrics |
| 2025-06-01 | Average Viewport Area | [Food] June 2025 \| SEO Input Metrics; [Non-Food] June 2025 \| SEO Input Metrics |
| 2025-06-01 | Category Page Description (Description Word Count) | [Food] June 2025 \| SEO Input Metrics |
| 2025-06-01 | Category Page PVs \| Last Completed Month | [Food] June 2025 \| SEO Input Metrics; [Non-Food] June 2025 \| SEO Input Metrics |
| 2025-06-01 | Category Page PVs \| P3MA | [Food] June 2025 \| SEO Input Metrics; [Non-Food] June 2025 \| SEO Input Metrics |
| 2025-06-01 | Category Page Titles (# of Optimized Titles) | [Food] June 2025 \| SEO Input Metrics |
| 2025-06-01 | DA BIN | [Non-Food] June 2025 \| SEO Input Metrics |
| 2025-06-01 | "Long" OG Titles Average length of OG titles (# of characters) | [Food] June 2025 \| SEO Input Metrics; [Non-Food] June 2025 \| SEO Input Metrics |
| 2025-06-01 | MoM | [Food] June 2025 \| SEO Input Metrics; [Non-Food] June 2025 \| SEO Input Metrics |
| 2025-06-01 | # of Update Opportunities # Posts in Position 4-10, 12mo+ old, received 1K+ impressions in 12mo | [Food] June 2025 \| SEO Input Metrics; [Non-Food] June 2025 \| SEO Input Metrics |
| 2025-06-01 | Optimized OG Images Average width of OG images (px) | [Food] June 2025 \| SEO Input Metrics; [Non-Food] June 2025 \| SEO Input Metrics |
| 2025-06-01 | Unique OG Titles Average OG title vs. title tag similarity % | [Food] June 2025 \| SEO Input Metrics; [Non-Food] June 2025 \| SEO Input Metrics |
| 2025-06-01 | Yield / post (90 day avg of Pageviews for new content, since publish date) | [Food] June 2025 \| SEO Input Metrics; [Non-Food] June 2025 \| SEO Input Metrics |
| 2025-07-01 | # of Roundups \| Last Complete Month | 🟢 July 2025 \| SEO Input Metrics |
| 2025-07-01 | Optimized OG Images | 🟢 July 2025 \| SEO Input Metrics |
| 2025-08-01 | # of Roundups \| Last Complete Month | 🟢 August 2025 \| SEO Input Metrics |
| 2025-08-01 | Optimized OG Images | 🟢 August 2025 \| SEO Input Metrics |
| 2025-09-01 | # of Roundups \| Last Complete Month | 🟢 September 2025 \| SEO Input Metrics |
| 2025-09-01 | Optimized OG Images | 🟢 September 2025 \| SEO Input Metrics |
| 2025-09-01 | Roundup PVs \| Last Complete Month | 🟢 September 2025 \| SEO Input Metrics |
| 2025-10-01 | # of Roundups \| Last Complete Month | 🟢 October 2025 \| SEO Input Metrics |
| 2025-10-01 | Optimized OG Images | 🟢 October 2025 \| SEO Input Metrics |
| 2025-10-01 | Roundup PVs \| Last Complete Month | 🟢 October 2025 \| SEO Input Metrics |
| 2025-11-01 | # of Roundups \| Last Complete Month | 🟢 November 2025 \| SEO Input Metrics |
| 2025-11-01 | Optimized OG Images | 🟢 November 2025 \| SEO Input Metrics |
| 2025-11-01 | PTU Visits | 🟢 November 2025 \| SEO Input Metrics |
| 2025-11-01 | Roundup Discover Clicks \| Last Complete Month | 🟢 November 2025 \| SEO Input Metrics |
| 2025-11-01 | Roundup PVs \| Last Complete Month | 🟢 November 2025 \| SEO Input Metrics |
| 2025-12-01 | # of Roundups \| Last Complete Month | 🟢 December 2025 \| SEO Input Metrics |
| 2025-12-01 | Optimized OG Images | 🟢 December 2025 \| SEO Input Metrics |
| 2025-12-01 | PTU Visits | 🟢 December 2025 \| SEO Input Metrics |
| 2025-12-01 | Roundup Discover Clicks \| Last Complete Month | 🟢 December 2025 \| SEO Input Metrics |
| 2025-12-01 | Roundup PVs \| Last Complete Month | 🟢 December 2025 \| SEO Input Metrics |
| 2026-01-01 | # of Roundups \| Last Complete Month | 🟢 January 2026 \| SEO Input Metrics |
| 2026-01-01 | Optimized OG Images | 🟢 January 2026 \| SEO Input Metrics |
| 2026-01-01 | Roundup Discover Clicks \| Last Complete Month | 🟢 January 2026 \| SEO Input Metrics |
| 2026-01-01 | Roundup PVs \| Last Complete Month | 🟢 January 2026 \| SEO Input Metrics |
| 2026-02-01 | # of Roundups \| Last Complete Month | 🟢 February 2026 \| SEO Input Metrics |
| 2026-02-01 | Optimized OG Images | 🟢 February 2026 \| SEO Input Metrics |
| 2026-02-01 | Roundup Discover Clicks \| Last Complete Month | 🟢 February 2026 \| SEO Input Metrics |
| 2026-02-01 | Roundup PVs \| Last Complete Month | 🟢 February 2026 \| SEO Input Metrics |
| 2026-03-01 | # of Roundups \| Last Complete Month | 🟢 March 2026 \| SEO Input Metrics |
| 2026-03-01 | Optimized OG Images | 🟢 March 2026 \| SEO Input Metrics |
| 2026-03-01 | Roundup Discover Clicks \| Last Complete Month | 🟢 March 2026 \| SEO Input Metrics |
| 2026-03-01 | Roundup PVs \| Last Complete Month | 🟢 March 2026 \| SEO Input Metrics |
| 2026-04-01 | # of Roundups \| Last Complete Month | 🟢 April 2026 \| SEO Input Metrics |
| 2026-05-01 | # of Roundups \| Last Complete Month | 🟢 May 2026 \| SEO Input Metrics |
| 2026-05-01 | Roundup Discover Clicks \| Last Complete Month | 🟢 May 2026 \| SEO Input Metrics |
| 2026-05-01 | Roundup PVs \| Last Complete Month | 🟢 May 2026 \| SEO Input Metrics |
| 2026-06-01 | # of Roundups \| Last Complete Month | 🟢 June 2026 \| SEO Input Metrics |
| 2026-06-01 | Roundup Discover Clicks \| Last Complete Month | 🟢 June 2026 \| SEO Input Metrics |
| 2026-06-01 | Roundup PVs \| Last Complete Month | 🟢 June 2026 \| SEO Input Metrics |

## Header mappings

| Source Row 2 header | Canonical column | Source files |
|---|---|---|
| A2C Bin | A2C_BIN | August 2026 \| SEO Input Metrics; 🟢 April 2026 \| SEO Input Metrics; 🟢 December 2025 \| SEO Input Metrics; 🟢 February 2026 \| SEO Input Metrics; 🟢 January 2026 \| SEO Input Metrics; 🟢 July 2026 SEO Input Metrics; 🟢 June 2026 \| SEO Input Metrics; 🟢 March 2026 \| SEO Input Metrics; 🟢 May 2026 \| SEO Input Metrics; 🟢 November 2025 \| SEO Input Metrics |
| Abs Branded Clicks | ABS_BRANDED_CLICKS | August 2026 \| SEO Input Metrics; 🟢 April 2026 \| SEO Input Metrics; 🟢 August 2025 \| SEO Input Metrics; 🟢 December 2025 \| SEO Input Metrics; 🟢 February 2026 \| SEO Input Metrics; 🟢 January 2026 \| SEO Input Metrics; 🟢 July 2026 SEO Input Metrics; 🟢 June 2026 \| SEO Input Metrics; 🟢 March 2026 \| SEO Input Metrics; 🟢 May 2026 \| SEO Input Metrics; 🟢 November 2025 \| SEO Input Metrics; 🟢 October 2025 \| SEO Input Metrics; 🟢 September 2025 \| SEO Input Metrics |
| Active Bin | ACTIVE_BIN | August 2026 \| SEO Input Metrics; 🟢 April 2026 \| SEO Input Metrics; 🟢 December 2025 \| SEO Input Metrics; 🟢 February 2026 \| SEO Input Metrics; 🟢 January 2026 \| SEO Input Metrics; 🟢 July 2026 SEO Input Metrics; 🟢 June 2026 \| SEO Input Metrics; 🟢 March 2026 \| SEO Input Metrics; 🟢 May 2026 \| SEO Input Metrics; 🟢 November 2025 \| SEO Input Metrics |
| AS BIN | AS_BIN | August 2026 \| SEO Input Metrics; 🟢 April 2026 \| SEO Input Metrics; 🟢 December 2025 \| SEO Input Metrics; 🟢 February 2026 \| SEO Input Metrics; 🟢 January 2026 \| SEO Input Metrics; 🟢 July 2026 SEO Input Metrics; 🟢 June 2026 \| SEO Input Metrics; 🟢 March 2026 \| SEO Input Metrics; 🟢 May 2026 \| SEO Input Metrics; 🟢 November 2025 \| SEO Input Metrics |
| Authority Score (Semrush) | AUTHORITY_SCORE_SEMRUSH | August 2026 \| SEO Input Metrics; 🟢 April 2026 \| SEO Input Metrics; 🟢 August 2025 \| SEO Input Metrics; 🟢 December 2025 \| SEO Input Metrics; 🟢 February 2026 \| SEO Input Metrics; 🟢 January 2026 \| SEO Input Metrics; 🟢 July 2025 \| SEO Input Metrics; 🟢 July 2026 SEO Input Metrics; 🟢 June 2026 \| SEO Input Metrics; 🟢 March 2026 \| SEO Input Metrics; 🟢 May 2026 \| SEO Input Metrics; 🟢 November 2025 \| SEO Input Metrics; 🟢 October 2025 \| SEO Input Metrics; 🟢 September 2025 \| SEO Input Metrics |
| Domain Authority | AUTHORITY_SCORE_SEMRUSH | SEO Input Metrics \| Feb 2025 |
| Domain Authority (Semrush) | AUTHORITY_SCORE_SEMRUSH | [All Food View] SEO Input Metrics \| March 2025; [Food] June 2025 \| SEO Input Metrics; [Food] May 2025 \| SEO Input Metrics; [Food] SEO Input Metrics \| April 2025; [Non-Food] June 2025 \| SEO Input Metrics; [Non-Food] May 2025 \| SEO Input Metrics; [Non-Food] SEO Input Metrics \| April 2025 |
| AVG_ADS_IN_VIEW | AVG_ADS_IN_VIEW | 🟢 July 2025 \| SEO Input Metrics |
| Avg Ads in View | AVG_ADS_IN_VIEW | August 2026 \| SEO Input Metrics; 🟢 April 2026 \| SEO Input Metrics; 🟢 August 2025 \| SEO Input Metrics; 🟢 December 2025 \| SEO Input Metrics; 🟢 February 2026 \| SEO Input Metrics; 🟢 January 2026 \| SEO Input Metrics; 🟢 July 2026 SEO Input Metrics; 🟢 June 2026 \| SEO Input Metrics; 🟢 March 2026 \| SEO Input Metrics; 🟢 May 2026 \| SEO Input Metrics; 🟢 November 2025 \| SEO Input Metrics; 🟢 October 2025 \| SEO Input Metrics; 🟢 September 2025 \| SEO Input Metrics |
| AVG_ADS_TO_CONTENT_RATIO | AVG_ADS_TO_CONTENT_RATIO | 🟢 July 2025 \| SEO Input Metrics |
| Avg Ads-to-Content Ratio | AVG_ADS_TO_CONTENT_RATIO | August 2026 \| SEO Input Metrics; 🟢 April 2026 \| SEO Input Metrics; 🟢 August 2025 \| SEO Input Metrics; 🟢 December 2025 \| SEO Input Metrics; 🟢 February 2026 \| SEO Input Metrics; 🟢 January 2026 \| SEO Input Metrics; 🟢 July 2026 SEO Input Metrics; 🟢 June 2026 \| SEO Input Metrics; 🟢 March 2026 \| SEO Input Metrics; 🟢 May 2026 \| SEO Input Metrics; 🟢 November 2025 \| SEO Input Metrics; 🟢 October 2025 \| SEO Input Metrics; 🟢 September 2025 \| SEO Input Metrics |
| AVG_AD_REFRESH | AVG_AD_REFRESH | 🟢 July 2025 \| SEO Input Metrics |
| Avg Ad Refresh | AVG_AD_REFRESH | August 2026 \| SEO Input Metrics; 🟢 April 2026 \| SEO Input Metrics; 🟢 August 2025 \| SEO Input Metrics; 🟢 December 2025 \| SEO Input Metrics; 🟢 February 2026 \| SEO Input Metrics; 🟢 January 2026 \| SEO Input Metrics; 🟢 July 2026 SEO Input Metrics; 🟢 June 2026 \| SEO Input Metrics; 🟢 March 2026 \| SEO Input Metrics; 🟢 May 2026 \| SEO Input Metrics; 🟢 November 2025 \| SEO Input Metrics; 🟢 October 2025 \| SEO Input Metrics; 🟢 September 2025 \| SEO Input Metrics |
| AVG_PAGE_WEIGHT | AVG_PAGE_WEIGHT | 🟢 July 2025 \| SEO Input Metrics |
| Avg Page Weight | AVG_PAGE_WEIGHT | August 2026 \| SEO Input Metrics; 🟢 April 2026 \| SEO Input Metrics; 🟢 August 2025 \| SEO Input Metrics; 🟢 December 2025 \| SEO Input Metrics; 🟢 February 2026 \| SEO Input Metrics; 🟢 January 2026 \| SEO Input Metrics; 🟢 July 2026 SEO Input Metrics; 🟢 June 2026 \| SEO Input Metrics; 🟢 March 2026 \| SEO Input Metrics; 🟢 May 2026 \| SEO Input Metrics; 🟢 November 2025 \| SEO Input Metrics; 🟢 October 2025 \| SEO Input Metrics; 🟢 September 2025 \| SEO Input Metrics |
| Avg Word Count | AVG_WORD_COUNT | August 2026 \| SEO Input Metrics; SEO Input Metrics \| Feb 2025; [All Food View] SEO Input Metrics \| March 2025; [Food] June 2025 \| SEO Input Metrics; [Food] May 2025 \| SEO Input Metrics; [Food] SEO Input Metrics \| April 2025; [Non-Food] June 2025 \| SEO Input Metrics; [Non-Food] May 2025 \| SEO Input Metrics; [Non-Food] SEO Input Metrics \| April 2025; 🟢 April 2026 \| SEO Input Metrics; 🟢 August 2025 \| SEO Input Metrics; 🟢 December 2025 \| SEO Input Metrics; 🟢 February 2026 \| SEO Input Metrics; 🟢 January 2026 \| SEO Input Metrics; 🟢 July 2025 \| SEO Input Metrics; 🟢 July 2026 SEO Input Metrics; 🟢 June 2026 \| SEO Input Metrics; 🟢 March 2026 \| SEO Input Metrics; 🟢 May 2026 \| SEO Input Metrics; 🟢 November 2025 \| SEO Input Metrics; 🟢 October 2025 \| SEO Input Metrics; 🟢 September 2025 \| SEO Input Metrics |
| CLS | CLS | August 2026 \| SEO Input Metrics; [Food] June 2025 \| SEO Input Metrics; [Food] May 2025 \| SEO Input Metrics; [Non-Food] June 2025 \| SEO Input Metrics; 🟢 April 2026 \| SEO Input Metrics; 🟢 August 2025 \| SEO Input Metrics; 🟢 December 2025 \| SEO Input Metrics; 🟢 February 2026 \| SEO Input Metrics; 🟢 January 2026 \| SEO Input Metrics; 🟢 July 2025 \| SEO Input Metrics; 🟢 July 2026 SEO Input Metrics; 🟢 June 2026 \| SEO Input Metrics; 🟢 March 2026 \| SEO Input Metrics; 🟢 May 2026 \| SEO Input Metrics; 🟢 November 2025 \| SEO Input Metrics; 🟢 October 2025 \| SEO Input Metrics; 🟢 September 2025 \| SEO Input Metrics |
| Content Updates P3MA | CONTENT_UPDATES_P3MA | August 2026 \| SEO Input Metrics; SEO Input Metrics \| Feb 2025; [All Food View] SEO Input Metrics \| March 2025; [Food] June 2025 \| SEO Input Metrics; [Food] May 2025 \| SEO Input Metrics; [Food] SEO Input Metrics \| April 2025; [Non-Food] June 2025 \| SEO Input Metrics; [Non-Food] May 2025 \| SEO Input Metrics; [Non-Food] SEO Input Metrics \| April 2025; 🟢 April 2026 \| SEO Input Metrics; 🟢 August 2025 \| SEO Input Metrics; 🟢 December 2025 \| SEO Input Metrics; 🟢 February 2026 \| SEO Input Metrics; 🟢 January 2026 \| SEO Input Metrics; 🟢 July 2025 \| SEO Input Metrics; 🟢 July 2026 SEO Input Metrics; 🟢 June 2026 \| SEO Input Metrics; 🟢 March 2026 \| SEO Input Metrics; 🟢 May 2026 \| SEO Input Metrics; 🟢 November 2025 \| SEO Input Metrics; 🟢 October 2025 \| SEO Input Metrics; 🟢 September 2025 \| SEO Input Metrics |
| Discover Clicks \| P3MA | DISCOVER_CLICKS_P3MA | August 2026 \| SEO Input Metrics; SEO Input Metrics \| Feb 2025; [All Food View] SEO Input Metrics \| March 2025; [Food] June 2025 \| SEO Input Metrics; [Food] May 2025 \| SEO Input Metrics; [Food] SEO Input Metrics \| April 2025; [Non-Food] June 2025 \| SEO Input Metrics; [Non-Food] May 2025 \| SEO Input Metrics; [Non-Food] SEO Input Metrics \| April 2025; 🟢 April 2026 \| SEO Input Metrics; 🟢 August 2025 \| SEO Input Metrics; 🟢 December 2025 \| SEO Input Metrics; 🟢 February 2026 \| SEO Input Metrics; 🟢 January 2026 \| SEO Input Metrics; 🟢 July 2025 \| SEO Input Metrics; 🟢 July 2026 SEO Input Metrics; 🟢 June 2026 \| SEO Input Metrics; 🟢 March 2026 \| SEO Input Metrics; 🟢 May 2026 \| SEO Input Metrics; 🟢 November 2025 \| SEO Input Metrics; 🟢 October 2025 \| SEO Input Metrics; 🟢 September 2025 \| SEO Input Metrics |
| Discover Clicks \| Last Completed Month | DISCOVER_CLICKS_REPORTING_MONTH | SEO Input Metrics \| Feb 2025; [All Food View] SEO Input Metrics \| March 2025; [Food] June 2025 \| SEO Input Metrics; [Food] May 2025 \| SEO Input Metrics; [Food] SEO Input Metrics \| April 2025; [Non-Food] June 2025 \| SEO Input Metrics; [Non-Food] May 2025 \| SEO Input Metrics; [Non-Food] SEO Input Metrics \| April 2025 |
| Discover Clicks \| Reporting Month | DISCOVER_CLICKS_REPORTING_MONTH | August 2026 \| SEO Input Metrics; 🟢 April 2026 \| SEO Input Metrics; 🟢 August 2025 \| SEO Input Metrics; 🟢 December 2025 \| SEO Input Metrics; 🟢 February 2026 \| SEO Input Metrics; 🟢 January 2026 \| SEO Input Metrics; 🟢 July 2025 \| SEO Input Metrics; 🟢 July 2026 SEO Input Metrics; 🟢 June 2026 \| SEO Input Metrics; 🟢 March 2026 \| SEO Input Metrics; 🟢 May 2026 \| SEO Input Metrics; 🟢 November 2025 \| SEO Input Metrics; 🟢 October 2025 \| SEO Input Metrics; 🟢 September 2025 \| SEO Input Metrics |
| Discover CTR \| P3MA | DISCOVER_CTR_P3MA | August 2026 \| SEO Input Metrics; 🟢 April 2026 \| SEO Input Metrics; 🟢 August 2025 \| SEO Input Metrics; 🟢 December 2025 \| SEO Input Metrics; 🟢 February 2026 \| SEO Input Metrics; 🟢 January 2026 \| SEO Input Metrics; 🟢 July 2025 \| SEO Input Metrics; 🟢 July 2026 SEO Input Metrics; 🟢 June 2026 \| SEO Input Metrics; 🟢 March 2026 \| SEO Input Metrics; 🟢 May 2026 \| SEO Input Metrics; 🟢 November 2025 \| SEO Input Metrics; 🟢 October 2025 \| SEO Input Metrics; 🟢 September 2025 \| SEO Input Metrics |
| Discover CTR \| Reporting Month | DISCOVER_CTR_REPORTING_MONTH | August 2026 \| SEO Input Metrics; 🟢 April 2026 \| SEO Input Metrics; 🟢 August 2025 \| SEO Input Metrics; 🟢 December 2025 \| SEO Input Metrics; 🟢 February 2026 \| SEO Input Metrics; 🟢 January 2026 \| SEO Input Metrics; 🟢 July 2025 \| SEO Input Metrics; 🟢 July 2026 SEO Input Metrics; 🟢 June 2026 \| SEO Input Metrics; 🟢 March 2026 \| SEO Input Metrics; 🟢 May 2026 \| SEO Input Metrics; 🟢 November 2025 \| SEO Input Metrics; 🟢 October 2025 \| SEO Input Metrics; 🟢 September 2025 \| SEO Input Metrics |
| Discover Clicks % \| P3MA (Discover / GSC Clicks) | DISCOVER_PCT_P3MA | SEO Input Metrics \| Feb 2025 |
| Discover % \| P3MA | DISCOVER_PCT_P3MA | August 2026 \| SEO Input Metrics; 🟢 April 2026 \| SEO Input Metrics; 🟢 December 2025 \| SEO Input Metrics; 🟢 February 2026 \| SEO Input Metrics; 🟢 January 2026 \| SEO Input Metrics; 🟢 July 2026 SEO Input Metrics; 🟢 June 2026 \| SEO Input Metrics; 🟢 March 2026 \| SEO Input Metrics; 🟢 May 2026 \| SEO Input Metrics; 🟢 November 2025 \| SEO Input Metrics; 🟢 October 2025 \| SEO Input Metrics; 🟢 September 2025 \| SEO Input Metrics |
| Discover % \| Last Completed Month (Discover / GSC Clicks) | DISCOVER_PCT_REPORTING_MONTH | SEO Input Metrics \| Feb 2025 |
| Discover % \| Reporting Month | DISCOVER_PCT_REPORTING_MONTH | August 2026 \| SEO Input Metrics; 🟢 April 2026 \| SEO Input Metrics; 🟢 December 2025 \| SEO Input Metrics; 🟢 February 2026 \| SEO Input Metrics; 🟢 January 2026 \| SEO Input Metrics; 🟢 July 2026 SEO Input Metrics; 🟢 June 2026 \| SEO Input Metrics; 🟢 March 2026 \| SEO Input Metrics; 🟢 May 2026 \| SEO Input Metrics; 🟢 November 2025 \| SEO Input Metrics; 🟢 October 2025 \| SEO Input Metrics; 🟢 September 2025 \| SEO Input Metrics |
| Google PVs YTD | GOOGLE_PVS_YTD | August 2026 \| SEO Input Metrics; SEO Input Metrics \| Feb 2025; [All Food View] SEO Input Metrics \| March 2025; [Food] June 2025 \| SEO Input Metrics; [Food] May 2025 \| SEO Input Metrics; [Food] SEO Input Metrics \| April 2025; [Non-Food] June 2025 \| SEO Input Metrics; [Non-Food] May 2025 \| SEO Input Metrics; [Non-Food] SEO Input Metrics \| April 2025; 🟢 April 2026 \| SEO Input Metrics; 🟢 August 2025 \| SEO Input Metrics; 🟢 December 2025 \| SEO Input Metrics; 🟢 February 2026 \| SEO Input Metrics; 🟢 January 2026 \| SEO Input Metrics; 🟢 July 2025 \| SEO Input Metrics; 🟢 July 2026 SEO Input Metrics; 🟢 June 2026 \| SEO Input Metrics; 🟢 March 2026 \| SEO Input Metrics; 🟢 May 2026 \| SEO Input Metrics; 🟢 November 2025 \| SEO Input Metrics; 🟢 October 2025 \| SEO Input Metrics; 🟢 September 2025 \| SEO Input Metrics |
| GSC Clicks \| P3MA | GSC_CLICKS_P3MA | August 2026 \| SEO Input Metrics; SEO Input Metrics \| Feb 2025; 🟢 April 2026 \| SEO Input Metrics; 🟢 December 2025 \| SEO Input Metrics; 🟢 February 2026 \| SEO Input Metrics; 🟢 January 2026 \| SEO Input Metrics; 🟢 July 2026 SEO Input Metrics; 🟢 June 2026 \| SEO Input Metrics; 🟢 March 2026 \| SEO Input Metrics; 🟢 May 2026 \| SEO Input Metrics; 🟢 November 2025 \| SEO Input Metrics; 🟢 October 2025 \| SEO Input Metrics; 🟢 September 2025 \| SEO Input Metrics |
| GSC Clicks \| Last Completed Month | GSC_CLICKS_REPORTING_MONTH | SEO Input Metrics \| Feb 2025 |
| GSC Clicks \| Reporting Month | GSC_CLICKS_REPORTING_MONTH | August 2026 \| SEO Input Metrics; 🟢 April 2026 \| SEO Input Metrics; 🟢 December 2025 \| SEO Input Metrics; 🟢 February 2026 \| SEO Input Metrics; 🟢 January 2026 \| SEO Input Metrics; 🟢 July 2026 SEO Input Metrics; 🟢 June 2026 \| SEO Input Metrics; 🟢 March 2026 \| SEO Input Metrics; 🟢 May 2026 \| SEO Input Metrics; 🟢 November 2025 \| SEO Input Metrics; 🟢 October 2025 \| SEO Input Metrics; 🟢 September 2025 \| SEO Input Metrics |
| GSC Status | GSC_STATUS | August 2026 \| SEO Input Metrics; 🟢 April 2026 \| SEO Input Metrics; 🟢 August 2025 \| SEO Input Metrics; 🟢 December 2025 \| SEO Input Metrics; 🟢 February 2026 \| SEO Input Metrics; 🟢 January 2026 \| SEO Input Metrics; 🟢 July 2025 \| SEO Input Metrics; 🟢 July 2026 SEO Input Metrics; 🟢 June 2026 \| SEO Input Metrics; 🟢 March 2026 \| SEO Input Metrics; 🟢 May 2026 \| SEO Input Metrics; 🟢 November 2025 \| SEO Input Metrics; 🟢 October 2025 \| SEO Input Metrics; 🟢 September 2025 \| SEO Input Metrics |
| INP | INP | August 2026 \| SEO Input Metrics; [Food] June 2025 \| SEO Input Metrics; [Food] May 2025 \| SEO Input Metrics; [Non-Food] June 2025 \| SEO Input Metrics; 🟢 April 2026 \| SEO Input Metrics; 🟢 August 2025 \| SEO Input Metrics; 🟢 December 2025 \| SEO Input Metrics; 🟢 February 2026 \| SEO Input Metrics; 🟢 January 2026 \| SEO Input Metrics; 🟢 July 2025 \| SEO Input Metrics; 🟢 July 2026 SEO Input Metrics; 🟢 June 2026 \| SEO Input Metrics; 🟢 March 2026 \| SEO Input Metrics; 🟢 May 2026 \| SEO Input Metrics; 🟢 November 2025 \| SEO Input Metrics; 🟢 October 2025 \| SEO Input Metrics; 🟢 September 2025 \| SEO Input Metrics |
| Last Completed Mo | LAST_COMPLETED_MO | August 2026 \| SEO Input Metrics; SEO Input Metrics \| Feb 2025; [All Food View] SEO Input Metrics \| March 2025; [Food] June 2025 \| SEO Input Metrics; [Food] May 2025 \| SEO Input Metrics; [Food] SEO Input Metrics \| April 2025; [Non-Food] June 2025 \| SEO Input Metrics; [Non-Food] May 2025 \| SEO Input Metrics; [Non-Food] SEO Input Metrics \| April 2025; 🟢 April 2026 \| SEO Input Metrics; 🟢 August 2025 \| SEO Input Metrics; 🟢 December 2025 \| SEO Input Metrics; 🟢 February 2026 \| SEO Input Metrics; 🟢 January 2026 \| SEO Input Metrics; 🟢 July 2025 \| SEO Input Metrics; 🟢 July 2026 SEO Input Metrics; 🟢 June 2026 \| SEO Input Metrics; 🟢 March 2026 \| SEO Input Metrics; 🟢 May 2026 \| SEO Input Metrics; 🟢 November 2025 \| SEO Input Metrics; 🟢 October 2025 \| SEO Input Metrics; 🟢 September 2025 \| SEO Input Metrics |
| LCP | LCP | August 2026 \| SEO Input Metrics; [Food] June 2025 \| SEO Input Metrics; [Food] May 2025 \| SEO Input Metrics; [Non-Food] June 2025 \| SEO Input Metrics; 🟢 April 2026 \| SEO Input Metrics; 🟢 August 2025 \| SEO Input Metrics; 🟢 December 2025 \| SEO Input Metrics; 🟢 February 2026 \| SEO Input Metrics; 🟢 January 2026 \| SEO Input Metrics; 🟢 July 2025 \| SEO Input Metrics; 🟢 July 2026 SEO Input Metrics; 🟢 June 2026 \| SEO Input Metrics; 🟢 March 2026 \| SEO Input Metrics; 🟢 May 2026 \| SEO Input Metrics; 🟢 November 2025 \| SEO Input Metrics; 🟢 October 2025 \| SEO Input Metrics; 🟢 September 2025 \| SEO Input Metrics |
| Mobile Ad Density | MOBILE_AD_DENSITY | August 2026 \| SEO Input Metrics; 🟢 July 2026 SEO Input Metrics; 🟢 June 2026 \| SEO Input Metrics; 🟢 May 2026 \| SEO Input Metrics |
| MoM% (Last 28 days) | MOM_PCT_LAST_28_DAYS | August 2026 \| SEO Input Metrics; [Food] June 2025 \| SEO Input Metrics; [Food] May 2025 \| SEO Input Metrics; [Non-Food] June 2025 \| SEO Input Metrics; 🟢 April 2026 \| SEO Input Metrics; 🟢 August 2025 \| SEO Input Metrics; 🟢 December 2025 \| SEO Input Metrics; 🟢 February 2026 \| SEO Input Metrics; 🟢 January 2026 \| SEO Input Metrics; 🟢 July 2025 \| SEO Input Metrics; 🟢 July 2026 SEO Input Metrics; 🟢 June 2026 \| SEO Input Metrics; 🟢 March 2026 \| SEO Input Metrics; 🟢 May 2026 \| SEO Input Metrics; 🟢 November 2025 \| SEO Input Metrics; 🟢 October 2025 \| SEO Input Metrics; 🟢 September 2025 \| SEO Input Metrics |
| Month Enrolled | MONTH_ENROLLED | August 2026 \| SEO Input Metrics; SEO Input Metrics \| Feb 2025; [All Food View] SEO Input Metrics \| March 2025; [Food] June 2025 \| SEO Input Metrics; [Food] May 2025 \| SEO Input Metrics; [Food] SEO Input Metrics \| April 2025; [Non-Food] June 2025 \| SEO Input Metrics; [Non-Food] May 2025 \| SEO Input Metrics; [Non-Food] SEO Input Metrics \| April 2025; 🟢 April 2026 \| SEO Input Metrics; 🟢 August 2025 \| SEO Input Metrics; 🟢 December 2025 \| SEO Input Metrics; 🟢 February 2026 \| SEO Input Metrics; 🟢 January 2026 \| SEO Input Metrics; 🟢 July 2025 \| SEO Input Metrics; 🟢 July 2026 SEO Input Metrics; 🟢 June 2026 \| SEO Input Metrics; 🟢 March 2026 \| SEO Input Metrics; 🟢 May 2026 \| SEO Input Metrics; 🟢 November 2025 \| SEO Input Metrics; 🟢 October 2025 \| SEO Input Metrics; 🟢 September 2025 \| SEO Input Metrics |
| 1M Club? | ONE_MILLION_CLUB | August 2026 \| SEO Input Metrics; 🟢 April 2026 \| SEO Input Metrics; 🟢 December 2025 \| SEO Input Metrics; 🟢 February 2026 \| SEO Input Metrics; 🟢 January 2026 \| SEO Input Metrics; 🟢 July 2026 SEO Input Metrics; 🟢 June 2026 \| SEO Input Metrics; 🟢 March 2026 \| SEO Input Metrics; 🟢 May 2026 \| SEO Input Metrics; 🟢 November 2025 \| SEO Input Metrics |
| Optimized OG Images | OPTIMIZED_OG_IMAGES | August 2026 \| SEO Input Metrics; 🟢 July 2026 SEO Input Metrics; 🟢 June 2026 \| SEO Input Metrics; 🟢 May 2026 \| SEO Input Metrics |
| Optimized OG Titles | OPTIMIZED_OG_TITLES | August 2026 \| SEO Input Metrics; 🟢 April 2026 \| SEO Input Metrics; 🟢 August 2025 \| SEO Input Metrics; 🟢 December 2025 \| SEO Input Metrics; 🟢 February 2026 \| SEO Input Metrics; 🟢 January 2026 \| SEO Input Metrics; 🟢 July 2025 \| SEO Input Metrics; 🟢 July 2026 SEO Input Metrics; 🟢 June 2026 \| SEO Input Metrics; 🟢 March 2026 \| SEO Input Metrics; 🟢 May 2026 \| SEO Input Metrics; 🟢 November 2025 \| SEO Input Metrics; 🟢 October 2025 \| SEO Input Metrics; 🟢 September 2025 \| SEO Input Metrics |
| P6MA | P6MA | August 2026 \| SEO Input Metrics; SEO Input Metrics \| Feb 2025; [All Food View] SEO Input Metrics \| March 2025; [Food] June 2025 \| SEO Input Metrics; [Food] May 2025 \| SEO Input Metrics; [Food] SEO Input Metrics \| April 2025; [Non-Food] June 2025 \| SEO Input Metrics; [Non-Food] May 2025 \| SEO Input Metrics; [Non-Food] SEO Input Metrics \| April 2025; 🟢 April 2026 \| SEO Input Metrics; 🟢 August 2025 \| SEO Input Metrics; 🟢 December 2025 \| SEO Input Metrics; 🟢 February 2026 \| SEO Input Metrics; 🟢 January 2026 \| SEO Input Metrics; 🟢 July 2025 \| SEO Input Metrics; 🟢 July 2026 SEO Input Metrics; 🟢 June 2026 \| SEO Input Metrics; 🟢 March 2026 \| SEO Input Metrics; 🟢 May 2026 \| SEO Input Metrics; 🟢 November 2025 \| SEO Input Metrics; 🟢 October 2025 \| SEO Input Metrics; 🟢 September 2025 \| SEO Input Metrics |
| # Pages < 500 words | PAGES_LT_500_WORDS | August 2026 \| SEO Input Metrics; SEO Input Metrics \| Feb 2025; [All Food View] SEO Input Metrics \| March 2025; [Food] June 2025 \| SEO Input Metrics; [Food] May 2025 \| SEO Input Metrics; [Food] SEO Input Metrics \| April 2025; [Non-Food] June 2025 \| SEO Input Metrics; [Non-Food] May 2025 \| SEO Input Metrics; [Non-Food] SEO Input Metrics \| April 2025; 🟢 April 2026 \| SEO Input Metrics; 🟢 August 2025 \| SEO Input Metrics; 🟢 December 2025 \| SEO Input Metrics; 🟢 February 2026 \| SEO Input Metrics; 🟢 January 2026 \| SEO Input Metrics; 🟢 July 2025 \| SEO Input Metrics; 🟢 July 2026 SEO Input Metrics; 🟢 June 2026 \| SEO Input Metrics; 🟢 March 2026 \| SEO Input Metrics; 🟢 May 2026 \| SEO Input Metrics; 🟢 November 2025 \| SEO Input Metrics; 🟢 October 2025 \| SEO Input Metrics; 🟢 September 2025 \| SEO Input Metrics |
| Pageviews \| Email P3MA | PAGEVIEWS_EMAIL_P3MA | August 2026 \| SEO Input Metrics; SEO Input Metrics \| Feb 2025; [All Food View] SEO Input Metrics \| March 2025; [Food] June 2025 \| SEO Input Metrics; [Food] May 2025 \| SEO Input Metrics; [Food] SEO Input Metrics \| April 2025; [Non-Food] June 2025 \| SEO Input Metrics; [Non-Food] May 2025 \| SEO Input Metrics; [Non-Food] SEO Input Metrics \| April 2025; 🟢 April 2026 \| SEO Input Metrics; 🟢 August 2025 \| SEO Input Metrics; 🟢 December 2025 \| SEO Input Metrics; 🟢 February 2026 \| SEO Input Metrics; 🟢 January 2026 \| SEO Input Metrics; 🟢 July 2025 \| SEO Input Metrics; 🟢 July 2026 SEO Input Metrics; 🟢 June 2026 \| SEO Input Metrics; 🟢 March 2026 \| SEO Input Metrics; 🟢 May 2026 \| SEO Input Metrics; 🟢 November 2025 \| SEO Input Metrics; 🟢 October 2025 \| SEO Input Metrics; 🟢 September 2025 \| SEO Input Metrics |
| Pageviews \| Pinterest P3MA | PAGEVIEWS_PINTEREST_P3MA | August 2026 \| SEO Input Metrics; SEO Input Metrics \| Feb 2025; [All Food View] SEO Input Metrics \| March 2025; [Food] June 2025 \| SEO Input Metrics; [Food] May 2025 \| SEO Input Metrics; [Food] SEO Input Metrics \| April 2025; [Non-Food] June 2025 \| SEO Input Metrics; [Non-Food] May 2025 \| SEO Input Metrics; [Non-Food] SEO Input Metrics \| April 2025; 🟢 April 2026 \| SEO Input Metrics; 🟢 August 2025 \| SEO Input Metrics; 🟢 December 2025 \| SEO Input Metrics; 🟢 February 2026 \| SEO Input Metrics; 🟢 January 2026 \| SEO Input Metrics; 🟢 July 2025 \| SEO Input Metrics; 🟢 July 2026 SEO Input Metrics; 🟢 June 2026 \| SEO Input Metrics; 🟢 March 2026 \| SEO Input Metrics; 🟢 May 2026 \| SEO Input Metrics; 🟢 November 2025 \| SEO Input Metrics; 🟢 October 2025 \| SEO Input Metrics; 🟢 September 2025 \| SEO Input Metrics |
| % Branded Search Clicks | PCT_BRANDED_SEARCH_CLICKS | August 2026 \| SEO Input Metrics; 🟢 April 2026 \| SEO Input Metrics; 🟢 August 2025 \| SEO Input Metrics; 🟢 December 2025 \| SEO Input Metrics; 🟢 February 2026 \| SEO Input Metrics; 🟢 January 2026 \| SEO Input Metrics; 🟢 July 2025 \| SEO Input Metrics; 🟢 July 2026 SEO Input Metrics; 🟢 June 2026 \| SEO Input Metrics; 🟢 March 2026 \| SEO Input Metrics; 🟢 May 2026 \| SEO Input Metrics; 🟢 November 2025 \| SEO Input Metrics; 🟢 October 2025 \| SEO Input Metrics; 🟢 September 2025 \| SEO Input Metrics |
| % Branded Search Volume | PCT_BRANDED_SEARCH_VOLUME | August 2026 \| SEO Input Metrics; 🟢 April 2026 \| SEO Input Metrics; 🟢 August 2025 \| SEO Input Metrics; 🟢 December 2025 \| SEO Input Metrics; 🟢 February 2026 \| SEO Input Metrics; 🟢 January 2026 \| SEO Input Metrics; 🟢 July 2025 \| SEO Input Metrics; 🟢 July 2026 SEO Input Metrics; 🟢 June 2026 \| SEO Input Metrics; 🟢 March 2026 \| SEO Input Metrics; 🟢 May 2026 \| SEO Input Metrics; 🟢 November 2025 \| SEO Input Metrics; 🟢 October 2025 \| SEO Input Metrics; 🟢 September 2025 \| SEO Input Metrics |
| Branded Search Volume % (GSC Impressions) | PCT_BRANDED_SEARCH_VOLUME | SEO Input Metrics \| Feb 2025 |
| % Pages < 500 words (Ratio of total WP Posts) | PCT_PAGES_LT_500_WORDS | August 2026 \| SEO Input Metrics; [All Food View] SEO Input Metrics \| March 2025; [Food] June 2025 \| SEO Input Metrics; [Food] May 2025 \| SEO Input Metrics; [Food] SEO Input Metrics \| April 2025; [Non-Food] June 2025 \| SEO Input Metrics; [Non-Food] May 2025 \| SEO Input Metrics; [Non-Food] SEO Input Metrics \| April 2025; 🟢 April 2026 \| SEO Input Metrics; 🟢 August 2025 \| SEO Input Metrics; 🟢 December 2025 \| SEO Input Metrics; 🟢 February 2026 \| SEO Input Metrics; 🟢 January 2026 \| SEO Input Metrics; 🟢 July 2025 \| SEO Input Metrics; 🟢 July 2026 SEO Input Metrics; 🟢 June 2026 \| SEO Input Metrics; 🟢 March 2026 \| SEO Input Metrics; 🟢 May 2026 \| SEO Input Metrics; 🟢 November 2025 \| SEO Input Metrics; 🟢 October 2025 \| SEO Input Metrics; 🟢 September 2025 \| SEO Input Metrics |
| PTU Recs Given | PTU_RECS_GIVEN | August 2026 \| SEO Input Metrics; 🟢 April 2026 \| SEO Input Metrics; 🟢 February 2026 \| SEO Input Metrics; 🟢 July 2026 SEO Input Metrics; 🟢 June 2026 \| SEO Input Metrics; 🟢 March 2026 \| SEO Input Metrics; 🟢 May 2026 \| SEO Input Metrics |
| Publishing Volume P3MA | PUBLISHING_VOLUME_P3MA | August 2026 \| SEO Input Metrics; SEO Input Metrics \| Feb 2025; [All Food View] SEO Input Metrics \| March 2025; [Food] June 2025 \| SEO Input Metrics; [Food] May 2025 \| SEO Input Metrics; [Food] SEO Input Metrics \| April 2025; [Non-Food] June 2025 \| SEO Input Metrics; [Non-Food] May 2025 \| SEO Input Metrics; [Non-Food] SEO Input Metrics \| April 2025; 🟢 April 2026 \| SEO Input Metrics; 🟢 August 2025 \| SEO Input Metrics; 🟢 December 2025 \| SEO Input Metrics; 🟢 February 2026 \| SEO Input Metrics; 🟢 January 2026 \| SEO Input Metrics; 🟢 July 2025 \| SEO Input Metrics; 🟢 July 2026 SEO Input Metrics; 🟢 June 2026 \| SEO Input Metrics; 🟢 March 2026 \| SEO Input Metrics; 🟢 May 2026 \| SEO Input Metrics; 🟢 November 2025 \| SEO Input Metrics; 🟢 October 2025 \| SEO Input Metrics; 🟢 September 2025 \| SEO Input Metrics |
| PV Status | PV_STATUS | August 2026 \| SEO Input Metrics; 🟢 April 2026 \| SEO Input Metrics; 🟢 July 2026 SEO Input Metrics; 🟢 June 2026 \| SEO Input Metrics; 🟢 March 2026 \| SEO Input Metrics; 🟢 May 2026 \| SEO Input Metrics |
| # Republishes \| Last Complete Month | REPUBLISHES_LAST_COMPLETE_MONTH | August 2026 \| SEO Input Metrics; 🟢 April 2026 \| SEO Input Metrics; 🟢 December 2025 \| SEO Input Metrics; 🟢 February 2026 \| SEO Input Metrics; 🟢 January 2026 \| SEO Input Metrics; 🟢 July 2026 SEO Input Metrics; 🟢 June 2026 \| SEO Input Metrics; 🟢 March 2026 \| SEO Input Metrics; 🟢 May 2026 \| SEO Input Metrics; 🟢 November 2025 \| SEO Input Metrics |
| Service Level | SERVICE_LEVEL | August 2026 \| SEO Input Metrics; SEO Input Metrics \| Feb 2025; [All Food View] SEO Input Metrics \| March 2025; [Food] June 2025 \| SEO Input Metrics; [Food] May 2025 \| SEO Input Metrics; [Food] SEO Input Metrics \| April 2025; [Non-Food] June 2025 \| SEO Input Metrics; [Non-Food] May 2025 \| SEO Input Metrics; [Non-Food] SEO Input Metrics \| April 2025; 🟢 April 2026 \| SEO Input Metrics; 🟢 August 2025 \| SEO Input Metrics; 🟢 December 2025 \| SEO Input Metrics; 🟢 February 2026 \| SEO Input Metrics; 🟢 January 2026 \| SEO Input Metrics; 🟢 July 2025 \| SEO Input Metrics; 🟢 July 2026 SEO Input Metrics; 🟢 June 2026 \| SEO Input Metrics; 🟢 March 2026 \| SEO Input Metrics; 🟢 May 2026 \| SEO Input Metrics; 🟢 November 2025 \| SEO Input Metrics; 🟢 October 2025 \| SEO Input Metrics; 🟢 September 2025 \| SEO Input Metrics |
| Site | SITE | August 2026 \| SEO Input Metrics; SEO Input Metrics \| Feb 2025; [All Food View] SEO Input Metrics \| March 2025; [Food] June 2025 \| SEO Input Metrics; [Food] May 2025 \| SEO Input Metrics; [Food] SEO Input Metrics \| April 2025; [Non-Food] June 2025 \| SEO Input Metrics; [Non-Food] May 2025 \| SEO Input Metrics; [Non-Food] SEO Input Metrics \| April 2025; 🟢 April 2026 \| SEO Input Metrics; 🟢 August 2025 \| SEO Input Metrics; 🟢 December 2025 \| SEO Input Metrics; 🟢 February 2026 \| SEO Input Metrics; 🟢 January 2026 \| SEO Input Metrics; 🟢 July 2025 \| SEO Input Metrics; 🟢 July 2026 SEO Input Metrics; 🟢 June 2026 \| SEO Input Metrics; 🟢 March 2026 \| SEO Input Metrics; 🟢 May 2026 \| SEO Input Metrics; 🟢 November 2025 \| SEO Input Metrics; 🟢 October 2025 \| SEO Input Metrics; 🟢 September 2025 \| SEO Input Metrics |
| Site ID | SITE_ID | August 2026 \| SEO Input Metrics; SEO Input Metrics \| Feb 2025; [All Food View] SEO Input Metrics \| March 2025; [Food] June 2025 \| SEO Input Metrics; [Food] May 2025 \| SEO Input Metrics; [Food] SEO Input Metrics \| April 2025; [Non-Food] June 2025 \| SEO Input Metrics; [Non-Food] May 2025 \| SEO Input Metrics; [Non-Food] SEO Input Metrics \| April 2025; 🟢 April 2026 \| SEO Input Metrics; 🟢 August 2025 \| SEO Input Metrics; 🟢 December 2025 \| SEO Input Metrics; 🟢 February 2026 \| SEO Input Metrics; 🟢 January 2026 \| SEO Input Metrics; 🟢 July 2025 \| SEO Input Metrics; 🟢 July 2026 SEO Input Metrics; 🟢 June 2026 \| SEO Input Metrics; 🟢 March 2026 \| SEO Input Metrics; 🟢 May 2026 \| SEO Input Metrics; 🟢 November 2025 \| SEO Input Metrics; 🟢 October 2025 \| SEO Input Metrics; 🟢 September 2025 \| SEO Input Metrics |
| Top 20% Content \| Median Age in Months | TOP_20_CONTENT_MEDIAN_AGE_MONTHS | August 2026 \| SEO Input Metrics; SEO Input Metrics \| Feb 2025; [All Food View] SEO Input Metrics \| March 2025; [Food] June 2025 \| SEO Input Metrics; [Food] May 2025 \| SEO Input Metrics; [Food] SEO Input Metrics \| April 2025; [Non-Food] June 2025 \| SEO Input Metrics; [Non-Food] May 2025 \| SEO Input Metrics; [Non-Food] SEO Input Metrics \| April 2025; 🟢 April 2026 \| SEO Input Metrics; 🟢 August 2025 \| SEO Input Metrics; 🟢 December 2025 \| SEO Input Metrics; 🟢 February 2026 \| SEO Input Metrics; 🟢 January 2026 \| SEO Input Metrics; 🟢 July 2025 \| SEO Input Metrics; 🟢 July 2026 SEO Input Metrics; 🟢 June 2026 \| SEO Input Metrics; 🟢 March 2026 \| SEO Input Metrics; 🟢 May 2026 \| SEO Input Metrics; 🟢 November 2025 \| SEO Input Metrics; 🟢 October 2025 \| SEO Input Metrics; 🟢 September 2025 \| SEO Input Metrics |
| TOTAL_UNIQUE_GPIDS | TOTAL_UNIQUE_GPIDS | 🟢 July 2025 \| SEO Input Metrics |
| Total Unique GPIDs | TOTAL_UNIQUE_GPIDS | August 2026 \| SEO Input Metrics; 🟢 April 2026 \| SEO Input Metrics; 🟢 August 2025 \| SEO Input Metrics; 🟢 December 2025 \| SEO Input Metrics; 🟢 February 2026 \| SEO Input Metrics; 🟢 January 2026 \| SEO Input Metrics; 🟢 July 2026 SEO Input Metrics; 🟢 June 2026 \| SEO Input Metrics; 🟢 March 2026 \| SEO Input Metrics; 🟢 May 2026 \| SEO Input Metrics; 🟢 November 2025 \| SEO Input Metrics; 🟢 October 2025 \| SEO Input Metrics; 🟢 September 2025 \| SEO Input Metrics |
| # of Total Wordpress Posts | TOTAL_WORDPRESS_POSTS | August 2026 \| SEO Input Metrics; SEO Input Metrics \| Feb 2025; [All Food View] SEO Input Metrics \| March 2025; [Food] June 2025 \| SEO Input Metrics; [Food] May 2025 \| SEO Input Metrics; [Food] SEO Input Metrics \| April 2025; [Non-Food] June 2025 \| SEO Input Metrics; [Non-Food] May 2025 \| SEO Input Metrics; [Non-Food] SEO Input Metrics \| April 2025; 🟢 April 2026 \| SEO Input Metrics; 🟢 August 2025 \| SEO Input Metrics; 🟢 December 2025 \| SEO Input Metrics; 🟢 February 2026 \| SEO Input Metrics; 🟢 January 2026 \| SEO Input Metrics; 🟢 July 2025 \| SEO Input Metrics; 🟢 July 2026 SEO Input Metrics; 🟢 June 2026 \| SEO Input Metrics; 🟢 March 2026 \| SEO Input Metrics; 🟢 May 2026 \| SEO Input Metrics; 🟢 November 2025 \| SEO Input Metrics; 🟢 October 2025 \| SEO Input Metrics; 🟢 September 2025 \| SEO Input Metrics |
| Vertical | VERTICAL | August 2026 \| SEO Input Metrics; SEO Input Metrics \| Feb 2025; [All Food View] SEO Input Metrics \| March 2025; [Food] June 2025 \| SEO Input Metrics; [Food] May 2025 \| SEO Input Metrics; [Food] SEO Input Metrics \| April 2025; [Non-Food] June 2025 \| SEO Input Metrics; [Non-Food] May 2025 \| SEO Input Metrics; [Non-Food] SEO Input Metrics \| April 2025; 🟢 April 2026 \| SEO Input Metrics; 🟢 August 2025 \| SEO Input Metrics; 🟢 December 2025 \| SEO Input Metrics; 🟢 February 2026 \| SEO Input Metrics; 🟢 January 2026 \| SEO Input Metrics; 🟢 July 2025 \| SEO Input Metrics; 🟢 July 2026 SEO Input Metrics; 🟢 June 2026 \| SEO Input Metrics; 🟢 March 2026 \| SEO Input Metrics; 🟢 May 2026 \| SEO Input Metrics; 🟢 November 2025 \| SEO Input Metrics; 🟢 October 2025 \| SEO Input Metrics; 🟢 September 2025 \| SEO Input Metrics |
| Workbook Access? (Y/N) | WORKBOOK_ACCESS | August 2026 \| SEO Input Metrics; 🟢 April 2026 \| SEO Input Metrics; 🟢 December 2025 \| SEO Input Metrics; 🟢 February 2026 \| SEO Input Metrics; 🟢 January 2026 \| SEO Input Metrics; 🟢 July 2026 SEO Input Metrics; 🟢 June 2026 \| SEO Input Metrics; 🟢 March 2026 \| SEO Input Metrics; 🟢 May 2026 \| SEO Input Metrics; 🟢 November 2025 \| SEO Input Metrics |
| Workbook Visits | WORKBOOK_VISITS | August 2026 \| SEO Input Metrics; 🟢 April 2026 \| SEO Input Metrics; 🟢 December 2025 \| SEO Input Metrics; 🟢 February 2026 \| SEO Input Metrics; 🟢 January 2026 \| SEO Input Metrics; 🟢 July 2026 SEO Input Metrics; 🟢 June 2026 \| SEO Input Metrics; 🟢 March 2026 \| SEO Input Metrics; 🟢 May 2026 \| SEO Input Metrics; 🟢 November 2025 \| SEO Input Metrics |
| Yield / publish (0-3 months) | YIELD_PUBLISH_0_3_MONTHS | August 2026 \| SEO Input Metrics; 🟢 April 2026 \| SEO Input Metrics; 🟢 August 2025 \| SEO Input Metrics; 🟢 December 2025 \| SEO Input Metrics; 🟢 February 2026 \| SEO Input Metrics; 🟢 January 2026 \| SEO Input Metrics; 🟢 July 2025 \| SEO Input Metrics; 🟢 July 2026 SEO Input Metrics; 🟢 June 2026 \| SEO Input Metrics; 🟢 March 2026 \| SEO Input Metrics; 🟢 May 2026 \| SEO Input Metrics; 🟢 November 2025 \| SEO Input Metrics; 🟢 October 2025 \| SEO Input Metrics; 🟢 September 2025 \| SEO Input Metrics |
| Yield / publish (12+ months) | YIELD_PUBLISH_12_PLUS_MONTHS | August 2026 \| SEO Input Metrics; 🟢 April 2026 \| SEO Input Metrics; 🟢 August 2025 \| SEO Input Metrics; 🟢 December 2025 \| SEO Input Metrics; 🟢 February 2026 \| SEO Input Metrics; 🟢 January 2026 \| SEO Input Metrics; 🟢 July 2025 \| SEO Input Metrics; 🟢 July 2026 SEO Input Metrics; 🟢 June 2026 \| SEO Input Metrics; 🟢 March 2026 \| SEO Input Metrics; 🟢 May 2026 \| SEO Input Metrics; 🟢 November 2025 \| SEO Input Metrics; 🟢 October 2025 \| SEO Input Metrics; 🟢 September 2025 \| SEO Input Metrics |
| Yield / publish (3-6 months) | YIELD_PUBLISH_3_6_MONTHS | August 2026 \| SEO Input Metrics; 🟢 April 2026 \| SEO Input Metrics; 🟢 August 2025 \| SEO Input Metrics; 🟢 December 2025 \| SEO Input Metrics; 🟢 February 2026 \| SEO Input Metrics; 🟢 January 2026 \| SEO Input Metrics; 🟢 July 2025 \| SEO Input Metrics; 🟢 July 2026 SEO Input Metrics; 🟢 June 2026 \| SEO Input Metrics; 🟢 March 2026 \| SEO Input Metrics; 🟢 May 2026 \| SEO Input Metrics; 🟢 November 2025 \| SEO Input Metrics; 🟢 October 2025 \| SEO Input Metrics; 🟢 September 2025 \| SEO Input Metrics |
| Yield / publish (6-9 months) | YIELD_PUBLISH_6_9_MONTHS | August 2026 \| SEO Input Metrics; 🟢 April 2026 \| SEO Input Metrics; 🟢 August 2025 \| SEO Input Metrics; 🟢 December 2025 \| SEO Input Metrics; 🟢 February 2026 \| SEO Input Metrics; 🟢 January 2026 \| SEO Input Metrics; 🟢 July 2025 \| SEO Input Metrics; 🟢 July 2026 SEO Input Metrics; 🟢 June 2026 \| SEO Input Metrics; 🟢 March 2026 \| SEO Input Metrics; 🟢 May 2026 \| SEO Input Metrics; 🟢 November 2025 \| SEO Input Metrics; 🟢 October 2025 \| SEO Input Metrics; 🟢 September 2025 \| SEO Input Metrics |
| Yield / publish (9-12 months) | YIELD_PUBLISH_9_12_MONTHS | August 2026 \| SEO Input Metrics; 🟢 April 2026 \| SEO Input Metrics; 🟢 August 2025 \| SEO Input Metrics; 🟢 December 2025 \| SEO Input Metrics; 🟢 February 2026 \| SEO Input Metrics; 🟢 January 2026 \| SEO Input Metrics; 🟢 July 2025 \| SEO Input Metrics; 🟢 July 2026 SEO Input Metrics; 🟢 June 2026 \| SEO Input Metrics; 🟢 March 2026 \| SEO Input Metrics; 🟢 May 2026 \| SEO Input Metrics; 🟢 November 2025 \| SEO Input Metrics; 🟢 October 2025 \| SEO Input Metrics; 🟢 September 2025 \| SEO Input Metrics |
| Yield / update (0-3 months) | YIELD_UPDATE_0_3_MONTHS | August 2026 \| SEO Input Metrics; 🟢 April 2026 \| SEO Input Metrics; 🟢 August 2025 \| SEO Input Metrics; 🟢 December 2025 \| SEO Input Metrics; 🟢 February 2026 \| SEO Input Metrics; 🟢 January 2026 \| SEO Input Metrics; 🟢 July 2025 \| SEO Input Metrics; 🟢 July 2026 SEO Input Metrics; 🟢 June 2026 \| SEO Input Metrics; 🟢 March 2026 \| SEO Input Metrics; 🟢 May 2026 \| SEO Input Metrics; 🟢 November 2025 \| SEO Input Metrics; 🟢 October 2025 \| SEO Input Metrics; 🟢 September 2025 \| SEO Input Metrics |
| Yield / update (12+ months) | YIELD_UPDATE_12_PLUS_MONTHS | August 2026 \| SEO Input Metrics; 🟢 April 2026 \| SEO Input Metrics; 🟢 August 2025 \| SEO Input Metrics; 🟢 December 2025 \| SEO Input Metrics; 🟢 February 2026 \| SEO Input Metrics; 🟢 January 2026 \| SEO Input Metrics; 🟢 July 2025 \| SEO Input Metrics; 🟢 July 2026 SEO Input Metrics; 🟢 June 2026 \| SEO Input Metrics; 🟢 March 2026 \| SEO Input Metrics; 🟢 May 2026 \| SEO Input Metrics; 🟢 November 2025 \| SEO Input Metrics; 🟢 October 2025 \| SEO Input Metrics; 🟢 September 2025 \| SEO Input Metrics |
| Yield / update (3-6 months) | YIELD_UPDATE_3_6_MONTHS | August 2026 \| SEO Input Metrics; 🟢 April 2026 \| SEO Input Metrics; 🟢 August 2025 \| SEO Input Metrics; 🟢 December 2025 \| SEO Input Metrics; 🟢 February 2026 \| SEO Input Metrics; 🟢 January 2026 \| SEO Input Metrics; 🟢 July 2025 \| SEO Input Metrics; 🟢 July 2026 SEO Input Metrics; 🟢 June 2026 \| SEO Input Metrics; 🟢 March 2026 \| SEO Input Metrics; 🟢 May 2026 \| SEO Input Metrics; 🟢 November 2025 \| SEO Input Metrics; 🟢 October 2025 \| SEO Input Metrics; 🟢 September 2025 \| SEO Input Metrics |
| Yield / update (6-9 months) | YIELD_UPDATE_6_9_MONTHS | August 2026 \| SEO Input Metrics; 🟢 April 2026 \| SEO Input Metrics; 🟢 August 2025 \| SEO Input Metrics; 🟢 December 2025 \| SEO Input Metrics; 🟢 February 2026 \| SEO Input Metrics; 🟢 January 2026 \| SEO Input Metrics; 🟢 July 2025 \| SEO Input Metrics; 🟢 July 2026 SEO Input Metrics; 🟢 June 2026 \| SEO Input Metrics; 🟢 March 2026 \| SEO Input Metrics; 🟢 May 2026 \| SEO Input Metrics; 🟢 November 2025 \| SEO Input Metrics; 🟢 October 2025 \| SEO Input Metrics; 🟢 September 2025 \| SEO Input Metrics |
| Yield / update (9-12 months) | YIELD_UPDATE_9_12_MONTHS | August 2026 \| SEO Input Metrics; 🟢 April 2026 \| SEO Input Metrics; 🟢 August 2025 \| SEO Input Metrics; 🟢 December 2025 \| SEO Input Metrics; 🟢 February 2026 \| SEO Input Metrics; 🟢 January 2026 \| SEO Input Metrics; 🟢 July 2025 \| SEO Input Metrics; 🟢 July 2026 SEO Input Metrics; 🟢 June 2026 \| SEO Input Metrics; 🟢 March 2026 \| SEO Input Metrics; 🟢 May 2026 \| SEO Input Metrics; 🟢 November 2025 \| SEO Input Metrics; 🟢 October 2025 \| SEO Input Metrics; 🟢 September 2025 \| SEO Input Metrics |
| Yo2Y | YO2Y | August 2026 \| SEO Input Metrics; SEO Input Metrics \| Feb 2025; [All Food View] SEO Input Metrics \| March 2025; [Food] June 2025 \| SEO Input Metrics; [Food] May 2025 \| SEO Input Metrics; [Food] SEO Input Metrics \| April 2025; [Non-Food] June 2025 \| SEO Input Metrics; [Non-Food] May 2025 \| SEO Input Metrics; [Non-Food] SEO Input Metrics \| April 2025; 🟢 April 2026 \| SEO Input Metrics; 🟢 August 2025 \| SEO Input Metrics; 🟢 December 2025 \| SEO Input Metrics; 🟢 February 2026 \| SEO Input Metrics; 🟢 January 2026 \| SEO Input Metrics; 🟢 July 2025 \| SEO Input Metrics; 🟢 July 2026 SEO Input Metrics; 🟢 June 2026 \| SEO Input Metrics; 🟢 March 2026 \| SEO Input Metrics; 🟢 May 2026 \| SEO Input Metrics; 🟢 November 2025 \| SEO Input Metrics; 🟢 October 2025 \| SEO Input Metrics; 🟢 September 2025 \| SEO Input Metrics |
| YoY | YOY | August 2026 \| SEO Input Metrics; SEO Input Metrics \| Feb 2025; [All Food View] SEO Input Metrics \| March 2025; [Food] June 2025 \| SEO Input Metrics; [Food] May 2025 \| SEO Input Metrics; [Food] SEO Input Metrics \| April 2025; [Non-Food] June 2025 \| SEO Input Metrics; [Non-Food] May 2025 \| SEO Input Metrics; [Non-Food] SEO Input Metrics \| April 2025; 🟢 April 2026 \| SEO Input Metrics; 🟢 August 2025 \| SEO Input Metrics; 🟢 December 2025 \| SEO Input Metrics; 🟢 February 2026 \| SEO Input Metrics; 🟢 January 2026 \| SEO Input Metrics; 🟢 July 2025 \| SEO Input Metrics; 🟢 July 2026 SEO Input Metrics; 🟢 June 2026 \| SEO Input Metrics; 🟢 March 2026 \| SEO Input Metrics; 🟢 May 2026 \| SEO Input Metrics; 🟢 November 2025 \| SEO Input Metrics; 🟢 October 2025 \| SEO Input Metrics; 🟢 September 2025 \| SEO Input Metrics |
| YoY Bin | YOY_BIN | August 2026 \| SEO Input Metrics; 🟢 April 2026 \| SEO Input Metrics; 🟢 December 2025 \| SEO Input Metrics; 🟢 February 2026 \| SEO Input Metrics; 🟢 January 2026 \| SEO Input Metrics; 🟢 July 2026 SEO Input Metrics; 🟢 June 2026 \| SEO Input Metrics; 🟢 March 2026 \| SEO Input Metrics; 🟢 May 2026 \| SEO Input Metrics; 🟢 November 2025 \| SEO Input Metrics |

## Definition changes and known limitations

- February 2025 is a 70-site legacy scorecard subset, not the full network.
- March 2025 is Food-only because the full-network March workbook is explicitly marked do not use.
- April-June 2025 use complementary Food and Non-Food partitions; July 2025 onward uses consolidated network workbooks.
- The August 2026 Row 2 template has no roundup columns, so historical roundup columns are excluded.
- PTU Visits is not equivalent to PTU Recs Given and is excluded from the canonical column.
- Optimized OG Images used an exact-1200px rule through April 2026; those values are excluded. May 2026 onward uses the current at-least-1200px rule.
- Legacy 90-day yield fields are not equivalent to the current publish/update age buckets and are excluded.
- Early MoM values use inconsistent units and are not mapped to MoM% (Last 28 days).
- P6MA, YoY, Yo2Y, and several P3MA labels have historical formula/documentation conflicts. Values remain source-reported and the affected months should not be compared without reviewing definitions.
- Discover % P3MA has historical unit and calculation differences; values are preserved under the current header and explicitly flagged here.
- June 2026 contains carried-forward metric families. July 2026 has blocked roundup/word-count metrics and a Discover-share definition conflict.
- Historical workbooks may exclude Enterprise sites. The transformer itself applies no service-level filter.
- Zero and null remain distinct; unavailable, blocked, and formula-error values become null.

## Inventory and exclusions

| File | Classification | Reason |
|---|---|---|
| SEO Input Metrics \| Feb 2025 | Selected | Only accessible February scorecard; partial 70-site legacy subset. |
| [All Food View] SEO Input Metrics \| March 2025 | Selected | Usable March source; Food-only coverage. |
| [do not use] SEO Input Metrics \| March 2025 | Excluded — do not use | Title explicitly says do not use. |
| [Food] SEO Input Metrics \| April 2025 | Selected | Authoritative Food partition. |
| [Non-Food] SEO Input Metrics \| April 2025 | Selected | Authoritative Non-Food partition. |
| Ravi's Copy of SEO Input Metrics \| April 2025 | Excluded — duplicate | Named copy of the authoritative April Food workbook. |
| [Food] May 2025 \| SEO Input Metrics | Selected | Authoritative Food partition. |
| [Non-Food] May 2025 \| SEO Input Metrics | Selected | Authoritative Non-Food partition; severe metric-population limitation retained as a flag. |
| [Food] June 2025 \| SEO Input Metrics | Selected | Authoritative Food partition. |
| [Non-Food] June 2025 \| SEO Input Metrics | Selected | Authoritative Non-Food partition. |
| Copy of [Food] June 2025 \| SEO Input Metrics | Excluded — duplicate | Named copy of the authoritative June Food workbook. |
| 🟢 July 2025 \| SEO Input Metrics | Selected | Authoritative consolidated network workbook. |
| 🟢 August 2025 \| SEO Input Metrics | Selected | Authoritative file in the supplied folder. |
| Copy of 🟢 August 2025 \| SEO Input Metrics | Excluded — duplicate | Named copy; authoritative version is in the supplied folder. |
| 🟢 September 2025 \| SEO Input Metrics | Selected | Authoritative file in the supplied folder. |
| 🟢 October 2025 \| SEO Input Metrics | Selected | Authoritative file in the supplied folder. |
| 🟢 November 2025 \| SEO Input Metrics | Selected | Authoritative file in the supplied folder. |
| 🟢 December 2025 \| SEO Input Metrics | Selected | Authoritative file in the supplied folder. |
| 🟢 January 2026 \| SEO Input Metrics | Selected | Authoritative file in the supplied folder. |
| 🟢 February 2026 \| SEO Input Metrics | Selected | Authoritative file in the supplied folder. |
| 🟢 March 2026 \| SEO Input Metrics | Selected | Authoritative file in the supplied folder. |
| 🟢 April 2026 \| SEO Input Metrics | Selected | Authoritative file in the supplied folder. |
| 🟢 May 2026 \| SEO Input Metrics | Selected | Authoritative file in the supplied folder. |
| 🟢 June 2026 \| SEO Input Metrics | Selected | Authoritative file in the supplied folder; carried-forward metrics flagged. |
| 🟢 July 2026 SEO Input Metrics | Selected | Authoritative file in the supplied folder; blocked metric families flagged. |
| August 2026 \| SEO Input Metrics | Selected — canonical | Newest authoritative file; Site List Row 2 defines the canonical metric structure. |
| Draft Pipeline - SEO Input Metrics | Excluded — draft | Pipeline draft, not a finalized reporting-month snapshot. |
| Ads Analysis \| October 2025 \| SEO Input Metrics | Excluded — supporting | Analysis workbook, not the canonical monthly Site List. |
| Reference \| SEO Input Metrics | Excluded — supporting | Reference workbook, not a reporting-month snapshot. |
| Addisson Input Metrics | Excluded — personal/working copy | Personal working file, not an authoritative monthly snapshot. |
| Mediavine OG work | Excluded — supporting | OG-image research workbook, not a monthly input-metrics snapshot. |
| og_data_feb25 | Excluded — supporting | Raw OG research data. |
| [MODIFIED] Content Freshness - Logic Improvement | Excluded — supporting | Metric-development workbook, not a monthly snapshot. |
| Feb CQ Rubric URLs | Excluded — supporting | Content-quality rubric source data. |
| Feb Input Metrics - Updates | Excluded — supporting | Documentation, not a Site List dataset. |
| Top 200 Food - Latest URLs | Excluded — supporting | URL-level supporting data. |
| Mediavine OG.csv | Excluded — supporting | Raw OG source export. |
| og_data | Excluded — supporting | Raw OG research data. |
| Full OG.csv | Excluded — supporting | Raw OG source export. |
| titles_data.csv | Excluded — supporting | Raw title source export. |
| Austin's Copy of Network Traffic - Monthly Recap July 2025 | Excluded — presentation | Presentation copy, not an input-metrics Site List. |

## Blockers

- None.
