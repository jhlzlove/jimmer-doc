# 资源篇

import { useCurrentSidebarCategory } from '@docusaurus/theme-common';
import DocCardList from '@theme/DocCardList';

<DocCardList items={useCurrentSidebarCategory().items}/>