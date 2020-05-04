## Answering Business Queries using SQL

In this project we are using the Chinook database, provided as a SQLite database file called chinook.db.

There are 11 tables in the chinook database.

   *  `employees` table stores employees data such as employee id, last name, first name, etc. It also has a field named ReportsTo to specify who reports to whom.
   * `customers` table stores customers data.
   *  `invoices` & `invoice_items` tables: these two tables store invoice data. The invoices table stores invoice header data and the invoice_items table stores the invoice line items data.
   *  `artists` table stores artists data. It is a simple table that contains only the artist id and name.
   *  `albums` table stores data about a list of tracks. Each album belongs to one artist. However, one artist may have multiple albums.
   *  `media_types` table stores media types such as MPEG audio and AAC audio files.
   *  `genres` table stores music types such as rock, jazz, metal, etc.
   * `tracks` table stores the data of songs. Each track belongs to one album.
   *  `playlists` & `playlist_track` tables: playlists table store data about playlists. Each playlist contains a list of tracks. Each track may belong to multiple playlists. The relationship between the playlists table and tracks table is many-to-many. The playlist_track table is used to reflect this relationship.
 

The objective of this project is to use SQL queries to analyse the following:

1. The best selling genre in USA
1. Performance of the sales representative
1. Sales by country
1. Purchase of albums vs purchase of individual tracks
1. Which artist is used in the most playlists?
1. How many tracks have been purchased vs not purchased?
1. Is the range of tracks in the store reflective of their sales popularity?
1. Do protected vs non-protected media types have an effect on popularity?
