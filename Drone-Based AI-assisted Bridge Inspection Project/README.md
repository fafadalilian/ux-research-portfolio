# Drone-based AI-Assisted Bridge Inspections Project

## Project Overview
This project explores the effectiveness of AI-assisted drone-based bridge inspections compared to inspections without AI assistance. The focus is on understanding how AI impacts overall inspection accuracy, how drone piloting skills influence inspection performance, and which behaviors and cognitive states affect the probability of detecting or missing bridge damage.

<img src="graphs/human_AI_performance.jpg" alt="concept" width="70%">

## Research Questions
1. **How does AI assistance affect overall inspection accuracy?**
2. **Do drone piloting skills affect inspection performance?**
3. **What behaviors and cognitive states affect the probability of the operator missing or successfully detecting bridge damage?**

## Methodology
The research involved a controlled laboratory experiment simulating drone-based bridge inspections under two conditions: one without AI assistance (no-AI) and another with imperfect AI assistance (AI). Key elements included:

- **Participants**: 45 engineering students (31 male, 14 female) from the University of Iowa, aged 23.53 years on average.
- **Conditions**: 
  - **No-AI Condition**: Participants inspected the bridge for cracks without AI assistance.
  - **AI Condition**: An 80% accurate AI assisted participants by highlighting suspect cracks with green boxes. Participants confirmed or refuted these indications.
- **Data Collection**: Continuous EEG and eye tracking to measure brain activity and eye movements, joystick positions to capture control behavior.
- **Survey**: Participants completed a survey regarding their drone piloting experience and video gaming experience.
- **Experimental Setup**: Participants flew a drone along a simulated bridge, identifying and marking cracks, and reporting false alarms.

## Experimental Measures
- **EEG Band Powers**: Used to estimate cognitive and emotional states.
- **Eye Tracking**: Measures like fixation count, saccade count, and gaze velocity were used to assess search behavior.
- **Controller Inputs**: Right/left joystick positions were analyzed to compute stabilization and guidance input metrics.

## Analysis
Two main analyses were performed:

1. **Mixed Linear Regression**: To assess the effect of AI assistance and drone experience on inspection accuracy.
2. **Mixed Logistic Regression**: To determine the impact of biometric and behavioral metrics on the probability of missing cracks in each condition.

## Key Findings
### Q1 & Q2: The Effect of AI Assistance and Drone Piloting Experience on Inspection Accuracy
<img src="graphs/inspection_accuracy.jpg" alt="Inspection Accuracy" width="50%">

**Drone Piloting Experience**: More experience in piloting drones significantly improves inspection accuracy, suggesting that mastering piloting skills enhances overall task performance.
- **AI Condition**: In the AI-assisted condition, the AI's high accuracy (80%) helped compensate for human errors, reducing the impact of experience on inspection performance.
- **Training Implications**: Effective bridge inspection training programs should emphasize comprehensive and rigorous piloting training to ensure safety and quality of inspection.

<br>
 
**Initial AI Assistance**: Participants who started with the no-AI condition showed lower performance, while those who began with AI assistance maintained their performance even when transitioning to the no-AI condition. 
- **Training Implications**: Integrating AI assistance into inspection training programs can enhance the training process by automating tasks and providing initial learning support

### Q3: Biometric and Behavioral Correlates of P(Miss)
No AI condition:
<img src="graphs/noAI_condition.jpg" alt="The Biometric and Behavioral Factors of Missing a Crack in the No-AI Condition" width="70%">

AI condition:
<img src="graphs/AI_condition.jpg" alt="The Biometric and Behavioral Factors of Missing a Crack in the AI Condition" width="50%">

- **Inspector Cognitive State**: Specific cognitive states measured through EEG significantly affected the probability of missing a crack in both conditions. This highlights the need for careful management of cognitive load and vigilance in assistive systems and training modules.
- **Visual Scanning Strategies**: . Incorporating effective scanning strategies and gaze patterns into bridge inspection training ensures a systematic approach to visual inspection and can enhance the training process.

## Conclusion
This study highlights the importance of integrating AI assistance in bridge inspection training programs and suggests that understanding cognitive load and visual scanning strategies can enhance inspection accuracy. The findings support the development of AI-based training programs and cognitive monitoring systems to optimize inspector performance and safety.
