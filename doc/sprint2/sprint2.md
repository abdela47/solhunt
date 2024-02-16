# Sprint 1 Planning

## Sprint Goal

For this sprint, we are trying to merge some of the functionality we had that was developed seperately. We are also trying to get our pages to work with authenticated users properly. For example - a user should only be able to like something once 

## Participants

- Yousef Akiba
- Thivagar Nadarajan
- Thiago Vidal Murakami
- Ahmed Abdelaziz
- Thomas Verdier
- Ali Abushabanty

## Team Capacity

Our team aims to handle a total of 22 points this sprint.

## User Stories & Task Breakdown

SOL-21
- As a user, I want the ablity to view and add solutions for whichever question I'm on
- Subtasks:
	- SOL-61: Show solutions instead of solution ids
	- SOL-65: List the comments for each solution
	- SOL-66: Add textbox to add new solutions

SOL-52
- As a user, I want a navbar so I can navigate to pages of the site easily
- Subtasks:
	- SOL-56: As a user, I want to be able to navigate to login and signup pages from the home page or navbar for ease of access
	- SOL-59: Integrate Page component (containing the Navbar) into all relevant pages

SOL-6 
- As a user, I want the ability to find textbooks through filtering on different search criteria so that I can find the textbook more easily
- Subtasks:
	- SOL-67: Add a search results page
	- SOL-68: Add filtering to search results page

SOL-15
- As a moderator for the website, I want the ability to add textbooks so that answers can be added.
- Subtasks:
  - SOL-79: Create a script to generate a textbook object

SOL-2
- As a user, I want to be able to sign up with email or gmail so that I can keep track of my contributions to the site
- Subtasks:
  - SOL-60: Connect auth and Database
  - SOL-72: Add Button for google Sign up
  - SOL-73: Add Logic for signing up with Google Using Firebase

SOL-48
- As a user, I want the ability to change the password of my account.
- Subtasks:
  - SOL-62: Create UI for changing password
  - SOL-63: Integrate to firebase
  - SOL-64: Handle possible errors (password mismatch for instance)

SOL-49
- As a user, I want the ability to reset my password in case I forget it.
- Subtasks:
  - SOL-80: Create UI (page) for Resetting password
  - SOL-81: Link with firebase to send reset email

SOL-19
- As a user, I want the ability to bookmark specific questions (and consequently, their answers) so that I may easily return to them in the future.
  - SOL-44: Create Bookmark option in the questions page
  - SOL-69: Create list of bookmarked questions in the user page.


SOL-50
- As a user, I want ISBNs I enter when I request a textbook checked for validity so that the exact textbook I want can easily be added
- Subtasks:
  - SOL-70: Fix book request bugs
  - SOL-71: ISBN check function

SOL-53
- As a moderator, I want to be able to view textbook requests and delete them so that I can resolve textbook requests
- Subtasks:
  - SOL-57: As a moderator, I want to be able to view textbook requests
 
