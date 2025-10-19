🇬🇧 ENGLISH  
# 🎙️ Audio and Video Transcription with Whisper on Google Colab

Easily transcribe **audio and video files (including YouTube videos)** into text or subtitles (`.txt`, `.srt`, `.vtt`) using **OpenAI Whisper** — directly on **Google Colab**, with no need to install anything on your computer.

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1FU2OXAyBVkErRAIVDwB0H_PYJwRtvWIx?usp=sharing)

---

## 🧩 How it works

Inside the Colab notebook, you’ll find **all the steps already prepared and explained** in logical order.  
Here’s a quick overview of the workflow:

1. **Automatic installation** of Whisper and all required libraries (`yt-dlp`, `ffmpeg`, etc.).  
   ⚠️ *Always wait for the green check mark next to the cell before proceeding.*

2. **Optional YouTube download** using `yt-dlp`, with automatic conversion to `.m4a` audio.

3. **Upload a local file** if you want to transcribe your own audio or video.

4. **Choose your Whisper model:**  
   You can pick between **lighter and faster** models (`tiny`, `base`) or **more accurate** ones (`large`, `large-v3`).  
   👉 If you know the spoken language, set it with the `--language` parameter to get a much more accurate transcription.

5. **Run the transcription:**  
   Whisper automatically transcribes speech and generates text and subtitle files (`.txt`, `.srt`, `.vtt`).

6. **Save your results:**  
   All generated files are saved in the same Colab folder, ready to download.

---

## 🧠 Available models

Whisper provides several models — from the fastest and lightest to the most accurate and resource-intensive:

| Model               | Speed | Accuracy | Short Description                            |
|----------------------|:-----:|:---------:|----------------------------------------------|
| `tiny`               | ⚡⚡⚡  | 🟡        | Extremely fast, basic quality                |
| `small`              | ⚡⚡   | 🟢        | Good balance between speed and accuracy      |
| `medium`             | ⚡     | 🟢🟢      | Great balance for most use cases             |
| `large` / `large-v3` | 🐢     | 🟢🟢🟢    | Highest accuracy (slower, requires GPU)      |

💡 **Tip:**  
If you know the language spoken in the audio or video, specify it with `--language` (e.g., `--language English` or `--language Italian`)  
to get a more accurate and natural transcription.

---

## 📂 Generated outputs

Whisper automatically creates several output files:

- `file.txt` → plain text transcription  
- `file.srt` → subtitles with timestamps  
- `file.vtt` → web-compatible subtitle format  
- `file.json` → structured data with time segments  

---

## 🧰 Requirements

- A **Google account** (to access Colab)  
- Stable Internet connection  
- (Optional) Colab GPU for `large` or `large-v3` models

---

## 📘 License

This project uses [OpenAI Whisper](https://github.com/openai/whisper), released under the **MIT License**.  
You are free to use, modify, and share this code, as long as you provide proper attribution.

---

✅ **Final tip:**  
If you find this project useful, please give it a ⭐ on GitHub and share it!

---

🇮🇹 ITALIANO  
# 🎙️ Trascrizione Audio e Video con Whisper su Google Colab  

Trascrivi facilmente **audio e video (anche da YouTube)** in testo o sottotitoli (`.txt`, `.srt`, `.vtt`) utilizzando il modello **Whisper** di OpenAI — direttamente su **Google Colab**, senza bisogno di installare nulla sul tuo computer.

[![Apri in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1FU2OXAyBVkErRAIVDwB0H_PYJwRtvWIx?usp=sharing)

---

## 🧩 Come funziona

All’interno del notebook Colab troverai **tutti i passaggi già pronti e spiegati** in ordine logico.  
In breve, il flusso di lavoro è questo:

1. **Installazione automatica** di Whisper e delle librerie necessarie (`yt-dlp`, `ffmpeg`, ecc.).  
   ⚠️ *Attendi sempre che appaia la spunta verde accanto alle celle prima di continuare.*

2. **Download opzionale da YouTube** tramite `yt-dlp`, con conversione automatica in audio `.m4a`.

3. **Caricamento di un file locale**, se vuoi trascrivere un tuo audio o video.

4. **Scelta del modello Whisper:**  
   puoi selezionare tra modelli più **leggeri e veloci** (`tiny`, `base`) o più **accurati** (`large`, `large-v3`).  
   👉 Se conosci la lingua parlata, impostala con il parametro `--language` per ottenere una trascrizione più precisa.

5. **Avvio della trascrizione:**  
   Whisper trascrive automaticamente il parlato e genera i file di testo e sottotitoli (`.txt`, `.srt`, `.vtt`).

6. **Salvataggio dei risultati:**  
   Tutti i file vengono salvati nella stessa cartella del Colab, pronti da scaricare.

---

## 🧠 Modelli disponibili

Whisper offre diversi modelli, dal più leggero e veloce al più preciso e pesante:

| Modello              | Velocità | Precisione | Descrizione breve                               |
|----------------------|:--------:|:-----------:|------------------------------------------------|
| `tiny`               | ⚡⚡⚡     | 🟡          | Estremamente veloce, qualità base              |
| `small`              | ⚡⚡      | 🟢          | Buon compromesso tra velocità e accuratezza    |
| `medium`             | ⚡        | 🟢🟢        | Ottimo equilibrio per la maggior parte dei casi|
| `large` / `large-v3` | 🐢        | 🟢🟢🟢      | Massima precisione (più lento, richiede GPU)   |

💡 **Suggerimento:**  
Se conosci la lingua parlata nel video o nell’audio, specifica `--language` (es. `--language Italian`)  
per ottenere una trascrizione più accurata e naturale.

---

## 📂 Output generati

Whisper produce automaticamente diversi file di output:

- `file.txt` → trascrizione semplice  
- `file.srt` → sottotitoli con timestamp  
- `file.vtt` → formato sottotitoli web compatibile  
- `file.json` → dati strutturati con intervalli temporali  

---

## 🧰 Requisiti

- Account **Google** (per accedere a Colab)  
- Connessione Internet stabile  
- (Facoltativo) GPU Colab per modelli `large` o `large-v3`

---

## 📘 Licenza

Questo progetto utilizza [OpenAI Whisper](https://github.com/openai/whisper), rilasciato sotto licenza **MIT**.  
Puoi utilizzare, modificare e condividere liberamente questo codice, citando la fonte.

---

✅ **Suggerimento finale:**  
Se questo progetto ti è stato utile, lascia una ⭐ alla repository e condividilo!
