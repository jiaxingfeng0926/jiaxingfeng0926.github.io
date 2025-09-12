---
layout: project
type: project
image: jumbajuice.jpg
title: "Jamba Juice Simulator"
date: 2025-09-09
labels:
  - Typescript
  - Learning
summary: "Simulation of a Jamba Juice store that manages menus, drinks, orders, and inventory to process customer purchases realistically."
---

**Introduction**

This project is a TypeScript simulation of a Jamba Juice store. It models the real-world process of ordering drinks by defining classes for menu items, drinks, and orders, and extends the system with inventory management. Before fulfilling an order, the store checks whether there are enough ingredients available in the inventory, ensuring that drinks can only be made when there is sufficient stock. This structure captures both the customer-facing side (menus, drinks, orders) and the behind-the-scenes operations (inventory and fulfillment).

**Diffculty**

The most challenging parts of this project was ensuring that all the classes worked together correctly, especially the interaction between the inventory and the store. It was difficult to properly handle situations where a drink couldn’t be produced due to a missing ingredient, while other ingredients might still be available for different drinks.

**What I learned**

From this project, I learned how to design and connect multiple classes to build a complete program, rather than just writing isolated functions. I practiced designing and organizing various classes so that they could interact seamlessly, and I gained experience in considering real-world constraints, such as limited inventory. I also learned how to break down a larger problem into smaller, more manageable parts by designing separate classes for menu items, drinks, orders, inventory, and the store. This made the system much easier to understand and maintain.

