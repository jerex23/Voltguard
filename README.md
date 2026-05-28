# Voltguard
AI-powered outage prediction that warns you before the lights go out.


## The Problem

Across much of Africa, power outages are daily events with no warning. 
Computers crash, inverter batteries die, medical equipment loses power, 
and businesses shut down unprepared. VoltGuard changes that.

## What VoltGuard Does

VoltGuard connects to your power infrastructure (smart meter, inverter, 
changeover switch) and monitors real-time electrical characteristics. 
Combined with historical outage data, crowd-sourced reports, and weather 
signals, our AI model predicts outages before they happen — then sends 
You specific, actionable advice on what to do.

**Core capabilities:**
- Outage prediction with time estimates and confidence scores
- Appliance shutdown recommendations based on your registered devices
- Inverter and battery protection guidance
- Business downtime planning alerts
- Multi-channel delivery: push, SMS, WhatsApp, email

## Architecture

See `/docs/architecture.md` for the full system design.

Layers: IoT ingestion → Event stream → AI prediction core → 
Advisory engine → Multi-channel delivery

## Target Users

- Students and remote workers dependent on laptops and internet
- Small businesses (print shops, salons, restaurants)
- Households with medical equipment
- Hospitals and critical infrastructure operators
