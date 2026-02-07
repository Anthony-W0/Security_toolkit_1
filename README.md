# Security_toolkit_1

#Overview
This project evaluates LLM Guard as a security toolkit for protecting Large Language Model (LLM) applications. The focus is on detecting and reducing risks such as prompt injection, sensitive data leakage, and harmful content through hands-on experimentation.

## Project Goal
- Understand common security risks in LLM-based systems
- Use LLM Guard to analyze and filter unsafe prompts and outputs
- Demonstrate detection of prompt injection and harmful inputs
- Document strengths and limitations of the tool

## How it works
LLM Guard acst as a security layer around LLM inputs and outputs.
In this project:
1. A prompt or dataset is provided as input
2. LLM Guard analyzes the content using security rules and detectors
3. Unsafe content is flagged, filtered, or sanitized
4. Results are recorded and analyzed

This workflow helps identify how LLM Guard can reduce risks before prompts reach an LLM or before outputs are shown to users.

## Repo Structure
- scripts/ : runnable demo scripts
- notebooks/ : experiments
- data/ : test prompts / small datasets
- results/ : outputs, screenshots, tables
- report/ : written report files
- docs/ : diagrams and notes

## Milestone 1 Alignment 
This repository supports Milestone 1 - Code Replication & Walkthrough by:
- Identifying the security problem (LLM prompt-based attacks)
- Demonstrating how LLM Guard uses LLM-related techniques for defense
- Showing input → processing → output behavior
- Providing reproducible demos and documented results

## Current Status 
- Repository initialized
- Project structure defined
- Tool exploration and demos in progress

## Setup 
Setup instructions will be added, including:
- Python enviroment configuration
- Required dependencies
- Steps to run demo scripts
