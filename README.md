# Referral System Update V5

Fixed:
- Removed visible raw HTML tags such as `<b>`, `</b>`, `<code>`, `</code>` when custom MessageEntity rendering is active, including malformed tag combinations.
- `Copy Refer Link` now uses Telegram's native `copy_text` button only; it no longer falls back to a URL button that opens/sends the referral link.
- Refer Management admin submenu is arranged compactly with two buttons per row.

Preserved from V4:
- Referral user/admin modes and commission workflows
- Fixed/percent admin commission by category
- Green-ID-only admin commission
- Commission summary notifications
- Duplicate payout protection
- Referral statistics and management controls
