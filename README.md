# Chainalysis | Software Engineer, University Grad | Applicant Take Home Test

Web app written in Python (Flask) to recommend which between the two exchanges to buy and sell Bitcoin and Ethereum from

# Instructions: 

We would like to look at a webpage that shows:

Prices of Bitcoin and Ethereum from two (any) different exchanges/sources. 
Differentiate buy and sell price clearly 
Recommendations on which exchange one should buy and/or sell.
Recommend where to buy and where to sell. Each of the recommendation can be a different exchange

# Deliverables:

Link to github with the code: https://github.com/SMak06/Crypto-price-check

Detailed instructions on how to build and run:

* Clone the Repository
* Make sure you have Python 3.4 or up installed
* Install library requirements from requirements.txt
* Run the command 'python app.py' using terminal

Answers to below Questionnaire ( included as a markdown file in GH repo). 

For bonus points, provide a link to live version of the solution: https://crypto-checker-price.herokuapp.com/
 

# Other info that is useful for doing the exercise:

If BTC is 10000$ to buy on Exchange A and 10050$ to buy on Exchange B, you would recommend to buy on Exchange A. 
Any front end technology is fine. We use React
Any backend technology is fine. We use spring boot/java 
You can pick any exchange for pricing. If exchange price is unavailable, use price from any service provider such as blockchain.com
Your webpage is not hard coding the prices. It should talk to its own backend to fetch the prices. And that backend fetches prices from other exchanges/service providers
 
# Questionnaire:

Are there any sub-optimal choices( or short cuts taken due to limited time ) in your implementation?

Ans. If given a longer time, I would create a full stack application with a frontend framework (react) and a backend using Java and maven. However, the current application (built using Flask) caters to all the requirements.

Is any part of it over-designed? (It is fine to over-design to showcase your skills as long as you are clear about it)

Ans. Actually no. I kept the web-app pretty simple and straight forward to serve the demonstration purpose.

If you have to scale your solution to 100 users/second traffic what changes would you make, if any?

Ans. Presently, the API is being fetched directly and is major enough to handle good loads of traffic, however, if it were to have been on the backend in a server, I would have to make sure there are no bottlenecks. Would have written proper unit tests to ensure the server works at optimal speeds without overload to find out where do the bottlenecks or faults exist, if any. I would implement a multithreaded system to increase speeds and efficiency. 

What are some other enhancements you would have made, if you had more time to do this implementation

Ans. First of all, I would have made the look and feel more aesthetic, appealing and modern using Bootstrap/Material UI. Moreover, I would have loved to implement a backend system for the same using Java and maven. 
