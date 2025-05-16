#🌍 Currency Converter Web App

This is a simple currency converter web application that lets users convert one currency to another using real-time exchange rates. It has a clean UI, auto-loads country flags and currency codes, and uses an external API to fetch the latest rates.



#🚀 Features
✅ Real-time conversion between any two currencies

✅ Dropdowns auto-filled with currency codes

✅ Country flags shown for selected currencies

✅ Default: USD to INR conversion on page load

✅ User input validation for amount

✅ Built using only vanilla JavaScript (no frameworks)



#🛠️ Technologies Used
Technology	Purpose:-
HTML:	Structure and layout of the web page
CSS:	Styling and design
JavaScript:	App logic, event handling, API calls
Currency API:	Fetches live exchange rates from https://github.com/fawazahmed0/currency-api
Flags API:	Displays flags of selected currencies from https://flagsapi.com


#🔍 How It Works:-
When the page loads, the app:
Fills both dropdowns with currency codes (like USD, INR, EUR, etc.)
Sets default values to USD and INR
Shows the exchange rate from USD to INR


#When the user:
Changes a currency → the flag image updates
Enters an amount and clicks convert → the app fetches live exchange rate and shows the result
Exchange rates are pulled from an open-source API (no key required).



#📂 Project Files
index.html – HTML structure

style.css – Styling for UI

app.js – All functionality: dropdowns, flag updates, API fetch

codes.js – Contains currency-to-country mapping



📌 Example Output

1 USD = 83.22 INR
