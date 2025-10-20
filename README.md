# Bibles from bible.com

SQLite Bible translations from bible.com (YouVersion).

## Features

*   **Pure SQLite Format**: Simple, file-based databases that are easy to use.
*   **Well-Indexed**: Tables are indexed for efficient querying by book, chapter, and verse.
*   **Rich Metadata**: Includes publisher and version information.
*   **Standardized Book Names**: Each translation includes:
    *   Original language short, abbreviation, and long names for books.
    *   Standard English book abbreviations based on the USFM (Unified Standard Format Markers) (e.g., `GEN`, `EXO`).

## Limitations

*   **No Aliases**: Does not include shorthand book name aliases (e.g., for quick search , `"gen 1 1"`).
*   **No Lemmatization**: The text is stored as-is, without word stemming or root word analysis.
*   **No Full-Text Search**: The databases are not optimized with an FTS index for fast, word-based searches.
*   **No Reference Parsing**: Does not include a parser for complex queries like `"John 3:16-18"`.

## TODO

The following features are planned for future releases:

*   [ ] Add support for book name aliases.
*   [ ] Implement lemmatization for root word analysis.