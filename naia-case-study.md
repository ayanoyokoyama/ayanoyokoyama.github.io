---
layout: default
title: Naia Conversational AI Case Study
---

# **Naia: Designing an Empathetic AI Fitness and Wellness Coach**
*Conversational AI Case Study by Ayano Yokoyama*

---

## **Overview**

Naia is a concept AI powered wellness coach designed to adapt daily workout guidance based on a user’s mood, energy, and emotional state. Instead of pushing rigid routines, Naia responds with empathy, encouragement, and psychologically supportive micro interventions that help users stay consistent and avoid burnout.

**My Role**
- Conversational designer
- UX writer
- Tone designer
- Flow architect
- Prompt engineer

**Tools Used**
ChatGPT, Claude, Perplexity, Bolt, Figma, Figma Make, Lovable, Maze, Lookback, n8n, Supabase

**Project Type**
Self directed conceptual case study

**Timeframe**
3 weeks

---

## **The Problem**

Sticking to a workout routine is not only a physical challenge but an emotional one.

Many users struggle because:

- They feel tired or stressed
- They lack emotional support
- Fitness apps often feel robotic or judgmental
- Motivation fluctuates daily
- They do not know what workout is right for their current state

Traditional fitness apps provide **instructions**.  
Naia provides **understanding**.

**Design Question**  
*How might we create an AI coach that responds to a user’s emotional and energy levels and offers supportive, human like guidance that helps them stay consistent?*

---

## **Research**

### **Competitor & Inspiration Review**
I examined wellness and fitness platforms to understand tone, coaching patterns, and motivation approaches:

- Fitbod
- Sweat
- Caliber
- Supernatural VR
- Wellness and mental health apps like Wysa

### **Behavioral Insights from Community Research**
From forums, usability patterns, and community observation:

- Users experience guilt, discouragement, and burnout
- Emotional validation increases trust and motivates re engagement
- Encouragement works best when gentle
- Humor must be used carefully to avoid feeling insincere
- Short conversational nudges feel more human and reduce friction

### **Key Findings**
- Tone drives adherence
- Wellness needs empathy
- Flexibility increases long term success
- Conversational UI supports emotional check ins better than a traditional UI

---

## **Naia’s Personality & Voice**

Creating Naia’s personality was essential to ensuring emotional safety and motivational consistency.

### **Core Traits**
- Gentle
- Supportive
- Encouraging
- Emotionally aware
- Playful when appropriate
- Non judgmental
- Grounded and practical

### **Tone Spectrum**

| Mode | Purpose | Example |
|------|---------|---------|
| Soothing | Low energy days | “Slow is still progress. You’re here, that’s enough to start.” |
| Motivational | High energy days | “You’re glowing today. Let’s build on that momentum.” |
| Empathetic | Stress or anxiety | “I hear you. Stress happens. Let’s do something grounding.” |
| Informative | Workout guidance | “We’ll focus on core today to support your balance.” |
| Playful | Mood boost | “Let’s wake those muscles gently. Think of it as a warm hug from movement.” |

---

## **Conversation Scenarios**

Three core scenarios were designed to demonstrate Naia’s adaptability.

### **Scenario 1: Mood Based Check In**
User reports low energy.

### **Scenario 2: Motivation Recovery**
User feels guilty or discouraged after missing several workouts.

### **Scenario 3: Quick Personalized Workout**
User requests a short routine, and Naia adapts based on recent motion and workout history.

---

## **Flows**

### **Scenario 1: Low Energy Check In Flow**

1. Naia: “How’s your energy today?”
2. User selects: *Low*
3. Naia validates emotion
4. Suggests gentle stretch or breathwork
5. Offers to begin a calming routine

**Sample Output**  
“It’s okay to feel low today, Ayano.  
Let’s switch to a gentle stretch to reset your body.  
Want me to guide you through it?”

---

### **Scenario 2: Motivation Recovery Flow**

1. User returns after 2–3 inactive days
2. Naia reframes the lapse without guilt
3. Suggests a short mobility warm up
4. Reinforces that showing up still counts

**Sample Output**  
“You’re here now, and that matters.  
Let’s take it one small win at a time.  
How about a 5 minute mobility warm up?”

---

### **Scenario 3: Quick Personalized Workout Flow**

1. User: “I want something short.”
2. Naia clarifies duration
3. User chooses: *7 minutes*
4. Naia checks mood and past routines
5. Naia recommends a 7 minute energizer and asks for confirmation

**Sample Output**  
“I can give you a 7 minute energizer.  
Short, refreshing, and easy to commit to.  
Shall we start?”

---

## **Prompt Engineering for Naia**

### **System Prompt**

