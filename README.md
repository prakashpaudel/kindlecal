# A simple website to show a calendar on a old kindle

# TODO
-[x] proof of concept: load calendar with some events as list and show on kindle
-[] format and style the content by day.
  -[x] format the date simply
  -[x] each day there is a game, have a header
  -[x] list all games for that day under that header
  -[x] format each game like: 2:30pm Arsenal v Liverpool
  -[x] style the content using css
-[] Refreshing
  -[] periodically refresh calendar incase date/time of game was changed
  -[] This shouldn't envolve reloading the website, because it's a local site, the server will be off once set up. Should be handled client side without server.
  -[] Once a day should be enough, test with a custom public calendar, changing a event time and seeing if it updates.
-[] Add multiple calendar support
  -[] Add champions league games calendar
  -[] be able to get events from both calendars and show in same list
    -[] maybe can combine calendars in google calendar, or atleast combine the api call to get multiple calendars at once
    -[] Otherwise, may not be feasible
  -[] update game format to specify which calendar the game is for. e.g. [epl], [champions league], [formula 1]
