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

## Day 9 ~ 10
https://codesandbox.io/s/day-seven-blueprint-iw9fr

```
You will have to create the following hooks and use them all in one page:

useDeviceOrientation
useFavicon
useGeolocation
useKeyPress
useLocalStorage
useMousePosition
useOnline
useLockScroll

Here is the desired output:

useDeviceOrientation:

Takes no arguments, returns an object containing "alpha, beta, gamma".

useFavicon:

Takes the initial favicon URL as argument, returns 'setFavicon' that changes the favicon.

useGeolocation:

Take no arguments, returns an object containing 'error, coords: {lat:long}'

useKeyPress

Takes one argument, a key, returns a boolean that becomes 'true' or 'false' if the key is pressed

useLocalStorage

Takes two arguments, the name of the localStorage key, and the initialValue to give to it.

Returns an array where the first item is the current element in localStorage and the second item is a function to update localStorage

useMousePosition:

Takes no arguments, returns the x,y coordinates of the mouse.

useOnline:

Takes no arguments, returns a boolean that changes when the user goes online or offline.

useLockScroll:

Takes no arguments, returns an array with two elements.

The first element notifies 'true' or 'false' if the scroll is locked, the second element is an object containing two functions, one to lock scroll, one to unlock it.

Requirements:

Don't you dare give up! 
Make a page that uses all the hooks, like the one on the video.

IF ANY OF THE REQUIREMENTS ARE NOT FULFILLED YOU WILL GET AN ❌

```

## Day 11

https://codesandbox.io/s/day-six-solution-myfok

```
Take the boilerplate and turn refactor it to use hooks 100%

Requirements:
Don't use Class Components.
Use only hooks.
No Container/Presenter.
All functionality should remain the same.
```

## Day 12

https://codesandbox.io/s/day-seven-blueprint-7n8cn
```
Using everything that you know, create a page that calls an API with infinite scrolling.
It should behave like this:

API Documentation: https://yts.lt/api#list_movies

Clues:
﻿This is how I would make the API file.
The URL would end up looking something like this:
https://yts.lt/api/v2/list_movies.json?page=1&limit=50

Requirements:
Don't use Class Components.
Use only hooks.
When the user reaches the end of the page, request more movies (other page)
No Container/Presenter.
All functionality should remain the same.

IF ANY OF THE REQUIREMENTS ARE NOT FULFILLED YOU WILL GET AN ❌
```
