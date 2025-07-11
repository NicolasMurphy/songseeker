# SongSeeker

A music geography game where players guess countries based on traditional music.

## What is SongSeeker?

Players listen to traditional music from around the world and guess which country it originates from by clicking on a map.

## Tech Stack (Planned)

- **Frontend**: Vite + React + TypeScript
- **Backend**: FastAPI + Python
- **Database**: PostgreSQL + PostGIS
- **Audio delivery**: To be determined
- **Deployment**: Docker on Railway

## Status

**Planning Phase** - Currently designing architecture and database schema.

## Development

This is a complete rewrite of the original SongSeeker to improve:

- Scoring system (border-based distance instead of center points)
- Content management (database instead of large JSON files)
- Audio delivery (potentially replacing Spotify API dependency)
- Performance and user experience

## Audio Strategy

Need to look at the different options and determine the best option.

---

_Previous versions: [SongSeeker Beta](https://github.com/NicolasMurphy/songseeker-beta)_
