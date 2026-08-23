# Event Tasks

Participants will receive additional feature requirements during the event.

The feature challenges are designed to progressively increase in difficulty.

## Problem 1 — Genre Filter

Add a genre filter to the movie collection.

Users should be able to filter movies based on genres such as:

* Action
* Comedy
* Drama
* Sci-Fi
* Thriller
* Animation

---

## Problem 2 — Rating Sort

Add sorting functionality that allows users to sort movies:

* Highest rating → Lowest rating
* Lowest rating → Highest rating

---

## Problem 3 — Watchlist

Add a **Watchlist** feature.

Users should be able to:

* Add movies to their watchlist
* Remove movies from their watchlist
* View their watchlist

The Watchlist should be accessible from the navigation bar.

---

## Problem 4 — Dark Mode

Add a Dark Mode / Light Mode toggle.

Requirements:

* Toggle should be accessible from the navigation bar.
* The theme should affect the entire application.
* The selected theme should remain after refreshing the page.

---

## Problem 5 — Recently Viewed

Add a **Recently Viewed** section.

Whenever a user opens a movie's details page, that movie should be added to the Recently Viewed list.

Requirements:

* Display the most recently viewed movies.
* Maximum of **5 movies** should be displayed.
* Newer views should appear before older views.
* Previously viewed movies should not appear multiple times.
* Recently viewed data should persist after refreshing the page.

---

## Problem 6 — Make It Real 

The foundation project contains placeholder movie data. Your first task is to replace the placeholder content with real-world movies.

Update the movie dataset so that each movie represents an actual movie.

For every movie, update all relevant information, including:

Movie title
Movie poster
Genre
Release year
Rating
Duration
Director
Cast
Description

---

# Bonus Challenge — Surprise Me

Add a **Surprise Me** button.

When clicked, the application should randomly select a movie from the available movie collection and take the user to its details page.

### Bonus Requirement

The same movie should not be selected twice consecutively.

---

# Git/GitHub Workflow

The primary objective of **Fork ’nd Roll** is to evaluate how effectively participants use Git and GitHub.

Participants are expected to follow a proper development workflow.

```text
Fork Repository
       ↓
Clone Repository
       ↓
Create Feature Branch
       ↓
Implement Feature
       ↓
Commit Changes
       ↓
Push Branch
       ↓
Create Pull Request
       ↓
Review Changes
       ↓
Merge / Submit
```

---

# Branching Requirements

Each feature should be implemented in a separate branch.

Example:

```text
feature/genre-filter
feature/rating-sort
feature/watchlist
feature/dark-mode
feature/recently-viewed
```

Participants should **not directly implement all features on the main branch**.

---

# Commit Requirements

Participants should make **meaningful and descriptive commits**.

### Good examples

```text
feat: add genre filtering
feat: implement movie watchlist
feat: add rating sorting
feat: add dark mode toggle
feat: implement recently viewed movies
```

### Avoid commits such as

```text
done
final
changes
update
asdfgh
working
```

Meaningful commits are an important part of the evaluation.

---


# Evaluation Focus

The event is primarily focused on **Git/GitHub workflow**, while also evaluating the quality of the implemented features.

The evaluation may consider:

### Git/GitHub Usage

* Correct repository fork
* Correct branch creation
* Meaningful commits
* Proper commit history
* Correct pushing workflow
* Pull Request usage
* Branch organization
* Repository cleanliness

### Implementation

* Feature correctness
* Functional behavior
* Handling of edge cases
* Integration with the existing project

### Code Quality

* Readability
* Reusability
* Meaningful naming
* Reasonable component structure
* Avoidance of unnecessary code

### UI/UX

* Responsive design
* Visual consistency
* Usability
* Proper handling of different screen sizes

---

# General Restrictions

Participants should not:

* Replace the entire project with a new project.
* Delete the existing project structure unnecessarily.
* Add a backend.
* Add a database.
* Use external APIs unless explicitly permitted.
* Use unnecessary frameworks or libraries.
* Commit directly to the original organizer repository.
* Submit someone else's work.

The objective is to **extend the provided project**, not rebuild it from scratch.

---

# Event Philosophy

Fork ’nd Roll is not simply about who writes the most code.

It is about demonstrating that you can:

> **Fork it.
> Branch it.
> Build it.
> Commit it.
> Push it.
> PR it.
> Roll with it.**

Good luck, and may your commits be meaningful. 
