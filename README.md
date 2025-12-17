# toolkit_capstone

A small command-line calculator used for demonstration and testing.

## Requirements ✅
- Python 3.8 or newer

## Run 🔧
1. Open a terminal in the project root.
2. Run the script with Python 3:

```bash
python3 calculator.py
```

3. Follow the on-screen prompts to choose an operation and enter numbers.

## Notes / Known issue ⚠️
- The interactive code currently calls arithmetic functions before they are defined which may raise a NameError. To fix this, either:
  - Move the function definitions (`add`, `subtract`, `multiply`, `divide`) above the interactive prompt, or
  - Wrap the interactive prompt in a `if __name__ == "__main__":` block and place it after the function definitions.

## Contributing 💡
Feel free to open issues or submit pull requests to fix the known issue or add features.
