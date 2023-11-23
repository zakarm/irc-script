# IRC Script

## Overview
This script is a simple IRC (Internet Relay Chat) client written in Python using the asyncio library. It connects to an IRC server, joins a channel, and sends messages at regular intervals.

## Features
- Connects to the IRC server at 127.0.0.1:6667.
- Creates multiple socket connections (up to 10) to simulate concurrent users.
- Joins the "#general" channel and sends messages periodically.

## Usage
1. Make sure you have Python installed on your system.
2. Run the script by executing the following command in your terminal:

   ```bash
   python3 irc_script.py
