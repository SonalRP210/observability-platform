# observability-platform

Centralized observability assets for the Sports Betting platform.

## Scope

- Grafana dashboards
- Prometheus configuration and scrape definitions
- Alerting and SLO assets (as added)

## Out of Scope

- Application source code
- Infrastructure provisioning and deployment pipeline logic

## Repository Layout

- `grafana/dashboards/` dashboard JSON definitions
- `grafana/datasources/` datasource provisioning configs
- `prometheus/config/` base Prometheus configuration
- `prometheus/rules/` recording and alert rule groups
- `prometheus/alerts/` alert routing and policies
- `slo/` service-level objective definitions
- `pipelines/` observability validation workflows
- `runbooks/` alert response and troubleshooting guides
