# BuildCored-Orcas-Day6
BreathClock — BUILDCORED ORCAS Day 06

What it does. It uses my laptop's mic to listen to the sound of my breathing and filters out all the background noise so it only sees the slow "puffs." Then, it counts how many times that signal hits a certain level to figure out my breaths per minute.

Hardware concept. The microphone acts like an analog sensor that turns air pressure from my breath into digital numbers. By using a Butterworth filter, I’m basically telling the computer to ignore fast sounds (like talking) and only pay attention to the slow, steady waves of my breathing.

What I would do differently. I’d want to find a way to make the threshold auto-adjust because it was really tricky to find the "sweet spot" where it wouldn't miss a breath or count room noise. I also think using a headset mic might work better than my laptop mic to get a cleaner signal without having to lean in so close.

Run it. python day06_starter.py
