<% tp.date.now("YYYY-MM-DD HH:mm") %>

## Overdue
```tasks
not done
due before today
```

## Due Today
```tasks
((not done) AND (due today))
```

## Due This Week
```tasks
not done
(due after today) AND (due before next monday)
short mode
hide edit button
hide backlink
```

## Task Log
\```tasks
\```


## Related Links


## Recurring
\```tasks
- [ ] write todo list 📅 <% tp.date.now("YYYY-MM-DD") %>
- [ ] daily journal 📅 <% tp.date.now("YYYY-MM-DD") %>
- [ ] duolingo 📅 <% tp.date.now("YYYY-MM-DD") %>
- [ ] ADD_YOUR_OWN 📅 <% tp.date.now("YYYY-MM-DD") %>
``

## Completed Today
```tasks
done today
```

## Due This Month
```tasks
not done
(due after next sunday) AND (due before next month)
short mode
hide edit button
hide backlink
```

## Due This Year
```tasks
not done
(due after this month) AND (due before next year)
short mode
hide edit button
hide backlink
```

## Due Later
```tasks
not done
due after this year
short mode
hide edit button
hide backlink
```
