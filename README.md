The file contains a dataset of 62 contentious cases before the International Court of Justice (ICJ) in which the ICJ: (a) rendered a final judgment on merits, and (b) imposed positive or negative obligation(s) capable of substantive compliance.

I record the follwing variables in the dataset: 

| Variable          | Description                                                                                                                                               |
| ----------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `Case`            | Name of the ICJ case or consolidated dispute                                                                                                              |
| `Party1`          | Applicant state, coded `1` for Global North and `0` for Global South                                                                                      |
| `Party2`          | Respondent state, coded `1` for Global North and `0` for Global South                                                                                     |
| `PowerDiff` | Difference between the party classifications: `Party1 - Party2`                                                                                           |
| `ModDiff` | Absolute value of `PowerDiff`; coded `1` where a power asymmetry was identified and `0` otherwise                                                   |
| `Compliance`      | Coded `1` where the judgment received timely and substantive compliance and `0` where compliance was absent, substantially delayed, partial, or contested |

The Global North–Global South classification is primarily based on the United Nations Conference on Trade and Development (UNCTAD) classification of developed and developing economies. In a limited number of cases, the classification was adjusted where the parties displayed an especially clear difference in economic, military, territorial, or geopolitical power that was not adequately captured by the UNCTAD framework.

The variable PowerDifference should therefore be understood as a rough proxy for conspicuous relative power asymmetry, rather than a precise qualitative label.

Additionally, in cases where a power asymmetry and non-compliance is noted, a separate  variable “Noncomply_Power” is coded to 1 where the “stronger” state (State having a power advantage) shows noncompliance, and to 0 where the “weaker” state shows noncompliance. In all cases except those which record no power symmetry and compliance, the variable “Territory_Geopolitcal_Rivalry” codes to 1 where the basis of the case is a territorial dispute or where the countries exhibit a well-established geopolitical rivalry, and codes to 0 otherwise.

Compliance was coded using publicly available materials, including ICJ documents, government statements, official press releases, academic research, and academic and media reports on post-judgment compliance. The standard adopted for the purposes of this dataset was that of _substantive_ and _timely_ compliance. The legal foundations and implications of this standard are discussed in the paper.



