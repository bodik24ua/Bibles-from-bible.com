# Bibles from bible.com

A collection of SQLite Bible translations sourced from bible.com (YouVersion).

**Find a Bible translation or language you need**
   # *   [**Click here to search for a Bible translation**](https://github.com/bodik24ua/Bibles-from-bible.com?search=1)

## Features

*   **Pure SQLite Format**: Simple, file-based databases that are easy to use.
*   **Well-Indexed**: Tables are indexed for efficient querying by book, chapter, and verse.
*   **Rich Metadata**: Includes publisher and version information.
*   **Standardized Book Names**: Each translation includes:
    *   Original language short, abbreviation, and long names for books.
    *   Shortened English book abbreviations based on the USFM (Unified Standard Format Markers) (e.g., `GEN`, `EXO`).

## Limitations

These databases are designed for direct lookups and do not include advanced search features out-of-the-box. Application-level logic is required for the following:

*   **No Book Name Aliases**: Does not support alternative or shorthand book names (e.g., mapping "gen" or "gn" to "Genesis").
*   **No Lemmatization**: The text is stored as-is, without word stemming or root word analysis.
*   **No Full-Text Search**: The databases are not optimized with an FTS index for fast, word-based searches.
*   **No Reference Parsing**: Does not include a parser for complex queries like `"John 3:16-18"`.

## TODO

The following features are planned to releases in the new repository:

**These changes are designed to significantly improve the search experience in future applications:**

*   [ ] Add support for book name aliases.
*   [ ] Implement lemmatization for root word analysis.
*   [ ] Provide versions with a pre-built Full-Text Search (FTS5) index.
