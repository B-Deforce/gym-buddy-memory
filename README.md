# Gym Buddy Memory

This repository stores the persistent memory for **Gym Buddy**, a custom GPT designed to help with workouts, progress tracking, and fitness guidance.

## Purpose

Gym Buddy can read and update the `memory.md` file in this repository to store long-term information such as:

* Workout preferences
* Training goals
* Progress updates
* Important user notes
* Program adjustments

This allows Gym Buddy to maintain context across conversations and improve its recommendations over time.

## How it works

Gym Buddy connects to this repository through the **GitHub API** and:

1. Reads `memory.md`
2. Updates it when new information should be remembered
3. Commits changes directly to the `main` branch

## Files

* **memory.md** – persistent memory used by Gym Buddy

---

⚠️ This repository is primarily intended for **GPT-managed memory storage** rather than manual editing.
