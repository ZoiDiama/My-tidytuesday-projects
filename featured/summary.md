# Featured charts: the story behind each one

Seven charts from my #TidyTuesday work, each with why it matters, what I found, and what to take from it. All charts were built in R, and most were finished in Figma. The code is linked in the [chart catalogue](../Chart_Catalogue.md).

📄 Prefer one file? Download the [portfolio (PDF)](tidytuesday-portfolio.pdf).

---

## 1. Men do 75% of the talking in Springfield

![Treemap of words spoken by Simpsons characters, split by gender](2025_w05.png)

**Why it matters:**The Simpsons has been on TV for over 35 years. Millions of people have grown up with it. So who gets to talk on the show matters.

**What I found:** Most of the characters are men: 79%. And they don't just show up more, they talk more too: 75% of all the words. Apart from Marge and Lisa, the women barely speak.

**The takeaway:** Counting heads isn't enough. To understand representation, measure voice too.

<sub>Data: Simpsons dataset, Kaggle · Characters without gender information are excluded · TidyTuesday 2025, week 5</sub>

---

## 2. Space got crowded fast

![Streamgraph of objects launched into space by country, 1957–2023](2024_w17.png)

**Why it matters:** Orbit around the Earth is shared by everyone, but it's filling up quickly, and mostly through a few countries.

**What I found:** For decades launches stayed fairly flat, after an early jump to 142 in 1963. Then, after 2015, numbers took off: more than 1,000 objects a year since 2019, out of 34,595 in total. The United States alone accounts for 9,632.

**The takeaway:** The space story is no longer about firsts, but about volume. The growth is recent, sudden and concentrated.

<sub>Data: Our World in Data · TidyTuesday 2024, week 17</sub>

---

## 3. Being 8,000 m tall isn't enough

![Glyph chart of expeditions to 16 Himalayan summits above 8,000 m, 2020–2024](2025_w03.png)

**Why it matters:** Where people put their effort is rarely spread evenly. It follows reputation.

**What I found:** Of 16 summits above 8,000 m in the Nepal Himalaya, 8 saw no expeditions at all in 2020–2024. The 8 that did are the "official" eight-thousanders. Everest alone drew 189 expeditions, about 2 in every 5. And Manaslu, one of the shortest, came second with 96.

**The takeaway:** A famous list can matter more than the thing it measures. Being on the list, not height, decides where climbers go.

<sub>Data: The Himalayan Database · TidyTuesday 2025, week 3</sub>

---

## 4. Hamlet never stops talking

![Voronoi treemap of words spoken by characters in Hamlet, Macbeth and Romeo and Juliet](2024_w38.png)

**Why it matters:** How a story shares out its words tells you whose story it is.

**What I found:** Hamlet speaks 11,543 words, 38% of his play. Macbeth takes 31% of his. But Romeo and Juliet split their play almost evenly (4,665 and 4,263 words), with a large supporting cast.

**The takeaway:** Two tragedies are about one man's mind, and one is about a relationship, and you can see it in the word counts alone.

<sub>Data: shakespeare.mit.edu · Top 10 characters per play, including stage directions · TidyTuesday 2024, week 38</sub>

---

## 5. The planet has warmed sharply since 1980

![Heatmap of monthly global temperature anomalies, 1880–2023](2023_w28.png)

**Why it matters:** Climate change is often shown as one line. That makes it look like a slow trend rather than a change you can feel in every season.

**What I found:** Every month from 1880 to 2023, compared with the 1951–1980 average. Until around 1980, the picture is a mix of blue and pale red. After that, it turns red in every month of the year, reaching up to 1.37°C above the baseline.

**The takeaway:** This isn't a few hot summers. The whole calendar has shifted.

<sub>Data: NASA GISS Surface Temperature Analysis (GISTEMP v4) · TidyTuesday 2023, week 28</sub>

---

## 6. Fewer than 1 in 5 of rock's "greatest albums" are by women

![Waffle chart of Rolling Stone's 500 greatest albums by artist gender, 2003, 2012 and 2020](featured/2025_w05.png)

**Why it matters:** "Greatest of all time" lists shape what gets played, taught and remembered.

**What I found:** Across Rolling Stone's 2003, 2012 and 2020 lists, only 170 entries were by female artists. The share nearly tripled, from 6% to 17%, but it's still far from parity.

**The takeaway:** Canons change, but slowly. A list called "the greatest" also reflects who was recorded, reviewed and voting.

<sub>Data: Rolling Stone / Data is Plural · "Mixed" groups shown separately · TidyTuesday 2024, week 19</sub>

---

## 7. Over 250,000 Americans live without plumbing

![Waffle chart showing 0.08% of the US population without plumbing](2025_w04.png)

**Why it matters:** Small percentages can hide large numbers of people.

**What I found:** In 2023, 0.08% of the US population lacked basic plumbing at home. It looks like a rounding error, a single tiny square out of 100. But it's about 265,000 people.

**The takeaway:** Always turn a small share back into a head count. "Almost everyone" still leaves people out.

<sub>Data: U.S. Census Bureau via tidycensus · TidyTuesday 2025, week 4</sub>
