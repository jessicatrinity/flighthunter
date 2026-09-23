# FlightHunter

Flight search and itinerary optimization engine.

## V0.1
- Search requirements model
- Provider adapter architecture
- Alternate-airport expansion
- Alternate-destination expansion
- Creative multi-leg route generation
- Offer normalization
- Price/revalidation hooks
- Saved-search and auto-buy rule models
- Auto-buy disabled by default

## Architecture
UI → Search API → Provider Adapters → Normalizer → Route Optimizer → Validator → Results

## Status
Foundation scaffold. Live provider credentials are intentionally not committed.

## Environment
Copy `.env.example` to `.env.local` and add provider credentials when configured.
