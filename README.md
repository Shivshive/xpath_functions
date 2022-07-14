# xpath_functions

$x('//div[./div[@id="market_filter_coinInfo"]]/following-sibling::div//a[@data-bn-type="link"]/following-sibling::div[@data-area="right"]/div[number(substring(text(),2,4))>"0.01"]/text()').forEach(e=>{
    console.log(e)
})

https://www.binance.com/en/markets
