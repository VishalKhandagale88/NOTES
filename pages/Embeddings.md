## 2. Embeddings (turning tokens into meaning)

Once we have tokens, we still need to make them **understandable for a computer**.

Computers don’t “get” words, they get **numbers**.

So, we **turn each token into a list of numbers** (a vector).

That list captures the **meaning** of the word.
- ### Example:
- “king” → [0.21, 0.87, -0.44, …]
- “queen” → [0.19, 0.85, -0.40, …]
  
  Notice how **“king” and “queen” end up with numbers that are close together** — because they have related meanings.
- ## 🧠 Why embeddings are powerful
  
  Embeddings let AI **understand relationships** between words:
- “king - man + woman ≈ queen”
- “Paris is to France” like “Tokyo is to Japan”
  
  It’s like mapping every word into a giant **3D map of meaning**, where similar words are near each other.