# 🤝 Guía de Contribución - boch-clarity

¡Gracias por tu interés en contribuir a `boch-clarity`! Este documento explica cómo hacer contribuciones efectivas.

---

## 📋 Antes de Contribuir

### 1. Verifica que tu información sea:
- **Auténtica:** Proviene de fuentes confiables o puede verificarse
- **Relevante:** Relacionada con prompts del sistema de IA
- **Legal:** Respeta derechos de autor y leyes aplicables
- **Ética:** No busca causar daño

### 2. Tipos de Contribuciones Aceptadas

#### ✅ Prompts del Sistema
- Prompts de modelos de lenguaje (ChatGPT, Claude, Gemini, etc.)
- Instrucciones de herramientas de IA
- Directrices internas documentadas

#### ✅ Documentación
- Guías de extracción
- Análisis de prompts
- Investigación sobre comportamiento de IA

#### ✅ Herramientas
- Scripts para análisis
- Validadores
- Parsers

#### ✅ Mejoras
- Mejor organización
- Correcciones
- Actualizaciones

#### ❌ No Aceptamos
- Contenido malintencionado
- Información personal (PII)
- Código malicioso
- Publicidad o spam

---

## 🔧 Proceso de Contribución

### Paso 1: Fork y Configuración

```bash
# Fork el repositorio en GitHub

# Clona tu fork
git clone https://github.com/tu-usuario/CL4R1T4S.git
cd CL4R1T4S

# Añade upstream
git remote add upstream https://github.com/bochmen3/CL4R1T4S.git

# Crea una rama nueva
git checkout -b feat/descripcion-corta
```

### Paso 2: Realiza los Cambios

**Para prompts:**
```markdown
## [Nombre del Modelo]

**Laboratorio:** OpenAI/Anthropic/Google/etc.
**Modelo:** [ej: GPT-4 Turbo]
**Versión:** [número de versión si aplica]
**Fecha:** YYYY-MM-DD
**Fuente:** [Leak/Reverse-engineering/Documentación]

### Contenido

[El prompt completo aquí]

### Notas

- [Observaciones relevantes]
- [Cambios vs versiones previas]
- [Contexto de extracción]

### Verificación

- [ ] Contenido verificado
- [ ] Formato correcto
- [ ] Sin información personal
- [ ] Sin contenido malintencionado
```

**Para documentación:**
- Sigue formato Markdown estándar
- Incluye ejemplos cuando sea posible
- Añade referencias si existen

### Paso 3: Commit y Push

```bash
# Stage cambios
git add .

# Commit descriptivo
git commit -m "feat: Agregar prompt ChatGPT GPT-4 v2024"

# Push a tu rama
git push origin feat/descripcion-corta
```

### Paso 4: Pull Request

1. Ve a GitHub y crea un Pull Request
2. **Título:** Descriptivo y conciso
3. **Descripción:** Incluye:
   - Qué se agrega/modifica
   - Por qué es importante
   - Fuentes/referencias
   - Cualquier consideración ética

**Template de PR:**

```markdown
## Descripción
Describe brevemente el cambio.

## Tipo de Cambio
- [ ] Nuevo prompt
- [ ] Actualización
- [ ] Corrección
- [ ] Documentación

## Fuente/Referencia
[Enlace o descripción de dónde proviene]

## Checklist
- [ ] He verificado la autenticidad del contenido
- [ ] Sigue el formato requerido
- [ ] No contiene información personal
- [ ] He leído la guía de contribución
```

---

## 📐 Estándares y Convenciones

### Nombres de Rama
```
feat/     - Nueva característica
fix/      - Corrección de bug
docs/     - Cambios en documentación
refactor/ - Refactorización
test/     - Pruebas
```

### Mensajes de Commit
```
feat: Agregar descripción breve
fix: Resolver descripción breve
docs: Actualizar descripción
refactor: Simplificar descripción
```

### Estructura de Carpetas
```
prompts/[laboratorio]/[modelo-version].md
docs/[tema].md
utils/[nombre].py
```

---

## 🔍 Revisión de PR

Esperamos que los PR sean revisados por mantainers dentro de 3-7 días.

### Criterios de Aceptación

✅ **Será aceptado si:**
- Contiene información verificable
- Sigue el formato establecido
- Tiene propósito educativo/transparencia
- Cumple con consideraciones éticas
- No afecta negativamente a usuarios

❌ **Será rechazado si:**
- Contiene información personal (PII)
- Busca evasión de seguridad malintencionada
- Viola derechos de autor
- No sigue los estándares
- Contiene spam o publicidad

---

## ❓ Preguntas Frecuentes

### ¿Qué pasa si mi contribución es rechazada?

Te proporcionaremos feedback específico. Puedes:
1. Revisar los comentarios
2. Hacer los cambios sugeridos
3. Reenviar el PR

### ¿Se dan créditos?

¡Por supuesto! Tu contribución se reconocerá en:
- La historia de commits
- El archivo CONTRIBUTORS.md (próximamente)
- Mención en releases

### ¿Hay requisitos de experiencia?

No, todos pueden contribuir:
- Principiantes: Documentación, correcciones menores
- Intermedios: Nuevos prompts, herramientas
- Avanzados: Herramientas complejas, análisis

---

## 🛡️ Código de Conducta

- Sé respetuoso
- Aceptamos diversidad de opiniones
- No tolemos discriminación
- Mantén discusiones constructivas

Violaciones pueden resultar en prohibición del repositorio.

---

## 💡 Tips para Contribuciones Exitosas

1. **Empieza pequeño:** No necesita ser perfecto
2. **Comunica primero:** Abre una Issue para discutir cambios grandes
3. **Sigue el formato:** Ahorra tiempo en revisiones
4. **Sé paciente:** Los mantainers tienen trabajo
5. **Aprende:** Este es un proyecto comunitario

---

## 📞 Ayuda y Soporte

- **Issues:** Para preguntas y problemas
- **Discussions:** Para debates generales
- **Email:** [info del proyecto]

---

¡Gracias por contribuir a `boch-clarity`! 🙏✨
