circlesdir = $(datadir)/mdm/themes/circles
circles_DATA = \
	MdmGreeterTheme.desktop \
	circles.xml \
	background.svg \
	flower.png  \
	screenshot.png

circles_in_files = \
	MdmGreeterTheme.desktop.in

@INTLTOOL_DESKTOP_RULE@

EXTRA_DIST = $(circles_DATA) $(circles_in_files)

clean-local:
	/bin/rm -f MdmGreeterTheme.desktop
