- {{query (and "high margin" (not (property :tags "unavailable")) (not (page-tags [[unavailable]])))}}
  query-sort-by:: page
  query-table:: true
  query-sort-desc:: false
  query-properties:: [:page]
- {{query (and "high margin" (page-tags [[unavailable]]))}}
  query-table:: true
  query-properties:: [:page]
-