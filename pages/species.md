tags:: species, class
icon:: 🌈

- [[plants]]: hundreds of species in [[citadel genesis]] and [[batuka]]
- [[animals]]: dozens of species in [[citadel genesis]] and [[batuka]]
- [[fungi]]: dozens of species in [[batuka]]
-
- system of tagging
	- abundance: abundant, limited, trial, none, gone
	- supply: next-month, next-quarter, next-year, later, no
	- margin: high, mid, low, none
	- seeds: amount
	- seedling: amount
	- autonomy: staple, support, revenue, none, external
-
-
- ## [[species/all]]
- {{query (and (page-tags [[species]]) (not (page-tags [[research]])))}}
  query-sort-by:: page
  query-sort-desc:: false
  query-properties:: [:page :alias]
- {{query (and (page-tags [[species]]) (page-tags [[research]]))}}
  query-sort-by:: page
  query-sort-desc:: false
  query-properties:: [:page :alias]