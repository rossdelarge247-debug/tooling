# tooling

A collection of independent tools, one per directory under `tools/`.

## Layout

```
tooling/
├── tools/
│   ├── _template/     # copy this to start a new tool
│   └── <tool-name>/   # one self-contained tool per folder
├── CLAUDE.md
└── README.md
```

Each tool has its own dependencies, build setup, tests and docs. That way tools can use different languages without affecting each other.

## Tools

| Tool | Status | Description |
|------|--------|-------------|
| _none yet_ | | |

Status is one of `experimental`, `active` or `archived`.

## Adding a tool

1. Copy `tools/_template` to `tools/<tool-name>` (lowercase, hyphenated).
2. Fill in its README.
3. Add a row to the table above.
