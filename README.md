# El Coleccionista - Unity WebGL Build

Este repositorio contiene el **build de producción** del proyecto "El Coleccionista", un avatar especializado en cartas de trading.

"El Coleccionista" es un avatar 3D interactivo que utiliza IA conversacional en tiempo real para responder preguntas sobre cartas de trading (Pokémon, Magic, Yu-Gi-Oh, etc.). 

### Características principales:
- **Push-to-Talk** - Habla con el avatar usando tu micrófono
- **Subtítulos sincronizados** - Texto sincronizado con la voz del avatar
- **Animaciones expresivas** - El avatar reacciona según el estado de la conversación
- **Conversación natural** - Powered by Groq LLM (Llama 3.3 70B)
- **Voz realista** - ElevenLabs Text-to-Speech

## 🛠️ Stack Tecnológico

- **Frontend:** Unity WebGL + Ready Player Me
- **Backend:** Node.js + Express ([REPO DEL SERVER](https://github.com/GonzaloAsencio/avatar-backend))
- **APIs:** Groq (LLM) + ElevenLabs (STT/TTS)
- **Deploy:** Vercel (frontend) + Render (backend)

## 📂 Repositorio Completo

Para ver el código fuente completo, documentación técnica y arquitectura del sistema:

**[[REPO DEL FRONT](https://github.com/GonzaloAsencio/project-new-light))**

## 💡 Cómo Usar

1. Haz clic en el botón **"Start"** (se pondrá rojo cuando esté activo)
2. **Opción A - Voz:** Mantén presionado el botón de micrófono y habla (ej: "Cuéntame sobre Charizard")
3. **Opción B - Texto:** Escribe tu mensaje en el campo de texto y presiona Enter
4. El avatar procesará tu pregunta y responderá con voz y subtítulos
5. Presiona **"Stop"** para finalizar la conversación
