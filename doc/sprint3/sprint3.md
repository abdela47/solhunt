# Sprint 3 Planning

## Sprint Goal

For this sprint, we are focused on adding more features to improve the experience of both users and moderators.

## Participants

- Yousef Akiba
- Thivagar Nadarajan
- Thiago Vidal Murakami
- Ahmed Abdelaziz
- Thomas Verdier
- Ali Abushabanty

## Team Capacity

Our team aims to handle a total of 26 points this sprint.

## User Stories & Task Breakdown

SOL-15
- As a moderator, I want the ability to add textbooks so that answers can be added
- Subtasks:
	- SOL-87: Create UI to recursively ask for textbook sections & generate the textbook object
	- SOL-89: Add new document to textbooks collection, using the UI
	- SOL-90: Clean up the UI & add more styling

SOL-84
- As a user, I want a cleaner UI for filtering textbook results so I can more easily filter textbook results
- Subtasks:
	- SOL-97: Add filtering drawer

SOL-85
- As a user, I want my information (such as name, email, username) to show on my home page.
- Subtasks:
	- SOL-99: Fix issue with username -- some usernames were not unique
	- SOL-100: Get user information from Firebase
	- SOL-101: Add Change password/logout functionality (Already implemented in a test page)
	- SOL-102: Discontinue test home-page

SOL-86
- As a user, I want to have a unique username that can be traced back to my account.
- Subtasks:
	- SOL-94: Add username field to sign_up page
	- SOL-95: Store username in Database
	- SOL-96: Make sure username is unique

SOL-19
- As a user, I want the ability to bookmark specific questions (and consequently, their answers) so that I may easily return to them in the future.
- Subtasks:
	- SOL-44: Create Bookmark option in the questions page
	- SOL-69: Create list of bookmarked questions in the user page.
