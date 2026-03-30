# **Week 9 A6**

## How to run
Terminal - python3 -m http.server 4040
Browser Link - http://localhost:4040/

## Base state
query: "",
sortBy: "title-asc",
activeKind: "all",  showFavoritesOnly: false,
selectedId: null,
favorites: new Set(["echo", "tide"]),
items: [],
isLoading: false,
error: null,
lastLoadedAt: null,

## Derived state
Filtered Items 
Sorted Items
Visible Items
Kind Counts
Selected Item
Active Summary
Explanation