# form-master
# Plan Your Movie Night

This is a simple web application to plan your movie night. Users can select their preferred language, movie, snacks, and date and submit the form to view their planned details.

## Features

- Select a movie from multiple languages (English, Hindi, Kannada).
- Enter your name, email, preferred date, and snacks.
- Dynamically populate movies based on the selected language.
- Submit the form and view the entered details.

## Requirements

- XAMPP (or any other local server environment with PHP support).
- Web browser.

## File Structure

```
form-master/
├── index.html      # Main HTML form file
├── style.css       # Styling for the form
├── script.js       # JavaScript for dynamic movie population
├── submit.php      # Backend PHP script to handle form submissions
```

## Setup Instructions

1. **Download and Install XAMPP:**
   - If not already installed, download XAMPP from [Apache Friends](https://www.apachefriends.org/index.html) and install it.

2. **Place Files in the Server Directory:**
   - Copy the `form-master` folder to the `htdocs` directory of your XAMPP installation:
     ```
     C:\xampp\htdocs\form-master
     ```

3. **Start the Server:**
   - Open the XAMPP Control Panel and start the **Apache** service.

4. **Access the Application:**
   - Open your web browser and navigate to:
     ```
     http://localhost/form-master/index.html
     ```

5. **Test the Form:**
   - Fill out the form and submit it.
   - The `submit.php` script will display the submitted details.

## How It Works

1. **Dynamic Movie List:**
   - The JavaScript file (`script.js`) dynamically updates the list of movies in the dropdown based on the selected language.

2. **Form Submission:**
   - The form data is sent to `submit.php` using the POST method.
   - The PHP script sanitizes the input and displays the planned movie night details in a styled table.

## Example Output

After form submission, the user will see something like:

```
Your Movie Night Plan
----------------------
Your Name: John Doe
Email: john@example.com
Date: 2024-12-20
Selected Movie: Inception
Snacks: Popcorn, Nachos, Coke
```

## License

This project is open-source and available under the MIT License.

