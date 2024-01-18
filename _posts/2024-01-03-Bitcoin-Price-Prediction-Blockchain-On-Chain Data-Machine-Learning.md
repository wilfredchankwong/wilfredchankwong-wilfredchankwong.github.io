---
layout: post
title: "Unveiling the Power of On-Chain Metrics: A Journey into Bitcoin Price Prediction with Machine Learning"
date:   2024-01-03 01:00:00
categories: projects
---

https://github.com/wilfredchankwong/BitCoin_Prices_Machine_Learning



Introduction:

In the ever-evolving world of finance, where traditional and digital assets converge, there lies an opportunity for innovative strategies and predictive models. This article delves into a project that combines a finance background, past options trading experience, and a keen interest in the cryptocurrency market. The project's objective is to leverage on-chain metrics and machine learning to predict short-term Bitcoin price movements, ultimately informing strategic decisions in the options trading realm.

Domain and Motives:

With a background in finance and prior experience in options trading, the author sought to explore new horizons in the cryptocurrency space. The decision to focus on crypto was motivated by the availability of readily accessible and real-time on-chain data. Unlike traditional financial markets, the crypto markets operate 24/7, providing a continuous stream of data to evaluate and refine prediction models.

Objective:

The primary objective of this project is to employ machine learning models to formulate short-term Bitcoin option trading strategies. The approach involves assessing whether the model predicts an upward or downward movement in prices. Based on these predictions, the author executes long call or put options accordingly. In cases where the model foresees a relatively flat market, short call or put options are considered, depending on whether the author holds Bitcoin at that time.

Progress and Observations:

The project commenced with an extensive literature review to identify key on-chain metrics that have shown significance in predicting Bitcoin price movements. The identified metrics include hash rate, funding rate, block count, exchange balance, and addresses holding more than 10 coins.

The initial machine learning model implementation involved adopting a unique approach to incorporating these metrics. Rather than directly inputting the raw metrics, a simple moving average (SMA) methodology was employed. The author recognized the importance of determining the optimal time window for each metric's SMA calculation. To achieve this, the Mean Squared Error (MSE) was employed, testing various SMA time windows to find the most predictive configuration.

Building upon this foundation, the project aims to expand the model by incorporating additional relevant factors. This iterative process allows for a dynamic and adaptive machine learning model that evolves with the ever-changing crypto landscape.

Conclusion:

This project represents a captivating intersection of finance, machine learning, and cryptocurrency. By leveraging on-chain metrics and employing innovative strategies, the author seeks to navigate the volatile waters of the crypto market with confidence. The ongoing progress and observations provide valuable insights not only into Bitcoin price prediction but also into the potential for informed decision-making in the options trading arena.

As the project unfolds, the article will continue to document the evolution of the model, sharing lessons learned, successes, and challenges encountered along the way. Stay tuned for further updates on this exciting journey into the world of on-chain metrics and machine learning in cryptocurrency trading.