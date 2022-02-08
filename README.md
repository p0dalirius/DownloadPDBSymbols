# DownloadPDBSymbols

<p align="center">
    A Python script to download PDB files associated with a Portable Executable (PE).
    <br>
    <img alt="GitHub release (latest by date)" src="https://img.shields.io/github/v/release/p0dalirius/DownloadPDBSymbols">
    <a href="https://twitter.com/intent/follow?screen_name=podalirius_" title="Follow"><img src="https://img.shields.io/twitter/follow/podalirius_?label=Podalirius&style=social"></a>
    <br>
</p>



![](./.github/)

## Features

 - [x] Download PDB symbols from `msdl.microsoft.com`.
 - [x] Process a single or a batch of PortableExecutable (PE) files.

## Usage

```
$ ./DownloadPDBSymbols.py -h
usage: DownloadPDBSymbols.py [-h] (-f PE_FILE | -d PE_DIR) [-S SYMBOLS_DIR] [-v]

Description message

optional arguments:
  -h, --help            show this help message and exit
  -f PE_FILE, --pe-file PE_FILE
  -d PE_DIR, --pe-dir PE_DIR
  -S SYMBOLS_DIR, --symbols-dir SYMBOLS_DIR
                        Output dir where symbols will be downloaded.
  -v, --verbose         Verbose mode. (default: False)
```

## Example

![](./.github/example.png)

## Contributing

Pull requests are welcome. Feel free to open an issue if you want to add other features.
