# Formula 1 Race Intelligence

Formula 1 Race Intelligence is an interactive data analysis and visualization project developed using Tableau. It focuses on exploring the vast amount of information generated throughout Formula 1 racing and converting it into understandable visual insights. The project examines several important aspects of the sport, such as team and driver performance, tyre-compound effectiveness, Grand Prix hosting statistics, podium achievements, and race reliability. By presenting the data through different types of charts and dashboards, the project aims to make comparisons easier and reveal interesting patterns across the available racing seasons.

## Project Scenarios

### 1. F1 Team Performance Strategist

This scenario is designed to analyze the competitive performance of Formula 1 teams and drivers, with particular attention to championship results and race strategies.

- **Constructor Championship Points Trend:** illustrates how championship points earned by different constructors change from one season to another, helping identify improvements and variations in team performance.
- **Tyre Compound Performance by Circuit Type:** investigates podium results according to the starting tyre compound and circuit type, providing an overview of how tyre choices relate to race outcomes.
- **Driver Talent and Performance Ranking:** presents a comparison of drivers based on their performance statistics in a particular season, making it easier to identify leading performers.

### 2. Motorsport Broadcast Analyst

This scenario focuses on presenting Formula 1 records and statistics in an informative manner. It highlights historical achievements and important information that can be useful for understanding the sport.

- **All-Time Driver Points Leaderboard:** displays a ranking of drivers according to the total championship points accumulated across all seasons available in the dataset.
- **Countries Hosting the Most Grand Prix Rounds:** identifies the countries that have organized the greatest number of Grand Prix events by calculating the distinct number of races hosted.
- **Podium Achievements by Driver and Team:** visualizes the podium finishes recorded by different drivers and their associated teams, allowing their achievements to be compared.

### 3. F1 Technical Regulation Analyst

This scenario explores race reliability and retirement-related statistics. It aims to highlight patterns in race completion and provide an overview of the challenges faced by different drivers and teams.

- **DNF Reasons by Team:** analyzes the recorded reasons behind races not finished by drivers from different teams and compares the distribution of retirement categories.
- **DNF Patterns by Circuit Type and Driver:** examines the occurrence of DNFs among different drivers across various circuit types to identify possible differences in retirement patterns.
- **Driver and Team Reliability Trend:** represents race-completion rates across multiple seasons, helping compare reliability trends among drivers and teams.

## Dataset Description

The project uses a collection of related data tables containing information about circuits, championships, qualifying sessions, laps, and race results. These tables provide the foundation for creating the visualizations and performing the required analysis.

| Sheet | Description |
|---|---|
| `circuits` | Contains details about different Formula 1 circuits along with their associated information and characteristics. |
| `championship_standings` | Provides driver championship standings and the points earned by drivers across individual seasons. |
| `lap_intelligence` | Contains detailed lap-level information that can be used to study race performance and related statistics. |
| `qualifying_results` | Stores qualifying session information and the results achieved by participating drivers. |
| `race_results` | Includes race outcomes, driver and constructor details, finishing positions, tyre information, and recorded retirement details. |

## Sharing Through Tableau Public

Tableau Public provides a convenient way to publish and share interactive visualizations online. Once the workbook has been published, other users can access the project through a web browser using its public link.

1. Open the completed workbook in Tableau Public Edition.
2. Sign in to an existing Tableau Public account or create a new free account.
3. Navigate to **Server → Tableau Public → Save to Tableau Public**. The exact wording or location of the option may vary depending on the Tableau version.
4. Wait for the workbook to finish publishing, then visit your Tableau Public profile to locate the published visualization.
5. Select the **Share** option to copy the public URL and share it with others.

## Tools Used

The following tools and platforms support the preparation, analysis, visualization, and sharing of the project:

- **Tableau** — used to create charts, interactive dashboards, filters, and story presentations for exploring Formula 1 statistics.
- **Microsoft Excel / Spreadsheet Data** — used for accessing, examining, organizing, and preparing the dataset for further analysis.
- **GitHub** — used for maintaining the project repository, organizing related files, tracking changes, and sharing the project with others.

## Notes and Limitations

- The analysis is performed using only the seasons and records included in the supplied dataset. Since the latest season may contain incomplete records, its results and statistics should be considered with appropriate care.
- Championship standings are available at the driver level. Therefore, calculating constructor-level points requires the correct identification of the team associated with each driver during the corresponding season.
- The country hosting a Grand Prix and the nationality of a participating driver represent two different attributes. To perform nationality-based analysis, a reliable driver nationality field or a separately verified reference table is required.
- DNF analysis is dependent on the retirement information and status classifications available in the dataset. These categories should be examined and understood before interpreting the visualized results.
- Joining data tables that contain different levels of detail may lead to duplicated records and incorrect aggregations. It is important to verify row counts and calculated totals after combining tables. Tableau relationships should be preferred wherever they are suitable.
- The visualizations are intended to present useful comparisons, highlight trends, and reveal relationships within Formula 1 data. However, the patterns displayed should not be treated as definite proof of the causes behind particular race outcomes, performance changes, or retirement incidents.
