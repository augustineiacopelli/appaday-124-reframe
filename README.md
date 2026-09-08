# AppADay 124: Reframe

Part of [AppADay](https://augustineiacopelli.github.io/appaday/), a project to design, build, and publish one complete web app every day.

## What it does

Paste whatever is weighing on you, in your own words. Claude sorts it into three plain sections: what is actually established by what you wrote, what you may be adding on top of it (assumptions, predictions, worst-case stories), and one concrete, doable thing within your control this week.

The tool is built to stay dry and honest rather than comforting. It is instructed to skip cheerfulness and encouragement, and it is explicitly forbidden from inventing any fact, relationship, or detail about your life that you did not supply. If there is not enough in what you wrote to fill a section honestly, it says so instead of making something up.

## Category

Health & Wellness (H), AI-powered.

## Tech

Single self-contained `index.html`. Inline CSS and JavaScript, no build step, no framework. Calls the Anthropic API directly from the browser using `claude-sonnet-5`. Your API key is entered once through the settings gear and stored only in your browser's local storage.

## Try it

Open `index.html`, add your Anthropic API key in Settings, and paste in whatever you need sorted out.
