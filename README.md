unbury.us: loan calculator web application
=================================================

# About
[http://unbury.us](http://unbury.us)

*unbury.us* is a loan calculator designed to help you get debt-free as fast as possible. Once your loan information is entered, you may set the total amount you're able to put towards loans in a month. If this amount is greater than the minimum you're able to pay on loans, the extra money is put towards one loan every month to eliminate it. Once a loan is paid off, the money that was previously going towards that loan is now put towards the next loan, and so forth.

The order of which loans are paid off first is either highest-to-lowest interest rate (*Avalanche*), or lowest-to-highest remaining principal (*Snowball*), depending on which you choose.

Put just an extra $100 a month towards your loans and see how much time and interest paid you save!

*unbury.us* is a loan calculator forked by [Sean Freiburg](http://www.seanfreiburg.com) from unbury.me by Jordan Santell. Source code is licensed under the [MIT License](http://opensource.org/licenses/mit-license.php).

## Contribute

How to run locally:
Install [nodejs.org] (nodejs.org)

run following in node.js command prompt where package.json exists...

`npm install`

That command installs all the node packages for the app to run, however we still need the front end libraries which we get from bower:

`bower install`

You are now ready to run the app, in the app directory run the following:

`node app.js`

Then check link with favorite browser [http://localhost:3000/] (http://localhost:3000/)

