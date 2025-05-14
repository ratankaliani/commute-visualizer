# Distance Map Generator

Recently, I wanted to get a visualization of the commute times from all neighborhoods in SF to the newly built Gateway Hall in San Francisco.

Initially, I wanted `o4-mini-high` to create a diagram from scratch from scratch which would do what I wanted. Unfortunately, this data isn't granularly accessible for an arbitrary destination point (which is the specific data that I want).

So, I wanted to spend the least amount of time to generate the visualization here as possible, so I could quickly grok which neighborhoods are the best to live in based on commute times.

## Setup

1. Sign up for a Google Developers Console Account.
2. Add the `GOOGLE_MAPS_API_KEY` to your `.env`.