IF (NOT DISABLE_UNIT_TEST)
  ADD_SUBDIRECTORY (unit)
ENDIF ()
IF (NOT DISABLE_LONG_TEST)
  ADD_SUBDIRECTORY (long)
ENDIF ()
IF (NOT DISABLE_MOCK_TEST)
  ADD_SUBDIRECTORY (mock_build)
ENDIF ()
