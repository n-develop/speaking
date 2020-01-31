# Feature management with examples in .NET 

Continous Integration and Continous Delivery are getting more and more popular. There are companies who will make the new employees push
changes to production on Day 1. Sounds easy, doesn't it? But if every commit/merge to "master" leads to an update on production,
what do you do with your unfinished feature? Or the feature, which has not gotten through QA, yet? 

In this talk, we will look at two ways we can take care of unfinished or untested features. Features toggles in your code and feature branches in
your VCS. When talking about feature toggles, we will look at the Library "Microsoft.FeatureManagement", which the Azure-Team released in Spring 2019.

This talk is rated level 200 with a target audience of software developers.

It is assumed, that you have basic knowledge of software development with ASP.NET Core.
Code samples are written in C# and should be accessible to most programmers.
