## 多数据源 IP GEO

## 整合多接口的IP地址查询工具

## 整合多数据源的IP地址查询接口



## IP GEO, 多数据源查询 IP 归属地

可以不加参数请求（直接请求/geo_ip），直接查询请求源 IP 地址信息。 [Geo 数据发行方](https://iphunter.net/ipx/geo_data "Geo 数据发行方")

<pre>
http://iphunter.net/geo_ip?ipv4=8.8.8.8
 
{
    "code": 10000,
    "result": {
        "geo_GeoLite2_ASN": {...},
        "geo_ipipNet": {...},
        "geo_MaxMindGEOLite2": {...},
        "geo_ip2location": {...},
        "geo_cz88Net": {...},
        "geo_ip2Region": {...}
    },
    "msg": "查询成功，数据仅作为对照参考，如有疑问请联系数据发行方",
    "query": {
        "ip": "8.8.8.8",
        "ip_int": 134744072
    }
}</pre>

### https://iphunter.net/ipx/api
