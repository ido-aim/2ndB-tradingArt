---
title: Crypto Art Position Size
author: Aim Liu
date: 2022-12-24
category: Jekyll
layout: post
---
updated : _{{ page.date }}_

# Risk -> Calculate Position size for Crypto

## step1 : determine trading USD amount

$$
Trading\ Amount = \frac{Free\ capital}{\%\ SL distance}
$$

## step2 : trading amount also equal Leverage*Amount and Free capital = %loss x Total capital


$$
Leverage * Pos\ Amount = \frac{\%\ loss * total\  capital}{\%\ SL distance}
$$

> ##### NOTICE
> the more the leverage, the less the SL distance we could place
{: .block-tip }


```markdown
i.e. BTCUSD open LONG 17400 
target 17500 SL 17300(0.57%) 
free cap = 1,000$
trading amount and leverage = ?
```

$$
Trading Amount = \frac{1000}{0.0057} = 175,438
$$

at different leverage we could send various  amount like the following;

<div class="table-wrapper" markdown="block">

|Leverage|Pos Amount| Trading Amount|
|:-:|:-:|:-:|
|50|3,508|175,438|
|20|8,771|175,438|
|10|17,543|175,438|

</div>