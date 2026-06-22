## Data download

Large trajectory files are stored using Git LFS.

For a single trajectory file, users may download it directly from the GitHub file page using the download button.

For the complete dataset, we recommend installing Git LFS and downloading the repository with:

```bash
git lfs install
git clone https://github.com/lhgaogroup/PEG-surfactant.git
cd PEG-surfactant
git lfs pull
```

If the downloaded trajectory file is only a few hundred bytes, it is likely a Git LFS pointer file rather than the actual trajectory file. In that case, please install Git LFS and run `git lfs pull`.

Please note that Git LFS may have monthly bandwidth limitations. If the trajectory files cannot be downloaded due to Git LFS quota limitations, please try again later or contact the authors for access to the data.
