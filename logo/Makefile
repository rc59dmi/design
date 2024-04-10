# INKSCAPE = inkscape
INKSCAPE = flatpak run org.inkscape.Inkscape

RASTERS = raster.png

all: $(RASTERS)

raster.png: vector.svg
	$(INKSCAPE) $< --export-filename $@

clean:
	rm *.png
