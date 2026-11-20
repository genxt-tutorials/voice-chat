# Voice Chat for LFM3-Omni

A free, one-file web page for talking to **LFM3-Omni-2B** (Liquid AI) out loud, with **llama.cpp** running on your own
PC. No graphics card needed. The page talks only to the model on your own computer
(`ws://127.0.0.1:9931/v1/realtime`, llama.cpp's realtime API).

**Download:** https://genxt-tutorials.github.io/voice-chat/ · **Video:** https://youtu.be/STBPdVs_muE

## How to use it on Windows

1. Right-click Start, open Terminal: `winget install llama.cpp`
2. In a new Terminal: `llama serve -hf LiquidAI/LFM3-Omni-2B-GGUF:Q4_K_M --reasoning off --temp 0`
   (downloads about 1.4 GB the first time; wait for "listening", keep it open)
3. Open `voice-chat.html` in Edge or Chrome, press the microphone, allow it, and talk.

Settings on the page: female or male voice, the instructions, the spoken language, the server address. You can also
type messages and save each spoken answer as a WAV file.

Made by Genxt Tutorials (YouTube). MIT licence. Not made by or affiliated with Liquid AI or llama.cpp.
