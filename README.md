## Filter Functionality

### Scenario Description:
The filter functionality allows users to refine their search results based on specific criteria such as price range, star rating, location, amenities, flight type (non-stop), and vehicle type. This helps users quickly find results that meet their preferences, improving their experience.

### Key Features:
- Filters for flights, hotels, and car rentals.
- Price range filter to choose between low, medium, and high price options.
- Star rating filter for hotels and user ratings for services.
- Location-based filters for hotels, flights, and car rentals.
- Additional filters based on specific criteria like vehicle type (SUV, sedan, etc.) and flight types (non-stop, connecting).
  
### Functionality Flow:
1. User inputs search query (flight, hotel, or car rental).
2. Filter options are displayed based on the search type.
3. User selects filter criteria (price range, rating, amenities, etc.).
4. Search results are dynamically updated based on the selected filters.

### Example Use Cases:
- Filtering flights by price range: Users can narrow down flights to their budget.
- Filtering hotels by star rating: Users can choose hotels based on their preferred rating (1-5 stars).
- Filtering car rentals by vehicle type: Users can select the type of car (SUV, sedan, etc.) they prefer.

### Expected Behavior:
- The filters should return results that strictly match the selected criteria.
- Multiple filters can be applied simultaneously.
- When no results match the filter criteria, a "No Results Found" message should be displayed.
- Filter results should be updated dynamically without needing to reload the page.
