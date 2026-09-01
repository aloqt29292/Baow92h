# Update V12 — Complete Referral + Tutorial Update

Included:
- Referral system preserved and working.
- Refer & Earn button is blue; Tutorial button is green (Telegram button style/custom UI behavior preserved from the current build).
- Referral message does not display the raw referral URL.
- Inline button is named `কপি রেফার লিংক`.
- The button uses Telegram Bot API `copy_text`, so tapping it copies the referral URL to the user's clipboard instead of opening/sending it.
- Tutorial Center and Tutorial Management workflows are included.
- Support remains the last row in the user panel.

## Dependency
This build requires aiogram 3.31+ because `CopyTextButton` / `InlineKeyboardButton.copy_text` are required.

Install with:
`pip install -U -r requirements.txt`

Then restart the bot.
