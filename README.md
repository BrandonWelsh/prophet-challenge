## Information
Written by: Brandon Welsh

Start date: 1/1/2024 10:30am

Due date: 1/3/2023 11:59pm

## Program Goals
"You’re a growth analyst at Mercado LibreLinks to an external site.. With over 200 million users, Mercado Libre is the most popular e-commerce site in Latin America. You've been tasked with analyzing the company's financial and user data in clever ways to make the company grow. So, you want to find out if the ability to predict search traffic can translate into the ability to successfully trade the stock.

The instructions for this Challenge are divided into four steps, as follows:

Step 1: Find unusual patterns in hourly Google search traffic.

Step 2: Mine the search traffic data for seasonality.

Step 3: Relate the search traffic to stock price patterns.

Step 4: Create a time series model with Prophet." 

(copied from BootcampSpot Module 8 Challenge Overview)

## Dependencies
Prophet Library, Pandas Library, Datetime Library, Numpy Library

## Setup Instructions
Run pip install Prophet, Pandas, Datetime, and Numpy before running program (if you do not already have these libraries).

## How to use
Run each jupyter notebook cell. That's pretty much it.

## Resources Utilized
This section is dedicated to keep track of what I used to help complete this project:

70% class notes

30% AI assistance

I was able to stick to the class notes (specifically the ones we made using google collab) for most of the project. Any time I got hung up on something or was getting an error, I had an AI walk me through what went wrong and steps to take to fix my code. It's incredibly useful having an AI assistant while coding, it just knows EVERYTHING.

## Bugs
Oh boy here we go, there were a few things to note on this one lol:

When I had to calcluate the monthly median search traffic across all months in Part 1, it kept showing the average of monthly medians of every year rather than one single value for the overall monthly median. To circumvent this, I took an average of the yearly medians.

Part 3 already had all the answers filled in to the open-ended questions, so I deleted those and replaced them with answers which reflect my own observations of the data.

In step 3 of Part 4, I could not set the index in the forecast_mercado_trends DataFrame to the ds datetime column because ds was already the index. So I commented out the troublesome code and moved on.

I have no idea what forecast_canada means, I think that was just a typo in the comments left by the curriculum team.

## Update Log
1/1/2024: Created github repo. Modified my README.md template in accordance with the feedback I recieved on my Module 6 challenge. Finished Step 1, Step 2, and Step 3. Pushed changes to github. I'm tired, I'll finish this project tomorrow.

1/2/2024: Finished Step 4, proofread and proofran entire thing, and got the project ready to submit.