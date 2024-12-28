TravelSpace - A Travel Booking Website
## Description
TravelSpace is a comprehensive travel website designed to make booking flights, tour packages, and other travel-related services easy and convenient.
The platform allows users to browse available travel packages, book flights, and manage their travel bookings. It also includes user authentication features to personalize the experience for each traveler.

## Project Structure
The project is built using Django, and the main folder of the project is `project3`, which contains several subfolders and Django apps:

- **Templates**: The folder that contains the front-end templates (HTML, CSS, etc.) for the website.
- **Users**: A Django app responsible for handling user authentication and registration.
- **travel_website**: The main app for displaying the homepage and other static pages of the website.
- **packages**: An app dedicated to managing travel tour packages that users can book.
- **bookings**: The app for managing flight and tour bookings, where users can book travel services.

## Static Files

The `static/` folder contains all the assets that are used by the front-end of the website. It includes:

- **Images**: Logos, banners, and other graphical elements.
- **CSS**: Styling files for the website layout and design.
- **JavaScript**: Scripts that enable dynamic behavior on the website, such as form validation, interactivity, and dynamic updates.


### Usage

- The **CSS** files are linked within the HTML templates to style the website.
- The **JavaScript** files are used for dynamic content and client-side functionality.
- The **images** are used for branding, icons, and other visual elements on the website.

These static files are essential for the proper functioning and appearance of the TravelSpace website. Django will automatically serve these files during development, but for production, they should be managed using a static file server.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Amaljith26/TravelSpace---Travel-Website.git

2. Navigate to the project directory:
   cd project3

3. Install the required dependencies:
   pip install -r requirements.txt

4. Set up the database (run migrations):
   python manage.py migrate

5. Create a superuser for admin access (optional):
   python manage.py createsuperuser

6. Run the Django development server:
   python manage.py runserver

Acknowledgments

Special thanks to the Django community for providing such a powerful framework.
