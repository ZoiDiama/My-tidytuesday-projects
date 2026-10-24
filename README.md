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

## Gallery of examples: 
### 2025
<p align="left">
  <img src="https://github.com/user-attachments/assets/e075746a-eea9-4555-ab87-30a395c4d59b" alt="Image" width="200"/>
  <img src="https://github.com/user-attachments/assets/0fe0a989-4b98-430e-ab4d-ae1e3781314a" alt="Week 3" width="200"/>
    <img src="https://github.com/user-attachments/assets/635e4579-33ea-4921-b686-f7043c2c9116" alt="Week 4" width="200"/>

</p>

### 2024
<p align="left">
  <img src="https://github.com/ZoiDiama/My-tidytuesday-projects/assets/139105670/f46600d3-404e-4311-ba10-0a70cb816225" alt="2024Week3" width="200"/>
  <img src="https://github.com/ZoiDiama/My-tidytuesday-projects/assets/139105670/db7b8751-7329-471d-823b-d87af7aec162" alt="2024Week4" width="200"/>
  <img src="https://github.com/ZoiDiama/My-tidytuesday-projects/assets/139105670/15b0710c-a43a-40ed-b665-35adb7ea463e" alt="2024Week6" width="200"/>
  <img src="https://github.com/user-attachments/assets/05300f56-6308-49b6-9649-0d8c974da782" alt="20024Week11" width="200"/>
  </p>
   <p align="left">  
  <img src="https://github.com/user-attachments/assets/8543f4a4-823c-47ed-b95d-3e04b5a780e3" alt="2024Week11" width="200"/>
  <img src="https://github.com/user-attachments/assets/5ac02908-283b-4e14-8266-4ccd869ac63b" alt="2024Week22" width="200"/>
  <img src="https://github.com/user-attachments/assets/fdb8bdc3-ee96-4ef9-9bb2-6135922b9128" alt="2024Week26" width="200"/>
  <img src="https://github.com/user-attachments/assets/b0f9b662-8195-4f6c-b535-1fef2334b335" alt="20024Week43" width="200"/>  
 
</p>
  <p align="left">  
  <img src="https://github.com/user-attachments/assets/7472f043-b27e-4df1-acae-ea52e11bfc00" alt="2024Week17" width="200"/>
  <img src="https://github.com/user-attachments/assets/6a5d83fd-137d-4f85-908b-5cc4b8d82c5e" alt="2024Week19" width="200"/>
  <img src="https://github.com/ZoiDiama/My-tidytuesday-projects/assets/139105670/5c1047d9-02ab-42a3-9332-4f9d6f8f9896" alt="2024Week21" width="200"/>
  <img src="https://github.com/user-attachments/assets/92375c72-fcf2-4aa2-8e82-327f2b19c416" alt="20024Week35" width="200"/>  
 
</p>
<p align="left">  
  <img src="https://github.com/user-attachments/assets/5ad00671-272a-4b13-b61c-953099c9959a" alt="2024Week28" width="200"/>
   <img src="https://github.com/user-attachments/assets/e8724fb9-5517-4307-9b78-6d3919c8abb2" alt="20024Week38" width="200"/>  
  <img src="https://github.com/user-attachments/assets/1f42bd6a-827d-4086-a975-c8a4fef92df5" alt="2024Week30" width="200"/>
  <img src="https://github.com/user-attachments/assets/0b84742f-6985-453e-af28-11342ba73764" alt="2024Week31" width="200"/>
  
</p>


 
### 2023
<p align="left">  
  <img src="https://github.com/ZoiDiama/My-tidytuesday-projects/assets/139105670/5e04df52-dd01-4b6d-a68b-6f9d10ae5e06" alt="2023Week_34" width="200"/>
  <img src="https://github.com/ZoiDiama/My-tidytuesday-projects/assets/139105670/9e5e3cfb-6ea0-41bf-b34b-f70c598c2998" alt="2023Week37" width="200"/>
  <img src="https://github.com/ZoiDiama/My-tidytuesday-projects/assets/139105670/178bc72c-446d-4e89-8fa7-43c72702687d" alt="2023Week45" width="200"/>
  <img src="https://github.com/ZoiDiama/My-tidytuesday-projects/assets/139105670/dfd68c4a-b76c-4cef-86de-9a56716df71c" alt="2023Week47" width="200"/>
 </p>
 <p align="left">  
  <img src="https://github.com/ZoiDiama/My-tidytuesday-projects/assets/139105670/c99ebfef-6131-445d-b7bf-26995e016479" alt="2023Week_47" width="200"/>
  <img src="https://github.com/ZoiDiama/My-tidytuesday-projects/assets/139105670/91bbf2f5-a325-4bad-b9a0-df98a108f8f4" alt="2023Week48" width="200"/>
  <img src="https://github.com/ZoiDiama/My-tidytuesday-projects/assets/139105670/6b6f7ec6-f51a-4d11-93c4-6935b3a0dfb7" alt="2023Week50" width="200"/>
  <img src="https://github.com/ZoiDiama/My-tidytuesday-projects/assets/139105670/c6373430-32e8-4e76-bf50-64a394adf0db)" alt="2023Week52" width="200"/>
 </p>



















