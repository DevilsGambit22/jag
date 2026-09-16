TAMUSA CHESS CLUB - GITHUB PAGES SIDEBAR

Upload all files and the assets folder to the root of your GitHub Pages repository.

FILES
- index.html: sidebar layout, Chess.com PubAPI new-member board, and quick links.
- announcements.yml: important announcements.
- tournaments.yml: tournament information.
- staff.yml: staff roster.
- assets/tamusa-chess-club.jpg: supplied TAMUSA Chess Club logo.

EDITING YAML
Keep the field names as provided. Duplicate an entire "-" entry to add another item.
Set active: false to hide an item without deleting it.

NEW JAGUARS
The five newest club members are loaded automatically from the public Chess.com club API. Their public avatar and highest current Rapid/Blitz/Bullet rating are then loaded from the public player endpoints.

SCROLLING
The GitHub page is intentionally narrow and vertically scrollable. When embedded at a fixed height on Chess.com, the sidebar itself provides the scrolling surface.
