Hello All,

I have created a tool for Indian Crypto lovers who love to trade

## What does this tool do? 
- It alerts trader when his/her set price (Track Price) for selected Cryptocurrency reaches to latest buy price at the moment.

## How does it alert?
- It makes a beep sound (like an alarm) when the set price is lower or higher than the current buy price of the selected cryptocurrency

## Why we need this tool?
>I observed that we mostly miss the moment when our desired crypto reaches some price where we wanted to trade(buy or sell) it. --> In that case this tool beeps like an alarm and alerts a trader to pay attention to it and do trading (as we can't sit in front of the exchange console all time)

## How to use it?
- Download Tracker.exe on your computer (it totally safe and do not ask for any login details as its just a monitoring tool that works on the public API of WazirX/Binance)
- In Exchange dropdown, select the exchange from which you want to fetch rate and create tracker alert
- In coin name dropdown select your crypto or you can write its name, it will display matching results 
- You can get the latest Buy/Sell Price of that crypto using the Get Price button (it's just to get the latest rate, nothing to do with creating an alert tracker) 
- Now Enter the value (you track price) in the Track Price textbox 
- Enter refresh time interval, which indicates fetching new price in specific seconds
- Select radion button High or Low (if you select High, then when crypto's buy rate exceeds your track price it will alert and vice-versa) 
- Click on Create Tracker button to start the monitoring process in the background 
- A tracking job will be created in below box (Current Running Trackers) 
- When track price is High/Low than current crypto's buy price, your computer will make a beep sound alerting you about the current market situation of your selected Crypto 
- To stop the alert, select that tracker job from (Current Running Trackers) window and click Stop Tracker button, the job will be removed and beep sound will stop

- To stop all all alarming tracker click on Clear Alerted button
- In case if user want to stop all Tracker, click Stop All button

## ::Note::
- No malware or virus, just a tool written using Powershell Form and powershell language 
- Do not press Get Rate button too repeatadly, it will freeze as it will be fetching data and process 
- Only works on Windows (Tested on Windows 10)
- Refresh value should be integer only and suggested to use 10, otherwise exchange will treat the requests as attack and block your IP for geting new values


## ::Screenshots::


![UI](Tracker.Png)
