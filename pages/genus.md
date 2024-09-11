## selected genus for [[citadel genesis]]
- {{query (and (page-tags [[genus]]) (not (page-tags [[class]])) (not (page-tags [[research]])))}}
  query-sort-by:: page
  query-sort-desc:: false
  query-properties:: [:page :alias]
- ## genus to research
- {{query (and (page-tags [[genus]]) (not (page-tags [[class]])) (and (page-tags [[research]])))}}
  query-properties:: [:page :alias :tags]
-