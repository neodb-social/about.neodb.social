---
title: "NeoDB API"
date: 2022-07-09T15:12:01-04:00
draft: false
---

开发者目前可以通过 `https://neodb.social/search.json/?c=book&q=9787544720779` 这个简版API搜索获取NeoDB的数据。c参数可以是 `movie` `book` `music` `game` 之一；暂不支持分字段搜索。

```
$ curl 'https://neodb.social/search.json/?c=book&q=9787544720779' | jq .
{
  "num_pages": 1,
  "items": [
    {
      "subtitle": "",
      "original_title": "Between Past and Future",
      "author": [
        "[美] 汉娜·阿伦特"
      ],
      "translator": [
        "王寅丽",
        "张立立"
      ],
      "publisher": "译林出版社",
      "publish_year": 2011,
      "publish_month": 11,
      "language": "",
      "isbn": "9787544720779",
      "title": "过去与未来之间",
      "brief": "阿伦特的笔下勾勒出现代社会面临的一个紧迫危机：政治学中，诸如正义、理性、责任、德性、荣誉等传统关键词的意义失落，及其带来的后果。通过八篇随笔，她再一次提炼出传统概念中至关重要的精华，以此来评估我们现代人当前所处的位置，重新获致观照未来的框架。\n阿伦特对政治本质的分析，体现出让人耳目一新的原创性和洞察力；在历史上没有任何一个政治哲学家，像他那样给与政治生活的现象学如此多的关注。——比库·帕勒克",
      "rating": "10.0",
      "url": "https://neodb.social/books/273773/",
      "cover_url": "https://neodb.social/media/book/2021/12/12d5d76bb4-5178-456a-98e9-9d2ab3f3eebe.jpg",
      "top_tags": [],
      "category_name": "书籍",
      "other_info": {
        "丛书": "人文与社会译丛"
      }
    },
    {
      "subtitle": "",
      "original_title": "",
      "author": [
        "阿伦特"
      ],
      "translator": [],
      "publisher": "译林出版社",
      "publish_year": 2011,
      "publish_month": null,
      "language": "zh",
      "isbn": "9787544720779",
      "title": "过去与未来之间",
      "brief": "本书作者以其最深沉而动人的笔触, 迫切又独特的情怀, 阐释了政治学的经典意蕴.内容包括: 传统与现代, 历史概念, 何为权威, 何为自由, 教育的危机, 对太空的征服以及人的地位等.",
      "rating": null,
      "url": "https://neodb.social/books/226769/",
      "cover_url": "https://neodb.social/media/book/default.svg",
      "top_tags": [],
      "category_name": "书籍",
      "other_info": null
    }
  ]
}
```

NeoDB会在未来增加完整的API支持。
