- [[Byte Pair Encoding]]
- ## 1. Tokenization (breaking text into pieces)
  
  Imagine you have a big sentence:
  
  **“I love chocolate ice cream.”**
  
  A computer can’t understand the whole sentence the way humans do.
  
  So first, we **break it down into smaller chunks** called **tokens**.
- ### Different ways to tokenize:
- **By words:**
  
  → [“I”, “love”, “chocolate”, “ice”, “cream”]
- **By sub-words (common in AI models):**
  
  → [“I”, “love”, “choco”, “late”, “ice”, “cream”]
- **By characters:**
  
  → [“I”, “l”, “o”, “v”, “e”, …]
  
  Think of **tokens as Lego blocks 🧱** that we use to build and understand language.
-
- After tokenization [[Embeddings]] comes into play
-