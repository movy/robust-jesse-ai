# robust-jesse-ai
Tricks &amp; tools to make Jesse trading bot scalable and robust

This repo is dedicated to amazing [Jesse crypto trading bot](https://jesse.trade/). While Jesse is probably the best trading solution out of the box, it was not created with running at scale in mind but at some point every serious trader faces this challenge.

Currently I am building a scalable trading framework with Jesse in its core, and along the way I encountered number of issues. This repo is a collection of tricks and tools I created along this exciting journey. 

While everyone's approach to trading is different, I hope these tools will help some traders to improve their setups and make trading more robust, less repetitive and fun! 

My framework is in the __very__ active stage of development right now, so my time is extremely limited, but I will do my best to populate this repo with new stuff once it is well tested and open-source ready, so stay tuned.

---------- 

## Getting rid of Binance's `ERROR: 503 Service Unavailable` errors

... and avoiding abuse on Binance APIs no matter how many routes you're running

See /nginx_api_proxy for configs and explanations. 

## TODO

Below is the list of future additions to this repo with a glimpse of what they look like. 

- [ ] Developing strategies TradingView style

<img width="1387" alt="image" src="https://user-images.githubusercontent.com/4336560/224215163-3ab60d24-ef45-4a3c-8f5f-79aa33b97314.png">


- [ ] Trading same routes with multiple strategies

- [ ] Trading 100s of routes on a single machine

<img width="720" alt="image" src="https://user-images.githubusercontent.com/4336560/224216552-f2398016-8358-4f4d-8daf-626561687187.png">

- [ ] Backtesting at scale

<img width="1143" alt="image" src="https://user-images.githubusercontent.com/4336560/224215791-8a6d045a-de16-4d7c-a195-cdfe8083e11f.png">

- [ ] Advanced notifications
- [ ] Cloud logging
- [ ] Backup bots
- [ ] Automatic strategies deployment with autoscaling

<img width="720" alt="image" src="https://user-images.githubusercontent.com/4336560/224216246-0aedd1bb-8927-47dc-aff2-1342f1d179f0.png">

