---
title: Trading Art Position Size
author: Aim Liu
date: 2022-12-24
category: Jekyll
layout: post
---
updated : _{{ page.date }}_

# Risk -> Mindset

## Part1 : Find Free cap
 - Determine Total Capital

$$
ex\ cap = 100\ mUSD
$$

 - Determine Target Profit 

$$
ex\ target\ profit = 10\%\ APR
$$

 - Determine Free Capital or Maximum loss 

$$
ex\ target\ profit = 10\%\ ex\ cap = 1\ mUSD
$$

 - Conclusion

$$
free\ capital = 1\ mUSD
$$

## Part2 : Find Periodic target

- Set up Daily/Weekly/Monthly Free Capital 

$$
Monthly\ Free\ cap = \frac{Anually\ Free\ cap}{12} = \frac{1\ mUSD}{12} = 83.33\ kUSD
$$

- Target ~ 1-1.5X Free Capital

$$
Target = 1.3*83.33\ kUSD= 108.33\ kUSD
$$

- Revised `Profit Goal` and `Stop Loss`

## Part3 : scenario example
- Determine Free cap `5$`
- 1st month made `2M$`
- Total Free cap = `5M$ + 2M$ = 7M$`
- Next Month can risk `Free Cap/12 = 7M/12 = 583k$`
- Next Month Target = 1.5X Free Capital = `At least 874.5k$`

## Part4 : Tracking
Daily/Weekly/Monthly : Avg gain loss - try to reduce volatility


# Risk -> Calculate Position size for Fx
> ##### NOTE
> These calculation only apply on 1 Standard lot = 100,000 units
{: .block-tip }

## step1 : determine trading amount

$$
trading\ amount = Lot * units
$$

## step 2 : trading amount also equal to %loss x free capital

$$
\%\ loss * free\ capital = Lot * units
$$

## step 3 : example

$$
Lot = \frac{\%\ loss * Free\ capital}{units} = \frac{\%\ loss * Free\ capital}{10*pips}
$$

```markdown
i.e. XAUUSD open LONG 1740.317 
target 1750.323(1000.6 units)
expected loss 50$
open lot = ?
```

$$
Lot = \frac{50}{1000.6} = 0.05
$$

# Calculate Position size for Fx -> Lot Note

<div class="table-wrapper" markdown="block">

|pips|units| Lot|
|:-:|:-:|:-:|
|10,000|100,000|1|
|1,000|10,000|0.1|
|100|1,000|0.01|

</div>

# Risk -> example Excel

<a href="https://ido-aim.github.io/paper/dist/20220902_FuturePositionSize/" target="_blank">Risk -> example Excel</a>