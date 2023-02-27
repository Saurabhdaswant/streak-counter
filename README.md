# `@Saurabhdaswant/streak-counter` - a basic streak counter

this is a basic streak counter - inspired by duolingo - writtern in Typescript and meant for the browser (uses `localstorage`).

## Install

```shell
npm install @Saurabhdaswant/streak-counter
```
```shell
yarn add @c/streak-counter
```

## Usage

```js
import {streakCounter} from "@streakCounter/streak-counter"

const today = new Date()
const streak = streakCounter(localStorage, today)

// streak returns an object:
// {
//    currentCount: 1,
//    lastLoginDate: "11/11/2021",
//    startDate: "11/11/2021",
// }
```
