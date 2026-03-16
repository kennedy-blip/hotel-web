Urban Stay Hotel Website
A modern, responsive, and fully functional hotel booking landing page. This project features a sleek user interface built with Vanilla HTML5, CSS3, and JavaScript, integrated with external APIs to provide real-time data and enhanced user interactivity.

🚀 Features
Dynamic Room Listings: Fetches room data, pricing, and availability via a REST API.

Real-time Weather Integration: Displays current weather conditions for the hotel's location to help guests plan their stay.

Interactive Booking Form: Client-side validation for check-in/out dates and guest counts.

Responsive Design: Fully optimized for mobile, tablet, and desktop views using CSS Flexbox and Grid.

Glassmorphic UI: Modern design aesthetics with blurred backgrounds and smooth CSS transitions.

Live Map: Embedded location services to help guests find the property easily.

🛠️ Tech Stack
Frontend: HTML5, CSS3 (Custom Properties & Animations)

Scripting: Vanilla JavaScript (ES6+)

Data Fetching: Fetch API

External APIs: * OpenWeatherMap API (for local climate data)

Custom Mock API / JSON Placeholder (for room details)

📂 Project Structure
Plaintext
hotel-website/
├── assets/
│   ├── images/          # Optimized room and hero images
│   └── icons/           # SVG icons for amenities
├── css/
│   └── style.css        # Main stylesheet with responsive queries
├── js/
│   ├── api.js           # API fetch logic and async functions
│   └── main.js          # DOM manipulation and event listeners
├── index.html           # Main entry point
└── README.md
⚙️ Setup & Installation
Clone the repository:

Bash
git clone https://github.com/your-username/hotel-website.git
Navigate to the folder:

Bash
cd hotel-website
API Configuration:

Open js/api.js.

Replace YOUR_API_KEY with your actual OpenWeatherMap or booking engine API key.

Launch:

Open index.html directly in your browser or use a "Live Server" extension in VS Code.

📈 Future Enhancements
Payment Gateway: Integration with Stripe or PayPal for actual transactions.

User Auth: A dashboard for guests to manage their previous bookings.

Multi-language Support: i18n integration for international travelers.