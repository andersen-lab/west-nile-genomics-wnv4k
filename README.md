#### Summary

By partnering with West Nile virus surveillance labs across the country, the [WestNile 4K Project](https://westnile4k.org/) is planning to sequence more than 4,000 virus genomes to reconstruct a high definition picture of West Nile virus spread and evolution during the last 20 years in the United States. The data that they generate will be immediately released and, along with other entomological data, will be used to uncover local transmission dynamics. As little progress has been made in effectively controlling West Nile virus outbreaks since its emergence, their goal is to use fine-scale transmission networks revealed through virus genomics to better design targeted control measures.

#### Collaborators

| Region                                                                   | Collaborators                                                                                                                                                                                                                                                                                                                                                                                                                             |
|--                                                                        |--                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| San Diego county, California                                             | Nikos Garfield and Saran Grewal from the [San Diego County Vector Control Program](https://www.sandiegocounty.gov/deh/pests/vector_disease.html)                                                                                                                                                                                                                                                                                          |
| All the other counties in California, including Sacramento-Yolo and Kern | Ying Fang and Chris Barker from the [Barker Lab, University of California, Davis](https://barkerlab.ucdavis.edu/) and Sarah Wheeler from [Sacramento-Yolo Mosquito and Vector Control Program](https://www.fightthebite.net/).                                                                                                                                                                                                            |
| Iowa, Idaho, and the US Virgin Islands                                   | [Washington Animal Disease Diagnostic Laboratory (WADDL)](https://waddl.vetmed.wsu.edu/)                                                                                                                                                                                                                                                                                                                                                  |
| Oregon                                                                   | [Oregon Veterinary Diagnostic Laboratory](https://vetmed.oregonstate.edu/diagnostic)                                                                                                                                                                                                                                                                                                                                                      |
| Washington                                                               | [Krisztian Magori](https://sites.ewu.edu/diseaseecology/krisztian-magori-phd/) from the Eastern Washington University, Amy Salamone, Wayne Clifford, David Kangiser from the [Washington State Department of Health](https://www.doh.wa.gov/), the [Washington Animal Disease Diagnostic Laboratory (WADDL)](https://waddl.vetmed.wsu.edu/), and the [Oregon Veterinary Diagnostic Laboratory](https://vetmed.oregonstate.edu/diagnostic) |
| New Hampshire                                                            | Denise Bolton, Abigail Mathewson, Carolyn Fredett, Amy Kutschke and Rebecca Lovell at the [New Hampshire Division of Public Health Services, Department of Health and Human Services](https://www.dhhs.nh.gov/)                                                                                                                                                                                                                           |
| Louisiana                                                                | Udeni Balasuriya, Rebecca Christofferson, Tarra Harden, Zelalem Mekuria, Laura Peak, Alma Roy, and Keith Strother from the [Louisiana Animal Disease Diagnostic Laboratory](https://www.lsu.edu/vetmed/laddl/) at Louisiana State University                                                                                                                                                                                              |
| Minnesota                                                                | David Neitzel from the [Minnesota Department of Health](https://www.health.state.mn.us/index.html)                                                                                                                                                                                                                                                                                                                                        |

#### Raw Data

The BAM files are available on [Google Cloud](https://console.cloud.google.com/storage/browser/andersen-lab_project_westnile4k_genomics).

The sequencing is being performed using an amplicon-based sequencing scheme using [PrimalSeq](https://www.nature.com/articles/nprot.2017.066). Our full protocol is available online [here](https://docs.google.com/document/d/1PilT4w5jHO-ROsE8TL5WBGa0wSCdTHAsNl1LIOYiTgk/edit?usp=sharing). Sequencing data is aligned using [bwa](https://github.com/lh3/bwa) and processed using [iVar](https://github.com/andersen-lab/ivar) ([Grubaguh et al. Genome Biology 2019](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-018-1618-7)).

Below is a table showing the number of sequenced genomes by state.

| State | Count |
|:------|:------|
| CA    | 740   |
| IA    | 1     |
| ID    | 2     |
| IL    | 26    |
| LA    | 46    |
| MN    | 85    |
| NH    | 41    |
| OH    | 27    |
| OR    | 10    |
| WA    | 7     |
| Other | 1     |
| Total | 986   |


**Disclaimer**. Please note that this data is released as work in progress by the WestNile 4K Project and should be considered preliminary. If you intend to include any of these data in publications, please let us know – otherwise please feel free to download and use without restrictions. We have shared this data with the hope that people will download and use it, as well as scrutinize it so we can improve our methods and analyses. Please contact us if you have any questions or comments.

---
**Andersen Lab**  
The Scripps Research Institute  
La Jolla, CA, USA  
[data@andersen-lab.com](mailto:data@andersen-lab.com)
