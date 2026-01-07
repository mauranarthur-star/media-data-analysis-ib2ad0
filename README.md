Instagram Competitive Intelligence: Deep Learning & Strategic Optimization
Author: Arthur Mauran

Project ID: IB2AD0 - Data Science & AI

Focus Channel: Sporf

Benchmarks: SportBible, Goal Global

1. Executive Pitch: The Data-Driven Growth Opportunity
In the high-velocity world of football media, engagement isn't just a vanity metric—it is a byproduct of speed and emotional resonance. This project analyzes approximately 3,000 posts and tens of thousands of comments to determine why legacy rivals consistently out-median the focus channel (Sporf).

By utilizing Deep Learning (Transformer-based NLP) and Structural Gap Analysis, I identified a specific operational mismatch. Correcting this mismatch represents a 70,000+ monthly "Recoverable Likes" opportunity for Sporf, achievable through timing optimization and tactical theme alignment.

2. The Production Pipeline (From 41 Scripts to 1 Engine)
The development phase involved 41 specialized Python scripts in Visual Studio Code to handle API orchestration and modular logic. For the final portfolio, these were refactored into a streamlined 6-Stage Pipeline to demonstrate production-grade coding standards.

Stage A: Data Architecture

01_Data_Acquisition.py: Merges raw Apify JSON/CSV exports with comment datasets using universal URL mapping.

02_Temporal_Features.py: Engineers "Velocity Metrics," including time-to-first-comment (Deltas) and first-hour engagement rates.

Stage B: AI & NLP (Deep Learning)

03_Content_AI_Tagging.py: Integrates GPT-4o-mini via the OpenAI API for zero-shot thematic classification of post captions.

04_Deep_Learning_NLP.py: Implements the RoBERTa (GoEmotions) Transformer model to classify 27 distinct emotional states in fan comments.

Stage C: Strategic Benchmarking

05_Market_Analytics.py: Measures market health using Gini Coefficients and Lorenz Curves to identify engagement inequality.

06_Strategic_Optimization.py: The "Business Intelligence" layer. Benchmarks Sporf against rival medians to quantify specific Recoverable Likes per hour/theme.

3. Methodology: Folder 04 Deep Learning Requirements
Thematic Tagging (LLM)

Rather than manual tagging, I built an automated classifier using GPT-4o-mini. It categorizes content into 8 strategic buckets (e.g., Transfers, Scandal, Humour) based on a custom priority-signal hierarchy.

Emotion Detection (Transformers)

To move beyond basic "Positive/Negative" sentiment, I utilized the roberta-base-go_emotions model. This allowed for the detection of nuanced states like Admiration, Disapproval, and Curiosity.

4. Strategic Insights & Findings
I. Engagement Inequality (Lorenz Curve Analysis)

We calculated the Gini Coefficient for all three channels. While SportBible has the highest raw reach, it also shows the highest inequality—meaning it relies heavily on a few "viral lottery" posts. Sporf maintains a lower Gini, indicating a more stable, loyal core community.

II. The First-Mover Premium

By creating Event Windows (competitive groups of posts on the same news break), we proved that the First-to-Post channel receives a 240% engagement premium. Sporf's primary gap is not content quality, but release velocity in breaking news cycles.

III. Theme Efficiency (The "Humour" Advantage)

Heatmap analysis reveals that Sporf's Efficiency Ratio (Theme Mean / Channel Mean) is highest in Humour & Offbeat (1.2x). However, it is significantly under-activated in Breaking News/Scandal, where rivals gain the most "algorithmic oxygen."

5. Repository Structure
/data: Cleaned datasets and the final Strategic Blueprint (Excel).

/scripts: The 6 master pipeline scripts (and a zip of the 41 original production files).

/visuals: PNG exports of Gini curves, efficiency heatmaps, and sentiment distribution charts.

6. Setup & Reproducibility
Clone the Repo: git clone [url]

Install Requirements: pip install pandas transformers openai openpyxl

Environment: Ensure OPENAI_API_KEY is configured in your terminal session.

Execute: Run scripts 01 through 06 in sequential order to replicate the full analysis
