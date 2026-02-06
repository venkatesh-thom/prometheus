# Prometheus & Alertmanager Directory Structure

/opt/
├── prometheus/
│   ├── prometheus           # Prometheus binary
│   ├── prometheus.yml       # Prometheus configuration
│   ├── promtool             # Prometheus CLI tool
│   ├── data/                # Prometheus time-series database storage (to be created)
│   └── alert-rules/         # Folder for Prometheus alert rules (to be created)
├── alertmanager/
│   ├── alertmanager         # Alertmanager binary
│   └── alertmanager.yml     # Alertmanager configuration file
