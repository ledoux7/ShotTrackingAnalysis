# ShotTrackingAnalysis
Investigating selection bias in grading of shot type

## Regular Season 05/06
|**SHOT_ZONE**|**SHOT_TYPE**|**FGM**|**FGA**|**FG%**|**PPS**|
:--|:--|:--|:--|:--|:--|
|MR|Jump Shot|22608|59859|0.378|0.756|
|MR|Turnaround Jump Shot|1355|2487|0.545|1.09|
|MR|Fadeaway Jump Shot|1196|2009|0.595|1.191|
|MR|Running Jump Shot|535|934|0.573|1.146|
|MR|Jump Bank Shot|611|910|0.671|1.343|

&nbsp;

|**SHOT_ZONE**|**FGM**|**FGA**|**FG%**|**PPS**|
:--|:--|:--|:--|:--|
|MR|26627|66926|0.398|0.796|
|RA|37304|63017|0.592|1.184|
|ATB3|9752|27816|0.351|1.052|
|PAINT|10167|25107|0.405|0.81|
|LC3|2184|5668|0.385|1.156|
|RC3|2123|5409|0.392|1.176|
|BCOURT|9|371|0.024|0.073​|

Jump shots are close to 90% of all midrangers


## Regular Season 18/19
|**SHOT_ZONE**|**SHOT_TYPE**|**FGM**|**FGA**|**FG%**|**PPS**|
:--|:--|:--|:--|:--|:--|
|MR|Pullup Jump shot|5076|11791|0.43|0.861|
|MR|Jump Shot|3754|10363|0.362|0.729|
|MR|Step Back Jump shot|1504|3489|0.431|0.862|
|MR|Fadeaway Jump Shot|749|1916|0.391|0.782|
|MR|Turnaround Fadeaway shot|581|1374|0.423|0.846|
|MR|Turnaround Jump Shot|469|1261|0.372|0.744​|

&nbsp;

|**SHOT_ZONE**|**FGM**|**FGA**|**FG%**|**PPS**|
:--|:--|:--|:--|:--|
|RA|45574|72427|0.629|1.258|
|ATB3|21061|60285|0.349|1.048|
|PAINT|14177|35122|0.404|0.807|
|MR|13404|33275|0.403|0.807|
|LC3|3519|9112|0.386|1.159|
|RC3|3313|8771|0.378|1.133|
|BCOURT|14|466|0.03|0.09​|

Total mid-rangers are cut in half since 05/06 to now 33275 FGAs

## Player Breakdown
Difference between fadeaway and turnaround shots vs regular jump shot on mid-rangers

|**PLAYER_NAME**|**FGM**|**FGA**|**FG%**|**FG%_JS**|**FG%_DIFF**|**FGM_JS**|**FGA_JS**|
:--|:--|:--|:--|:--|:--|:--|:--|
|Dirk Nowitzki|101|164|0.616|0.439|0.177|260|592|
|Kobe Bryant|106|153|0.693|0.355|0.338|281|792|
|Kevin Garnett|72|131|0.55|0.451|0.099|215|477|
|Jason Richardson|58|112|0.518|0.296|0.222|80|270|
|Yao Ming|54|100|0.54|0.252|0.288|41|163|
|LeBron James|44|93|0.473|0.348|0.125|178|511|
|Carmelo Anthony|38|73|0.521|0.398|0.123|225|566|
|Elton Brand|53|73|0.726|0.417|0.309|221|530|
|Dwyane Wade|29|70|0.414|0.359|0.055|163|454|
|Chris Bosh|24|63|0.381|0.455|-0.074|212|466|
|Rasheed Wallace|36|61|0.59|0.387|0.203|111|287|
|Paul Pierce|39|61|0.639|0.411|0.228|182|443|
|Jerry Stackhouse|28|59|0.475|0.376|0.099|79|210|
|Vince Carter|29|59|0.492|0.386|0.106|139|360|
|Allen Iverson|45|54|0.833|0.351|0.482|235|669​|


&nbsp;


|**PLAYER_NAME**|**FGM**|**FGA**|**FG%**|**FG%_JS**|**FG%_DIFF**|**FGM_JS**|**FGA_JS**|
:--|:--|:--|:--|:--|:--|:--|:--|
|LaMarcus Aldridge|99|216|0.458|0.473|-0.015|114|241|
|Kevin Durant|89|153|0.582|0.432|0.15|54|125|
|DeMar DeRozan|45|121|0.372|0.451|-0.079|51|113|
|Dwyane Wade|37|112|0.33|0.167|0.163|5|30|
|Klay Thompson|49|96|0.51|0.325|0.185|49|151|
|Lou Williams|36|88|0.409|0.28|0.129|14|50|
|Kyrie Irving|47|86|0.547|0.48|0.067|24|50|
|LeBron James|30|78|0.385|0.541|-0.156|20|37|
|Kawhi Leonard|31|70|0.443|0.475|-0.032|28|59|
|Jayson Tatum|24|68|0.353|0.188|0.165|6|32|
|Khris Middleton|29|61|0.475|0.333|0.142|27|81​|

For the 05/06 season there seems to be some selection bias going on where made field goals are more likely to be graded as turnaround or fadeaway shots. For 18/19 there is a smaller sample size so it is harder to tell if there are some biases affecting grading.


## Grading of 3 pointers
3P FGA also includes pullup / step back.
|**PLAYER_NAME**|**SHOT_VALUE**|**SHOT_TYPE**|**FGM**|**FGA**|**FG%**|**FG%_3P**|**FG%_DIFF**|**FGA_3P**|
:--|:--|:--|:--|:--|:--|:--|:--|:--|
|Klay Thompson|3|Pullup Jump shot|44|72|0.611|0.402|0.209|599|
|Stephen Curry|3|Pullup Jump shot|88|140|0.629|0.437|0.192|810|
|Blake Griffin|3|Pullup Jump shot|42|101|0.416|0.362|0.054|522|
|D'Angelo Russell|3|Pullup Jump shot|80|194|0.412|0.369|0.043|635|
|Spencer Dinwiddie|3|Pullup Jump shot|40|107|0.374|0.335|0.039|370|
|Kevin Durant|3|Pullup Jump shot|32|82|0.39|0.353|0.037|388|
|Luka Doncic|3|Step Back Jump shot|60|166|0.361|0.327|0.034|514|
|Kemba Walker|3|Pullup Jump shot|92|238|0.387|0.356|0.031|731|
|Damian Lillard|3|Pullup Jump shot|114|287|0.397|0.369|0.028|643​|

Some players might actually be better at step backs or pullups than other types even though they are "harder" shots. Hard to tell if there is something going on due high volatility from 3 pointers and low sample sizes. Though Steph and Klay seems to have unreasonable high FG%.

