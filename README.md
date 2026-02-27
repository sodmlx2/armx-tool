
> **armx-tool:** Linux (Cross-Compile Workspace Tool)

---

* Facility cross compile (CC) workspace configuration and kernel compile process.
* Running in the most principal linux distros ;)
* Useful to study linux kernel source code.
* Using `zenity`.

### Linux Development.

### Packages for development (Debian/Fedora/Red Hat/Slackware):

```bash
sudo apt-get install -y build-essential bison flex libncurses5-dev libncursesw5-dev libssl-dev libgnutls28-dev
```
```bash
sudo dnf groupinstall -y "Development Tools" "C Development Tools and Libraries"
```
```bash
sudo dnf install -y bison flex ncurses-devel openssl-devel gnutls-devel zenity curl sed gawk
```

### FIX
* **Versão do Compilador:** Agora valida se versões prévias do compilador/bootloader existem antes de baixar.
* **Automação de Perfil:** Adicionada a atualização automática do `.bash_profile`.
* **Git Clone:** Removida a flag `--depth 1` dos repositórios (Compiler/Bootloader) para permitir acesso ao histórico completo.

---


