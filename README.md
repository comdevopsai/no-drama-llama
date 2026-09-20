# No Drama Llama Talking Demo

## Run

Open `index.html` directly in a modern browser.

For the most reliable behavior, serve it locally:

```bash
cd llama_talking_demo
python3 -m http.server 8000
```

Then open:

http://localhost:8000

## Visemes

- REST
- M/B/P
- A/AH
- E/EE
- O
- U/W/Q
- F/V
- L

The demo uses a simple heuristic text-to-viseme mapper and browser speech synthesis.
For production-quality lip sync, replace the heuristic timing with phoneme/viseme timestamps from your TTS pipeline.
