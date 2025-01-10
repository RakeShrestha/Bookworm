# Bookworm

Bookworm is an iOS app built with SwiftUI and SwiftData that allows users to track books they like. The app lets users add books, rate them with custom star ratings, view book details, and manage their book collection efficiently.

## Overview

The Bookworm app demonstrates key SwiftUI concepts including:

- **Core Data Integration with SwiftData**: Using SwiftData to persist and manage book data.
- **Custom Components**: Creating custom UI components, such as a star rating system.
- **Text Input Handling**: Accepting multi-line text input via the `TextEditor`.
- **Data Management with SwiftData Queries**: Using `@Query` to fetch data and manage CRUD operations.
- **Dynamic Sorting and Deletion**: Sorting book entries using `SortDescriptor` and enabling deletion from lists.

### Key Concepts Covered:
- Creating books with SwiftData
- Adding a custom star rating component
- Building lists using `@Query`
- Showing detailed information for each book
- Sorting entries with `SortDescriptor`
- Deleting data from a SwiftData query
- Using alerts to trigger navigation programmatically

## Features

- **Add Books**: Add a new book to your collection by entering the book's title, author, genre, and a custom rating.
- **Rate Books**: Rate each book with a 1 to 5 star rating.
- **Book Details**: View detailed information about each book when tapping on it.
- **List of Books**: Display a list of books that you have added, with the option to sort by title or rating.
- **Delete Books**: Swipe to delete a book from your collection.
- **Sort Books**: Sort your book collection by title or rating.
