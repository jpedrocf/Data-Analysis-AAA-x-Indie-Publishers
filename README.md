# Comparative Analysis of AAA and Indie Game Publishers on Steam for 2024 Releases

This research aims to conduct an exploratory comparative analysis between the performance of AAA and Indie game publishers using data exclusively from the Steam library, focusing on games released between January 1, 2024, and September 9, 2024. The analysis is based on a single comprehensive dataset that includes variables such as game titles, release dates, copies sold, prices, total revenue, average playtime, review scores, publisher classifications (AAA, Indie), the names of developers and publishers.

The study will graphically represent the main differences between AAA and Indie publishers, examining market trends, sales performance, audience appeal and critical reception within this specific timeframe. By focusing solely on Steam data, the research will provide insights into how these games perform on one of the largest digital distribution platforms for PC gaming.

This approach will offer a timely snapshot of the 2024 gaming market on Steam, illustrating how these publishers navigate the platform to capture audience interest and achieve commercial success. The data underscores how evolving market dynamics and the appeal of creative freedom are empowering smaller developers to make a mark in the gaming industry.

To better illustrate the relationship between key variables, the following correlation heatmaps were used to generate insights that guided the creation of further graphs and analyses throughout this work. They provide a side-by-side comparison of how different factors interact in both AAA and Indie game releases. These visualizations highlight distinct patterns in each category, offering deeper insights into varying market dynamics and player behavior, which will be further explored in the following sections.

<img src="https://github.com/user-attachments/assets/4180a4e9-1c0d-4297-8ee4-e7426f4f5e0d" alt="image" width="500" height="400">

<img src="https://github.com/user-attachments/assets/d2075125-12da-4396-b741-8705692eb605" alt="image" width="500" height="400">


## But what are AAA and Indie Publishers?

### AAA Publishers
AAA publishers are large, well-established companies known for producing high-budget, high-profile games. These games typically have extensive development teams, significant marketing budgets, and high production values, resulting in polished graphics, detailed gameplay and cinematic storytelling. Examples of AAA publishers include companies like Electronic Arts (EA), Ubisoft and Activision Blizzard. AAA games are often released across multiple platforms, including PC, consoles, sometimes mobile, aiming to reach a broad, global audience.


![NVIDIA GeForce GIF](https://media.giphy.com/media/dv0H4AykXpixbapq6k/giphy.gif)

_AAA Game - Black Myth: Wukong_

AAA titles are characterized by their focus on achieving high sales volumes, often through mainstream appeal, franchise development and leveraging popular genres like first-person shooters, sports games and open-world adventures. Due to their massive budgets, these games are generally expected to perform well commercially, and their success is often driven by extensive marketing campaigns, pre-orders and early access releases.

### Indie Publishers
Indie publishers, on the other hand, are smaller, independent companies or even individual developers who create games without the backing of major financial resources. Indie games are known for their creativity, unique gameplay mechanics and willingness to explore unconventional themes. Unlike AAA games, Indie titles are usually developed with much smaller budgets and smaller teams, often resulting in more experimental and innovative gameplay experiences.


<img src="https://media.giphy.com/media/FLbIyZXtv31xo1aJXO/giphy.gif" alt="DigiPen Game Dev GIF">

_Indie Game - Nohra_

Indie games have gained popularity thanks to digital platforms like Steam, which allow developers to reach audiences directly without needing the extensive marketing budgets typical of AAA games. Indie publishers often rely on word-of-mouth, social media and community engagement to promote their games. This model allows for more creative freedom but also comes with higher financial risks since the games don’t have the same guaranteed market presence as AAA titles.

##

The following chart highlights the significant difference in the number of releases between AAA and Indie games in 2024, with 52 AAA and 1301 Indie releases. This means that only 4 out of every 100 games released are from AAA studios. This disparity not only reflects the accessibility provided by platforms like Steam mentioned before but also the growing preference among players for diverse and innovative gaming experiences.


![Distribution Publisher](https://github.com/user-attachments/assets/5af89553-eac8-4649-8817-f177399fe1f1)



# Revenue Performance


Despite the overwhelming number of Indie game releases in 2024, AAA titles continue to dominate the gaming market when it comes to revenue generation. While Indie games offer diversity and creativity, the financial power of AAA studios cannot be ignored. Even though AAA publishers account for only 4% of the games released, they still managed to generate a total revenue of approximately $1.5 billion—almost double the $880 million earned by Indie games.

One standout example of this financial disparity is Black Myth: Wukong, a AAA title that alone has generated over $830 million in revenue—nearly matching the entire revenue of the Indie market. This monster-like revenue gap highlights the substantial influence of massive marketing budgets, established fanbases and blockbuster-level production quality that AAA games bring to the table. The following chart illustrates this monstruous contrast in total revenue between AAA and Indie games, underscoring the formidable financial muscle of AAA studios.

![Revenue - all data](https://github.com/user-attachments/assets/2c44d9be-6f9f-46ed-9f47-56b1e00597eb)


The disparity becomes even more monstrous when we compare the top five highest-revenue publishers from each category. The AAA 'monster' continues to dominate with approximately $1.5 billion in revenue, showing that nearly the entire amount is concentrated among just five major publishers, highlighting how the financial success of the AAA category is overwhelmingly driven by a small number of industry giants. This extreme revenue difference becomes even more apparent in the next chart, where the Indie 'monster,' with earnings around $150 million, is barely noticeable compared to the towering scale of the AAA revenue. The contrast is staggering, as the AAA giants completely overshadow their Indie counterparts.

![Revenue - top 5](https://github.com/user-attachments/assets/dd67cf39-00f2-4ddf-9aab-a61388899c87)


Continuing with the revenue performance analysis, interesting trends emerge when we examine the relationship between game prices and revenue for both Indie and AAA titles. In the scatter plot below, each point represents a game’s price and its corresponding revenue. Even when excluding two significant outliers — Black Myth: Wukong and HELLDIVERS 2 — a clear pattern emerges: lower-priced games tend to cluster around lower revenues, while higher-priced titles generally generate more substantial returns.

![scatter plot - AAA (price revenue)](https://github.com/user-attachments/assets/3eceda63-cb61-46e4-9448-55ac0ba5f2ea)


However, the most remarkable aspect of the Indie market is its diverse and innovative monetization strategies. A prime example is Once Human, the highest-grossing Indie game, which follows a free-to-play model, showing how alternative approaches can generate significant revenue without an upfront cost. On the other hand, Gray Zone Warfare, priced around $35, achieved the second-highest revenue among Indie games, demonstrating the flexibility of pricing strategies within the Indie scene. This variety allows independent developers to experiment with different formats, attracting a broad range of players and offering accessible gaming experiences. While AAA games often adhere to more rigid pricing models, the Indie market continues to evolve, using creativity and innovation as its core tools to maximize revenue in a highly competitive environment.

![scatter plot - Indie (price revenue)](https://github.com/user-attachments/assets/3801fa60-ab18-40c1-adbc-077ab3204844)


# Release Strategy

AAA games are often strategically released during key moments of the year to maximize their impact and revenue potential. One common approach is to align game releases with major holiday seasons, such as the end-of-year holiday rush, when consumer spending peaks. Additionally, AAA publishers frequently time their game launches to coincide with the release of related media, such as movies or TV series within the same franchise. An example of this is Star Wars Outlaws, a game that was released between the launches of seasons of a series on Disney+, keeping the franchise fresh in the consumer's mind.



<img src="https://media.giphy.com/media/7WfjbOXzDqkzixUPIp/giphy.gif" alt="Ubisoft Forward">

_AAA Game - Star Wars Outlaws_

Another important aspect of the AAA release strategy is tying launches to major gaming conventions and events. Announcing a game during large-scale events like E3, Gamescom or The Game Awards generates significant buzz, and releasing the game soon after these announcements keeps the momentum going. These carefully timed releases help AAA publishers generate massive waves of attention, driving immediate sales and engagement.

![gamescom](https://github.com/user-attachments/assets/2e3997ae-5b80-489d-a0af-10aac344e48a)

_Gamescom 2024_


However, this strategy can be risky when it comes to launching around AAA outliers—games that capture unprecedented levels of attention and break historical records. A prime example of this in 2024 was Black Myth: Wukong, which set a historic record for sales and concurrent players. Released during Gamescom (Aug/21), Wukong's launch dominated the market, drawing immense media coverage and player interest worldwide, as seen in the dramatic revenue spike in late August on the chart below. Competing directly with a game of this magnitude poses a significant risk for other AAA publishers, as even well-established titles could struggle to gain traction amidst such overwhelming competition.

![revenue by release date AAA](https://github.com/user-attachments/assets/f058ce2a-d757-4e03-b1fa-cf4d7b1ca7ba)

The data from 2024 highlights a clear trend: as publishers recognized the overwhelming market presence of Wukong, many chose to delay or avoid releases in the same window to prevent reduced visibility and sales. This illustrates the calculated risks in timing AAA launches, especially when contending with industry-shifting outliers. The following graph shows a sharp spike in AAA releases during March, a strategic move by publishers to maximize visibility and financial performance. March, aligned with many companies' fiscal year-end, allows publishers to boost financial results and avoid the competitive holiday season, making it an ideal release window.

![releases by release date AAA](https://github.com/user-attachments/assets/ddc56395-9729-482c-b9b4-4b520051d092)

Indie games were released consistently throughout the year, with no significant seasonal spikes like in AAA titles. This suggests that Indie developers do not rely as heavily on major events or specific release windows, likely due to the lack of accessibility to the large-scale marketing and promotional opportunities that major industry events, like E3 or Gamescom, offer to bigger studios. Instead, Indie developers focus on a steady stream of releases to maintain visibility in a crowded market, relying more on organic growth, niche communities, and digital platforms for exposure. Additionally, since Indie games are produced by a wide variety of publishers and small teams, the sheer number of releases helps maintain a balanced release pattern throughout the year, contributing to the overall consistency seen in the graph.

![releases by release date Indie](https://github.com/user-attachments/assets/7038768f-f39f-4b4e-b05e-e6891c18fa7b)


# Public Appeal: Review Scores

Review scores are a key indicator of both critical and public reception in the gaming industry. They provide insight into how well a game resonates with its audience, from gameplay mechanics to storytelling and technical performance. By comparing review scores between AAA and Indie games, we can gain a deeper understanding of the overall quality, consistency, and variability within each publisher class. The following boxplot illustrates the distribution of review scores, offering a visual comparison between AAA and Indie titles.

![boxplot review scores](https://github.com/user-attachments/assets/2ddd945f-5cad-4651-86ce-93bab1a9dd0b)

The median review scores for AAA and Indie games are surprisingly similar, showing that both can produce titles that resonate with players and critics. Indie games, however, have more variability and lower-scoring outliers due to the large number of releases on Steam.

Despite this, both AAA and Indie games are capable of achieving high review scores, proving that each can deliver standout titles that captivate players.

#

![scatter plot review scores](https://github.com/user-attachments/assets/51e9a92b-48bb-4482-85eb-8aba48deeb07)

This scatter plot demonstrates the relationship between review scores and average playtime for both Indie and AAA games. Notably, Indie games exhibit a wider range of average playtimes, with some surpassing even AAA games. Indie games, typically less complex in terms of graphics, gameplay, and on-screen information, tend to fit better into players' routines, allowing for longer and more consistent play sessions. Another key strategy of indie games is replayability, creating cyclical gameplay that, in a clever way, encourages players to spend more hours playing the same game repeatedly.


# Conclusion

This comparative analysis between AAA and Indie game publishers on Steam for 2024 releases highlights key distinctions in how each type of publisher navigates the gaming market. AAA publishers, with their massive budgets, focus on high-profile releases timed around key financial or cultural events, driving substantial revenue despite releasing fewer games. Their success is largely due to blockbuster marketing campaigns, established franchises, and polished production quality, exemplified by the immense financial impact of titles like Black Myth: Wukong.

On the other hand, Indie publishers dominate the market in terms of the sheer number of releases, leveraging platforms like Steam to reach diverse audiences with creative and innovative gameplay experiences. Despite their smaller budgets and fewer resources, Indie games have carved out a significant space in the gaming industry, driven by community engagement, alternative monetization strategies, and replayability. The consistent stream of Indie releases throughout the year, without the reliance on major marketing events, demonstrates their flexibility and adaptability.

Both AAA and Indie games have demonstrated the ability to achieve high review scores, showing that creativity, player engagement, and gameplay quality are not exclusively tied to budget size. While AAA games continue to dominate in terms of revenue, the Indie market’s growing appeal shows the industry's increasing openness to diverse gaming experiences. This study provides a snapshot of the evolving dynamics within the Steam platform, underscoring the complementary roles of AAA and Indie publishers in shaping the future of gaming.


# Data Preprocessing

In this stage, I conducted a comprehensive cleaning and transformation of the dataset. The goal was to ensure that the data was prepared for accurate analysis and model training. To achieve this, I addressed missing values, eliminated outliers that could potentially skew the results and normalized key numerical variables to bring consistency across different scales.

One of the critical maintenance tasks performed was the handling of missing data, as demonstrated below:


![Null Cleaning](https://github.com/user-attachments/assets/14740001-4ebe-42c3-b77c-e0bbabe43737)

_Null Cleaning with missingno_

During the model training phase, I first separated the features (X) and the target variable (y), where the target was the reviewScoreClass, a classification label derived from the game's review score. The data was split into training and test sets using an 80%-20% split to ensure a robust evaluation of the model's performance on unseen data. Before training, the feature set was scaled to normalize the data, enhancing the performance and convergence of the algorithm.

I then trained a RandomForestClassifier with a predefined random state to ensure reproducibility. After training, predictions were made on the test set, marking the completion of the training process.

In the evaluation phase, the model was assessed through various metrics. The confusion matrix provided an overview of the true positive, false positive, true negative, and false negative predictions, helping to identify potential misclassifications across different classes. Additionally, the accuracy score indicated that the model correctly predicted the outcome for approximately 62.5% of the test cases. Finally, a classification report was generated, detailing precision, recall, and F1-score for each class, giving a comprehensive view of the model's performance in terms of balancing precision and recall across classes.

This evaluation highlights both the model's strengths and areas where further tuning may improve overall performance.

##

*I hope this material has helped the reader to better understand each publisher's strategies for navigating the vast wave that is the gaming market in 2024, up until September. I would like to thank my professors for their support throughout my journey. See ya!*

<img src="https://pa1.aminoapps.com/6496/9b8856a1cbfa03a0603d54f2db3c315f8fdd1944_hq.gif" width="100" alt="Undertale GIF">

<img src="https://pa1.aminoapps.com/6496/9b8856a1cbfa03a0603d54f2db3c315f8fdd1944_hq.gif" width="100" style="transform: scaleX(-1);" alt="Undertale GIF">
