# WeekBox News

The app reads `content/news/index.json` first. That file lists posts in the
order they should appear. Each entry also sets the publish date and tags.

To add a post:

1. Copy `templates/post.json` and `templates/body.md` into
   `content/news/posts/<slug>/`.
2. Use a short, lowercase, slug, such as `weekbox-2-4-3`.
3. Set the title, excerpt, and cover path in `post.json`.
4. Write the article in `body.md`.
5. Add an entry for the slug to `content/news/index.json`.

The folder for a post contains everything used by that post:

```text
content/news/
├── index.json
└── posts/
    └── my-post-slug/
        ├── post.json
        ├── body.md
        └── assets/
            ├── cover.webp
            └── 01.png
```

An index entry looks like this:

```json
{
  "slug": "my-post-slug",
  "publishedAt": "2026-09-17T12:00:00.000Z",
  "tags": ["Release"]
}
```

The available tags are `Release`, `Mod of the Week`, and `Development` but you can add more if theres a new section, but it has to be continued and NOT dropped.
