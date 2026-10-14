# Seen Live

A wall of ticket stubs for every musician I've seen live.

## Adding someone

1. Open `artists.js` on GitHub and click the pencil (edit) icon.
2. Add a line at the bottom of the list, before the `];`:

   ```js
   { name: "Artist Name" },
   { name: "Artist Name", times: 2 },
   { name: "Artist Name", where: "Festival 2027" },
   ```

   `times` adds a "SEEN ×2" stamp; `where` prints on the ticket. Both are optional.
3. Commit. The page updates in a minute or so.

If you've seen someone again, just bump their `times` number.

## Hosting

Settings → Pages → Deploy from branch → `main` / root.
