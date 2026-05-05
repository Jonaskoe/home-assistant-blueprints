# Home Assistant Blueprints

Reusable Home Assistant automation blueprints for practical daily use.

## Purpose

This repository collects simple, reusable blueprints that can be imported into Home Assistant and adapted with your own entities and thresholds.

## Repository structure

```text
.
├── blueprints/
│   └── ventilation_recommendation.yaml
├── .gitignore
├── LICENSE
└── README.md
```

## Blueprints

### Ventilation Recommendation (Humidity Difference)

Sends a notification when ventilation is recommended based on absolute humidity difference, room humidity, presence, weather conditions, time window, and window status.

[![Import Blueprint](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https://raw.githubusercontent.com/Jonaskoe/home-assistant-blueprints/refs/heads/main/blueprints/ventilation_recommendation.yaml)


**Path**
`blueprints\ventilation_recommendation.yaml`

## Installation and usage (Home Assistant)

### Option 1: Import via My Home Assistant

Open the blueprint entry below and click the import badge.
Home Assistant will open the blueprint import dialog automatically. [Home Assistant supports importing blueprints from GitHub URLs.]

### Option 2: Manual import

1. Open **Home Assistant**.
2. Go to **Settings → Automations & Scenes → Blueprints**.
3. Click **Import Blueprint**.
4. Paste the raw GitHub URL of a blueprint from this repository.
5. Create an automation from the imported blueprint and fill in the required inputs.

