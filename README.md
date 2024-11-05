# Bulldozer-project

## Overview
The goal is to predict the sale price of a particular piece of heavy equiment at auction based on it's usage, equipment type, and configuaration.  The data is sourced from auction result postings and includes information on usage and equipment configurations.

Fast Iron is creating a "blue book for bull dozers," for customers to value what their heavy equipment fleet is worth at auction.

## Data
For this competition, you are predicting the sale price of bulldozers sold at auctions.

The data for this competition is split into three parts:

Train.csv is the training set, which contains data through the end of 2011.


Valid.csv is the validation set, which contains data from January 1, 2012 - April 30, 2012 You make predictions on this set throughout the majority of the competition. Your score on this set is used to create the public leaderboard.


Test.csv is the test set, which won't be released until the last week of the competition. It contains data from May 1, 2012 - November 2012. Your score on the test set determines your final rank for the competition.


The key fields are in train.csv are:

SalesID: the unique identifier of the sale

MachineID: the unique identifier of a machine.  A machine can be sold multiple times

saleprice: what the machine sold for at auction (only provided in train.csv)

saledate: the date of the sale

## Evaluation

The evaluation metric for this competition is the RMSLE (root mean squared log error) between the actual and predicted auction prices.
