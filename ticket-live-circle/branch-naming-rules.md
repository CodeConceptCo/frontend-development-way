## 1. Branch naming rules.

Let's imagine that we have a ticket called **Create pie widget card** and we start working on it.

Before you start working, create a new branch with a name related to the ticket name. The name should fully reflect the essence of the task. You have different options to do this based on your project tracking software or development process. 

A basic structure of the branch can be **pie-widget-card.**

Also, you can use **ticket id** from your tracking software. 

If you have sprints in your development process and create new branch for each sprint with the unique name — use that name instead of ticket id. 



_Bad_

-   my-develop-branch

_Good_

-   pie-widget-card
-   СС-001-pie-widget-card



If you have tiket id like **CC-001 **then branch name will be **CC-001-pie-widget-card**.



Benefits:

1.  Understanding on which ticket you working over time.
2.  Understanding for which ticket changes were made in git history without hassle.
3.  If you use id, you can simply open that ticket with just pass id in URL, instead of looking for it overall board.