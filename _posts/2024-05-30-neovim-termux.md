---
layout: post
title: "Configuración Definitiva de NeoVim en Termux"
date: 2024-05-30
categories: [mobile-dev]
---

## 🛠️ Paso 1: Instalación Básica
```bash
pkg update && pkg install neovim -y
nvim --version
```

## ⚡ Paso 2: Configuración Mobile-First
```lua
-- ~/.config/nvim/init.lua
vim.opt.number = true
vim.opt.tabstop = 2  # Ahorro de espacio en móvil
```
**Resultado final:** IDE funcional en 300MB de RAM -> [Ver Demo](#)
___

### **7. Comandos Clave para Ejecutar**
```bash
# Construir sitio localmente
bundle exec jekyll serve --livereload

# Acceder desde móvil (usando Termux)
termux-open-url http://localhost:4000
```
