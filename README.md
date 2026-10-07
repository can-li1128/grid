# Grid Design for a Theme Book List #
- index.html is a self-contained .html that has html, css, and javascript.
- index.html reads books_enriched.json. When use this HTML code, replace file name in line 319 with your own JSON file that has the same elements.
- books_enriched.json contains Syndetics img_urls, permalinks, subjects, and description/abstract from PNX data (returned from a Primo Search API call)

# Display with no permalinks
- Run https://can-li1128.github.io/grid/grid_no_links to display just the cover images (file is grid_no_links.html)
- grid_no_links.html reads california-books.xlsx. When use this HTML code, replace file name in line 201 with your own Excel file that has the same columns.
