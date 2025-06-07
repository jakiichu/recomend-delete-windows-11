# Windows 11 Recommended Section Removal Script

## Overview

This script (`script.reg`) is designed to disable the "Recommended" section in the Start menu of Windows 11 by modifying specific registry keys. This provides a cleaner Start menu experience by removing the recommended apps and recent files section.

## Prerequisites

- **Operating System**: Windows 11
- **Permissions**: Administrator privileges are required to modify the Windows Registry.
- **Backup**: It is strongly recommended to back up the Windows Registry before applying any changes.

## Usage

1. **Download or Create the Script**:
   - Save the provided registry script as `script.reg`.

2. **Apply the Script**:
   - Double-click the `script.reg` file.
   - Confirm the prompt to add the information to the registry.
   - Alternatively, run the following command in Command Prompt (as Administrator):
     ```cmd
     reg import script.reg