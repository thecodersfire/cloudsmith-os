# Built-in features for cloudsmith-os

Purpose: DevOps and infrastructure

1. **prepare a technical project** — run cloudsmith-os-workspace. It creates ~/Documents/cloudsmith-os-workspace/ with Design, Builds, Logs folders.
2. **plan a build or maintenance session** — run cloudsmith-os-plan to open a purpose-specific Markdown plan, saved under ~/Documents/cloudsmith-os-session-plans/.
3. **check technical change readiness** — run cloudsmith-os-check for an interactive checklist. Answers are not saved or transmitted.

These local tools create folders, open a local note, or display prompts. They do not install packages, change system settings, or send data.

Install them from this repository:

    mkdir -p "$HOME/.local/bin"
    install -m 0755 features/cloudsmith-os-workspace features/cloudsmith-os-plan features/cloudsmith-os-check "$HOME/.local/bin/"

## Preinstalled purpose software

The installer adds these three Flathub applications for DevOps and infrastructure:

1. **DB Browser for SQLite** — org.sqlitebrowser.sqlitebrowser
2. **Wireshark** — org.wireshark.Wireshark
3. **KeePassXC** — org.keepassxc.KeePassXC

They are installed from Flathub during setup. The repository contains application IDs and documentation, not third-party binaries; each publisher’s terms and licenses apply.

## Ten more purpose-specific preinstalled applications

The setup installs these ten Flathub apps selected for DevOps and infrastructure:

1. **Thonny** — write and debug Python code (org.thonny.Thonny)
2. **Godot Engine** — build and test 2D and 3D games (org.godotengine.Godot)
3. **OpenSCAD** — model parametric 3D parts in code (org.openscad.OpenSCAD)
4. **GNOME Boxes** — test workflows in virtual machines (org.gnome.Boxes)
5. **GNOME Text Editor** — edit plain-text notes and configuration files (org.gnome.TextEditor)
6. **GNOME Calculator** — perform scientific and financial calculations (org.gnome.Calculator)
7. **GNOME Logs** — inspect logs during troubleshooting (org.gnome.Logs)
8. **Disk Usage Analyzer** — find large files and manage storage (org.gnome.baobab)
9. **Flatseal** — review Flatpak app permissions (com.github.tchx84.Flatseal)
10. **GNOME Extensions** — manage GNOME desktop extensions (org.gnome.Extensions)

Flathub distributes the app packages. Check each publisher license and terms. This repository contains app IDs and documentation, not third-party binaries.
