# Giblayout Environment Dataset

We annotated eighty small and medium-sized scenes in the Gibson dataset. For a detailed introduction to the Gibson dataset, please refer to the website: https://github.com/StanfordVL/GibsonEnv/blob/master/gibson/data/README.md . Our supplementary content is the mesh model and point cloud model of each floor after segmentation and the ground truth of walls and doors in each scene.


## Download
website：https://pan.baidu.com/s/1ZdPPhjhKIwd5W3eDGRqYew

Extraction code：1w05 


### Citation
If you use Gibson's database or software please cite:

~~~
{
  No content for now
}
~~~

## Dataset Modalities
Each space in the database has its own folder. All the modalities and metadata for each space are contained in that folder.

~~~
/layout
  /Mesh1.obj              # layered Mesh model
  /Mesh2.obj              # layered Mesh model
  /PointCloud1.pcd        # layered PointCloud model
  /PointCloud2.pcd        # layered PointCloud model
/pano
  /points                 # camera metadata
  /rgb                    # rgb images
  /mist                   # depth images
mesh.obj                  # 3d mesh
mesh_z_up.obj             # 3d mesh for physics engine
camera_poses.csv          # camera locations
semantic.obj (optional)   # 3d mesh with semantic annotation
model1.txt                # layered 3D model ground truth
model2.txt                # layered 3D model ground truth
~~~
