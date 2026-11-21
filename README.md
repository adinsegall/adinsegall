# Adin Segall

I build ML systems for music and audio. Just finished my MSc in Sound & Music Computing at Queen Mary's Centre for Digital Music in London. I also DJ, so most of these projects started as problems I actually had.

The main one is [dj-playlist-generation](https://github.com/adinsegall/dj-playlist-generation), my dissertation and an [ISMIR 2026 late-breaking demo](https://ismir2026program.ismir.net/lbd_663.html). You type something like "warm minimal house to open, peak-time techno to close" and it builds a playlist from your own Rekordbox library. I ran a blinded study with 12 DJs comparing a heuristic ranker against a learned retriever, and the honest answer is that they tied, for interesting reasons. The full code is private for now, but the eval harness, thesis, and demo video are in the repo, and I'm happy to walk anyone through the rest.

Other projects:

- [riffusion-lora](https://github.com/adinsegall/riffusion-lora) fine-tunes Riffusion to generate EDM samples. There's an [audio gallery](https://adinsegall.github.io/riffusion-lora/) if you want to hear what it makes.
- [dl4am-cvae-bilstm](https://github.com/adinsegall/dl4am-cvae-bilstm) generates loopable audio by steering a VAE's latent space with a loop classifier.
- [audio-fingerprinting](https://github.com/adinsegall/audio-fingerprinting) is a Shazam clone built from scratch with numpy and librosa.
- [music-artist-ontology](https://github.com/adinsegall/music-artist-ontology) is a knowledge graph of music artists built from Wikidata and DBpedia.
- [WakeTag](https://github.com/adinsegall/WakeTag) is an iOS alarm clock that won't shut up until you scan an NFC tag in the other room.

Before the MSc I was at the University of Miami, where I started building audio plugins in JUCE/C++ ([A-Simple-Synth](https://github.com/adinsegall/A-Simple-Synth), [Channel-Strip-GPT](https://github.com/adinsegall/Channel-Strip-GPT)).

Reach me at segalladin@gmail.com.
