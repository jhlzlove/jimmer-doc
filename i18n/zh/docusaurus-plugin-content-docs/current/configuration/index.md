# 配置篇

这个章节介绍Jimmer所支持的全局配置。

import { useCurrentSidebarCategory } from '@docusaurus/theme-common';
import DocCardList from '@theme/DocCardList';

<DocCardList items={useCurrentSidebarCategory().items}/>
