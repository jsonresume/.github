# JSON Resume

**An open standard for resumes, written as JSON.** Write your resume once as
structured data, then render it with any theme, host it at a free URL, validate
it, and convert it to other formats. It's portable and has no lock-in. The
project has been community-run since 2014.

## Get started

**Host it online (no install):** create a public GitHub Gist named
`resume.json`, then open `https://registry.jsonresume.org/<your-github-username>`.
Choose a theme with `{"meta": {"theme": "elegant"}}` in the file or `?theme=elegant`
in the URL.

**Work locally with the CLI:**

```sh
npm install -g resume-cli
resume init        # create a starter resume.json
resume validate    # check it against the schema
resume serve       # preview it in the browser
```

## Where things live

Everything is developed in one repo: **[jsonresume/jsonresume.org](https://github.com/jsonresume/jsonresume.org)**.
It contains:

| | |
|---|---|
| Schema | [`@jsonresume/schema`](https://www.npmjs.com/package/@jsonresume/schema) · [browse it](https://jsonresume.org/schema) |
| CLI | [`resume-cli`](https://www.npmjs.com/package/resume-cli) |
| Registry (free hosting, 60+ themes) | [registry.jsonresume.org](https://registry.jsonresume.org) |
| Themes gallery | [jsonresume.org/themes](https://jsonresume.org/themes) |
| Docs | [jsonresume.org/docs](https://jsonresume.org/docs) |
| Converters | e.g. [`@jsonresume/jsonresume-to-rendercv`](https://www.npmjs.com/package/@jsonresume/jsonresume-to-rendercv) |

Also here: **[mcp](https://github.com/jsonresume/mcp)**, an MCP server that lets
your AI coding assistant update your resume as you work.

The older standalone repos (`resume-schema`, `resume-cli`, `resume-website`, …)
are archived. Their code now lives in the monorepo.

## Get involved

- Read the [contributing guide](https://github.com/jsonresume/jsonresume.org/blob/master/CONTRIBUTING.md)
- Propose schema changes or report bugs in [issues](https://github.com/jsonresume/jsonresume.org/issues)
- Publish a theme to npm and [request it for the registry](https://github.com/jsonresume/jsonresume.org/issues/new?template=theme_request.yml)
- Chat on [Discord](https://discord.gg/GTZtn8pTXC)
