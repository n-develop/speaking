# Microsoft presents: "Fun with (Feature) Flags"

## An introduction to Microsoft's Feature Management Library

Continuous Integration and Continuous Delivery are getting more and more popular. Some companies will make the new employees push
changes to production on Day 1. Sounds easy, doesn't it? But if every commit/merge to the "main" branch leads to an update on production,
what do you do with your unfinished feature? Or the feature, which has not gotten through QA, yet?

---

    Now either this

In this talk, we will look at one way of dealing with unfinished or untested features. Feature flags (aka. Feature toggles) in your code.
We will look at the library "Microsoft.FeatureManagement", which the Azure-Team released in Spring 2019.

    or this

In this talk, we will look at two ways we can take care of unfinished or untested features. Features toggles in your code and feature branches in
your VCS. When talking about feature toggles, we will look at the library "Microsoft.FeatureManagement", which the Azure-Team released in Spring 2019.

---

There are only a few slides used for the introduction. The rest of the time will be spent in the code to see how easy it is to integrate 
feature flags in a .NET Core codebase. While going through the demo, we will see why the package is called "FeatureManagement" and not just "FeatureFlags".


This talk is rated level 200 with a target audience of .NET developers.

It is assumed, that you have basic knowledge of software development with ASP.NET Core.
Code samples are written in C# and should be accessible to most programmers. 
