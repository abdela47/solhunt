# Sprint 3 Planning

## Sprint Goal

For this sprint, we are focused on cleaning up the look of the website and fully implementing user features

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

SOL-106

- As a moderator, I want the ability to update existing textbooks
- Subtasks:
  - SOL-107: Create component to edit book, using a hard-coded book id
  - SOL-108: Add view to search and edit textbooks
  - SOL-109: Consolidate AddBook & EditBook components

SOL-91

- As a user, I want the ability to view profiles of other users so that I can get an idea of how reliable the solutions from a user are (ie. user's average answer rating).
- Subtasks:
  - SOL-115: Create page for other-user-profile
  - SOL-116: Add style to page (CSS)
  - SOL-117: Link user references to this page

SOL-114

- As a user, I want to post solutions and comment on solutions with my own username.
- Subtasks:
  - SOL-118: Replace Mock by actual logged in user
  - SOL-119: Make sure that only logged in users can post answers/comments
  - SOL-120: Add style (CSS) to new components
  - SOL-121: Handle errors (messages for non-logged in users)

SOL-82

- As a user, I should only be able to like/flag a solution (or comment) once.
- Subtasks:
  - SOL-110: Limit likes and flags per user in a solution.
  - SOL-111: Limit likes and flags per user in a comment.

SOL-54

- As a moderator, I want to be able to view flagged items that have passed a
  certain flag threshold so that I may remove problematic items
- Subtasks:
  - SOL-112: View flagged items on mods page
  - SOL-122: Navigate to the flagged item's question page by clicking the flagged item
