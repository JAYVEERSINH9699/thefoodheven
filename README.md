# The Food Haven — standalone static website

This rebuild contains standalone HTML pages. There are no `fetch()` calls and no dependency on Live Server. Double-click `index.html` to open the site.

## Demo admin
- Email: admin@foodhaven.com
- Password: admin123

## Demo customer
- Email: riya@example.com
- Password: demo123

Data is stored in browser localStorage. Unsplash images and the OpenStreetMap embed require an internet connection to load their remote content, but the HTML/JS pages themselves do not require a web server.

For production, replace localStorage authentication with a real backend, hashed passwords, server-side authorization and a database.
