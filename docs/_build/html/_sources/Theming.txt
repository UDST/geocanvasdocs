Theming
=======

**Theming is how you visualize data.**

In GeoCanvas, theming is done on a layer-by-layer basis. By theming a shape layer, you are determining how the shapes are colored or how tall they are when they are extruded into 3D volumes.

Each shape layer has a set of theming controls located directly below the :guilabel:`visibility limit` controls. The theme controls are separated out into two tabs: the **Fill** tab and the **Extrusion** tab.

To create a data visualization, you need to specify two main things: *the data source*, and *the aspect of the visualization that is controlled by that data.*

Accordingly, the **Fill** and **Extrusion** tabs each are split into two parts:

- Data Source (the top half)
- Theme Settings (the bottom half)

The :guilabel:`Data Source` section looks the same on both tabs. There are two things to choose in this section; the :guilabel:`Data Set` and the :guilabel:`Data Field`.

The :guilabel:`Data Set` is the original source of the data that you'd like to use to either color or extrude shapes. Some shape layers have built-in attributes - columns of data associated with shapes. These built-in attributes can be accessed by selecting "Indicators from this layer" in the :guilabel:`Data Set` drop down box. If you've added any additional attributes from files or database tables, you can select the name of the original file or table here.

Once the data is selected, you'll see that the :guilabel:`Data Field` drop down gets filled with a set of options that correspond to the numeric fields in the source data set.

The :guilabel:`Data Field` is the column of data (a.k.a. the "indicator" or "attribute") that you'll be visualizing on each shape.


Fill
----

Once you've selected a :guilabel:`Data Source` for Fill by choosing a :guilabel:`Data Set` and :guilabel:`Data Field` you specify how that gets translated into colors on shapes in the :guilabel:`Theme Settings` section. This section has three controls: :guilabel:`Colors`, :guilabel:`Intervals` and :guilabel:`Bins`.
 
.. image:: images/layercontrols-fill.png
   :scale: 50 %

Colors
~~~~~~

Select a color scheme for the visualization.

.. note:: Different color schemes provide different numbers of bins (explained below). Most of the schemes allow between 9 and 12 bins. Try different combinations of schemes and bins to see what works best for your data.


Intervals
~~~~~~~~~

- **Quantile**
- **Equal**
- **Custom**

TODO - Custom intervals dialog.

Bins
~~~~

TODO

Extrusion
---------

.. image:: images/layercontrols-extrusion.png
   :scale: 50 %

TODO - Fill and Extrusion data sources are independent.

TODO - Building footprint example.


Scale Factor
~~~~~~~~~~~~

If 3D extrusions are too short, try a lower value for units.

If 3D extrusions are too tall, try a higher value for units.

Typically experimenting by changing values by factors of ten gets you in the ballpark pretty quickly.
