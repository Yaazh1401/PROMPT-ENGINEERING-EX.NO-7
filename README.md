# Exno.7-Develop a prompt-based application tailored to their personal needs, fostering creativity and practical problem-solving skills while leveraging the capabilities of large language models.

# Date:
# Register no.
# Aim: To develop a prompt-based application using ChatGPT - To demonstrate how to create a prompt-based application to organize daily tasks, showing the progression from simple to more advanced prompt designs and their corresponding outputs.

#AI Tools Required: 


# Explanation: 
Prompt:
"Design a personal productivity assistant that can help manage daily tasks, schedule reminders, suggest wellness tips, and answer general queries. The assistant should interact using natural language and be adaptable to the user’s changing preferences over time."
Procedure:
1. Define the core requirements of a personal productivity assistant.
2. Identify and construct appropriate prompts for each task using an LLM (e.g., ChatGPT).
3. Simulate natural user interaction through a simple interface or command-line system.
4. Collect feedback or inputs from users and adapt responses accordingly.
5. (Optional) Integrate basic memory to simulate preference adaptation.
EXPECTED OUTPUT: - (attached the drive link)
Output (Example Response by LLM):
Personal Productivity Assistant Features:
1. Daily Task Manager:
o Accept tasks via natural language (e.g., "Remind me to call mom at 6 PM").
o Organize tasks by priority and deadline.
o Provide daily summaries and pending items.
2. Smart Scheduler:
o Schedule events and set reminders using contextual understanding.
o Notify user of overlapping appointments or free time slots.
3. Wellness Tips Generator:
o Suggest daily wellness advice (hydration, exercise, screen-time breaks).
o Adapt suggestions based on past user preferences and responses.

# output:
Prompt-Based Application Using ChatGPT
Personal Productivity Assistant
1. Objective

The objective of this project is:

To develop a prompt-based application using ChatGPT
To organize daily tasks using natural language interaction
To demonstrate the evolution from simple prompts to advanced prompt engineering
To simulate a personal productivity assistant
2. AI Tool Required
AI Tool	Purpose
ChatGPT	Natural language interaction and task management
3. Problem Statement

Design a personal productivity assistant that can:

Manage daily tasks
Schedule reminders
Suggest wellness tips
Answer general queries
Adapt to user preferences over time

The assistant should interact naturally using conversational prompts.

4. Core Requirements of the Productivity Assistant
Feature	Description
Daily Task Manager	Add, update, and organize tasks
Smart Scheduler	Set reminders and schedule events
Wellness Tips Generator	Suggest health and productivity tips
General Query Assistant	Answer user questions
Preference Adaptation	Learn user preferences over time
5. Prompt Engineering Progression

The project demonstrates progression from:

Simple prompts
Structured prompts
Context-aware prompts
Adaptive prompts with memory
6. Prompt Designs and Outputs
A. Simple Prompt Design
Prompt

Add a task to remind me to submit my assignment tomorrow at 5 PM.

Example Output

Task added: “Submit assignment” scheduled for tomorrow at 5 PM.

Analysis
Aspect	Observation
Complexity	Very basic
Context Handling	Limited
Flexibility	Low
B. Structured Prompt Design
Prompt

You are a personal productivity assistant.

Perform the following:

Add the task “Submit assignment”
Set reminder for tomorrow at 5 PM
Mark priority as High
Include the task in tomorrow’s summary
Example Output

Task successfully added.

Task: Submit assignment
Reminder: Tomorrow, 5 PM
Priority: High
Included in daily summary.

Analysis
Aspect	Observation
Clarity	Improved
Organization	Better
Accuracy	High
C. Context-Aware Prompt Design
Prompt

You are an intelligent productivity assistant.

The user has exams this week and prefers evening study sessions.

Add the task “Prepare AI presentation” for today and suggest an appropriate study schedule with breaks.

Example Output

Task Added: Prepare AI presentation

Suggested Schedule:

6:00 PM – 7:30 PM → Presentation preparation
7:30 PM – 7:45 PM → Short break
7:45 PM – 9:00 PM → Practice session

Wellness Tip:
Stay hydrated and avoid continuous screen exposure.

Analysis
Aspect	Observation
Context Awareness	Excellent
Personalization	High
User Experience	Improved
D. Advanced Adaptive Prompt Design
Prompt

You are a smart productivity assistant with memory.

The user prefers:

Morning exercise
Evening study sessions
Short reminders instead of long notifications

Organize today’s schedule with tasks, wellness tips, and reminders.

Example Output

Today’s Personalized Schedule:

7:00 AM → Morning exercise
9:00 AM → Attend classes
5:00 PM → Reminder: AI assignment
6:00 PM → Study session

Wellness Tip:
Take a 5-minute eye break every hour.

Reminder Style:
“AI Assignment at 5 PM.”

Analysis
Aspect	Observation
Adaptability	Excellent
Personalization	Very High
Natural Interaction	Advanced
7. Python Command-Line Implementation
Sample Python Code
tasks = []

print("=== Personal Productivity Assistant ===")

while True:

    user_input = input("You: ")

    if "add task" in user_input.lower():

        task = user_input.replace("add task", "")
        tasks.append(task)

        print(f"Assistant: Task '{task}' added successfully.")

    elif "show tasks" in user_input.lower():

        print("Assistant: Your Tasks")

        for i, task in enumerate(tasks, start=1):
            print(f"{i}. {task}")

    elif "wellness tip" in user_input.lower():

        print("Assistant: Drink enough water and take short breaks while studying.")

    elif "exit" in user_input.lower():

        print("Assistant: Goodbye!")
        break

    else:

        print("Assistant: I can help manage tasks, reminders, and wellness tips.")
8. Simulated User Interaction
User Input	Assistant Response
Add task Submit AI assignment	Task added successfully
Show tasks	Displays task list
Give wellness tip	Suggests hydration and breaks
Schedule study at 6 PM	Reminder created
9. Optional Memory Integration
Example Preference Storage
user_preferences = {
    "study_time": "evening",
    "exercise_time": "morning",
    "notification_style": "short"
}
Adaptive Response Example
User

Plan my day.

Assistant

Since you prefer evening study sessions, your AI preparation task is scheduled for 6 PM.

10. Expected Output Features
Personal Productivity Assistant Features
A. Daily Task Manager

Features:

Accept natural language tasks
Organize tasks by:
Priority
Deadline
Category
Provide task summaries
Example

“Remind me to call mom at 6 PM.”

B. Smart Scheduler

Features:

Schedule events intelligently
Detect conflicts
Suggest available time slots
Example

“You already have a meeting at 5 PM. Would you like to move the reminder to 6 PM?”

C. Wellness Tips Generator

Features:

Suggest hydration reminders
Recommend breaks
Encourage exercise and sleep routines
Example

“Take a 10-minute walk after long study sessions.”

D. Preference Adaptation

Features:

Learn user habits
Adjust reminders
Personalize recommendations
11. Comparison of Prompt Designs
Prompt Type	Complexity	Personalization	Context Awareness	Output Quality
Simple Prompt	Low	Low	Low	Moderate
Structured Prompt	Medium	Medium	Medium	Good
Context-Aware Prompt	High	High	High	Very Good
Adaptive Prompt	Advanced	Very High	Very High	Excellent
12. Key Findings
Better prompts produce more intelligent responses.
Structured prompts improve task organization.
Context-aware prompts improve personalization.
Adaptive prompts simulate real AI assistants effectively.
13. Conclusion

This project demonstrates how ChatGPT can be used to build a prompt-based personal productivity assistant.

The experiment shows that:

Prompt engineering significantly improves AI interaction quality.
Advanced prompts provide more human-like assistance.
Memory and preference adaptation enhance user experience.

Final Insight:

Effective prompt design is essential for building intelligent AI-powered applications.

# Result: 
The lab exercise resulted in the creation of a prototype concept for a personal assistant powered by large language models. Students were able to:
 Understand how to tailor LLM prompts to real-life applications.
 Foster creativity by designing features suited to their personal or academic lives.
 Learn prompt engineering techniques for optimal interaction with AI tools.
 Experience the versatility and utility of generative AI in solving everyday problems.
