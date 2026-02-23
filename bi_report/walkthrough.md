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
  - **Most Divisive Shows** — Largest rating gap between audience and critics. Critics loved "Saved by the Bell" far more than audiences; audiences loved "Stalker" far more than critics.
  - **Universal Favorite** — Where critics and users agree: "The Sopranos"

- **Top 5 Matrices** — Shows top 5 by users and by critics, with the corresponding score from the other group to highlight agreement or disagreement.

- **Consensus** — Adjustable threshold lets users explore how many shows are rated within X points by both audiences and critics (e.g., within 3 points).

- **Score Distribution** — Compares how scores are distributed for users vs critics. Both peak in the 60–69 range, showing general alignment overall.


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

Selecting **Comedy** filters all visuals to show comedy-specific insights — most divisive comedy, top 5 comedies by audience, and so on.

<p align="center">
  <img src="../images/overview-page-comedy-genre.png" alt="Comedy filter" width="800"/>
</p>

#### Filtering by Year: 2024

Similarly, selecting **2024** filters to shows released that year:

<p align="center">
  <img src="../images/overview-page-year-2024.png" alt="2024 filter" width="800"/>
</p>
## Page 2: People & Companies


<img src="../images/people-companies.png" alt="comedy" width="800"/>

### Cards
Occupying the top row are 4 static cards giving statistics on the number of directors, actors, writers and production comppanies
### Entity Analysis


Consider the Director entity. The report user can gain insights into which directors have the highest rated shows by the critics and audience trhough the matrix visuals. Furthermore, because some directors have only one show and may be a "one trick pony" all told, a minimum number of shows paramater is introduced which allows the report viewer to determine the minimum number of shows the entity must have produced.

Farther down we have a bar chart to show the most prolific directors, for example. 

The report viewe can then switch entities by clicking the appropraite button to gain similar insights. 
We use **bookmarks** to switch between Directors, Actors, Creators, Companies.