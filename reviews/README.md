# Reviews Folder

This folder contains customer review files in JSON format.

## Adding New Reviews

To add a new review, create a new JSON file with the following structure:

```json
{
  "name": "Customer Name",
  "initials": "CN",
  "rating": 5,
  "text": "The review text goes here...",
  "date": "2024-09-28"
}
```

## Fields Explanation

- **name**: Full name of the customer
- **initials**: 2-letter initials for the avatar circle
- **rating**: Star rating from 1-5
- **text**: The review text (keep it concise and impactful)
- **date**: Date of the review (YYYY-MM-DD format)

## Current Process

Currently, reviews are loaded from the JavaScript array in index.html. To add new reviews:

1. Create a new JSON file in this folder
2. Add the review data to the `reviews` array in the `loadReviews()` function in index.html

## Future Enhancement

This system could be enhanced to automatically load all JSON files from this folder, making it truly dynamic without needing to update the JavaScript code.
