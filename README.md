# Numerology Script

This is a Python script for calculating numerology values such as Life Path, Expression, Soul Urge, and Birthday based on a person's name and date of birth. The script also provides detailed meanings for each numerology value.

## Features

- Calculate Life Path, Expression, Soul Urge, and Birthday numbers
- Detect and handle master numbers (11, 22, 33)
- Provide detailed meanings for each numerology value
- User-friendly input validation
- Colorful and formatted terminal output using `colorama`

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/numerology.git
   cd numerology
   ```

2. Create and activate a virtual environment (optional):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```

3. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
Run the script:

```bash
python3 numerology.py
Follow the prompts to enter your full name and date of birth.
```

View the calculated numerology values and their detailed meanings in the terminal output.

### File Structure
numerology.py: Main script for calculating and displaying numerology values.
meanings.py: Contains dictionaries with general and detailed meanings for numerology values.
requirements.txt: Lists the required Python packages (colorama).

### License
This project is licensed under the GNU General Public License v3.0. See the LICENSE file for details.

### Contributing
Contributions are welcome! Please feel free to submit a Pull Request or open an Issue on GitHub.

### Acknowledgments
This project uses the colorama library for terminal colors.
