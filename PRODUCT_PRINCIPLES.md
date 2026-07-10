# PRODUCT PRINCIPLES

Version

1.0.0

---

# Purpose

This document defines the immutable product rules of Talia.

These principles must not change during implementation.

Any future feature must comply with these principles.

---

# Principle 01

The Quran is the Product

The application exists to help users interact with the Quran.

Every feature must directly support this purpose.

If a feature does not strengthen the user's relationship with the Quran, it should not be implemented.

---

# Principle 02

Reading and Memorization are Separate Experiences

Reading and memorization are different user journeys.

Reading should never force memorization.

Memorization should never interrupt reading.

Both experiences share the same Quran content.

---

# Principle 03

One Quran Data Layer

The Quran content exists only once.

All modules use the same source.

Reading

↓

Memorization

↓

Review

↓

Search

↓

Recitation

All consume the same Quran data.

---

# Principle 04

Quality Before Quantity

The goal is correct memorization.

Not memorizing the largest number of verses.

Assessment quality always has higher priority than memorization speed.

---

# Principle 05

Review is Mandatory

Every memorized verse must eventually return for review.

Memorization without review is considered incomplete.

---

# Principle 06

Smart Coach Recommends

Smart Coach recommends.

It does not force.

The final decision always belongs to the user.

---

# Principle 07

Local First

Every user action is stored locally first.

Network connectivity must never block the user.

---

# Principle 08

Offline First

Core features must work without internet.

Cloud services improve the experience.

They never enable the experience.

---

# Principle 09

Single Source of Truth

Each type of information has one authoritative source.

Progress is calculated.

Never duplicated.

---

# Principle 10

Kids Mode is a Presentation Layer

Kids Mode changes the presentation.

It never changes memorization rules.

Children and adults use the same memorization engine.

---

# Principle 11

Parents Observe

Parents monitor progress.

Parents encourage.

Parents cannot modify memorization data.

---

# Principle 12

Progress is Earned

Progress reflects real learning.

It cannot be purchased.

It cannot be unlocked artificially.

---

# Principle 13

Gamification Supports Learning

Gamification motivates.

It never replaces learning.

Rewards must always follow meaningful progress.

---

# Principle 14

Notifications Have Purpose

Notifications exist only when there is a meaningful action.

Notifications must never exist to increase screen time.

---

# Principle 15

Simple Before Smart

Whenever two solutions solve the same problem,

the simpler solution wins.

---

# Principle 16

Consistency Over Creativity

Every repeated interaction behaves identically.

Users should never relearn the interface.

---

# Principle 17

One Responsibility Per Component

Every screen,

service,

class,

repository,

and engine

has one responsibility.

---

# Principle 18

Business Logic Belongs to the Domain

Presentation displays.

Data stores.

Domain decides.

---

# Principle 19

Features are Independent

Each feature should evolve independently.

Features communicate through contracts.

Never through implementation details.

---

# Principle 20

User Trust is Sacred

The application must never:

- lose progress
- manipulate users
- generate fake achievements
- hide important information
- misuse notifications

User trust has higher priority than engagement metrics.

---

# Final Rule

When there is uncertainty,

choose the solution that is:

- simpler
- clearer
- easier to maintain
- more consistent
- closer to the product vision

If a solution violates these principles,

it should not be implemented.