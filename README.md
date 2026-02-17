Challenges Faced During Development

1. Authentication Setup

Setting up Google login with Supabase was harder than expected.
I had to configure the OAuth consent screen, add the correct redirect URLs, and manage the client ID and secret. Small mistakes in the callback URL caused login failures, so understanding how the OAuth flow works and debugging those issues took time.

2. Managing Bookmark State

Handling bookmark data across the app required careful state management.
I needed to make sure the UI stayed in sync with the database, avoid unnecessary re-renders, and ensure the bookmark list updated immediately when a user added or deleted a bookmark. Getting this smooth user experience working consistently was challenging.
