# Basqar — орнатқыштар

Бұл репода тек Basqar desktop қолданбасының орнатқыштары мен автожаңарту манифесті (`latest.json`)
тұрады, код жоқ. Жиналады: `saq-commits/basqar-desktop` CI.

## Орнату (macOS, Apple Silicon)

1. [Соңғы нұсқа](https://github.com/saq-commits/basqar-releases/releases/latest) → `Basqar_…_aarch64.dmg` жүктеу.
2. `.dmg`-ны ашып, `Basqar.app`-ты **Applications**-қа сүйреу.
3. Қолданба әзірге Apple Developer ID-мен қол қойылмаған, сондықтан бір рет екі жолдың бірі:
   - терминалда:
     ```bash
     xattr -cr /Applications/Basqar.app
     ```
   - немесе Basqar-ды ашып көріңіз, macOS бөгейді; сосын **System Settings → Privacy & Security**
     төменінде **Open Anyway** басыңыз.

   `0.1.5` және одан ескі нұсқалар «is damaged» деп ашылмайды — тек `xattr -cr` көмектеседі.
4. Applications-тан Basqar-ды ашыңыз.

Кейінгі нұсқалар қолданба ашылғанда өзі табылады: жоғарыда «Жаңа нұсқа» баннері шығады.
Жаңартулар қол қойылған, қолданба тексермей орнатпайды.
