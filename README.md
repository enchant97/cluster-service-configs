# Cluster Service Configs
Anonymized configs that are used in my cluster.

## Directories
- `swarm_data/` files to be placed where you keep swarm data (*could be a GlusterFS mount*)
- `stack.yml.d` Docker Swarm stack config files

## Pre Requisites
- Docker Swarm setup
- Docker Swarm Networks Created
  - metrics (overlay, attachable)

## Usage
- Replace template fields with own values (Wrapped in `%%<Field Name>%%`)
  - TIME_ZONE
  - SWARM_DATA
