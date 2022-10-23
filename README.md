# estuary-postgres-playbook

Builds a highly available PostgreSQL setup for Estuary using [Patroni](https://github.com/zalando/patroni) and [HAProxy](https://www.haproxy.org/).

Usage:
* ansible-galaxy install -r requirements.yml
* ansible-playbook site.yml
