# 2024年中国全国5级行政区划（省、市、县、镇、村）


* 数据来源 中华人民共和国国家统计局 https://www.stats.gov.cn/sj/tjbz/tjyqhdmhcxhfdm/2023/
* 最新数据量 665552 （2023年6月30日）
* CSV格式 area_code_2024.csv.gz
* SQL格式 area_code_2024.sql.gz
* JSON格式 单JSON格式太大就不生成了
* 建议级联操作，数据量确实太大了
* 级别
  * 1级：省、直辖市、自治区
  * 2级：地级市
  * 3级：市辖区、县（旗）、县级市、自治县（自治旗）、特区、林区
  * 4级：镇、乡、民族乡、县辖区、街道
  * 5级：村、居委会
* 城乡分类 (1开头是城镇，2开头是乡村)
  * 111表示主城区；
  * 112表示城乡接合区；
  * 121表示镇中心区；
  * 122表示镇乡接合区；
  * 123表示特殊区域；
  * 210表示乡中心区；
  * 220表示村庄


## 2010-2024年行政区划数量变化

|     年    | 省 |  市 |  县  |   镇  |   村   |
|-----------|----|-----|------|-------|--------|
|    2010   | 31 | 345 | 3144 | 44050 | 700107 |
|    2023   | 31 | 342 | 3261 | 41350 | 619502 |
|    2024   | 31 | 343 | 3255 | 41351 | 620572 |
| 2010-2024 | 0  |  -2 | 111  | -2699 | -79535 |


2024年分省行政区划数量

|     代码     |       省份       |   市  |   县   |    镇   |    村    |
|--------------|------------------|-------|--------|---------|----------|
| 110000000000 |      北京市      |   1   |   16   |   349   |   7535   |
| 120000000000 |      天津市      |   1   |   16   |   299   |   5617   |
| 130000000000 |      河北省      |   12  |  201   |   2365  |  54145   |
| 140000000000 |      山西省      |   11  |  132   |   1352  |  21895   |
| 150000000000 |   内蒙古自治区   |   12  |  117   |   1225  |  14592   |
| 210000000000 |      辽宁省      |   14  |  114   |   1406  |  16727   |
| 220000000000 |      吉林省      |   9   |   77   |   1075  |  11860   |
| 230000000000 |     黑龙江省     |   13  |  138   |   1703  |  13877   |
| 310000000000 |      上海市      |   1   |   16   |   234   |   6509   |
| 320000000000 |      江苏省      |   13  |  117   |   1487  |  21958   |
| 330000000000 |      浙江省      |   11  |  101   |   1387  |  25547   |
| 340000000000 |      安徽省      |   16  |  135   |   1685  |  18334   |
| 350000000000 |      福建省      |   9   |   93   |   1169  |  17497   |
| 360000000000 |      江西省      |   11  |  111   |   1767  |  22080   |
| 370000000000 |      山东省      |   16  |  167   |   1853  |  62074   |
| 410000000000 |      河南省      |   18  |  198   |   2586  |  52378   |
| 420000000000 |      湖北省      |   14  |  117   |   1475  |  27057   |
| 430000000000 |      湖南省      |   14  |  147   |   2008  |  29534   |
| 440000000000 |      广东省      |   21  |  141   |   1757  |  26842   |
| 450000000000 |  广西壮族自治区  |   14  |  125   |   1284  |  16681   |
| 460000000000 |      海南省      |   5   |   28   |   243   |   3296   |
| 500000000000 |      重庆市      |   2   |   38   |   1031  |  11270   |
| 510000000000 |      四川省      |   21  |  201   |   3111  |  34412   |
| 520000000000 |      贵州省      |   9   |   93   |   1510  |  17964   |
| 530000000000 |      云南省      |   16  |  137   |   1461  |  14888   |
| 540000000000 |    西藏自治区    |   7   |   80   |   705   |   5580   |
| 610000000000 |      陕西省      |   10  |  117   |   1335  |  20356   |
| 620000000000 |      甘肃省      |   14  |   99   |   1403  |  17718   |
| 630000000000 |      青海省      |   8   |   46   |   422   |   4716   |
| 640000000000 |  宁夏回族自治区  |   5   |   27   |   259   |   2912   |
| 650000000000 | 新疆维吾尔自治区 |   15  |  110   |   1405  |  14721   |
| `2024年全国` |     `665552`     | `343` | `3255` | `41351` | `620572` |



## 2010 - 2024 年城乡数据对比

| 城乡分类 | 分类描述         |  2010  |  2024  |    差距   |   百分比  |
|----------|--------------|--------|--------|-----------|-----------|
|   111    | 主城区          | 58509  | 76500  |   +17991  |  +30.75%  |
|   112    | 城乡接合区        | 20389  | 30211  |   +9822   |  +48.17%  |
|   121    | 镇中心区         | 46440  | 53168  |   +6728   |  +14.49%  |
|   122    | 镇乡接合区        | 48447  | 53050  |   +4603   |   +9.50%  |
|   123    | 特殊区域         |  6525  |  5730  |   `-795`  | `-12.18%` |
|   210    | 乡中心区         | 23198  | 11371  |  `-11827` | `-50.98%` |
|   220    | 村庄           | 496599 | 390542 | `-106057` | `-21.36%` |
|----------| ------------ |--------|--------|-----------|-----------|
|    -     | `城区`总数       | 173785 | 212929 |   +39144  |  +22.52%  |
|    -     | `村庄`总数       | 519797 | 401913 | `-117884` | `-22.68%` |


从数据可以看出13年来，村庄(乡中心区和村庄）从`519797` 减少 `401913` 到 `117884`，减少了 `22.68%`，相应的城镇数量`+39144`。
大量人口从农村进入城镇，城镇化率大幅提升。

未来此趋势可能持续，大量的村庄将会荒废直至被合并至其他村庄或者取消行政村。

### 分省份来看2010-2024数据变化

![2010-2024](2010-2024.png "分省查看变化")

### 按照乡村减少比例排序

|     代码     |       省份       | 乡村2010 | 乡村2024 | 乡村变化 | 比例%  |
|--------------|------------------|----------|----------|----------|--------|
| 460000000000 |      海南省      |   5499   |   2268   |  -3231   | -58.76 |
| 430000000000 |      湖南省      |  38202   |  19238   |  -18964  | -49.64 |
| 610000000000 |      陕西省      |  23740   |  12630   |  -11110  | -46.80 |
| 510000000000 |      四川省      |  43097   |  24399   |  -18698  | -43.39 |
| 330000000000 |      浙江省      |  23643   |  13779   |  -9864   | -41.72 |
| 370000000000 |      山东省      |  64691   |  40740   |  -23951  | -37.02 |
| 140000000000 |      山西省      |  25350   |  16220   |  -9130   | -36.02 |
| 420000000000 |      湖北省      |  22765   |  16961   |  -5804   | -25.50 |
| 520000000000 |      贵州省      |  15636   |  12262   |  -3374   | -21.58 |
| 320000000000 |      江苏省      |  11188   |   8985   |  -2203   | -19.69 |
| 340000000000 |      安徽省      |  13697   |  11477   |  -2220   | -16.21 |
| 310000000000 |      上海市      |   838    |   705    |   -133   | -15.87 |
| 120000000000 |      天津市      |   2673   |   2372   |   -301   | -11.26 |
| 620000000000 |      甘肃省      |  14911   |  13473   |  -1438   | -9.64  |
| 130000000000 |      河北省      |  39616   |  36145   |  -3471   | -8.76  |
| 360000000000 |      江西省      |  14642   |  13373   |  -1269   | -8.67  |
| 630000000000 |      青海省      |   3927   |   3621   |   -306   | -7.79  |
| 640000000000 |  宁夏回族自治区  |   2062   |   1913   |   -149   | -7.23  |
| 650000000000 | 新疆维吾尔自治区 |  10686   |  10068   |   -618   | -5.78  |
| 450000000000 |  广西壮族自治区  |  13143   |  12518   |   -625   | -4.76  |
| 530000000000 |      云南省      |  11803   |  11247   |   -556   | -4.71  |
| 110000000000 |      北京市      |   2807   |   2684   |   -123   | -4.38  |
| 350000000000 |      福建省      |  11825   |  11391   |   -434   | -3.67  |
| 150000000000 |   内蒙古自治区   |  10908   |  10732   |   -176   | -1.61  |
| 230000000000 |     黑龙江省     |   9197   |   9085   |   -112   | -1.22  |
| 410000000000 |      河南省      |  38078   |  37866   |   -212   | -0.56  |
| 220000000000 |      吉林省      |   8402   |   8408   |    6     |  0.07  |
| 540000000000 |    西藏自治区    |   5162   |   5185   |    23    |  0.45  |
| 440000000000 |      广东省      |  14662   |  14773   |   111    |  0.76  |
| 210000000000 |      辽宁省      |   9502   |   9691   |   189    |  1.99  |
| 500000000000 |      重庆市      |   7445   |   7704   |   259    |  3.48  |


### 按照乡村减少数量绝对值排序

|     代码     |       省份       | 乡村2010 | 乡村2024 | 乡村变化 | 比例%  |
|--------------|------------------|----------|----------|----------|--------|
| 370000000000 |      山东省      |  64691   |  40740   |  -23951  | -37.02 |
| 430000000000 |      湖南省      |  38202   |  19238   |  -18964  | -49.64 |
| 510000000000 |      四川省      |  43097   |  24399   |  -18698  | -43.39 |
| 610000000000 |      陕西省      |  23740   |  12630   |  -11110  | -46.80 |
| 330000000000 |      浙江省      |  23643   |  13779   |  -9864   | -41.72 |
| 140000000000 |      山西省      |  25350   |  16220   |  -9130   | -36.02 |
| 420000000000 |      湖北省      |  22765   |  16961   |  -5804   | -25.50 |
| 130000000000 |      河北省      |  39616   |  36145   |  -3471   | -8.76  |
| 520000000000 |      贵州省      |  15636   |  12262   |  -3374   | -21.58 |
| 460000000000 |      海南省      |   5499   |   2268   |  -3231   | -58.76 |
| 340000000000 |      安徽省      |  13697   |  11477   |  -2220   | -16.21 |
| 320000000000 |      江苏省      |  11188   |   8985   |  -2203   | -19.69 |
| 620000000000 |      甘肃省      |  14911   |  13473   |  -1438   | -9.64  |
| 360000000000 |      江西省      |  14642   |  13373   |  -1269   | -8.67  |
| 450000000000 |  广西壮族自治区  |  13143   |  12518   |   -625   | -4.76  |
| 650000000000 | 新疆维吾尔自治区 |  10686   |  10068   |   -618   | -5.78  |
| 530000000000 |      云南省      |  11803   |  11247   |   -556   | -4.71  |
| 350000000000 |      福建省      |  11825   |  11391   |   -434   | -3.67  |
| 630000000000 |      青海省      |   3927   |   3621   |   -306   | -7.79  |
| 120000000000 |      天津市      |   2673   |   2372   |   -301   | -11.26 |
| 410000000000 |      河南省      |  38078   |  37866   |   -212   | -0.56  |
| 150000000000 |   内蒙古自治区   |  10908   |  10732   |   -176   | -1.61  |
| 640000000000 |  宁夏回族自治区  |   2062   |   1913   |   -149   | -7.23  |
| 310000000000 |      上海市      |   838    |   705    |   -133   | -15.87 |
| 110000000000 |      北京市      |   2807   |   2684   |   -123   | -4.38  |
| 230000000000 |     黑龙江省     |   9197   |   9085   |   -112   | -1.22  |
| 220000000000 |      吉林省      |   8402   |   8408   |    6     |  0.07  |
| 540000000000 |    西藏自治区    |   5162   |   5185   |    23    |  0.45  |
| 440000000000 |      广东省      |  14662   |  14773   |   111    |  0.76  |
| 210000000000 |      辽宁省      |   9502   |   9691   |   189    |  1.99  |
| 500000000000 |      重庆市      |   7445   |   7704   |   259    |  3.48  |

### 一些有意思的数据分析

- 市这个级别比较稳定，数据变化不大
- 绝大部分省份的城镇数量都在增加，只有黑龙江（`-223`）和四川（`-429`）的城镇有所减少
- 绝大部分省份的乡村数量都在减少，只有辽宁（`+189`）、吉林（`+6`）、广东（`+111`）、重庆（`+259`）、西藏（`+23`）的乡村数量在增加
- 山东省减少了`-23951`个乡村，同比减少`-37%`，是减少最多的省份
- 湖南、四川、陕西减少的乡村数都超过10000个
- 海南、湖南、陕西、四川、浙江的乡村减少比例排在前5，都超过`41%`的比例
----


## CSV格式数据

* code,name,level,pcode,category
* level: 省1，市2，县3，镇4，村5
* code: 12位，省2位，市2位，县2位，镇3位，村3位
* pcode: 直接父级别的code
* category: 城乡分类

文本内容

```bash
$ gzcat area_code_2024.csv.gz |wc -l
  665552

$ gzcat area_code_2024.csv.gz |head
110000000000,北京市,1,0,0
110100000000,市辖区,2,110000000000,0
110101000000,东城区,3,110100000000,0
110101001000,东华门街道,4,110101000000,0
110101001001,多福巷社区居委会,5,110101001000,111
110101001002,银闸社区居委会,5,110101001000,111
110101001005,东厂社区居委会,5,110101001000,111
110101001006,智德社区居委会,5,110101001000,111
110101001007,南池子社区居委会,5,110101001000,111
110101001009,灯市口社区居委会,5,110101001000,111
```

## SQL 格式数据

> $ gzcat area_code_2024.sql.gz |head -n 36

```sql
-- MariaDB dump 10.19  Distrib 10.5.21-MariaDB, for debian-linux-gnu (x86_64)
--
-- Host: 127.0.0.1    Database: china_area
-- ------------------------------------------------------
-- Server version	8.0.32

/*!40101 SET @OLD_CHARACTER_SET_CLIENT=@@CHARACTER_SET_CLIENT */;
/*!40101 SET @OLD_CHARACTER_SET_RESULTS=@@CHARACTER_SET_RESULTS */;
/*!40101 SET @OLD_COLLATION_CONNECTION=@@COLLATION_CONNECTION */;
/*!40101 SET NAMES utf8mb4 */;
/*!40103 SET @OLD_TIME_ZONE=@@TIME_ZONE */;
/*!40103 SET TIME_ZONE='+00:00' */;
/*!40014 SET @OLD_UNIQUE_CHECKS=@@UNIQUE_CHECKS, UNIQUE_CHECKS=0 */;
/*!40014 SET @OLD_FOREIGN_KEY_CHECKS=@@FOREIGN_KEY_CHECKS, FOREIGN_KEY_CHECKS=0 */;
/*!40101 SET @OLD_SQL_MODE=@@SQL_MODE, SQL_MODE='NO_AUTO_VALUE_ON_ZERO' */;
/*!40111 SET @OLD_SQL_NOTES=@@SQL_NOTES, SQL_NOTES=0 */;

--
-- Table structure for table `area_code_2024`
--

DROP TABLE IF EXISTS `area_code_2024`;
/*!40101 SET @saved_cs_client     = @@character_set_client */;
/*!40101 SET character_set_client = utf8 */;
CREATE TABLE `area_code_2024` (
  `code` bigint unsigned NOT NULL COMMENT '区划代码',
  `name` varchar(128) NOT NULL DEFAULT '' COMMENT '名称',
  `level` tinyint(1) NOT NULL COMMENT '级别1-5,省市县镇村',
  `pcode` bigint DEFAULT NULL COMMENT '父级区划代码',
  `category` int DEFAULT NULL COMMENT '城乡分类',
  PRIMARY KEY (`code`),
  KEY `name` (`name`),
  KEY `level` (`level`),
  KEY `pcode` (`pcode`)
) ENGINE=InnoDB DEFAULT CHARSET=utf8mb4 COLLATE=utf8mb4_0900_ai_ci;
/*!40101 SET character_set_client = @saved_cs_client */;

```

## 文件列表

- [area_code_2024.csv.gz](area_code_2024.csv.gz) 
  - MD5 (area_code_2024.csv.gz) = 81794067ccf4660d555f725c23bfec0f
- [area_code_2024.sql.gz](area_code_2024.sql.gz)
  - MD5 (area_code_2024.sql.gz) = ac8460cecf025e115c5b2a4ce8c5d1f3
- [area_code_2023.csv.gz](area_code_2023.csv.gz) 
  - MD5 (area_code_2023.csv.gz) = bd59582978111beeb70e9fb9a99d5630
- [area_code_2023.sql.gz](area_code_2023.sql.gz)
  - MD5 (area_code_2023.sql.gz) = 7a6c2499c430343ac8d1e19866d2e1d1
- [area_code_2010.csv.gz](area_code_2010.csv.gz) 
  - MD5 (area_code_2010.csv.gz) = caea79525da13ae341c176c2af0a12f5
- [area_code_2010.sql.gz](area_code_2010.sql.gz)
  - MD5 (area_code_2010.sql.gz) = c76bf44ca08f19cac6d0592375395f96
