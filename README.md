# Ex.No.4-EXP 4 Generate the Prompt and evaluate that for following prompt patterns - Zero-shot Prompting.•	Few-shot Prompting - Chain of Thought -	Persona Pattern - Reverse Prompting - Graph Prompting - Active Prompting
### DATE:27-8-26                                                                    
### REGISTER NUMBER: 212223040022
### NAME: AYISHA RINSI K
# Ex.No.4 – Generate the Prompt and Evaluate for Advanced Prompting Techniques
Zero-shot Prompting

Few-shot Prompting

Chain of Thought

Persona Pattern

Reverse Prompting

Graph Prompting

Active Prompting

# Use Case :

## Drone Navigation using AI and Computer Vision

### Scenario

Autonomous drones use AI, GPS, cameras, and sensors to detect obstacles, plan routes, and navigate safely without continuous human control.

### Target Audience

* AI engineers
* Robotics students
* Drone developers
* Researchers

### Main Objectives

* Improve navigation accuracy.
* Avoid obstacles.
* Reduce travel time.
* Save battery.
* Ensure safe flight.

---

# Prompt Design and Evaluation

## 1. Zero-shot Prompting

### Prompt

> Explain how AI helps a drone navigate safely while avoiding obstacles.

### Expected AI Response

AI uses cameras, GPS, LiDAR, and sensors to detect obstacles and calculate safe routes. It continuously updates the flight path to avoid collisions.

### Observation

The model answers directly without examples.

---

## 2. Few-shot Prompting

### Prompt

**Example 1**

**Input:** Tree detected.
**Output:** Change direction to avoid it.

**Example 2**

**Input:** Battery below 20%.
**Output:** Return to base.

**Now Answer**

**Input:** Building detected ahead.

### Expected AI Response

Change the flight path and move around the building safely.

### Observation

Examples help the AI understand the expected response pattern.

---

## 3. Chain of Thought

### Prompt

> Explain step by step how a drone delivers medicine while avoiding obstacles and saving battery.

### Expected AI Response

1. Receive destination.
2. Collect GPS and sensor data.
3. Detect obstacles.
4. Generate possible routes.
5. Select the safest route.
6. Monitor battery.
7. Update the route when needed.
8. Reach the destination.

### Observation

The response presents the task in a logical sequence.

---

## 4. Persona Pattern

### Prompt

> You are an experienced drone engineer. Explain how AI improves drone navigation.

### Expected AI Response

AI combines GPS, camera, and sensor data to detect obstacles and select efficient routes. It continuously adjusts the drone's movement to improve safety and battery usage.

### Observation

The response reflects the role of a drone engineer.

---

## 5. Reverse Prompting

### Prompt

> A drone avoided obstacles, reached its destination, and returned safely. What prompt could have generated this response?

### Expected AI Response

Create an AI drone system that detects obstacles, selects safe routes, reaches the destination, and automatically returns to its base.

### Observation

The AI reconstructs a possible original prompt from the output.

---

## 6. Graph Prompting

### Prompt

> Represent autonomous drone navigation as a flow diagram.

### Expected AI Response

```text
Start
  ↓
Set Destination
  ↓
Collect Sensor Data
  ↓
Detect Obstacles
  ↓
Plan Safe Route
  ↓
Navigate
  ↓
Obstacle Detected?
  ↓
Recalculate Route
  ↓
Reach Destination
  ↓
End
```

### Observation

The graph makes the navigation process easy to understand.

---

## 7. Active Prompting

### Prompt

> A drone detects heavy rain during flight. Ask for missing information before recommending an action.

### Expected AI Response

The AI asks:

* What is the battery level?
* How heavy is the rain?
* Is the drone waterproof?
* How far is the destination?

It then recommends continuing, changing the route, or returning to base.

### Observation

The AI collects additional information before making a decision.

---

# Outputs for Each Prompting Technique

## 1. Zero-shot Prompting

### Prompt

Explain how AI helps a drone navigate safely while avoiding obstacles.

### AI Output

AI uses cameras, GPS, and sensors to detect obstacles and calculate safe routes. It continuously updates the flight path during navigation.

---

## 2. Few-shot Prompting

### Prompt

Input: Building detected ahead.

### AI Output

Change direction and select a safe alternate route.

---

## 3. Chain of Thought Prompting

### Prompt

Explain step by step how a drone delivers medicine safely.

### AI Output

Receive destination → Detect obstacles → Plan route → Monitor battery → Adjust route → Deliver medicine → Return safely.

---

## 4. Persona Pattern

### Prompt

You are an experienced drone engineer. Explain AI-based navigation.

### AI Output

AI helps drones detect obstacles, choose efficient routes, and automatically adjust their movement using real-time sensor information.

---

## 5. Reverse Prompting

### Prompt

A drone avoided obstacles and safely reached its destination. Generate the original prompt.

### AI Output

Design an AI drone that detects obstacles and selects a safe route to reach its destination.

---

## 6. Graph Prompting

### Prompt

Represent drone navigation as a flow diagram.

### AI Output

```text
Start
 ↓
Sensor Data
 ↓
Obstacle Detection
 ↓
Route Planning
 ↓
Navigation
 ↓
Destination
 ↓
End
```

---

## 7. Active Prompting

### Prompt

A drone detects heavy rain. Ask questions before deciding what to do.

### AI Output

The AI asks about battery level, rainfall intensity, drone waterproofing, and destination distance before recommending an action.

# Comparison with Different AI Tools

| Prompt Type      | ChatGPT        | Google Gemini | Microsoft Copilot |
| ---------------- | -------------- | ------------- | ----------------- |
| Zero-shot        | Clear          | Clear         | Concise           |
| Few-shot         | Very good      | Good          | Good              |
| Chain of Thought | Detailed       | Logical       | Short             |
| Persona          | Professional   | Professional  | Brief             |
| Reverse          | Accurate       | Good          | Moderate          |
| Graph            | Clear          | Clear         | Simple            |
| Active           | Good questions | Good          | Basic             |

---

# Evaluation Method – Rubrics

## Evaluation Criteria

| Criteria    | Excellent (5)   | Good (4)       | Average (3) |
| ----------- | --------------- | -------------- | ----------- |
| Reasoning   | Complete        | Mostly logical | Basic       |
| Correctness | Highly accurate | Minor errors   | Some errors |
| Token Usage | Concise         | Moderate       | Verbose     |

---

## Rubrics Scores

| AI Tool           | Reasoning | Correctness | Token Usage | Total / 15 |
| ----------------- | --------: | ----------: | ----------: | ---------: |
| ChatGPT           |         5 |           5 |           5 |     **15** |
| Google Gemini     |         4 |           5 |           4 |     **13** |
| Microsoft Copilot |         4 |           4 |           4 |     **12** |

---

# Result Analysis

* **ChatGPT** provided detailed and accurate responses.
* **Google Gemini** provided logical and relevant responses.
* **Microsoft Copilot** provided concise but less detailed responses.

---

# Conclusion

The experiment demonstrated the use of seven advanced prompting techniques for AI-based drone navigation. Each technique produced different types of responses based on its purpose. Rubric evaluation showed that ChatGPT achieved the highest overall score for reasoning, correctness, and token efficiency.

---

# Result

Thus, the advanced prompting techniques were successfully implemented, compared using different AI tools, and evaluated using a rubric-based method for the Drone Navigation use case.
