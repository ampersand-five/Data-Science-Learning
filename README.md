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