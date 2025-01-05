# TooltipBuilder

A library that provides a fluent interface to the GameTooltip APIs, making it easier to manage tooltip lines and customize their appearance.

#### Dependencies: [LibStub](https://www.curseforge.com/wow/addons/libstub), [Contracts](https://github.com/Eyal-WowHub/Contracts)

### Examples:

```lua
local Tooltip = LibStub("TooltipBuilder-1.0")
```

1. Build a single line tooltip.
```lua
Tooltip
    :SetLine("Hello from TooltipBuilder")
    :SetPlayerClassColor()
    :ToLine()
```

2. Build a double line tooltip.
```lua
Tooltip
    :SetLine("Hello")
    :SetWhiteColor()
    :SetLine("TooltipBuilder")
    :SetPlayerClassColor()
    :ToLine()
```







