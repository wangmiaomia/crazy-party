V86.1 AUDIO STABILITY HOTFIX (based strictly on V86)

Fixes:
1. Removed 1.6s audio watchdog and pause/suspend reload loops.
2. Removed WebAudio duplicate fallback that could overlap with HTMLAudio.
3. Pause button now performs a real audio.pause(); resume continues at same currentTime.
4. Mobile visibility resume only occurs when the user did not manually pause.
5. Theme 06 has exactly one dedicated player and still starts only after needle drop.
6. Five MP3 files optimized from 256/320 kbps to 160 kbps for smoother mobile streaming.
7. No V87 layout code included.
