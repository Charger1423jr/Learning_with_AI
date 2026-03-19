# Notes on Book Recommendation AI Approach

---

## Planned AI Model/Type to Use for Book Recommendation
#### Reactive Machine AI

---

## Notes on Reactive Machine AI
- Deemed one of the simplist AI types
- Performs basic Operations; Reacts to input with an output
- Examples: Netflix's Recommendation System

---

## Plan to Incorperate
- Will take the user's read books stored on Bookeep as basis for system
- Utilizing the OpenLibrary API, we will scrub the library for similar books to user database
  - Will take the Title, Author, Genre
- Process will generate a score of books based on information
- Will send the list (JSON) to the backend for sharing
- JavaScript code will post the list on the HTML page, linking to that book's OpenLibrary Page and GoodRead's page.
  - Will Present 10 Books. Button to filter out book or hide it will be there, which will replace that book with another one.
