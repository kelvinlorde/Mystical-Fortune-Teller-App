Build a Mystical Fortune Teller App where users can input their name, get a randomized 3-card tarot reading, calculate their daily "Cosmic Luck Score," and search through a library of possible fortunes.


Requirements Checklist

1. The Layout (HTML/CSS)
Create a webpage with a dark, mystical theme (e.g., purple/black backgrounds, glowing text, gold accents).
Add a form where users type their Name and select their Zodiac Sign from a dropdown list.
Create a dedicated container called the "Destiny Zone" where the results will be printed.
2. The Data Structure (JS Arrays & Variables)
Create a main array called fortunes containing at least 8 different fortune strings (e.g., "A great financial wind blows your way", "Beware of a trickster hiding behind a smile", "An unexpected email will alter your week").
Create another array called pastReadings which starts completely empty.
3. Core Feature 1: The Destiny Teller (Conditionals & Operators)
When the user clicks a "Reveal My Fate" button, your script must:
Validate that the user actually typed a name. If the name is blank, use a Conditional Statement (if/else) to alert them to input their name.
Calculate a random "Cosmic Luck Score" from 1 to 100.
Use a Ternary Operator to determine if their luck is good or bad. If the score is above 50, set a variable status to "Blessed". If below 50, set it to "Cursed".
Display a personalized summary on the screen:
4. Core Feature 2: The 3-Card Tarot Spread (Array Methods)
When the fate is revealed, pull a "Tarot Reading" using their list of fortunes:
Use array indexing or a randomized method to pick 3 distinct fortunes from the fortunes array.
Dynamically display these 3 fortunes as "Cards" on the screen using JavaScript DOM manipulation.
Use pastReadings.push() to save this session's reading to your history array so the user doesn't lose it.
5. Core Feature 3: The Fortune Archive Search (Array Methods)
Add an advanced section at the bottom of the page titled "Explore the Cosmos".
Add a search text input field and a "Search" button.
When clicked, use array.find() combined with string.includes() to let the user search for a keyword (like "wind" or "email") inside the fortunes array.
Bonus Challenge: Ensure the search works even if the user types in lowercase or uppercase!
Add a "Sort" button that uses array.sort() to sort the text archive alphabetically on the screen.

Happy Hacking!!!
Push to github and submit your repo link by !2:45