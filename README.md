# Tradezey - MERN Stack Application
## 🌍 Project Overview

Tradezey is a full-stack web application that visualizes how international trade agreements and import/export data impact everyday consumer goods prices. The platform connects global trade metrics to local price effects, making complex economic data accessible to general users.

## Problem Statement
Citizens often struggle to understand how international trade policies affect the prices of daily essentials like fuel, food, and electronics. Current trade data platforms are either too technical (for economists) or too simplistic (basic news articles).

## Solution
- TradeImpact bridges this gap by:
- Fetching real-time trade data from WTO APIs
- Processing and analyzing import/export statistics
- Mapping trade commodities to consumer goods categories
- Generating plain-language explanations of price impacts

## Providing country-specific trade dashboards

## 🚀 Features
## Core Features (MVP)
- Country Trade Dashboard: Visualize imports/exports by country
- Category Impact Analysis: See how specific goods categories are affected
- Trade Agreement Explorer: View active FTAs and their implications
- Risk Assessment: Dependency and exposure risk indicators
- Historical Trends: Time-series analysis of trade patterns

## Technical Features
- RESTful API with proper error handling
- Real-time data fetching from WTO APIs
- Responsive React frontend with data visualizations
- MongoDB data persistence and caching
- Automated data refresh via cron jobs
- Environment-based configuration

## Tech Stack

- Frontend: React.js, Tailwind CSS, Recharts, Axios
- Backend: Node.js, Express.js, MongoDB, Mongoose
- External APIs: WTO Timeseries API, UN Comtrade (phase 2)
- Deployment: Render/Vercel, MongoDB Atlas
