Social Network Data Structures - Proof of Concept (Phase 2)

Project Overview
This repository contains a partial implementation of data structures for a social network application, developed as part of Phase 2: Proof of Concept Implementation. The focus is on demonstrating the core functionalities of user profile management, user connections (graph relationships), and influencer ranking.

Features
- User Profile Management using Hash Tables
  - Add, search, and delete user profiles
- User Connections using Graph (Adjacency List)
  - Add follower/following relationships
  - Display user connection graph
- Top Influencer Ranking using Priority Queue (Heap)
  - Retrieve Top-K users with the highest follower counts

Project Structure
```
├── user_profile.py        # Hash Table implementation for user profiles
├── social_graph.py        # Graph implementation for user connections
├── priority_queue.py    # Priority Queue implementation for Top-K influencers
├── main.py                # Script to demonstrate key functionalities
└── README.md              # Project documentation
```

How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/Snath32491/MSCS_Project_Phase 2.git
   cd MSCS_Project_Phase 2 
   ```
2. Run the demonstration script:
   ```bash
   python main.py
   ```

Next Steps
- Extend user profiles with additional metadata
- Implement bidirectional friendships
- Add post, like, and comment management
- Integrate persistent storage (database)
- Develop a front-end user interface

Note: This is a Proof of Concept and not a production-ready application.


