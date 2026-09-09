# Contributing

This is a personal reading log, but it is public and pull requests are welcome.

## Adding notes for a new book

1. Copy [`books/_template.md`](./books/_template.md) to `books/<book-title>.md`, using a
   lowercase, hyphenated file name (e.g. `books/born-to-run.md`).
2. Fill in the metadata list at the top (author, published, category, status, optional
   rating) and the one line thesis, then work through the sections in order.
3. Add a row to the right table in [`books/README.md`](./books/README.md), keeping the columns
   in the same order.
4. Open a pull request describing what the book changed for you.

## Suggesting a book

Open an issue with the title, the author, and one or two sentences on why it is worth the time.

## House rules

- **Write in your own words.** Summaries and reflections only. Do not paste chapters, scanned
  pages or long extracts. Keep quotations to a line or two with a page reference.
- **Be specific.** "Great book" helps no one; "this changed how I warm up" does.
- **Say where it is wrong.** Every note has a section for what did not hold up. Filling it in
  is not optional, it is most of the value.
- **No medical advice.** Share what worked for you, not what others must do.
- **Keep it kind.** People arrive at fitness from very different starting points.

## Style

- One book per file, one `# Heading` at the top of each file.
- Use relative links between files so they work on GitHub.
- Wrap lines at roughly 100 characters to keep diffs readable.
