# 📊 Comparative Analysis of Mobile Applications Across Playstore and App store

## Overview
This project presents a comprehensive comparative analysis of mobile applications listed on the Apple App Store and Google Play Store. The analysis aims to uncover platform-specific differences in app characteristics such as size, price, ratings, release timelines, and content categorization.

## Team
- Ketaki Paranjape
- Rajasi Barapatre 
- Sanika Chavan

## Objective
To analyze and visualize cross-platform trends in mobile app metadata and evaluate:
- App release patterns across platforms
- Differences in size and price
- Similarities in content rating and genres
- User rating discrepancies
- Platform-specific app availability timelines

## Key Methodologies
- **Data Integration**: Merging cleaned Apple and Google app datasets on app name using pandas.
- **Fuzzy Matching**: `fuzzywuzzy` library used to assess genre and content rating similarity.
- **Data Normalization**: Handling format inconsistencies, typecasting, and outlier detection.
- **Visualization**: Seaborn and Matplotlib used for insightful and comparative visual reporting.

## Comparative Dimensions

### 1. 🎨 Content Categorization
- **Genre vs Category**:  Verified alignment of Apple’s `Primary_Genre` with Google’s `Category`.
- **Content Rating Comparison**: Assessed user-appropriate content tagging consistency.

### 2. 📅 Release and Update Analysis
- Identified which platform had the earlier release or update date.
- Found that a large proportion of apps launched simultaneously, with slight lead variations by platform.

### 3. 📦 App Size and 💵 Price Trends
- Apple's app packages generally exhibited larger sizes.
- The majority of apps are free across both stores; where prices differ, discrepancies were minimal.

### 4. 🌟 Ratings and Reviews
- Average ratings were platform-dependent, with notable variations observed in popular apps.
- Comparative user sentiment was mapped using side-by-side bar plots.

### 5. 📱 OS Compatibility
- Evaluated minimum Android vs. required iOS versions.
- Android apps exhibited broader backward compatibility.

### 6. 🔍 Case Study: Popular Apps
Detailed comparisons were made for:
- Instagram
- Facebook
- WhatsApp
- Snapchat
- Telegram
- TikTok

Metrics considered included platform-based size, price, and rating differences.

## Tools and Libraries
- Python (Pandas, NumPy, Seaborn, Matplotlib)
- FuzzyWuzzy (String matching)
- Jupyter Notebook / Google Colab

## Results Summary
- **Consistency** in app availability and updates across platforms.
- **Size differential** favoring smaller Google Play APKs.
- **Rating bias** observed, sometimes favoring Google, sometimes Apple.
- **Content structure** remains largely aligned across ecosystems.

## Conclusion
The comparative insights derived from this analysis highlight key differences and overlaps between Apple and Google app marketplaces. These findings are especially relevant for:
- **App developers** planning cross-platform deployments.
- **Marketers** assessing pricing or popularity trends.
- **Consumers** curious about store-specific app behaviors.

The project underscores the importance of platform-aware development and data-driven optimization strategies.

