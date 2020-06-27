# BNS Data Web

Blade & Soul: Item Database Website & Tools (ChineseT, Mainly for TW Server)

## Website

> [https://dbnryanc92.github.io/BNSDataWeb/](https://dbnryanc92.github.io/BNSDataWeb/)

## Contributors

* **dbnryanc92** - *Website / Data* - [dbnryanc92](https://github.com/dbnryanc92)

## URL Queries

1. **class & style**
	- Format: class=[classAbbr] / class=[classAbbr]-[styleNo]
	- classAbbr: [bm, kfm, fm, des, sin, sum, bd, wl, sf, gun, wd, arc]
	- styleNo: [1, 2, 3]
	- e.g. class=sum / class=bm-3
    
2. **item**
	- Format: item=[itemID] (-[lv]) (-[relicLv]) (-[varNo])
	- Dictionary of itemID will be documented later
	- Optional parameters (in square brackets) can be skipped, default values will be applied to empty fields
	- e.g. item=weapon21 / item=weapon21-6-12

3. **cate**
	- Format: cate=[cateID1] (-[cateID2]) ... (-[cateIDN])
	- Dictionary of cateID will be documented later
	- If multiple cateID is provided, all items satisfying AT LEAST 1 category will be displayed
	- e.g. cate=weapon / cate=gem-petgem

4. **page**
	- Format: page=[pageName]
	- pageName: [Unity, ToolAuction, ToolStatsCurve, About], etc.
	- e.g. page=Unity

5. **search**
	- Format: search=[searchText]
	- e.g. search=雪風

Multiple queries can be used together

- Group 1: **class**
- Group 2: **item** > **cate** > **page** > **search**

At most one can be used in each group, if more than one is used, the one with highest priority will be applied

## Disclaimer

Some resources in the website are owned by NCSOFT.
