# 20211019_MacroImageJ_Semi_automatic_Macropinocytosis_analysis
This package contains 3 separate macro for semi-automatically analyse and export results for macropinocytosis assay.

Step 1: Use the "Updated_Auto_split_adjust_save" macro
This macro automatically split the 2 channels DAPI and Dextran, and adjust the brightness of the Dextran channel to allow area selection later on and then save all the images
into a selected Output folder. 

Step 2: Open the Output folder and use the Freehand selection tool to outline the selected area in the Area_ images then delete the outter unselected area. Transfer the selected
area to the second Dextran image by pressing Shift+Command+E, then delete the outter unselected area. Save these images into 2 sets of folders called "Area" and "Dextran" to 
make it easier for the macro to work later on.

Step 3: Use the "Auto_Analyse_Area_Export_Results" macro
This macro will take input images from the "Area" folder and automatically measure the area selected previously from step 2 then save the Results files back to the "Area" folder.

Step 4: Use the "Auto_Analyse_Dextran_Export_Results" macro
This macro will take input images from the "Dextran" folder and automatically measure the Dextran area selected previously from step 2 then save the Summary files back to the 
"Dextran" folder.
