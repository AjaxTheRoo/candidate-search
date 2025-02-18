# candidate-search
Web application to help find candidates on GitHub.
-View GitHub user profiles, including name, username, location, email, and company.
-Save profiles to a list of potential hires.
-Remove candidates from the saved list.
-Seamlessly navigate between the search and saved candidates pages.

## Features
Candidate Search: Fetch and display GitHub user profiles with key details.
Save Candidates: Add promising profiles to a saved list for later review.
Remove Candidates: Delete profiles from the saved list when no longer needed.
Responsive UI: Clean, modern, and adaptable design.

## Tech Used
**React**
**TypeScript**
**Vite**
**GitHub API**
**React Router**

## Code Attribution
API Integration: GitHub user data is retrieved using the GitHub REST API, with integration logic in src/api/API.tsx.
React Router Setup: Navigation is structured using React Router, with configurations in src/main.tsx.
LocalStorage Usage: Candidate saving and retrieval logic is implemented in src/pages/CandidateSearch.tsx and src/pages/SavedCandidates.tsx.

![screenshot1](https://github.com/AjaxTheRoo/candidate-search/blob/main/assets/Capture1.JPG)
![screenshot2](https://github.com/AjaxTheRoo/candidate-search/blob/main/assets/Capture2.JPG)
