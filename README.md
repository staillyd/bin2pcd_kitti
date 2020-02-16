forked from https://github.com/HTLife/kitti_velodyne_bin_to_pcd.git

# kitti_velodyne_bin_to_pcd

 - [Visual Odometry / SLAM Evaluation 2012](http://www.cvlibs.net/datasets/kitti/eval_odometry.php)


# Usage
```
Options
  --help : produce help message
  --b : bin file folder, 默认"./bin"
  --p : pcd file folder, 默认"./pcd"
  --m : mode - bin2pcd, pcd2bin, 默认"bin2pcd"
```

## Example
Eg1:
```
./binpcd --m=bin2pcd --b=/home/docker_share/sequences/00/velodyne/ --p=/home/docker_share/sequences/00_pcd
```
Eg2:
```
./binpcd
```