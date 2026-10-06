# Mindbough MVP

**Think with AI in branches. Keep the decisions. Take them to any model or agent.**

**Open it: https://mig-kharkov.github.io/mindbough-demo/**, on a phone too. Menu → **Try a sample conversation** works without an API key.

Long AI chats pollute their own context: every dead end rides along into the next answer, and the threads you were following get lost. Mindbough lets you think in branches instead. Each branch sends the model only its own path, what a branch settles reaches the others as a decision, what holds for you everywhere is memory, and every prompt shows what it was built from, with its model and tokens. This app is the MVP, on Google's Gemini API: it stores each conversation as a Thinking State, plain files that you can export and give to an agent.

This repository only hosts the built app on GitHub Pages. CI overwrites it on every change, so don't edit it here. The format and its tools are in a repository that stays private until the first public release, when the format is published.

Licensed under the Apache License 2.0: see [LICENSE](LICENSE).
