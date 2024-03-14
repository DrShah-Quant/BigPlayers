<h1>PeriodBigPlayers</h1>



<h2>Description</h2>
This Python program analyzes stock market tick data and visualizes transactions and volumes to help traders identify potential signs of large order activity (potentialy by big players) over time.
<br />


<h2>Languages and Libraries Used</h2>

- <b>Python</b> 
- <b>Matplotlib</b>
- <b>NumPy</b>
- <b>CSV</b>

<h2>Environments Used </h2>

- <b>Windows 10 Pro</b>
- <b>Jupyter Notebook</b>

<h2>Program walk-through:</h2>

<p align="justify"> The example run presented here is from a Jupyter Notebook environment. You can run the file using Ctrl+Enter key presses. Alternatively you can run the python script <i>BigPlayers.py</i> using command <i>python BigPlayers.py</i> in a command line if you have python installed properly. The program is depended on a CSV file containing stock transactions raw data. In the example presented below, I have used raw data provided by M+ Securities, a Malaysian stock broker. The raw data contains comma separated values organized into the following colums: "Time","Type","Price","Chg","Vol","Value". "Time" is the time when the transaction occured. "Type" refers to the type of transaction such as buy, close, and open. "Price" refers to the price the share was transacted. "Chg" refers to the difference from the previous price. "Vol" refers to the transaction volume measured in lot sizes (1 lot = 100 shares). And finally "Value" refers to the value of the trasaction (i.e. no of shares x share price). </p>

<p align="center">
Sample CSV raw data : <br/>
<img src="https://i.imgur.com/ZwC3mJi.png" height="80%" width="80%" />
<br />
 <br/>
Launch the Program and enter CSV data file location : <br/>
<img src="https://i.imgur.com/3K3XUKj.png" height="80%" width="80%"/>
<br />
<br />
Legend:  <br/>
<img src="https://i.imgur.com/8ZBA08y.png" height="80%" width="80%" />
<br />
 <p align="justify">The legend lists the percentile rank achieved by buy and sell transactions at the 80th percentile for the whole of the period in consideration (i.e. the CVS dataset date range). In the example, top 20% (i.e. above percentile 80) buy volumes are all over 200 lots (percentile rank = 200) and top 20% sell volumes are all over 100 lots. </p>

<br />
Above 80 percentile buy/sell volume transactions: <br/>
<img src="https://i.imgur.com/TIr6qgZ.png" height="80%" width="80%" />
<br />
 <p align="justify"> The figure above shows periodic time series illustrating the top 20% volume transactions. Assuming big players (e.g. fund managers, high net worth individuals, etc) transact in large quantities, from this figure we can know at what price and when the transactions occur. The percentile rank (as found in the legend) indicates us on the reliability of our assumption -- it is more reliable if the percentile rank is above the average of a longer period.   </p>
<br />
Number of buy and sell transactions with volume per buy (or sell) transaction:  <br/>
<img src="https://i.imgur.com/aC50fWJ.png" height="80%" width="80%" />
<br />
 <p align="justify"> The figure above is a time series depicting the volume of buy (or sell) transactions at each price level across the time domain. The visualization highlights the price level that attracts the most buying or selling activity. Corresponding to this information, we are also presented with volume per buy(or sell) transaction at each price level to enable us analyse the magnitude of interest at each price level.    </p>
<br />

</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
