# Week 12 | Day 5 Daily Journal

## *Final Checkpoint*

My goal for today: Get graded first thing in the morning so I can guage where I'm at, see if anything fails that I thought was passing and get a good game plan for the day.

I passed! I had a couple requirements missing- I couldn't delete vault keeps or increment view/keep count yet but passed all other requirements. I am so happy :DDDDDDD

The first part of the morning, I focused on getting my view/keep count incrementing. I went back to the server for this logic. On keeps get by id, I added to the sql statement to also update the property 'views' by setting views = views + 1. In the client, every time the keep is opened in a modal to be 'viewed', the function get by id is triggered and the keep count increments!

I did something similar with my vault keeps and just included that update inside the create vault method in my repository.