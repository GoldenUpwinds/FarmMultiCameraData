# FarmMultiCameraData

### 1.1 Description
The image data is collected by RealSense D435 in in experimental fields of the College of Agriculture and Biology, Shanghai Jiao Tong University. The data is used to get freespace in highly degraded environment, taking farmland as an example, which is now used in Bachelor's undergraduate degree thesis:

Unstructured Driving Road Recognition for Autonomous Driving Agricultural Machinery based on Visible Light/Infrared, Yicheng Jin

### 1.2 Sensor parameter
* **RGB-D Camera:** RealSense D435

* **Rostopics of rosbag sequences:** 
    * /camera/aligned_depth_to_color/image_raw_throttle
    * /camera/color/image_raw_throttle
    * /camera/infra1/image_rect_raw_throttle
    * /camera/infra2/image_rect_raw_throttle

* **intrinsic parameters:** D435/camera_extrinsic.yaml

### 1.3 Dataset sequences

#### 1.3.1 2023-03-08
These data were mainly recorded in the afternoon when the sunlight was good, including all accessible farmland at that time.
* topic frequency: 5Hz

Sequence Name|Collection Date|Total Size|Duration|Environment|Depth Topic|Fill Light|Rosbag
--|:--|:--:|--:|--:|--:|--:|--:
farm-daylight-01|2023-03-08|1.0GB|113s|Clear/Daytime|include|-|[Rosbag(b5uf)](https://pan.baidu.com/s/12hzjC_QVNAdiXyDWHvTE6A)
farm-daylight-02|2023-03-08|590.9 MB|63s|Clear/Daytime|include|-|[Rosbag(kvwa)](https://pan.baidu.com/s/1JK-eiCetOLEkjd4VVWQ0Qg)
farm-daylight-03|2023-03-08|593.9 MB|63s|Clear/Daytime|include|-|[Rosbag(gt4k)](https://pan.baidu.com/s/1Wji2woliqFqSgczPDumzuA)
farm-daylight-04|2023-03-08|949.1 MB|100s|Clear/Daytime|include|-|[Rosbag(h69z)](https://pan.baidu.com/s/1nI18jmxm9MoWsCE3dIFyug)
farm-daylight-05|2023-03-08|1.5 GB|157s|Clear/Daytime|include|-|[Rosbag(xu2m)](https://pan.baidu.com/s/11uhOVShFysDr7KyIKqIv4g)
farm-daylight-06|2023-03-08|1.4 GB|154s|Clear/Daytime|include|-|[Rosbag(mppc)](https://pan.baidu.com/s/1OIQ7oa-e76qI1z_ubPRndA)

Labelled images(semantic segmentation) can be found in: [Labelled(8b4k)](https://pan.baidu.com/s/1D_ar20gX4WsoLncszl3l5A)

#### 1.3.2 2023-04-06
These data were recorded on a cloudy day with slight drizzle, and there were significant variations in lighting conditions compared to sunny weather.
* topic frequency: 5Hz

Sequence Name|Collection Date|Total Size|Duration|Environment|Depth Topic|Fill Light|Rosbag
--|:--|:--:|--:|--:|--:|--:|--:
farm-daliycloudy-01|2023-04-06|246.2 MB|36s|Cloudy/Daytime|-|-|[Rosbag(xy7z)](https://pan.baidu.com/s/1OvgkXncLqeMB5WN-VwA_1A)
farm-daliycloudy-02|2023-04-06|395.7 MB|59s|Cloudy/Daytime|-|-|[Rosbag(tmc8)](https://pan.baidu.com/s/1CBuwG6yYpaTO36nUAmHiwA)
farm-daliycloudy-03|2023-04-06|121.4 MB|17s|Cloudy/Daytime|-|-|[Rosbag(xn35)](https://pan.baidu.com/s/1Axbc89LVIo25ZNZs71E3Dg)

#### 1.3.2 2023-04-11
These data were recorded at night, and to address the issue of poor lighting in nighttime scenes, various methods such as visible light supplementation, infrared supplementation, and mixed supplementation were employed to provide diverse environmental conditions.
* topic frequency: 5Hz

Sequence Name|Collection Date|Total Size|Duration|Environment|Depth Topic|Fill Light|Rosbag
--|:--|:--:|--:|--:|--:|--:|--:
farm-night-01|2023-04-11|427.6 MB|39s|Clear/Night|-|-|[Rosbag(jqit)](https://pan.baidu.com/s/1zjSYWBHU11b9mxs6K7a3eQ)
farm-night-02|2023-04-11|603.5 MB|56s|Clear/Night|-|-|[Rosbag(uxf7)](https://pan.baidu.com/s/1AkAWKzEqbGjKxF2FijYQbg)
farm-night-03|2023-04-11|602.6 MB|56s|Clear/Night|-|-|[Rosbag(yqf7)](https://pan.baidu.com/s/19xcSt2hnPrrpP2jz4i5cyw)
farm-filllight-01|2023-04-11|481.0 MB|45s|Clear/Night|-|visible light|[Rosbag(t4a3)](https://pan.baidu.com/s/1VpgRgvz-dZ9Qj6_2dx0jjg)
farm-fillinfra-01|2023-04-11|731.6 MB|67s|Clear/Night|-|850nm infra|[Rosbag(i54p)](https://pan.baidu.com/s/1m-DCJYMvKcga23gll25iTQ)
farm-fillinfra-02|2023-04-11|297.8 MB|27s|Clear/Night|-|850nm infra|[Rosbag(e5hb)](https://pan.baidu.com/s/1tsshN0CL89j_UQa8LbvGEg)
farm-fillmix-02|2023-04-11|549.9 MB|51s|Clear/Night|-|visible+850nm|[Rosbag(d2bb)](https://pan.baidu.com/s/1UYeb6Bxv1tvMlI1NBgp38A)