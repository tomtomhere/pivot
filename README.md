# 🔁 pivot

![current](https://img.shields.io/badge/current%20thesis-AI-brightgreen) ![previous](https://img.shields.io/badge/previous%20thesis-deprecated-red) ![next](https://img.shields.io/badge/next%20thesis-pending%20keynote-lightgrey)

Migration tool. Converts any codebase to whatever's trending.

## Version history

| Version | Was | Became | Reason |
|---|---|---|---|
| v1 | (nothing) | Blockchain | greenfield |
| v2 | Blockchain | Metaverse | the room went quiet at the blockchain part |
| v3 | Metaverse | AI | investor used the word "AI" once, approvingly |
| v4 | AI | AI-native | "AI" felt insufficiently committed |
| v5 | AI-native | Agentic | a competitor raised on it |
| v6 | Agentic | (pending) | awaiting next keynote |

## Install

```bash
npm install -g pivot   # by the time this finishes installing, the thesis may have changed
```

## Usage

```bash
pivot --to agentic
```

`pivot` scans your repository, locates every instance of your previous thesis,
and replaces it with the current one. It does not touch the code, only the README,
the pitch deck, and the company's self-description. This is sufficient.

## The `--honest` flag

```bash
pivot --honest
```

Reverts all pivots and restores the original thesis. This flag has never been used.

## FAQ

**Q: Does this change my actual product?**
A: You have an actual product?

## License

MIT, currently. Will be pivoted.
