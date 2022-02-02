{{ DOC }}
title: "Fix database error"
key: TKT-2
keyName: TKT-2
ticketStatusKey: todo
type: Card
labels: 
  - database
  - error
{{ /DOC }}

{{ USE_LAYOUT }}
  name: IssueLayout
{{ /USE_LAYOUT }}

{{ LAYOUT_CONTENT name="content" }}

{{ MODULE }}
  moduleType: DocContent  
  moduleKey: labels    
  docContent:
    docContentType: LabelPublic
{{ /MODULE }}

{{ MODULE }}
  moduleType: Text
  moduleKey: description
  text:
    type: Markdown
  {{ TEXT }}
No data after:
```
drop * from users;
```
  {{ /TEXT }}
{{ /MODULE }}

{{ /LAYOUT_CONTENT }} 

