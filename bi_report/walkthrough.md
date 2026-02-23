## Page 1: Overview

![Overview](../images/overview-page.png)

### KPI Cards
- Total Shows
- Average Metascore / Userscore (which are suprisingly the exact)
- The typical score gap between users and critics (in absolute value )

### Key Visuals

- **Insight Cards**
    - **Most divisive shows**. These shows had the largest difference in rating between audience and critics.
        - The ones critics loved way more than the audience is "Saved by the Bell", and concversly the audience loved "Stalker" way more
    - **The Show both critics and users loved**. Here is where users and critics are agreed: "The Sopranos"
- **Matrix Visuals**. These show top 5 shows by users and by critics. For the user table for example, we also show the corresponing critic rating to see how much in agreement they are about the quality of the show.
- **Consensus.**The report user can also gain further insights into how in agreement critics and the audience is by varying the consensus threshold to see how many shows are rated to within, 3 points, for example by audience and critics.
- **Score Distribution**. With this visual we can see how scores are distributed for users vs ciritics. In particular here we see that there isn't that large a difference on the whole, with both sets of scores peaking in the 60-69 range.


### Slicer Panel

Over on the left we have a slicer panel which will allow further deep dives by genre and release year.
<table>
  <tr>
    <td><img src="../images/slicer-1.png" width="400"/></td>
    <td><img src="../images/slicer-2.png" width="400"/></td>
  </tr>
</table>
For example, selecting the **Comdey** genre filters the visuals on the page to show insights into comedy, for instance which show was the most divisve, which were top 5 for the audience and so on.

![Comedy](../images/overview-page-comedy-genre.png)
And in a similar vein, slicing by year and selecting year 2024 gives the following view:
![year](../images/overview-page-year-2024.png)
## Page 2: People & Companies

![People Page](../images/people-companies.png)
### Cards
Occupying the top row are 4 static cards giving statistics on the number of directors, actors, writers and production comppanies
### Entity Analysis


Consider the Director entity. The report user can gain insights into which directors have the highest rated shows by the critics and audience trhough the matrix visuals. Furthermore, because some directors have only one show and may be a "one trick pony" all told, a minimum number of shows paramater is introduced which allows the report viewer to determine the minimum number of shows the entity must have produced.

Farther down we have a bar chart to show the most prolific directors, for example. 

The report viewe can then switch entities by clicking the appropraite button to gain similar insights. 
We use **bookmarks** to switch between Directors, Actors, Creators, Companies.