# puppeteer-heroku-buildpack

Installs dependencies needed in order to run puppeteer on heroku. Be sure to include `{ args: ['--no-sandbox', '--disable-setuid-sandbox'] }` in your call to `puppeteer.launch`

**This fork of the [CoffeAndCode puppeteer buildpack](https://github.com/CoffeeAndCode/puppeteer-heroku-buildpack)
adds support for Thai characters.**
