# Free Fire Bot Project

## Overview
This is a Free Fire game bot that automates various in-game interactions and responds to player messages with commands. The bot connects to Free Fire game servers using WebSocket connections and handles encrypted communication.

## Project Structure
- **jexarbangladesh.py** - Main bot file with all bot logic and commands
- **accs.txt** - JSON file containing account credentials (ID and password hash)
- **requirements.txt** - Python dependencies
- **Protobuf files** (*.pb2.py) - Generated protobuf message definitions for game protocol
- **Helper files**:
  - `important_zitado.py` - Important utility functions
  - `byte.py` - Byte manipulation utilities
  - `client.py`, `data.py`, `secret.py`, `utils.py` - Additional helper modules

## Technology Stack
- Python 3.11
- Flask (web framework)
- pycryptodome (AES encryption)
- protobuf (message serialization)
- PyJWT (JWT token handling)
- requests (HTTP client)
- psutil (process utilities)

## Features
The bot supports various in-game commands including:
- Squad invitations and management
- Player status checking
- Friend request spam
- Profile visits
- Room joining
- Auto-accept squad invitations
- And more...

## Running the Bot
The bot automatically starts when you run the Replit. It reads credentials from `accs.txt` and connects to Free Fire servers.

**Workflow**: `Free Fire Bot` - Runs `python jexarbangladesh.py`

## Security Notes
⚠️ **Important**: The `accs.txt` file contains sensitive account credentials and is excluded from version control via `.gitignore`. Make sure to keep this file secure and never share it publicly.

## Recent Changes
- **2025-10-04**: Initial project setup in Replit environment
  - Installed Python 3.11
  - Installed all required dependencies
  - Created workflow to run the bot
  - Added .gitignore for Python artifacts and sensitive files
  - Bot successfully connecting to Free Fire servers
