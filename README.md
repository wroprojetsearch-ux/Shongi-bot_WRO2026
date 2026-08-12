# ShongiBot — Cultural Companion Robot

## Project Team

**Team Name:** Circuit Breakers

### Team Members

* **Omor** — Team Leader
* **Wadi** — Team Member
* **Mahir** — Team Member

---

## 1. Project Title

**ShongiBot — A Cultural Companion for Bangladesh**

**Project Focus:** Preserving and promoting Bangladeshi cultural heritage through robotics and interactive technology.

**Current Development Stage:** Stationary cultural companion with conversational interaction, display, and servo-controlled hand movement.

**Future Vision:** An autonomous cultural companion capable of movement, obstacle avoidance, and interactive cultural education.

---

## 2. Project Overview

ShongiBot is a **culture-based companion robot** designed to help preserve, promote, and reconnect people with the cultural heritage of Bangladesh.

The project is based on the idea that, as society changes and becomes increasingly influenced by modern technology and global culture, some traditional aspects of Bangladeshi culture are becoming less familiar to younger generations.

Many people may not know about important elements of Bangladesh's cultural heritage, such as **terracotta art, traditional saris, Nakshi Kantha, folk music, traditional crafts, festivals, architecture, food, literature, and regional traditions**.

ShongiBot uses modern technology to help address this problem.

The robot allows people to **talk with it and ask questions about Bangladeshi culture**. Instead of giving completely general responses, ShongiBot's main purpose is to provide **culture-focused answers** and introduce users to Bangladesh's cultural heritage.

The ultimate goal is to use modern robotics and artificial intelligence to help **preserve and restore people's connection with Bangladeshi culture**.

---

# 3. Main Objective

The **first and most important objective of ShongiBot is culture**.

The robot is being developed as a **cultural companion**, not simply as a talking robot or a mobile robot.

Day by day, some aspects of Bangladeshi culture are becoming less familiar to people, especially younger generations. Traditional knowledge and heritage can gradually be forgotten when it is not passed from one generation to another.

ShongiBot aims to help by creating an interactive robot that people can talk to about Bangladeshi culture.

### The main objectives are to:

* Preserve and promote Bangladeshi cultural heritage.
* Help people learn about cultural traditions they may not know.
* Encourage younger generations to become interested in their cultural heritage.
* Allow users to ask questions about Bangladeshi culture.
* Provide culture-focused responses.
* Introduce people to traditional Bangladeshi arts and crafts.
* Share information about traditional clothing and textiles.
* Explain festivals, traditions, history, music, food, and literature.
* Encourage appreciation of Bangladesh's cultural diversity.
* Use modern technology to keep cultural knowledge relevant and accessible.
* Create a friendly cultural companion that people can interact with.

### Core Principle

> **Culture comes first. Technology supports the culture.**

The artificial intelligence, Raspberry Pi, display, speech system, servo motors, and future movement systems are all technologies that support ShongiBot's primary cultural mission.

---

# 4. The Cultural Problem

Bangladesh has a rich cultural heritage that has developed over centuries.

However, many traditional practices, arts, crafts, stories, and forms of cultural knowledge are becoming less familiar to parts of the population.

For example, some people may know very little about:

* Terracotta art.
* Traditional Bangladeshi saris.
* Nakshi Kantha.
* Folk music.
* Traditional handicrafts.
* Regional traditions.
* Traditional festivals.
* Folk stories.
* Traditional architecture.
* Bangladeshi food heritage.
* Traditional art forms.

This creates a risk that cultural knowledge may become disconnected from future generations.

ShongiBot is designed as one possible technological approach to help address this problem.

---

# 5. ShongiBot as a Cultural Companion

The word **companion** is important to the project.

ShongiBot is designed to interact with people rather than simply display information.

A user can ask a question, and ShongiBot can respond with information related to Bangladeshi culture.

### Example

**User:**
"What is terracotta art?"

**ShongiBot:**
"Terracotta is a traditional form of clay art that has an important place in the cultural heritage of Bengal. Terracotta decorations can be seen in historic architecture and traditional artistic works."

---

**User:**
"Tell me about Bangladeshi saris."

**ShongiBot:**
"Bangladesh has a rich tradition of handwoven saris. Different regions are known for different weaving traditions, patterns, materials, and techniques. These textiles are an important part of Bangladeshi cultural heritage."

---

**User:**
"What is Nakshi Kantha?"

**ShongiBot:**
"Nakshi Kantha is a traditional embroidered quilt from Bengal. It is known for decorative stitching and designs and represents an important part of Bengali folk art and craftsmanship."

---

# 6. Cultural Conversation

ShongiBot's conversation system is designed around **cultural knowledge**.

The user can ask questions, and the system processes the question and generates an appropriate response.

### Basic Interaction

**User → ShongiBot**

↓

**Question is received**

↓

**Raspberry Pi processes the question**

↓

**Cultural information is identified**

↓

**ShongiBot generates a response**

↓

**Response is spoken to the user**

The goal is to make learning about culture feel more like a conversation than a traditional lesson.

---

# 7. Current Robot Capabilities

ShongiBot is currently a **stationary prototype**.

It can:

* Understand questions from users.
* Respond to users.
* Provide culture-focused answers.
* Communicate through speech.
* Display information and expressions.
* Move its hands using servo motors.

### Important Current Limitation

ShongiBot **cannot move around yet**.

It currently has:

* No wheels.
* No drive motors.
* No mobile navigation.
* No obstacle avoidance.

The only physical movement currently available is **hand/arm movement using servo motors**.

---

# 8. Hardware Components

## Raspberry Pi 4

The Raspberry Pi 4 is the main computer of ShongiBot.

It is responsible for higher-level functions such as:

* Processing user questions.
* Running the conversational system.
* Generating responses.
* Managing the display.
* Handling communication.
* Controlling or communicating with other electronic systems.

---

## Arduino Nano

The Arduino Nano is used as a secondary microcontroller for hardware control.

Its role can include:

* Controlling servo motors.
* Managing hand movement.
* Handling future motor-control tasks.
* Receiving commands from the Raspberry Pi.
* Controlling other low-level hardware.

This creates a separation between the robot's **intelligence** and its **physical hardware control**.

**Raspberry Pi 4 → Intelligence and communication**

**Arduino Nano → Hardware and movement control**

---

## Display

The display gives ShongiBot a visual personality.

It can show:

* Animated eyes.
* Facial expressions.
* Greetings.
* Cultural information.
* Text.
* Animations.
* Reactions while talking.

---

## Servo Motors

Servo motors currently provide ShongiBot's physical movement.

They are used to move the robot's hands/arms.

Possible movements include:

* Waving.
* Raising a hand.
* Lowering a hand.
* Greeting gestures.
* Expressive movements while speaking.

---

## Power Bank

The current planned power source is a **10,000 mAh power bank**.

The power system must be designed according to the voltage and current requirements of the Raspberry Pi, Arduino, display, servo motors, and future motors.

As the robot develops, the power system may need to be upgraded to safely support additional motors and autonomous hardware.

---

# 9. Current System Architecture

```text
                 ┌────────────────────┐
                 │        USER        │
                 │  Asks a Question   │
                 └─────────┬──────────┘
                           │
                           ▼
                 ┌────────────────────┐
                 │     MICROPHONE     │
                 │    Voice Input     │
                 └─────────┬──────────┘
                           │
                           ▼
                 ┌────────────────────┐
                 │   RASPBERRY PI 4   │
                 │                    │
                 │ Question Processing│
                 │ Cultural Knowledge │
                 │ Response Generation│
                 └─────────┬──────────┘
                           │
                 ┌─────────┴─────────┐
                 ▼                   ▼
        ┌────────────────┐   ┌────────────────┐
        │    DISPLAY     │   │    SPEAKER     │
        │ Expressions &  │   │ Voice Response │
        │ Information    │   └────────────────┘
        └────────────────┘
                           │
                           ▼
                 ┌────────────────────┐
                 │    ARDUINO NANO    │
                 └─────────┬──────────┘
                           │
                           ▼
                 ┌────────────────────┐
                 │   SERVO MOTORS     │
                 │   Hand Movement    │
                 └────────────────────┘
```

---

# 10. Why Culture Is the Priority

ShongiBot is not being developed primarily as a robot that moves.

Movement is a future capability.

The central purpose is to **communicate culture**.

The robot's technology exists to make cultural information:

* More accessible.
* More interactive.
* More engaging.
* Easier to explore.
* More interesting for younger generations.

A person should be able to approach ShongiBot and ask:

> **"Tell me something about Bangladesh's cultural heritage."**

Instead of simply giving a generic response, ShongiBot should guide the conversation toward Bangladeshi culture.

---

# 11. Cultural Areas ShongiBot Can Cover

The cultural knowledge system can eventually cover many areas.

### Traditional Arts

* Terracotta.
* Folk painting.
* Traditional crafts.
* Woodwork.
* Pottery.

### Clothing and Textiles

* Traditional saris.
* Nakshi Kantha.
* Handloom traditions.
* Regional textiles.
* Traditional clothing.

### Music

* Folk music.
* Baul traditions.
* Traditional instruments.
* Regional musical traditions.

### Festivals

* Pohela Boishakh.
* Traditional regional celebrations.
* Folk festivals.
* Cultural events.

### Food

* Traditional Bangladeshi dishes.
* Regional foods.
* Traditional cooking methods.
* Food traditions.

### History and Heritage

* Historical locations.
* Heritage architecture.
* Important cultural figures.
* Historical traditions.

### Literature and Stories

* Bengali literature.
* Folk stories.
* Traditional storytelling.
* Cultural legends.

---

# 12. Future Movement System

Although ShongiBot cannot move currently, movement is planned for future versions.

The future robot is expected to have:

* Four wheels.
* Four motors.
* One motor connected to each wheel.
* A suitable motor driver.
* Motor control electronics.

The wheels and drive motors are **future components**, not current capabilities.

---

# 13. Future Types of Movement

The long-term goal is to give ShongiBot multiple types of movement.

### Wheel Movement

The future mobile system could support:

* Forward movement.
* Backward movement.
* Turning.
* Left/right movement.
* Rotating.
* Variable-speed movement.

### Arm Movement

Existing servo-controlled hands can be expanded to provide:

* Waving.
* Greeting.
* Pointing.
* Expressive gestures.
* Movement synchronized with speech.

### Head Movement

Future versions could potentially include:

* Looking left and right.
* Looking up and down.
* Head tilting.
* Expressive head movements.

### Body Movement

Future mechanical improvements could potentially allow:

* Body rotation.
* Expressive gestures.
* Coordinated body movements.

---

# 14. Future Autonomous ShongiBot

A major future goal is to transform ShongiBot into an **autonomous cultural companion**.

The future robot will be designed to:

* Move independently.
* Detect obstacles.
* Avoid obstacles.
* Navigate its environment.
* Make movement decisions.
* Interact with people while moving.

The development will progress approximately as follows:

**Stationary Cultural Companion**

↓

**Talking + Hand Movement**

↓

**Mobile Cultural Companion**

↓

**Obstacle-Avoiding Robot**

↓

**Autonomous Cultural Companion**

---

# 15. Future Obstacle Avoidance

The future ShongiBot will use sensors to detect objects in its environment.

A simplified system could work as follows:

```text
             ENVIRONMENT
                  │
                  ▼
           ┌───────────────┐
           │    SENSORS    │
           │ Detect Objects│
           └───────┬───────┘
                   │
                   ▼
           ┌───────────────┐
           │ Raspberry Pi /│
           │    Arduino   │
           │ Make Decision│
           └───────┬───────┘
                   │
                   ▼
           ┌───────────────┐
           │ Motor Control │
           └───────┬───────┘
                   │
                   ▼
           ┌───────────────┐
           │   Movement    │
           │ Avoid Object  │
           └───────────────┘
```

---

# 16. Development Roadmap

## Phase 1 — Cultural Brain

**Current Development**

* Raspberry Pi 4.
* Arduino Nano.
* Display.
* Voice interaction.
* Question understanding.
* Cultural responses.
* Servo-controlled hands.

## Phase 2 — Expressive Companion

* Improve display animations.
* Improve hand gestures.
* Add more expressive movements.
* Improve conversational interaction.
* Expand cultural knowledge.

## Phase 3 — Mobile Robot

* Add four wheels.
* Add four motors.
* Add motor driver.
* Implement basic driving.
* Develop movement control.

## Phase 4 — Autonomous Robot

* Add sensors.
* Detect obstacles.
* Avoid obstacles.
* Navigate independently.
* Improve environmental awareness.

## Phase 5 — Complete Cultural Companion

The final goal is a robot that can:

* Talk with people.
* Understand questions.
* Give cultural answers.
* Teach people about Bangladeshi heritage.
* Display expressions.
* Move its hands.
* Move around independently.
* Avoid obstacles.
* Perform different types of movement.
* Interact naturally with people.

---

# 17. Expected Impact

The goal of ShongiBot is to make cultural heritage **interesting, accessible, and interactive**.

Instead of culture being something that people only encounter in textbooks or museums, ShongiBot could provide a new way for people to interact with cultural knowledge.

A child or student could ask:

> **"What is this?"**

> **"Why is it important?"**

> **"Where did it come from?"**

> **"How is it made?"**

> **"Tell me another Bangladeshi tradition."**

ShongiBot can turn these questions into opportunities for cultural learning.

The long-term vision is to help create a stronger connection between **modern technology and traditional Bangladeshi heritage**.

---

# 18. Conclusion

ShongiBot is a **Cultural Companion Robot for Bangladesh**.

Its most important purpose is not movement, entertainment, or robotics alone. Its primary purpose is to **help preserve, promote, and restore people's connection with Bangladeshi cultural heritage**.

The current ShongiBot is stationary. It can understand questions, provide cultural responses, communicate with users, display information and expressions, and move its hands using servo motors.

It does not currently have wheels or drive motors.

In future versions, ShongiBot will gain wheels, motors, different types of physical movement, autonomous navigation, and obstacle avoidance.

However, even as the technology becomes more advanced, the project's central principle will remain the same:

> **Culture comes first. Technology supports the culture.**

The ultimate vision is to create a friendly autonomous robot that can **talk with people, teach them about Bangladesh's cultural heritage, preserve cultural knowledge, and help future generations reconnect with their culture.**
