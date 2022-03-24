# 这些年身入其中或主导的项目

### 参与品牌形象重塑与升级

- 明牌珠宝
- 卡利罗银器
- 经历万隆珠宝到曼卡龙珠宝
- SEO sitemap.
- Use `/commits/master.atom` of source repository for RSS.
- `application/git+http` rel tag.
6. Use [Primer] Jekyll theme, which is the default theme for GitHub Pages

[Primer]: https://github.com/pages-themes/primer

### 转型期的品牌策略与基础形象

1. 西安古丽兰珠宝

2. 万帝珠宝

    ```
    url: your-username.github.io
    title: your-site-title
    ```

3. (optional) Add a `favicon.ico` file.


6. Commit changes and push.

[weakish/micro-gh-page]: https://github.com/weakish/micro-gh-page

### 从0到1的项目

德诚珠宝集团之"因美优品"；"00:59临时"

Key to beauty时尚手串产品品牌”TROII窍“ 
Preview locally:

```sh
bundle exec jekyll serve
```

### 产品概念发掘

不是吉娃娃，明牌珠宝之”喆娃娃“系列
”再不U惑，就不惑了“，古丽兰珠宝之”U惑“
"Unique U"，独特的你
”我的自钻“


To deploy to [ZeroNet], just add a new config file, e.g. `_zeronet.yml`, to override the `site.url` variable:

```yaml
url: /YOUR_ZERONET_SITE_ADDRESS
```

Then build the site with:

```sh
bundle exec jekyll build --config _config.yml,_zeronet.yml -d PATH_TO_ZERONET/data/YOUR_ZERONET_SITE_ADDRESS
```

Afterwards you can sign and publish your zeronet site:

```sh
zeronet.py siteSign YOUR_ZERONET_SITE_ADDRESS
zeronet.py sitePublish YOUR_ZERONET_SITE_ADDRESS
```

You can also sign and publish your site via the zero panel in the browser.

[ZeroNet]: https://zeronet.io/

## 相关站点

- [意识碗](https://consciousnessbowl.com/)
- [读与未读](https://readunread.cn/)
