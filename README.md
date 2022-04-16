# mortgage_calculator
![alt text](https://github.com/Tetiana-25/mortgage_calculator/blob/main/img/banks_page.png)
![alt text](https://github.com/Tetiana-25/mortgage_calculator/blob/main/img/calculator_page.png)

<h2>Attention! This application works only in browser Google Chrome and Opera. WEB SQL is not supported in Mozilla Firefox</h2>
To start work with mortgage calculator, you need to clone this repository: <br>
<i>git clone https://github.com/Tetiana-25/mortgage_calculator</i> <br>
<br>
Then you need to open file <i>index.html</i> <br><br>
When you first time open this file, table in WEB SQL will created. And you need to comment line <i>createNewTableDB();</i> in the "script.js" file <br><br>

<h2>Change table name: </h2><br>
1) Open file <i>script.js</i>. <br>
2) Find function createNewTableDB(). <br>
3) Change <u>bank_4</u> on the value that you want. <br>
4) Every time when you change table name you need to change table name in th db.transaction function in <i>script.js</i> and <i> calc.js</i> files. <br><br>

<h2>Change DB name:</h2><br>
1) Open file <i>script.js</i>. <br>
2) Find const db = openDatabase('bank', '1.0', 'Test DB', 5 * 1024 * 1024). <br>
3) Change <u>'bank'</u> on the value that you want. <br>
4) Also you need to change this value in the <i>calc.js</i> file. <br><br>

<h2>Add new banks:</h2><br>
1) Open file <i>index.html</i><br>
2) Chick on the <b>+</b> symbol. <br>
3) New card with undefined field will be created. <br>
4) Click on the <i>edit</i> symbol on the card and change values.<br><br>

<h2>Delete bank:</h2><br>
1) Chick on the <b>x</b> symbol on the bank card. <br><br>

<h2>Edit data:</h2><br>
1) Click on the <i>edit</i> symbol on the card and change values.<br>
2) Click on the <i>Edit bank</i> button to save results.<br><br>

<h2>See the DB data:</h2><br>
1) In the browser click "F12" or "Fn+F12" button. <br>
2) In the navigation menu choose the "Application" menu item.<br>
3) Find WEB SQL at the Storage field and click on the name of DB. <br>
4) Choose table. <br>
Example:<br>
https://github.com/Tetiana-25/mortgage_calculator/blob/main/img/db_data.png <br><br>

<h2>Calculator page:</h2><br>
1) To calculate monthly mortgage payment you need to click on the "Go to the Mortgage calculator" button. <br>
2) Choose bank. <br>
3) Enter in the "Initial loan" and "Down payment" inputs your data. <br>
4) Click on the "Calculate" button to see the result. <br>
5) If you see ERROR messages, change your values to correct values and click on the "Calculate" button again. <br><br>
  
<h2>If you don't see DB data after adding banks or you don't see in the dropdown menu banks:</h2><br>
1) Restart the page. <br><br>



