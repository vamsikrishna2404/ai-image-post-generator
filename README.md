# AI Image Post Generator

An n8n automation workflow that generates AI-powered LinkedIn posts and images from article links stored in Google Sheets.

## Workflow

Google Sheets Trigger  
→ Summarize Article  
→ Create LinkedIn Post  
→ Generate Image Prompt  
→ Text-to-Image API  
→ LinkedIn Publishing

## Features

- Reads article links from Google Sheets
- Summarizes articles using Google Gemini
- Generates professional LinkedIn post content
- Creates prompts for AI image generation
- Generates images using a text-to-image API
- Publishes content to LinkedIn

## Tools Used

- n8n
- Google Sheets
- Google Gemini
- FLUX / Image Generation API
- LinkedIn API
- Google OAuth

## Challenges Solved

- Google OAuth test-user configuration
- Google Drive API permissions
- Gemini API authentication issues
- FLUX image-generation endpoint errors
- Header authentication setup
- LinkedIn OAuth and publishing setup

## Security

API keys, access tokens, passwords, and OAuth secrets are not included in this repository.

## Project Type

Low-code / no-code AI automation project built using n8n and external APIs.
