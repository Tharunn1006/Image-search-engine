An Image Search Engine web app built using HTML, CSS, and JavaScript, integrated with the Unsplash API.
This project allows users to search for high-quality images by keyword and view them directly on the page. Users can also load more results using the “Show More” button, thanks to API pagination.

*) Features
->Search for any keyword (e.g., “nature”, “cars”, “animals”)

->Fetch real-time image results using the Unsplash API

->“Show More” button to load additional images (pagination support)

->Clickable images that open the original photo on Unsplash

->Responsive and minimal design with custom styling in CSS

*) Tech Stack
HTML5 – Structure of the webpage
CSS3 – Styling and layout
JavaScript (ES6) – Functionality and API handling
Unsplash API – Provides access to high-quality, free images

*) How It Works
1)The user enters a search term in the input box.
2)JavaScript captures the input and sends a fetch() request to the Unsplash API.
3)The API returns a JSON response containing image data.
4)The app dynamically creates image elements (<img>) and displays them on the page.
5)Clicking “Show More” fetches and displays the next set of images.
