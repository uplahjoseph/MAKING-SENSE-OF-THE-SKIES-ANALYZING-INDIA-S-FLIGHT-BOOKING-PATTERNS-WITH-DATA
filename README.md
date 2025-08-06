# MAKING-SENSE-OF-THE-SKIES-ANALYZING-INDIA-S-FLIGHT-BOOKING-PATTERNS-WITH-DATA
## Introduction
India’s aviation industry is not only one of the fastest-growing in the world, but it is also a dynamic reflection of the nation’s economic aspirations, growing middle class, and technological transformation. With over 140 operational airports and a civil aviation market projected to become the third-largest globally by 2026, India’s skies are busier than ever. The post-liberalisation era ushered in a new phase for Indian aviation. From being dominated by state-owned carriers like Air India, the sector evolved with the entry of private players, including IndiGo, Vistara, SpiceJet, Go First, and AirAsia India. These airlines brought competition, innovation, and affordability to the masses. Today, low-cost carriers (LCCs) dominate the market, catering to a population increasingly willing to fly.
In the fiscal year 2023–24, Indian airports handled over 350 million passengers, with domestic travel accounting for nearly 75% of that number. Affordable ticketing, improved airport infrastructure, regional connectivity schemes like UDAN (Ude Desh ka Aam Nagrik), and the digitisation of the booking experience have all contributed to this aviation boom. Unlike Western markets, India’s domestic flyers are highly price-sensitive. Fare changes, especially those affected by class of travel, days-to-departure, or seasonal demand, can significantly influence consumer behaviour. Despite this, there’s a growing segment of premium travellers demanding higher service quality, leading to a strong Business Class presence among private full-service carriers like Vistara. The industry’s dual nature, balancing mass low-cost demand with an emerging appetite for luxury and comfort, makes it a goldmine for data analysis.
## Data Overview
For this project, I worked with a flight booking dataset scraped from a major travel website. They include the following; 
- Source and destination cities
- Departure and arrival times
- Flight duration
- Ticket prices
- Cabin class and number of stops
- Route
- Days before departure
  ## Data Source
  This dataset was sourced from Kaggle's Airline Dataset. The dataset captures detailed, date-wise information on airline operations across various Indian cities. It is meant for educational purposes only
  ## Objective
  To evaluate the current state, challenges, and opportunities in the Indian airline industry by analysing stakeholder dynamics, market trends, operational performance, and policy environment to inform strategic decisions, policy recommendations, or investment insights:
- Data Cleaning
- Interactive Dashboards
- Feature Engineering
- Consistent Formatting & Branding
  ## Data Cleaning
  The process began by sourcing Adidas’ sales data from Kaggle. Next came data cleaning, addressing the following:
  - Missing values
  - Correcting inconsistent formats
  - Eliminating duplicates
  - Standardising data categories, I added two new columns pertinent to this analysis, which are;
    - Route
    - Days before departure
  This step was essential to ensure the dataset was accurate, reliable, and ready for meaningful analysis
## Chart & Visualization
The dashboard includes the following visuals capturing the unity with the airline's operations in India
## 1. Total Flight by Frequency (Column Chart)
![Total Flight by Frequency](https://github.com/uplahjoseph/MAKING-SENSE-OF-THE-SKIES-ANALYZING-INDIA-S-FLIGHT-BOOKING-PATTERNS-WITH-DATA/blob/main/Total%20Flight%20by%20Frequency.png)
## 2. Total Flight by Time of Flight (Column Chart)
![Total Flight by Time of Flight](https://github.com/uplahjoseph/MAKING-SENSE-OF-THE-SKIES-ANALYZING-INDIA-S-FLIGHT-BOOKING-PATTERNS-WITH-DATA/blob/main/Total%20Flight%20by%20Time.jpeg)
## 3. Flight by City to City Traffic (Bar Chart)
![Flight by City to City Traffic](https://github.com/uplahjoseph/MAKING-SENSE-OF-THE-SKIES-ANALYZING-INDIA-S-FLIGHT-BOOKING-PATTERNS-WITH-DATA/blob/main/City%20by%20City%20Traffic%20.jpeg)
## 4. Flight by Class Usage Frequency (Pie Chart)
![Flight by Class Usage Frequency](https://github.com/uplahjoseph/MAKING-SENSE-OF-THE-SKIES-ANALYZING-INDIA-S-FLIGHT-BOOKING-PATTERNS-WITH-DATA/blob/main/Flight%20by%20Class%20%20Usage%20Frequency.jpeg)
## 5. Average Ticket Price by Route(Line Chart)
![Average Ticket Price by Route](https://github.com/uplahjoseph/MAKING-SENSE-OF-THE-SKIES-ANALYZING-INDIA-S-FLIGHT-BOOKING-PATTERNS-WITH-DATA/blob/main/Ticket%20by%20Route.jpeg)
## 6. Flight Class Fare Comparison(Doughnut Chart)
![Flight Class Fare Comparison](https://github.com/uplahjoseph/MAKING-SENSE-OF-THE-SKIES-ANALYZING-INDIA-S-FLIGHT-BOOKING-PATTERNS-WITH-DATA/blob/main/Flight%20ClassFare%20%20Comparison.jpeg)
## 7. Average Fare by Booking Window (Bar Chart)
![Average Fare by Booking Window](https://github.com/uplahjoseph/MAKING-SENSE-OF-THE-SKIES-ANALYZING-INDIA-S-FLIGHT-BOOKING-PATTERNS-WITH-DATA/blob/main/Fare%20by%20Booking%20Window.jpeg)
## Dashboard Overview
- I designed a fully interactive Excel dashboard that brings all charts together into one streamlined, cohesive view. Key highlights of the dashboard include:
- A clean, well-structured layout with consistent margins and spacing
- Clear typography and precise alignment to improve readability and visual flow
- Interactive slicers that allow users to filter data across multiple dimensions in real time
![Dashbboard](https://github.com/uplahjoseph/MAKING-SENSE-OF-THE-SKIES-ANALYZING-INDIA-S-FLIGHT-BOOKING-PATTERNS-WITH-DATA/blob/main/Dashboard.png)
## Tools Used
- Microsoft Excel: Utilised extensively for Data Cleaning, Analysis, and Dashboard creation.
- Adobe Colour: Employed for selecting a brand-consistent colour theme.
## File Included 
- ### ![MAKING-SENSE-OF-THE-SKIES-ANALYZING-INDIA-S-FLIGHT-BOOKING-PATTERNS-WITH-DATA](https://medium.com/@uplahjoseph/making-sense-of-the-skies-analyzing-indias-flight-booking-patterns-with-data-c49c479741a5)
## Insights 
### Observations.
- Vistara accounted for 42.6% of total flights, significantly leading over competitors.
- Morning flights made up 23.72% of total trips — the most preferred time slot.
- Delhi recorded the highest flight activity, with 20.44% of total departures.
- 68.85% of passengers booked Economy, reflecting strong price sensitivity.
- The Delhi–Mumbai corridor alone accounted for 5.1% of all flights.
- Business Class fares are on average 78.34% higher than Economy.
- Booking at least 11 days in advance led to fares up to 79.5% cheaper.
## Recommendations 
- Competing airlines should analyse Vistara’s route strategies, pricing, and service offerings to identify gaps and opportunities for market penetration or strategic collaboration.
- Airlines should increase capacity and frequency during morning hours, especially on high-demand routes, while ensuring minimal delays to capitalise on peak preferences.
- Airlines and airport authorities should prioritise infrastructure, staffing, and scheduling in Delhi to manage volume efficiently and maintain high service quality.
- Airlines should enhance the Economy Class experience (e.g., flexible fares, loyalty perks) and optimise fleet configurations to favour Economy seats without compromising profitability.
- Airlines should consider dynamic pricing, frequent flyer incentives, and schedule optimisation on this high-volume route to boost both load factor and profitability.
- Introduce “Premium Economy” or hybrid offerings for travellers seeking some business-class benefits at a lower price point, and improve value propositions in Business Class to justify the premium.
- Airlines can promote early bird discounts and educate passengers on fare advantages to improve forecasting, reduce last-minute fare volatility, and boost advance cash flow.

### Beyond the insights, this project was a major step forward in my growth as a data analyst.
- I gained hands-on experience in cleaning and structuring messy, raw data, transforming it into something reliable and analysis-ready.
- I discovered the real power of slicers, and how they can turn a static report into an interactive tool.
- I also deepened my understanding of dashboard design—learning how consistency, clarity, and layout can elevate the impact of your visuals. Most importantly, I came to appreciate that Excel isn’t just a spreadsheet tool—it’s a surprisingly powerful (and even enjoyable) platform for serious data analysis and storytelling.
