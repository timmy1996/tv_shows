## Page 1: Overview

<p align="center">
  <img src="../images/overview-page.png" alt="Overview" width="800"/>
</p>

### KPI Cards
- Total Shows
- Average Metascore / Userscore (surprisingly identical)
- Typical score gap between users and critics (absolute value)

### Key Visuals

- **Insight Cards**
  - **Most Divisive Shows** : Largest rating gap between audience and critics. Critics loved "Saved by the Bell" far more than audiences; audiences loved "Stalker" far more than critics.
  - **Universal Favorite** : Where critics and users agree: "The Sopranos"

- **Top 5 Matrices** : Shows top 5 by users and by critics, with the corresponding score from the other group to highlight agreement or disagreement.

- **Consensus** : Adjustable threshold lets users explore how many shows are rated within X points by both audiences and critics (e.g., within 3 points).

- **Score Distribution** : Compares how scores are distributed for users vs critics. Both peak in the 60–69 range, showing general alignment overall.


### Slicer Panel

A slicer panel on the left enables deeper exploration by genre and release year.

<p align="center">
  <table>
    <tr>
      <td align="center"><img src="../images/slicer-1.png" width="200"/></td>
      <td align="center"><img src="../images/slicer-2.png" width="200"/></td>
    </tr>
  </table>
</p>

#### Filtering by Genre: Comedy

Selecting **Comedy** filters all visuals to show comedy-specific insights : most divisive comedy, top 5 comedies by audience, and so on.

<p align="center">
  <img src="../images/overview-page-comedy-genre.png" alt="Comedy filter" width="800"/>
</p>

#### Filtering by Year: 2024

Similarly, selecting **2024** filters to shows released that year:

<p align="center">
  <img src="../images/overview-page-year-2024.png" alt="2024 filter" width="800"/>
</p>


## Page 2: People & Companies

<p align="center">
  <img src="../images/people-companies.png" alt="People & Companies" width="800"/>
</p>

### KPI Cards

Four static cards display totals for Directors, Actors, Writers, and Production Companies.

### Entity Analysis

Users can select which entity to explore via toggle buttons. Bookmark-based navigation switches between Directors, Actors, Creators, and Companies.

**For each entity:**
- **Top Rated** : Matrix visuals show highest-rated by critics and by audience
- **Most Prolific** : Bar chart shows entities with the most shows

**Minimum Shows Threshold** : Some entities have only one show and may be a "one-hit wonder." An adjustable parameter lets users set the minimum number of shows an entity must have to appear in the ratings rankings.

By way of example, below is the view when "Actors" are selected.
<p align="center">
  <img src="../images/actor-toggle.png" alt="Entity toggle" width="600"/>
</p>

## Page 3: Genre, Release Year & Content Rating Analysis

<p align="center">
  <img src="../images/genre-year-content.png" alt="Genre and Year Analysis" width="800"/>
</p>

### Visuals

- **Ratings Over Time (Line Chart)**: Shows average critic and audience ratings by release year. Earlier years (pre-2000) have fewer shows, so averages may represent only one or two titles. That said, ratings remain relatively stable over time, i.e. there is no consistent upward or downward trend.

- **Top Genres by Volume (Bar Chart)**: Horizontal bar chart ranking genres by number of shows. Overall (with no slicers/filters) Drama leads, followed by Comedy.

- **Genre Share by Release Year (Area Chart)**: Shows genre proportions over time, revealing how the genre mix has evolved.

- **Year-on-Year Analysis**: Compare show counts and percentage growth between consecutive years. Users select a comparison year; the dashboard displays the change in volume and percentage growth. For example, 2022 vs 2021 shows 28 more shows (+13.9%). A clustered bar chart breaks this down by genre with Romance having the largest growth. *Note: This dataset is not exhaustive; conclusions are limited by the data source.*

### Slicer Panel

The slicer panel allows further exploration by genre and content rating.

<p align="center">
  <table>
    <tr>
      <td align="center">
        <img src="../images/genre-slice.png" width="500"/>
        <br><em>Filtering by Action, Adventure & Animation</em>
      </td>
      <td align="center">
        <img src="../images/content-rating-slice.png" width="500"/>
        <br><em>Filtering by content rating</em>
      </td>
    </tr>
  </table>
</p>

## Closing Thoughts

This project was an exercise in turning raw entertainment data into interesting insights.

There's always room to extend: additional pages for networks, seasons, or episode-level analysis could add further depth.
