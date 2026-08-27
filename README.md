# 中小型制造企业质量管理系统

## 前言
欢迎来到我们的中小型制造企业质量管理系统项目页面。本项目致力于为中小型制造企业提供全面、高效的质量管理解决方案。我们采用了Java语言结合Spring Boot框架，以及前端技术如JS、Vue和CSS3，构建了一个强大且易于使用的质量管理系统。现在，让我们一起深入了解这个项目的详细信息。

## 内容介绍
本项目旨在帮助中小型制造企业实现质量管理流程的自动化和高效化。系统提供了从基础数据管理、抽样标准设定、质量检验到检验结果统计分析等一系列功能，使得企业管理人员能够实时监控生产质量，及时发现并解决问题，从而提升产品品质和客户满意度。此外，系统还包含了工作人员管理模块，方便企业对内部人员进行有效的管理和监督。

## 技术介绍
本项目采用了以下技术构建：
- **语言**：Java
- **使用框架**：Spring Boot
- **前端技术**：JS、Vue、CSS3
- **开发工具**：IDEA/Eclipse
- **数据库**：MySQL 5.7/8.0
- **数据库管理工具**：phpstudy/Navicat
- **JDK版本**：jdk1.8
- **Maven**：apache-maven 3.8.1-bin
- **前端环境**：Node.js 12/14/16

## 核心代码
以下是系统中抽样标准管理模块的一部分核心代码：

```java
@RestController
@RequestMapping("/samplingStandard")
public class SamplingStandardController {

    @Autowired
    private SamplingStandardService samplingStandardService;

    @GetMapping("/list")
    public ResponseData list() {
        List<SamplingStandard> list = samplingStandardService.list();
        return ResponseData.success(list);
    }

    @PostMapping("/add")
    public ResponseData add(@RequestBody SamplingStandard samplingStandard) {
        boolean result = samplingStandardService.add(samplingStandard);
        return result ? ResponseData.success() : ResponseData.error();
    }

    @PutMapping("/update")
    public ResponseData update(@RequestBody SamplingStandard samplingStandard) {
        boolean result = samplingStandardService.update(samplingStandard);
        return result ? ResponseData.success() : ResponseData.error();
    }

    @DeleteMapping("/delete/{id}")
    public ResponseData delete(@PathVariable("id") Long id) {
        boolean result = samplingStandardService.delete(id);
        return result ? ResponseData.success() : ResponseData.error();
    }
}
```

这段代码展示了如何通过Spring Boot的RestController和RequestMapping来实现对抽样标准管理接口的增删查改操作。

## 免费源码获取

```
5000套系统成品在线演示视频，复制到流浪器： 
```
```
https://www.yuque.com/yuqueyonghux32e1j/kxdc9g/ad8oz3bamkxmay0e#Cxun
```
![下载](https://img12.360buyimg.com/ddimg/jfs/t1/339687/11/1349/28408/68ad865fF412d7877/adaa650483a100f2.jpg)

# 项目截图

![封面图片](https://img12.360buyimg.com/ddimg/jfs/t1/318258/12/25033/180065/689e09c6F2d034fc7/5d1975da7b4cd872.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/328850/26/4541/28384/689e09a4F164b2c7a/95bb5616c888b2a5.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/309987/32/26546/130394/689e09a5Fb492634e/40deec1eb1e52f08.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/312713/38/25163/53131/689e09aaF13151d08/1e66ccd5bee4cebc.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/288123/24/25171/72020/689e09acF9ba38471/47edd710321a500b.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/303112/14/25348/32947/689e09acF3df19fc1/f56b5ee94700d44f.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/306829/39/26676/69657/689e09afFfa6bca47/0a8946b522d9c71f.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/295792/11/12920/131624/689e09b0F728141e1/656302e7a72ed963.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/318453/20/24910/71733/689e09b2Ffb0e143a/7894bb7b04e6570d.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/294906/29/13968/32745/689e09b2F9f9fd432/0e538a54d7d1c169.jpg)


## 万字文档
![文档介绍](https://img14.360buyimg.com/ddimg/jfs/t1/338393/1/3576/156947/68b1ad0cF74dc525c/ff9cd6c574295685.jpg)
