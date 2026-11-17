# Vehicle Financing Calculator

A Hebrew JavaScript interface for selecting a vehicle price and calculating a down payment and an illustrative monthly amount. Original commits date to March 2022.

![Original calculator animation](Untitled%20design.gif)

## How it works

The [calculation code](index.js) reads the selected price and down-payment percentage from the form, calculates the down payment, and renders the results in Hebrew.

The monthly amount is the remaining balance multiplied by the hard-coded factor `0.011667`. That fixed factor is part of the original demonstration.

## View locally

```sh
python3 -m http.server 8080
```

Open `http://localhost:8080`.

## Project structure

- [index.html](index.html) contains the interface.
- [index.js](index.js) contains the calculation and result rendering.
- [css/main.scss](css/main.scss) contains the source styles.

## Project history

[Original March 2022 commits](https://github.com/shlomisaadon/financingCalculator/commits/main/?since=2022-03-01&until=2022-03-31).

This early project demonstrates browser form handling, numeric calculations, and DOM updates. Current browser behavior has not been revalidated during the November 2026 documentation update.
