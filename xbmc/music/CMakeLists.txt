set(SOURCES Album.cpp
            Artist.cpp
            ContextMenus.cpp
            GUIViewStateMusic.cpp
            MusicDatabase.cpp
            MusicDbUrl.cpp
            MusicInfoLoader.cpp
            MusicLibraryQueue.cpp
            MusicThumbLoader.cpp
            Song.cpp)

set(HEADERS Album.h
            Artist.h
            ContextMenus.h
            EmbeddedArt.h
            GUIViewStateMusic.h
            MusicDatabase.h
            MusicDbUrl.h
            MusicInfoLoader.h
            MusicLibraryQueue.h
            MusicThumbLoader.h
            Song.h)

core_add_library(music)
