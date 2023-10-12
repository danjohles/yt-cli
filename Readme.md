# yt-cli
Search and play YouTube videos via the command line.

## Installation
It's just a simple bash script and relies on `yt-dlp`, `jq`, `fzf` and `mpv` for the heavy
lifting, so make sure these programs are installed.   
Place it somewhere like `~/.scripts`,     
make it executable and add an alias in your `.bashrc`   
`alias yt='/home/user/.scripts/yt'`    
On Debian-based distros like Ubuntu, to get the latest version of yt-dlp, get the binaries from GitHub

```sh
sudo wget https://github.com/yt-dlp/yt-dlp/releases/latest/download/yt-dlp -O /usr/local/bin/yt-dlp
sudo chmod a+rx /usr/local/bin/yt-dlp  
```

## Usage
```
USAGE yt [OPTIONS] "SEARCH STRING"

Search and play YouTube videos.

  -h, --help         Show this help.
  -n, --num-results  Number of search results to fetch, defaults to 50.
  -c, --consumer     Command to be called with URLs of selected videos,
                     default is mpv.
  -v, --version      Print version.
  --                 Stops interpreting the following arguments as options.
```
##Showcase

https://github.com/danjohles/yt-cli/assets/82652108/9eb9332e-3cd0-4fc8-a381-28a11579d530

