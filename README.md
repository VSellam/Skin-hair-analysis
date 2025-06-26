# Skin-hair-analysis
This dataset contains structured records on dermatological and trichological health across 2,000 anonymized individuals from the Indian population. It supports AI/ML research in personalized care, dermatology, and lifestyle-linked skin health. Data is divided across diagnostic results, lifestyle factors, and AI-generated care recommendations.

Skin & Scalp Health Dataset (Indian Population)
Introduction: The Problem We’re Addressing Skin and scalp health issues are among the most common yet overlooked conditions affecting individuals across India. These conditions are deeply influenced by personal lifestyle, environmental factors such as pollution and humidity, and regional variations in skin tone and hair type. Despite this complexity, most existing diagnostic and care models rely on generalized approaches that fail to account for this diversity.
There is a growing demand for personalized, data-driven dermatological care that is context-aware and capable of adapting to the individual needs of patients. To meet this need, healthcare providers and AI developers require access to reliable, structured data that reflects the lived realities of the target population.

This dataset has been developed to support:
•	AI model development for image-based skin and hair diagnostics
•	Clinical and academic research on dermatological patterns across diverse Indian demographics
•	Education and training in applying machine learning to personalized healthcare
It captures a comprehensive view of each individual, combining diagnostic outcomes, lifestyle factors, and care recommendations. By focusing on an Indian population, the dataset enables context-specific insights that can inform more accurate and equitable health solutions.
 
📊 Dataset Summary
1. skin_scalp_diagnostics.csv
This dataset contains diagnostic-level information generated through AI analysis of skin and scalp conditions.
Fields:
•	user_id: Unique, anonymized hospital-style identifier
•	gender: Male or Female
•	age: Age of the individual
•	skin_type: Dry, Oily, Combination, or Normal
•	skin_tone: Fair, Wheatish, Brown, Dusky, or Dark
•	acne_score: Score from 0 (none) to 5 (severe)
•	wrinkle_score: Score from 0 (none) to 5 (deep wrinkles)
•	pigmentation_score: Score from 0 (none) to 5 (heavy pigmentation)
•	texture_irregularity_score: Score from 0 (smooth) to 5 (highly uneven texture)
•	scalp_condition: Normal, Oily, Dandruff, or Dry
•	scalp_sensitivity: Score from 0 (no sensitivity) to 5 (very sensitive)
•	hair_density: Measured in hairs per cm²
•	hair_thickness: Hair strand thickness in microns
•	diagnosis_confidence: AI confidence score (0.0–1.0)
•	diagnosis_date: Date of diagnostic assessment
 
2. lifestyle_data.csv
This file provides lifestyle and behavior factors that could affect dermatological health outcomes.
Fields:
•	user_id: Same identifier as in diagnostic file
•	diet_type: Vegetarian, Mixed, Vegan, or Keto
•	smoker: True or False
•	alcohol_consumption: None, Rare, or Regular
•	stress_level: Self-reported scale from 1 (low) to 10 (high)
•	sleep_hours: Average sleep per night in hours
•	water_intake_liters: Daily average water intake in liters
•	exercise_frequency: None, 1–2x/week, 3–5x/week, Daily
•	skincare_routine_level: Score from 0 (none) to 3 (extensive)
•	satisfaction_score: Score from 1 (low) to 5 (high)
•	perceived_improvement_score: Self-assessed progress from 0 to 5
 
3. ai_recommendations.csv
Logs AI-generated recommendations for skincare and haircare, as well as follow-up compliance metrics.
Fields:
•	user_id: Matches other datasets
•	recommendation_type: Skincare, Haircare, Diet, or Lifestyle
•	recommended_product: Name of the product or suggestion
•	product_type: Serum, Cleanser, Supplement, Oil, or Tool
•	target_issue: The primary concern being addressed (e.g. Acne, Wrinkles, Pigmentation)
•	confidence_score: Confidence of AI in the recommendation (0.0–1.0)
•	accepted_by_user: Whether the user accepted the recommendation (True/False)
•	compliance_rate: Percentage of adherence to the recommendation (0.0–1.0)
•	followup_result_score: Outcome score based on follow-up results (0–5)
•	days_until_followup: Time between recommendation and follow-up in days
 
🎯 Applications
These datasets can be used for:
•	Teaching AI and data science in healthcare contexts
•	Research in dermatology and cosmetology
•	Prototyping ML pipelines for personalized care systems
•	Simulating patient data in clinical or academic environments
 
⚠️ Disclaimer
This dataset is intended for academic, training, and research purposes only. No personally identifiable information is included.
 
👨‍🏫 Authors & Attribution
Compiled and curated under the guidance of Dr. V. Sellam, SCOPE, VIT-Chennai.
For inquiries or contributions, please open an issue on this repository.

![image](https://github.com/user-attachments/assets/4226e9f2-95fb-494b-bf0c-2a67dad39665)
