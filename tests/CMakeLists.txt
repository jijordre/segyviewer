configure_file(test-data/small.sgy test-data/small.sgy COPYONLY)

add_python_test(python.segyview test_segyview.py)
