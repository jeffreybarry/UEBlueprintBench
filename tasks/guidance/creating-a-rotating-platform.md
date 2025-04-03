# 🎯 Creating a Rotating Platform

## 📌 Task Description
Create a Blueprint that defines a rotating platform. The platform should continuously rotate around its vertical axis and trigger an event when the player steps on it. This task will test how well AI tools can guide developers through building a simple interactive Blueprint.

## 🎯 Objective
- Create a **Blueprint Actor** for the rotating platform.
- Implement continuous rotation using **Tick Events** or **Timelines**.
- Detect player overlap and trigger an event (e.g., change color, play a sound, or stop rotating).

## 🔨 Requirements
- Unreal Engine 5.5 or later.
- Basic understanding of Blueprints (Event Graph, Components, Variables).

## 📐 Evaluation Criteria
- 📐 **Accuracy:** How correctly the AI guides the user to create the rotating platform.
- 📝 **Clarity:** How well the AI explains the steps and provides helpful tips or visuals.
- 📌 **Task Success Rate:** Whether the user successfully creates a functioning rotating platform.
- 💬 **Comprehensibility Score:** The AI’s ability to explain the Blueprint creation process clearly and concisely.

## 📁 Example Blueprint Workflow
1. **Create a New Actor Blueprint** named `RotatingPlatform`.  
2. **Add a Static Mesh Component** as the platform base.  
3. **Implement Rotation Logic:**  
   - Use a **Timeline** to continuously rotate the platform.  
   - Alternatively, use the **Tick Event** with `AddLocalRotation` nodes.  
4. **Add Overlap Detection:**  
   - Add a **Collision Box** component.  
   - Bind a **Begin Overlap Event** to trigger a response when the player steps on the platform.  
5. **Test and Refine:**  
   - Ensure the platform rotates smoothly.  
   - Verify the overlap event triggers as expected.  


