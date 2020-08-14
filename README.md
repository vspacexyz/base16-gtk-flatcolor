# base16-gtk-flatcolor
This is a [Base16](https://github.com/chriskempson/base16) template for [FlatColor](https://github.com/jasperro/FlatColor), a gtk3 theme by jasperro and deviantfero,

## Instructions
	git clone https://github.com/jasperro/FlatColor ~/.local/share/themes/flatcolor
	cd ~/.local/share/themes/flatcolor
	ln -fs $gtk2_config_path ~/.local/share/themes/flatcolor/gtk-2.0/gtkrc
	ln -fs $gtk3_config_path ~/.local/share/themes/flatcolor/gtk-3.0/gtk.css
	ln -fs $gtk3_config_path ~/.local/share/themes/flatcolor/gtk-3.20/gtk.css

...where gtk_config_path contain the path to configs created by base16 builder.
