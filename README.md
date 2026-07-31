The file contains a dataset of 62 contentious cases before the International Court of Justice (ICJ) in which the ICJ: (a) rendered a final judgment on merits, and (b) imposed positive or negative obligation(s) capable of substantive compliance.

I record the follwing variables in the dataset: 

| Variable          | Description                                                                                                                                               |
| ----------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `Case`            | Name of the ICJ case or consolidated dispute                                                                                                              |
| `Party1`          | Applicant state, coded `1` for Global North and `0` for Global South                                                                                      |
| `Party2`          | Respondent state, coded `1` for Global North and `0` for Global South                                                                                     |
| `SignedPowerDiff` | Difference between the party classifications: `Party1 - Party2`                                                                                           |
| `PowerDifference` | Absolute value of `SignedPowerDiff`; coded `1` where a power asymmetry was identified and `0` otherwise                                                   |
| `Compliance`      | Coded `1` where the judgment received timely and substantive compliance and `0` where compliance was absent, substantially delayed, partial, or contested |

The Global North–Global South classification is primarily based on the United Nations Conference on Trade and Development (UNCTAD) classification of developed and developing economies. In a limited number of cases, the classification was adjusted where the parties displayed an especially clear difference in economic, military, territorial, or geopolitical power that was not adequately captured by the UNCTAD framework. The paper associated with the dataset discusses the theoretical issues pertaining to the classification of states on the basis of "power".
The variable PowerDifference should therefore be understood as a rough proxy for conspicuous relative power asymmetry, rather than a precise qualitative label.
