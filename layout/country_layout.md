{{ LAYOUT }}
name: CountryLayout
{{ /LAYOUT }}

{{ MODULE }}
    includeName: content1
{{ /MODULE }}

{{ MODULE }}
  moduleType: DocumentFilter
  moduleTitle: "Cities"
  documentFilter:
    filterType: NavigationFilter
    navigationType: childrenList
{{ /MODULE }}

{{ MODULE }}
    includeName: content2
{{ /MODULE }}