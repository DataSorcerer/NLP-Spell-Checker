# NLP-Spell-Checker
A spell checking system with various NLP strategies using Python &amp; NLTK

A spell checking system is one of the most useful applications of Natural Language Processing. The objective of this task is to develop a spellchecking system, enhance it with various NLP techniques and evaluate of its performance using an annotated corpus.    
We break down this task in following sub tasks:   
**1. Task 1:** Import and prepare text data    
**2. Task 2:** Statistical analysis of text      
**3. Task 3:** Find correction candidates   
**4. Task 4:** Build a rudimentary spell checker (Baseline version)    
**5. Task 5:** Evaluation of baseline performance   
**6. Task 6:** Develop an enhanced spell checker    
**7. Task 7:** Evaluation of enhanced spell checker    

The spell checker is enhanced with following NLP techniques:   
  - Handling *Named Entities*   
  - Word Contractions (I'll/ can't/ etc.)    
  - Consider word collocations with external corpus   
  - Good-Turing and Kneser–Ney smoothing    
  - Linear interpolation of trigrams, bigrams and unigrams       


The final enhanced spell checker algorithm is around **<font color="blue">91.23 % accurate</font>** in spelling correction task. Morever, it uses smoothing and interpolation techniques that have ***lower perplexity*** than the original algorithm
