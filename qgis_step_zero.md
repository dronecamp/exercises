# QGIS 'Step Zero' Assignment

If you plan to take the [QGIS workshop](https://dronecamp.github.io/2020/2020-06-24.html#mapping-and-analyzing-drone-data-in-arcgis-pro) at DroneCamp, please complete the following exercise *before* the start of DroneCamp.

## 1. Install QGIS

To install QGIS, start by downloading the installation file for your operating system:

https://qgis.org/en/site/forusers/download.html

Please install the **long-term release (most stable)** version, which is currently QGIS 3.10.5 (*A Coruña*). We recommend using a **Standalone installer**.

Installation is usually very straight-forward. If needed, more detailed instructions can be found [here](https://qgis.org/en/site/forusers/alldownloads.html).

QGIS is available on Windows, macOS, Linux and Android. Please note that the DroneCamp 2020 QGIS workshop was developed and tested on **Windows**. The software appearance or behavior may differ slightly on other operating systems.

**Launch QGIS**. If it opens, you're in business!

## 2. Download a TIF Image

Imagery from drones and satellites are generally saved in *raster* files (i.e., tif). Please download the following sample tif image (which contains a vegetation index of field - we'll learn how to make this during the workshop). The tif file has been compressed as a zip file (64MB).

https://github.com/dronecamp/exercises/raw/master/data/Solano_4l7l20_index_ndre.zip

Be sure to take note where the zip file goes! (When in doubt look in your Downloads folder).

## 3. Unzip the Data

Create a folder for the QGIS workshop at a location of your choice (your Desktop or Documents folder are good options). Double-click the zip file to open it, then **drag the contents out of the zip file put them in your workshop folder**. On Windows you can also right-click a zip file and choose 'Extract'. If you don't have an unzip program, we recommend [7zip](https://www.7-zip.org/download.html).

## 4. Start a New QGIS Project

1. Open QGIS
2. Under the "Project" tab select "New" to create a new project (or `ctrl + n`)
3. Under the "Project" tab select "Save As..." (`ctrl + shift + s`) to save the project. Give it a name like *crop_analysis.qgz*.

* Tip 1: You can save your QGIS project anywhere, but putting in the same location as the data will make it easier to find and move.

* Tip 2: It is a good idea to regularly save projects while working on them (`ctrl + s`).

## 5. Add a Raster Layer

A **Raster Layer** is simply a layer in your map that contains some raster data.

1. Add a raster layer by going to `Layer` >> `Add Layer` >> `Add Raster Layer...` (or `ctrl + shift + r`). This opens the *Data Source Manager*.

![](img/qgis_data_source_manager_444x400x256.png)

2. Make sure the `Source type` radio button is selected to be `File`.

3. Click the `...` button and find  the *Solano_4l7l20_index_ndre.tif* file (in the `example_data` folder).

4. Choose `Add` to add the image to the project, then `Close` the Data Source Manager.

## 6. Conclusion

Can you see the raster layer below? If so, **you're done!** Be ready to download more data the week before DroneCamp.

If not, check the steps and if you still can't figure it out please come to one of the [Drop-In Tech-Support](https://dronecamp.github.io/2020/index.html#schedule-at-a-glance) sessions the week before DroneCamp.

![](img/check-in-1_1024x576.png)
