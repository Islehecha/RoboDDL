# RoboDDL

RoboDDL is a deadline tracker for robotics conferences and strong journals. It is inspired by `ccf-deadlines`, but keeps the source-of-truth venue data in a readable JSON file so contributors can update deadlines, ratings, and metadata without touching React code unless the UI actually changes.

Contribution and collaboration guidelines live in [`CONTRIBUTING.md`](/home/zdj/.openclaw/workspace/roboddl/CONTRIBUTING.md).

## Highlights

- 🤖 Conference deadline tracking for ICRA, IROS, RSS, CoRL, ICML, NeurIPS, ICLR, AAAI, and AAMAS
- 📚 Journal tracking for Science Robotics, T-RO, IJRR, RA-L, T-ASE, and T-FR
- ⏳ AoE-normalized deadline display and countdowns
- 🧭 Estimated deadlines when a new official paper deadline has not been announced yet
- 🔎 Venue filters for `Conference` and `Journal`
- ⭐ One-click follow with local persistence and favorite-first sorting
- 🗓️ A month-by-month submission overview for upcoming conference deadlines
- 📊 Journal-specific rating display using `CCF / CAAI / CAS / JCR` when available

## Data

- The source-of-truth data file is [`src/data/venues.json`](/home/zdj/.openclaw/workspace/roboddl/src/data/venues.json)
- Conference venues use official deadlines when available, otherwise the site estimates the next cycle from the latest known paper deadline
- Journal venues are shown as rolling-submission targets with rating metadata when available

## Notes

- 🌍 All displayed deadlines are normalized to AoE
- 🛠️ Most updates should only require editing the JSON data file
- 🧪 Development workflow, project structure, Issue guide, and PR guide live in [`CONTRIBUTING.md`](/home/zdj/.openclaw/workspace/roboddl/CONTRIBUTING.md)
