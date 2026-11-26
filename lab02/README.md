# 953261 Lab 2 — Kad Café (Modern JavaScript)

| | |
|---|---|
| **Name** | _Watcharachai_ |
| **Nickname** | _Washi_ |
| **Student ID** | _692115037_ |
| **Section** | 701 |

## How to run

```bash
cd lab02
npm run warmup   # Part B
npm test         # Part C
npm start        # Part D — the daily report
```

## My own function (Part D)

`itemsWithTag(menu, tag)` returns the names of the menu items that have the given tag.
It uses `filter` (with `includes`) to keep only the items whose `tags` contain the tag,
then `map` to turn each item into its name.

## What I learned today

I use `map` to change every item into something else, like menu items into names,
and `filter` to keep only the items I need. I use `find` to get one item by its id,
and `reduce` to combine a whole array into one value, like the total sales of the day.

## AI-use statement
I used Claude to explain JavaScript concepts and error messages, and to help me
debug my code. When I was stuck, it showed me example solutions and code outlines.