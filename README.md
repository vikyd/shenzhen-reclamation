
# 深圳填海卫星图

![1973 Landsat vs 2016 ArcGISMap 动图](https://github.com/vikyd/shenzhen-reclamation/raw/master/gif/1973landsat_vs_2016arcgismap.gif)


![1973 Landsat vs 2016 ArcGISMap 地点](https://github.com/vikyd/shenzhen-reclamation/raw/master/jpg/1973landsat_vs_2016arcgismap_POI.jpg)

# 1973 年卫星图
- 年份：1973 年
- 卫星：Landsat 1
- 传感器：MSS
- 坐标系统：WGS_1984_UTM_zone_49N
- 分辨率：60m*60m
- 格式：GeoTIFF
- 下载：https://earthexplorer.usgs.gov/browse/gisready/mss/LM11310441973359AAA05?did=335087495



# 2016 年卫星图
- 年份：2016 年
- 卫星：Landsat 8
- 传感器：OLI + TIRS 合成
- 坐标系统：WGS_1984_UTM_zone_49N
- 分辨率：30m*30m
- 格式：GeoTIFF
- 下载：https://earthexplorer.usgs.gov/browse/gisready/landsat_8/LC08_L1TP_122044_20160918_20170321_01_T1?did=335089046

# 2016 年 ArcGIS Map
- 年份：约 2016 年
- 来源：https://www.arcgis.com/home/webmap/viewer.html?useExisting=1&layers=10df2279f9684e4a9f6a7f08febac2a9
- 下载：某地图下载器



# 文件目录
```
│  shenzhen-reclamation.mxd
│
├─1973-landsat
│      LM11310441973359AAA05.tif
│
├─2016-landsat
│      LC08_L1TP_122044_20160918_20170321_01_T1.tif
│
├─2016-nearby-arcgismap
│      2016-nearby-arcgismap.jgw
│      2016-nearby-arcgismap.jpg
│      2016-nearby-arcgismap.jpg.aux.xml
│
├─gif
│      1973landsat_vs_2016landsat.gif
│      1973landsat_vs_2016arcgismap.gif
│      1973landsat_vs_2016landsat.uga
│      1973landsat_vs_2016arcgismap.uga
│
└─jpg
        1973-landsat.jpg
        2016-landsat.jpg
        2016-nearby-arcgismap.jpg
        1973landsat_vs_2016landsat.jpg
        1973landsat_vs_2016arcgismap.jpg
        1973landsat_vs_2016arcgismap_POI.jpg
```



# 软件
- ArcMap
- 某地图下载器



# 更多卫星图下载
- 美国地质调查局 USGS：https://glovis.usgs.gov/



# 为什么选择 Landsat 卫星图像？
- 免费下载
- 带精确地理坐标
- 1972 年 至 今 一直有图像数据
- Landsat 1 卫星发射于 1972 年，若还有更早的且可免费获取的卫星图像，请告诉我（issue）


# 其他
- Landsat 卫星图像的命名规则
  - https://landsat.usgs.gov/what-are-naming-conventions-landsat-scene-identifiers
- Google 地图与 1973 Landsat卫星图略有偏移，估计是因为 Google 用了墨卡托投影，而 Landsat 图像用的是 UTM。不过卫星图1973 vs 2016是没有偏移的。