# Beat Shaker

Audio beat visualizer overlay using PyGame. Listens to Easy Effects Sink and displays a pulsing border + flash effects in fullscreen.

## Usage

1. Install dependencies: `pip install -r requirements.txt`
2. Edit `config.yaml` (set device_index).
3. Run: `python main.py`

## Building standalone binary

```bash
pip install pyinstaller
pyinstaller --onefile --add-data "config.yaml:." main.py -n beat-shaker
