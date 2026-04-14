Movie Recommender by Mood (MRM)
**What the software does**
Movie Recommender by Mood is a simple web application that recommends movies based on the user's current mood. The user selects a mood, and the app displays a short curated list of matching films.

**Core features implemented**
- Mood selection screen
- Six mood options: Happy, Sad, Relaxed, Excited, Romantic, Motivated
- Movie recommendation cards
- Movie title, year, rating, mood tag, poster, and short description
- Trailer button that opens YouTube search results
- More Info button that opens IMDb search results
- Change mood button to return to the mood selection screen
- Simple and responsive visual design
- No login required

**Setup and run instructions**
1. Download or copy the project folder.
2. Make sure the following files are in the same project folder:
   - movie-recommender.html
   - images folder
3. Open movie-recommender.html in a modern web browser such as Chrome, Edge, or Firefox.
4. Select a mood from the home screen.
5. View the recommended movies for that mood.
6. Use the Change mood button to go back and choose another mood.

**Dependencies / install steps**
No installation is required.
This project does not use npm, Python, backend code, or a database because the app does not require the use to login may add them in the future though. It runs locally using HTML, CSS, and JavaScript.
The project uses Google Fonts through an online link. If there is no internet connection, the website will still work, but the font style may look slightly different.
**Environment variables / config**
No environment variables are needed.
A .env file is not required because there is no backend, database, or API key in this prototype.

**Test credentials / sample inputs**
No test credentials are needed because the system does not have a login feature.
Sample inputs:
- Happy
- Sad
- Relaxed
- Excited
- Romantic
- Motivated

**Known limitations / not implemented yet**
- The movie dataset is static and manually written inside the JavaScript code.
- There is no user account or login system.
- There is no database.
- There is no machine learning or advanced personalised recommendation algorithm.
- Movie posters must be stored correctly in the local images folder.
- Trailer and IMDb buttons open search result pages, not exact official movie pages.
- User feedback and review storage are not implemented yet.
- The user cant choose more than one mood
- The movies are limited to 5 choices per mood

**Project scope note**
This prototype focuses on the main idea of the project: helping users choose a movie quickly by selecting their current mood. The aim is to demonstrate the core functionality in a simple and understandable way.i may make it more functional and add more wider of moveies to choose from in the future
