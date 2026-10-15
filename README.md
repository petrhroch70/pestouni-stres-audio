# Nahrávky ke kurzu „Stres v pěstounské péči“

Statické soubory pro přehrávač kurzu (GitHub Pages, větev `main`, kořen):
- `<klíč>.mp3`: jedna replika (mono, 24 kHz, 48 kb/s, −17 LUFS),
- `<klíč>.lip.json`: vizémy pro avatary,
- `index.json`: seznam klíčů a znělka,
- `jingle.mp3`: znělka podcastu.

Klíč je hash role a textu repliky (viz `js/audio.js` v aplikaci). Hlasy jsou syntetické (AI), vygenerované službou Gemini TTS (Google); každá nahrávka byla zkontrolována zpětným přepisem proti textu. Původní FOSS verze (Piper + kNN-VC) je v historii repozitáře. Licence viz [CREDITS.md](CREDITS.md).
