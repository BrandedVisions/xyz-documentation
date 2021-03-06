**[HERE XYZ Studio](https://xyz.here.com/studio)** is an interactive, visual, web-based application for accessing XYZ Hub data and creating maps within minutes - without any code.

Just go to - **[`https://xyz.here.com/studio`](https://xyz.here.com/studio)** - and log in.

## Dashboard

When you first open the application, you will start at the dashboard, where you can see all of the maps you have created. It is empty when you first get started, but it will fill up as soon as you begin creating projects.

[![Dashboard](../assets/images/studio-dashboard2.png)](../assets/images/studio-dashboard2.png)

## Create new project

You can quickly create a new map project by clicking on the button near the top. This takes you into the **Project workspace**.

[![Project](../assets/images/studio-newmap.png)](../assets/images/studio-newmap.png)

Every map has at least a basemap, which you can style by picking from the list of themes provided.
But to make an interesting project, you need to put some data on top of that map.

The *data* will stored
in a Space on the Hub for you and nobody else can see it until you start sharing it. In addition,
you can *style* your data so it looks like you want to see it. The combination of data+style
is called a *layer*. You can add many layers to make your map and put them on top of each other.

## Upload your data

You can create an empty layer or upload data by clicking on the `+ Add` command below your project name.
This brings up a data selection dialog where you can pick from data that you already have in your Hub,

or upload a new file. This file would preferably be GeoJSON, but you can also use JSON, CSV or a Shapefile.

[![Project](../assets/images/studio-addlayer.png)](../assets/images/studio-addlayer.png)

Once the data has finished uploading, you can mark the Space with the right name in the list and
add it as a layer to your project.

## Data Table

By default you see your data directly on the map, which gives you a good spatial overview of your
data. Depending on the data and how you work with it you might find it helpful to look at it
in table.

When you are looking at a layer, the `Data` button in the top right hand corner
switches to table view where you can edit fields, add columns, and delete rows.
You can always get using the corresponding `Map` button.

[![Project](../assets/images/studio-dataview.png)](../assets/images/studio-dataview.png)

!!! tip
    A similar data table view is also available from the main `Data Hub` where you can also edit
    the name and description of the space.

## Create or edit content

You can also use Studio to visually edit the features contained in your layers. Once you have
selected a layer from the list, you will see a `Pencil` button in the top left hand corner of
the map.

[![Project](../assets/images/studio-editLayer.png)](../assets/images/studio-editLayer.png)

When you switch into editing mode, the sidebar moves out of the way to give you more room to
work with the features in the layer visually on the map.

!!! note "Geographic Feature Editor"
    Studio has a very powerful feature editor built-in. In fact, you get access to the same
    editor that drives the community map editing capabilities in the [**HERE Map Creator**](http://mapcreator.here.com)

[![Project](../assets/images/studio-editFeatures.png)](../assets/images/studio-editFeatures.png)

On the top of the screen you find a toolbar you can use to create new features like points, lines
or area polygons. This new - or of course any of the existing features you select on the map - can
then be moved or even re-shaped visually by dragging control points. It's just like in a drawing
program like Illustrator or Sketch.

[![Project](../assets/images/studio-editToolbar.png)](../assets/images/studio-editToolbar.png)

If you make a mistake or want to change something, you can undo (or redo) any change you made.
You need to commit any changes you want to keep permanently in your data by selecting the
`save` button. You can also `revert` back to the original version if you want to start over
again.

## Style your layer

Now that you have a layer with your data in your project and it sits on top of the basemap, you
can start picking colors, symbols and text to adjust how you want to see it.

[![Project](../assets/images/studio-style.png)](../assets/images/studio-style.png)

As different features (like points, lines or polygons) need different stylistic treatment, there is a
separate section for each of those for every layer in your project.

## Add interactivity

You can also add a bit of interactivity to your map by using *Cards* to show pieces of your data.
In the card section in the left panel you can select which data fields will be shown by dragging above
or below the separator line. Anything above will be shown on the card - if there is enough space - the
rest will be visible for the viewers when they select `Show more` in the published map.

[![Project](../assets/images/studio-cards.png)](../assets/images/studio-cards.png)
