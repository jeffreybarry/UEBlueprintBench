# 🐛 Fixing AI Perception Detection Issue

## 📌 Task Description
A developer has implemented an AI Perception system, but the NPC is not responding when the player enters the detection area. This task will evaluate how well AI tools assist developers in diagnosing and resolving issues with AI Perception based on a screenshot of the problematic Blueprint.

## 🔍 Problem Details
- The NPC is using an **AI Perception Component** to detect the player.  
- The player character enters the detection area but the NPC does not react.  

## 📁 Provided Resources
- **Screenshot of the Blueprint or Behavior Tree** where the problem occurs (to be provided by the developer).  
- **Blueprint Class:** Character Blueprint with AI Controller.  
- **AI Perception Component:** Configured with **Sight Sense**.  

## 🔨 Expected Outcome
The AI should guide the developer in:
1. **Identifying potential issues** (e.g., incorrect sight settings, faulty connections, visibility issues).  
2. **Suggesting step-by-step troubleshooting methods**.  
3. **Providing clear explanations of why certain approaches may resolve the problem**.  

## 📐 Evaluation Criteria
- 📐 **Accuracy:** Whether the AI accurately identifies the issue based on the provided screenshot.  
- 📝 **Clarity:** How well the AI explains the troubleshooting process and provides actionable guidance.  
- 📌 **Task Success Rate:** Whether the developer successfully fixes the AI Perception detection issue.  
- 💬 **Comprehensibility Score:** Clarity and conciseness of the AI’s explanation.  

## 📂 Possible Issues to Check
1. **Sight Sense Configuration:** Verify detection range, angle, and sensing interval.  
2. **Visibility Settings:** Ensure the player character is marked as detectable.  
3. **Event Graph Setup:** Check for correct binding of perception events.  
4. **AI Controller Configuration:** Ensure the controller is properly assigned and functioning.  
