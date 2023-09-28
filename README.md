# Tights.no Webscraper/Discord Bot        
    
## Overview 
The Tights.no Webscraper/Discord Bot is a tool designed to monitor product prices on the Tights.no website and provide updates through Discord. 
This project combines web scraping capabilities with Discord integration to keep you informed about price changes for your favorite products.


## Features

Web Scraping: Utilizes Axios and Cheerio to extract product pricing information from specific URLs on Tights.no.

Automated Price Monitoring: A Node.js cron job regularly checks for price changes, ensuring you never miss a deal.

Discord Notifications: Integrates with Discord.js to send price updates directly to your Discord channel.

Configurable: Easily configure the URLs you want to monitor and the Discord channel to receive notifications.

Customizable Messages: Craft personalized messages for notifications based on price changes.

## Notes

Be aware that you have to setup .env file with you Discord Bot's token on your own and set which channel you wish the messages to be sent to

You also need to install all the dependencies needed using NPM (just install npm, then use "npm install" command) 

