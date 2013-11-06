Adding Attributes
=================


What are Attributes?
--------------------

**Attributes**, in the most general sense, are values associated with shapes. For example, if you have a set of shapes that represent states, each one might have a *population* attribution and a *land area* attribute. 

Sometimes attributes are also called *indicators* when they are calculated values, as opposed to measured values.

If you're familiar with databases, you might consider each shape as a record and an attribute as a field. Or, in spreadsheet terms, you might have a table of shapes, with each row representing one shape, and each column representing an attribute of that shape.

Attributes are often saved with shapes (as is the case with shapefiles.) GeoCanvas will automatically load attributes from shapefiles and database tables when you load shape layers that contain such data.

However, you may want to add additional attributes to a shape layer. To do so, follow the steps below.

Either:

1. Click on the name of a shape layer in the layer list to make it current. The name will turn blue. Note that you can't add attributes to base map layers, so clicking their names will have no effect.

2. Then, select :menuselection:`Add Attributes to Layer` from the :guilabel:`File` menu, and follow the instructions in the dialog box that appears.

**OR**

1. Click the arrow to the right of the layer to which you'd like to add attributes, and the layer controls for that layer will appear.

2. Click the |dataAdd| :guilabel:`Add Attributes` button on the right side of the dialog and follow the instructions in the dialog box that appears.


From File
---------

.. image:: images/AddAttributesToLayer-File.png
   :scale: 50 %

From Database
-------------

.. image:: images/AddAttributesToLayer-Database.png
   :scale: 50 %

.. |dataAdd| image:: images/dataAdd@2x.png
   :scale: 50 %