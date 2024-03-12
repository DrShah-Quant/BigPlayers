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
Launch the Program and enter CSV data file location : <br/>
<img src="https://i.imgur.com/3K3XUKj.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Select the disk:  <br/>
<img src="https://i.imgur.com/tcTyMUE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Enter the number of passes: <br/>
<img src="https://i.imgur.com/nCIbXbg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Confirm your selection:  <br/>
<img src="https://i.imgur.com/cdFHBiU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Wait for process to complete (may take some time):  <br/>
<img src="https://i.imgur.com/JL945Ga.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Sanitization complete:  <br/>
<img src="https://i.imgur.com/K71yaM2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Observe the wiped disk:  <br/>
<img src="https://i.imgur.com/AeZkvFQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
