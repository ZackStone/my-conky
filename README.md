# my-conky

How to install and configure: [A Beginner's Guide to Conky](https://www.lifewire.com/beginners-guide-to-conky-4043352)

Fork the repo, play with the options, build your own custom style and share your Conky template.

![Image 1](https://github.com/zackstone/my-conky/blob/master/Screenshot1.png?raw=true)

![Image 2](https://github.com/zackstone/my-conky/blob/master/Screenshot2.png?raw=true)

## Some info

- In the wireless section, replace `wlp2s0` with your adapter name (execute `iwconfig` or `ifconfig` in terminal to find it).
- Change `color1` (default green) to other color that you like (you can also define more color variables).
- You can set many disk partitions, just duplicate and change the path.
- Background transparency: 
  - `own_window_argb_visual` (`true` or `false`)
  - `own_window_argb_value` (range: 0-255)
  - `own_window_colour` (color name ou rgb)
  
- [Conky variables](http://conky.sourceforge.net/variables.html)
- [Conky configuration settings](http://conky.sourceforge.net/config_settings.html)

Based on [My Conky Config 1.3 by hundone](https://www.deviantart.com/hundone/art/My-Conky-Config-1-3-60095106)
