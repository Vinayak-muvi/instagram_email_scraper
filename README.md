# Instagram Email Scraper

A Python-based tool that scrapes public emails, bios, and follower counts from the followings of Instagram profiles using the private API.

## Features
- Handles rate-limiting and feedback loops using exponential backoff
- Extracts emails from bio + native email field
- Saves data to `.csv` and `.xlsx`
- Supports session rotation and cooldowns to reduce ban risk

> Note: Sensitive credentials are excluded via `.gitignore`
