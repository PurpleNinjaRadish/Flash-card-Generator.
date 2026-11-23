# Word Flash Card Maker

A single-file web page for making printable vocabulary flash cards and worksheets on US Letter paper.

- **Flash cards:** the front shows the word centered. The back shows the word small at the top, then the definition and pronunciation. Cut lines are dotted, with adjustable bleed and cut-line position. Each back card is rotated 180° so it lines up behind its front when the sheet is flipped.
- **Worksheets:** word sets with three layouts: full practice (word, boxes and lines), word list (adjustable columns and rows, words only), and write (a line beside each word for a definition, or below it for a sentence). Random high-frequency words can be added to a set.
- **Printing:** the save button creates a print file. Open it and print at 100% on Letter paper.
- **Use:** open `index.html` in any modern browser. Settings are saved in that browser. Word lists can be pasted one per line as `word | definition | pronunciation`.
- **Generate lists with AI:** pick a provider in the Cards section and paste its API key. Supported: Claude, OpenAI, Google Gemini (free key), Groq (free key), OpenRouter (free models), Mistral, and local models through Ollama, LM Studio, or any OpenAI-compatible server such as llama.cpp. The key is kept for the browser session only unless you tick Remember, and it is sent only to the provider you choose. Never commit a key to this repository.
