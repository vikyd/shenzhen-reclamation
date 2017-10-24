
# 深圳填海卫星图



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



# 图片文件
- pdf 文件是一个多图层文件，可方便只看某年份卫星图，或叠加两年份对比查看
- png 是原始清晰度的图片（但不带地理坐标参考信息），`1973 vs 2017GoogleMap.png`放大查看更好



# 软件
- ArcMap
- ArcGoogle（ArcMap 插件，查看 Google 地图）：http://ungdungmoi.com/arcgoogle.htm



# 更多卫星图下载
- 美国地质调查局 USGS：https://glovis.usgs.gov/



# 为什么选择 Landsat 卫星图像？
- 免费下载
- 带精确地理坐标
- 1972 年 至 今 一直有图像数据
- Landsat 1 卫星发射于 1972 年，若还有更早的且可免费获取的卫星图像，请告诉我（issue）


# 杂
- Landsat 卫星图像的命名规则
  - https://landsat.usgs.gov/what-are-naming-conventions-landsat-scene-identifiers
- Google 地图与 1973 Landsat卫星图略有偏移，估计是因为 Google 用了墨卡托投影，而 Landsat 图像用的是 UTM。不过卫星图1973 vs 2016是没有偏移的。