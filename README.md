# hifz-juz-completion-certificates
```python
juz_data = [
    {"juz": 1,  "arabic": "آلم"},
    {"juz": 2,  "arabic": "سَيَقُولُ"},
    {"juz": 3,  "arabic": "تِلْكَ ٱلْرُّسُلُ"},
    {"juz": 4,  "arabic": "لَنْ تَنَالُوْ الْبِرَّ"},
    {"juz": 5,  "arabic": "وَٱلْمُحْصَنَاتُ"},
    {"juz": 6,  "arabic": "لَا يُحِبُّ ٱللهُ"},
    {"juz": 7,  "arabic": "وَإِذَا سَمِعُوا"},
    {"juz": 8,  "arabic": "وَلَوْ أَنَّنَا"},
    {"juz": 9,  "arabic": "قَالَ ٱلْمَلَأُ"},
    {"juz": 10, "arabic": "وَٱعْلَمُواْ"},
    {"juz": 11, "arabic": "يَعْتَذِرُونَ"},
    {"juz": 12, "arabic": "وَمَا مِنْ دَآبَّةٍ"},
    {"juz": 13, "arabic": "وَمَا أُبَرِّئُ"},
    {"juz": 14, "arabic": "رُبَمَا"},
    {"juz": 15, "arabic": "سُبْحَانَ ٱلَّذِى"},
    {"juz": 16, "arabic": "قَالَ أَلَمْ"},
    {"juz": 17, "arabic": "ٱقْتَرَبَ لِلْنَّاسِ"},
    {"juz": 18, "arabic": "قَدْ أَفْلَحَ"},
    {"juz": 19, "arabic": "وَقَالَ ٱلَّذِينَ"},
    {"juz": 20, "arabic": "أَمَّنْ خَلَقَ"},
    {"juz": 21, "arabic": "أُتْلُ مَاأُوْحِیَ"},
    {"juz": 22, "arabic": "وَمَنْ يَّقْنُتْ"},
    {"juz": 23, "arabic": "وَمَآ لي"},
    {"juz": 24, "arabic": "فَمَنْ أَظْلَمُ"},
    {"juz": 25, "arabic": "إِلَيْهِ يُرَدُّ"},
    {"juz": 26, "arabic": "حم"},
    {"juz": 27, "arabic": "قَالَ فَمَا خَطْبُكُم"},
    {"juz": 28, "arabic": "قَدْ سَمِعَ ٱللهُ"},
    {"juz": 29, "arabic": "تَبَارَكَ ٱلَّذِى"},
    {"juz": 30, "arabic": "عَمَّ"}  # Assumed text for Juz 30.
]
```
You can use the docx2pdf package to convert DOCX files to PDF. First, install the package if you haven’t already:

```bash
pip install docx2pdf
```
Then, you can run the following one-liner from your terminal (in the folder where your DOCX files are located):

```bash
python -c "from docx2pdf import convert; convert('.')"
```
