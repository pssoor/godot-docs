:github_url: hide

.. DO NOT EDIT THIS FILE!!!
.. Generated automatically from Godot engine sources.
.. Generator: https://github.com/godotengine/godot/tree/master/doc/tools/make_rst.py.
.. XML source: https://github.com/godotengine/godot/tree/master/doc/classes/EditorInspectorPlugin.xml.

.. _class_EditorInspectorPlugin:

EditorInspectorPlugin
=====================

**Inherits:** :ref:`RefCounted<class_RefCounted>` **<** :ref:`Object<class_Object>`

Plugin for adding custom property editors on the inspector.

.. rst-class:: classref-introduction-group

Description
-----------

**EditorInspectorPlugin** allows adding custom property editors to :ref:`EditorInspector<class_EditorInspector>`.

When an object is edited, the :ref:`_can_handle<class_EditorInspectorPlugin_method__can_handle>` function is called and must return ``true`` if the object type is supported.

If supported, the function :ref:`_parse_begin<class_EditorInspectorPlugin_method__parse_begin>` will be called, allowing to place custom controls at the beginning of the class.

Subsequently, the :ref:`_parse_category<class_EditorInspectorPlugin_method__parse_category>` and :ref:`_parse_property<class_EditorInspectorPlugin_method__parse_property>` are called for every category and property. They offer the ability to add custom controls to the inspector too.

Finally, :ref:`_parse_end<class_EditorInspectorPlugin_method__parse_end>` will be called.

On each of these calls, the "add" functions can be called.

To use **EditorInspectorPlugin**, register it using the :ref:`EditorPlugin.add_inspector_plugin<class_EditorPlugin_method_add_inspector_plugin>` method first.

.. rst-class:: classref-introduction-group

Tutorials
---------

- :doc:`Inspector plugins <../tutorials/plugins/editor/inspector_plugins>`

.. rst-class:: classref-reftable-group

Methods
-------

.. table::
   :widths: auto

   +-------------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
   | :ref:`bool<class_bool>` | :ref:`_can_handle<class_EditorInspectorPlugin_method__can_handle>` **(** :ref:`Object<class_Object>` object **)** |virtual| |const|                                                                                                                                                                                                                                                                                                                |
   +-------------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
   | void                    | :ref:`_parse_begin<class_EditorInspectorPlugin_method__parse_begin>` **(** :ref:`Object<class_Object>` object **)** |virtual|                                                                                                                                                                                                                                                                                                                      |
   +-------------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
   | void                    | :ref:`_parse_category<class_EditorInspectorPlugin_method__parse_category>` **(** :ref:`Object<class_Object>` object, :ref:`String<class_String>` category **)** |virtual|                                                                                                                                                                                                                                                                          |
   +-------------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
   | void                    | :ref:`_parse_end<class_EditorInspectorPlugin_method__parse_end>` **(** :ref:`Object<class_Object>` object **)** |virtual|                                                                                                                                                                                                                                                                                                                          |
   +-------------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
   | void                    | :ref:`_parse_group<class_EditorInspectorPlugin_method__parse_group>` **(** :ref:`Object<class_Object>` object, :ref:`String<class_String>` group **)** |virtual|                                                                                                                                                                                                                                                                                   |
   +-------------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
   | :ref:`bool<class_bool>` | :ref:`_parse_property<class_EditorInspectorPlugin_method__parse_property>` **(** :ref:`Object<class_Object>` object, :ref:`Variant.Type<enum_@GlobalScope_Variant.Type>` type, :ref:`String<class_String>` name, :ref:`PropertyHint<enum_@GlobalScope_PropertyHint>` hint_type, :ref:`String<class_String>` hint_string, :ref:`PropertyUsageFlags<enum_@GlobalScope_PropertyUsageFlags>` usage_flags, :ref:`bool<class_bool>` wide **)** |virtual| |
   +-------------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
   | void                    | :ref:`add_custom_control<class_EditorInspectorPlugin_method_add_custom_control>` **(** :ref:`Control<class_Control>` control **)**                                                                                                                                                                                                                                                                                                                 |
   +-------------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
   | void                    | :ref:`add_property_editor<class_EditorInspectorPlugin_method_add_property_editor>` **(** :ref:`String<class_String>` property, :ref:`Control<class_Control>` editor, :ref:`bool<class_bool>` add_to_end=false **)**                                                                                                                                                                                                                                |
   +-------------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
   | void                    | :ref:`add_property_editor_for_multiple_properties<class_EditorInspectorPlugin_method_add_property_editor_for_multiple_properties>` **(** :ref:`String<class_String>` label, :ref:`PackedStringArray<class_PackedStringArray>` properties, :ref:`Control<class_Control>` editor **)**                                                                                                                                                               |
   +-------------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+

.. rst-class:: classref-section-separator

----

.. rst-class:: classref-descriptions-group

Method Descriptions
-------------------

.. _class_EditorInspectorPlugin_method__can_handle:

.. rst-class:: classref-method

:ref:`bool<class_bool>` **_can_handle** **(** :ref:`Object<class_Object>` object **)** |virtual| |const|

Returns ``true`` if this object can be handled by this plugin.

.. rst-class:: classref-item-separator

----

.. _class_EditorInspectorPlugin_method__parse_begin:

.. rst-class:: classref-method

void **_parse_begin** **(** :ref:`Object<class_Object>` object **)** |virtual|

Called to allow adding controls at the beginning of the property list for ``object``.

.. rst-class:: classref-item-separator

----

.. _class_EditorInspectorPlugin_method__parse_category:

.. rst-class:: classref-method

void **_parse_category** **(** :ref:`Object<class_Object>` object, :ref:`String<class_String>` category **)** |virtual|

Called to allow adding controls at the beginning of a category in the property list for ``object``.

.. rst-class:: classref-item-separator

----

.. _class_EditorInspectorPlugin_method__parse_end:

.. rst-class:: classref-method

void **_parse_end** **(** :ref:`Object<class_Object>` object **)** |virtual|

Called to allow adding controls at the end of the property list for ``object``.

.. rst-class:: classref-item-separator

----

.. _class_EditorInspectorPlugin_method__parse_group:

.. rst-class:: classref-method

void **_parse_group** **(** :ref:`Object<class_Object>` object, :ref:`String<class_String>` group **)** |virtual|

Called to allow adding controls at the beginning of a group or a sub-group in the property list for ``object``.

.. rst-class:: classref-item-separator

----

.. _class_EditorInspectorPlugin_method__parse_property:

.. rst-class:: classref-method

:ref:`bool<class_bool>` **_parse_property** **(** :ref:`Object<class_Object>` object, :ref:`Variant.Type<enum_@GlobalScope_Variant.Type>` type, :ref:`String<class_String>` name, :ref:`PropertyHint<enum_@GlobalScope_PropertyHint>` hint_type, :ref:`String<class_String>` hint_string, :ref:`PropertyUsageFlags<enum_@GlobalScope_PropertyUsageFlags>` usage_flags, :ref:`bool<class_bool>` wide **)** |virtual|

Called to allow adding property-specific editors to the property list for ``object``. The added editor control must extend :ref:`EditorProperty<class_EditorProperty>`. Returning ``true`` removes the built-in editor for this property, otherwise allows to insert a custom editor before the built-in one.

.. rst-class:: classref-item-separator

----

.. _class_EditorInspectorPlugin_method_add_custom_control:

.. rst-class:: classref-method

void **add_custom_control** **(** :ref:`Control<class_Control>` control **)**

Adds a custom control, which is not necessarily a property editor.

.. rst-class:: classref-item-separator

----

.. _class_EditorInspectorPlugin_method_add_property_editor:

.. rst-class:: classref-method

void **add_property_editor** **(** :ref:`String<class_String>` property, :ref:`Control<class_Control>` editor, :ref:`bool<class_bool>` add_to_end=false **)**

Adds a property editor for an individual property. The ``editor`` control must extend :ref:`EditorProperty<class_EditorProperty>`.

.. rst-class:: classref-item-separator

----

.. _class_EditorInspectorPlugin_method_add_property_editor_for_multiple_properties:

.. rst-class:: classref-method

void **add_property_editor_for_multiple_properties** **(** :ref:`String<class_String>` label, :ref:`PackedStringArray<class_PackedStringArray>` properties, :ref:`Control<class_Control>` editor **)**

Adds an editor that allows modifying multiple properties. The ``editor`` control must extend :ref:`EditorProperty<class_EditorProperty>`.

.. |virtual| replace:: :abbr:`virtual (This method should typically be overridden by the user to have any effect.)`
.. |const| replace:: :abbr:`const (This method has no side effects. It doesn't modify any of the instance's member variables.)`
.. |vararg| replace:: :abbr:`vararg (This method accepts any number of arguments after the ones described here.)`
.. |constructor| replace:: :abbr:`constructor (This method is used to construct a type.)`
.. |static| replace:: :abbr:`static (This method doesn't need an instance to be called, so it can be called directly using the class name.)`
.. |operator| replace:: :abbr:`operator (This method describes a valid operator to use with this type as left-hand operand.)`
