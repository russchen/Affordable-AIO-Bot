**Donation:**
Feel free to buy me a cup of coffee, so I can stay motivated and keep updating this project.

[![PayPal](https://img.shields.io/badge/Donate-PayPal-green.svg)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=3WA5WTGP9HPYG)

#
Affordable AIO Bot, sneaker bot coded in VB.Net.
![Example](http://i.imgur.com/LH0fs05.png)
#
Status: **Under Development**

Description: Automated sneaker bot to get sneakers from different sites. Supports auto checkout, account, and proxy management.
#
**Completed List:**
1. Account Add Form
 - User can add normal accounts or guest accounts.
 - Fields: guest, email, password, size, site, link, keyword, checkout profile, notification e-mail, phone carrier, and notification number.
 
2. About Form
 - Descriptions about the bot.
 
3. Browser Form
 - Display the added item via browser. If user wants to see it.
 
4. Cart Form
 - Display currently carted items with time, product name, email, size, and site.
 
5. Checkout Add Form
 - User can add checkout profiles. Use for auto checkout.
 - Fields: profile name, first name, last name, address 1, address 2, zip code, city, US states, country, phone, email, card type, card number, expire date, and cvv.
 
6. Keyword Edit Form
 - User can edit account's keyword all at once.

7. Keyword Edit Selected Form
 - User can edit selected account's keyword.

8. Link Edit Form
 - User can edit account's link all at once.

9. Link Edit Selected Form
 - User can edit selected account's link.

10. Login Form
 - Authenticate users using backend server.
 - Check if user is banned. If so, displays the reason.
 - One license per computer, validated using HWID.
 - Added login attempt counter. After three failed login attempts, terminates the program.
 
11. Main Form
 - Main form where users can add, remove, edit, and clone accounts and checkout profiles.
 - Import and export accounts and checkout profiles.
 - Account and checkout profiles are seprated by tabs. Also has a log tab for logs.
 - Link to the Account Add Form, Cart Form, Checkout Add Form, Proxy Form, and Tips Form.
 - All updates are pushed using wyUpdate. Included a wyUpdate button to check for updates and to install it.
 - All files are saved and loaded to/from a .csv formated file for easy access/edit.
 - When program closes all current data will be autosaved onto the following file:
  - autosaveaccount.csv - account data
  - autosavecheckout.csv - checkout data
  - autosaveproxy.csv - proxy data
 - Added right click functions to remove, clone, import, export, remove all, and edit all for size, site, link, keyword.
 - Added account and checkout counter, so user can track how many account and checkout there are.
 
12. Maintenance Form
 - Check if the bot is currently under maintenance.
 
13. Proxy Form
 - User can paste proxies in here using following format: ip address:port OR ip address:port:username:password.
 - User can test proxy againt sites to see if the proxy is blocked/banned and check the ping.

14. Site Edit Form
 - User can edit account's site all at once.

15. Site Edit Selected Form
 - User can edit selected account's site.

16. Size Edit Form
 - User can edit account's size all at once.
 
17. Size Edit Selected Form
 - User can edit selected account's size.

18. Tips Form
 - User can see tips or any release information.
 - Tips are posted using backend server.
#
**To-Do List:**

- Finish GUI part.
- Add proxy test against sites to see if it is blocked/banned and display ping.
- Code add to cart functions.
- Make start and stop button work.
- Fix any bugs/errors.