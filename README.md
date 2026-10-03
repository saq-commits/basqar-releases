# Basqar — орнатқыштар

Бұл репода тек Basqar desktop қолданбасының орнатқыштары мен автожаңарту манифесті (`latest.json`)
тұрады, код жоқ. Жиналады: `saq-commits/basqar-desktop` CI.

## Орнату (macOS, Apple Silicon)

1. [Соңғы нұсқа](https://github.com/saq-commits/basqar-releases/releases/latest) → `Basqar_…_aarch64.dmg` жүктеу.
2. `.dmg`-ны ашып, `Basqar.app`-ты **Applications**-қа сүйреу.
3. Терминалда бір рет (қолданба әзірге Apple Developer ID-мен қол қойылмаған, онсыз macOS
   «зақымдалған» деп ашпайды):
   ```bash
   xattr -cr /Applications/Basqar.app
   ```
4. Applications-тан Basqar-ды ашыңыз.

Кейінгі нұсқалар қолданба ашылғанда өзі табылады: жоғарыда «Жаңа нұсқа» баннері шығады.
Жаңартулар қол қойылған, қолданба тексермей орнатпайды.
