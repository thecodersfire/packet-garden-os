# Built-in features for packet-garden-os

Purpose: network administration

1. **prepare field and mapping files** — run packet-garden-os-workspace. It creates ~/Documents/packet-garden-os-workspace/ with Field Notes, Source Data, Map Exports folders.
2. **plan field work** — run packet-garden-os-plan to open a purpose-specific Markdown plan, saved under ~/Documents/packet-garden-os-session-plans/.
3. **check data and location readiness** — run packet-garden-os-check for an interactive checklist. Answers are not saved or transmitted.

These local tools create folders, open a local note, or display prompts. They do not install packages, change system settings, or send data.

Install them from this repository:

    mkdir -p "$HOME/.local/bin"
    install -m 0755 features/packet-garden-os-workspace features/packet-garden-os-plan features/packet-garden-os-check "$HOME/.local/bin/"

## Preinstalled purpose software

The installer adds these three Flathub applications for network administration:

1. **DB Browser for SQLite** — org.sqlitebrowser.sqlitebrowser
2. **KeePassXC** — org.keepassxc.KeePassXC
3. **LibreOffice** — org.libreoffice.LibreOffice

They are installed from Flathub during setup. The repository contains application IDs and documentation, not third-party binaries; each publisher’s terms and licenses apply.
