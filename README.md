# BaiduMapKit_Subspec

百度地图 iOS SDK(官方) 支持subspecs，已经支持cocoapods

地址:
https://github.com/YiJianJun/BaiduMapKit_Subspec

目前版本见tag_version，支持Base/Cloud/Location/Map/Radar/Search/Utils
Subspecs:
- BaiduMapKit_Subspec/Base
- BaiduMapKit_Subspec/Cloud
- BaiduMapKit_Subspec/Location
- BaiduMapKit_Subspec/Map
- BaiduMapKit_Subspec/Radar
- BaiduMapKit_Subspec/Search
- BaiduMapKit_Subspec/Utils

CocoaPods导入
###单个导入 
pod 'BaiduMapKit_Subspec/Location'
###多个导入 
pod 'BaiduMapKit_Subspec', :subspecs => ['Base', 'Location', 'Map', 'Search', 'Utils'] # 'Cloud', 'Radar',

###注意：pod 'BaiduMapKit_Subspec' #等价于pod "BaiduMapKit"

