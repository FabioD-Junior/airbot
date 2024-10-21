##### <table style="border-collapse: collapse; border: 0;"> <tr> <td style="border: 0;">![Markdown Logo](source/airbot_logo.png) </td> <td style="border: 0;"> ![Markdown Logo](source/airbot2.png)  <br>Academic project for building a Stock Trading Bot using Deep Reinforcement Learning. </td> </tr> </table>

<hr>

# Welcome

> Welcome to our humble repository.
> We are the BR@IN team, and this repository is about our academic work where we faced the challenge of creating a bot (an automation that simulates a human) using advanced AI techniques such as Deep Reinforcement Learning.

<hr>

###  Our project repository
<hr>

> Our solution is divided into several repositories, each with different purposes.
> FinRL Mini is one of our best shots, with restricted computational resources, for instance, 1GB memory, we managed to create a lighter version of FinRL able to run on AWS free tier by removing libs and components that are not used in our project and those used just for model training, keeping only the necessary to run our agent.

####  Repository List  
| Repository | Description | Status |
|------|-------|-------|
| [Simulator](https://github.com/FabioD-Junior/brainSimulator) | Back-end tool for model testing | public
| [API](https://github.com/FabioD-Junior/brainApi)       | Flask API built to run on AWS freetier| public |
| [AI Hub](https://github.com/FabioD-Junior/brainAiHub) | Chatbot based on RAG and other NLP techniques | public|
| [FinRl Mini](https://github.com/FabioD-Junior/finrl_mini)      | A lighter version of FinRL lib, created by us, to run on AWS t2.micro environment | public |
| [Platform UI](https://github.com/bhattjaldhi/stock-trading-bot-nextjs)  | The UI Platform made in react.js which connects all our solutions in one place | private (to prevent credentials exposure)|

<hr>

### The Air Bot project

<hr>

> Our project uses the FinRL library (see the references section) to create agents (bots) capable of performing trading actions such as buying, selling, or holding a specific stock symbol.
> The final product is capable of executing single and multiple stock trading, but it is limited to the tickers of the Dow30.
Due to computational resource constraints, we had to use our creativity to come up with a solution that was light enough to run using free tiers of cloud while still achieving relevant results. Because of this, we divided our solution into parts to focus on optimizing each of these functionalities.

<hr>

### The Br@in Team
<hr>

> These are the team members in alphabetical order.

| Team Member | Main Role | 
|------|-------|
|Abin Benny	|  Research Data Engineer|
|Fabio Duarte Junior	| Team Leader / Machine Learning Engineer |
| Jaldhi Himanshu Bhatt	| Full Stack Software Engineer |
| Manali Shaileshkumar Patel	| User Experience Engineer|
| Shivaganesh Birru	| Analytics Engineer|
	
	

<hr>
### How to cite our work (in case you want to use any reference or code from our repository)
<hr>

> If you want to use our work or our code do not forget to cite us.

```
@misc{AirBot,
author = {Fabio Duarte Junior, Jaldhi Himanshu Bhatt, Shivaganesh Birru, Manali Shaileshkumar Patel, Abin Benny},
title = {AirBot: A stock trading bot based on FinRL lib. Academic project by group A3- BR@IN},
year = {2024},
note = {Available at: \url{https://github.com/FabioD-Junior/airbot/}, AI & DS course at Loyalist College},
}
```

<hr> 

## Disclaimer
> It is important to reinforce that this is a purely academic project. We do not intend to guarantee that this project, as it is, can be used in a real environment. Nor can we affirm or guarantee any kind of profit or that the project's applications are free from flaws, even though we have conducted several tests.

## References

> This project is mostly based on the cited work below. 
>> Article  : dynamic_datasets
>> 
>> Authors : Liu, Xiao-Yang and Xia, Ziyi and Yang, Hongyang and Gao, Jiechao and Zha, Daochen and Zhu, Ming and Wang, Christina Dan and Wang, Zhaoran and Guo, Jian
>>
>> Title   : Dynamic Datasets and Market Environments for Financial Reinforcement Learning
>>
>> Journal : Machine Learning - Springer Nature
>>
>> Year    : 2024

<br>

<hr>
