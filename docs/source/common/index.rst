Common Component
================

Installation
------------
Add this to ``main/idf_component.yml``:

.. code-block:: yaml

  dependencies:
    pl_common:
      path: component
      git: https://github.com/plasmapper/common-esp-cpp.git

Add this to the source code:

.. code-block:: C++

  #include "pl_common.h"

Add ``extern "C"`` to ``app_main`` in ``main.cpp``:

.. code-block:: C++

  extern "C" void app_main(void) {...}

API reference
-------------

.. toctree::
  
  macros
  types      
  lockable
  lock_guard
  mutex
  buffer
  typed_buffer
  event
  event_handler
  stream
  hardware_interface
  server
