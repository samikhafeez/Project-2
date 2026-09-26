# Contributing

This repository preserves the original project and its recorded experiments. Start with the README for the current application and follow the relevant historical folder's instructions when reviewing earlier work.

1. Use a topic branch for changes.
2. Keep datasets, trained weights, face encodings and local media out of commits.
3. Keep stored notebook outputs when changing documentation. Run experiments separately when changing model behaviour, and record the configuration and evaluation split.
4. Stage the intended files, then run `python3 tools/check_repository.py` from the repository root. This checks tracked files; it does not run project code.
5. Describe what changed and which checks or runtime experiments were performed.

The GitHub Actions workflow runs the same static checks after publication. A passing check is not a claim that training, webcam inference or the API has been tested. Dependencies remain as declared by the original projects; no new performance result is implied.
