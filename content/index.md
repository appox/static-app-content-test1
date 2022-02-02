{{ DOC }}
title: Static content test 1
type: NewsChannel
key: root
variation: ContentProject
references:
    - 
      documentKey: berlin     
      group: capitalCity
    - 
      documentKey: paris     
      group: capitalCity      
    - 
      documentKey: rome     
      group: capitalCity            
    - 
      documentKey: madrid     
      group: capitalCity         
    - 
      documentKey: barcelona     
      group: featureCity         
    - 
      documentKey: hamburg     
      group: featureCity                        
{{ /DOC }}

{{ GROUP }}
  moduleType: Group
  moduleLayoutId: tip
    {{ MODULE }}
      moduleType: Text
      text:
        type: Markdown
      {{ TEXT }}
      This is a _static content_ *Demo* app. 
      The documents are saved in a git repository and rendered in the app.
      {{ /TEXT }}
    {{ /MODULE }}
{{ /GROUP }}

Sem viverra aliquet eget sit. Velit laoreet id donec ultrices. In hac habitasse platea dictumst quisque sagittis purus sit. Feugiat sed lectus vestibulum mattis. Mauris ultrices eros in cursus turpis massa tincidunt. 2

{{ MODULE }}
  moduleType: DocumentFilter
  moduleLayoutId: scroll
  moduleTitle: "Capital Cities:"
  documentFilter:
    filterType: DocumentReference
    referenceGroup: capitalCity
{{ /MODULE }}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

{{ MODULE }}
  moduleType: DocumentFilter
  moduleLayoutId: scroll
  moduleTitle: "top Cities:"
  documentFilter:
    filterType: DocumentReference
    referenceGroup: featureCity
{{ /MODULE }}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Mollis nunc sed id semper risus. Dui ut ornare lectus sit. Mauris cursus mattis molestie a iaculis. Arcu non odio euismod lacinia at quis risus. Accumsan tortor posuere ac ut. Amet risus nullam eget felis eget nunc lobortis mattis aliquam. Lobortis elementum nibh tellus molestie nunc non blandit massa. 

{{ MODULE }}
  moduleType: DocumentFilter
  moduleTitle: "Countries"
  documentFilter:
    filterType: NavigationFilter
    navigationType: childrenList
{{ /MODULE }}


