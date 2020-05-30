# Mach42 Code Challenge 5/30/2020
# Building a Like Feature
You will have approximately 2 hours to complete the following project:
You'll be building a simple like feature very similar to other social networks like Facebook. 

For a given post, users should be able to "like" the post. This will increase a "like score" by 1 point for each like. Users should only be able to like a post a single time.  Additionally, if the user decides to change their mind, they should be able to undo their like by clicking the same button again.
The button for liking and unliking should be one and the same with a conditional render determining whether the unlike or like icon shows, meaning the icon changes visually in some way to show that it is “clicked”

# Requirements:
- The user should be able like a post (maximum of 1 time)
- The user should be able to unlike a post
- The post should display the total like score across all users.
- The like and unlike button should be the same button but conditionally render the correct action.

# Instructions for Submission:
Fork and Clone this repo onto YOUR github account of choice.
Submissions should be in the form of a Pull Request with YOUR NAME in the title (ie: Luke Skywalker - Mach42 5/30/20 Code Challenge).

# Challenge modifications!
Users should now be able to upvote and downvote a post. Users can only upvote, downvote or reverse those actions. As an example, an Upvote would increase the like score by 1. This action should be able to be undone so that the like score is not affected by the user. The User can also downvote a post which would reduce the like score by 1. This action should also be reversible.

Unlike button (unclicked):
```
<i class="far fa-thumbs-down"></i>
```
Unlike button (clicked):
```
<i class="fas fa-thumbs-down"></i>
```
# Optional Hosting:
Hosting isn't required for this Hack, but if you want to, feel free to use whichever hosting service you would like. Here is a quick 30 second video for using Surge to host.
https://www.youtube.com/watch?v=W-Kc_zjfeH0


