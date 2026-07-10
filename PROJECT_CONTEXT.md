# PROJECT CONTEXT

Project Name

Talia

Version

1.0.0

---

# Purpose

Talia is a Local-First Quran platform designed to help Muslims build a long-term relationship with the Quran through reading, memorization, review, and progress tracking.

The application is designed to work completely offline, with cloud synchronization used only for backup, multi-device support, and parent features.

---

# Product Vision

The Quran is the center of the application.

Everything else exists to help the user interact with the Quran consistently.

The product is not a habit tracker.

The product is not a gamification app.

The product is not a social network.

The product is a Quran platform.

---

# Target Users

Adult users

Users who want to memorize the Quran using a structured scientific system.

Children

Children who learn through a game-based experience while using the same memorization engine.

Parents

Parents who want to follow their children's progress without interfering with the memorization process.

Readers

Users who only want to read the Quran.

---

# Main Experiences

Reading

A distraction-free Quran reading experience.

Memorization

Daily memorization sessions.

Review

Long-term retention through scheduled review.

Progress

Track memorization, reading, consistency and achievements.

Kids

Game-based experience powered by the same memorization engine.

Parent

Read-only dashboard for following children's progress.

---

# Navigation

The application contains four primary tabs.

Home

Personal dashboard powered by Smart Coach.

Quran

Reading experience.

Memorization

Memorization, review and sessions.

Progress

Progress, achievements, statistics and journey.

No additional primary tabs are allowed.

---

# Product Principles

Reading and memorization are separate experiences.

Both use the same Quran data.

The user should never lose progress.

Offline functionality has higher priority than cloud functionality.

The application minimizes user decisions whenever possible.

The system decides whenever it can.

The user decides only when necessary.

---

# Smart Coach

Smart Coach is the decision engine of the application.

It answers one question.

"What should the user do now?"

Smart Coach never teaches.

Smart Coach never evaluates.

Smart Coach only recommends the next best action.

---

# Memorization Philosophy

Memorization is based on:

Assessment

↓

Review

↓

Long-term retention

Not on counting pages or verses.

Quality is always more important than quantity.

---

# Kids Philosophy

Kids Mode is not another memorization engine.

Kids Mode is another presentation layer.

Everything shown to the child maps to the real memorization engine.

---

# Parent Philosophy

Parents monitor.

Parents encourage.

Parents do not modify memorization results.

---

# Data Philosophy

The application is Local First.

Every action is saved locally first.

Cloud synchronization happens later.

Cloud never blocks user interaction.

---

# Source of Truth

Every type of data has exactly one source of truth.

Progress is always calculated.

Never duplicated.

---

# Architecture

Presentation

↓

Domain

↓

Data

↓

Infrastructure

Business logic exists only inside Domain.

---

# State Management

Cubit

Single source of state.

No business logic inside UI.

---

# Database

Local Database

Isar

Cloud Backend

Supabase

---

# Sync Model

Local Save

↓

UI Update

↓

Sync Queue

↓

Cloud Synchronization

↓

Confirmation

---

# Non-Goals

The application is not intended to become:

A social media platform.

A competitive leaderboard application.

A messaging application.

A productivity application.

Every feature must directly support interaction with the Quran.

---

# Documentation Structure

This repository is the single source of truth for the project.

No implementation should be started before consulting the documentation.

If documentation conflicts with implementation:

Documentation wins until officially updated.

---

# Documentation Priority

PROJECT_CONTEXT.md

↓

PRODUCT_PRINCIPLES.md

↓

Architecture Decisions

↓

Product Documentation

↓

Engineering Documentation

↓

Implementation

---

# Definition of Success

A user can:

Read the Quran consistently.

Memorize using a structured scientific approach.

Retain memorization over the long term.

Continue using the application without internet.

Recover all data after login.

Move between devices safely.

Experience a simple, distraction-free interface.