
# 订阅

https://gh-proxy.com/https://raw.githubusercontent.com/YYDS678/uzVideo-extensions/refs/heads/main/uzAio.json

# 添加方式

uz 影视 -> 设置 -> 数据管理 -> 订阅 -> + -> 输入链接 -> 确定


# json 格式

```
{
    "recommend": [
        {
            "name": "名称",
            "codeID": "如果选择了加密请填写，由 uz 生成",
            "url": "扩展链接",
            "remark": "备注",
            "env":"",//环境变量名称1##环境变量描述1&&环境变量名称2##环境变量描述2
            "version": 1, //扩展版本号
            "type": 200 //推荐首页扩展固定 200
        }
    ],
    "panTools": [
        {
            "name": "名称",
            "codeID": "如果选择了加密请填写，由 uz 生成",
            "url": "扩展链接",
            "remark": "备注",
            "env":"",//环境变量名称1##环境变量描述1&&环境变量名称2##环境变量描述2
            "version": 1, //扩展版本号
            "type": 300 //网盘工具扩展固定 300
        }
    ],
    "danMu": [
        {
            "name": "名称",
            "codeID": "如果选择了加密请填写，由 uz 生成",
            "url": "扩展链接",
            "remark": "备注",
            "env":"",//环境变量名称1##环境变量描述1&&环境变量名称2##环境变量描述2
            "version": 1, //扩展版本号
            "type": 400 //弹幕扩展固定 400
        }
    ],
    "live": [
        {
            "name": "名称",
            "url": "直播源链接 m3u 或 txt 格式",
            "remark": "备注",
            "type": 10 //直播源固定 10
        }
    ],
    "vod": [
        {
            "name": "名称",
            "codeID": "如果选择了加密请填写，由 uz 生成",
            "url": "扩展链接",
            "remark": "备注",
            "env":"",//环境变量名称1##环境变量描述1&&环境变量名称2##环境变量描述2
            "version": 1, //扩展版本号
            "type": 101 //视频源扩展固定 101
        }
    ]
}

```
