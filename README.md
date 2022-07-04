# Cryptocurrenc_REST-API

An API lets two pieces of software talk to each other. 
Just like a function, you don’t have to know how the API works only its inputs and outputs.
An essential type of API is a REST API that allows you to access resources via the internet.
In this lab, we will review the Pandas Library in the context of an API, we will also review a basic REST API

we will be using the 
<a href=https://www.coingecko.com/en/api?utm_medium=Exinfluencer&utm_source=Exinfluencer&utm_content=000026UJ&utm_term=10006555&utm_id=NA-SkillsNetwork-Channel-SkillsNetworkCoursesIBMDeveloperSkillsNetworkPY0101ENSkillsNetwork19487395-2022-01-01>
CoinGecko API to create one of these candlestick graphs for Bitcoin. We will use the API to get the price data for 30 days with 24 observation per day, 1 per hour.
We will find the max, min, open, and close price per day meaning we will have 30 candlesticks and use that to generate the candlestick graph.
Although we are using the CoinGecko API we will use a Python client/wrapper for the API called <a href=https://github.com/man-c/pycoingecko?utm_medium=Exinfluencer&utm_source=Exinfluencer&utm_content=000026UJ&utm_term=10006555&utm_id=NA-SkillsNetwork-Channel-SkillsNetworkCoursesIBMDeveloperSkillsNetworkPY0101ENSkillsNetwork19487395-2022-01-01>PyCoinGecko. PyCoinGecko will make performing the requests easy and it will deal with the enpoint targeting.

Rest API’s function by sending a request, the request is communicated via HTTP message.
The HTTP message usually contains a JSON file. This contains instructions for what operation we would like the service or resource to perform.
In a similar manner, API returns a response, via an HTTP message, this response is usually contained within a JSON.

In cryptocurrency a popular method to display the movements of the price of a currency.

              /  \  /  \  /  \  /  \
                /    \/    \/    \/    \
███████████████/  /██/  /██/  /██/  /████████████████████████
              /  / \   / \   / \   / \  \____
             /  /   \_/   \_/   \_/   \    o \__,
            / _/                       \_____/  `
                
                ********PYTHON************
