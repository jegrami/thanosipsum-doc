======
Usage
======

Web Interface
-------------

Visit https://thanos-ipsum.onrender.com

- Select number of quotes and optionally filter by movie.
- Copy quotes to your clipboard with one click.

API Access
----------

Base URL: ``https://thanos-ipsum.onrender.com/api``

- ``/quotes``: fetch all quotes from the database
- ``/quotes/{limit}``: Fetch a specified number of quotes 
- ``/quotes/{limit}/{movie}``: Get a limited number of quotes from the specfied movie
- ``/quotes/{movie}``: Get all quotes from the specified movie

Example:

.. code-block:: bash

    curl https://thanos-ipsum.onrender.com/api/quotes/3/

    curl https://thanos-ipsum.onrender.com/api/quotes/3/endgame



