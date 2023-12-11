# COVAC_Custom-Lexicon
---

In the development of our COVAC_Custom Lexicon, we meticulously analyzed comments collected to enhance the precision of text-mining analysis concerning vaccinations. This process involved the construction of specialized dictionaries:

1. Stopword Lexicon: This lexicon includes 13,821 words - nouns, verbs, prepositions, conjunctions, and adverbs - sourced from the standard Korean dictionary. These words are characterized by their lack of direct relevance to vaccination topics.

2. Sentiment Lexicon: We created a comprehensive sentiment dictionary tailored to vaccination contexts, encompassing 15,032 words. This dictionary was expanded by incorporating words that convey emotions, such as adjectives, verbs, and adverbs. This expansion was based on an in-depth review of 14,843 sentiment-expressive words found in the KNU Korean Sentiment Dictionary. For each new word, a sentiment score ranging from −2 to +2 was assigned, denoting positive, negative, or neutral sentiments. This scoring was meticulously carried out by three researchers using a structured questionnaire.

3. CustomWords Lexicon: Focusing on terms pertinent to infectious disease management, diseases, and medications, this lexicon enhances the accuracy of both syntax and semantic analysis in the comments. It includes essential terms related to adverse reactions post-COVID-19 vaccination, such as “anaphylaxis,” “myocarditis,” “thrombosis,” and “arthritis.” These terms are selected based on their suspected causal relationships as reported by domestic medical institutions. Furthermore, we integrated 543 user dictionaries encompassing terms related to various medications (e.g., Tylenol, Ibuprofen, acetaminophen) and policies associated with infectious disease management (e.g., vaccine pass, quarantine, isolation, distancing).
