### Micro-Mamba virtual environments:
- Install, from scratch, from a given folder, with
(alias mba = micromamba):
  ```bash
  mba create -f venv.yml
  ```
- Activate venv with:
  ```bash
  mba activate <venv name>
  ```
- Deactivate venv with:
  ```bash
  mba deactivate
  ```
- Install new dependencies by adding them to the venv.yml file and then outside the
environment (i.e. don't activate it first) run:
  ```bash
  mba env update -f venv.yml
  ```

Notes:
- Micromamba is not supported by VS Code's IntelliSense that powers the hover over
  variable information. Intellisense tries to use a conda command but micromamba doesn't
  have conda installed so it fails. VS Code is building a general solution for this that
  micromamba will be able to use, but it's not available now. Pixi is supported and
  Poetry is supported. Otherwise, everything else works on Micromamba.