# shopify

## RSS Feed
要使用ADP置顶，DeepLink调用Handle\
正面代码（2处）：\
```<g:custom_label_4>{{ product.metafields.mm-google-shopping.custom_label_4 }}</g:custom_label_4>```\
替换为：\
```<g:custom_label_4>{{ product.handle }}</g:custom_label_4>```\
