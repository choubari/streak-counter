# `@choubari/streak-counter` - a basic streak counter

This is a basic streak counter - inspired by Duolingo - written in TypeScript and meant for the browser (uses `localStorage`).

## Install

```shell
yarn add @choubari/streak-counter
```

```shell
npm install @choubari/streak-counter
```

### Usage

```typescript
import { useStreak } from "@choubari/streak-counter";

const today = new Date();
const streak = useStreak(localStorage, today);
// streak returns an object:
// {
//    currentCount: 1,
//    lastLoginDate: "11/11/2021",
//    startDate: "11/11/2021",
// }
```

### Demo

This [repository](https://github.com/choubari/streak-counter-demo) serves as a usecase demonstration of this npm package. The demo was created using [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).
