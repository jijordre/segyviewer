set(PYTHON_SOURCES
    __init__.py
    layoutcombo.py
    layoutcanvas.py
    layoutfigure.py
    colormapcombo.py

    slicemodel.py
    slicedatasource.py
    sliceviewcontext.py
    sliceview.py
    sliceviewwidget.py
    settingswindow.py
    _samplescalecontroller.py
    _indexcontroller.py
    _plotexportsettingscontroller.py
    arrayspinbox.py
    segyviewwidget.py

    )

add_python_package(segyviewlib segyviewlib "${PYTHON_SOURCES}")
