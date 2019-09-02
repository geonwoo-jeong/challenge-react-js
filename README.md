# challenge-react-js

## Day 1

https://codesandbox.io/s/day-one-blueprint-c92k1

```
Complete the "ObjectUtilities" class with the following functions.

mergeObjects: Merge two objects. Return an object.
removePassword: Remove the 'password' key on an object. Return an object.
freezeObj: Freezes an object. Returns the frozen object.
getOnlyValues: Returns an array of all the values inside of an object.
getOnlyProperties: Returns an array of all the properties inside of an object.
Changing the 'name' of the 'frozenUser' SHOULD throw an error.

조건:

The output of the program must be EXACTLY like on the image above.
Place your functions INSIDE of 'ObjectUtilities'
DO NOT edit ANYTHING OUTSIDE of 'ObjectUtiliies'.
Don't give up!


IF ANY OF THE REQUIREMENTS ARE NOT FULFILLED YOU WILL GET AN ❌

힌트:

Use arrow functions
Use spread and rest operators
```

## Day 2

https://codesandbox.io/s/day-two-blueprint-9oocu

```
Complete the "ArrayUtilities" class with the following functions:

addZeros: Add zeros to all the numbers. Return an array of numbers.
moreThanFifty: Remove the numbers that are not more than 50. Return an array of numbers.
removeFirst: Remove the first element of the array. Return an array of numbers.
sumAll: Sum all the elements of the array. Return ONE number.
divide: Take a number and divide it into an array.


This is the desired output.

조건:

The output of the program must be EXACTLY like on the image above.
Place your functions INSIDE of 'ArrayUtilities'
DO NOT edit ANYTHING OUTSIDE of 'ArrayUtilities'.
Don't give up!


IF ANY OF THE REQUIREMENTS ARE NOT FULFILLED YOU WILL GET AN ❌



힌트:

Use arrow functions
Not everything is on the videos, research!
```

## Day 3

https://codesandbox.io/s/day-three-blueprint-px5zv

```
조건:

DO NOT create or delete ANY file.
DO NOT use <a></a>


IF ANY OF THE REQUIREMENTS ARE NOT FULFILLED YOU WILL GET AN ❌

```

## Day 4

https://codesandbox.io/s/day-four-boilerplate-3zsy9

```
조건:

Use 'styled-components' , 'styled-reset' and 'createGlobalStyle'
The header must be location aware and the links should reflect that.
DO NOT use ANY .css file or 'className' attribute.


IF ANY OF THE REQUIREMENTS ARE NOT FULFILLED YOU WILL GET AN ❌
```

## Day 5 ~ 6

https://codesandbox.io/s/day-five-blueprint-iimnw

```
Extend the Coin Explorer to call the following API endpoints on the following pages:

/ (Homepage) https://api.coinpaprika.com/v1/tickers
/exchanges https://api.coinpaprika.com/v1/exchanges
/coins https://api.coinpaprika.com/v1/coins


Homepage: Show the name of the coin, the symbol and price.
Exchanges: Show the name of the exchange, description and website link.
Coins: List the coins and sort them by rank.


Global Requirements:

Use Container/Presenter pattern with class components.
DO NOT use Hooks. I know they are awesome, we will use them later.
ALL PRESENTERS should use PropTypes.
Use PropTypes.shape
Use async/await
All AJAX requests MUST be made with an AXIOS INSTANCE ('axios.create')
Containers MUST NEVER call Axios directly, they should call the instance.
Use a Loader Component.


IF ANY OF THE REQUIREMENTS ARE NOT FULFILLED YOU WILL GET AN ❌

위의 조건을 수행하지 못하시면, 전체 출석하셔도 나중에 X 결격 처리 되실 수 있으니 참고하세요!
```

## Day 7 ~ 8
https://codesandbox.io/s/day-five-solution-fwm5w
```
Extend the Coin Explorer to create a detail view of each coin. You have to make the following URLs on your existing app.

/coins/{coin_id} https://api.coinpaprika.com/v1/coins/{coin_id}
/coins/{coin_id}/exchanges https://api.coinpaprika.com/v1/coins/{coin_id}/exchanges
/coins/{coin_id}/markets https://api.coinpaprika.com/v1/coins/{coin_id}/markets
Documentation: https://api.coinpaprika.com/?ref=public-apis#operation/getCoinById

Coin Markets & Coin Exchanges: These two ROUTES should be inside of the Coin Detail. 


Global Requirements:

Use Container/Presenter pattern with class components.
DO NOT use Hooks. I know they are awesome, we will use them later.
ALL PRESENTERS should use PropTypes.
Use PropTypes.shape
Use async/await
All AJAX requests MUST be made with an AXIOS INSTANCE ('axios.create')
Containers MUST NEVER call Axios directly, they should call the instance.
Use a Loader Component.
Coin Markets and Coin Exchanges should be ROUTES. 


IF ANY OF THE REQUIREMENTS ARE NOT FULFILLED YOU WILL GET AN ❌

```
