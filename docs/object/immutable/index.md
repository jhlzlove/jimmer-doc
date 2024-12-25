# Immutability

Immutability is used to ensure that the data structure represented by Jimmer objects never contains circular references.

import { useCurrentSidebarCategory } from '@docusaurus/theme-common';
import DocCardList from '@theme/DocCardList';

<DocCardList items={useCurrentSidebarCategory().items}/>