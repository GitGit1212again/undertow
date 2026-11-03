# Undertow

A behavioural questionnaire that runs entirely in your browser, in one HTML file. It asks true/false questions about what a person has actually done (not what they think they are like), tallies the answers against published models, and shows the evidence behind every result.

**Use it now:** https://gitgit1212again.github.io/undertow/

## What it covers

- **Insecurities, deception, love language, emotion, orientation.** Each situation is a heading with several true/false statements; mark every one that has actually happened.
- **Observers.** Someone who knows the subject can answer the same items about them. Observer answers about deception only count when marked "turned out otherwise: yes", and intent is never recorded.
- **Validity checks.** A lie scale, reworded-pair inconsistency, straight-line and yes-saying checks, shown before the results.
- **Disputes.** Markers of gaslighting-type patterns, scored in both directions and banded none / isolated / recurrent / pervasive. It describes patterns; it never labels a person.
- **Messages.** Load a message export and it counts word-level markers per 100 messages per contact, non-answers, pursuit bursts, reply delay and late-night share. Supported: Facebook `message_1.json`, DiscordChatExporter JSON/HTML, Android SMS CSV, WhatsApp and "Name: text" transcripts, or pasted text. The raw text stays in memory for the session; only counts and up to five example lines are saved.
- **Incident log, snapshots, change plan.** Log real incidents with contradiction flags, save snapshots with reliable-change flags, and work through about 28 behavioural experiments with daily check-ins.
- **PHQ-9 and GAD-7** in their published four-point format.

The default view is Simple (Start, four core sections, Orientation, Results, Method). The **advanced** button in the nav adds observers, disputes, screens, validity, messages, log, notes, compare and plan.

## Privacy

There is no server. Nothing is uploaded or sent anywhere. Answers are saved in your browser's local storage on your own device under the key `undertow.v3`. Use **Export subject (JSON)** to back up or move your data, and **Import** to restore it.

## Run it

**Windows or Mac:** download `index.html` (green **Code** button, then **Download ZIP**, or save the file from the repository), then double-click it. Any current browser works (Chrome, Edge, Firefox, Safari). No install, no internet needed after you have the file.

**iPhone or iPad:** open the link above in Safari, tap **Share**, then **Add to Home Screen**. It opens full screen like an app. Your answers live only on that device. The home-screen app and the Safari tab keep separate storage, so pick one and use **Export subject (JSON)** before you clear Safari data or delete the app.

**Run it from a folder with a local server** (optional): `python3 -m http.server 8000` in this folder, then open `http://localhost:8000/`.

## Limits

This is a self-reflection and evidence-organising tool, not a clinical instrument or a diagnosis. The PHQ-9 and GAD-7 sections are screening questionnaires only. Message exports include other people's words, so keep them private.

## License

MIT. See [LICENSE](LICENSE).
