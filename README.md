# ConTracker - Anime & Cosplay Convention Calendar

A simple, clean website to track upcoming anime and cosplay conventions worldwide.

## Features

- **Clean Design**: Minimalist black and white interface
- **Country Search**: Filter events by country
- **Event Images**: Placeholder images for each convention
- **Responsive**: Works on desktop and mobile devices
- **Chronological Listing**: Events sorted by date

## Usage

1. Open `index.html` in your web browser
2. Browse all upcoming events or search by country
3. Click "More information" links to visit event websites

## Project Structure

```
contracker/
├── index.html          # Main website file
├── README.md          # Project documentation
├── images/            # Convention images
│   ├── animexpo-2025.jpg
│   ├── nordic-cosplay.jpg
│   ├── manga-festival.jpg
│   └── ...
└── data/
    └── events.js      # Event data (for future expansion)
```

## Adding Images

1. **Create an `images/` folder** in your project directory
2. **Add your convention images** (recommended formats: JPG, PNG, WebP)
3. **Update the image paths** in your event data:

```javascript
{
    id: 1,
    name: "AnimeXpo 2025",
    // ... other fields
    image: "images/animexpo-2025.jpg"  // Local path
}
```

## Customization

To add your own events, update the `eventsData` array in `index.html` with:

```javascript
{
    id: 1,
    name: "Convention Name",
    date: "2025-MM-DD",
    endDate: "2025-MM-DD", // Optional for multi-day events
    city: "City Name",
    country: "Country Name",
    venue: "Venue Name",
    description: "Event description",
    website: "https://event-website.com",
    image: "https://path-to-image.jpg" // Or placeholder URL
}
```

## Future Enhancements

- Connect to external APIs for event data
- Add event registration/ticket links
- Implement user favorites
- Add calendar export functionality
- Include event categories and tags

## License

This project is open source and available under the MIT License.