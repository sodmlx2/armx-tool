# ARMX-TOOL 🛠️

> **Versão:** `furia-v1.7 (dev)`
> **Sistema:** Linux (Cross-Compile Workspace Tool)

---

## 🎯 OBJETIVOS:
* Facility cross compile (CC) workspace configuration and kernel compile process.
* Running in the most principal linux distros ;)
* Useful to study linux kernel source code.

---

## 📦 DEPENDÊNCIAS:
* **Linux packages:** `git`, `zenity`, `curl`, `sed`, `awk`, `sort` e `bash`.

### Instalação (Debian/Ubuntu):
```bash
sudo apt-get install -y build-essential bison flex libncurses5-dev libncursesw5-dev libssl-dev libgnutls28-dev
```

### Instalação (Red Hat/Fedora):
```bash
sudo dnf groupinstall -y "Development Tools" "C Development Tools and Libraries"
```

```bash
sudo dnf install -y bison flex ncurses-devel openssl-devel gnutls-devel zenity curl sed gawk
```

## 🛠️ Registro de Alterações (Changelog)

### ✅ Correções (FIX)
* **Versão do Compilador:** Agora valida se versões prévias do compilador/bootloader existem antes de baixar.
* **Automação de Perfil:** Adicionada a atualização automática do `.bash_profile`.
* **Git Clone:** Removida a flag `--depth 1` dos repositórios (Compiler/Bootloader) para permitir acesso ao histórico completo.

### 🚀 Próximos Passos (TODO)
* [ ] Suporte a múltiplos mirrors para Bootloader, Compilador e RTFS.
* [ ] Implementar verificação de projetos existentes ao rodar o comando `armx init`.
* [ ] Refinar o output de erro nos logs de compilação.

---

## 🧪 Testes de Validação
O funcionamento do compilador é validado através do comando:

```bash

```

## 🛠️ Registro de Alterações (Changelog)

### ✅ Correções (FIX)
* **Versão do Compilador:** Agora valida se versões prévias do compilador/bootloader existem antes de baixar.
* **Automação de Perfil:** Adicionada a atualização automática do `.bash_profile`.
* **Git Clone:** Removida a flag `--depth 1` dos repositórios (Compiler/Bootloader) para permitir acesso ao histórico completo.

### 🚀 Próximos Passos (TODO)
* [ ] Suporte a múltiplos mirrors para Bootloader, Compilador e RTFS.
* [ ] Implementar verificação de projetos existentes ao rodar o comando `armx init`.
* [ ] Refinar o output de erro nos logs de compilação.

---

## 🧪 Testes de Validação
O funcionamento do compilador é validado através do comando:



