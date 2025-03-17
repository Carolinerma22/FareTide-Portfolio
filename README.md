# FareTide-Portfolio
GCU CST-452 Assignment
# FareTide README Content

## Project Overview
FareTide helps users decide the best time to buy airline tickets. It combines real-time flight data with past fare trends to predict when prices will be lowest.

## Features
- Search for flights using trip details.
- View live flight results with prices.
- Get fare predictions: best date to buy and possible savings.
- See flight details.
- Click to book on external websites.
- Share flight links.

## Technology Used
- Backend: Python Flask
- Frontend: ReactJS
- Machine Learning: scikit-learn
- Data: CSV files (historical) and Skyscanner API (live data)

## How It Works
1. User searches for flights.
2. Backend gets real-time data from Skyscanner API.
3. ML model gives best date to buy and savings.
4. Frontend shows results and predictions.
5. User can view details, share, or book flight.

## Installation
1. Set up Python and Flask backend.
2. Set up React frontend.
3. Add Skyscanner API key in `.env` file.
4. Run backend and frontend locally.

## Demo Video

**DUE TO ISSUES VIDEO IS SPLIT INTO TWO PARTS. PLEASE WATCH BOTH TO SEE FULL CONTENT**

WATCH FIRST! Presentation Youtube Video Link: 
https://youtu.be/qGCMDvGbpyU?si=tTBMzQuPhdEaAhlM

WATCH SECOND! Demo Loom Video Link: https://www.loom.com/share/bca4ac38e8b1455ab89eb34705d665ec?sid=a4ae15d2-755e-4b64-914e-75d501b5fed9

## Other Links
Github Link: Private Repo – contact via Halo messages or Carolinerma@gmail.com for access

Jira Task Management Platform Link: Contact via Halo messages or Carolinerma@gmail.com for access.


## Known Issues/bugs
- Incomplete: NO styling, no prediction feature, no filtering results, some missing headers and data, no logo.
- CAPTCHA-triggered API access block - skyscanner API refuses requests.
- Reorganize and take advantage of component files.
- Round-trip booking agent results produce only for out-bound leg.
- Adjusted sitemap/file structure to remove final purchaseoptionspage.js –> replaced with repeating specificflightpage.js.



## Future Plans
- Complete all features and styling. 
- Evolve into a Chrome extension. 
  Iintegrating FareTide tool into employee portals.
- Compliant to ADA standards (Accessible).
- Compliant with legal standards and licensing. 
- Tested for security.
- Base fare prediction on additional factors. 
- Collect our own flight historical data for all routes and dates.
- Create our own api and databases of current/live flight fares.



## Contact
Caroline Macauley  
Email: carolinerma@gmail.com 

