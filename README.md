# Maximizing Max Challenge - Bot

## Introduction
Max Verstappen gained a lot popularity since his appearance in the Formula 1. With his popularity comes a big fan base who is interested in his carreer and his fans are emailing him all kind of questions the whole day.
Max likes the personal touch with his fans and would like to answer them, but he has a very busy schedule with preparing for races. Because of this he is very interested in a solution to automatically answering the emails from his fans.

## Challenge
Write a bot who is capable of answering the questions coming from Max's fans. The answers to the questions can be found by using Max's content REST API 

### Participate
- Clone one of the sample applications
  - C#: https://github.com/exactsoftware/maxbotchallenge-csharp
  - Node.js: https://github.com/exactsoftware/maxbotchallenge-nodejs
- Build your bot to find the answers to questions directed to Max
- Push your bot to the given team git repository

### Judgement
- We will ask 10 questions by sending requests to your bot's endpoint.
- We expect that your endpoint is giving the correct answers to these questions within 5 seconds.
- If your bot give content back which contains the right answer you will recieve __1 point__.
- If your bot gives exactly the right answer you will recieve __3 points__.
- In case of equal scores, the time taken by your bot to provide the answers will be taken.
- It’s not permitted to put the answers inside your code.

## Max API
The Max content API has the endpoints where you can use to harvest the answers.
- News: https://raw.githubusercontent.com/exactsoftware/maxbotchallenge/master/data/news.xml
- Events: https://raw.githubusercontent.com/exactsoftware/maxbotchallenge/master/data/events.json

## Samples
We will not let you getting started in the dark and provided you with some sample questions and an application which you can take as starting point.

### Questions
These are some questions which you can expect.

- What time do you start the qualifying race of the Formula 1 Monaco?  
  _13:00_
- What do you think of the Formula 1 Russia?  
  _Sochi is an interesting track: a circuit with room to overtake. Hopefully we don’t need to but if it’s necessary, there are opportunities._
- For which team do you race?  
  _Red Bull Racing_
- Which place did you end in Barcalona in 2016?  
  _1st_

> All answers can be harvested from the content provided by the Max API. 
