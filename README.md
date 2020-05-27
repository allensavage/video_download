# video_download

## hints for encrypted m3u8 video download 

1. install modules
2. create m3u8_utl.txt under m3u8_download dir
3. run python m3u8_download.py

### Prerequisites

The following dependencies are necessary:

* **[Python](https://www.python.org/downloads/)**  3 or above
* **[aria2](https://aria2.github.io/)** 

```python
pip install requests
pip install pycryptodome
# maybe you find out that these two little guys missing
pip install m3u8
pip install natsort
```

## Getting Started

### Download a video with m3u8

如果获取m3u8时总是失败，比如返回404，可以在浏览器中调试模式找到m3u8内容，复制到本地文件。（此时需要注意是否需要修改ts文件的url）

#aria2c.exe  --conf-path=aria2.conf


#mitmdump -s proxy.py --flow-detail 0



