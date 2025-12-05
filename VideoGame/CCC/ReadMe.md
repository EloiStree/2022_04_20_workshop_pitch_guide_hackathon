

# GPT 🤖

## 🎮 What is a **CCC**?

A **CCC** stands for **Camera–Character Controller**.
It’s a small set of rules and code that decides:

1. **How the player’s character moves**
2. **How the camera follows the character**
3. **How the player sees and interacts with the game world**

Think of it as the *“brains”* behind movement and camera behavior.

---

## 🧍‍♂️ **Character Controller**

This part handles everything about **how the character moves**, such as:

* Walking
* Running
* Jumping
* Colliding with the environment
* Sliding on slopes
* Not falling through the floor

It's basically the physics and movement logic of the player.

> If you press **W**, the Character Controller decides:
> *“Move forward at this speed, and don’t go through the wall.”*

---

## 🎥 **Camera Controller**

This part controls **how the camera behaves**, such as:

* Following the character smoothly
* Rotating when the player moves the mouse or right stick
* Zooming in/out
* Keeping the character visible and centered

> When you move the mouse, the Camera Controller decides:
> *“Rotate the camera and show the world from a new angle.”*

---

## 🤝 Putting them together = **CCC**

When you combine both the **Character Controller** and the **Camera Controller**, you get a **CCC**.

It’s what makes the basic gameplay feel **nice**, **smooth**, and **fun**.

Without a CCC, even a great game idea feels bad because:

* movement is weird
* the camera shakes or gets stuck
* the player gets frustrated

That’s why a **CCC is usually the FIRST thing to prototype in any game** during a hackathon.

---

## 🧠 Why we insist on making a CCC in a game project

Because a CCC shows:

* You can turn an idea into something playable
* You understand user experience (UX) in games
* The game world is testable
* You can build features on top of it

It’s a **minimum useful prototype** for any game project.
