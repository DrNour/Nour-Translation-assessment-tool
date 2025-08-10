# Nour-Translation Assessment Tool

## 🎯 Purpose
This tool helps students evaluate their English-to-Arabic translations by comparing them with a reference translation. It computes a similarity score and provides feedback using human-defined error criteria.

## 📂 How to Use

1. Download the [CSV Template](link-to-template) and fill in:
   - `Student Translation`
   - `Reference Translation`
   - (Optional) `Error Type`, `Error Severity`, and `Error Description`
2. Upload your filled CSV file into the app.
3. Click **Evaluate**.
4. Review the results:
   - Similarity Score (%)
   - Errors listed by type and severity
   - Suggestions (if any)


Accuracy Score	Fluency Score	Glossary Precision/Recall	Likely Translation Profile	Common Issues / Strengths
High (≥ 0.85)	High (≥ 0.80)	High (≥ 0.80)	Excellent translation	Faithful to source, natural-sounding, correct use of terminology. Minimal or no errors.
High (≥ 0.85)	Low (< 0.60)	High or Moderate	Literal but accurate	Overly word-for-word rendering, awkward phrasing, grammatical rigidity.
Moderate (0.65–0.84)	High (≥ 0.80)	High or Moderate	Creative but correct	Good rephrasing, natural style, but some omissions or paraphrasing reduce exact match with reference.
Moderate (0.65–0.84)	Low (< 0.60)	Low or Moderate	Weak translation	Inaccurate rendering combined with awkward structure; errors likely in both meaning and grammar.
Low (< 0.65)	High (≥ 0.80)	Low or Moderate	Fluent but inaccurate	Natural style but significant mistranslations, meaning distortions, or missing information.
Low (< 0.65)	Low (< 0.60)	Low (< 0.60)	Poor translation	Major loss of meaning, poor grammar, incorrect or missing terminology.
Any Accuracy	Any Fluency	Low Precision / Low Recall (< 0.60)	Terminology issues	Incorrect use of key terms, omission of domain-specific vocabulary. Can occur in otherwise strong translations.

## 👨‍🏫 Developer/Instructor

Dr. Nour El Din Abdelaal  
[Contact](mailto:nourabdelal@yahoo.com) | [GitHub](https://github.com/yourusername)
