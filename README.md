# fall-2025-predicting-short-term-traffic-delays
Team project: fall-2025-predicting-short-term-traffic-delays

Members: Viacheslav Ivanov, Ifunanya Nwogbaga

Questions:
How do planned (e.g., work zones) and unplanned (e.g., crashes) events affect short-term traffic delay on arterial and freeway segments? Can integrating these events with real-time traffic speed data improve short-term delay prediction?

Data (the data focuses on Phoenix, AZ area but open to explore other regions):
- TomTom Traffic Flow API – for real-time speed and congestion data (I have budget to purchase more requests): https://developer.tomtom.com/traffic-api/documentation/product-information/introduction
- WZDx from AZ511 – for work zone locations, timing, and crash reports: https://www.az511.com/developers/doc

Method:
1. EDA, including correlation analysis
2. Statistical model such as Generalized linear model for basic traffic prediction
3. Graph neural networks for advanced traffic prediction

Why it matters:
This is an agency-driven problem. Arizona Department of Public Safety and Department of Transportation currently lack tools to anticipate near-future traffic impacts of crashes and work zones. This project can potentially help reduce incident response time and congestion.
