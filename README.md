# PapersPleaseAndThanks


BUAN 315 Final Project Proposal
Sam Maloof – October 27, 2025
Project Title:
AI-Powered Document Verification Assistant for Papers, Please
Project Option:
Option 3 – Trends and Emerging Technologies in AI (Computer Vision + AI Reasoning)
Overview
 This project will design and evaluate an AI system that assists players in the game Papers, Please by automatically detecting discrepancies in immigration documents. The system will use computer-vision-based text extraction and AI-driven reasoning to flag inconsistencies such as mismatched dates, invalid issuing cities, and forged seals all under the game’s real-time time-pressure setting.
While presented as a gaming application, the project models real-world document-verification systems used in border security, finance, and compliance auditing.
Business and Practical Relevance
 The AI assistant reflects real business challenges in:
 • Border-control and immigration processing
 • Fraud and compliance checks in financial services
 • Automated claims and identity verification
 • Insurance and legal document review
By simulating these workflows in an interactive setting, the project highlights how AI reasoning and explainability can improve both speed and trust in high-stakes verification tasks.
Technical Approach
 • Computer Vision / OCR: Capture and extract structured data from screenshots using Tesseract or GPT-4 Vision API.
 • Rule Engine: Encode document-validation rules (date consistency, issuing city validity, seal authenticity).
 • AI Reasoning: Employ a large-language-model prompt pipeline to compare extracted attributes, detect anomalies, and output explanations.
 • Explainability Layer: Provide clear natural-language rationales for each flagged issue.
 • (Optional) Train pattern-recognition models to spot forged seals or doctored graphics.
AI Concepts Applied
 • Computer Vision and Optical Character Recognition
 • Structured Prompt Engineering
 • Logical Inference and AI Reasoning
 • Pattern and Anomaly Detection
 • Explainable AI (XAI) for Decision Transparency
Deliverables
 Primary Deliverable:
 A 10–15 page research and design paper including:
 • System architecture diagram and component explanations
 • Implementation methods (OCR, LLM reasoning flow, rule logic)
 • Evaluation metrics for accuracy and speed
 • Ethical and societal discussion (bias, automation of judgment, privacy risks)
 • Reflections on business applications and future enhancements
Optional Creative Artifact:
 • A short demo video or interactive prototype showing how the assistant flags inconsistencies in game screenshots.
Why This Project Matters
 This project unites my interests in AI, gaming, and real-world automation. I’ve applied computer-vision techniques in a current project, and this builds directly on that experience. Developing an AI verification tool not only deepens my understanding of applied AI reasoning but also creates a framework reusable for business contexts such as document compliance and identity validation. I also really enjoy this game. 

Expected Challenges
 • OCR accuracy on stylized or low-contrast game graphics
 • Handling edge-case rule combinations
 • Balancing automation speed with human-explainability
 • Translating game logic to real regulatory contexts







Tools bash for renumbering 
n=1
for f in *; do
  mv -- "$f" "shot_$(printf "%03d" $n).${f##*.}"
  ((n++))
done