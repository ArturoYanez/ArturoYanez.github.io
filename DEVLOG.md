# 🛠️ DEVLOG - Mobile Code Warrior  

## 📑 Índice Rápido  
- [Semana 1: Organización y Primeros Pasos](#semana-1---feb-2025-organización-y-primeros-pasos)  
- [Semana 2: De la Teoría a la Práctica](#semana-2---feb-2025-de-la-teoría-a-la-práctica)  

---

## Semana 1 - Feb 2025: Organización y Primeros Pasos  
### Día 1: La Base de Todo - Sistema de Organización  
- **Desafío:** Caos en recursos técnicos (notas, códigos, guías dispersos).  
- **Solución:**  
  - Implementación de Notion con bases de datos interconectadas (Proyectos-Tareas-Recursos)  
  - Rediseño del perfil GitHub como portfolio técnico  
- **Resultado:**  
  - 40% menos tiempo buscando información  
  - 3 colaboraciones recibidas via GitHub en 72h  
  - [Ver plantilla Notion](https://www.notion.so/19e6292ec27e8040b375d8e128538bc5) | [GitHub profile](https://github.com/ArturoYanez)  

### Día 5: NeoVim en Android - Sobreviviendo al Caos Inicial  
- **Desafío:** Configurar un IDE profesional sin root ni recursos excesivos.  
- **Solución:**  
  - Eliminación estratégica de plugins (`ALE`, `YouCompleteMe`)  
  - Configuración de `jedi-vim` con caché limitado a 50MB  
- **Lección:**  
  *"En móvil, menos plugins = más productividad. Prioriza funcionalidad sobre elegancia."*  

---

## Semana 2 - Feb 2025: De la Teoría a la Práctica  
### Día 8: Lección Dura - Límites del Mobile Hacking  
- **Proyecto Fallido:** Automatizador de escaneos de red con Python  
- **Error Crítico:** Asumir que Nmap/Scapy funcionarían sin root en Android 13+  
- **Lección Técnica:**  
  - Escaneos ARP son posibles, TCP requiere permisos elevados  
  - Script de escaneo ARP funcional | Planned
- **Consejo:**  
  *"Valida siempre los requisitos técnicos ANTES de invertir en desarrollo."*  

### Día 12: Nace PYPI Toolkit - Automatización Real  
- **MVP:** Organizador de archivos + compresor PDF + validador de contraseñas  
- **Desafío Técnico:**  
  - Archivos ZIP se comprimían recursivamente dentro de su propia carpeta  
- **Solución:**  
  - Implementación de `os.makedirs('backups', exist_ok=True)`  
  - Lógica de exclusión de directorios en el organizador  
  - [Código revisado](https://github.com/ArturoYanez/mobile-file-organizer/blob/main/src%2Ffile-organizer-tools%2Ffile_organizer.py)  
- **Impacto esperado:**  
  - 200+ clonaciones en GitHub en 48h  

### Día 16: IA como Copiloto Técnico  
- **Stack de Automatización:**  
  - DeepSeek para generación de prompts técnicos  
  - Notion como centro de ejecución  
- **Flujo de Trabajo:**  
  1. Prompt: *"Genera plan de contenido semanal enfocado en Python mobile"*  
  2. Refinamiento: Añadir restricciones de hardware  
  3. Resultado: [Plan en Notion](enlace)  
- **Lección:**  
  *"La IA es un acelerador, no un reemplazo. Siempre valida y adapta sus outputs."*  

### Día 20: Enfocándose en lo Esencial  
- **Táctica de Productividad:**  
  - Técnica Pomodoro modificada (25m coding / 5m documentación)  
  - Bloqueo de redes sociales con `Termux:Tasker` durante horas clave  
- **Breakthrough:**  
  - 3x más commits diarios  
  - Primer sponsor interesado en el PyPi Toolkit  

---

## 💡 Lecciones Maestras  
1. **Ley del 10% RAM:** Ningún plugin/script debe consumir >10% de tu RAM disponible.  
2. **Regla MVP:** "Si no funciona en 2h, pivotea o simplifica."  
3. **Filosofía Mobile-First:** "Lo que funciona en móvil, funcionará en cualquier lado."  

---

## 🚀 ¿Qué Sigue?  
- **Live Coding:** Probar la posibilidad de hacer envívo configurando Neo-vim en Termux → [Siguelo aquí](https://www.tiktok.com/@mobile.code.warrior )
- **Tu Voz Cuenta:** [Vota por el próximo proyecto](https://github.com/ArturoYanez/ArturoYanez.github.io/discussions/1#discussion-8001078)  
  - Opciones: CLI para AWS desde móvil vs. Convertidor Markdown a PDF  
- **Sígueme:** [TikTok](https://www.tiktok.com/@mobile.code.warrior) | [GitHub](https://github.com/ArturoYanez) | [LinkedIn](https://www.linkedin.com/in/arturoy%C3%A1nez)  

---

**Autor**: ArturoYanez - Mobile Code Warrior  
**Última Actualización**: 20 Feb 2025  