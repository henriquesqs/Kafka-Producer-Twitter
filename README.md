# Kafka-Producer-Twitter
A Kafka producer using Twitter API to get access to tweets. 
This is a project from [Apache Kafka for Beginners course](https://www.udemy.com/course/apache-kafka/) by Stephane Maarek

## Description
This project creates a simple **[Apache Kafka](https://kafka.apache.org/) Producer** that searches for specific strings on tweets and prints all the public informations (provided by the API) about the found tweets. For example, if you set to search for **"soccer"**, you'll receive on terminal all tweets with the string **"soccer"** in it in **real-time**.

To see the "real-time" action, set the variable `terms` to some weird string and post a new tweet on your personal Twitter account using this same string. You must see the tweet on your terminal immediately!

## Goal

I started to learn Kafka to understand more about real-time and near real-time data streams and how to consume its content. 
Also, I was working on a project that needed some understanding about real-time data streams so I choose to learn a little about Apacha Kafka alongside the concepts of data streams.

## Notes

**To run this project, you'll need to [apply to get access to Twitter API](https://developer.twitter.com/en/apply-for-access) and replace the missing informations on this project.**

**REMEMBER THAT YOU SHOULD NOT SHARE YOUR API ACCESS INFORMATIONS!**
