# First Day Objectives - Welcome to the Lab!

**Date:** Monday, August 18th, 2025  
**New Lab Member:** Rhiana Rutherford  
**Role:** PhD Student - Experimental Lead, tFUS-Fiber Photometry Project  

---

## Morning Session (9:30 AM - 12:00 PM)

### 1. Welcome & Lab Introduction
- [ ] **Meet with Jacek ** - Initial welcome and overview
- [ ] **Lab tour** - Familiarize with:
    - Rhiana's workspace
      - TODO: Discuss laptop preferences + peripherals
    - Main experimental space
    - Surgery location: Corner desk with stereotaxic frame
    - Fiber photometry setup: Round desk (equipment in Jacek's office)
    - Behavior testing: 
      - Current: Round desk
      - Future: Shielded Faraday cage
    - Equipment storage: currently in Jacek's office (gray boxes)
- [ ] **Key card access**
    - TODO: identify vendor, contact them to get info on purchasing card printer
- [ ] **Other Lab Members** 
    - All part-time except for Jacek and Rhiana
    - Admin: Brian Avila (great resource)
    - Surgery + Fiber Photometry Tech: Federico Gnazzo (now at Regeneron)
    - Undergrad RA: Mila Edwards (has been involved in surgeries/fiber photometry/tFUS
    - BME Undergrads who may be around (desks adjacent to my office): 
      - Emily Valera 
      - Anthony Mathai

### 2. Project Overview Discussion
- [ ] **Scientific Context** - Review with PI:
  - Ultimate vision: closed loop control of brain state
    - Record brain state
    - Decode current state
    - Compute optimal stimulation parameters
    - Deliver stimulation
    - Repeat
  - Core Techniques
    - Transcranial Focused Ultrasound (tFUS)
      - Low-intensity ultrasonic pressure wave delivered through the skull
      - Excellent spatial resolution (~1 mm)
      - Non-invasive, no ionizing radiation
      - Can reach deep brain structures
      - Challenge: identify mechanism of action and develop control strategies for driving brain to desired states
      - The lab has both a human (Sonic Concepts NeuroFUS, CTX 500) and rodent (Sonic Concepts SU-132, DIY transducer stack) tFUS system
    - Fiber Photometry (FP)
      - Adeno-Associated Virus (AAV) Surgery
      - Viral vector delivery of genetically encoded calcium indicators (GECIs)
        - Right now we are working with a red dopamine sensor, but this is flexible
      - Allows monitoring of neural activity in specific cell populations
      - Fiber optic cable implanted in brain region of interest
      - FP system detects fluorescence changes during neural activity 
    - Stochastic Thermodynamics
      - The framework that we are using to understand tFUS' effects on brain state
      - Warning: it's dense and mathematical, but you will not be required to become an ST expert
        - ST is one of the tools for this project, but it's not the central one (that being tFUS)
      - An emerging field that extends classical thermodynamics to small systems far from equilibrium
      - Focuses on energy flow, entropy production, and state-space perturbations
      - Collaboration with Dr. David Wolpert (Santa Fe Institute)
  - Project aims and hypotheses
    - Loosely speaking, we want to understand how tFUS perturbs brain state, and how we can leverage this to drive brain state in a desired direction
    - Hypothesis: the brain is a dynamic non-equilbrium system, and we need to understand its dynamics in order to control it with tFUS
  - Current funding:
    - NIH R16 terminating 06.30.2026
      - Renewal application in May 2026
  - Proposals
    - NSF CRCNS grant: 
      - Deadline: Nov 12 2025
      - Aims(https://docs.google.com/document/d/1Ce6Qh02gLD-YUBnsO6Rphmu0VeKlZGydA_m2UhPdsYM/edit?usp=sharing)
      - Collaboration with Dr. David Wolpert (Physicist, Santa Fe Institute)
    - Looking at other funding opportunities (proposal will be similar to CRCNS)
  
- [ ] **Your Role**
  - Primary responsibility: Experimental Lead
  - Expected contributions to grant preliminary data
  - Publication expectations and authorship discussions
- [ ] **Immediate Priorities** (Next 2-4 weeks):
  1. Complete all required training modules
  2. Shadow existing procedures
  3. Begin literature review (see reading lists)
  4. Establish baseline competency in core techniques

### 3. Administrative Setup
- [ ] **IT Setup**
  - CCNY email account verification
  - TODO: Lab Slack workspace invitation and setup
  - Discuss use of Notion for project management
  - GitHub account creation/verification for lab repositories
  - Access to shared lab drives and cloud storage
    - [Lab Google Drive](https://drive.google.com/drive/folders/1_BhO-ryK10HTxUtNxiBLqNIjJ9VrNzf8?usp=drive_link)
    - [Lab GitHub Boilerplate]: (dmochow.github.io/focused-ultrasound-lab-wiki])
      - Work in progress, but will hopefully become the single source of truth for the lab
- [ ] **IACUC Documentation**
  - Share current IACUC protocol
  - TODO: Schedule IACUC training with Harry Acosta (hacosta007@ccny.cuny.edu)


---

## Afternoon Session (1:00 PM - ?)

### 4. Documentation & Resources Review 
- [ ] **Navigate Lab Wiki Together**
  - Together: create reading lists for fiber photometry and tFUS
  - Understand milestone tracking system
- [ ] **Communication Protocols**
  - Discuss Slack for communication (alternative: google chat)
  - Weekly meeting schedule
- [ ] **AI Resources**
  - Use of AI tools is highly encouraged
  - ChatGPT/Claude/Claude Code for lit search, learning new concepts, coding
  - NotebookLM for literature synthesis (deep dive podcast feature for hard papers)
  - TODO: discuss currently available AI tools and consider lab-paid subscriptions

### 5. Initial tasks
- [ ] **Background Reading**
  - Murphy papers on fiber photometry and tFUS
  - tFUS review papers
  - Primer on Fiber Photometry
- [ ] **Hands-On Task: Learning Operant Chamber**
  - Lafayette Instruments operant chamber
  - Familiarize with basic operation and data collection
  - We will probably need to schedule a call with Lafayette Instruments for training
- [ ] **Hands-On Task: Learning GitHub**
  - Together: find a YouTube tutorial on GitHub basics