---
title: Proofer privacy policy
---

# Proofer privacy policy

Last updated: 2 October 2026

## The short version

Proofer runs entirely on your own computer. It never sends what you type to
Proofer's author or to anyone else. It keeps a log **on your computer** of the
sentences it checks, so its work can be reviewed; you can switch the log off,
save it to a file, or delete it at any time.

## What Proofer does with your text

When you finish a sentence in a text box, Proofer sends that sentence — with up
to 2,500 characters of the text before it, as context — to **Ollama running on
your own computer** (`localhost`), which runs Proofer's proofreading engine and
answers with a correction. The extension only ever connects to Ollama on this
computer; it has no server of its own.

## What Proofer keeps on your computer

With "Keep a log" on (it is on by default), Proofer stores in your browser's
local storage, for each sentence it checks:

- the sentence, and up to 400 characters of the text before it
- the website it was typed on (the site's address, such as `mail.example.com`)
- what the engine proposed, including corrections Proofer chose not to make
- what happened next: whether the correction was kept, taken back with Escape,
  or edited by you (and, if you edited it, the edited sentence)
- timings, and which version of Proofer's prompt and engine answered

It also keeps counters that hold no text (for example, how often it skipped a
sentence and why) and the result of its speed check (timings and version
numbers, no text).

**How long:** the newest 5,000 sentences. Older ones are deleted as new ones
arrive, and earlier if the browser's storage fills up (the toolbar menu says
when that has happened).

**Deleting it:** open Proofer's toolbar menu and choose **Clear**. That deletes
every entry from this computer at once. Files you saved earlier with Export are
yours and are not affected. Removing the extension deletes its storage too.

**Switching it off:** untick **Keep a log** in the toolbar menu. Proofer still
corrects; nothing new is logged.

Sites where you switch Proofer off never have anything proofread or logged.

## Downloading the proofreading engine

Setup asks Ollama to download Proofer's proofreading engine (about 1.7 GB) from
ollama.com. That download is made by Ollama, under Ollama's own terms; Proofer
sends nothing of yours with it. Setup then runs a speed check on made-up
sentences, on your computer.

## Sharing your log (only if you choose to)

Nothing is ever sent automatically. **Export log** saves a file on your
computer; what you do with it is up to you. The first time you export, Proofer
shows this notice:

> Export log saves a file on your computer. It doesn't send anything, and on its
> own it doesn't give permission for anything. The file holds the sentences
> Proofer checked, the text just before them, the sites, what Proofer proposed
> and any edits you made — and it may mention other people. If you choose to
> send it to Jay, Jay will use it to improve Proofer: that may include reviewing
> it with AI assistants such as Claude or ChatGPT and, after removing names and
> anything identifying or confidential, using it to help train the next version
> of Proofer's proofreading model, which may become a paid product. Scrubbing
> and testing reduce, but can't eliminate, the chance that a model repeats
> something it was trained on. You can ask Jay at any time to stop using your
> file and delete it and anything made from it; that can't recall copies of a
> model others have already downloaded.

If you send a log:

- **What is recorded about it:** a pseudonym for you, the date, which version of
  this notice you saw, whether you agreed to training use, and how it arrived.
- **Deletion:** ask Jay, or write to tryproofer@gmail.com, and your file, and everything
  made from it, is deleted. A model that has already been published cannot be
  recalled.

## Test reports

**Save test report** in setup saves a file with the speed check's timings,
version numbers and what the browser can tell about the hardware (the operating
system, the number of processor cores, the graphics chip). It holds nothing you
typed, no websites and no file paths. It is sent only if you send it.

## Permissions, and why

- **Read and change data on all websites** — Proofer has to see the text box you
  are typing in and write the correction into it, on whatever site you write on,
  including editors inside frames.
- **Connect to `localhost`** — to reach Ollama on your own computer, and nothing
  else.
- **Storage** — the settings and the local log described above.
- **Declarative network rules** — one rule that lets Ollama accept Proofer's own
  requests (Ollama refuses browser extensions by default). It applies only to
  Proofer's requests to Ollama on this computer.
- **The current tab** (when you click Proofer's toolbar button) — so the menu
  can say whether Proofer is running on the page in front of you.

## Chrome Web Store User Data Policy

Proofer's handling of your data follows the Chrome Web Store User Data Policy,
including its Limited Use requirements. What Proofer reads is used only to
proofread your writing, and a log you choose to send is used only to improve
Proofer. It is never sold, never used for advertising, and never used to
decide creditworthiness or for lending.

## Contact

tryproofer@gmail.com
