# Toolbox playbook

Playbok for configuring new server and new sites

## Usage

### New server
`ansible-playbook -i env/stage server.yml -u root`

### New site
`ansible-playbook -i env/dev site.yml -u root`
