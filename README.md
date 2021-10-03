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
allows the paginator to start in a different context than the one from which it was invoked.

## Customisation
It is easy to create and customise buttons if desired. By default, there are 5 standard navigation buttons 
and 1 quit button. Navigation buttons are disabled in situations where they are unavailable to be clicked.

Information on button attributes can be found [here](https://discordpy.readthedocs.io/en/master/api.html#id7).


