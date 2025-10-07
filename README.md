A VRAM percentage chart widget config for your sfwbar.

Download the gpu.source and gpu.widget files and put them in your ~/.config/sfwbar directory.

Includes an example sfwbar.config file with the default config plus the gpu widget added.

If you want to use your existing sfwbar.config, just add this wherever you want the widget on your bar:

`include("gpu.widget")`

And then style your chart with this in the CSS section:

```
chart#gpu_chart {
  background: rgba(127,127,127,0.3);
  min-width: 9px;
  -GtkWidget-vexpand: true;
  margin: 2px;
  border: 1px solid @theme_fg_color;
  color: pink;
}
```
Enjoy!
