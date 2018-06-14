## 1.链接
    千丁VPN账号：liliange 密码：llg@2014
    千丁git地址：[图片]http://git.iqdnet.cn
    龙湖git地址：[图片]http://git.longhu.net
    千丁mis测试地址：[图片]http://10.37.253.7:81/wui/main.jsp

    千丁mis正式地址：[图片]http://mis.qdingnet.com

    mis测试环境修改密码 保存调用接口地址：[图片]http://10.37.251.71:8081/ajax/changePassword
    POST 参数loginId，newPassword

    龙湖app下载链接：
    [图片]https://www.pgyer.com/n8bg （android 测试版）
    [图片]https://www.pgyer.com/22P4 （android 线上版）
    ios测试版：[图片]https://fir.im/39ql?release_id=5a97c5b2959d6930248ad322
								
    部署请假出差申请：【请教】
    网址 [图片]http://devjenkins.iqdnet.cn
    用户名：liangwei
    密码：liangweI!


    龙信用户名-mis用户名接口：【备用】
    [图片]https://mis-mmp.qdingnet.com/ajax/getMisLoginNameLH/{龙信用户名}

    返回值{"code":"200","message":"成功","data":"weihuaning"}

    BPM登陆网址：[图片]http://10.37.251.48:28110/Portal/index.html#/platform/login
    用户：liangwei
    密码：000000
    【发起流程】

    移动审批：
    [图片]http://192.168.33.45:8080/lhydsp/PAGE_APP/list.html?usercode=qd_menghu、
    【显示我的代办，我的已办，我的发起三个模块，手机端也可以查看】

    settings-devices-edit： 788dc519-3962-4acc-832e-1f30b60add0d


## 2.说明
* BPM包含MIS和BOSS页面，数据传输方式是一样的，目前测试环境中的mis页面都已经迁移成新页面的写法，以后的开发也都是用新页面的写法
* 费控数据传输方式不一样，按照接口文档渲染页面
* 接口都是走直连版的，如有不懂问后端
* moapproval-cli文件是龙信详情页项目，可以看看代码
* mis文件夹下放的是写过的mis系统写过的代码,已经上线后期维护可以看。
操作步骤：登陆mis系统->后端应用中心->流程引擎->路径管理->路径设置->搜索表单->流转设置->节点信息->表单内容->显示模板->插入->代码块
* 做过一个微信分享，已经上线，知道就可以
* 目前的遗留问题是MIS的一部分新流程，开发完毕，正在测试环节，需要帮助测试解决出现的问题，费控页面也已经进入测试环节，需要帮助测试遇到的问题

