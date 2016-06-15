# 3ds Max 2017 MCG Samples

A library of useful Max Creation Graph (MCG) compounds and tools for 3ds Max 2017.

You can use these sample by downloading and unzipping the repository from:  
  https://github.com/ADN-DevTech/3dsMax-MCG-Samples/archive/master.zip
  
to:
  %userprofile%\Autodesk\3ds Max 2017\Max Creation Graph\Tools

Where %userprofile% can be entered directly into Windows explorer. 

Once you have downloaded the new tools, either restart 3ds Max or open the Max Creation Graph Editor and selected 
  Operators > ReloadOperators 

Followed by: 
  Build > Evaluate All Tools.

## Sample MCG Tools

In the object construction panel under the "MCG Cloners" category:
* Grid Cloner - Computes a 3D grid of clones 
* Path Cloner - Computes a series of clones along a spline

In the modifier panel:
* Clone - A simple object cloner sample modifier.
* Cloner from Surface - Computes clones randomly on the surface of a mesh. 
* Cloner from Vertices - Computes clones at each vertex of a mesh.
* Cloner Mesher - Copies a mesh to each cloned location (requires a Cloner below it on the stack)
* Cloner Transform - Transforms the location of each clone location (required a Cloner below it on the stack) 
* Smart Scale - Enables an object to be scaled along an axis selectively stretching parts of the mesh 
* Stacker - Creates copies of meshes that are aligned along an axi using the bounding box

## Sample MCG Compounds

All sample compounds have the suffix "-ext". You can type into the search dialog "*-ext" to see a list of new operators. 

## Sample Scenes 

There are several sample scenes included in the zip that demonstrate the various tools.

## Notes

We recommend that you do not save modify the tools and compounds, but instead copy the files you want into a new directory and make the changes there. 

