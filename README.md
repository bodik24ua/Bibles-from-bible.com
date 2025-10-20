# Bibles from bible.com

SQLite Bible translations from bible.com (YouVersion).

## Features

*   **Pure SQLite Format**: Simple, file-based databases that are easy to use.
*   **Well-Indexed**: Tables are indexed for efficient querying by book, chapter, and verse.
*   **Rich Metadata**: Includes publisher and version information.
*   **Standardized Book Names**: Each translation includes:
    *   Original language short, abbreviation, and long names for books.
    *   Standard English book names based on the USFM (Unified Standard Format Markers) standard.

## Limitations

These databases are designed for direct lookups and do not include advanced search features. Please be aware of the following:

*   **No Aliases**: Does not support shorthand book name aliases (e.g., "gen" for "Genesis", `"gen 1:1-5"`).
*   **No Lemmatization**: The text is stored as-is, without word stemming or root word analysis.