
=============
API Reference
=============

``GET /api/quotes``

   **Description:** Retrieve all quotes from the database.

   **Responses:**
     - 200: List of quotes in JSON.

``GET /api/quotes/{limit}``

   **Description:** Fetch a number of random quotes.

   :param limit: Number of quotes to return

   **Responses:**
     - 200: List of quotes
     - 404: No quotes found

``GET /api/quotes/{limit}/{movie}``

   **Description:** Fetch a number of quotes from the specified movie.

   :param limit: Number of quotes
   :param movie: Movie title

   **Responses:**
     - 200: List of quotes
     - 404: No quotes found

``GET /api/quotes/{movie}``

   **Description:** Get all quotes from the specified movie.

   :param movie: Movie title

   **Responses:**
     - 200: List of quotes
     - 404: No quotes found
