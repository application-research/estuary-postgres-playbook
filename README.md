# estuary-postgres-playbook

🚧 Under construction 🚧
🚧 DO NOT USE, especially on Production EstuaryV1 PostgreSQL! 🚧
🚧 This playbook is transitioning to be a generally useful playbook instead, for deploying arbitrary PostgreSQL clusters 🚧

Builds a highly available PostgreSQL setup for Estuary using [Patroni](https://github.com/zalando/patroni) and [HAProxy](https://www.haproxy.org/).

Depends on having a working HAProxy deployment via estuary-haproxy-playbook. In future, this playbook will actually allow you to call that one as appropriate.

Usage:
* ansible-galaxy install -r requirements.yml
* ansible-playbook site.yml