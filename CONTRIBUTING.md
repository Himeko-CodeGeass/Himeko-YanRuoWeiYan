# Contributing to Himeko-YanRuoWeiYan

Thank you for your interest in contributing to **Himeko-YanRuoWeiYan** (言若未言). We welcome modular extensions that respect human cognitive dignity and non-invasive design.

## Guidelines for Contributors
1. **Respectful Ambiguity:** Core algorithms should avoid invasive profiling and preserve user control.
2. **On-device first:** Do not add network imports to `core/`. Changes must keep `tests/test_no_network.py` passing.
3. **Main-Branch Discipline:** Please run `python typing_demo.py` and `python -m pytest tests/test_no_network.py -v` locally before opening a pull request.

Please open an issue or submit a pull request.
