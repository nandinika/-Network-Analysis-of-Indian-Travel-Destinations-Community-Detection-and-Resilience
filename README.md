# -Network-Analysis-of-Indian-Travel-Destinations-Community-Detection-and-Resilience

This project explores travel behavior in India by analyzing Reddit discussions using network science techniques. It constructs a co-occurrence network of Indian travel destinations, applies community detection algorithms, and evaluates the resilience of key travel hubs to uncover tourism circuits and network dependencies.

📌 Project Highlights
🔍 Data Collection: Scraped Reddit posts from 17 India-focused travel subreddits using the Reddit API (PRAW).

🏙️ NER-Based Extraction: Applied Named Entity Recognition (NER) with spaCy to extract city and region mentions.

🌐 Network Construction: Built a destination co-occurrence network where nodes represent locations and edges signify co-visits in posts.

🧠 Community Detection: Identified meaningful travel clusters using the Louvain and Girvan-Newman algorithms.

🔄 Network Resilience: Assessed how removal of central hubs (like Kochi) affects the network’s structure and connectivity.

⚙️ Technologies Used
Python

Reddit API (PRAW)

spaCy (for NER)

NetworkX, Matplotlib

Community Detection (Louvain, Girvan-Newman)

📈 Key Insights
Central hubs like Kochi, Mumbai, and Delhi form the backbone of Indian travel conversations.

Distinct regional clusters (e.g., Kerala, Rajasthan, North India) highlight popular travel circuits.

Network fragmentation after removing central hubs reveals dependency on specific destinations.
