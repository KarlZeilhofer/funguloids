bininstall_PROGRAMS = funguloids
noinst_PROGRAMS = makempk

funguloids_CPPFLAGS = -I$(top_srcdir)/include -I$(top_srcdir)/include/SimpleIni
funguloids_LDADD = @OIS_LIBS@ @OGRE_LIBS@ @LUA_LIBS@
funguloids_CXXFLAGS = @OIS_CFLAGS@ @OGRE_CFLAGS@ @LUA_CFLAGS@

funguloids_SOURCES = asteroid.cpp \
	ballworm.cpp \
	base.cpp \
	bground.cpp \
	blackhole.cpp \
	effects.cpp \
	fmodexsoundsystem.cpp \
	gamecamera.cpp \
	game.cpp \
	hiscore.cpp \
	input.cpp \
	main.cpp \
	menu.cpp \
	movingobject.cpp \
	mp3stream.cpp \
	mpak.cpp \
	mpakogre.cpp \
	mushroom.cpp \
	object.cpp \
	objectsystem.cpp \
	oggstream.cpp \
	ogreapp.cpp \
	ogrelistener.cpp \
	openalchannel.cpp \
	openalchannelgroup.cpp \
	openalsoundsystem.cpp \
	player.cpp \
	playlist.cpp \
	scriptsystem.cpp \
	streamplayer.cpp \
	tentacles.cpp \
	whirler.cpp

makempk_CPPFLAGS = -I$(top_srcdir)/include
makempk_SOURCES = makempk.cpp \
	mpak.cpp
