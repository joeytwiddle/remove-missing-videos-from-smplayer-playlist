## Installation

1. Clone this repository

2. Run `npm install multi-ini`

3. You may like to link the script into your PATH, to make it easy to run:

   ```bash
   sudo ln -s "$PWD"/remove-missing-videos-from-smplayer-playlist /usr/bin/
   ```

## Usage

1. Stop SMPlayer

2. Run `remove-missing-videos-from-smplayer-playlist`

3. Start SMPlayer

4. If you are happy, you may like to delete the backup files:

   ```bash
   del ~/.config/smplayer/playlist.ini.20*
   ```

