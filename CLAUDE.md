# Talks repo

## General

- Do not use the auto memory system. Persist all instructions and preferences in this file only.

## Adding a new talk

1. **Create a file** named `talks/YYYYMMDD_short_slug.md`:
   ```markdown
   # Talk Title

   ## Talk Resources

   * [YouTube](https://www.youtube.com/watch?v=VIDEO_ID)
   * [Slides](../slides/YYYYMMDD_short_slug.pdf)
   * Article [EN](url) | [RU](url)
   ```
   Include only the resources that exist.

2. **Add a row** to `README.md` table, sorted by date descending:
   ```
   | YYYY-MM-DD | [Title](talks/filename.md) | Event name or link | English/Russian |
   ```
   If no event, use `—`. If event has a URL, link it. The title must be in English (translate if needed). Use the same English title in both the markdown file heading and the README row.

3. **Ask for** any info not available: exact date, event name/URL, available resources. Ask questions one by one, not all at once.

4. **Commit** the talk markdown (`talks/YYYYMMDD_short_slug.md`), `README.md`, and the slides PDF (`slides/YYYYMMDD_short_slug.pdf`) if it exists. **Always check for the PDF before committing — do not forget to include it.** The slug must be the same in both the markdown filename and the PDF filename. Commit message format: `feat: add YYYYMMDD` (date only, nothing else). No co-author trailer.
