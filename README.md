# 🎶 AI Music Compositor with LangChain, LangGraph & GenAI  

This project demonstrates how to build an **AI-Powered Music Compositor** using **LangChain**, **LangGraph**, and **Generative AI models**. The system generates **melody, harmony, rhythm, and style-adapted compositions**, and then converts them into **MIDI files** for playback.  

---

## 🚀 Key Components  

- **State Management** → Uses a `MusicState` class to manage workflow state.  
- **Language Model** → Employs the **LLaMA-3.3 (Groq)** model for generating musical elements.  
- **Musical Functions**  
  - 🎵 *Melody Generator*  
  - 🎼 *Harmony Creator*  
  - 🥁 *Rhythm Analyzer*  
  - 🎨 *Style Adapter*  
- **MIDI Conversion** → Transforms the composition into a playable **MIDI file**.  
- **LangGraph Workflow** → Orchestrates the composition process via a **state graph**.  
- **Playback Functionality** → Uses **FluidSynth** to convert MIDI → WAV and allows **immediate playback** inside notebooks.  

---

## 📦 Installation  

First, install required dependencies:  

```bash
pip install langchain langchain_core langgraph langchain_community langchain_groq music21

---
🎯 Future Improvements

Add multi-instrument orchestration (strings, piano, drums).

Enable multi-turn conversation for refining compositions.

Support different time signatures & tempos.

Web deployment (e.g., Gradio / Streamlit app) for interactive composition.

---

📜 License

This project is licensed under the MIT License.

---
Author
SANIYA CHHABRA
