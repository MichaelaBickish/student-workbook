# Week 5 | Day 2 Daily Journal

Afternoon Project: https://github.com/MichaelaBickish/spring21-gregslist-revisited
https://github.com/MichaelaBickish/spring21-gregslist-server

Read Servers with Node/Express > MongoDb Relationships and answer the following questions

## *What are the three types of relationships?*
one-to-one
one-to-many
many-to-many

## *What are the benefits of the traditional linking of relationships instead of Embedding*
As the "comments" grow, the original document doesn't also grow, making it less likely to run into the max doc size of 16 mb. Also easier to return paginated comments as the app can slice and dice the comments more easily.

## *What are some of the challenges faced when deciding how to manage a many-to-many relationship that ultimately drive your decision on how to create it?*
many to many can get really complicated