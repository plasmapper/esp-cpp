UART Component
==============

Installation
------------
Add this to ``main/idf_component.yml``:

.. code-block:: yaml

  dependencies:
    pl_common:
      path: component
      git: https://github.com/plasmapper/uart-esp-cpp.git

Add this to the source code:

.. code-block:: C++

  #include "pl_uart.h"
  
Add ``extern "C"`` to ``app_main`` in ``main.cpp``:

.. code-block:: C++

  extern "C" void app_main(void) {...}

API reference
-------------

.. toctree::
  
  types      
  uart_port
  uart_server
  
Examples
--------
| `UART port <https://github.com/plasmapper/uart-esp-cpp/tree/main/examples/port>`_
| `UART echo server <https://github.com/plasmapper/uart-esp-cpp/tree/main/examples/echo_server>`_
