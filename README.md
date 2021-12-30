<p align="center"><img src="https://capsule-render.vercel.app/api?type=soft&fontColor=e5ab3e&text=pystardust/ani-cli&height=150&fontSize=60&desc= beautiful, documented and portable.&descAlignY=75&descAlign=60&color=00000000&animation=twinkling"></p> 

# ani-cli

> Thank you @RaynardGerraldo for fixing the crippling issues 221 and 202

A cli to browse and watch anime.

This tool scrapes the site [gogoanime](https://gogoanime.pe).

## Download

```bash
git clone https://github.com/pystardust/ani-cli.git
```

## Install

```bash
cd ani-cli
sudo make
```

## Usage

  ### watch anime
  ``ani-cli <query>``

  ### download anime
  ``ani-cli -d <query>``

  ### resume watching anime
  ``ani-cli -H``

  ### delete anime from history
  ``ani-cli -D``

  ### set video quality
  ``ani-cli -q 360``

By default `ani-cli` would try to get the best video quality available  
You can give specific qualities like `360/480/720/..`

You can also use special names:

* `best`: Select the best quality available
* `worst`: Select the worst quality available

Multiple episodes can be viewed/downloaded by giving the episode range like so

  Choose episode [1-13]: 1 6

This would open/download episodes 1 2 3 4 5 6

## Dependencies

* grep
* curl
* sed
* mpv
* ffmpeg

## Misc

- Windows instructions can be found in this branch https://github.com/pystardust/ani-cli/tree/windows-vlc
