

add_executable(
    examples

    mainwindow.cpp
        main.cpp
        avatarsettingseditor.cpp
        badgesettingseditor.cpp
        checkboxsettingseditor.cpp
        fabsettingseditor.cpp
        raisedbuttonsettingseditor.cpp
        flatbuttonsettingseditor.cpp
        iconbuttonsettingseditor.cpp
        progresssettingseditor.cpp
        circularprogresssettingseditor.cpp
        slidersettingseditor.cpp
        radiobuttonsettingseditor.cpp
        togglesettingseditor.cpp
        textfieldsettingseditor.cpp
        tabssettingseditor.cpp
        snackbarsettingseditor.cpp
        dialogsettingseditor.cpp
        drawersettingseditor.cpp
        scrollbarsettingseditor.cpp
        appbarsettingseditor.cpp
        autocompletesettingseditor.cpp
        menusettingseditor.cpp
        mainwindow.h
        avatarsettingseditor.h
        badgesettingseditor.h
        checkboxsettingseditor.h
        fabsettingseditor.h
        raisedbuttonsettingseditor.h
        flatbuttonsettingseditor.h
        iconbuttonsettingseditor.h
        progresssettingseditor.h
        circularprogresssettingseditor.h
        slidersettingseditor.h
        radiobuttonsettingseditor.h
        togglesettingseditor.h
        textfieldsettingseditor.h
        tabssettingseditor.h
        snackbarsettingseditor.h
        dialogsettingseditor.h
        drawersettingseditor.h
        scrollbarsettingseditor.h
        appbarsettingseditor.h
        autocompletesettingseditor.h
        menusettingseditor.h

        examples.qrc

        avatarsettingsform.ui
        badgesettingsform.ui
        checkboxsettingsform.ui
        fabsettingsform.ui
        flatbuttonsettingsform.ui
        iconbuttonsettingsform.ui
        progresssettingsform.ui
        circularprogresssettingsform.ui
        slidersettingsform.ui
        snackbarsettingsform.ui
        radiobuttonsettingsform.ui
        togglesettingsform.ui
        textfieldsettingsform.ui
        tabssettingsform.ui
        dialogsettingsform.ui
        drawersettingsform.ui
        scrollbarsettingsform.ui
        appbarsettingsform.ui

)

target_link_libraries(examples
PRIVATE
components
Qt${QT_VERSION_MAJOR}::Widgets
Qt${QT_VERSION_MAJOR}::StateMachine
)

# target_include_directories(examples PRIVATE ${CMAKE_CURRENT_LIST_DIR}/../components)
