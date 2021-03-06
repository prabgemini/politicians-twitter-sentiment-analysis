# Our Feelings About Politicians
Check it out here: [ourfeelingsaboutpoliticians.herokuapp.com](https://ourfeelingsaboutpoliticians.herokuapp.com/)

## What is this?
A real time analysis of the public's sentiment via Twitter of America's presidential candidates in the upcoming 2016 election and recent news articles relating to each of the candidates.

## Stack
* Node.js
* [Grommet](http://www.grommet.io/)
* [HPE Haven OnDemand](http://havenondemand.com/)
* [socket.io](http://socket.io/)

## Contribute to this open source project!
We're continually looking to update this dashboard with powerful insights extracted from rich data and metrics. We strongly encourage developers to fork the source code and submit a pull request with new features.

* [Fork it](https://github.com/HPE-Haven-OnDemand/politicians-twitter-sentiment-analysis/fork)
* Create your feature branch (`git checkout -b my-new-feature`)
* Commit your changes (`git commit -am 'Add some feature'`)
* Push to the branch (`git push origin my-new-feature`)

## Priorities
We encourage developers to add to this as they see fit. Here is what we think woud be neat additions to this dashboard:

1. Historical, searchable graphs (line, bar, or chart) of the information presented on this dashboard.
2. How each of the candidates stand on particular issues.
3. Each of the candidates plans once in office (taxes, military, etc).
4. Each of the candidates most recent tweets.
5. The capability for an admin account where they can change which hashtags, users, and topics to monitor through the UI.
6. Use Haven OnDemand's [Concept Extraction API](https://dev.havenondemand.com/apis/extractconcepts#overview) and [Entity Extraction API](https://dev.havenondemand.com/apis/extractentities) to create a tag (word) cloud for each candidate.
7. Save the topics and associated sentiment score from each tweet analyzed to determine an aggregate sentiment score for each topic. From this data, create a visualization to show the most negative and most positive topics related to each candidate.
