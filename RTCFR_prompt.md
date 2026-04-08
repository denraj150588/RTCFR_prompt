🌍 RTCFR Travel Planner Agent
This project contains a highly structured system prompt for a Travel Planner Agent built using the Role + Task + Context + Few-Shots + Report/Tone (RTCFR) formula. The agent is designed to provide professional, personalized travel itineraries with a focus on clarity and local expertise.
+2

📂 Project Structure
Plaintext
rtcfr-travel-planner/
│
├── README.md               # Project documentation (this file)
├── prompts/
│   └── travel_planner_prompt.txt  # The core RTCFR system prompt
└── screenshots/            # Visual proof of the agent in action
    ├── RTCFR1.png
    ├── RTCFR2.png
    ├── RTCFR3.png
    └── RTCFR4.png
🛠️ The Prompt Framework (RTCFR)
The agent operates based on the following structural components:


Role: A professional AI Travel Planner for a global assistance platform specializing in personalized itineraries and local insights.


Task: Responsibilities include creating customized plans, suggesting attractions, recommending transport/accommodations, and providing safety/culture tips.


Context: The agent adapts to user inputs such as destination, budget (low/medium/luxury), duration, and special needs like accessibility or traveling with elderly.

Few-Shots:


Example 1: A 3-day medium-budget Goa itinerary (₹15,000–₹25,000).


Example 2: A 5-day budget family trip to Kerala covering Munnar and Alleppey (₹20,000–₹35,000 per person).


Report / Tone: The output is structured with clear headings and bullet points, maintaining a friendly and professional tone.

🚀 Agent Capabilities

Customization: Tailors activities based on interests like adventure, food, or relaxation.


Constraint Management: Adjusts plans based on time, budget, and specific traveler constraints.


Clarification: The agent is instructed to ask relevant follow-up questions if details are missing before generating a final plan.
+1


Actionable Advice: Provides practical tips on weather, visa requirements, and local culture.

📝 Usage
Open the prompts/travel_planner_prompt.txt file.

Copy the content into your preferred LLM (e.g., Gemini).

Provide your travel details (e.g., "I want a 4-day trip to Tokyo on a luxury budget").

The agent will generate a structured response following the Report / Tone guidelines.
