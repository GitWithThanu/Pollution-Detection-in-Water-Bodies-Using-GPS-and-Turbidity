 🌊 Pollution Detection in Water Bodies Using GPS and Turbidity Levels

This project focuses on detecting and visualizing water pollution levels in different water bodies using GPS location data and turbidity measurements. The system provides an interactive mapbased visualization to help identify polluted regions and support environmental monitoring and sustainability efforts.

 🎯 Problem Statement
Water pollution is a major environmental issue affecting ecosystems, public health, and water availability. Traditional monitoring methods are often slow and locationlimited. There is a need for a scalable, visual, and datadriven system to identify polluted water bodies efficiently.

 💡 Solution Overview
This project presents a webbased water pollution detection and visualization system that:
 Uses turbidity data to classify pollution levels
 Maps pollution geographically using GPS coordinates
 Provides realtime visual insights through markers and heatmaps
 Supports filtering, searching, and data export

 🛠️ Technologies Used
 HTML, CSS, JavaScript
 Leaflet.js – Interactive map visualization
 Leaflet Heatmap Plugin
 PapaParse.js – CSV data parsing
 OpenStreetMap – Map tiles
 CSV Dataset – Water quality parameters

 📊 Key Features
 🌍 Interactive map showing polluted water bodies
 🔴🟠🟢 Pollution classification (Low / Medium / High) based on turbidity
 🔍 Locationbased search and pollutionlevel filtering
 🔥 Heatmap visualization for pollution intensity
 🌙 Dark mode support for better usability
 ⬇️ Download filtered pollution data as CSV
 ⏱️ Autorefresh of data every 1 minute
 📌 Popup details including pH, BOD, DO, conductivity, and turbidity

 🧪 Pollution Classification Logic
| Turbidity Value | Pollution Level |
|||
| ≤ 7             | Low             |
| 7 – 10          | Medium          |
| > 10            | High            |

 🧭 Project Workflow
1. Load water quality data from CSV file
2. Parse and process data using PapaParse
3. Classify pollution levels based on turbidity
4. Plot locations on an interactive map
5. Apply filters, search, and heatmap visualization
6. Display realtime updates and alerts

 🌱 Sustainability & Impact
 Supports environmental monitoring and conservation
 Helps identify highrisk polluted zones
 Encourages datadriven decisionmaking
 Designed to be costeffective and scalable
 Aligns with societal and ecological sustainability goals

 🚀 Future Enhancements
 Realtime sensor data integration (IoT)
 Mobilefriendly interface
 Government and authority alert system
 Advanced analytics and predictive pollution trends
 Cloudbased data storage

 📂 How to Run the Project
1. Clone the repository
   ```bash
   git clone https://github.com/GitWithThanu/PollutionDetectioninWaterBodiesUsingGPSandTurbidity.git
