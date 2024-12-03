
#ConstructionSafety: PPE Detection and Alert System

This project leverages YOLOv8 and YOLOv9 models to detect personal protective equipment (PPE) in construction environments using images and videos. It integrates Twilio API for automated WhatsApp alerts and provides a Streamlit-based interface for monitoring and downloading detection results.

#Features:

YOLOv8 and YOLOv9 Models: Trained on Colab, achieving 90% accuracy for detecting PPE such as helmets, vests, gloves, etc.
Twilio API Integration: Sends automated WhatsApp alerts when PPE is missing in the detected images or videos.
Streamlit Interface: Users can upload media, view detection results, and download the output.
Optimized Performance: The models are fine-tuned for speed and scalability, ensuring real-time monitoring.
Seven PPE Classes Detected: Including helmet, vest, gloves, boots, goggles, ear protection, and mask.
