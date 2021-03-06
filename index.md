## Amazon Relay Auto-Booker Chrome Extension Help Page 

### Content
- [About the extension](\#about-the-extension)
- [Requirements](\#requirements)
- [How to install](\#how-to-install)
- [How to use](\#requirements)
- [Possible issues](\#possible-problems-and-solutions)
- [Contact](\#contact)

### About the extension

Amazon Relay Auto-Booker Extension is developed by experienced developers to help you to book amazon relay loads.

### Requirements

1. Must have [Google Chrome](https://www.google.com/chrome/) web browser installed
2. Must have an access to [Amazon Relay](https://www.relay.amazon.com)

### How to install
1. Open Chrome web browser and navigate to [Google Webstore](https://chrome.google.com/webstore/detail/amazon-relay-auto-refresh/gooaddljkpdcjbdigogmajlcgifjjhgp)
2. Click on **Buy** button (If you do not see **Buy** button, you should change the account [location](\#possible-problems-and-solutions))

![Image](./screenshots/extension_webstore.png)

### How to use extension

1. Open Google Chrome web browser.
2. Navigate to [Amazon Relay](https://www.relay.amazon.com) website and login.
![Image](./screenshots/dashboard.png)
3. Click on **Load Board** Link on left navigation area
![Image](./screenshots/loadboard.png)
4. Setup Filters
![Image](./screenshots/filters.png)
5. Click on extension icon on browser right top corner
![Image](./screenshots/extension_clear.png)
6. By default refresh rate is determined by app, but if you want to set your own value, toggle **Refresh Rate** and enter the number of refreshes per second
![Image](./screenshots/extension_refresh_rate.png)
7. If you want to get notified on a load with less than specific number of stops, then turn on **Max Stops** toggle and enter the number of maximum stops
![Image](./screenshots/extension_max_stops.png)
8. If you want to any new load to be booked automatically, then turn on **Autobook** toggle, but be careful, this option will book any load that matches filter criteria, so you want to make sure you <b style="color: red">setup filters first</b>.
![Image](./screenshots/extension_autobook_only.png)
9. If you want extension to book any new load that matches your filter criteria and has less than or equal defined number of max stops, then turn on both toggles and specify maximum number of stops.
![Image](./screenshots/extension_both.png)
10. To start the task, click on **Start** button
![Image](./screenshots/extension_started.png)
11. If you want to cancel, click on **Stop** button
12. Depending on how you setup the extension parameters, when a new load becomes available in load board, extension either marks it:
![Image](./screenshots/marked_load.png)
or books it by clicking on book and accept buttons. Extension notifies you with sound as well.
![Image](./screenshots/booked_trip.png)

### Possible problems and solutions
#### Problem:
Unable to download the extension
#### Solution:
Extension is not available in some countries, in order to download from one of those countries, you should change location of your account.

1. Find gear button by your account name and click on it:
![Image](./screenshots/webstore_gear.png)
2. Select **United States** from the list of countries

![Image](./screenshots/webstore_countries.png)
#### Problem:
Extension icon is grayed out
#### Solution:
Extension is active only on amazon relay load board, please navigate to [Load Board](https://relay.amazon.com/tours/loadboard?)

#### Problem:
Loading spinner is not going away on load board when I manually set refresh rate.
#### Solution:
When refresh rate is too high, relay might log you out, we recommend to keep refresh rate on auto or set it to lower rates.

### Contact
Thank you for using Amazon Relay Autobooker Extension!
If you have any suggestions, questions or comments, please feel free to [contact us](mailto:castusoft@gmail.com)
