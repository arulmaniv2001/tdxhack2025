Salesforce-Powered Smart Health Assistant: Patient Glucose Monitoring Use Case 
 
Link to our TDX Salesforce Hackathon Presentation
 - https://docs.google.com/presentation/d/10lSpLo0h_QG9Yfs1OPwQ9SevfnvvI9F-/edit?usp=sharing&ouid=104336907052833755836&rtpof=true&sd=true

Link to our Youtube recording
 - https://youtu.be/aogV-ZihCqw
 
In this Salesforce implementation, the journey begins with Agentforce readiness. The system loads critical patient glucose data and threshold levels directly from Data Cloud (integrated with Databricks), ensuring agents and bots have real-time health information at hand. When a patient reaches out, the bot identifies the intent—whether it's a general inquiry, emergency, or device-related issue. To proceed, the system verifies the patient's identity by requesting a Patient ID or Device ID. Once verified, it fetches only the relevant patient's glucose data. Next, the bot performs a real-time analysis of the patient’s current glucose level against predefined thresholds (min/max values from Data Cloud). Based on the comparison, it determines the risk level, severity, and provides personalized next steps—from suggesting medical advice to initiating emergency support. This use case showcases how Salesforce, integrated with Data Cloud and AI, creates an intelligent, responsive health support experience—improving patient care, enabling fast decision-making, and ensuring safety through proactive engagement.
