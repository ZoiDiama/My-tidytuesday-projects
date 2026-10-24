# TidyTuesday: three years of data, one chart at a time

[TidyTuesday](https://github.com/rfordatascience/tidytuesday) is a weekly data challenge. Every week, the R community shares a new dataset, and people around the world make something from it in R. Almost, every week since 2023, I've picked one question from it and tried to answer it with one clear chart.

This repo holds 60+ visualizations and the R code behind every one of them. Most were built in R with ggplot2 and finished in Figma. Below are the ones I'm proudest of. Every chart, week by week, is in the chart catalogue.


## Featured charts

| Week | Chart | What it shows | Data |
|---|---|---|---|
| 2025 · W5 | [**Men do 75% of the talking in Springfield**](featured/2025_w05.png) | Men are 79% of the cast and speak about 168,000 of the 224,000 words. | Simpsons dataset, Kaggle |
| 2024 · W17 | [**Space got crowded fast**](featured/2024_w17.png) | From 4 launches in 1957 to 1,000+ a year since 2019. | Our World in Data |
| 2025 · W3 | [**8 of 16 Himalayan summits saw zero climbers**](featured/2025_w03.png) | Expeditions to the 8,000 m peaks of Nepal, 2020–2024. | Himalayan Dataset |
| 2024 · W38 | [**Hamlet never stops talking**](featured/2024_w38.png) | Word counts for the main characters across three Shakespeare plays. | shakespeare.mit.edu |
| 2023 · W28 | [**The planet has warmed sharply since 1980**](featured/2023_w28.png) | Monthly temperatures from 1880 to 2023 against the 1951–1980 average. | NASA GISTEMP v4 |
| 2024 · W19 | [**Fewer than 1 in 5 of rock's 'greatest albums' are by women**](featured/2024_w19.png) | Across three Rolling Stone lists, only 170 of 1,500 entries were by women. Share of albums by women: 6% (2003), 12% (2012), 17% (2020). | Rolling Stone / Data is Plural |
| 2025 · W4 | [**Over 265,000 Americans live without plumbing**](featured/2025_w04.png)| It's only 0.08% of the population, which sounds like nothing. But it's hundreds of thousands of people. | tidycensus |


## How I approach each chart

Start with one question. Not "what's in this data?" but "what would someone want to know?"
Clean and check. Every dataset has quirks: missing values, odd categories, duplicates.
Break it down. The story is usually in the split (by gender, country, year), not the total.
Pick the simplest chart that answers it.
Write the headline last. It should state the finding, not the topic.

## How each project is organized

```
- One R script per week. Each script runs start to finish, from loading the data to making the chart.
- The finished charts appear in the gallery above and are saved as PNG files in [your images folder name].
- Final edits are made in Figma, as explained in the note at the top.
```

## Tools
R · tidyverse · ggplot2 · Figma

## Credits

Data comes from the sources named in each row and in each chart's footer. Thanks to the TidyTuesday community for the weekly push.

Made by [Zoi Diamantakou](https://github.com/ZoiDiama) 



















