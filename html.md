# Expression of Multiplication, Plus...

```erb
<%= 2 * 2 %>
```

# If

```erb
<% if 1+1 == 2 %>
  <a>Correct!</a>
<% else %>
  <a>Wrong!</a>
<% end %>
```

# Each

```erb
<% ["A", "B", "C", "D"].each do |values| %>
  <%= values %>
<% end %>
```

```erb
<% @use_variables.each do |var| %>
  <%= var.data %>
<% end %>
```

# Datetime

```erb
<%= DateTime.now %>
```

