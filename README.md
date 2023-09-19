# Credit Default

## setup-env

```
conda env create -f ./environment.yml
```

## data describe

|            字段            |              含义              |
| :------------------------: | :----------------------------: |
|             Id             |               id               |
|         LIMIT_BAL         |           限制的金额           |
|            SEX            |              性别              |
|         EDUCATION         |            教育水平            |
|          MARRIAGE          |              婚否              |
|            AGE            |              年龄              |
|           PAY_x           |   支付类型x（其中x包含1-6）   |
|         BILL_AMTx         | 限制类型x的额度（其中x包括1-6) |
|          PAY_AMTx          |  支付总额类型x（其中x包括1-6)  |
| default.payment.next.month |         下个月是否支付         |
