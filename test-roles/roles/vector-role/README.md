# Vector Ansible Role

## Description
Install and configure Vector log agent.

## Variables

| Variable | Default | Description |
|-------|--------|-------------|
| clickhouse_host | localhost | ClickHouse server |
| clickhouse_db | logs | Database name |

## Example playbook

```yaml
- hosts: vector
  roles:
    - vector-role

