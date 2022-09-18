Network C++ Class Component for ESP-IDF
=======================================

Installation
------------
Add this to ``main/idf_component.yml``:

.. code-block:: yaml

  dependencies:
    pl_common:
      path: component
      git: https://github.com/plasmapper/network-esp-cpp.git

Add this to the source code:

.. code-block:: C++

  #include "pl_network.h"

API reference
-------------

.. toctree::
  
  types      
  network_interface
  ethernet
  wifi_station
  esp_network_interface
  esp_ethernet
  esp_wifi_station
  network_stream
  network_server
  tcp_client
  tcp_server
  
Examples
--------
| `Ethernet <https://github.com/plasmapper/network-esp-cpp/tree/main/examples/ethernet>`_
| `Wi-Fi station <https://github.com/plasmapper/network-esp-cpp/tree/main/examples/wifi_station>`_
| `TCP echo server <https://github.com/plasmapper/network-esp-cpp/tree/main/examples/tcp_echo_server>`_