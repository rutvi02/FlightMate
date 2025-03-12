# FlightMate - Your AI companion for all flight related queries
Hackathon Submission 
<img width="1446" alt="Screenshot 2025-03-09 at 8 59 47 PM" src="https://github.com/user-attachments/assets/9b89e83a-8ccb-4fba-9e34-a519ecf92cca" />


# Inspiration
Despite the vast availability of flight-related data, there is still a lack of chatbots that provide accurate, real-time flight information in a user-friendly manner. Finding the shortest flight paths, understanding airport statistics, and retrieving live flight details often require navigating through multiple sources. We really need a conversational AI assistant that simplifies this process and delivers precise insights.

# What it does
FlightMate is an intelligent chatbot that utilizes a graph-based dataset of airports, flights, and airline information to provide insightful responses to user queries. 
Key features include: 
Flight details: Find direct or connecting flights between two locations. Busiest airports: Identify high-traffic airports based on flight data. Shortest flight paths: Determine optimal routes with layovers using graph algorithms. 
Live weather updates: Fetch current weather conditions for any airport. 
Airline insights: Retrieve airline-specific data, including operational flights. 
Interactive visualizations: Generate dynamic network graphs to showcase connections and insights.

# How I built it
Enhanced the given tools to improve accuracy and added multiple new capabilities: Integrated a hybrid tool that combines AQL queries with NetworkX-based visualization to deliver clear and interactive graph representations. Incorporated real-time weather data using a weather API. Designed an intuitive user interface (UI) with Gradio for seamless interaction. Optimized agent-based reasoning to allow the chatbot to use the right tools dynamically.

# Challenges I ran into
Hybrid Tool Integration: Combining graph-based querying (AQL) with algorithmic processing (NetworkX) was complex but crucial for improving insights. Interactive Graph Visualization: Implementing a real-time, dynamic visualization that updates based on user queries posed a significant challenge, but overcame it with a refined approach. Ensuring Accurate Query Responses: Training the agent to choose the right tools for queries required refining our architecture and debugging complex scenarios.

# Accomplishments that I'm proud of
A chat interface that supports both text and audio responses for accessibility. Successfully integrated an interactive graph visualization that enhances user experience. Built a multi-tool agentic architecture that dynamically selects the best tool for each query.

# What we learned
How to build and integrate AI-powered tools for intelligent querying. The importance of tool selection for AI agents to optimize responses. How to implement agentic architectures that allow for multi-step reasoning.

# What's next for FlightMate
I have big plans for improving FlightMate: Context Awareness: Right now, the chatbot summarizes history but does not fully understand context. We aim to introduce a memory-based agent to track past queries and improve relevance. More Dynamic UI: A visually appealing, highly interactive UI to enhance user experience. Real-time Data Integration: Directly linking real-time flight databases for live updates, making FlightMate even more powerful.

