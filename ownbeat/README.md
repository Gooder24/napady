# Ownbeat

**Your watch knows more than its app tells you.** A local-first health app that reads any watch, ring or chest
strap, shows which sensors it really has, and computes every metric that published research supports from them.
Every number carries its method, source and a confidence class; where the data cannot back a number, it shows none
and says what is missing.

Stopped: 23 November 2026.

- **The idea and research**: [PLAN.md](PLAN.md) (onboarding, device card, unlock levels, metric catalogue with
  citations, multi-device rules, trust, architecture, privacy, EU legal position, phases), [DEVICES.md](DEVICES.md)
  (how to get data out of each brand without the vendor's permission), [BRAND.md](BRAND.md) (names checked, tone,
  sample copy, visual direction). These are the current versions; the copy in wristlogic's `idea/` is older.
- **Working code** (phase 0): [Gooder24/wristlogic](https://github.com/Gooder24/wristlogic), Python, AGPL-3.0-or-later.
  Reads a Garmin watch over USB, stores samples per device, computes sleep, resting heart rate, SRI, HRV against a
  personal baseline, TRIMP and the Banister model, and lists which metrics are still locked and why.
- **Where to start:** the phases in section 12 of the plan, then Gadgetbridge as the second data source.
