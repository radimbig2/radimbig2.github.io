# Portfolio Projects

Curated project descriptions for the personal portfolio website.

## KVService

**Apartment operations management platform**

KVService is a private full-stack system for managing apartment cleaning operations. It provides a secure API for managers, employees, and administrators to track apartments, assign responsible workers, manage deadlines, update access keys, and record cleaning status with text or photo evidence.

**Tech stack:** C#, ASP.NET Core, PostgreSQL, Entity Framework Core, Microsoft Identity, JWT, DDD-style architecture

**Highlights:**
- Role-based workflows for administrators, managers, and workers.
- Apartment assignment, deadline management, status tracking, and key management.
- Clean layered architecture with Domain, Application, Infrastructure, and API projects.
- Designed for an authenticated mobile-first workflow.

## BigFitness

**Mobile calorie and weight tracking app**

BigFitness is a mobile health tracking application built with .NET MAUI Blazor Hybrid. It helps users track daily calories, macronutrients, food entries, body weight history, and personal calorie goals based on profile data.

**Tech stack:** .NET 9, MAUI, Blazor Hybrid, SQLite, Entity Framework Core, Blazor-ApexCharts

**Highlights:**
- Daily calorie and macronutrient tracking.
- Product database with search and food journal entries.
- Weight history charts and goal calculation using BMR/TDEE.
- Android and Windows support.

## Monobank Donation Tracker

**Donation notification and stream overlay tool**

Monobank Donation Tracker is a streamer-focused Python application that monitors Monobank donations in real time, displays donation alerts in OBS overlays, and can play YouTube music links submitted through donation comments.

**Tech stack:** Python, aiohttp, PyQt5, HTML, CSS, JavaScript, OBS browser overlays

**Highlights:**
- Real-time donation notifications for livestreams.
- OBS overlay and live donation feed pages.
- YouTube music queue with caching, playback controls, and duration limits.
- Both CLI and GUI control interfaces.

## RadymDownloadBot

**Telegram media downloader bot**

RadymDownloadBot is a Telegram bot that downloads media from TikTok, Instagram, YouTube, and X/Twitter links. It uses a whitelist-based access model so only authorized users can interact with the bot.

**Tech stack:** Python, Telegram Bot API, yt-dlp, FFmpeg, pytest

**Highlights:**
- Downloads videos and media from major social platforms.
- Whitelist and admin command system for access control.
- Environment-based configuration for deployment.
- Test coverage for core command and downloader behavior.

## Student Recruitment Management

**Recruitment workflow management system**

SRM is a web application for managing student recruitment workflows. It combines a FastAPI backend with a React and TypeScript frontend, providing a structured interface for recruitment data, API-driven workflows, and local deployment.

**Tech stack:** FastAPI, Python, SQLAlchemy, SQLite, React, TypeScript, Vite, Tailwind CSS

**Highlights:**
- Full-stack recruitment management application.
- FastAPI backend with SQLAlchemy models and Pydantic schemas.
- React + TypeScript frontend built with Vite.
- Local development scripts for backend and frontend startup.

## git-merged

**CLI tool for finding merged Git branches**

git-merged is a command-line utility that finds local or remote Git branches already merged into a target branch. It helps developers identify branches that are safe to clean up and can optionally delete them with confirmation.

**Tech stack:** Shell, PowerShell, npm package distribution

**Highlights:**
- Detects branches merged into `main`, `develop`, `production`, or any custom target branch.
- Supports local and remote branch scanning.
- Can save reports to a file or print results directly.
- Optional branch deletion with confirmation and author filtering.

## Pinchana Core

**Shared core package for a scraper platform**

Pinchana Core is an unofficial PyPI-distributed fork of the Pinchana core package. It provides shared models, storage utilities, VPN control, Docker orchestration, and plugin registration logic for scraper-based systems.

**Tech stack:** Python, Pydantic, Docker, Gluetun, PyPI packaging

**Highlights:**
- Shared Pydantic models for scraper requests and responses.
- Media cache with LRU eviction and download helpers.
- VPN rotation and health checks through Gluetun.
- Docker module discovery and lifecycle management.

## Pinchana Twitter

**Twitter/X scraper plugin and Python package**

Pinchana Twitter is an unofficial Pinchana plugin and importable Python package for scraping public Twitter/X post metadata and media. It uses X internal GraphQL where possible, supports VPN rotation for resilience, and falls back to public metadata services when needed.

**Tech stack:** Python, FastAPI-style plugin API, X GraphQL, Gluetun, PyPI packaging

**Highlights:**
- Scrapes text, author data, images, and videos from X/Twitter posts.
- Provides both HTTP endpoints and a synchronous Python library wrapper.
- Uses VPN rotation for rate-limit resilience.
- Publishes as an installable package for downstream projects.

## Personal Portfolio

**GitHub Pages portfolio website**

Personal Portfolio is the repository for the public GitHub Pages website that will showcase projects, experience, and contact information. The current repository is prepared for a future React-based implementation.

**Tech stack:** GitHub Pages, React planned

**Highlights:**
- Public portfolio repository at `radimbig2.github.io`.
- Ready for a React implementation.
- Intended to become the central showcase for selected projects.
