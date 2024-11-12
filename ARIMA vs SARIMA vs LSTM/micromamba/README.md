Notes:
- Micromamba is not supported by VS Code's IntelliSense that powers the hover over
  variable information. Intellisense tries to use a conda command but micromamba doesn't
  have conda installed so it fails. VS Code is building a general solution for this that
  micromamba will be able to use, but it's not available now. Pixi is supported and
  Poetry is supported. Otherwise, everything else works with Micromamba.