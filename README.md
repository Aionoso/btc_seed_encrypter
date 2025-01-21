# btc_seed_encrypter
Uses a PW (UTF-8) in a SHA-2 512 Hash in Decimal to do a Ceasar encryption using the bip39 words.


## Use this to create environment and exe
1. `python -m venv env`

2. `env\scripts\activate`

3. `pip install pyinstaller`

4. `pyinstaller --noconfirm --noconsole --onefile --icon "icon.ico" --add-data "icon.png;." --version-file="version.txt" "btc_seed_encrypter.py"`
