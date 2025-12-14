# Restaurant Reservations Voice Agent (Google Calendar)

## Overview
Voice agent for restaurant table bookings (e.g., Alderaj Toronto). Handles party size, time preferences, and knowledge-based questions (allergies, seating duration). Integrated with Google Calendar via **n8n**.

## Features
- Party size and time slot booking
- Max bookings per slot limit
- Knowledge base answers (e.g., seating times, allergy handling)
- SMS confirmations
- Reschedule and cancel with confirmation

## Tech Stack
- **Voice Agent**: Retell AI
- **Calendar**: Google Calendar
- **Workflows**: n8n
- **SMS**: Twilio

## Setup Instructions
1. Connect Google Calendar via n8n nodes.
2. Set slot capacity limits.
3. Attach knowledge base in Retell AI.

## Usage
- "Table for 4 at 8 PM" → Checks availability → Books → Sends confirmation

## Demo
Refer to the attached `project_demo.pdf` for Google Calendar events, knowledge base responses, n8n workflow, and call flow.

## License
MIT
