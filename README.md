# SPAS
将字符串坐标数组（如：[[[109.2041015625,30.088107753367257],[115.02685546875,30.088107753367257], [115.02685546875,32.7872745269555],[109.2041015625,32.7872745269555],[109.2041015625,30.088107753367257]]]）和属性字段统一转成geojson数据格式！

geojson格式举例：
{
  "type": "FeatureCollection",
  "features": [
        {"type":"Feature",
        "properties":{},
        "geometry":{
            "type":"Point",
            "coordinates":[105.380859375,31.57853542647338]
            }
        }
    ]
}
