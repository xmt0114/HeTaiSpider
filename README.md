# HeTaiSpider
a spider for HeTai company to collect info

## home page : https://sf.taobao.com/item_list.htm

## full url : *https://sf.taobao.com/%category%__%sorder%.htm?auction_start_seg=-1&province=&city=&location_code=&sorder=&auction_start_from=&auction_start_to=&page=*
---
## params : 
- category
  - 50025969 -- 房产
  - 50025970 -- 土地
        
- auction_start_seg=-1

- page       -- 页码

- sorder 
  - -1        -- 不限
  - 0         -- 正在进行
  - 1         -- 即将开始
  - 2         -- 已结束
  - 3         -- 中止
  - 4         -- 撤回
       
- province =         -- 省
- city =             -- 市
- location_code =    -- 区域代码（从哪获取？）

- auction_start_from=yyyy-mm-dd
- auction_start_to=yyyy-mm-dd
