<p align="center">
  <strong>Explain with pictures, not walls of text.</strong><br>
  Dyslexia-friendly AI explanations. No diagnosis needed.
</p>
<p align="center">
  <a href="LICENSE"><img src="https://img.shields.io/github/license/i-have-dyslexia/i-have-dyslexia?style=flat" alt="License"></a>
</p>

## Install

In Claude Code:

```text
/plugin install i-have-dyslexia --marketplace i-have-dyslexia/i-have-dyslexia
```

Or copy/paste into any AI coding tool:

```text
Install the i-have-dyslexia skill from https://github.com/i-have-dyslexia/i-have-dyslexia, refer to the repo's AGENTS.md for instructions.
```

Or see [INSTALL.md](INSTALL.md).

## What it does

Every time the AI explains something, it **shows a picture first**. Then a few short, plain sentences.

```
  Question ──▶ Visual ──▶ Short text ──▶ "In short" line
```

The picture is picked to fit the idea:

| The idea is... | You get a... |
|---|---|
| Steps or a process | Flow |
| A comparison | Table |
| Parts of a whole | Tree |
| Something over time | Timeline |
| Amounts | Bar chart |
| A decision | Yes/no branch |

## Before / after

<table>
<tr>
<td width="50%">

### Before

> Great question! So when you type a URL into your browser, a number of things happen behind the scenes. First, the browser needs to figure out the IP address of the server, which it does by asking a DNS server. Once it has the address, it opens a connection to the server, and then sends an HTTP request. The server processes that request, possibly talking to a database, and sends back a response, which the browser then renders into the page you see.

</td>
<td width="50%">

### After

```
 You type URL
      │
      ▼
 DNS ──▶ finds the server's address
      │
      ▼
 Browser ──▶ Server ──▶ Database
      ▲          │
      └──────────┘
       sends page back
```

1. **DNS** is the internet's phone book.
2. The **browser** asks the **server** for the page.
3. The **server** gets data and sends the page back.

**In short:** find the address, ask, get the page.

</td>
</tr>
</table>

## Turn it off

Say **"stop dyslexia mode"**.

## Why pictures?

Dyslexia makes decoding words slow and tiring. Shapes and layout are read much faster. A picture cuts the amount of text the reader has to get through.

## License

[MIT](LICENSE)
