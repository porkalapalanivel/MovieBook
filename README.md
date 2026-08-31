# Movie Ticket Booking Management Application

## Description
A Pega application for booking movie tickets. Customers can submit ticket requests with movie name, show date, show time, and number of tickets.

## Case Type: Movie Ticket Request
### Stages:
1. Request Intake - Collect ticket request details, verify customer info
2. Ticket Processing - Check availability, reserve seats, calculate cost
3. Payment Review - Process payment, approve transaction
4. Ticket Fulfillment - Generate tickets, send confirmation
5. Request Closure - Update status, close request

## Fields
- Movie Title
- Show Date
- Show Time
- Number of Tickets
- Customer (Data Reference)
- Payment Method (Data Reference)

## Technology
Built using Pega Infinity '25.1.3 with Autopilot-assisted case design.
