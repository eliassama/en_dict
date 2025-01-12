# 数据介绍

这里的数据是从 [github.com/kajweb/dict](https://github.com/kajweb/dict) 的数据中，二次清洗后得到的。

去除了全部短语，只保留单词数据。并针对每个单词的数据做了一些处理。

总共有 21581 个单词的数据。

# 组成介绍

每个单词是一个目录，一个目录下有三个文件，分别是：
1. info.json: 单词简化+处理后的详细信息
2. uk.mpga: 英式发音文件
3. us.mpga: 美式发音文件


# info.json 组成

以 info.json 为例介绍大致结构

```json
{
    "word": "tea", // 单词 
    "ipa": {
        "us": "tiː", // 美式音标
        "uk": "tiː"  // 英式音标
    },
    "sentences": [ // 例句，所有单词都存在
        {
            "en": "...a box of tea.",
            "cn": "…一盒茶叶。"
        },
        {
            "en": "...a cup of tea.",
            "cn": "…一杯茶。"
        },
        {
            "en": "All he wanted was a cup of tea and a sit-down.",
            "cn": "他只求一杯清茶、片刻小憩。"
        },
        {
            "en": "At tea-time, Victoria sang duets with her Consort, Prince Albert.",
            "cn": "喝下午茶的时候，维多利亚与其夫君艾伯特亲王表演了二重唱。"
        },
        {
            "en": "Do you take milk and sugar in your tea?",
            "cn": "你的茶里面要放牛奶和糖吗？"
        },
        {
            "en": "He started working for a gallery sweeping up and making the tea.",
            "cn": "他开始在画廊做扫地沏茶的工作。"
        },
        {
            "en": "I don't rant and rave or throw tea cups.",
            "cn": "我不会大喊大叫或摔茶杯。"
        },
        {
            "en": "I drank a cup of tea that tasted of diesel.",
            "cn": "我喝了杯有股柴油味的茶。"
        },
        {
            "en": "I should like to have a good tea.",
            "cn": "我想吃一顿好茶点。"
        },
        {
            "en": "I’d like two teas and a piece of chocolate cake, please.",
            "cn": "我想要两杯茶和一块巧克力蛋糕。"
        },
        {
            "en": "I'll make the tea and you pop off for a while.",
            "cn": "我来备茶，你去歇一会儿吧。"
        },
        {
            "en": "I'll put on the kettle for tea. Or boil up some coffee.",
            "cn": "我要烧壶水沏茶，或者煮些咖啡。"
        },
        {
            "en": "One import that comes into England is tea.",
            "cn": "茶叶是输入英国的商品之一。"
        },
        {
            "en": "She accidentally knocked the tea tin off the shelf.",
            "cn": "她不小心把架子上的茶叶罐碰了下来。"
        },
        {
            "en": "She put a cup of tea down on the bedside table.",
            "cn": "她在床头柜上放了一杯茶。"
        },
        {
            "en": "She swung around to him, spilling her tea without noticing it.",
            "cn": "她一下子转身面向他，茶水溅了出来都没注意到。"
        },
        {
            "en": "The tea was sweetened with a hoarded tin of condensed milk.",
            "cn": "用贮藏的一罐炼乳为茶添加了甜味。"
        },
        {
            "en": "They had their coffee and tea on the veranda.",
            "cn": "他们在阳台上喝咖啡和茶。"
        },
        {
            "en": "We could all do with a cup of tea.",
            "cn": "要是能给我们都来杯茶就好了。"
        },
        {
            "en": "Well then, I'll put the kettle on and make us some tea.",
            "cn": "好吧，我来烧壶水，我们沏点茶喝。"
        },
        {
            "en": "When I drink tea, my glasses mist over.",
            "cn": "我喝茶时眼镜片上会蒙上一层水汽。"
        },
        {
            "en": "While he was gone she had tea with the Colonel.",
            "cn": "他不在时她跟上校一起喝了茶。"
        },
        {
            "en": "Would you like a cup of tea or coffee?",
            "cn": "你想来一杯茶还是咖啡？"
        }
    ],
    "rel_words": [ // 同根词，部分单词为空

    ],
    "synos": [ // 近义词，部分单词为空
        {
            "pos": "n",
            "words": [
                {
                    "words": [
                        "tealeaf",
                        "refreshments"
                    ],
                    "tran_cn": "茶叶；茶树；茶点"
                }
            ]
        }
    ],
    "phrases": [ // 短语，部分单词为空
        {
            "phrase": "afternoon tea",
            "tran_cn": "下午茶"
        },
        {
            "phrase": "black tea",
            "tran_cn": "红茶"
        },
        {
            "phrase": "china tea",
            "tran_cn": "中国茶"
        },
        {
            "phrase": "chinese tea",
            "tran_cn": "中国茶，国内名茶"
        },
        {
            "phrase": "cup of tea",
            "tran_cn": "n. 命运；心爱之人或物"
        },
        {
            "phrase": "drink tea",
            "tran_cn": "喝茶"
        },
        {
            "phrase": "green tea",
            "tran_cn": "绿茶"
        },
        {
            "phrase": "hot tea",
            "tran_cn": "热茶"
        },
        {
            "phrase": "jasmine tea",
            "tran_cn": "茉莉花茶；香片"
        },
        {
            "phrase": "make tea",
            "tran_cn": "泡茶，沏茶"
        },
        {
            "phrase": "milk tea",
            "tran_cn": "奶茶"
        },
        {
            "phrase": "not for all the tea in China",
            "tran_cn": "(非正式)无论如何都不"
        },
        {
            "phrase": "oolong tea",
            "tran_cn": "乌龙茶"
        },
        {
            "phrase": "strong tea",
            "tran_cn": "浓茶"
        },
        {
            "phrase": "tea and coffee",
            "tran_cn": "清茶和咖啡"
        },
        {
            "phrase": "tea and sympathy",
            "tran_cn": "(非正式)安慰与同情"
        },
        {
            "phrase": "tea house",
            "tran_cn": "茶馆；茶楼"
        },
        {
            "phrase": "tea leaf",
            "tran_cn": "茶叶"
        },
        {
            "phrase": "tea party",
            "tran_cn": "茶话会"
        },
        {
            "phrase": "tea set",
            "tran_cn": "茶具"
        },
        {
            "phrase": "tea table",
            "tran_cn": "茶几；茶桌"
        },
        {
            "phrase": "tea tree",
            "tran_cn": "茶树，茶树精油"
        }
    ],
    "trans": [ // 翻译，所有单词都有。含中英文翻译，注意翻译内容有部分重复。部分不存在英文翻译。
        {
            "pos": "n",
            "tran_cn": "茶水，茶，茶树，午后小吃",
            "tran_en": "a hot brown drink made by pouring boiling water onto the dried leaves from a particular Asian bush, or a cup of this drink"
        },
        {
            "pos": "other",
            "tran_cn": "茶",
            "tran_en": "a hot drink made by pouring boiling water onto leaves or flowers, sometimes used as a medicine"
        },
        {
            "pos": "vi",
            "tran_cn": "喝茶；进茶点"
        },
        {
            "pos": "vt",
            "tran_cn": "给…沏茶"
        }
    ],
    "exchange": { // 变形词，部分单词有
        "pl": [
            "teas"
        ]
    }
}
```

## rel_words 示例

以单词 cheeseburger 为例：
```json
// 单词 cheeseburger 的 rel_words

[
  {
    "pos": "adj",
    "words": [
      {
        "word": "cheese",
        "tran_cn": " 叛变的；胆小的"
      },
      {
        "word": "cheesy",
        "tran_cn": " 干酪质的；下等的；漂亮的"
      }
    ]
  },
  {
    "pos": "n",
    "words": [
      {
        "word": "cheese",
        "tran_cn": " [食品] 奶酪；干酪；要人"
      },
      {
        "word": "cheesemonger",
        "tran_cn": " 干酪商，干酪店"
      }
    ]
  },
  {
    "pos": "vt",
    "words": [
      {
        "word": "cheese",
        "tran_cn": " 停止"
      }
    ]
  }
]
```

## exchange 示例

```json
// 单词 tender 的 exchange
{
  "pl": [ // 复数
    "tenders"
  ],
  "third": [ // 第三人称单数
    "tenders"
  ],
  "past": [ // 过去式
    "tendered"
  ],
  "done": [ // 过去分词
    "tendered"
  ],
  "ing": [ // 现在分词
    "tendering"
  ],
  "er": [ // 比较级形式
    "tenderer"
  ],
  "est": [ // 最高级形式
    "tenderest"
  ],
  "adv": [ // 副词
    "tenderly"
  ],
  "noun": [ // 名词
    "tenderness"
  ]
}

```
