:github_url: hide

.. Generated automatically by doc/tools/makerst.py in Godot's source tree.
.. DO NOT EDIT THIS FILE, but the Camera.xml source instead.
.. The source is found in doc/classes or modules/<name>/doc_classes.

.. _class_Camera:

Camera
======

**Inherits:** :ref:`Spatial<class_Spatial>` **<** :ref:`Node<class_Node>` **<** :ref:`Object<class_Object>`

**Inherited By:** :ref:`ARVRCamera<class_ARVRCamera>`, :ref:`ClippedCamera<class_ClippedCamera>`, :ref:`InterpolatedCamera<class_InterpolatedCamera>`

**Category:** Core

Brief Description
-----------------

Camera node, displays from a point of view.

Properties
----------

+-----------------------------------------------------+-----------------------------------------------------------------+-----------------+
| :ref:`int<class_int>`                               | :ref:`cull_mask<class_Camera_property_cull_mask>`               | 1048575         |
+-----------------------------------------------------+-----------------------------------------------------------------+-----------------+
| :ref:`bool<class_bool>`                             | :ref:`current<class_Camera_property_current>`                   | false           |
+-----------------------------------------------------+-----------------------------------------------------------------+-----------------+
| :ref:`DopplerTracking<enum_Camera_DopplerTracking>` | :ref:`doppler_tracking<class_Camera_property_doppler_tracking>` | 0               |
+-----------------------------------------------------+-----------------------------------------------------------------+-----------------+
| :ref:`Environment<class_Environment>`               | :ref:`environment<class_Camera_property_environment>`           |                 |
+-----------------------------------------------------+-----------------------------------------------------------------+-----------------+
| :ref:`float<class_float>`                           | :ref:`far<class_Camera_property_far>`                           | 100.0           |
+-----------------------------------------------------+-----------------------------------------------------------------+-----------------+
| :ref:`float<class_float>`                           | :ref:`fov<class_Camera_property_fov>`                           | 70.0            |
+-----------------------------------------------------+-----------------------------------------------------------------+-----------------+
| :ref:`Vector2<class_Vector2>`                       | :ref:`frustum_offset<class_Camera_property_frustum_offset>`     | Vector2( 0, 0 ) |
+-----------------------------------------------------+-----------------------------------------------------------------+-----------------+
| :ref:`float<class_float>`                           | :ref:`h_offset<class_Camera_property_h_offset>`                 | 0.0             |
+-----------------------------------------------------+-----------------------------------------------------------------+-----------------+
| :ref:`KeepAspect<enum_Camera_KeepAspect>`           | :ref:`keep_aspect<class_Camera_property_keep_aspect>`           | 1               |
+-----------------------------------------------------+-----------------------------------------------------------------+-----------------+
| :ref:`float<class_float>`                           | :ref:`near<class_Camera_property_near>`                         | 0.05            |
+-----------------------------------------------------+-----------------------------------------------------------------+-----------------+
| :ref:`Projection<enum_Camera_Projection>`           | :ref:`projection<class_Camera_property_projection>`             | 0               |
+-----------------------------------------------------+-----------------------------------------------------------------+-----------------+
| :ref:`float<class_float>`                           | :ref:`size<class_Camera_property_size>`                         | 1.0             |
+-----------------------------------------------------+-----------------------------------------------------------------+-----------------+
| :ref:`float<class_float>`                           | :ref:`v_offset<class_Camera_property_v_offset>`                 | 0.0             |
+-----------------------------------------------------+-----------------------------------------------------------------+-----------------+

Methods
-------

+-----------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| void                              | :ref:`clear_current<class_Camera_method_clear_current>` **(** :ref:`bool<class_bool>` enable_next=true **)**                                                                                            |
+-----------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`RID<class_RID>`             | :ref:`get_camera_rid<class_Camera_method_get_camera_rid>` **(** **)** const                                                                                                                             |
+-----------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Transform<class_Transform>` | :ref:`get_camera_transform<class_Camera_method_get_camera_transform>` **(** **)** const                                                                                                                 |
+-----------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`bool<class_bool>`           | :ref:`get_cull_mask_bit<class_Camera_method_get_cull_mask_bit>` **(** :ref:`int<class_int>` layer **)** const                                                                                           |
+-----------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Array<class_Array>`         | :ref:`get_frustum<class_Camera_method_get_frustum>` **(** **)** const                                                                                                                                   |
+-----------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`bool<class_bool>`           | :ref:`is_position_behind<class_Camera_method_is_position_behind>` **(** :ref:`Vector3<class_Vector3>` world_point **)** const                                                                           |
+-----------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| void                              | :ref:`make_current<class_Camera_method_make_current>` **(** **)**                                                                                                                                       |
+-----------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Vector3<class_Vector3>`     | :ref:`project_local_ray_normal<class_Camera_method_project_local_ray_normal>` **(** :ref:`Vector2<class_Vector2>` screen_point **)** const                                                              |
+-----------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Vector3<class_Vector3>`     | :ref:`project_position<class_Camera_method_project_position>` **(** :ref:`Vector2<class_Vector2>` screen_point, :ref:`float<class_float>` z_depth **)** const                                           |
+-----------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Vector3<class_Vector3>`     | :ref:`project_ray_normal<class_Camera_method_project_ray_normal>` **(** :ref:`Vector2<class_Vector2>` screen_point **)** const                                                                          |
+-----------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Vector3<class_Vector3>`     | :ref:`project_ray_origin<class_Camera_method_project_ray_origin>` **(** :ref:`Vector2<class_Vector2>` screen_point **)** const                                                                          |
+-----------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| void                              | :ref:`set_cull_mask_bit<class_Camera_method_set_cull_mask_bit>` **(** :ref:`int<class_int>` layer, :ref:`bool<class_bool>` enable **)**                                                                 |
+-----------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| void                              | :ref:`set_frustum<class_Camera_method_set_frustum>` **(** :ref:`float<class_float>` size, :ref:`Vector2<class_Vector2>` offset, :ref:`float<class_float>` z_near, :ref:`float<class_float>` z_far **)** |
+-----------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| void                              | :ref:`set_orthogonal<class_Camera_method_set_orthogonal>` **(** :ref:`float<class_float>` size, :ref:`float<class_float>` z_near, :ref:`float<class_float>` z_far **)**                                 |
+-----------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| void                              | :ref:`set_perspective<class_Camera_method_set_perspective>` **(** :ref:`float<class_float>` fov, :ref:`float<class_float>` z_near, :ref:`float<class_float>` z_far **)**                                |
+-----------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Vector2<class_Vector2>`     | :ref:`unproject_position<class_Camera_method_unproject_position>` **(** :ref:`Vector3<class_Vector3>` world_point **)** const                                                                           |
+-----------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+

Enumerations
------------

.. _enum_Camera_Projection:

.. _class_Camera_constant_PROJECTION_PERSPECTIVE:

.. _class_Camera_constant_PROJECTION_ORTHOGONAL:

.. _class_Camera_constant_PROJECTION_FRUSTUM:

enum **Projection**:

- **PROJECTION_PERSPECTIVE** = **0** --- Perspective projection. Objects on the screen becomes smaller when they are far away.

- **PROJECTION_ORTHOGONAL** = **1** --- Orthogonal projection, also known as orthographic projection. Objects remain the same size on the screen no matter how far away they are.

- **PROJECTION_FRUSTUM** = **2** --- Frustum projection. This mode allows adjusting :ref:`frustum_offset<class_Camera_property_frustum_offset>` to create "tilted frustum" effects.

----

.. _enum_Camera_KeepAspect:

.. _class_Camera_constant_KEEP_WIDTH:

.. _class_Camera_constant_KEEP_HEIGHT:

enum **KeepAspect**:

- **KEEP_WIDTH** = **0** --- Preserves the horizontal aspect ratio; also known as Vert- scaling. This is usually the best option for projects running in portrait mode, as taller aspect ratios will benefit from a wider vertical FOV.

- **KEEP_HEIGHT** = **1** --- Preserves the vertical aspect ratio; also known as Hor+ scaling. This is usually the best option for projects running in landscape mode, as wider aspect ratios will automatically benefit from a wider horizontal FOV.

----

.. _enum_Camera_DopplerTracking:

.. _class_Camera_constant_DOPPLER_TRACKING_DISABLED:

.. _class_Camera_constant_DOPPLER_TRACKING_IDLE_STEP:

.. _class_Camera_constant_DOPPLER_TRACKING_PHYSICS_STEP:

enum **DopplerTracking**:

- **DOPPLER_TRACKING_DISABLED** = **0** --- Disables Doppler effect simulation (default).

- **DOPPLER_TRACKING_IDLE_STEP** = **1** --- Simulate Doppler effect by tracking positions of objects that are changed in ``_process``. Changes in the relative velocity of this camera compared to those objects affect how Audio is perceived (changing the Audio's ``pitch shift``).

- **DOPPLER_TRACKING_PHYSICS_STEP** = **2** --- Simulate Doppler effect by tracking positions of objects that are changed in ``_physics_process``. Changes in the relative velocity of this camera compared to those objects affect how Audio is perceived (changing the Audio's ``pitch shift``).

Description
-----------

Camera is a special node that displays what is visible from its current location. Cameras register themselves in the nearest :ref:`Viewport<class_Viewport>` node (when ascending the tree). Only one camera can be active per viewport. If no viewport is available ascending the tree, the camera will register in the global viewport. In other words, a camera just provides 3D display capabilities to a :ref:`Viewport<class_Viewport>`, and, without one, a scene registered in that :ref:`Viewport<class_Viewport>` (or higher viewports) can't be displayed.

Property Descriptions
---------------------

.. _class_Camera_property_cull_mask:

- :ref:`int<class_int>` **cull_mask**

+-----------+----------------------+
| *Default* | 1048575              |
+-----------+----------------------+
| *Setter*  | set_cull_mask(value) |
+-----------+----------------------+
| *Getter*  | get_cull_mask()      |
+-----------+----------------------+

The culling mask that describes which 3D render layers are rendered by this camera.

----

.. _class_Camera_property_current:

- :ref:`bool<class_bool>` **current**

+-----------+--------------------+
| *Default* | false              |
+-----------+--------------------+
| *Setter*  | set_current(value) |
+-----------+--------------------+
| *Getter*  | is_current()       |
+-----------+--------------------+

If ``true``, the ancestor :ref:`Viewport<class_Viewport>` is currently using this camera.

----

.. _class_Camera_property_doppler_tracking:

- :ref:`DopplerTracking<enum_Camera_DopplerTracking>` **doppler_tracking**

+-----------+-----------------------------+
| *Default* | 0                           |
+-----------+-----------------------------+
| *Setter*  | set_doppler_tracking(value) |
+-----------+-----------------------------+
| *Getter*  | get_doppler_tracking()      |
+-----------+-----------------------------+

If not :ref:`DOPPLER_TRACKING_DISABLED<class_Camera_constant_DOPPLER_TRACKING_DISABLED>`, this camera will simulate the Doppler effect for objects changed in particular ``_process`` methods. See :ref:`DopplerTracking<enum_Camera_DopplerTracking>` for possible values.

----

.. _class_Camera_property_environment:

- :ref:`Environment<class_Environment>` **environment**

+----------+------------------------+
| *Setter* | set_environment(value) |
+----------+------------------------+
| *Getter* | get_environment()      |
+----------+------------------------+

The :ref:`Environment<class_Environment>` to use for this camera.

----

.. _class_Camera_property_far:

- :ref:`float<class_float>` **far**

+-----------+-----------------+
| *Default* | 100.0           |
+-----------+-----------------+
| *Setter*  | set_zfar(value) |
+-----------+-----------------+
| *Getter*  | get_zfar()      |
+-----------+-----------------+

The distance to the far culling boundary for this camera relative to its local Z axis.

----

.. _class_Camera_property_fov:

- :ref:`float<class_float>` **fov**

+-----------+----------------+
| *Default* | 70.0           |
+-----------+----------------+
| *Setter*  | set_fov(value) |
+-----------+----------------+
| *Getter*  | get_fov()      |
+-----------+----------------+

The camera's field of view angle (in degrees). Only applicable in perspective mode. Since :ref:`keep_aspect<class_Camera_property_keep_aspect>` locks one axis, ``fov`` sets the other axis' field of view angle.

----

.. _class_Camera_property_frustum_offset:

- :ref:`Vector2<class_Vector2>` **frustum_offset**

+-----------+---------------------------+
| *Default* | Vector2( 0, 0 )           |
+-----------+---------------------------+
| *Setter*  | set_frustum_offset(value) |
+-----------+---------------------------+
| *Getter*  | get_frustum_offset()      |
+-----------+---------------------------+

----

.. _class_Camera_property_h_offset:

- :ref:`float<class_float>` **h_offset**

+-----------+---------------------+
| *Default* | 0.0                 |
+-----------+---------------------+
| *Setter*  | set_h_offset(value) |
+-----------+---------------------+
| *Getter*  | get_h_offset()      |
+-----------+---------------------+

The horizontal (X) offset of the camera viewport.

----

.. _class_Camera_property_keep_aspect:

- :ref:`KeepAspect<enum_Camera_KeepAspect>` **keep_aspect**

+-----------+-----------------------------+
| *Default* | 1                           |
+-----------+-----------------------------+
| *Setter*  | set_keep_aspect_mode(value) |
+-----------+-----------------------------+
| *Getter*  | get_keep_aspect_mode()      |
+-----------+-----------------------------+

The axis to lock during :ref:`fov<class_Camera_property_fov>`/:ref:`size<class_Camera_property_size>` adjustments. Can be either :ref:`KEEP_WIDTH<class_Camera_constant_KEEP_WIDTH>` or :ref:`KEEP_HEIGHT<class_Camera_constant_KEEP_HEIGHT>`.

----

.. _class_Camera_property_near:

- :ref:`float<class_float>` **near**

+-----------+------------------+
| *Default* | 0.05             |
+-----------+------------------+
| *Setter*  | set_znear(value) |
+-----------+------------------+
| *Getter*  | get_znear()      |
+-----------+------------------+

The distance to the near culling boundary for this camera relative to its local Z axis.

----

.. _class_Camera_property_projection:

- :ref:`Projection<enum_Camera_Projection>` **projection**

+-----------+-----------------------+
| *Default* | 0                     |
+-----------+-----------------------+
| *Setter*  | set_projection(value) |
+-----------+-----------------------+
| *Getter*  | get_projection()      |
+-----------+-----------------------+

The camera's projection mode. In :ref:`PROJECTION_PERSPECTIVE<class_Camera_constant_PROJECTION_PERSPECTIVE>` mode, objects' Z distance from the camera's local space scales their perceived size.

----

.. _class_Camera_property_size:

- :ref:`float<class_float>` **size**

+-----------+-----------------+
| *Default* | 1.0             |
+-----------+-----------------+
| *Setter*  | set_size(value) |
+-----------+-----------------+
| *Getter*  | get_size()      |
+-----------+-----------------+

The camera's size measured as 1/2 the width or height. Only applicable in orthogonal mode. Since :ref:`keep_aspect<class_Camera_property_keep_aspect>` locks on axis, ``size`` sets the other axis' size length.

----

.. _class_Camera_property_v_offset:

- :ref:`float<class_float>` **v_offset**

+-----------+---------------------+
| *Default* | 0.0                 |
+-----------+---------------------+
| *Setter*  | set_v_offset(value) |
+-----------+---------------------+
| *Getter*  | get_v_offset()      |
+-----------+---------------------+

The vertical (Y) offset of the camera viewport.

Method Descriptions
-------------------

.. _class_Camera_method_clear_current:

- void **clear_current** **(** :ref:`bool<class_bool>` enable_next=true **)**

If this is the current camera, remove it from being current. If ``enable_next`` is ``true``, request to make the next camera current, if any.

----

.. _class_Camera_method_get_camera_rid:

- :ref:`RID<class_RID>` **get_camera_rid** **(** **)** const

Returns the camera's RID from the :ref:`VisualServer<class_VisualServer>`.

----

.. _class_Camera_method_get_camera_transform:

- :ref:`Transform<class_Transform>` **get_camera_transform** **(** **)** const

Gets the camera transform. Subclassed cameras such as :ref:`InterpolatedCamera<class_InterpolatedCamera>` may provide different transforms than the :ref:`Node<class_Node>` transform.

----

.. _class_Camera_method_get_cull_mask_bit:

- :ref:`bool<class_bool>` **get_cull_mask_bit** **(** :ref:`int<class_int>` layer **)** const

----

.. _class_Camera_method_get_frustum:

- :ref:`Array<class_Array>` **get_frustum** **(** **)** const

----

.. _class_Camera_method_is_position_behind:

- :ref:`bool<class_bool>` **is_position_behind** **(** :ref:`Vector3<class_Vector3>` world_point **)** const

Returns ``true`` if the given position is behind the camera.

**Note:** A position which returns ``false`` may still be outside the camera's field of view.

----

.. _class_Camera_method_make_current:

- void **make_current** **(** **)**

Makes this camera the current camera for the :ref:`Viewport<class_Viewport>` (see class description). If the camera node is outside the scene tree, it will attempt to become current once it's added.

----

.. _class_Camera_method_project_local_ray_normal:

- :ref:`Vector3<class_Vector3>` **project_local_ray_normal** **(** :ref:`Vector2<class_Vector2>` screen_point **)** const

Returns a normal vector from the screen point location directed along the camera. Orthogonal cameras are normalized. Perspective cameras account for perspective, screen width/height, etc.

----

.. _class_Camera_method_project_position:

- :ref:`Vector3<class_Vector3>` **project_position** **(** :ref:`Vector2<class_Vector2>` screen_point, :ref:`float<class_float>` z_depth **)** const

Returns the 3D point in worldspace that maps to the given 2D coordinate in the :ref:`Viewport<class_Viewport>` rectangle on a plane that is the given ``z_depth`` distance into the scene away from the camera.

----

.. _class_Camera_method_project_ray_normal:

- :ref:`Vector3<class_Vector3>` **project_ray_normal** **(** :ref:`Vector2<class_Vector2>` screen_point **)** const

Returns a normal vector in worldspace, that is the result of projecting a point on the :ref:`Viewport<class_Viewport>` rectangle by the camera projection. This is useful for casting rays in the form of (origin, normal) for object intersection or picking.

----

.. _class_Camera_method_project_ray_origin:

- :ref:`Vector3<class_Vector3>` **project_ray_origin** **(** :ref:`Vector2<class_Vector2>` screen_point **)** const

Returns a 3D position in worldspace, that is the result of projecting a point on the :ref:`Viewport<class_Viewport>` rectangle by the camera projection. This is useful for casting rays in the form of (origin, normal) for object intersection or picking.

----

.. _class_Camera_method_set_cull_mask_bit:

- void **set_cull_mask_bit** **(** :ref:`int<class_int>` layer, :ref:`bool<class_bool>` enable **)**

----

.. _class_Camera_method_set_frustum:

- void **set_frustum** **(** :ref:`float<class_float>` size, :ref:`Vector2<class_Vector2>` offset, :ref:`float<class_float>` z_near, :ref:`float<class_float>` z_far **)**

----

.. _class_Camera_method_set_orthogonal:

- void **set_orthogonal** **(** :ref:`float<class_float>` size, :ref:`float<class_float>` z_near, :ref:`float<class_float>` z_far **)**

Sets the camera projection to orthogonal mode, by specifying a width and the ``near`` and ``far`` clip planes in worldspace units. (As a hint, 2D games often use this projection, with values specified in pixels)

----

.. _class_Camera_method_set_perspective:

- void **set_perspective** **(** :ref:`float<class_float>` fov, :ref:`float<class_float>` z_near, :ref:`float<class_float>` z_far **)**

Sets the camera projection to perspective mode, by specifying a ``fov`` angle in degrees (FOV means Field of View), and the ``near`` and ``far`` clip planes in world-space units.

----

.. _class_Camera_method_unproject_position:

- :ref:`Vector2<class_Vector2>` **unproject_position** **(** :ref:`Vector3<class_Vector3>` world_point **)** const

Returns the 2D coordinate in the :ref:`Viewport<class_Viewport>` rectangle that maps to the given 3D point in worldspace.

