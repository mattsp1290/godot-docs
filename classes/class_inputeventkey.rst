.. Generated automatically by doc/tools/makerst.py in Godot's source tree.
.. DO NOT EDIT THIS FILE, but the InputEventKey.xml source instead.
.. The source is found in doc/classes or modules/<name>/doc_classes.

.. _class_InputEventKey:

InputEventKey
=============

**Inherits:** :ref:`InputEventWithModifiers<class_inputeventwithmodifiers>` **<** :ref:`InputEvent<class_inputevent>` **<** :ref:`Resource<class_resource>` **<** :ref:`Reference<class_reference>` **<** :ref:`Object<class_object>`

**Category:** Core

Brief Description
-----------------

Input event type for keyboard events.

Member Functions
----------------

+------------------------+-------------------------------------------------------------------------------------------------------+
| :ref:`int<class_int>`  | :ref:`get_scancode<class_InputEventKey_get_scancode>` **(** **)** const                               |
+------------------------+-------------------------------------------------------------------------------------------------------+
| :ref:`int<class_int>`  | :ref:`get_scancode_with_modifiers<class_InputEventKey_get_scancode_with_modifiers>` **(** **)** const |
+------------------------+-------------------------------------------------------------------------------------------------------+
| :ref:`int<class_int>`  | :ref:`get_unicode<class_InputEventKey_get_unicode>` **(** **)** const                                 |
+------------------------+-------------------------------------------------------------------------------------------------------+
| void                   | :ref:`set_echo<class_InputEventKey_set_echo>` **(** :ref:`bool<class_bool>` echo **)**                |
+------------------------+-------------------------------------------------------------------------------------------------------+
| void                   | :ref:`set_pressed<class_InputEventKey_set_pressed>` **(** :ref:`bool<class_bool>` pressed **)**       |
+------------------------+-------------------------------------------------------------------------------------------------------+
| void                   | :ref:`set_scancode<class_InputEventKey_set_scancode>` **(** :ref:`int<class_int>` scancode **)**      |
+------------------------+-------------------------------------------------------------------------------------------------------+
| void                   | :ref:`set_unicode<class_InputEventKey_set_unicode>` **(** :ref:`int<class_int>` unicode **)**         |
+------------------------+-------------------------------------------------------------------------------------------------------+

Member Variables
----------------

  .. _class_InputEventKey_echo:

- :ref:`bool<class_bool>` **echo** - If ``true`` the key was already pressed before this event. It means the user is holding the key down.

  .. _class_InputEventKey_pressed:

- :ref:`bool<class_bool>` **pressed** - If ``true`` the key's state is pressed. If ``false`` the key's state is released.

  .. _class_InputEventKey_scancode:

- :ref:`int<class_int>` **scancode** - Key scancode, one of the ``KEY\_\*`` constants in @global Scope.

  .. _class_InputEventKey_unicode:

- :ref:`int<class_int>` **unicode** - Key unicode identifier when relevant.


Description
-----------

Stores key presses on the keyboard. Supports key presses, key releases and :ref:`echo<class_InputEventKey_echo>` events.

Member Function Description
---------------------------

.. _class_InputEventKey_get_scancode:

- :ref:`int<class_int>` **get_scancode** **(** **)** const

.. _class_InputEventKey_get_scancode_with_modifiers:

- :ref:`int<class_int>` **get_scancode_with_modifiers** **(** **)** const

.. _class_InputEventKey_get_unicode:

- :ref:`int<class_int>` **get_unicode** **(** **)** const

.. _class_InputEventKey_set_echo:

- void **set_echo** **(** :ref:`bool<class_bool>` echo **)**

.. _class_InputEventKey_set_pressed:

- void **set_pressed** **(** :ref:`bool<class_bool>` pressed **)**

.. _class_InputEventKey_set_scancode:

- void **set_scancode** **(** :ref:`int<class_int>` scancode **)**

.. _class_InputEventKey_set_unicode:

- void **set_unicode** **(** :ref:`int<class_int>` unicode **)**


