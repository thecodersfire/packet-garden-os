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

## Ten more purpose-specific preinstalled applications

The setup installs these ten Flathub apps selected for network administration:

1. **GNOME Maps** — look up places and plan routes (org.gnome.Maps)
2. **GNOME Weather** — check local weather conditions (org.gnome.Weather)
3. **GNOME Calendar** — schedule sessions, deadlines, and events (org.gnome.Calendar)
4. **GNOME Clocks** — time work sessions and events (org.gnome.clocks)
5. **GNOME Calculator** — perform scientific and financial calculations (org.gnome.Calculator)
6. **GNOME Contacts** — organize partner and team contacts (org.gnome.Contacts)
7. **Document Scanner** — digitize paper notes and forms (org.gnome.SimpleScan)
8. **GNOME Papers** — read project and reference PDFs (org.gnome.Papers)
9. **GNOME Text Editor** — edit plain-text notes and configuration files (org.gnome.TextEditor)
10. **GNOME Boxes** — test workflows in virtual machines (org.gnome.Boxes)

Flathub distributes the app packages. Check each publisher license and terms. This repository contains app IDs and documentation, not third-party binaries.

## Fifteen more purpose-specific preinstalled applications

These applications add tools suited to this setup focus. They are installed from Flathub by the setup scripts.

1. **DBeaver Community** (io.dbeaver.DBeaverCommunity) — browse, query, and manage SQL databases.
2. **Gitg** (org.gnome.gitg) — review Git history and branches graphically.
3. **Xournal++** (com.github.xournalpp.xournalpp) — annotate PDFs and take handwritten notes.
4. **JabRef** (org.jabref.jabref) — organize BibTeX references and research citations.
5. **Thunderbird** (org.mozilla.Thunderbird) — manage email and communication accounts.
6. **Evolution** (org.gnome.Evolution) — manage email, calendars, and contacts.
7. **QElectroTech** (org.qelectrotech.QElectroTech) — draw electrical schematics and wiring diagrams.
8. **LibreCAD** (org.librecad.librecad) — draft precise 2D technical drawings.
9. **GeoGebra Classic** (org.geogebra.GeoGebra) — explore geometry, algebra, graphing, and 3D math.
10. **Stellarium** (org.stellarium.Stellarium) — explore a planetarium sky for astronomy learning.
11. **Pixelorama** (com.orama_interactive.Pixelorama) — draw pixel-art sprites and frame-based animations.
12. **Synfig Studio** (org.synfig.SynfigStudio) — create vector-based 2D animations.
13. **GNOME Builder** (org.gnome.Builder) — build and debug software.
14. **Thonny** (org.thonny.Thonny) — write and debug Python code.
15. **Godot Engine** (org.godotengine.Godot) — build and test 2D and 3D games.

Emulator frontends do not include game ROMs or copyrighted game files; supply only files you are legally allowed to use.
