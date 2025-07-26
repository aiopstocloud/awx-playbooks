# AWX Playbooks Repository

This repository contains all playbooks and configurations for AWX automation.

## Directory Structure
- connectivity/ - Connection and health check playbooks
- software/vlc/ - VLC Media Player playbooks
- agents/dynatrace/ - Dynatrace OneAgent management
- common/ - Shared utilities and common tasks
- inventory/ - Inventory files and variable definitions

## Usage in AWX
1. Create AWX Project pointing to this Git repository
2. Create Job Templates using playbooks from organized directories
3. Run automation with proper inventory and credentials
