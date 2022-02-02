{{ DOC }}
title: "Test Board 1"
type: Board
icon: 
  asset: team/icon.png
ticketStatusMapping:
  list:
    - todo
    - wip
    - done
  workflow:   
    todo:
      next:
        - wip
filterInfo:         
  assignedFilter:
    - errorLabelFilter 
    - featureLabelFilter 
  filterGroup: board        
{{ /DOC }}

{{ USE_LAYOUT }}
  name: BoardLayout
{{ /USE_LAYOUT }}

{{ LAYOUT_CONTENT name="content" }}
## Board content page - Sichtbar?

 * TODO: Columns mit TicketStatusList aufbauen.

{{ /LAYOUT_CONTENT }} 

