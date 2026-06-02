# Setup

The tutorial is designed to run in a browser-based GPU environment. The recommended option is **Google Colab with a GPU runtime**. If the conference provides a cloud GPU environment, use that access first and fall back to Colab if needed.

## What you need

- a laptop with a modern web browser
- a stable internet connection
- a Google account for Colab access
- basic Python familiarity

## Using Google Colab

1. Open one of the tutorial notebook pages from this site.
2. Click the **Open in Colab** badge.
3. Sign in with your Google account if prompted.
4. In Colab, go to **Runtime -> Change runtime type**.
5. Set **Hardware accelerator** to **GPU**.
6. Run the setup cell at the top of the notebook before running the rest of the tutorial.
7. Save your own working copy with **File -> Save a copy in Drive** if you want to keep your edits.

## Notes for attendees

- If a package install fails, rerun the setup cell and restart the runtime.
- GPU availability in Colab can vary by account and usage limits.
- The tutorial materials are notebook-based, so no local installation is required for the core hands-on session.

## Notebook links

- [Tutorial 1: Scikit-learn + RAPIDS](tutorials/tutorial-1.md)
- [Tutorial 2: Ray Tune + RAPIDS](tutorials/tutorial-2.md)
- [Tutorial 3: Skorch + RAPIDS](tutorials/tutorial-3.md)
