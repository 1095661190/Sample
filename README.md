# 获取数据目录列表文档示例

该项目为分页查询，获取元数据库命名空间（Catalog）列表。文档示例，该示例**无法在线调试**，如需调试可下载到本地后替换 [AK](https://usercenter.console.aliyun.com/#/manage/ak) 以及参数后进行调试。

## 运行条件

- 下载并解压需要语言的代码;


- 在阿里云帐户中获取您的 [凭证](https://usercenter.console.aliyun.com/#/manage/ak)并通过它替换下载后代码中的 ACCESS_KEY_ID 以及 ACCESS_KEY_SECRET;

- 执行对应语言的构建及运行语句

## 执行步骤

下载的代码包，在根据自己需要更改代码中的参数和 AK 以后，可以在**解压代码所在目录下**按如下的步骤执行

- Java V2.0
- *最低要求Java 8*
```sh
mnv clean package
java -jar target/sample-1.0.0-jar-with-dependencies.jar
```
## 使用的 API

-  ListCatalogs 分页查询，获取元数据库命名空间（Catalog）列表。文档示例，可以参考：[文档](https://next.api.aliyun.com/document/DataLake/2020-07-10/ListCatalogs)

## 返回示例

*实际输出结构可能稍有不同，属于正常返回；下列输出值仅作为参考，以实际调用为准*


- JSON 格式 
```js
{
  "Catalogs": [
    {
      "CatalogId": "1090142773636588",
      "CreateTime": 1598664214
    },
    {
      "CatalogId": "1344371",
      "CreateTime": 1597650660
    },
    {
      "CatalogId": "owner_136b8fddb1614a5d92c145b5e6682945",
      "CreateTime": 1598664213
    },
    {
      "CatalogId": "owner_20614244f6b24d12a1f89c231a54895b",
      "CreateTime": 1598871054
    },
    {
      "CatalogId": "owner_356e0d8eba20493381ae2268fb056184",
      "CreateTime": 1598871054
    },
    {
      "CatalogId": "owner_3b0f1ced66bf4a53a120bb15c2b4963c",
      "CreateTime": 1598664214
    },
    {
      "CatalogId": "owner_5a99a3cb45ec4b24a694828477098eda",
      "CreateTime": 1598664214
    },
    {
      "CatalogId": "owner_6414ebfc6dea45a9a106712cf4f36fb5",
      "CreateTime": 1598664215
    },
    {
      "CatalogId": "owner_668ef68165814bf99cc733cbec5426a9",
      "CreateTime": 1598664215
    },
    {
      "CatalogId": "owner_66b5e8fd3f8446f7a8c7d8145fbc81b9",
      "CreateTime": 1598871055
    }
  ],
  "Code": "OK",
  "HttpStatusCode": 200,
  "Message": "",
  "NextPageToken": "owner_66b5e8fd3f8446f7a8c7d8145fbc81b9!",
  "RequestId": "DE12C68A-E063-4238-92A7-09422B30097B",
  "Success": true
}
```
- XML 格式 
```xml

```

