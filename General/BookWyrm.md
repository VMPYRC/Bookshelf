---
created: 2025-07-20
modified: 2025-07-20
description: Resources for BookWyrm
aliases: 
tags:
  - Notes
  - Book-Tracker
---

# Shelves

|  Type   |       Name        | Note                                                                                                | Shelf Description                                                                                  |
| :-----: | :---------------: | --------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- |
| Default | Currently Reading | - Ongoing<br>- In Progress<br>- Active<br>- Reading                                                 | Ongoing ✨ In Progress ✨ Active ✨ Reading                                                        |
| Default |      To Read      | - Plan to Read, Read Next, Up Next<br>- Upcoming, Unreleased<br>- Want to Read, Don't Own, Wishlist | Plan to Read - Read Next - Up Next ✨ Upcoming - Unreleased ✨ Want to Read - Don't Own - Wishlist |
| Default |       Read        | - Completed, Finished<br>- Re-Read                                                                  | Completed - Finished ✨ Re-Read                                                                    |
| Default |  Stopped Reading  | - On Hold, Stalled, Delayed, Paused<br>- Abandoned, Dropped                                         | On Hold - Stalled - Delayed - Paused ✨ Abandoned - Dropped                                        |

# Editing Books

|       Section       |         Type         | Notes                                                     | Example                                                                                        | Example            |
| :-----------------: | :------------------: | --------------------------------------------------------- | ---------------------------------------------------------------------------------------------- | ------------------ |
|      Metadata       |        Title         |                                                           | The Hobbit                                                                                     |                    |
|      Metadata       |      Sort Title      | lowercases, remove The                                    | The Hobbit ➡️ hobbit                                                                           |                    |
|      Metadata       |       Subtitle       | usually the text after the colon `:`                      | or There and Back Again                                                                        |                    |
|      Metadata       |     Description      |                                                           |                                                                                                |                    |
|      Metadata       |        Series        |                                                           |                                                                                                |                    |
|      Metadata       |    Series number     |                                                           |                                                                                                |                    |
|      Metadata       |      Languages       |                                                           | English                                                                                        |                    |
|      Metadata       |       Subjects       | Genres, Tags, Themes                                      |                                                                                                |                    |
|     Publication     |      Publisher       |                                                           |                                                                                                |                    |
|     Publication     | First published date |                                                           |                                                                                                |                    |
|     Publication     |    Published date    |                                                           |                                                                                                |                    |
|       Authors       |     Add Authors      |                                                           |                                                                                                |                    |
|        Cover        |     Upload cover     |                                                           |                                                                                                |                    |
|        Cover        | Load cover from URL  |                                                           |                                                                                                |                    |
| Physical Properties |        Format        | Audiobook, eBook, Graphic novel, Hardcover, Paperback<br> |                                                                                                |                    |
| Physical Properties |    Format Details    | See the next section: [[BookWyrm#Format Details]]         |                                                                                                |                    |
| Physical Properties |        Pages         |                                                           |                                                                                                |                    |
|  Book Identifiers   |       ISBN 13        | 13 numbers on the copyright page, or the back cover       | 9780307120007                                                                                  |                    |
|  Book Identifiers   |       ISBN 10        | 10 numbers on the copyright page, or the back cover       | 0307120007                                                                                     |                    |
|  Book Identifiers   |    Openlibrary ID    | https://openlibrary.org/                                  | https://openlibrary.org/books/OL9443250M/Pat_the_Bunny                                         | OL9443250M         |
|  Book Identifiers   |    Inventaire ID     | https://inventaire.io/                                    | https://inventaire.io/entity/isbn:9780307120007                                                | isbn:9780307120007 |
|  Book Identifiers   |    Goodreads key     | https://www.goodreads.com/search?q=                       | https://www.goodreads.com/book/show/13532212-pat-the-bunny                                     | 13532212           |
|  Book Identifiers   |     OCLC Number      | https://search.worldcat.org/                              | https://search.worldcat.org/title/621768522                                                    | 621768522          |
|  Book Identifiers   |         ASIN         | https://www.amazon.com/                                   | https://www.amazon.com/Pat-Bunny-Touch-Feel-Book/dp/0307120007                                 | 0307120007         |
|  Book Identifiers   |     Audible ASIN     | https://www.audible.com/                                  | https://www.audible.com/pd/Harry-Potter-and-the-Chamber-of-Secrets-Book-2-Audiobook/B017V4IWVG | B017V4IWVG         |
|  Book Identifiers   |       ISFDB ID       | https://www.isfdb.org/                                    | https://www.isfdb.org/cgi-bin/title.cgi?69917                                                  | 69917              |

## Titles

- Manga Title Name, Vol. 01: Name of the Volume
- Light Novel Title Name, Vol. 01: Name of the Volume
- Manga Title Name [Manga] Vol. 01: Name of the Volume
- Light Novel Title Name [Light Novel] Vol. 01: Name of the Volume

## Format Details

|                        Format                         | Types                                                                                                                                                                                                                                                                                                                                                                              | Example                                              |
| :---------------------------------------------------: | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------- |
|                       Audiobook                       | - CD<br>- Record<br>- Cassette Tape<br>- Digital File (MP3, AAC)<br>- Streaming Service (Spotify, Audible, Libby)                                                                                                                                                                                                                                                                  | - 9h 2 min, Narrated by Narrator Name, Narrator Name |
|                         eBook                         | - EPUB<br>- MOBI<br>- AZW3<br>- PDF<br>- HTML<br>- Digital comics (CBZ, CBR)                                                                                                                                                                                                                                                                                                       |                                                      |
|                     Graphic novel                     | - Traditional bound comics (softcover/hardcover)<br>- Webcomics (collected editions)<br>- Manga (Tankōbon, Omnibus)                                                                                                                                                                                                                                                                |                                                      |
| Hardcover<br>Hardback / Hardbound / Hbk<br>Case-bound | - Board Book (sturdy pages for toddlers, often interactive)<br>- Dust jacketed hardcover (removable paper cover for protection and aesthetics)<br>- Casewrap (printed cover directly on the hardcover)<br>- Library binding (reinforced for durability)<br>- Collector's edition (deluxe materials, gilded pages, slipcases)<br>- Textbook hardcover (academic/professional books) | - Board Book                                         |
|           Paperback<br>Softcover / Softback           | - Mass market paperback (small, cheaper, portable)<br>- Trade paperback (larger, better quality paper)<br>- Flexibound (between paperback and hardcover, flexible cover)<br>- Spiral-bound (notebook-style, easy to lay flat)<br>- Print-on-demand paperback (self-published, indie)<br>- Zine (small, DIY, self-published booklets)                                               |                                                      |
|                   eBook, Paperback                    | - Academic / Scholarly Journal<br>- Magazine                                                                                                                                                                                                                                                                                                                                       |                                                      |

# Managing Editions

| Issue                                                  | My Solution                                            |
| ------------------------------------------------------ | ------------------------------------------------------ |
| Wrong Editions in the same Work                        | Create a new book: https://bookwyrm.social/create-book |
| When asked if "this is an edition of an existing work" | Choose "This is a new work"                            |

# Resources

|       Type        | Link                                   | Example                                                 |
| :---------------: | -------------------------------------- | ------------------------------------------------------- |
| Year in the Books | `/user/[USERNAME]/[YEAR]-in-the-books` | https://bookwyrm.social/user/USERNAME/2025-in-the-books |
|    Yearly Goal    | `/user/[USERNAME]/goal/[YEAR]`         | https://bookwyrm.social/user/USERNAME/goal/2025         |
|   Create a Book   | `/create-book`                         | https://bookwyrm.social/create-book                     |

- https://github.com/bookwyrm-social/bookwyrm
- https://wiki.librarything.com/index.php/Media_and_format_definitions
- https://wiki.librarything.com/index.php/The_LibraryThing_Media_Taxonomy
- https://wikipedia.org/wiki/Book_size
- https://wikipedia.org/wiki/Bookbinding
