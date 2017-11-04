# 此项目已经停止维护更新
# 新项目地址 [https://github.com/imu-hupeng/xl_url_convert](https://github.com/imu-hupeng/xl_url_convert)
# urlconvert
## 用于普通下载地址与迅雷，快车，QQ旋风下载地址之间的转换
# 调用方式如下：
```python
address = download_address_translation('thunder://QUFlZDJrOi8vfGZpbGV8tcHEubHKvMcuSEQxMjgws6zH5bn60 /W0NOiy6vX1i5tcDR8MzA3NDc3Njk5NXxCOEE2OEY5RDQ2RkZGMzlEQzAzNUYzMEJCRkUzMDA4NHxoPVRXWkJWQkdIMlNRRURCTkFCM0M3WEdZQVRTSDY0RUoyfC9aWg==')
print('原始下载地址:'   address.get('origin'))
print('迅雷下载地址:'   address.get('thunder'))
print('快车下载地址:'   address.get('flashget'))
print('QQ旋风下载地址:'   address.get('qqdl'))
```
