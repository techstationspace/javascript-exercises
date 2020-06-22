# Find the Oldest

given an array of objects representing people with a birth and death year, return the oldest person.

## Hints
- You should return the whole person object, but the tests mostly just check to make sure the name is correct.
- this can be done with a couple of chained array methods, or by using `reduce`.
- One of the tests checks for people with no death-date.. use JavaScript's Date function to get their age as of today.

Run the tests by entering `npm run jest -- findTheOldest/findTheOldest.spec.js` in the terminal and watch it fail.