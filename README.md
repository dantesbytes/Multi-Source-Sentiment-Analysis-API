# Multi-Source Sentiment Analysis API

## Overview

This FastAPI-based API provides sentiment analysis for comments collected from multiple social media platforms (Reddit, YouTube, and Twitter). It's designed to help businesses, particularly in retail and fast food industries, gauge public reaction to new products or announcements.

## Features

- Collect comments from multiple sources:
  - Reddit posts
  - YouTube videos
  - Twitter tweets
- Perform sentiment analysis on collected comments
- Calculate average sentiment scores
- Provide detailed sentiment reports
- Easy-to-use RESTful API

## Use Cases

1. **New Product Launches**: Analyze public sentiment when a retailer introduces a new product line.
2. **Menu Item Reception**: Gauge customer reactions to new menu items at fast food restaurants.
3. **Marketing Campaign Feedback**: Evaluate the success of marketing campaigns across different social media platforms.
4. **Brand Perception**: Monitor overall brand sentiment by analyzing comments on official social media accounts.

## Getting Started

### Prerequisites

- Python 3.8+
- FastAPI
- uvicorn
- pydantic
- httpx
- textblob (or your preferred sentiment analysis library)
- python-dotenv

