# Note: Don't directly view files under this directory, please view [english documentation](https://babyfish-ct.github.io/jimmer-doc/)
# 注意：不要直接访问本目录下的文件，请查看[中文文档](https://babyfish-ct.github.io/jimmer-doc/zh)


## npm

```bash
npm i
# 启动
npm run start

# 启动中文
npm run start:zh
```

## yarn

```bash
yarn i
# 启动
yarn start:zh
```

## 备注

`_category_.yml` 中的 `position` 控制该目录在 sidebar 的顺序，link type 为 doc 时，点击目录列表时显示该文件夹内 index 的 MD/MDX 文件内容，具体的文章使用序号排序。

总之，目录排序采用 `_category_.yml` 控制（同一层级目录有效，和子目录中配置相互独立），文章排序使用 `数字-文章名称` 控制。

这样每篇文章内部可以直接使用 md 的语法而无需采用 frontmatter 元数据定义，可以帮助我们快速开启新文章，减少排序的工作量。
