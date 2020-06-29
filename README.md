# BNSDataWeb (劍靈蜂窩 / 劍靈裝備資料庫)

Blade & Soul: Item Database Website & Tools (ChineseT, Mainly for TW Server)
劍靈：裝備資料庫及其他工具（繁體中文，主要為台服設計）

## Website URL

> https://bnshive.com/
> ~~https://bnsdataweb.web.app/~~
> ~~https://dbnryanc92.github.io/BNSDataWeb/~~

## Contributors

* **dbnryanc92** - *Website / Data* - [GitHub: dbnryanc92](https://github.com/dbnryanc92)


## URL Queries

> Example: https://bnshive.com/?class=sum&item=weapon21

Multiple queries can be used. If more than 1 query from each group is used, highest priority one will apply.

- Group 1: **class**
- Group 2: **item** > **cate** > **page** > **search**

1. **class**
    - Format: **class=<classAbbr>** or **class=<classAbbr>-<styleNo>**
    - classAbbr: [bm, kfm, fm, des, sin, sum, bd, wl, sf, gun, wd, arc, td]
    - styleNo: [1, 2, 3]
    - e.g. class=sum / class=bm-3
    
2. **item**
    - Format: **item=<itemID>(-<lv>)(-<relicLv>)(-<varNo>)**
    - Dictionary of *itemID* will be documented later
    - Parameters in parentheses are **optional**, default values will be applied to unspecified fields
    - e.g. item=weapon21 / item=weapon21-6-12

3. **cate**
    - Format: **cate=<cateID1>(-<cateID2>)...(-<cateIDN>)**
    - Dictionary of *cateID* will be documented later
    - If multiple *cateID* is provided, all items satisfying at least 1 category will be displayed
    - e.g. cate=weapon / cate=gem-petgem

4. **page**
    - Format: **page=<pageName>**
    - pageName: [Unity, ToolAuction, ToolStatsCurve, About], etc.
    - e.g. page=Unity

5. **search**
    - Format: **search=<searchText>**
    - e.g. search=雪風

## Disclaimer

Some resources in the website are owned by NCSOFT.