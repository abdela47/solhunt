# Sprint 1 Planning

## Sprint Goal

For this sprint, we are trying to get comfortable with the stack that we're working with. This means we should understand NextJS and React principles, along with being able to work with Firebase's API so we can query our database. We will pick user stories that allow us to familiarize ourself with these technologies while also setting up the foundation for more complex features in future sprints.

## Participants

- Yousef Akiba
- Thivagar Nadarajan
- Thiago Vidal Murakami
- Ahmed Abdelaziz
- Thomas Verdier
- Ali Abushabanty

## Team Capacity

Our team aimed to handle a total of 22 points this sprint.

## User Stories & Task Breakdown

The following contains a list of stories that we aim to finish for this sprint along with the necessary sub-tasks required to complete each story.

- As a user, I want secure authentication when I sign up and sign in so that my account isn't compromised <b>[2 points]</b>
  
  - Set up form in React for signing up
  
  - Use Firebase's Auth API to connect the form the Firebase's Auth Records

- As a user, I want the ability to to request a textbook that I want solutions for so I can learn from the solutions provided <b>[1 point]</b>
  
  - Create a collection in Firestore for storing requested textbooks

  - Create a small form for requesting textbooks

  - Connect the form to the requested textbooks collection 

- As a user, I want the ability to search for a textbook that I want so I can add/view solutions for it <b>[2 points]</b>
  
  - Create a collection in Firestore for storing available textbooks
  
  - Create a searchbar component

  - Connect searchbar component to the textbooks collection

- As a user, I want the ability to navigate to a specific question in a textbook so that I can add/view solutions <b>[4 points]</b>

  - Create a navigation view to navigate a textbook's contents

  - Create a separate page to view the solutions for a given question

  - Link solutions page to the navigation view

- As a user, I want the ability to rate solutions so that other students may know how helpful/relevant an answer is <b>[1 point]</b>
  
  - Create a collection in Firestore for solutions to questions. The documents in this collection should contain an "upvotes" property

  - Create a basic test form to like solutions

  - Connect the form to the solution documents from the solutions collection in Firestore

- As a user, I want the ability to type my solutions in latex so that I can type mathmatical solutions better <b>[1 point]</b>

  - Add a latex package to our app (which works with React)

  - Add a test page to ensure that we can type out latex solutions using the latex package

- As a user, I want the ability to flag solutions or comments that are inappropriate so that others may know a solution or comment is problematic <b>[4 points]</b>

  - Add a flag property to the documents in the solutions collection and the comments sub-collection (within solutions)

  - Create a test page with solutions/comments, along with a button for each which flags the corresponding solution/comment

- As a moderator for the website, I want the ability to remove textbooks so that mistakes made in adding textbooks can be resolved <b>[1 point]</b>

  - Create a basic moderator page to view information which will be important for moderators (requested textbooks, current textbooks, flagged comments etc)

  - Add the ability to search from the available textbooks and delete them

- As a user, I want the ability to view profiles of other users so that I can get an idea of how reliable the solutions from a user are (ie. user's average answer rating) <b>[4 points]</b>

  - Create a basic user profile page with the user's available data

- As a user, I want the ability to comment on other solutions so that I can suggest potential improvements <b>[2 points]</b>

  - Create a collection in Firestore for solutions to questions. The documents in this collection should contain another sub-collection for comments

  - Create a test page with solutions and its comments   



