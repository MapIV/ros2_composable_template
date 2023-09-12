# composable_sample

Subscribes to a ROS2 PointCloud2 topic and stores received messages to Binary PCD files.

How to launch:
```
ros2 launch ros2_cloud_to_pcd cloud_to_pcd.xml \
    input/topic:=/lidar/pointcloud \
    output/topic:=/processed/pointcloud
```

## Parameters
| Parameter       | Default         | Description              |
|-----------------|-----------------|--------------------------|
| `input/topic`   | `/input_topic`  | ROS2 Topic to subscribe. |
| `output/topic`  | `/output_topic` | ROS2 Topic to publish.   |

