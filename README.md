## IPHunter API

Access-Control-Allow-Origin: *



## Get headers

<pre>http://iphunter.net/get

{
    "Remote_ip": "8.8.8.8",
    "X-Forwarded-For": "8.8.8.8",
    "X-Real-Ip": "8.8.8.8",
    "Remote_ip_int": 134744072,
    "Accept-Language": "zh-CN,zh;q=0.9,en-US;q=0.8,en;q=0.7",
    "Accept": "text/html,application/xhtml+xml,application/xml;",
    "Host": "iphunter.net",
    "Cookie": "",
    "User-Agent": "Mozilla/5.0 (Macintosh; Intel Mac OS X 10_14_6) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/75.0.3770.142 Safari/537.36",
}</pre>


---

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



### IPHunter
### IP-Hunter ['hʌntər]， 发掘 IP 地址更多价值

![avatar](https://iphunter.net/static/iphunter_font_2.png)

### https://iphunter.net/aips/

