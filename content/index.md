{{ DOC }}
title: Static content test 1
type: NewsChannel
key: root
variation: ContentProject
{{ /DOC }}

{{ USE_LAYOUT }}
  name: DemoLayout
{{ /USE_LAYOUT }}

{{ LAYOUT_CONTENT name="content" }}

## Documents (1)
{{ MODULE }}
  moduleType: DocumentFilter
  documentFilter:
    filterType: NavigationFilter
    navigationType: childrenList
{{ /MODULE }}

{{ /LAYOUT_CONTENT }} 

