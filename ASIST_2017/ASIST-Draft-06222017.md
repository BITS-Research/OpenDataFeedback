# Integrating User Feedback with Open Data Quality Models

## Abstract
User feedback is critical to improving the quality of open data. However, informal methods of collecting user feedback make it difficult to translate reported issues into formal design requirements. Drawing on  user comments collected from Data.Gov - an open data portal providing access to thousands of datasets published by city, state, and federal government agencies in the USA – we inductively develop a classification of reported data quality issues. This poster presents preliminary findings from applying this coding scheme to all issues that users filed on Data.gov in 2015 and 2016.

## Introduction 
Over the last decade open data initiatives have demonstrably increased access to public sector information (Davies, 2010); are shown to correlate strongly with more efficient and impactful basic science research (Piwowar and Vision, 2013); and, can act as a driver of private sector innovation in critical areas of our economy such as healthcare and renewable energy (Chan, 2013). Yet, many previous studies have shown that open data remains difficult for lay users to discover (Martin et al., 2013), access (Janssen et al., 2012), and use (Braunschweig et al, 2012). Some barriers to the meaningful use of open data include poor metadata quality (Neumaier et al. 2016), insufficient provenance information (Umbirch et al. 2015), and the organization of data portals that are supposed to match data producers with data consumers (Thorsby et al., 2017). Collectively, these barriers to use have been described as a function of the overall quality of open data (Martin, Rosario, & Perez, 2016). 

The goal of our on-going research is to better understand how to communicate a relative notion like quality to potential open data consumers. We believe that by avoiding rigid definitions of quality, and instead focusing on descriptive features will allow users to make better judgements about a dataset's fitness for given purpose. The preliminary work described in this poster is focused on creating an empirically informed model of user feedback, and in particular users of the Data.Gov site. Formally stated our research question asks : What do users report as 'issues' related to the use of open data available on Data.gov? And, how can this informal feedback be best categorized to improve requirements engineering for data portals, in particular Data.gov?

## Research Design
Users of data.gov can provide feedback about a particular dataset in a number of ways - through email, social media, or directly on the data.gov website. The latter option includes a button prominently placed at the top of each dataset that reads "Report Data Issue". All reported data issues are then published by data.gov for public viewing.

## Data
Using the RVest package from R, we scraped all data issues that were reported to data.gov from January 01, 2015 - December 31, 2016 (n = 956). For each issue, we collected the date the issue was reported, the status of the issue (open or closed), and a user's free-text response to the "issue" prompt.

## Inductive Coding
The two authors met and discussed themes that were reported in the free text of user issues. We developed an initial coding scheme to classify each issue, selected a subset of issues from our scraped data (n = 50), and separately coded the subset of issues. We then compared the applied codes for each issue, and revised our coding scheme. A new subset was selected (n = 50) and coded separately. For the second round of coding we calculated a kappa score (Carletta, 1996) to measure inter-coder agreement.  

We discussed discrepencies in our codes.
A selected a third subset (n=50)
'
We achieved a kappa score of ..

We then evenly split all remaining issues and coded

## Preliminary Results


## Discussion and Future Work

## Acknowledgments
This work is funded in part by the IMLS Grant [Removed for review purposes]. A openly accessible repository with the software, data, and coding scheme described in this paper is available at https://github.com/OpenDataLiteracy/Feedback

## Works Cited

Braunschweig, K., Eberius, J., Thiele, M., & Lehner, W. (2012). The state of open data. WWW2012, Lyon, France: ACM.

Carletta, J. (1996). Assessing agreement on classification tasks: the kappa statistic. Computational linguistics, 22(2), 249-254.

Chan, T.-C., Teng, Y.-C., Kuo, C., Yeh, Y.-H., & Lin, B.-C. (2017). Leveraging the Niche of Open Data for Disease Surveillance and Health Education. Online Journal of Public Health Informatics, 9(1).

Chen, Y., Wen, C.-Y., Chen, H.-P., Lin, Y.-H., & Sum, H.-C. (2011). Metrics for Metadata Quality Assurance and Their Implications for Digital Libraries. In ICADL (Vol. 7008, pp. 138–147). Springer.

Davies, T. (2010). Open data, democracy and public sector reform. A Look at Open Government Data Use from Data.Gov.Uk. (Dissertation)

Janssen, M., Charalabidis, Y., & Zuiderwijk, A. (2012). Benefits, adoption barriers and myths of open data and open government. Information systems management, 29(4), 258-268.

Martin, S., Foulonneau, M., Turki, S., & Ihadjadene, M. (2013, June). Open data: Barriers, risks and opportunities. In Proceedings of the 13th European Conference on eGovernment: ECEG (pp. 301-309).

Neumaier, S., Umbrich, J., & Polleres, A. (2016). Automated quality assessment of metadata across open data portals. Journal of Data and Information Quality (JDIQ), 8(1), 2.

Piwowar, H. A., & Vision, T. J. (2013). Data reuse and the open data citation advantage. PeerJ, 1, e175.

Thorsby, J., Stowers, G. N., Wolslegel, K., & Tumbuan, E. (2016). Understanding the content and features of open data portals in American cities. Government Information Quarterly.

Umbrich, J., Neumaier, S., & Polleres, A. (2015, March). Towards assessing the quality evolution of open data portals. In Proceedings of ODQ2015: Open Data Quality: from Theory to Practice Workshop, Munich, Germany.
