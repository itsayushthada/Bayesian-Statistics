| Attribute     | Discription   | Levels | Encoding | 
| :------------- |:-------------:|:------:|---------:|
| season | Season in which the analysis was performed | Winter, Spring, Summer, Fall | {-1, -0.33, 0.33, 1} |
| age | Age at the time of analysis | [18-36] | [0, 1] |
| childhood_disease | Childish diseases (like chicken pox, measles, mumps, polio) | Yes or No | {1, 0} |
| trauma | Accident or Serious Trauma | Yes or No | {1, 0} |
| surgeries | Surgical Intervention | Yes or No | {1, 0} |
| high_fever | High fevers in the last year | < 3 month before, > 3 month ago, No | {-1, 0, 1} |
| alcoholic | Frequency of alcohol consumption | Several times a Day, Everyday, Several times a Week, Once a week, Hardly ever or Never | {0.2, 0.4, 0.6, 0.8, 1.0} |
| smoking | Smoking habit | Never, Occasional, Daily | {-1, 0, 1} |
| sitting | Number of hours spent sitting per day ene-16 | (0, 16] | (0, 1] |
| diag_result | Result of Diagnosis | Normal, Altered | {N, O} |

**{a, b}** => Represents discrete levels. <br>
**[a, b]** => Represents closed continuous range between a and b. <br>
**(a, b]** => Represents half open continuous range between a and b where a is not included. <br>
