# book-organizer

This program demonstrates how to filter and sort an array of book objects in JavaScript.
Each book has three properties:

title – the name of the book

authorName – the author’s name

releaseYear – the year the book was released

The goal of the program is to:

Filter the books that were released in or before 1950

Sort the filtered books in ascending order by their release year

⚙️ How It Works

Array of Books – It starts with an array containing three book objects.

Filter Method (filter) – Selects only the books with releaseYear <= 1950.

Sorting Function (sortByYear) – Compares two books by their release year and returns:

-1 if the first book was released earlier,

1 if the first book was released later,

0 if both were released in the same year.

Sort Method (sort) – Orders the filtered books using the sortByYear function.

Console Output – Displays the filtered and sorted list of books.

📤 Output Example

After running the program, the console will show only the books published in or before 1950, arranged from oldest to newest.

💡 Concepts Used

Objects and Arrays

Array Methods: filter() and sort()

Comparison Logic in Sorting

Console Logging for Output
