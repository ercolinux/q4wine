cmake_minimum_required(VERSION 2.6)

SET( ICON_PIXMAPS
    ${CMAKE_SOURCE_DIR}/src/data/eject.png
    ${CMAKE_SOURCE_DIR}/src/data/explorer.png
    ${CMAKE_SOURCE_DIR}/src/data/exec_wine.png
    ${CMAKE_SOURCE_DIR}/src/data/notepad.png
    ${CMAKE_SOURCE_DIR}/src/data/regedit.png
    ${CMAKE_SOURCE_DIR}/src/data/uninstaller.png
    ${CMAKE_SOURCE_DIR}/src/data/winecfg.png
    ${CMAKE_SOURCE_DIR}/src/data/wineconsole.png
)

IF( RELEASE )
    install(FILES ${ICON_PIXMAPS} DESTINATION  ${DATA_ENTRY_PATH})
ENDIF( RELEASE )
