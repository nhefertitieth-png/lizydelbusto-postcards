# December 2026 — Pinterest bulk campaign

Carrier Pigeons collection, wholesale push.

## Campaign

- **Goal:** publish **90 Pins over 30 days** — about **3 per day**.
- **Destination page:** https://www.lizydelbusto.art/wholesale
- **Main Pinterest board:** Postcards + Gift Cards

## Folders

| Folder | Contents |
|---|---|
| `pigeon-mockups/` | Final vertical pigeon greeting-card mockups |
| `wholesale-product/` | Pins aimed at florists, gift shops and independent retailers |
| `collection-story/` | Portfolio, illustration-process and Carrier Pigeons collection Pins |
| `data/` | Pinterest bulk-upload CSV and campaign tracking spreadsheet |

## Image specs

- **Format:** JPG or PNG
- **Ratio:** 2:3 (preferred)
- **Dimensions:** 1000 × 1500 px (preferred)
- **File size:** below 10 MB

## What goes in here

- **Only final, approved images.**
- **No** PSD, Procreate files, temporary exports or rejected versions.

## Naming rules

`<PREFIX><NN>_<lowercase-words-with-hyphens>.<ext>`

| Prefix | Type | Folder | Example |
|---|---|---|---|
| `P` | Pigeon mockup | `pigeon-mockups/` | `P01_muscular-pigeon-card.png`, `P02_birthday-pigeon-card.png` |
| `W` | Wholesale / product | `wholesale-product/` | `W01_wholesale-pigeon-collection.png` |
| `S` | Collection / story | `collection-story/` | `S01_carrier-pigeons-story.png` |

The prefix and number stay uppercase (`P01`); the description after `_` is lowercase, words separated by hyphens. No spaces, accents or special characters, so URLs work in the CSV without escaping.

## Raw image URLs

Images must stay reachable at stable raw GitHub URLs for Pinterest's bulk-upload CSV. Do not rename or move a file once its URL is in a scheduled CSV.

```
https://raw.githubusercontent.com/nhefertitieth-png/lizydelbusto-postcards/main/pinterest/december-2026/<folder>/<filename>
```

Example:

```
https://raw.githubusercontent.com/nhefertitieth-png/lizydelbusto-postcards/main/pinterest/december-2026/pigeon-mockups/P01_muscular-pigeon-card.png
```

## Bulk-upload CSV

Template: `data/pinterest-bulk-template.csv`

Columns: `image_filename,image_url,title,description,destination_url,board,publish_date,publish_time,alt_text,topics,content_type,status`

The template has **one example row**, marked `EXAMPLE` — delete it before uploading.
