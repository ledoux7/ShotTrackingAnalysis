# Shot Type Grading Analysis

Inspired by threads on here on grading of shot type showing weird numbers like Kobe's turnaround fadeaways or Steph's pullup 3s.

https://www.reddit.com/r/nba/comments/clj8yc/mamba_mentality_prime_kobe_bryant_20012013_shot/

https://www.reddit.com/r/nba/comments/bwodpq/oc_wardell_currys_shot_chart_on_pullup_jumpers/

So I'm investigating possible selection bias in grading of shot type. Used 3 year spans.

## Regular Season 04/05 to 06/07

|**SHOT_ZONE**|**SHOT_TYPE**|**FGM**|**FGA**|**FG%**|**PPS**|
:--|:--|:--|:--|:--|:--|
|MR|Jump Shot|68177|180649|0.377|0.755|
|MR|Turnaround Jump Shot|3888|7357|0.528|1.057|
|MR|Fadeaway Jump Shot|3295|5612|0.587|1.174|
|MR|Jump Bank Shot|2082|3170|0.657|1.314|
|MR|Running Jump Shot|1618|2884|0.561|1.122|
|MR|Hook Shot|393|1128|0.348|0.697|
|MR|Jump Hook Shot|257|493|0.521|1.043|
|MR|Turnaround Hook Shot|132|261|0.506|1.011​|


&nbsp;

|**SHOT_ZONE**|**FGM**|**FGA**|**FG%**|**PPS**|
:--|:--|:--|:--|:--|
|MR|79935|201719|0.396|0.793|
|RA|112985|190672|0.593|1.185|
|ATB3|29736|84800|0.351|1.052|
|PAINT|30824|76078|0.405|0.81|
|LC3|6694|17505|0.382|1.147|
|RC3|6265|16128|0.388|1.164|
|BCOURT|22|1110|0.02|0.059​|


Jump shots are close to 90% of all midrangers.


## Regular Season 16/17 to 18/19

|**SHOT_ZONE**|**SHOT_TYPE**|**FGM**|**FGA**|**FG%**|**PPS**|
:--|:--|:--|:--|:--|:--|
|MR|Jump Shot|18726|53466|0.35|0.702|
|MR|Pullup Jump shot|15254|33177|0.46|0.92|
|MR|Step Back Jump shot|4332|9688|0.447|0.895|
|MR|Fadeaway Jump Shot|2318|5676|0.408|0.817|
|MR|Turnaround Jump Shot|1724|4369|0.395|0.789|
|MR|Turnaround Fadeaway shot|1713|3844|0.446|0.891|
|MR|Floating Jump shot|898|2289|0.392|0.785|
|MR|Driving Floating Jump Shot|769|1893|0.406|0.812|
|MR|Jump Bank Shot|530|1112|0.477|0.953​|


&nbsp;

|**SHOT_ZONE**|**FGM**|**FGA**|**FG%**|**PPS**|
:--|:--|:--|:--|:--|
|RA|128875|206591|0.624|1.248|
|ATB3|58290|165477|0.352|1.057|
|MR|48422|120186|0.403|0.806|
|PAINT|39831|98188|0.406|0.811|
|LC3|9754|25312|0.385|1.156|
|RC3|9286|23851|0.389|1.168|
|BCOURT|29|1489|0.019|0.058​|

There are more shot types in the later dataset. Now jump shots are close to 44% of all midrangers. And total midrangers have gone from 206591 to 120186.



## Player Breakdown
Difference between fadeaway and turnaround shots vs regular jump shot on midrangers

|**PLAYER_NAME**|**FGM**|**FGA**|**FG%**|**FG%_JS**|**FG%_DIFF**|**FGM_JS**|**FGA_JS**|
:--|:--|:--|:--|:--|:--|:--|:--|
|Kevin Garnett|242|421|0.575|0.414|0.161|624|1507|
|Dirk Nowitzki|236|385|0.613|0.43|0.183|811|1884|
|Yao Ming|189|338|0.559|0.308|0.251|130|422|
|Kobe Bryant|204|305|0.669|0.347|0.322|600|1729|
|LeBron James|115|241|0.477|0.335|0.142|497|1483|
|Jason Richardson|111|238|0.466|0.317|0.149|231|729|
|Vince Carter|117|228|0.513|0.383|0.13|442|1155|
|Rasheed Wallace|122|226|0.54|0.37|0.17|298|805|
|Tracy McGrady|107|211|0.507|0.409|0.098|685|1675​|



&nbsp;


|**PLAYER_NAME**|**FGM**|**FGA**|**FG%**|**FG%_JS**|**FG%_DIFF**|**FGM_JS**|**FGA_JS**|
:--|:--|:--|:--|:--|:--|:--|:--|
|LaMarcus Aldridge|263|599|0.439|0.426|0.013|362|849|
|DeMar DeRozan|152|364|0.418|0.344|0.074|162|471|
|Dwyane Wade|112|288|0.389|0.249|0.14|69|277|
|Kevin Durant|158|280|0.564|0.403|0.161|160|397|
|LeBron James|113|273|0.414|0.367|0.047|87|237|
|Andrew Wiggins|104|267|0.39|0.271|0.119|107|395|
|Dirk Nowitzki|92|223|0.413|0.454|-0.041|248|546|
|Marc Gasol|96|221|0.434|0.434|0|247|569|
|Klay Thompson|111|206|0.539|0.38|0.159|217|571|
|Harrison Barnes|90|200|0.45|0.366|0.084|164|448​|


For the earlier seasons there seems to be some selection bias going on where made field goals are more likely to be graded as turnaround or fadeaway shots.


## Grading of 3 pointers

3P FGA also includes pullup / step back.

|**PLAYER_NAME**|**SHOT_VALUE**|**SHOT_TYPE**|**FGM**|**FGA**|**FG%**|**FG%_3P**|**FG%_DIFF**|**FGA_3P**|
:--|:--|:--|:--|:--|:--|:--|:--|:--|
|Andre Iguodala|3|Pullup Jump shot|48|75|0.64|0.331|0.309|438|
|Draymond Green|3|Pullup Jump shot|60|106|0.566|0.3|0.266|684|
|Quinn Cook|3|Pullup Jump shot|50|78|0.641|0.418|0.223|330|
|Klay Thompson|3|Pullup Jump shot|153|242|0.632|0.418|0.214|1766|
|Stephen Curry|3|Pullup Jump shot|212|341|0.622|0.424|0.198|2099|
|Stephen Curry|3|Step Back Jump shot|96|159|0.604|0.424|0.18|2099|
|Austin Rivers|3|Pullup Jump shot|41|82|0.5|0.357|0.143|984|
|Wesley Matthews|3|Step Back Jump shot|44|87|0.506|0.371|0.135|1284|
|Kevin Durant|3|Pullup Jump shot|127|250|0.508|0.384|0.124|1113|
|Lou Williams|3|Pullup Jump shot|78|162|0.481|0.362|0.119|1254|
|Isaiah Thomas|3|Pullup Jump shot|78|171|0.456|0.356|0.1|877|
|Tobias Harris|3|Pullup Jump shot|38|78|0.487|0.389|0.098|1151|
|LeBron James|3|Step Back Jump shot|56|123|0.455|0.358|0.097|1074​|



Warriros have good shooters, but there seems to be something going on here. Hard to tell if there is something going elsewhere due too high volatility on 3 pointers. Worth metioning that some players might actually be better at step backs or pullups than other types even though they are "harder" shots. 

