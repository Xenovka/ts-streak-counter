# basic streak counter

This basic streak counter is inspired by DuoLingo - written in TypeScript and meant for browser

### Install

```shell
yarn add @xenovka/streak-counter
```

or

```shell
npm install @xenovka/streak-counter
```

### Usage

```javascript
import { streakCounter } from "@xenovka/streak-counter";

const today = new Date();
const streak = streakCounter(localStorage, today);
```
