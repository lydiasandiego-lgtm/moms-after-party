Mom's After Party — Firebase shared editing

This version makes Status, Score, Description, and Notes/Comments shared through Cloud Firestore.

IMPORTANT:
1. Upload all files to the GitHub repository root and replace index.html.
2. Firestore must allow reads/writes for your guests. During setup, Test Mode is sufficient temporarily.
3. On first load in your existing browser, old locally saved Status/Score/Notes are automatically migrated to Firestore if that restaurant does not already have shared data.
4. After migration, everyone viewing the same site sees updates in real time.

Collection used: restaurants
