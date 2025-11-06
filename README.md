# 前言

通讯录管理系统是我们在日常生活和工作中常用的一种软件，它能够帮助我们高效地管理和查找联系人信息。本项目是基于SSM（Spring、SpringMVC、MyBatis）框架实现的通讯录管理系统，具备良好的可扩展性和易用性。以下为项目的详细说明。

## 内容介绍

本项目主要包括联系人管理、用户管理、权限管理等功能模块。通过本项目，用户可以实现联系人信息的增删改查、分组管理、导入导出等操作。同时，系统采用角色权限控制，确保用户数据的安全性。此外，项目还提供了友好的用户界面，便于用户快速上手和使用。

## 技术介绍

- **语言：** Java
- **使用框架：** Spring、SpringMVC、MyBatis
- **前端技术：** JS、Vue、CSS3
- **开发工具：** IDEA/Eclipse
- **数据库：** MySQL 5.7/8.0
- **数据库管理工具：** phpstudy/Navicat
- **JDK版本：** jdk1.8
- **Maven：** apache-maven 3.8.1-bin
- **前端环境：** Node.Js 12\14\16

## 核心代码

以下是项目中与联系人管理相关的一段核心代码：

```java
// 联系人服务层接口实现类
@Service
public class ContactServiceImp implements ContactService {

    @Autowired
    private ContactMapper contactMapper;

    // 添加联系人
    @Override
    public boolean addContact(Contact contact) {
        return contactMapper.insert(contact) > 0;
    }

    // 修改联系人
    @Override
    public boolean updateContact(Contact contact) {
        return contactMapper.updateByPrimaryKey(contact) > 0;
    }

    // 删除联系人
    @Override
    public boolean deleteContact(Integer id) {
        return contactMapper.deleteByPrimaryKey(id) > 0;
    }

    // 查询联系人列表
    @Override
    public List<Contact> getContactList() {
        return contactMapper.selectAll();
    }
}
```

## 免费源码获取

```
5000套系统成品在线演示视频，复制到流浪器： 
```
```
https://www.yuque.com/yuqueyonghux32e1j/kxdc9g/ad8oz3bamkxmay0e#Cxun
```
![下载](https://img12.360buyimg.com/ddimg/jfs/t1/339687/11/1349/28408/68ad865fF412d7877/adaa650483a100f2.jpg)

## 项目截图

![封面图片](https://img13.360buyimg.com/ddimg/jfs/t1/341449/8/815/137869/68bdd46aF955aea47/a47b114392ec40c4.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/332793/37/10607/39308/68bdd443F0c37687d/9f40e22c7ac1c69c.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/331790/3/10563/82149/68bdd443F88991b61/ebd7e0f3566adbb7.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/342332/32/786/18869/68bdd443F85d10fc2/abd2d52e1476eb9a.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/337562/29/8170/73257/68bdd444Fb2f664f7/d99eee3b7deb6ea2.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/333483/25/10779/81181/68bdd445Fe6f2418f/5ba9d17ba6eb9be5.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/323240/39/12294/23813/68bdd445F6629e764/deed1ddbe20278d1.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/343338/9/776/37978/68bdd446Fe60653bb/af2b22d97839536a.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/328538/27/17354/49768/68bdd446F23c32321/63dbc7c5678f3894.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/345277/27/801/49765/68bdd447F151b7762/edc548417d4159b3.jpg)

