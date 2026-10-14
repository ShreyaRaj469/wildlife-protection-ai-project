# Wildlife Protection Through AI-Based Video Surveillance

## Project Overview
Wildlife Protection Through AI-Based Video Surveillance is an AI-powered project designed to analyse wildlife videos, detect animals, track their movement, estimate their species, and identify potentially risky situations.

The system combines multiple AI components into a single workflow and displays the results through a dashboard for human review.

## Objectives
- Detect animals in wildlife videos.
- Track animals across video frames.
- Estimate the species of detected animals.
- Analyse animal behaviour using video-based AI.
- Categorise potential risk levels.
- Display analysis results and supporting evidence.

## Technologies Used
- **MegaDetector V6:** Animal detection.
- **ByteTrack:** Multi-object tracking.
- **SpeciesNet:** Animal species estimation.
- **VideoMAE / behaviour inference:** Video analysis.
- **Risk Engine:** Rule-based risk categorisation.
- **Python and Dashboard/API:** Application workflow and result display.

## How It Works
1. Upload a wildlife video to the system.
2. Detect animals in sampled video frames.
3. Track detected animals across frames.
4. Estimate the species of each detected animal.
5. Analyse behaviour using the configured behaviour model.
6. Assign a risk category based on available model outputs and rules.
7. Display the results and available evidence for human review.

## Expected Outputs
- Detected and tracked animals.
- Candidate species predictions.
- Behaviour predictions.
- Risk categories such as LOW, MEDIUM, HIGH, CRITICAL or UNKNOWN.
- Supporting evidence and structured results when available.

## Limitations
The prototype demonstrates the integration of multiple AI components. Its accuracy and reliability have not yet been established through quantitative field testing on Indian wildlife videos. Behaviour predictions and risk categories should therefore be reviewed by humans.

## Future Scope
- Evaluate the system using expert-labelled wildlife videos.
- Test performance across different locations and environmental conditions.
- Improve behaviour classification and risk calibration.
- Measure false alarms, missed detections and processing time.
- Improve evidence quality and human review.

## Project Repository
This repository contains the project documentation and available source files for the wildlife-surveillance system.
