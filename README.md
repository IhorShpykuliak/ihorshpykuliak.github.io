# Dashboard & Report Examples

A small hub page for browsing front-end dashboard and report examples, all built with synthetic (non-real) data.

## Structure

```
portfolio-hub/
├── index.html                          # landing / switcher page
└── examples/
    ├── sales-dashboard.html            # interactive sales dashboard
    ├── outlook-mockup.html             # report shown inside an Outlook mock-up
    └── sales-report-email.html         # report as table-based HTML email
```

## Adding a new example

1. Drop the new `.html` file into `examples/`.
2. Open `index.html`, find the `EXAMPLES` array near the bottom of the `<script>`, and add an entry:

```js
{
  id: 'new-example',
  tag: 'Category',
  title: 'Example title',
  desc: 'One-line description.',
  file: 'examples/new-example.html',
  status: 'ready'
}
```

The landing page picks it up automatically — no other changes needed.

## Live site

Once deployed via GitHub Pages: `https://<username>.github.io/<repo-name>/`
