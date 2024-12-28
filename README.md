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

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Amaljith26/TravelSpace.git

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
