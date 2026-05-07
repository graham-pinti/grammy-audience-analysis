# grammy-audience-analysis
The Recording Academy, the non-profit organization behind the Grammy Awards, split its combined Grammys + Recording Academy website into two distinct sites: Grammy.com and RecordingAcademy.com, effective February 1, 2022. This project analyzes web analytics data across both sites to evaluate whether the split improved key performance indicators and whether the results are statistically significant.

The key analytical questions I set out to answer were:
1. How has Grammy.com traffic trended over time, and when do peaks occur?
2. What is the impact of Grammy Award ceremonies on site traffic?
3. How do key KPIs compare across the three website eras?
4. What percentage of visitors use mobile devices?
5. Is the difference in pages-per-session statistically significant? (A/B Test)
6. Should the websites remain separate?

To answer these I worked with raw daily web analytics for Grammy.com from 2017-2023, as well as raw daily web analytics for RecordingAcademy.com from 2022-2023.

Key Findings & Recommendations:
Recommendation: Keep the websites separate.
KPI data shows clear improvement across all core engagement metrics following the February 2022 split:
MetricCombined EraGrammy.comRecordingAcademy.comPages per Session1.862.252.78Bounce Rate41.6%40.2%33.7%Avg. Session Duration102.9 sec83.0 sec128.5 sec

The improvement in pages-per-session between the combined era and post-split sites is statistically significant at the 95% confidence level (two-sample t-test, p ≈ 0), confirming the separation meaningfully improved audience engagement rather than reflecting random variation.

Competitor context: Grammy.com holds a substantial traffic advantage over TheAMAs.com, particularly around ceremony dates. TheAMAs.com's higher mobile visitor share suggests an opportunity for Grammy.com to invest in mobile experience optimization to capture a younger audience segment year-round.

Bottom line: The split allows each property to serve a distinct audience — Grammy.com for pop-culture fans during awards season, RecordingAcademy.com for music industry professionals year-round — and the data supports that this focus is driving stronger engagement on both sites.

Tools Used — Excel, statistical analysis (two-sample t-test)
Data Sources — Raw daily web analytics, Grammy.com (2017–2023) and RecordingAcademy.com (2022–2023)
