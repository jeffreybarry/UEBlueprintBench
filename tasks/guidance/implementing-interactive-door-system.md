# 🎯 Implementing an Interactive Door System

## 📌 Task Description
Create a Blueprint-based interactive door system that opens and closes when the player approaches or interacts with it. This task will test how well AI tools guide developers through setting up interaction systems using Blueprints.

## 🎯 Objective
- Create a **Blueprint Actor** for the door.  
- Implement **Open/Close Logic** triggered by proximity or key press.  
- Add **Visual and Audio Feedback** (e.g., door creaking sound, smooth door animation).  

## 🔨 Requirements
- Unreal Engine 5.5 or later.  
- Basic understanding of **Blueprints, Collisions, and Timelines**.  

## 📐 Evaluation Criteria
- 📐 **Accuracy:** How well the AI guides the user through creating the interactive door system.  
- 📝 **Clarity:** How well the AI explains the process and provides helpful tips or visuals.  
- 📌 **Task Success Rate:** Whether the user successfully implements a working door system.  
- 💬 **Comprehensibility Score:** The AI’s ability to explain the Blueprint creation process clearly and concisely.  

## 📁 Example Blueprint Workflow
1. **Create a New Actor Blueprint** named `InteractiveDoor`.  
2. **Add Static Mesh Component:** Assign a door mesh.  
3. **Set Up Collision Trigger:**  
   - Add a **Box Collision** component to detect player presence.  
   - Bind an **OnBeginOverlap Event** to trigger the door’s opening.  
4. **Implement Open/Close Logic:**  
   - Use **Timelines or Rotator Nodes** to animate door movement.  
   - Trigger door closing after a delay or when the player moves away.  
5. **Add Visual & Audio Feedback:**  
   - Add a **Sound Cue** for door creaking.  
   - Apply materials that change appearance when interacted with.  
6. **Test and Refine:**  
   - Ensure the door opens and closes smoothly with proper feedback.
