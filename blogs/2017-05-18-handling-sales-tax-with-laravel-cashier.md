---
title: "Handling Sales Tax with Laravel Cashier"
url: "https://developers.taxjar.com/blog/handling-sales-tax-with-laravel-cashier/"
date: "2017-05-18"
author: "Jake Johnson"
feed_url: "https://developers.taxjar.com/blog/feed.xml"
---
Getting Started First you’ll want to install the taxjar/taxjar-php package via Composer using the following command: composer require taxjar/taxjar-php TaxJar API Token You’ll also need a way to authenticate with our sales tax API to request rates. Sign up for a TaxJar account to generate a new API token. From there, copy and paste the API token into your project’s .env file: TAXJAR_API_TOKEN=[Your API Token] Now you can securely reference that token anywhere in your app using env('TAXJAR_API_TOKEN') .
