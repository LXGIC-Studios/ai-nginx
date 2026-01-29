# ai-nginx

[![npm version](https://img.shields.io/npm/v/ai-nginx.svg)](https://www.npmjs.com/package/ai-nginx)
[![npm downloads](https://img.shields.io/npm/dm/ai-nginx.svg)](https://www.npmjs.com/package/ai-nginx)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)


Stop googling nginx config snippets and copy-pasting from StackOverflow. Just describe what you want in plain English.

## Install

```bash
npm install -g ai-nginx
```

## Usage

```bash
# Reverse proxy with SSL
npx ai-nginx "reverse proxy port 3000 with SSL and rate limiting"

# Static site
npx ai-nginx "serve static files from /var/www/html with caching"

# Save to file
npx ai-nginx "load balance between 3 node servers" -o nginx.conf
```

## Setup

Set your OpenAI API key:

```bash
export OPENAI_API_KEY=your-key-here
```

## Options

- `-o, --output <file>` - Write the config to a file

## License

MIT
