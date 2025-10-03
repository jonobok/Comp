# Comparator (Windows EXE via GitHub Actions)

This repo builds a portable **Comparator.exe** (no Python required on the work PC).

## Quick steps
1. Create a **new private GitHub repo**.
2. Upload these files:
   - `comparator_app.py`
   - `.github/workflows/build-windows.yml`
3. Go to the **Actions** tab → enable workflows if asked.
4. Click the latest run → download the **Comparator-Windows** artifact → inside is `Comparator.exe`.
5. Copy `Comparator.exe` to your work PC and double‑click.

If SmartScreen warns, click **More info → Run anyway** (normal for unsigned internal tools).
