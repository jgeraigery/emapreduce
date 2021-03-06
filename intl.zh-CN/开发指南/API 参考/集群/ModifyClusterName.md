# ModifyClusterName {#concept_n1l_qcb_kfb .concept}

修改集群参数以及示例代码

## 请求参数 {#section_atg_5cb_kfb .section}

|字段|类型|是否必须|默认值|描述|
|--|--|----|---|--|
|Id|String|是|无|集群 ID|
|Name|String|是|无|集群新的名称，要求和创建集群时一致。长度限制为1-64个字符，只允许包含中文、字母、数字、-、\_。|
|RegionId|String|是|无|区域 ID|

## 返回参数 {#section_sby_zcb_kfb .section}

公共返回参数

## 示例 {#section_s4t_2db_kfb .section}

-   请求示例

    ```
    https://emr.aliyuncs.com/?Action=ModifyClusterName
    &Id=C-13A570B821D4BAB3
    &Name=Cluster_Name
    &RegionId=cn-hangzhou
    &公共请求参数
    ```

-   返回格式

    JSON 格式

    ```
    {
        "RequestId": "34B08619-2636-49F9-AB4E-CD8D347B1E07"
    }
    ```


