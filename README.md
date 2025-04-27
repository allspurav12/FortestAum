# Pin Code & Place Search

This is a simple web application that allows users to search for a place using a pin code or find a pin code by entering a place name. The application uses the [Postal Pincode API](https://api.postalpincode.in/) to fetch data and is designed to be mobile-friendly.

## Features
- Search for a place (post office, district, state) by entering a 6-digit Indian pin code.
- Search for a pin code by entering a place name (e.g., post office name).
- Mobile-friendly design with responsive layout.
- Input validation to ensure only numbers are entered for pin codes.
- Displays "No results found" when no data is available.
- Includes an additional image section.

## Live Demo
You can view the live demo of this project on GitHub Pages:  
[https://<your-username>.github.io/<repo-name>/](https://<your-username>.github.io/<repo-name>/)

## How to Use
1. **Clone or Download the Repository**:
   - Clone this repository: `git clone https://github.com/<your-username>/<repo-name>.git`
   - Or download the ZIP file and extract it.

2. **Open Locally**:
   - Open `index.html` in a web browser to test the application locally.
   - Alternatively, use a local server (e.g., Live Server in VS Code) for a better experience.

3. **Deploy on GitHub Pages**:
   - Create a new repository on GitHub.
   - Upload all files (`index.html`, `style.css`, `script.js`, `README.md`) to the repository.
   - Go to the repository settings, scroll to "GitHub Pages", and enable it by selecting the `main` branch.
   - Your site will be live at `https://<your-username>.github.io/<repo-name>/`.

4. **Test the Application**:
   - Select "Search by Pin Code" and enter a valid 6-digit Indian pin code (e.g., `700001`) to get the place name.
   - Select "Search by Place" and enter a post office name (e.g., `Princep Street`) to get the pin code.

## Files
- `index.html`: The main webpage structure with logo, search section, image, and footer.
- `style.css`: Styling for the webpage, including mobile responsiveness.
- `script.js`: Logic for fetching pin code and place data using the Postal Pincode API.
- `README.md`: Documentation for the project (this file).

## Screenshots
### Desktop View
![Desktop View](https://via.placeholder.com/800x400.png?text=Desktop+View)

### Mobile View
![Mobile View](https://via.placeholder.com/400x600.png?text=Mobile+View)

*(Replace the placeholder URLs with actual screenshots of your project if available.)*

## Dependencies
- No external libraries or frameworks are required.
- The project uses the [Postal Pincode API](https://api.postalpincode.in/) for fetching pin code and place data.

## Notes
- The Postal Pincode API is free and does not require an API key.
- For place-to-pin code searches, enter the post office name (e.g., `Princep Street` for Kolkata).
- Ensure you have a stable internet connection for API calls.
- The application only accepts 6-digit pin codes for Indian postal codes.

## Credits
- **Design & Developed By**: Sourav Das
- **Logo**: AUM Express (as provided in the project)
- **Additional Image**: IMG-2743 (uploaded to ImgBB)

## License
This project is licensed under the MIT License. You are free to use, modify, and distribute it as per the license terms.

---
Feel free to contribute to this project by submitting pull requests or reporting issues!
