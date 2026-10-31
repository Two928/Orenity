# Orenity

A custom standalone launcher for Roblox with a classic look and feel.

## Features
- Supports distinct execution modes for Player and Studio.
- Lightweight, standalone `.exe`.

## Setup & Usage

Orenity reads your installation paths from the Windows Registry. Ensure the following keys are configured under `HKCU\Software\Orenity`:

* **`PlayerPath`** (REG_SZ): Full path to your target player executable.
* **`StudioPath`** (REG_SZ): Full path to your target studio executable.

### Running the Launcher
Launch the executable from your command line or a shortcut using the required flag:

```cmd
:: Launch Player mode
Orenity.exe -player

:: Launch Studio mode
Orenity.exe -studio
