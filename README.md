# Strip Log

Strip Log Control for Minecraft 1.21

### How to use
**Strip**
```mcfunction
# set coordinate
    data modify storage strip_log:input _.from set value "~ ~ ~"
    data modify storage strip_log:input _.to set value "~ ~ ~"

# strip
    function strip_log:util/1.strip
```
**Unstrip**
```mcfunction
# set coordinate
    data modify storage strip_log:input _.from set value "~ ~ ~"
    data modify storage strip_log:input _.to set value "~ ~ ~"

# unstrip
    function strip_log:util/2.unstrip
```

### Features
**Function**
- `strip_log:util/1.strip`
- `strip_log:util/2.unstrip`

**Block Tag**
- `strip_log:stripable`
- `strip_log:stripped`
