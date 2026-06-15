# ID-S-GATEWAY

A lightweight API gateway service for managing, routing, and securing microservice communication.

## 📋 Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Getting Started](#getting-started)
- [Installation](#installation)
- [Configuration](#configuration)
- [Usage](#usage)
- [API Reference](#api-reference)
- [Contributing](#contributing)
- [License](#license)

---

## Overview

ID-S-GATEWAY is a high-performance gateway designed to handle authentication, rate limiting, and request routing across distributed services. It acts as a single entry point for all client requests.

## Features

- 🔐 JWT-based authentication
- 🚦 Rate limiting & throttling
- 🔄 Dynamic request routing
- 📊 Request logging & monitoring
- ⚙️ Environment-based configuration
- 🌐 CORS support

## Getting Started

### Prerequisites

- Node.js >= 18.x
- npm >= 9.x
- Docker (optional)

## Installation

```bash
git clone https://github.com/your-org/id-s-gateway.git
cd id-s-gateway
npm install
```

## Configuration

Create a `.env` file in the root directory:

```env
PORT=3000
JWT_SECRET=your_secret_key
RATE_LIMIT=100
LOG_LEVEL=info
SERVICE_URL_AUTH=http://auth-service:4001
SERVICE_URL_USER=http://user-service:4002
```

## Usage

```bash
# Development
npm run dev

# Production
npm start

# Docker
docker-compose up --build
```

## API Reference

### Health Check# ID-S-GATEWAY
there will be all the information needed
