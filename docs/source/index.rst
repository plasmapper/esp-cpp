PL C++ Class Components for ESP-IDF
===================================

Introduction
------------
This is a set of components for `ESP-IDF <https://github.com/espressif/esp-idf>`_. Some of the components are basically wrappers for ESP-IDF C API,
while others are supposed to provide some additional functionality and/or simplicity of project implementation.

The main features of these components are:

1. Recurrent locking of hardware and software resources for multithreaded applications.
2. Event generation and handling.
3. Lockable stream and buffer classes for data reading and writing.
4. Base server classes with virtual methods for request handling.
5. Specific protocol server and client implementations.
6. Specific hardware interface implementations.

Components
----------

.. toctree::
  :maxdepth: 2
  
  components/common/docs/index
  components/uart/docs/index
  components/network/docs/index
  components/modbus/docs/index