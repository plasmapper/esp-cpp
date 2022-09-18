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