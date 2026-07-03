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

**Deployment setup for a recruitment management app**

SRM is a student recruitment management application where my work focused on preparing and configuring the project for deployment. The repository includes a FastAPI backend, a React and TypeScript frontend, startup scripts, and deployment configuration.

**Tech stack:** FastAPI, Python, SQLAlchemy, SQLite, React, TypeScript, Vite, Tailwind CSS

**Highlights:**
- Deployment-oriented project setup and configuration.
- Backend and frontend startup scripts for local and hosted environments.
- Render deployment configuration.
- FastAPI backend and React + TypeScript frontend structure.

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

**PyPI packaging fork for Pinchana Core**

Pinchana Core is an unofficial fork prepared so the original Pinchana Core project can be installed as a PyPI package. My work here was focused on packaging, distribution metadata, and making the package usable as a dependency for downstream projects.

**Tech stack:** Python, Pydantic, Docker, Gluetun, PyPI packaging

**Highlights:**
- PyPI-ready package distribution for an upstream project.
- Packaging metadata and dependency setup.
- Preserves the original `pinchana_core` import path.
- Intended for use as a dependency in Pinchana-based projects.

## Pinchana Twitter

**PyPI packaging fork for a Pinchana Twitter/X plugin**

Pinchana Twitter is an unofficial fork prepared so the original Pinchana Twitter/X scraper plugin can be installed as a PyPI package. My work here was focused on packaging the plugin, exposing it as an importable Python dependency, and keeping it usable in downstream projects.

**Tech stack:** Python, FastAPI-style plugin API, X GraphQL, Gluetun, PyPI packaging

**Highlights:**
- PyPI-ready package distribution for an upstream plugin.
- Importable Python wrapper for downstream use.
- Packaging metadata and release workflow setup.
- Keeps the original scraper logic attribution clear.
