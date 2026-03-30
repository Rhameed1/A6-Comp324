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

## Derived values
Filtered Items 
Sorted Items
Visible Items
Kind Counts
Selected Visible Item
Active Summary
Explanation

## Selectors
getSortedItems
getKindCounts(items) - reduce() implemented
getActiveSummary

## Composition
getFilteredItems() removes items that do not match the filters, getSortedItems() takes the result and puts it in order for getVisibleItems(). 
