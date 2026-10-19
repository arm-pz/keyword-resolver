# keyword-resolver

Resolve keyword cannibalization with Keyword-Guard, then generate alternative titles/H1/meta descriptions with Wordsmith. Use when the user wants to eliminate internal competition between pages, assign query ownership from Search Console or sitemap, de-conflict mixed-language pages with hreflang, or build cluster maps — and wants both the diagnosis and concrete rewrite alternatives.

## Usage

```text
/keyword-resolver [paste target keywords + current pages]
/keyword-resolver https://example.com/sitemap.xml
Resolve cannibalization for "agent skill" and "SEO audit".
```

## Workflow

1. **Keyword-Guard** audits cannibalization and assigns query ownership
2. **Wordsmith** generates 2-3 alternative titles/H1s/metas per conflict
3. Returns ownership map + alternatives + recommended actions

## Dependencies

Requires `keyword-guard` and `wordsmith` skills to be installed.

## License

MIT © Abdul Rahman P Z
