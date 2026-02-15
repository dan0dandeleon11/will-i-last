# Will I Last?

**A pace checker for your Claude weekly usage limits.**

Claude tells you *what %* you've used - but not whether you're burning too fast or have plenty of room. This tool answers the one question everyone asks mid-week: **"Will I last until reset?"**

**[Try it live](https://dan0dandeleon11.github.io/will-i-last/)**

## What It Does

1. You check your usage % in **Claude Settings > Usage**
2. You type those numbers in here
3. It instantly tells you:
   - Whether you're **ahead or behind pace** compared to where you should be
   - Your **projected usage** by week's end at your current rate
   - Exactly how much **% per day** you can safely spend for the rest of the week
   - Which day you'll **hit 100%** if you keep going at this rate

## Features

- **Pace comparison** - visual bars comparing your usage against elapsed time
- **Pace predictor graph** - see your projected trajectory plotted on a chart with the ideal pace line
- **Alert thresholds** - red warning banner when projected usage exceeds your set limit (default 90%)
- **Usage history** - optional tracking of your entries over time with a chart and list view
- **Dark & light mode** - toggle in the header, because night owls exist
- **Hours / Days toggle** - switch between "47h 23m" and "1d 23h" for time displays
- **Export / Import** - copy a base64 string to transfer all settings + history between devices
- **Daily budget calculator** - tells you exactly how much % per day you have left
- Tracks both **All Models** and **Sonnet** limits separately
- Configurable reset day/time (defaults to Thursday 10 PM)
- **Zero tracking, zero data collection** â€” everything stays in your browser's localStorage

## How It Works

Claude's weekly limits reset on a fixed schedule (e.g., every Thursday at 10 PM). This tool calculates what percentage of your billing week has elapsed, then compares that against your actual usage percentage.

- Used **30%** with **50%** of the week gone? You're under budget.
- Used **50%** with **30%** of the week gone? You're burning too fast.

It's that simple, but doing this math manually every time is annoying. So now you don't have to.

## Usage

Visit **[dan0dandeleon11.github.io/will-i-last](https://dan0dandeleon11.github.io/will-i-last/)** that's it. No install, no sign-up.

On mobile, tap **Share â†’ Add to Home Screen** for quick access.

### Transfer Between Devices

Open **Settings â†’ Export Settings** on your first device, copy the string, then **Settings > Import Settings** on your second device and paste it. This transfers your reset schedule, alert thresholds, theme preference, and full usage history.

## Why?

Because checking a datetime calculator for hours elapsed, then dividing by 168 on a separate calculator, then comparing against your usage %... is a terrible workflow. This does it in 2 seconds.

## License

MIT - do whatever you want with it.

