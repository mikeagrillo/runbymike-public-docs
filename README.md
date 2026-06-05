# Run by Mike

Periodized training plans, an on-device run coach, and route generation for iPhone runners.

[![Download on the App Store](https://developer.apple.com/assets/elements/badges/download-on-the-app-store.svg)](https://apps.apple.com/us/app/run-by-mike/id6770385534)

## What it does

Run by Mike meets you where you are. New to running? The Foundation block walks you from zero to a sustained 30-minute easy run over 8 weeks, then hands you off to a race plan. Already running? Pick your next 5K, 10K, half, or marathon and Run by Mike builds the plan around Daniels' VDOT formula, splitting it into Base, Build, Peak, and Taper phases with weekly long-run growth and cutback weeks every fourth week.

The Run Coach tells you whether right now is a good time to run, based on temperature, "feels like," humidity, and wind. If it's not, it tells you when later today would be better. The whole thing runs on your phone using Apple Intelligence. No data leaves the device.

The route generator drops out-and-back or loop routes wherever you are. Tempo and intervals get routed on flatter terrain. Hill days favor elevation. Out-and-back routes start into the wind so you finish with a tailwind. Want a specific path? Tap up to 12 waypoints to draw a custom route, or drag the markers on a saved one to tweak it.

## Features

### Training plans

* Foundation block: 8-week walk/run progression for runners building their first base, with a one-tap handoff to a race plan when you graduate
* Race-day plans for 5K, 10K, Half Marathon, and Marathon
* Paces derived from a recent race or goal time via Daniels' VDOT
* Phases: Base, Build, Peak, Taper. Cutback weeks every 4 weeks.
* Race-specific workouts in the Peak phase: marathon-pace long runs for half and full, VO2max intervals for 5K and 10K
* Set your experience level (Beginner, Novice, Intermediate, Advanced) and your weekly mileage

### Run Coach

* Daily verdict on whether to run now
* Best-window suggestion if conditions improve later
* Per-workout coaching tips
* Daily motivational line
* Runs on-device. Your weather, name, and run history never leave your iPhone.

### Route generator

* Out-and-back and loop routes from your current location
* Workout-aware: flat for tempo and intervals, elevation for hill days
* Wind-aware: into the wind on the way out, tailwind home
* Compass-aware: routes start in the direction you're facing
* Custom routes: tap up to 12 waypoints to draw your own path
* Edit saved routes by dragging, inserting, or removing waypoints
* Save routes and re-run them later

### Home-screen widgets

* Today's workout at a glance
* Next-best weather window for today
* Race-day countdown for your active plan

### Apple Health sync

* Auto-completes scheduled runs from your Apple Health workouts
* Manually-entered actuals are never overwritten
* Logged walks land as walks, so they don't skew your running PRs
* Imports skip runs you've already logged, so nothing duplicates

### iCloud sync

* Workouts, plans, and saved routes sync across iPhone, iPad, and Mac via CloudKit

### Stats and charts

* Monthly totals, longest run, current streak
* Last 12 weeks of distance
* Workout type mix
* Pace trend over time
* Walks stay out of running PRs and pace trends

## Privacy

* The Run Coach runs locally on your device through Apple's `FoundationModels` framework
* No third-party analytics, no advertising, no tracking
* Sign in with Apple
* Account deletion from inside the app, including all local and iCloud data

Full details: [Privacy Policy](privacy.md).

## Built with

* SwiftUI and SwiftData for the UI and persistence
* CloudKit for cross-device sync
* FoundationModels for the on-device coach and daily message
* WeatherKit for current and hourly forecasts
* HealthKit for workout sync
* MapKit for route generation, Look Around previews, and reverse geocoding
* WidgetKit and App Intents for home-screen widgets and Shortcuts actions
* StoreKit 2 with `SubscriptionStoreView` for the paywall

## Premium

Run by Mike Premium includes training plans, Run Coach, Apple Health sync, unlimited saved routes, and lifetime stats.

* $2.99 per month
* $24.99 per year (save about 30%)

Cancel anytime in iOS Settings, [your name], Subscriptions.

The free tier covers one-off route generation and up to 3 saved routes.

## Requirements

* iPhone running iOS 26 or later
* Apple Intelligence-capable iPhone (15 Pro or newer) for the Run Coach
* iCloud account for cross-device sync

## Support

Bug or feature request? Email **runbymike@icloud.com**.

## Legal

* [Privacy Policy](privacy.md)
* [Terms of Use](terms.md)

© 2026 Michael Agrillo. All rights reserved.
````
