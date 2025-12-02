A fully functional Next.js 14 (App Router) project implementing secure authentication, protected routes, search, filtering, and paginated data listing using a dummy API.
This project demonstrates frontend architecture, state management, and clean UI/UX.

Authentication
Login using NextAuth Credentials Provider
API integrated with dummyjson.com/auth/login
Secured session handling with JWT
Redirects based on authentication
Protected dashboard route
Live search filtering
Case-insensitive matches
Works seamlessly with pagination
Multi-field filters
Filter + Search + Pagination compatible
Clear filter option included
Dynamic route-based detail pages
Complete data view
Clean & structured UI

app/
 ├─ api/
 │   └─ auth/[...nextauth]/route.js
 ├─ dashboard/
 │   └─ page.js
 ├─ login/
 │   └─ page.js
 ├─ page.js
 ├─ layout.js
 └─ provider.js

store/
 └─ useStore.js

public/

username: kminchelle
password: 0lelplR
