PART I - Bug fixes

1. Create a new branch for this test.
2. How would you ensure that everyone would use the same version of npm when running the app? (18.10.0) Why would this be important?
3. Create a new user and log in.
4. When you navigate to the New Article page, there's a visual bug. What is it and how would you fix it?
5. On the New Article page, there are errors. What are they and how would you fix them?

PART II - New feature

The application currently has the ability for users to "favorite" articles, and display the articles that they've favorited. We'd like to add a new page where users can see their posts that have been favorited, as well as how many times that article has been favorited.

1. Make a new route "/profile/{user}/favorited" that copies the layout of the existing articles pages (e.g., /profile/{user}) and shows up as a tab on the profile screen.
2. Add a new method to the Articles service that returns the user's articles filtered by whether they have favorites.
3. Display just the title and the number of favorites on the page (design is not super important, just make it look decent).

PART III - Enhancement

The application profile settings screen currently has no validation.

1. For frontend validation, please make all fields required.
2. The username field should require at least 3 characters.
3. The password field should meet basic security requirements.
4. The email field should be a valid email address.
