# Tidytuesday-projects with R 

Visuals with R and Figma!

TidyTuesday is a weekly data challenge that invites data enthusiasts to explore and visualize a new dataset using the R programming language and the tidyverse suite of packages. Each week, a new dataset is shared, often highlighting interesting topics and stories, allowing participants to create their own visualizations and analyses. This initiative not only fosters a community of learners but also encourages creativity in data analysis and visualization. More info about TidyTuesday you can find [here](https://github.com/rfordatascience/tidytuesday).

I began creating visuals for TidyTuesday in 2023. This repository showcases the visualizations I prepared using R, often with the final design polished in Figma. The repository includes both the visualizations and its code. The graphics are grouped per year. 

<details close>
  <summary>2023</summary>

This year was the first time I started preparing graphs for TidyTuesday. Over the year, I created a total of 23 visuals. My main goal was to familiarize myself with ggplot2 and explore different types of plots.

### Week 28 | Global Surface Temperatures
This week's data is sourced from NASA GISS Surface Temperature Analysis (GISTEMP v4). It consists of global and hemispheric monthly means and zonal annual means, combining land, air, and sea-surface temperature anomalies (Land-Ocean Temperature Index, L-OTI). To visualize this data, I chose a heatmap, providing an intuitive and visually appealing representation of temperature patterns. 

Check the code [here](https://github.com/ZoiDiama/My-tidytuesday-projects/blob/4af0c90acb7b5255ed37e3b07756bb30bed0bf0a/Code/2023/Week28Global%20Surface%20Temperatures#L1C1-L80C4).

![TT2023Week28](https://github.com/ZoiDiama/My-tidytuesday-projects/assets/139105670/67775e46-398d-4823-872c-82e1d86e5fc3)


### Week29 | GPT detectors
This week's dataset is sourced from the R data package "detectors," which contains predictions from various GPT detectors. These predictions are based on a research paper titled "GPT Detectors Are Biased Against Non-Native English Writers" by Weixin Liang, Mert Yuksekgonul, Yining Mao, Eric Wu, and James Zou, published in CellPress Patterns. The study revealed that these detectors exhibit a bias against non-native English writers, as they tend to misclassify authentic writing from non-native English speakers as AI-generated. To effectively showcase the distributional characteristics of the predictions from GPT detectors and identify biases or patterns within the data, a violin plot was employed. This plot allowed for the comparison of predictions between detectors, shedding light on potential biases or patterns present in the data.

Check the code [here](https://github.com/ZoiDiama/My-tidytuesday-projects/blob/6af2a7e0af3014c1680eeb3b41d50830f453f767/Code/2023/Week29_GPT_detectors#L1-L33).
  
![TT_2023Week29](https://github.com/ZoiDiama/My-tidytuesday-projects/assets/139105670/8df46a9f-a944-4110-af1e-10c019264a07)


### Week 30 | Scurvy
This week's dataset comes from the medicaldata R package and the Scurvy dataset. The data are based on  James Lind published in 1757  "A Treatise on the Scurvy in Three Parts". Within this study, 12 participants with comparable scurvy severity underwent six distinct therapies. Subsequently, after a six-day period, they were invited to assess the severity of their condition using a 0-3 Likert scale. The graph below showcases the outcomes following the six days of treatment, providing a participant-specific breakdown across each treatment category. 

Check the code [here](https://github.com/ZoiDiama/My-tidytuesday-projects/blob/7daa9b29c8756a2f1d5c6863d426c17231363a8c/Code/2023/Week30_Scurvy#L1C1-L1C1)

![TT2023Week30_Scurvy](https://github.com/ZoiDiama/My-tidytuesday-projects/assets/139105670/13bf6ade-c546-4e59-8028-39acaf8ee92e)


### Week 31 | US States

The data this week comes from three Wikipedia articles: List of states and territories of the United States, List of demonyms for US states and territories, and List of state and territory name etymologies of the United States.

Check the code [here](https://github.com/ZoiDiama/My-tidytuesday-projects/blob/6be7b5fb61a83f814f43331f1c10a063c7d8fd83/Code/2023/Week31#L1-L169)

![TT2023Week31_Scurvy](https://github.com/ZoiDiama/My-tidytuesday-projects/assets/139105670/12d1b3c3-6407-4a11-82a9-73bd49fa21a2)

   
### Week 32 | Hot Ones Episodes
The data this week comes from Wikipedia articles: Hot Ones and List of Hot Ones episodes.

Check the code [here](https://github.com/ZoiDiama/My-tidytuesday-projects/blob/13dc335ddcf54d3f0f1b86576b0bf70f537cebcf/Code/2023/Week32#L1-L77).

![TT2023Week32_Hot](https://github.com/ZoiDiama/My-tidytuesday-projects/assets/139105670/60f46bcf-deb9-41c6-8e33-a7be0c5158b2)

### Week 33 | Spam emails

The data this week comes from Vincent Arel-Bundock's Rdatasets package.

Check the code [here](https://github.com/ZoiDiama/My-tidytuesday-projects/blob/4c8a235621e20b1d3b544c53abe8c451af2217ce/Code/2023/Week%2033#L1-L53)

![TT2023Week33](https://github.com/ZoiDiama/My-tidytuesday-projects/assets/139105670/d38aef5f-de3a-4203-a029-51cc7f140e10)


### Week 34 | Refugees

The data this week comes from PopulationStatistics {refugees} R package. I created a barchart showcasing refugee data trends since 2010, with annotations highlighting the most significant crises during this period.

Check the code [here](https://github.com/ZoiDiama/My-tidytuesday-projects/blob/c0dee5214455870cac4ce6eaad1dafe756ffb145/Code/2023/Week%2034#L1-L114)

![TT2023Week34](https://github.com/ZoiDiama/My-tidytuesday-projects/assets/139105670/5e04df52-dd01-4b6d-a68b-6f9d10ae5e06)

### Week 35 | Fair use

This week's data is sourced from the U.S. Copyright Office Fair Use Index. To illustrate the changing frequency of  use cases over time, across different jurisdictions and their corresponding outcome, I utilized a bubble timeline graph.

Check the code [here](https://github.com/ZoiDiama/My-tidytuesday-projects/blob/ffc7325327f91322c7b4dbc7fbee6c095bb7325f/Code/2023/Week%2035#L1-L78)

![TT2023Week35](https://github.com/ZoiDiama/My-tidytuesday-projects/assets/139105670/2d02c7a1-89a6-4715-a57c-af0fd15f92d2)


### Week 36 | Union Membership in the United States

The data this week comes from the Union Membership, Coverage, and Earnings from the CPS by Barry Hirsch (Georgia State University), David Macpherson (Trinity University), and William Even (Miami University).

Check the code [here](https://github.com/ZoiDiama/My-tidytuesday-projects/blob/e3e0516b72bc8f910db52a65ab83c4960ae77296/Code/2023/Week36#L1-L56)


![TT2023Week36](https://github.com/ZoiDiama/My-tidytuesday-projects/assets/139105670/732b6a58-c086-4567-b666-0ab044448bc5)


### Week 37 | The Global Human Day

The data this week comes from the The Human Chronome Project an initiative based at McGill University in Montreal, from their paper The global human day in PNAS and the associated dataset on Zenodo.

Check the code [here](https://github.com/ZoiDiama/My-tidytuesday-projects/blob/1a44f946eedf2792eb651dc56ea671d34e92d1cb/Code/2023/Week%2037#L1-L54)


![TT2023Week37](https://github.com/ZoiDiama/My-tidytuesday-projects/assets/139105670/9e5e3cfb-6ea0-41bf-b34b-f70c598c2998)

### Week 39 | Roy Kent F**k count

The data this week comes from Deepsha Menghani who created the dataset by watching the show and counting the number of F-cks used in sentences and as gestures.

Check the code [here](https://github.com/ZoiDiama/My-tidytuesday-projects/blob/4fe4900d1905b7c44c82a0a5f130e76c474cef55/Code/2023/Week%2039#L1-L121)

![TT2023Week39](https://github.com/ZoiDiama/My-tidytuesday-projects/assets/139105670/f1dc9f0f-7722-45b4-ad09-ddd4c147171a)

### Week 40 | US Government Grant Opportunities

The data this week comes from the R4DS Online Learning Community who exported all grants past and present listed on Grants.gov.

Check the code [here](https://github.com/ZoiDiama/My-tidytuesday-projects/blob/af8e13c0940b29831ed075fb7399c757a2330d05/Code/2023/Week%2040#L1-L225)

![TT2023Week40](https://github.com/ZoiDiama/My-tidytuesday-projects/assets/139105670/29152280-9b60-45c9-a3c0-6bc00c14d96c)

### Week 41 | Haunted Places in the United States

The data this week comes from a compilation of Haunted Places in the United States. The dataset was compiled by Tim Renner, using The Shadowlands Haunted Places Index, and shared on data.world.

Check the code [here](https://github.com/ZoiDiama/My-tidytuesday-projects/blob/709119e62b0e3bc35237645ae7b1a69fc809203f/Code/2023/Week%2041#L1-L104)

![TT2023Week41](https://github.com/ZoiDiama/My-tidytuesday-projects/assets/139105670/51d512bf-aaa1-47e2-b2a1-a3c2102f1e83)


### Week 42 | Taylor Swift data

The data this week comes from taylor R package from W. Jake Thompson which is a curated data set of Taylor Swift songs, including lyrics and audio characteristics. The data comes from Genius and the Spotify API.

Check the code [here](https://github.com/ZoiDiama/My-tidytuesday-projects/blob/af8e13c0940b29831ed075fb7399c757a2330d05/Code/2023/Week%2040#L1-L225)

![TT2023Week42](https://github.com/ZoiDiama/My-tidytuesday-projects/assets/139105670/f6d60abd-3528-4695-b57e-ae55b8bce229)


### Week 44 | Horror Legends
The data this week comes from snopes.com. 

Check the code [here](https://github.com/ZoiDiama/My-tidytuesday-projects/blob/2bf0d72551409886a1896a4630b7e03d93e2baeb/Code/2023/Week_44#L1-L112)

![TT2023Week44](https://github.com/ZoiDiama/My-tidytuesday-projects/assets/139105670/8feafe29-ccb0-4a53-ae07-66274c121e56)

### Week 45 | US House Election Results
The data this week comes from the MIT Election Data and Science Lab (MEDSL). 

Check the code[here](https://github.com/ZoiDiama/My-tidytuesday-projects/blob/710960a0d90b446587f63b8278db370592f36ac9/Code/2023/Week_45#L1-L109)

![TT2023Week45](https://github.com/ZoiDiama/My-tidytuesday-projects/assets/139105670/178bc72c-446d-4e89-8fa7-43c72702687d)

### Week 46 | Diwali Sales Data

The data this week comes from sales data for a retail store during the Diwali festival period in India.The graph was prepared with ggplot while the final editing was completed in Figma. 

Check the code [here](https://github.com/ZoiDiama/My-tidytuesday-projects/blob/19fcb485eabf89799b0f6dcf633dc368ec0dfc24/Code/2023/Week_46#L1-L110)

![TT2023Week46](https://github.com/ZoiDiama/My-tidytuesday-projects/assets/139105670/dfd68c4a-b76c-4cef-86de-9a56716df71c)

### Week 47 | R-Ladies Chapter Events

The data this week comes from  R-Ladies Global Website .The graph was prepared with ggplot while the final editing was completed in Figma. 

Check the code [here](https://github.com/ZoiDiama/My-tidytuesday-projects/blob/40cc4b705016af1cc0df352ec898fa3ef69f8f06/Code/2023/Week_47#L1-L99)

![TT_week_47_2023](https://github.com/ZoiDiama/My-tidytuesday-projects/assets/139105670/c99ebfef-6131-445d-b7bf-26995e016479)

### Week 48 | Doctor Who Episodes

The data this week comes from  Wikipedia's [List of Doctor Who episodes] via the {datardis} package.The graph was prepared with ggplot while the final editing was completed in Figma. 

Check the code [here](https://github.com/ZoiDiama/My-tidytuesday-projects/blob/ed0ed78637ff67ee5d48e5e85db7b775f7d33863/Code/2023/Week%2048#L1-L88)

![DR WHO](https://github.com/ZoiDiama/My-tidytuesday-projects/assets/139105670/91bbf2f5-a325-4bad-b9a0-df98a108f8f4)

### Week 49 | Life Expectancy

The data this week comes from  the Our World in Data Life Expectancy report.The graph was prepared with ggplot while the final editing was completed in Figma. 

Check the code [here](https://github.com/ZoiDiama/My-tidytuesday-projects/blob/bc38a04d5ce5cd5eda059e300d0c3e6268640ff1/Code/2023/Week%2049#L1-L206)

![TT2023Week49 (1)](https://github.com/ZoiDiama/My-tidytuesday-projects/assets/139105670/b39a69d7-9956-4b1d-b73a-79975f7742c0)

### Week 50 | Holiday movies

The data this week comes from the Internet Movie Database.The graph was prepared with ggplot. 

Check the code [here](https://github.com/ZoiDiama/My-tidytuesday-projects/blob/6da4d041fa6465cb4babbfcef87baacf722c6526/Code/2023/Week%2050#L1-L70)

![TT2023Week50](https://github.com/ZoiDiama/My-tidytuesday-projects/assets/139105670/6b6f7ec6-f51a-4d11-93c4-6935b3a0dfb7)

### Week 51 | Holiday Episodes

The data this week comes from the Internet Movie Database.The graph was prepared with ggplot while the final editing was completed in Figma. Inspired by [https://www.behance.net/gallery/13486555/Infographic-Data-Visualisation-Collection. ](https://www.behance.net/gallery/13486555/Infographic-Data-Visualisation-Collection).

Check the code [here](https://github.com/ZoiDiama/My-tidytuesday-projects/blob/f9b056a141896d82d1989c40e32df7c31e016440/Code/2023/Week%2051#L1-L113)

![TT2023Week51 2](https://github.com/ZoiDiama/My-tidytuesday-projects/assets/139105670/d5753874-dfef-417a-8121-721547df9c17)

### Week 52 | R structure package

The data this week comes from {pkgstats} R package .The graph was prepared with ggplot. 

Check the code [here](https://github.com/ZoiDiama/My-tidytuesday-projects/blob/9b5737a31939ec63b1dce6bab338afc334b51264/Code/2023/Week%2052#L1-L105)

![TT2023Week52](https://github.com/ZoiDiama/My-tidytuesday-projects/assets/139105670/c6373430-32e8-4e76-bf50-64a394adf0db)

</details>

<details close>
  <summary>2024</summary>

This was my second year making graphs for TidyTuesday. I created 40 visuals throughout the year. Along with improving my plot designs, I also focused on typography, colors etc. I used Figma to polish my final designs. My work included both traditional plots (bar, line, pie) and creative ones like streamgraphs, jitter plots, and alluvial diagrams.

### Week 2 | Canadian Hockey Players

The data this week comes from Statistics Canada .The graph was prepared with ggplot. Instead of considering birth month, my focus shifted to analyzing the height variations between Canadian and international players in the NHL.

Check the code [here](https://github.com/ZoiDiama/My-tidytuesday-projects/blob/aa0cd9959aba935d81078f7819e115eda1b68644/Code%202024/Week%202#L1-L112)

![TT2024Week2](https://github.com/ZoiDiama/My-tidytuesday-projects/assets/139105670/3e34abdf-e0ba-4670-8f95-2953f567202e)

### Week 3 | US Polling Places 2012-2020

The data this week comes from The Center for Public Integrity.The graph was prepared with ggplot and final edits were made with Figma. 

Check the code [here](https://github.com/ZoiDiama/My-tidytuesday-projects/blob/d8a5766568746806823ed1b87035e3ffac8989c7/Code%202024/Week%203#L1-L125)

![TT2024Week3_figma](https://github.com/ZoiDiama/My-tidytuesday-projects/assets/139105670/f46600d3-404e-4311-ba10-0a70cb816225)

### Week 4 | Educational attainment of young people in English towns

The data this week comes from The UK Office for National Statistics.The graph was prepared with ggplot  and final edits were made with Figma.

Check the code [here](https://github.com/ZoiDiama/My-tidytuesday-projects/blob/64db00486dd77f856422b0809e53fbfbd246e4a2/Code%202024/Week%204#L1-L103)

![TT2024_week4_Figma](https://github.com/ZoiDiama/My-tidytuesday-projects/assets/139105670/db7b8751-7329-471d-823b-d87af7aec162)

### Week 5 | Groundhog predictions

The data this week comes from groundhog-day.com.The graph was prepared with ggplot and final edits were made with Figma.

Check the code [here](https://github.com/ZoiDiama/My-tidytuesday-projects/blob/ef098be27a5f5c4acf24f23f826bbb86e62c429f/Code%202024/Week%205#L1-L131)

![TT2024Week5_figma](https://github.com/ZoiDiama/My-tidytuesday-projects/assets/139105670/b01a4e95-09ba-4e46-9ff7-55c2f93ecb03)

### Week 6 | A few world heritage sites

This week we analyse a small subset of UNESCO World Heritage Sites and we are inspired by the "1 dataset, 100 visualizations" project made by Ferdio.The graph was prepared with ggplot  and final edits were made with Figma.

Check the code [here](https://github.com/ZoiDiama/My-tidytuesday-projects/blob/86d5c3e78cde7efd6646e7a29cd185675f073cb8/Code%202024/Week%206#L1-L106)

![TT2024Week6_figma](https://github.com/ZoiDiama/My-tidytuesday-projects/assets/139105670/15b0710c-a43a-40ed-b665-35adb7ea463e)
  
### Week 7 | Valentine's Day Consumer Data

This week we analyse Valentine's Day survey data by Valentine's Day Data Center .The graph was prepared with ggplot and final edits were made with Figma.

Check the code [here](https://github.com/ZoiDiama/My-tidytuesday-projects/blob/3bd5adfb5a71c7e8fc2dc3425116f6b2944ea5ba/Code%202024/Week%207#L1-L118)

![TT2024Week7 2 (2)](https://github.com/user-attachments/assets/537bff22-bf4c-45dc-8f73-b1c4e9a61dda)

### Week 8 | R Consortium ISC Grants

This week we analyse R Consortium ISC Grants data.The graph was prepared with ggplot and final edits were made with Figma.

Check the code [here](https://github.com/ZoiDiama/My-tidytuesday-projects/blob/5beb4b3fa38b9d99f2f42c8ab63d893b6c22f335/Code%202024/Week%208#L1)

![Group 75](https://github.com/ZoiDiama/My-tidytuesday-projects/assets/139105670/9b94e522-3a19-4162-94fa-6637d31eee09)

### Week 9 | Leap Day

This week we analyse the data from the February 29 article on Wikipedia..The graph was prepared with ggplot.

Check the code [here](https://github.com/ZoiDiama/My-tidytuesday-projects/blob/d937c79cf26a4108c5e1fcfb797fb22d46a5de8b/Code%202024/Week%209#L1-L125)

![TT2024Week7](https://github.com/ZoiDiama/My-tidytuesday-projects/assets/139105670/8b77e788-f67f-40ca-86e7-6fa77dccd78f)

### Week 10 | Trash Wheel Collection Data

Check the code [here](https://github.com/ZoiDiama/My-tidytuesday-projects/blob/3f0266042d104c20fabcf24a6c7169be5d9c9a45/Code%202024/Week%2010#L1-L139)

![TT2024Week10 1](https://github.com/ZoiDiama/My-tidytuesday-projects/assets/139105670/8f266ebe-3213-4778-9f92-0a514ff867ce)

### Week 11 | Fiscal Sponsors

Check the code [here](https://github.com/ZoiDiama/My-tidytuesday-projects/blob/a3c5c45bf840b70d0211d0598a9ca383fee054b7/Code%202024/Week%2011#L1-L105)

![TT2024Week11 1 (2)](https://github.com/user-attachments/assets/05300f56-6308-49b6-9649-0d8c974da782)


### Week 11 | 2023 & 2024 US Solar Eclipses

Check the code [here](https://github.com/ZoiDiama/My-tidytuesday-projects/blob/46091eedd4006e021069708f9b899fe50fd2271a/Code%202024/Week%2015#L1)

![TT2024Week_15](https://github.com/user-attachments/assets/8543f4a4-823c-47ed-b95d-3e04b5a780e3)

### Week 14 | Du Bois Visualization Challenge 2024

Check the code [here](https://github.com/ZoiDiama/My-tidytuesday-projects/blob/d7d51bd24dab23a1d830bd831b0dbda36a3d9d99/Code%202024/Week%2014#L1)

![TT2024Week_14](https://github.com/user-attachments/assets/33a09c59-c003-4bad-85ed-af7407da9831)


### Week 17 | Objects Launched into Space

The graph was prepared in R and the final desing was made with Figma. 

Check the code [here](https://github.com/ZoiDiama/My-tidytuesday-projects/blob/184db5c457c1acbecae3d535969d114b2953d04b/Code%202024/Week%2017#L1-L114)

![TT2024Week17 1 (1)](https://github.com/user-attachments/assets/7472f043-b27e-4df1-acae-ea52e11bfc00)

### Week 18 | Worldwide Bureaucracy Indicators

The graph was prepared in R and the final desing was made with Figma. 

Check the code [here](https://github.com/ZoiDiama/My-tidytuesday-projects/blob/a268923887c2e0dbb4c74e436270bacab9cd7dcf/Code%202024/Week%2018#L1-L120)

![TT_week_18](https://github.com/user-attachments/assets/d5b029d8-c347-4e80-8e45-c7c17520fdab)

### Week 19 | Rolling Stone Album Rankings

The graph was prepared in R. 

Check the code [here](https://github.com/ZoiDiama/My-tidytuesday-projects/blob/4adae83b6a904462068498f2e1ceeac5d9ee8341/Code%202024/week%2019#L1)

![TT2024Week19](https://github.com/user-attachments/assets/6a5d83fd-137d-4f85-908b-5cc4b8d82c5e)

### Week 20 | The Great American Coffee Taste Test

Check the code [here](https://github.com/ZoiDiama/My-tidytuesday-projects/blob/4e3a9dde83fdf102f7e855d8844681f7740e924b/Code%202024/Week%2020#L1-L121)

![TT2024Week20_figma](https://github.com/ZoiDiama/My-tidytuesday-projects/assets/139105670/096576c8-e92b-43ad-ac1a-c7f3100d5662)

### Week 21 | Carbon Majors Emissions Data

Check the code [here](https://github.com/ZoiDiama/My-tidytuesday-projects/blob/b63fbd144ad42467cc1ca117154806f1c6e917bc/Code%202024/Week%2021#L1-L122)

![TT2024Week21](https://github.com/ZoiDiama/My-tidytuesday-projects/assets/139105670/5c1047d9-02ab-42a3-9332-4f9d6f8f9896)

### Week 22 | Lisa's Vegetable Garden Data

The graph was prepared in R and the final desing was made with Figma. 

Check the code [here](https://github.com/ZoiDiama/My-tidytuesday-projects/blob/10c1df73bad064ae65d907baddf811b8052eaa6c/Code%202024/Week%2022#L1-L89)

![week22 (1)](https://github.com/user-attachments/assets/5ac02908-283b-4e14-8266-4ccd869ac63b)

### Week 23 | Cheese

The graph was prepared in R and the final desing was made with Figma. 

Check the code [here](https://github.com/ZoiDiama/My-tidytuesday-projects/blob/6bf695c266dc37f3208916cc440ac46a88c36e23/Code%202024/Week%2023#L1)

![TT_week_21 (5)](https://github.com/user-attachments/assets/e7e56354-0688-46be-abc5-75d24bdf56d9)

### Week 24 | Campus Pride Index

The graph was prepared in R and the final desing was made with Figma. 

Check the code [here](https://github.com/ZoiDiama/My-tidytuesday-projects/blob/aa94d605dc46bf26437b1c8395bd5df0f1b54477/Code%202024/Week%2024#L1-L113)

![week 24](https://github.com/user-attachments/assets/c670d6ba-2e64-4bd2-88a3-87f7b6ac9cf6)

### Week 25 | US Federal Holidays

The graph was prepared in R and the final desing was made with Figma. R code inspired by R Coder in https://r-coder.com/calendar-plot-r/

![TT2024Week25](https://github.com/user-attachments/assets/162abb7a-ba89-42ef-8e86-da93ac7730cc)

### Week 26 | tidyRainbow Datasets

The graph was prepared in R. 

Check the code [here](https://github.com/ZoiDiama/My-tidytuesday-projects/blob/595a22cec50665f5d0eaf01a3eaf14423e241eb8/Code%202024/Week%2026#L1-L136)

![TT2024Week26](https://github.com/user-attachments/assets/fdb8bdc3-ee96-4ef9-9bb2-6135922b9128)

### Week 27 | TidyTuesday Datasets

The graph was prepared in R. 

Check the code [here](https://github.com/ZoiDiama/My-tidytuesday-projects/blob/8a59cab2c8736ff4635e3a9c3bed19ddbe63cfd8/Code%202024/Week%2027#L1)

![TT2024Week27](https://github.com/user-attachments/assets/ddd1b541-951d-47dd-9066-f0a100337610)

### Week 28 | David Robinson's TidyTuesday Functions

The graph was prepared in R and the final desing was made with Figma. 

Check the code [here](https://github.com/ZoiDiama/My-tidytuesday-projects/blob/271d3a0c35e28b9d1f05bf9aa0e260486f00ce85/Code%202024/Week%2028#L1)

![TT2024Week_28 2](https://github.com/user-attachments/assets/5ad00671-272a-4b13-b61c-953099c9959a)

### Week 29 | English Women's Football

The graph was prepared in R and the final desing was made with Figma. 

Check the code [here](https://github.com/ZoiDiama/My-tidytuesday-projects/blob/097f7714eb82b8ebafc2bdeb2272d903042ac5a2/Code%202024/Week%2029#L1-L114)

![TT2024Week29 1 (1)](https://github.com/user-attachments/assets/c92ee14b-b922-4053-acaf-e511eb1672c0)

### Week 30 | American Idol

The graph was prepared in R. 

Check the code [here](https://github.com/ZoiDiama/My-tidytuesday-projects/blob/a52f9a85ba62a03fd181332e401e49c8e6933c23/Code%202024/Week%2030#L1-L114)

![TT2024Week30 3](https://github.com/user-attachments/assets/1f42bd6a-827d-4086-a975-c8a4fef92df5)

### Week 31 | Summer Movies

The graph was prepared in R. 

Check the code [here](https://github.com/ZoiDiama/My-tidytuesday-projects/blob/a47d41ade715d330f0535ab138a9fa6c91b4fe17/Code%202024/Week%2031#L1-L111)

![TT2024Week_X 1 (1)](https://github.com/user-attachments/assets/0b84742f-6985-453e-af28-11342ba73764)

### Week 32 | Olympic Medals

The graph was prepared in R and the final desing was made with Figma. 

Check the code [here](https://github.com/ZoiDiama/My-tidytuesday-projects/blob/4dd30f6505e11e8536958c19895670f7029c17b0/Code%202024/Week%2032#L1)

![TT2024Week_32](https://github.com/user-attachments/assets/58885425-6d1e-449c-ae96-651bb62cf2a7)

### Week 33 | World's fair

The graph was prepared in R and the final desing was made with Figma. 

Check the code [here](https://github.com/ZoiDiama/My-tidytuesday-projects/blob/6b5a4aab16044c77c946ca9d6e3face376fca8c2/Code%202024/Week%2033#L1-L99)

![TT2024Week_X 2 (2)](https://github.com/user-attachments/assets/1ed10ba6-f1b4-4df0-8481-3fc303cbd186)

### Week 34 | English Monarchs and Marriages

The graph was prepared in R and the final desing was made with Figma. 

Check the code[here](https://github.com/ZoiDiama/My-tidytuesday-projects/blob/2bf94a1792686da56304532f99218a44787afdef/Code%202024/Week%2034#L1-L138)

![TT2024Week34](https://github.com/user-attachments/assets/f533fbe3-e097-4fb0-9f2f-50502b46f71c)

### Week 35 | The Power Rangers Franchise

The graph was prepared in R and the final desing was made with Figma. 

Check the code[here](https://github.com/ZoiDiama/My-tidytuesday-projects/blob/a96f5bd493cea56cad33739e1710ac2ba18820d6/Code%202024/Week%2035#L1)

![TT2024Week_35](https://github.com/user-attachments/assets/92375c72-fcf2-4aa2-8e82-327f2b19c416)

### Week 36 | Stack Overflow Annual Developer Survey 2024

The graph was prepared in R. 

Check the code [here](https://github.com/ZoiDiama/My-tidytuesday-projects/blob/a17150faa22ad2138433047492754555f7a448da/Code%202024/Week%2036#L1-L129)

![TT2024Week_36](https://github.com/user-attachments/assets/621be1ea-2e86-4af6-b604-08b80148892a)

### Week 37 | Economic Diversity and Student Outcomes

The graph was prepared in R. 

Check the code [here](https://github.com/ZoiDiama/My-tidytuesday-projects/blob/25c6a08ae2cd5e09e90cc671f7f333cee4c2218a/Code%202024/Week%2037#L1)

![TT2024Week_37](https://github.com/user-attachments/assets/cc3a51be-4df9-4996-8c1f-876391f26823)

### Week 38 | Shakespeare Dialogue

The graph was prepared in R and the final desing was made with Figma. 

Check the code [here](https://github.com/ZoiDiama/My-tidytuesday-projects/blob/2e3f3a081a264386db85afcae7f0d68e459c25c0/Code%202024/Week%2038#L1-L138)

![TT2024Week38](https://github.com/user-attachments/assets/e8724fb9-5517-4307-9b78-6d3919c8abb2)

### Week 39 | International Mathematical Olympiad (IMO) Data
The graph was prepared in R and the final desing was made with Adobe Illustrator. 

Check the code [here](https://github.com/ZoiDiama/My-tidytuesday-projects/blob/4b9cd1d82ff4edb40bda0e71898c9627caab4406/Code%202024/Week%2039#L1-L86)

![AI_draft-01](https://github.com/user-attachments/assets/cf30dea1-613f-4509-9c95-b5b69700cefa)


### Week 40 | Chess Game Dataset (Lichess)

The graph was prepared in R and the final desing was made with Figma. 

Check the code [here](https://github.com/ZoiDiama/My-tidytuesday-projects/blob/3b42a9e6d9962d5c98c37605f2aa6887f3b912be/Code%202024/Week%2040#L1-L130)

![TT2024Week40 1](https://github.com/user-attachments/assets/104e538e-3500-4fdb-98f5-99762b803efa)

### Week 41 | National Park Species

The graph was prepared in R.

Check the code [here](https://github.com/ZoiDiama/My-tidytuesday-projects/blob/7c9f06ace9684ca1740b9d0635c9624898230c9f/Code%202024/Week%2041#L1-L130)

![TT2024Week_41](https://github.com/user-attachments/assets/216d65d6-e3bf-4cfa-a5a6-3dc8b97bbf3a)

### Week 42 | Southern Resident Killer Whale Encounters

The graph was prepared in R.

Check the code [here](https://github.com/ZoiDiama/My-tidytuesday-projects/blob/61818796a0bb99468d96e452befa590dfe9e33cb/Code%202024/Week%2042#L1)

![TT2024Week_42](https://github.com/user-attachments/assets/6586b56c-26ac-46d1-9c97-c66f464f995e)

### Week 43 | The CIA World Factbook

The graph was prepared in R. 

Check the code [here](https://github.com/ZoiDiama/My-tidytuesday-projects/blob/0346d4f5c05faafd9dd10a4633c0f8d31551b550/Code%202024/Week%2043#L1-L353)

![TT2024Week_43](https://github.com/user-attachments/assets/b0f9b662-8195-4f6c-b535-1fef2334b335)

### Week 44 | Monster Movies

The graph was prepared in R. 

Check the code [here](https://github.com/ZoiDiama/My-tidytuesday-projects/blob/87f78655143e131f5bfdae880935da727f1b482d/Code%202024/Week%2044#L1)

![TT2024Week_44](https://github.com/user-attachments/assets/4828658b-d45e-4d84-aa08-d0330bca6d1f)

</details>

<details close>
  <summary>2025</summary>

### Week 1 | Bring your own data to start the year!

The graph was prepared in R and Figma. 

Check the code [here](https://github.com/ZoiDiama/My-tidytuesday-projects/blob/6fe630360628c9b56dcd543ce5308ffaaff18055/Code%202025/Week%201#L1)

![Image](https://github.com/user-attachments/assets/e075746a-eea9-4555-ab87-30a395c4d59b)

### Week 2 | posit::conf talks

The graph was prepared in R and Figma. 

Check the code [here](https://github.com/ZoiDiama/My-tidytuesday-projects/blob/7b0e3c0a4277cbda1b0c4ad1f4cf51a9aa9193eb/Code%202025/Week%202#L1)

![Image](https://github.com/user-attachments/assets/0e0c9af7-c589-4143-abf4-d4ce46016a39)

### Week 3 | The History of Himalayan Mountaineering Expeditions

The graph was prepared in R and Figma. 

Check the code [here](https://github.com/ZoiDiama/My-tidytuesday-projects/blob/c6a11fc9464669cf8d3a5eccb5b23297403243fa/Code%202025/Week%203#L1)

![Week 3](https://github.com/user-attachments/assets/0fe0a989-4b98-430e-ab4d-ae1e3781314a)


  </details>

## Gallery of examples: 

<p align="center">
<img src="https://github.com/ZoiDiama/My-tidytuesday-projects/assets/139105670/91bbf2f5-a325-4bad-b9a0-df98a108f8f4" alt="DR WHO" width="200"/>
<img src="https://github.com/user-attachments/assets/5ad00671-272a-4b13-b61c-953099c9959a" alt="TT2024Week_28 2" width="200"/>
 <img src="https://github.com/user-attachments/assets/e8724fb9-5517-4307-9b78-6d3919c8abb2" alt="TT2024Week38" width="200"/>
 </p>
  
  


<p align="center">
    <img src="https://github.com/ZoiDiama/My-tidytuesday-projects/assets/139105670/15b0710c-a43a-40ed-b665-35adb7ea463e" alt="TT2024Week6_figma" width="200"/>
  <img src="https://github.com/user-attachments/assets/05300f56-6308-49b6-9649-0d8c974da782" alt="TT2024Week11 1 (2)" width="200"/>
  <img src="https://github.com/user-attachments/assets/6a5d83fd-137d-4f85-908b-5cc4b8d82c5e" alt="TT2024Week19" width="200"/>
  
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/92375c72-fcf2-4aa2-8e82-327f2b19c416" alt="TT2024Week_35" width="200"/>
 
</p>



















