Inkphora Stroke-Based Emotional Embedding:
A Non-Biometric Model for Valence–Arousal Estimation and Creative Emotional Output
Autore: Maria Irene Marchetti— Inkphora Project

Abstract
This document provides an initial public disclosure of the Inkphora/Thymiko stroke-based emotional inference model.
The system estimates emotional valence and arousal from freehand touchscreen gestures, using non- biometric, anonymous motion features. The output embedding can be used for creative AI generation, adaptive interfaces, emotional recommendation systems, and multimodal interaction design.
This document establishes conceptual and methodological priority for the model.

        1. Motivation
Most existing emotion-detection methods rely on:
• facial analysis,
• voice prosody,
• physiological sensors,
• or text sentiment.
These approaches are invasive, biased, or impractical.
Inkphora introduces an alternative: emotion inference from freehand gesture, a universal human modality that preserves anonymity and does not rely on identifiable biometrics.
The goal is to provide a lightweight, scalable method for affective computing and human–AI interaction.

        2. Input Modality: Freehand Stroke
Users draw freely on a touchscreen or trackpad for ~20 seconds. No personal data, no image, and no identifying metadata are stored.
Extracted features include:
• total stroke length
• average speed
• speed variance
• pause ratio
• rhythm patterns
• left–right bias
• direction changes
• optional pressure/tilt when available
These features form the Stroke Feature Vector (SFV).
                           
         3. Emotional Mapping (Valence–Arousal Model)
The system uses a lightweight mapping to estimate:
• Valence (positive ↔ negative affect)
• Arousal (calm ↔ active state)
The mapping can be heuristic, regression-based, or MLP-based.
This document establishes the existence of the model but does not disclose internal thresholds or weights.
The output is the Inkphora Emotional Embedding (IEE) — a 2D or multidimensional vector.

        4. Creative Output Layer
The emotional embedding conditions different engines:
• poetic text generation (LLMs)
• symbolic music recommendation
• adaptive color and motion patterns
• UI emotional adaptation
• multimodal AI conditioning
No clinical interpretation is intended.
The system is designed for creative and wellbeing contexts only.
        
        5. Privacy & Anonymity
The method:
• does not capture the user’s identity
• does not process facial/voice/biometric signals
• does not store raw images (only numeric features)
• is fully anonymous by design
        
        6. Applications
Examples include:
• creative AI companions
• adaptive UI
• emotional recommendation engines
• affective input for games
• ritual- and wellness-based experiences                           
• emotional taste mapping (food)
• emotional activity suggestions
• multimodal conditioning models
• B2B affective APIs
        
        7. Prior Art and Conceptual Priority
This document establishes the date and authorship of the Inkphora gesture-based emotional embedding model.
Further refinements, models, and datasets will be disclosed progressively, while code implementations may remain private.
        
        8. Author & Project
Name: Maria Irene Marchetti
Project: Inkphora / Thymiko
Website: inkphora.ai
Contact: info@inkphora.ai / beta@inkphora.ai
Date: December 2025
                    
