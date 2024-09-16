
# Unreal Engine 5.4 AI Development Series

This repository contains the source code and assets used in my Unreal Engine 5.4 AI development tutorial series. Each part of the series explores a different aspect of AI behavior, ranging from basic setups to advanced state handling and task prioritization within behavior trees. You can find the related YouTube video links for each part in their respective sections.

## Table of Contents
- [Part 1: Basic AI Setup and Custom Tasks](#part-1-basic-ai-setup-and-custom-tasks)
- [Part 2: Patrolling, State Switching, and Animation Montages](#part-2-patrolling-state-switching-and-animation-montages)
- [Upcoming Parts](#upcoming-parts)
- [How to Use](#how-to-use)
- [Technologies](#technologies)
- [License](#license)

---

## Part 1: Basic AI Setup and Custom Tasks
**Video Link:** [Watch on YouTube](https://www.youtube.com/watch?v=hGEs4O3ccGs)

In this part, I demonstrate the foundational AI setup, which includes:

- **AI Controller Setup:** Creating a basic AI controller to handle AI movement and actions.
- **Behavior Tree Creation:** Setting up the behavior tree and blackboard to manage AI decision-making processes.
- **Custom Tasks:** Developing custom tasks such as AI attacks, focus handling, and other actions.
- **Leg IK Fix for UE5 Mannequin:** Ensuring correct leg IK setup for smoother animation blending.

---

## Part 2: Patrolling, State Switching, and Animation Montages
**Video Link:** [Watch on YouTube](https://www.youtube.com/watch?v=gCOWstlVqfI)

This part builds on the previous AI setup and focuses on the following:

- **Patrolling AI:** Implementing spline-based patrol paths for AI navigation.
- **State Switching:** Using behavior trees to switch between different AI states, such as idle, patrol, and attack.
- **Task Priority:** Managing task priorities in the behavior tree, allowing for interruption of lower-priority tasks by higher-priority ones.
- **Animation Montages:** Creating and utilizing animation montages, including triggering specific actions with montage notifies.
  
---

## Upcoming Parts
Additional parts will be added soon, focusing on more advanced AI behavior, including combat strategies, boss AI, and dynamic world interaction.

---

## How to Use

1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/FurkanBaytak/Unreal-Engine-5.4-EnemyAI-System.git
   ```
2. Open the project in **Unreal Engine 5.4**.
3. Navigate to the `Content` folder to view.
4. Behavior Trees, AI Controllers, and tasks can be found within the corresponding Blueprint and asset directories.

---

## Technologies
- **Unreal Engine 5.4**: The core game engine used for development.
- **Blueprints**: Used for visual scripting in conjunction with C++.
- **Behavior Trees**: For decision-making AI logic.
- **Custom Tasks**: For custom tasks used by AI.
- **Animation Montages**: For managing character animations.

---

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
