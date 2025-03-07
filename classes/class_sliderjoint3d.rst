:github_url: hide

.. DO NOT EDIT THIS FILE!!!
.. Generated automatically from Godot engine sources.
.. Generator: https://github.com/godotengine/godot/tree/master/doc/tools/make_rst.py.
.. XML source: https://github.com/godotengine/godot/tree/master/doc/classes/SliderJoint3D.xml.

.. _class_SliderJoint3D:

SliderJoint3D
=============

**Inherits:** :ref:`Joint3D<class_Joint3D>` **<** :ref:`Node3D<class_Node3D>` **<** :ref:`Node<class_Node>` **<** :ref:`Object<class_Object>`

Slider between two PhysicsBodies in 3D.

.. rst-class:: classref-introduction-group

Description
-----------

Slides across the X axis of the pivot object. See also :ref:`Generic6DOFJoint3D<class_Generic6DOFJoint3D>`.

.. rst-class:: classref-reftable-group

Properties
----------

.. table::
   :widths: auto

   +---------------------------+----------------------------------------------------------------------------------------------+----------+
   | :ref:`float<class_float>` | :ref:`angular_limit/damping<class_SliderJoint3D_property_angular_limit/damping>`             | ``0.0``  |
   +---------------------------+----------------------------------------------------------------------------------------------+----------+
   | :ref:`float<class_float>` | :ref:`angular_limit/lower_angle<class_SliderJoint3D_property_angular_limit/lower_angle>`     | ``0.0``  |
   +---------------------------+----------------------------------------------------------------------------------------------+----------+
   | :ref:`float<class_float>` | :ref:`angular_limit/restitution<class_SliderJoint3D_property_angular_limit/restitution>`     | ``0.7``  |
   +---------------------------+----------------------------------------------------------------------------------------------+----------+
   | :ref:`float<class_float>` | :ref:`angular_limit/softness<class_SliderJoint3D_property_angular_limit/softness>`           | ``1.0``  |
   +---------------------------+----------------------------------------------------------------------------------------------+----------+
   | :ref:`float<class_float>` | :ref:`angular_limit/upper_angle<class_SliderJoint3D_property_angular_limit/upper_angle>`     | ``0.0``  |
   +---------------------------+----------------------------------------------------------------------------------------------+----------+
   | :ref:`float<class_float>` | :ref:`angular_motion/damping<class_SliderJoint3D_property_angular_motion/damping>`           | ``1.0``  |
   +---------------------------+----------------------------------------------------------------------------------------------+----------+
   | :ref:`float<class_float>` | :ref:`angular_motion/restitution<class_SliderJoint3D_property_angular_motion/restitution>`   | ``0.7``  |
   +---------------------------+----------------------------------------------------------------------------------------------+----------+
   | :ref:`float<class_float>` | :ref:`angular_motion/softness<class_SliderJoint3D_property_angular_motion/softness>`         | ``1.0``  |
   +---------------------------+----------------------------------------------------------------------------------------------+----------+
   | :ref:`float<class_float>` | :ref:`angular_ortho/damping<class_SliderJoint3D_property_angular_ortho/damping>`             | ``1.0``  |
   +---------------------------+----------------------------------------------------------------------------------------------+----------+
   | :ref:`float<class_float>` | :ref:`angular_ortho/restitution<class_SliderJoint3D_property_angular_ortho/restitution>`     | ``0.7``  |
   +---------------------------+----------------------------------------------------------------------------------------------+----------+
   | :ref:`float<class_float>` | :ref:`angular_ortho/softness<class_SliderJoint3D_property_angular_ortho/softness>`           | ``1.0``  |
   +---------------------------+----------------------------------------------------------------------------------------------+----------+
   | :ref:`float<class_float>` | :ref:`linear_limit/damping<class_SliderJoint3D_property_linear_limit/damping>`               | ``1.0``  |
   +---------------------------+----------------------------------------------------------------------------------------------+----------+
   | :ref:`float<class_float>` | :ref:`linear_limit/lower_distance<class_SliderJoint3D_property_linear_limit/lower_distance>` | ``-1.0`` |
   +---------------------------+----------------------------------------------------------------------------------------------+----------+
   | :ref:`float<class_float>` | :ref:`linear_limit/restitution<class_SliderJoint3D_property_linear_limit/restitution>`       | ``0.7``  |
   +---------------------------+----------------------------------------------------------------------------------------------+----------+
   | :ref:`float<class_float>` | :ref:`linear_limit/softness<class_SliderJoint3D_property_linear_limit/softness>`             | ``1.0``  |
   +---------------------------+----------------------------------------------------------------------------------------------+----------+
   | :ref:`float<class_float>` | :ref:`linear_limit/upper_distance<class_SliderJoint3D_property_linear_limit/upper_distance>` | ``1.0``  |
   +---------------------------+----------------------------------------------------------------------------------------------+----------+
   | :ref:`float<class_float>` | :ref:`linear_motion/damping<class_SliderJoint3D_property_linear_motion/damping>`             | ``0.0``  |
   +---------------------------+----------------------------------------------------------------------------------------------+----------+
   | :ref:`float<class_float>` | :ref:`linear_motion/restitution<class_SliderJoint3D_property_linear_motion/restitution>`     | ``0.7``  |
   +---------------------------+----------------------------------------------------------------------------------------------+----------+
   | :ref:`float<class_float>` | :ref:`linear_motion/softness<class_SliderJoint3D_property_linear_motion/softness>`           | ``1.0``  |
   +---------------------------+----------------------------------------------------------------------------------------------+----------+
   | :ref:`float<class_float>` | :ref:`linear_ortho/damping<class_SliderJoint3D_property_linear_ortho/damping>`               | ``1.0``  |
   +---------------------------+----------------------------------------------------------------------------------------------+----------+
   | :ref:`float<class_float>` | :ref:`linear_ortho/restitution<class_SliderJoint3D_property_linear_ortho/restitution>`       | ``0.7``  |
   +---------------------------+----------------------------------------------------------------------------------------------+----------+
   | :ref:`float<class_float>` | :ref:`linear_ortho/softness<class_SliderJoint3D_property_linear_ortho/softness>`             | ``1.0``  |
   +---------------------------+----------------------------------------------------------------------------------------------+----------+

.. rst-class:: classref-reftable-group

Methods
-------

.. table::
   :widths: auto

   +---------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------+
   | :ref:`float<class_float>` | :ref:`get_param<class_SliderJoint3D_method_get_param>` **(** :ref:`Param<enum_SliderJoint3D_Param>` param **)** |const|                          |
   +---------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------+
   | void                      | :ref:`set_param<class_SliderJoint3D_method_set_param>` **(** :ref:`Param<enum_SliderJoint3D_Param>` param, :ref:`float<class_float>` value **)** |
   +---------------------------+--------------------------------------------------------------------------------------------------------------------------------------------------+

.. rst-class:: classref-section-separator

----

.. rst-class:: classref-descriptions-group

Enumerations
------------

.. _enum_SliderJoint3D_Param:

.. rst-class:: classref-enumeration

enum **Param**:

.. _class_SliderJoint3D_constant_PARAM_LINEAR_LIMIT_UPPER:

.. rst-class:: classref-enumeration-constant

:ref:`Param<enum_SliderJoint3D_Param>` **PARAM_LINEAR_LIMIT_UPPER** = ``0``

The maximum difference between the pivot points on their X axis before damping happens.

.. _class_SliderJoint3D_constant_PARAM_LINEAR_LIMIT_LOWER:

.. rst-class:: classref-enumeration-constant

:ref:`Param<enum_SliderJoint3D_Param>` **PARAM_LINEAR_LIMIT_LOWER** = ``1``

The minimum difference between the pivot points on their X axis before damping happens.

.. _class_SliderJoint3D_constant_PARAM_LINEAR_LIMIT_SOFTNESS:

.. rst-class:: classref-enumeration-constant

:ref:`Param<enum_SliderJoint3D_Param>` **PARAM_LINEAR_LIMIT_SOFTNESS** = ``2``

A factor applied to the movement across the slider axis once the limits get surpassed. The lower, the slower the movement.

.. _class_SliderJoint3D_constant_PARAM_LINEAR_LIMIT_RESTITUTION:

.. rst-class:: classref-enumeration-constant

:ref:`Param<enum_SliderJoint3D_Param>` **PARAM_LINEAR_LIMIT_RESTITUTION** = ``3``

The amount of restitution once the limits are surpassed. The lower, the more velocityenergy gets lost.

.. _class_SliderJoint3D_constant_PARAM_LINEAR_LIMIT_DAMPING:

.. rst-class:: classref-enumeration-constant

:ref:`Param<enum_SliderJoint3D_Param>` **PARAM_LINEAR_LIMIT_DAMPING** = ``4``

The amount of damping once the slider limits are surpassed.

.. _class_SliderJoint3D_constant_PARAM_LINEAR_MOTION_SOFTNESS:

.. rst-class:: classref-enumeration-constant

:ref:`Param<enum_SliderJoint3D_Param>` **PARAM_LINEAR_MOTION_SOFTNESS** = ``5``

A factor applied to the movement across the slider axis as long as the slider is in the limits. The lower, the slower the movement.

.. _class_SliderJoint3D_constant_PARAM_LINEAR_MOTION_RESTITUTION:

.. rst-class:: classref-enumeration-constant

:ref:`Param<enum_SliderJoint3D_Param>` **PARAM_LINEAR_MOTION_RESTITUTION** = ``6``

The amount of restitution inside the slider limits.

.. _class_SliderJoint3D_constant_PARAM_LINEAR_MOTION_DAMPING:

.. rst-class:: classref-enumeration-constant

:ref:`Param<enum_SliderJoint3D_Param>` **PARAM_LINEAR_MOTION_DAMPING** = ``7``

The amount of damping inside the slider limits.

.. _class_SliderJoint3D_constant_PARAM_LINEAR_ORTHOGONAL_SOFTNESS:

.. rst-class:: classref-enumeration-constant

:ref:`Param<enum_SliderJoint3D_Param>` **PARAM_LINEAR_ORTHOGONAL_SOFTNESS** = ``8``

A factor applied to the movement across axes orthogonal to the slider.

.. _class_SliderJoint3D_constant_PARAM_LINEAR_ORTHOGONAL_RESTITUTION:

.. rst-class:: classref-enumeration-constant

:ref:`Param<enum_SliderJoint3D_Param>` **PARAM_LINEAR_ORTHOGONAL_RESTITUTION** = ``9``

The amount of restitution when movement is across axes orthogonal to the slider.

.. _class_SliderJoint3D_constant_PARAM_LINEAR_ORTHOGONAL_DAMPING:

.. rst-class:: classref-enumeration-constant

:ref:`Param<enum_SliderJoint3D_Param>` **PARAM_LINEAR_ORTHOGONAL_DAMPING** = ``10``

The amount of damping when movement is across axes orthogonal to the slider.

.. _class_SliderJoint3D_constant_PARAM_ANGULAR_LIMIT_UPPER:

.. rst-class:: classref-enumeration-constant

:ref:`Param<enum_SliderJoint3D_Param>` **PARAM_ANGULAR_LIMIT_UPPER** = ``11``

The upper limit of rotation in the slider.

.. _class_SliderJoint3D_constant_PARAM_ANGULAR_LIMIT_LOWER:

.. rst-class:: classref-enumeration-constant

:ref:`Param<enum_SliderJoint3D_Param>` **PARAM_ANGULAR_LIMIT_LOWER** = ``12``

The lower limit of rotation in the slider.

.. _class_SliderJoint3D_constant_PARAM_ANGULAR_LIMIT_SOFTNESS:

.. rst-class:: classref-enumeration-constant

:ref:`Param<enum_SliderJoint3D_Param>` **PARAM_ANGULAR_LIMIT_SOFTNESS** = ``13``

A factor applied to the all rotation once the limit is surpassed.

.. _class_SliderJoint3D_constant_PARAM_ANGULAR_LIMIT_RESTITUTION:

.. rst-class:: classref-enumeration-constant

:ref:`Param<enum_SliderJoint3D_Param>` **PARAM_ANGULAR_LIMIT_RESTITUTION** = ``14``

The amount of restitution of the rotation when the limit is surpassed.

.. _class_SliderJoint3D_constant_PARAM_ANGULAR_LIMIT_DAMPING:

.. rst-class:: classref-enumeration-constant

:ref:`Param<enum_SliderJoint3D_Param>` **PARAM_ANGULAR_LIMIT_DAMPING** = ``15``

The amount of damping of the rotation when the limit is surpassed.

.. _class_SliderJoint3D_constant_PARAM_ANGULAR_MOTION_SOFTNESS:

.. rst-class:: classref-enumeration-constant

:ref:`Param<enum_SliderJoint3D_Param>` **PARAM_ANGULAR_MOTION_SOFTNESS** = ``16``

A factor applied to the all rotation in the limits.

.. _class_SliderJoint3D_constant_PARAM_ANGULAR_MOTION_RESTITUTION:

.. rst-class:: classref-enumeration-constant

:ref:`Param<enum_SliderJoint3D_Param>` **PARAM_ANGULAR_MOTION_RESTITUTION** = ``17``

The amount of restitution of the rotation in the limits.

.. _class_SliderJoint3D_constant_PARAM_ANGULAR_MOTION_DAMPING:

.. rst-class:: classref-enumeration-constant

:ref:`Param<enum_SliderJoint3D_Param>` **PARAM_ANGULAR_MOTION_DAMPING** = ``18``

The amount of damping of the rotation in the limits.

.. _class_SliderJoint3D_constant_PARAM_ANGULAR_ORTHOGONAL_SOFTNESS:

.. rst-class:: classref-enumeration-constant

:ref:`Param<enum_SliderJoint3D_Param>` **PARAM_ANGULAR_ORTHOGONAL_SOFTNESS** = ``19``

A factor applied to the all rotation across axes orthogonal to the slider.

.. _class_SliderJoint3D_constant_PARAM_ANGULAR_ORTHOGONAL_RESTITUTION:

.. rst-class:: classref-enumeration-constant

:ref:`Param<enum_SliderJoint3D_Param>` **PARAM_ANGULAR_ORTHOGONAL_RESTITUTION** = ``20``

The amount of restitution of the rotation across axes orthogonal to the slider.

.. _class_SliderJoint3D_constant_PARAM_ANGULAR_ORTHOGONAL_DAMPING:

.. rst-class:: classref-enumeration-constant

:ref:`Param<enum_SliderJoint3D_Param>` **PARAM_ANGULAR_ORTHOGONAL_DAMPING** = ``21``

The amount of damping of the rotation across axes orthogonal to the slider.

.. _class_SliderJoint3D_constant_PARAM_MAX:

.. rst-class:: classref-enumeration-constant

:ref:`Param<enum_SliderJoint3D_Param>` **PARAM_MAX** = ``22``

Represents the size of the :ref:`Param<enum_SliderJoint3D_Param>` enum.

.. rst-class:: classref-section-separator

----

.. rst-class:: classref-descriptions-group

Property Descriptions
---------------------

.. _class_SliderJoint3D_property_angular_limit/damping:

.. rst-class:: classref-property

:ref:`float<class_float>` **angular_limit/damping** = ``0.0``

.. rst-class:: classref-property-setget

- void **set_param** **(** :ref:`Param<enum_SliderJoint3D_Param>` param, :ref:`float<class_float>` value **)**
- :ref:`float<class_float>` **get_param** **(** :ref:`Param<enum_SliderJoint3D_Param>` param **)** |const|

The amount of damping of the rotation when the limit is surpassed.

A lower damping value allows a rotation initiated by body A to travel to body B slower.

.. rst-class:: classref-item-separator

----

.. _class_SliderJoint3D_property_angular_limit/lower_angle:

.. rst-class:: classref-property

:ref:`float<class_float>` **angular_limit/lower_angle** = ``0.0``

.. rst-class:: classref-property-setget

- void **set_param** **(** :ref:`Param<enum_SliderJoint3D_Param>` param, :ref:`float<class_float>` value **)**
- :ref:`float<class_float>` **get_param** **(** :ref:`Param<enum_SliderJoint3D_Param>` param **)** |const|

The lower limit of rotation in the slider.

.. rst-class:: classref-item-separator

----

.. _class_SliderJoint3D_property_angular_limit/restitution:

.. rst-class:: classref-property

:ref:`float<class_float>` **angular_limit/restitution** = ``0.7``

.. rst-class:: classref-property-setget

- void **set_param** **(** :ref:`Param<enum_SliderJoint3D_Param>` param, :ref:`float<class_float>` value **)**
- :ref:`float<class_float>` **get_param** **(** :ref:`Param<enum_SliderJoint3D_Param>` param **)** |const|

The amount of restitution of the rotation when the limit is surpassed.

Does not affect damping.

.. rst-class:: classref-item-separator

----

.. _class_SliderJoint3D_property_angular_limit/softness:

.. rst-class:: classref-property

:ref:`float<class_float>` **angular_limit/softness** = ``1.0``

.. rst-class:: classref-property-setget

- void **set_param** **(** :ref:`Param<enum_SliderJoint3D_Param>` param, :ref:`float<class_float>` value **)**
- :ref:`float<class_float>` **get_param** **(** :ref:`Param<enum_SliderJoint3D_Param>` param **)** |const|

A factor applied to the all rotation once the limit is surpassed.

Makes all rotation slower when between 0 and 1.

.. rst-class:: classref-item-separator

----

.. _class_SliderJoint3D_property_angular_limit/upper_angle:

.. rst-class:: classref-property

:ref:`float<class_float>` **angular_limit/upper_angle** = ``0.0``

.. rst-class:: classref-property-setget

- void **set_param** **(** :ref:`Param<enum_SliderJoint3D_Param>` param, :ref:`float<class_float>` value **)**
- :ref:`float<class_float>` **get_param** **(** :ref:`Param<enum_SliderJoint3D_Param>` param **)** |const|

The upper limit of rotation in the slider.

.. rst-class:: classref-item-separator

----

.. _class_SliderJoint3D_property_angular_motion/damping:

.. rst-class:: classref-property

:ref:`float<class_float>` **angular_motion/damping** = ``1.0``

.. rst-class:: classref-property-setget

- void **set_param** **(** :ref:`Param<enum_SliderJoint3D_Param>` param, :ref:`float<class_float>` value **)**
- :ref:`float<class_float>` **get_param** **(** :ref:`Param<enum_SliderJoint3D_Param>` param **)** |const|

The amount of damping of the rotation in the limits.

.. rst-class:: classref-item-separator

----

.. _class_SliderJoint3D_property_angular_motion/restitution:

.. rst-class:: classref-property

:ref:`float<class_float>` **angular_motion/restitution** = ``0.7``

.. rst-class:: classref-property-setget

- void **set_param** **(** :ref:`Param<enum_SliderJoint3D_Param>` param, :ref:`float<class_float>` value **)**
- :ref:`float<class_float>` **get_param** **(** :ref:`Param<enum_SliderJoint3D_Param>` param **)** |const|

The amount of restitution of the rotation in the limits.

.. rst-class:: classref-item-separator

----

.. _class_SliderJoint3D_property_angular_motion/softness:

.. rst-class:: classref-property

:ref:`float<class_float>` **angular_motion/softness** = ``1.0``

.. rst-class:: classref-property-setget

- void **set_param** **(** :ref:`Param<enum_SliderJoint3D_Param>` param, :ref:`float<class_float>` value **)**
- :ref:`float<class_float>` **get_param** **(** :ref:`Param<enum_SliderJoint3D_Param>` param **)** |const|

A factor applied to the all rotation in the limits.

.. rst-class:: classref-item-separator

----

.. _class_SliderJoint3D_property_angular_ortho/damping:

.. rst-class:: classref-property

:ref:`float<class_float>` **angular_ortho/damping** = ``1.0``

.. rst-class:: classref-property-setget

- void **set_param** **(** :ref:`Param<enum_SliderJoint3D_Param>` param, :ref:`float<class_float>` value **)**
- :ref:`float<class_float>` **get_param** **(** :ref:`Param<enum_SliderJoint3D_Param>` param **)** |const|

The amount of damping of the rotation across axes orthogonal to the slider.

.. rst-class:: classref-item-separator

----

.. _class_SliderJoint3D_property_angular_ortho/restitution:

.. rst-class:: classref-property

:ref:`float<class_float>` **angular_ortho/restitution** = ``0.7``

.. rst-class:: classref-property-setget

- void **set_param** **(** :ref:`Param<enum_SliderJoint3D_Param>` param, :ref:`float<class_float>` value **)**
- :ref:`float<class_float>` **get_param** **(** :ref:`Param<enum_SliderJoint3D_Param>` param **)** |const|

The amount of restitution of the rotation across axes orthogonal to the slider.

.. rst-class:: classref-item-separator

----

.. _class_SliderJoint3D_property_angular_ortho/softness:

.. rst-class:: classref-property

:ref:`float<class_float>` **angular_ortho/softness** = ``1.0``

.. rst-class:: classref-property-setget

- void **set_param** **(** :ref:`Param<enum_SliderJoint3D_Param>` param, :ref:`float<class_float>` value **)**
- :ref:`float<class_float>` **get_param** **(** :ref:`Param<enum_SliderJoint3D_Param>` param **)** |const|

A factor applied to the all rotation across axes orthogonal to the slider.

.. rst-class:: classref-item-separator

----

.. _class_SliderJoint3D_property_linear_limit/damping:

.. rst-class:: classref-property

:ref:`float<class_float>` **linear_limit/damping** = ``1.0``

.. rst-class:: classref-property-setget

- void **set_param** **(** :ref:`Param<enum_SliderJoint3D_Param>` param, :ref:`float<class_float>` value **)**
- :ref:`float<class_float>` **get_param** **(** :ref:`Param<enum_SliderJoint3D_Param>` param **)** |const|

The amount of damping that happens once the limit defined by :ref:`linear_limit/lower_distance<class_SliderJoint3D_property_linear_limit/lower_distance>` and :ref:`linear_limit/upper_distance<class_SliderJoint3D_property_linear_limit/upper_distance>` is surpassed.

.. rst-class:: classref-item-separator

----

.. _class_SliderJoint3D_property_linear_limit/lower_distance:

.. rst-class:: classref-property

:ref:`float<class_float>` **linear_limit/lower_distance** = ``-1.0``

.. rst-class:: classref-property-setget

- void **set_param** **(** :ref:`Param<enum_SliderJoint3D_Param>` param, :ref:`float<class_float>` value **)**
- :ref:`float<class_float>` **get_param** **(** :ref:`Param<enum_SliderJoint3D_Param>` param **)** |const|

The minimum difference between the pivot points on their X axis before damping happens.

.. rst-class:: classref-item-separator

----

.. _class_SliderJoint3D_property_linear_limit/restitution:

.. rst-class:: classref-property

:ref:`float<class_float>` **linear_limit/restitution** = ``0.7``

.. rst-class:: classref-property-setget

- void **set_param** **(** :ref:`Param<enum_SliderJoint3D_Param>` param, :ref:`float<class_float>` value **)**
- :ref:`float<class_float>` **get_param** **(** :ref:`Param<enum_SliderJoint3D_Param>` param **)** |const|

The amount of restitution once the limits are surpassed. The lower, the more velocity-energy gets lost.

.. rst-class:: classref-item-separator

----

.. _class_SliderJoint3D_property_linear_limit/softness:

.. rst-class:: classref-property

:ref:`float<class_float>` **linear_limit/softness** = ``1.0``

.. rst-class:: classref-property-setget

- void **set_param** **(** :ref:`Param<enum_SliderJoint3D_Param>` param, :ref:`float<class_float>` value **)**
- :ref:`float<class_float>` **get_param** **(** :ref:`Param<enum_SliderJoint3D_Param>` param **)** |const|

A factor applied to the movement across the slider axis once the limits get surpassed. The lower, the slower the movement.

.. rst-class:: classref-item-separator

----

.. _class_SliderJoint3D_property_linear_limit/upper_distance:

.. rst-class:: classref-property

:ref:`float<class_float>` **linear_limit/upper_distance** = ``1.0``

.. rst-class:: classref-property-setget

- void **set_param** **(** :ref:`Param<enum_SliderJoint3D_Param>` param, :ref:`float<class_float>` value **)**
- :ref:`float<class_float>` **get_param** **(** :ref:`Param<enum_SliderJoint3D_Param>` param **)** |const|

The maximum difference between the pivot points on their X axis before damping happens.

.. rst-class:: classref-item-separator

----

.. _class_SliderJoint3D_property_linear_motion/damping:

.. rst-class:: classref-property

:ref:`float<class_float>` **linear_motion/damping** = ``0.0``

.. rst-class:: classref-property-setget

- void **set_param** **(** :ref:`Param<enum_SliderJoint3D_Param>` param, :ref:`float<class_float>` value **)**
- :ref:`float<class_float>` **get_param** **(** :ref:`Param<enum_SliderJoint3D_Param>` param **)** |const|

The amount of damping inside the slider limits.

.. rst-class:: classref-item-separator

----

.. _class_SliderJoint3D_property_linear_motion/restitution:

.. rst-class:: classref-property

:ref:`float<class_float>` **linear_motion/restitution** = ``0.7``

.. rst-class:: classref-property-setget

- void **set_param** **(** :ref:`Param<enum_SliderJoint3D_Param>` param, :ref:`float<class_float>` value **)**
- :ref:`float<class_float>` **get_param** **(** :ref:`Param<enum_SliderJoint3D_Param>` param **)** |const|

The amount of restitution inside the slider limits.

.. rst-class:: classref-item-separator

----

.. _class_SliderJoint3D_property_linear_motion/softness:

.. rst-class:: classref-property

:ref:`float<class_float>` **linear_motion/softness** = ``1.0``

.. rst-class:: classref-property-setget

- void **set_param** **(** :ref:`Param<enum_SliderJoint3D_Param>` param, :ref:`float<class_float>` value **)**
- :ref:`float<class_float>` **get_param** **(** :ref:`Param<enum_SliderJoint3D_Param>` param **)** |const|

A factor applied to the movement across the slider axis as long as the slider is in the limits. The lower, the slower the movement.

.. rst-class:: classref-item-separator

----

.. _class_SliderJoint3D_property_linear_ortho/damping:

.. rst-class:: classref-property

:ref:`float<class_float>` **linear_ortho/damping** = ``1.0``

.. rst-class:: classref-property-setget

- void **set_param** **(** :ref:`Param<enum_SliderJoint3D_Param>` param, :ref:`float<class_float>` value **)**
- :ref:`float<class_float>` **get_param** **(** :ref:`Param<enum_SliderJoint3D_Param>` param **)** |const|

The amount of damping when movement is across axes orthogonal to the slider.

.. rst-class:: classref-item-separator

----

.. _class_SliderJoint3D_property_linear_ortho/restitution:

.. rst-class:: classref-property

:ref:`float<class_float>` **linear_ortho/restitution** = ``0.7``

.. rst-class:: classref-property-setget

- void **set_param** **(** :ref:`Param<enum_SliderJoint3D_Param>` param, :ref:`float<class_float>` value **)**
- :ref:`float<class_float>` **get_param** **(** :ref:`Param<enum_SliderJoint3D_Param>` param **)** |const|

The amount of restitution when movement is across axes orthogonal to the slider.

.. rst-class:: classref-item-separator

----

.. _class_SliderJoint3D_property_linear_ortho/softness:

.. rst-class:: classref-property

:ref:`float<class_float>` **linear_ortho/softness** = ``1.0``

.. rst-class:: classref-property-setget

- void **set_param** **(** :ref:`Param<enum_SliderJoint3D_Param>` param, :ref:`float<class_float>` value **)**
- :ref:`float<class_float>` **get_param** **(** :ref:`Param<enum_SliderJoint3D_Param>` param **)** |const|

A factor applied to the movement across axes orthogonal to the slider.

.. rst-class:: classref-section-separator

----

.. rst-class:: classref-descriptions-group

Method Descriptions
-------------------

.. _class_SliderJoint3D_method_get_param:

.. rst-class:: classref-method

:ref:`float<class_float>` **get_param** **(** :ref:`Param<enum_SliderJoint3D_Param>` param **)** |const|

.. container:: contribute

	There is currently no description for this method. Please help us by :ref:`contributing one <doc_updating_the_class_reference>`!

.. rst-class:: classref-item-separator

----

.. _class_SliderJoint3D_method_set_param:

.. rst-class:: classref-method

void **set_param** **(** :ref:`Param<enum_SliderJoint3D_Param>` param, :ref:`float<class_float>` value **)**

.. container:: contribute

	There is currently no description for this method. Please help us by :ref:`contributing one <doc_updating_the_class_reference>`!

.. |virtual| replace:: :abbr:`virtual (This method should typically be overridden by the user to have any effect.)`
.. |const| replace:: :abbr:`const (This method has no side effects. It doesn't modify any of the instance's member variables.)`
.. |vararg| replace:: :abbr:`vararg (This method accepts any number of arguments after the ones described here.)`
.. |constructor| replace:: :abbr:`constructor (This method is used to construct a type.)`
.. |static| replace:: :abbr:`static (This method doesn't need an instance to be called, so it can be called directly using the class name.)`
.. |operator| replace:: :abbr:`operator (This method describes a valid operator to use with this type as left-hand operand.)`
