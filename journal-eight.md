<h1># LJ Code 301 - Journal 8</h1>

page.js is middleware that listens for us to hit routes on the client side from our html. It defines a route mapping path to callbacks. The callbacks are invoked by two arguments... context and next.

This is really great to understand. I'm so brain dead most of the time. Reviewing our screen caps, I understand this much better now.

page('/books/:book_id', ctx => app.Book.fetchOne(ctx, app.bookView.initDetailPage));
