{{ LAYOUT }}
name: CityLayout
{{ /LAYOUT }}

{{ MODULE }}
    includeName: content
{{ /MODULE }}

{{ MODULE }}
  moduleType: DocumentFilter
  moduleTitle: "Other Cities:"
  documentFilter:
    filterType: DocumentReference
    referenceGroup: relatedCity
{{ /MODULE }}

{{ MODULE }}
  moduleType: DocumentFilter
  moduleTitle: "Country:"
  documentFilter:
    filterType: NavigationFilter
    navigationType: Parent
{{ /MODULE }}

{{ MODULE }}
  moduleType: DocumentFilter
  documentFilter:
    filterType: NavigationFilter
    navigationType: PrevNext
{{ /MODULE }}