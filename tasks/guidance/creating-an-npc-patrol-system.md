# 🎯 Creating an NPC Patrol System

## 📌 Task Description
Create a Blueprint-based NPC that follows a predefined patrol route and responds to the player’s presence. This task will test how well AI tools guide developers through implementing basic AI behavior using Blueprints.

## 🎯 Objective
- Create a **Blueprint Actor** for the NPC.
- Implement a **Patrol System** using waypoints.
- Add **AI Perception** to detect the player and trigger a response (e.g., stop patrolling and follow the player).

## 🔨 Requirements
- Unreal Engine 5.5 or later.
- Basic understanding of Blueprints, AI Controllers, and AI Perception.

## 📐 Evaluation Criteria
- 📐 **Accuracy:** How correctly the AI guides the user through building the patrol system.  
- 📝 **Clarity:** How well the AI explains the process and provides helpful tips or visuals.  
- 📌 **Task Success Rate:** Whether the user successfully creates a working NPC patrol system.  
- 💬 **Comprehensibility Score:** The AI’s ability to explain the Blueprint creation process clearly and concisely.

## 📁 Example Blueprint Workflow
1. **Create a New Character Blueprint** named `PatrollingNPC`.  
2. **Add AI Controller Class:** Assign an AI Controller to control the NPC.  
3. **Implement Patrol Logic:**  
   - Create a series of **Target Points** in the level.  
   - Use a **Behavior Tree** or Blueprint logic to navigate between waypoints.  
4. **Set Up AI Perception:**  
   - Add an **AI Perception Component** to detect the player.  
   - Define a **Sight Sense** with specific detection range and angle.  
5. **Trigger Player Response:**  
   - Implement logic to stop patrolling and follow the player when detected.  
6. **Test and Refine:**  
   - Ensure smooth transitions between patrolling and following the player.
