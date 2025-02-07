# AssetLibraryTools

AssetLibraryTools is a free addon which aims to speed up the process of creating asset libraries with the asset browser, This addon is currently very much experimental as is the asset browser in blender.

# Features
* Batch import PBR materials from texture sets
  * Add real displacement to materials upon import
  * Add fake user to materials upon import
  * Skip materials that already exist
* Batch import models of various filetypes (fbx, gltf, obj, x3d)
  * Hide imported models straight after import
* Batch append objects/materials from multiple .blend files at once
  * Search for .blend files to append from in subdirs recursively
  * Dont append lights option
  * Dont append cameras option
* Batch download CC0 assets from ambientcg.com via a python script
  * Filter assets by: Keyword, Download attributes, File extension
  * Unzip downloaded zip files automatically
  * Delete zip files after unzip automatically
  * Skip downloading files that already exist
* Generate custom collection/object asset browser thumbnails (base code from https://github.com/johnnygizmo/asset_snapshot)
* Batch import SBSAR files via Adobe substance 3D add-on for blender
* Batch mark/unmark materials, meshes, objects, images, and textures as assets
* Batch delete all materials/objects/textures/images/meshes
* Enable real displacement for cycles on all materials at once
* Change displacement scale on all materials at once
* Clean up duplicate materials (based on name)
* Clean up unused materials
* And more to come

![image](https://user-images.githubusercontent.com/65134690/131561256-c1c6f9ba-fc2e-4940-8e32-478bb7d12feb.png)
