# covid-data-ext
chrome extension to search covid-19 case data by country

![Alt Text](https://res.cloudinary.com/practicaldev/image/fetch/s--IrDwz8vh--/c_limit%2Cf_auto%2Cfl_progressive%2Cq_auto%2Cw_880/https://cdn-images-1.medium.com/max/800/0%2AXoNuKb0nTpObYNZ7)

learned how to make a basic chrome extension and integrate api calls using axios

# how to test it out:
1. go to `chrome://extensions/`
2. on the top right corner turn on `developer mode`
3. on the top left corner click `load unpacked`
4. select the directory where the `manifest.json` is stored (`hackviolet-chrome-ext`)
5. now when you make changes, click the reload button on the bottom of the hackviolet extension card
6. to see console logs, right-click extension icon and click `inspect popup`

# installation
`npm init -y`
`npm i axios --save`

# credits
followed a [tutorial by Adebola](https://dev.to/debosthefirst/how-to-build-a-chrome-extension-that-makes-api-calls-1g04)