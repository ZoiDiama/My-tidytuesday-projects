# TidyTuesday: three years of data, one chart at a time

[TidyTuesday](https://github.com/rfordatascience/tidytuesday) is a weekly data challenge. Every week, the R community shares a new dataset, and people around the world use it to create data visuals, most times in R. I also took part from 2023 until 2025: almost every week since 2023, I've picked one question from it and tried to answer it with one clear chart. 

This repo holds 67 visualizations and their R code. All built in R with ggplot2. Below are the ones I'm proudest of. Every chart, week by week, is in the [chart catalogue](Chart_Catalogue.md).

**2026 revision:** After having some break, I went back over every chart. Each one now has a headline that states its finding, a consistent layout, and numbers re-checked against the data. That review caught some errors, like duplicated records and mislabeled categories, which are now fixed. Earlier versions were finished by hand in Figma; the revised charts are made fully in code.

## Featured charts

| Week | Chart | What it shows | Data |
|---|---|---|---|
| [2025 · W5](https://github.com/rfordatascience/tidytuesday/tree/main/data/2025/2025-02-04) | [**Men do 75% of the talking in Springfield**](featured/2025_w05.png) | Men are 79% of the cast and speak about 168,000 of the 224,000 words. | Simpsons dataset, Kaggle |
| [2025 · W4](https://github.com/rfordatascience/tidytuesday/tree/main/data/2025/2025-01-28) | [**Over 250,000 Americans live without plumbing**](featured/2025_w04.png) | It's only 0.08% of the population, which sounds like nothing. But it's hundreds of thousands of people. | tidycensus |
| [2025 · W3](https://github.com/rfordatascience/tidytuesday/tree/main/data/2025/2025-01-21) | [**8 of 16 Himalayan summits saw zero climbers**](featured/2025_w03.png) | Expeditions to the 8,000 m peaks of Nepal, 2020–2024. | Himalayan Dataset |
| [2024 · W38](https://github.com/rfordatascience/tidytuesday/tree/main/data/2024/2024-09-17) | [**Hamlet never stops talking**](featured/2024_w38.png) | Word counts for the main characters across three Shakespeare plays. | shakespeare.mit.edu |
| [2024 · W19](https://github.com/rfordatascience/tidytuesday/tree/main/data/2024/2024-05-07) | [**Fewer than 1 in 5 of rock's 'greatest albums' are by women**](featured/2024_w19.png) | Across three Rolling Stone lists, only 170 of 1,500 entries were by women. Share of albums by women: 6% (2003), 12% (2012), 17% (2020). | Rolling Stone / Data is Plural |
| [2024 · W17](https://github.com/rfordatascience/tidytuesday/tree/main/data/2024/2024-04-23) | [**Space got crowded fast**](featured/2024_w17.png) | From 4 launches in 1957 to 1,000+ a year since 2019. | Our World in Data |
| [2023 · W28](https://github.com/rfordatascience/tidytuesday/tree/main/data/2023/2023-07-11) | [**The planet has warmed sharply since 1980**](featured/2023_w28.png) | Monthly temperatures from 1880 to 2023 against the 1951–1980 average. | NASA GISTEMP v4 |

📄 **Prefer a quick read?** Download the [portfolio (PDF)](featured/tidytuesday-portfolio.pdf).

## How I approach each chart

1. **Question comes first.** It is not about "what's in this data?" but "what would someone want to know?"
2. **Data cleaning and checking.** Every dataset has quirks: missing values, odd categories, duplicates.
3. **Break it down.** The story is usually in the split (by gender, country, year), not the total.
4. **Pick the simplest chart that answers it (unless you want to be creative).**
5. **Write the headline last.** It should state the finding, not the topic.

## What's in this repo

| Folder | What's inside |
|---|---|
| [`featured/`](featured/) | The featured charts and the PDF portfolio |
| [`charts/`](charts/) | Every revised chart, named by year and week (e.g. `2024_w26.png`) |
| [`Code/2023/`](Code/2023/) | R scripts for 2023 (23 charts, my first year learning ggplot2) |
| [`Code 2024/`](Code%202024/) | R scripts for 2024 (39 charts, with more focus on typography and design) |
| [`Code 2025/`](Code%202025/) | R scripts for 2025 (5 charts) |
| [`Chart_Catalogue.md`](Chart_Catalogue.md) | Every chart by topic, with its finding, chart type, dataset and code |

## Tools

R · tidyverse · ggplot2 · ggtext · patchwork · waffle · ggalluvial · Figma

## Credits

Data comes from the sources named in each row and in each chart's footer. Thanks to the TidyTuesday community for the weekly push.

Made by [Zoi Diamantakou](https://github.com/ZoiDiama)
