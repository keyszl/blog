---
layout: post
title:  "Data Modeling"
date:   2021-12-16 18:34:22 -0500
categories: jekyll update
author: Zoie Keys
---

**Entities! Schemas! Vertabelo!**

For this lab, I was tasked with creating a schema for a hypothetical grocery store that wanted to start online orders.
I began by starting up trust ol' vertabelo, and I began to create different entities based on what I thought the store would need, such as a customer table, order, order details, etc. I also made a table specifically for the address attached to the customer table, because I knew there were several parts of the address that would have to be considered, such as city, zip code, and country, besides the actual street address. I believe this schema is adequate for an online ordering system, and I am satisfied with it. I think a potential problem that could occur is if users are ordering at the same time. For example, if two users are shopping and both have the same item in their cart, which there is only one in stock, and one customer checks out before the other, then the customer who still hasn't checked out will think that the item is in stock, when in reality it isn't. 

![schema](schema.PNG)
