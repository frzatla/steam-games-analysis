**<h3> Project Overview </h3>**

This project analyzes the Steam Games dataset from Kaggle to identify what drives video game success on the platform. By exploring genres, pricing models, and release timing, the analysis uncovers how these specific factors impact player engagement and estimated sales as of December 2025.

**<h3> Key Objectives: </h3>**
- Identify correlations between Genre and User Ratings.
- Identify the optimal price range that maximizes sales for Indie vs. AAA titles.
- Determine the most optimal month to release a game.

**<h3> Data Source: </h3>**
Dataset is created by Martin Bustos on Kaggle. Data is collected from both the API provided by Steam themselves and Steam Spy, a Steam stats service based on Web API provided by Valve. <br>
Covers game up until the release year of 2025. <br>
https://www.kaggle.com/datasets/fronkongames/steam-games-dataset/data

**<h3> Attributes / Features: </h3>**
**AppID**: Unique identifier for each game on the Steam store.

**Name**: The game's title.

**Release date**: The date the game was released on Steam.

**Estimated owners**: A range estimating the number of people who own the game (for example, "0 - 20000", "20000 - 50000").

**Peak CCU**: The peak number of Concurrent Users (players) in the game on the previous day.

**Required age**: The minimum age required to play the game (0 indicates all ages).

**Price**: The current price of the game in US Dollars.

**Discount**: The number of discounts the game has experienced.

**DLC count**: The number of downloadable content (DLC) packs available for the game. 

**About the game**: A brief text description or summary of the game's content.

**Supported languages**: A list of all languages supported by the game (interface, audio, or subtitles).

**Full audio languages**: A list of languages that have full audio support (voice acting).

**Reviews**: A text summary of the user review score (for example, "Overwhelmingly Positive", "Mixed").

**Header image**: The URL to the game's main header image/banner on the store.

**Website**: The URL to the game's official website.

**Support url**: The URL for the game's customer support page.

**Support email**: The contact email address for game support.

**Windows**: True if the game is compatible with Windows, False otherwise.

**Mac**: True if the game is compatible with macOS, False otherwise.

**Linux**: True if the game is compatible with Linux, False otherwise.

**Metacritic score**: The game's critic score from Metacritic (0 if not available).

**Metacritic url**: The URL to the game's Metacritic page.

**User score**: A score calculated based on user reviews (0 if not available or insufficient data).

**Positive**: The total count of positive user reviews.

**Negative**: The total count of negative user reviews.

**Score rank**: A ranking of the game based on its user score compared to others (often null for most games).

**Achievements**: The total number of in-game achievements available.

**Recommendations**: The number of times users have recommended this game.

**Notes**: Extra information or warnings about the game content.

**Average playtime forever**: The average total playtime for all owners of the game (in minutes).

**Average playtime two weeks**: The average playtime in the last two weeks (in minutes).

**Median playtime forever**: The median total playtime for owners of the game (in minutes).

**Median playtime two weeks**: The median playtime in the last two weeks (in minutes).

**Developers**: The name of the studio or individual who created the game.

**Publishers**: The name of the company that published the game.

**Categories**: A list of game categories (for example, "Single-player", "Multi-player", "Co-op").

**Genres**: A list of genres the game belongs to (for example, "Action", "Indie", "RPG").

**Tags**: User-defined tags that describe the game (for example, "Pixel Art", "Difficult").

**Screenshots**: URLs to screenshots of the gameplay.

**Movies**: URLs to trailers or promotional videos.
