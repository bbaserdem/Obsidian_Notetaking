---
creation date: <% tp.file.creation_date() %>
modification date: <% tp.file.last_modified_date("dddd Do MMMM YYYY HH:mm:ss") %>
tags:
  - dailynote
---

 - [[<% tp.date.now("YYYY_MM_DD", -1) %>|Yesterday]]
 - [[<% tp.date.now("YYYY_MM_DD", +1) %>|Tomorrow]]

### High Priority Tasks

```tasks
priority is high
not done
```

### Pending Tasks

```tasks
priority is not high
not done
```

## New Tasks

- [ ] 

## Other Notes

## Tasks Completed

```tasks
done on {{date:YYYY-MM-DD}}
```
