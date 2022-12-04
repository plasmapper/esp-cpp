Installation
------------
The component requires ESP-IDF 5.0 and higher and is installed using `IDF Component Manager <https://github.com/espressif/idf-component-manager>`_.

Add this to the ``idf_component.yml`` in the project ``main`` directory or in the component directory:

.. code-block:: yaml
  :substitutions:
  
  dependencies:
    pl_|COMPONENT|:
      path: component
      git: https://github.com/plasmapper/|COMPONENT|-esp-cpp.git

Add this to the source code:

.. code-block:: C++
  :substitutions:

  #include "pl_|COMPONENT|.h"
  
Add ``extern "C"`` to the ``app_main`` function:

.. code-block:: C++

  extern "C" void app_main(void) {...}
  
Add this to the ``sdkconfig.defaults`` in the project directory or configure the values using `Project Configuration <https://docs.espressif.com/projects/esp-idf/en/latest/esp32/api-reference/kconfig.html>`_:
