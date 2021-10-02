# discordpy-paginator
A simple class for paginating menus with views.
Compatible with the latest and last official release of [discord.py, 2.0](https://github.com/Rapptz/discord.py).

## Usage
Install discord.py 2.0 with Python 3.8 or later.
```bash
python3.8 -m pip install -U git+https://github.com/Rapptz/discord.py
```
It is suggested to place the file in a general `utils` folder, from where it can then be reused.

The paginator can be constructed with the class `PaginationView()`, which expects to be given a list of embeds.

The paginator needs to be started by calling `start()`. An additional parameter, `notification_ctx`, is supplied, which 
allows the paginator to start in a different context than the one from which it was invoked. This can be useful for some
types of situations.


