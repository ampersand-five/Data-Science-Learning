Notes:
- Pytorch stopped supporting Intel Macs in version 2.3. So I need to use Pytorch 2.2.x
  for my Intel Mac.
- Pytorch 2.2 requires Python 3.11.x, so I need to use Python 3.11.x.
- Pytorch 2.3 is the first one to support Numpy 2.0, so I need to use Numpy 1.x for
  Pytorch 2.2.x.
- Darts v 30 introduced better anomaly detection. Using that as the minimum version.

- VS Code would not recognize the venv Poetry made in the folder. I had to manually add
  the venv folder path to the `python.venvFolders` setting in VS Code.