Layer Controls
==============

Current Layer
-------------

At any time, only one layer can be the :guilabel:`current layer` even though many layers may be visible. 

- The current layer is the shape layer to which new attributes are added when :menuselection:`Add Attributes to Layer` is selected from the File menu. 
- The current layer is also the selectable layer. Only shapes on the current layer can be selected with the selection tool.

Only shape layers can be made the current layer. So when GeoCanvas starts, there is no current layer, since there are only base map layers to start.

**To make a layer current, click its name in the layer panel.**

The name current layer will be shown in blue. All other layer names will be shown in black. (Clicking base map layer names has no effect.)


Visibility Toggle
-----------------

The control to the left of a layer's name in the layer panel is its :guilabel:`visibility toggle`. The :guilabel:`visibility toggle` indicates whether is layer is Off |layer_off|, 2D |layer_2d|, or 3D |layer_3d|.

- Base map layers can be Off |layer_off|, or 2D |layer_2d|. 
- Shape layers can be Off |layer_off|, 2D |layer_2d|, or 3D |layer_3d|.

**To switch between modes, click on the icon.**

.. note:: The :guilabel:`visibility limit` control (explained below) also determines the visibility of shape layers. If your layer is not appearing, first make sure it's in 2D or 3D mode, and then check it's visibility limit.

Expanded Controls
-----------------

Shows additional controls for each layer. Which controls are shown depends on the type of layer - that is, whether the layer is a base map layer or shape layer. There are also a common set of controls shown for all layers

Common Controls
---------------

|layerUp| Move Layer Up

|layerDown| Move Layer Down

Opacity


Base Map Layer Controls
-----------------------

Background Image
~~~~~~~~~~~~~~~~

.. image:: layercontrols-basemap.png
   :scale: 50 %


Shape Layer Controls
--------------------

Outline Visibility
~~~~~~~~~~~~~~~~~~

|outlineOn| This icon indicates outlines are shown. Click to hide.

|outlineOff| This icon indicates outlines are hidden. Click to show.

Delete Layer
~~~~~~~~~~~~

|layerDelete| Click to delete layer.

Visibility Limits
~~~~~~~~~~~~~~~~~

For details

Fill Controls:

.. image:: layercontrols-fill.png
   :scale: 50 %



Extrusion Controls
~~~~~~~~~~~~~~~~~~

.. image:: layercontrols-extrusion.png
   :scale: 50 %



.. |layerAdd| image:: layerAdd@2x.png
   :scale: 50 %

.. |layerDelete| image:: layerDelete@2x.png
   :scale: 50 %

.. |layerDown| image:: layerDown@2x.png
   :scale: 50 %

.. |layerUp| image:: layerUp@2x.png
   :scale: 50 %

.. |house| image:: house@2x.png
   :scale: 50 %

.. |globe| image:: globe@2x.png
   :scale: 50 %

.. |dataAdd| image:: dataAdd@2x.png
   :scale: 50 %

.. |dataDelete| image:: dataDelete@2x.png
   :scale: 50 %

.. |zoomExtents| image:: zoomextents@2x.png
   :scale: 50 %

.. |outlineOn| image:: outlineOn@2x.png
   :scale: 50 %

.. |outlineOff| image:: outlineOff@2x.png
   :scale: 50 %

.. |layer_off| image:: layer_off@2x.png
   :scale: 50 %

.. |layer_2d| image:: layer_2d@2x.png
   :scale: 50 %

.. |layer_3d| image:: layer_3d@2x.png
   :scale: 50 %



