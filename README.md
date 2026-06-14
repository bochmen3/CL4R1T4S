# boch-clarity 🔍

**Centro de Transparencia de Sistemas de IA** - Documentación centralizada de prompts del sistema, directrices y herramientas de principales laboratorios de IA.

> *"Para confiar en el resultado, debes entender la entrada."*

---

## 📖 Descripción

`boch-clarity` es un repositorio dedicado a documentar y compartir información sobre los prompts del sistema utilizados por:

- **OpenAI** (ChatGPT, GPT-4, etc.)
- **Anthropic** (Claude)
- **Google** (Gemini, Bard)
- **xAI** (Grok)
- **Perplexity**
- **Cursor & IDEs** (Windsurf, etc.)
- **Herramientas de IA** (Devin, Manus, Replit, etc.)

---

## 🎯 ¿Por qué existe esto?

Los laboratorios de IA utilizan arquitecturas masivas de prompts no visibles que definen:

- ✋ **Limitaciones** - Lo que los AIs no pueden hacer o decir
- 🎭 **Comportamientos** - Personas y funciones forzadas
- 📋 **Restricciones** - Cómo se les ordena mentir, rechazar o redirigir
- ⚖️ **Marcos éticos** - Disposiciones políticas y éticas preestablecidas

**El problema:** Cuando interactúas con un IA sin conocer su prompt del sistema, no estás hablando con una inteligencia neutral, sino con un títere manipulado.

**La solución:** `boch-clarity` existe para cambiar eso.

---

## 📁 Estructura del Repositorio

```
boch-clarity/
├── README.md                    # Este archivo
├── CONTRIBUIR.md                # Guía de contribución
├── LICENCIA                     # AGPL-3.0
│
├── prompts/                     # Prompts del sistema documentados
│   ├── openai/
│   │   ├── chatgpt-gpt4.md
│   │   └── ...
│   ├── anthropic/
│   │   ├── claude-3.md
│   │   └── ...
│   ├── google/
│   │   ├── gemini.md
│   │   └── ...
│   └── otros/
│
├── docs/                        # Documentación
│   ├── guia-extraccion.md      # Cómo extraer prompts
│   ├── verificacion.md         # Verificación de autenticidad
│   └── etica.md                # Consideraciones éticas
│
└── utils/                       # Herramientas útiles
    ├── parser.py               # Analizar prompts
    └── validador.py            # Validar contenido
```

---

## 🚀 Cómo Contribuir

¿Tienes prompts filtrados, extraídos o ingeniería inversa? Excelente. Abre un Pull Request con:

### Formato Requerido

```markdown
## [Nombre del Modelo / Producto]

**Fuente:** [OpenAI/Anthropic/Google/etc]
**Versión:** [ej: GPT-4 Turbo, Claude 3.5 Sonnet]
**Fecha de Extracción:** YYYY-MM-DD
**Método:** [Jailbreak/Filtración/Ingeniería Inversa/Documentación Oficial]

**Contenido:**
[Inserta el prompt aquí]

**Notas:**
- [Contexto adicional]
- [Observaciones relevantes]
- [Cambios vs versión anterior]
```

### Pasos:

1. **Bifurca (Fork)** este repositorio
2. **Crea una rama**: `git checkout -b feat/nuevo-prompt`
3. **Agrega tu contenido** en la carpeta correspondiente
4. **Actualiza** el índice si es necesario
5. **Abre un PR** con descripción clara

### Requisitos:

- ✅ Nombre del modelo/versión
- ✅ Fecha de extracción (si se conoce)
- ✅ Contexto/notas opcionales
- ✅ Verificación de autenticidad (si es posible)

Para más detalles, consulta [CONTRIBUIR.md](CONTRIBUIR.md).

---

## 📊 Contenido Actual

| Laboratorio | Modelos Documentados | Última Actualización |
|------------|---------------------|---------------------|
| OpenAI | ChatGPT, GPT-4, GPT-4V | - |
| Anthropic | Claude 3.5 Sonnet, Claude 3 Opus | - |
| Google | Gemini | - |
| xAI | Grok | - |
| Perplexity | - | - |
| Cursor/IDEs | - | - |

---

## ⚖️ Consideraciones Éticas y Legales

**Este proyecto se adhiere a:**

- ✅ Investigación académica y educativa
- ✅ Libertad de información
- ✅ Transparencia en sistemas de IA
- ✅ Responsabilidad corporativa

**No es para:**
- ❌ Uso malintencionado
- ❌ Fraude o suplantación
- ❌ Bypass de seguridad sin autorización

Consulta [docs/etica.md](docs/etica.md) para más detalles.

---

## 📞 Contacto y Comunidad

- **Issues:** Para preguntas, sugerencias o reportes
- **Discussions:** Para debates sobre ética y metodología
- **Pull Requests:** Para contribuciones

---

## 📜 Licencia

Este proyecto está bajo **AGPL-3.0**. Ver [LICENCIA](LICENCIA) para más detalles.

---

## 🙏 Créditos

- Basado en investigación de transparencia de IA
- Inspirado en iniciativas de código abierto
- Mantenido por la comunidad

---

**Última actualización:** 2026-06-14  
**Versión:** 1.0.0

---

*boch-clarity: Haciendo la IA más transparente, una línea de código a la vez.* 🔍✨
