# Function: <code>commands_show</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t commands_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "commands_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584705952,
      "name": "commands_show",
      "external": false,
      "loc": "drivers/nvdimm/core.c:246",
      "file": "drivers/nvdimm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584712784,
      "name": "commands_show",
      "external": false,
      "loc": "drivers/nvdimm/dimm_devs.c:274",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584705952,
      "name": "commands_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 222
    },
    {
      "addr": 18446744071584712784,
      "name": "commands_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t commands_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "commands_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585053632,
      "name": "commands_show",
      "external": false,
      "loc": "drivers/nvdimm/core.c:349",
      "file": "drivers/nvdimm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585063808,
      "name": "commands_show",
      "external": false,
      "loc": "drivers/nvdimm/dimm_devs.c:280",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585053632,
      "name": "commands_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
    },
    {
      "addr": 18446744071585063808,
      "name": "commands_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 255
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t commands_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "commands_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585236912,
      "name": "commands_show",
      "external": false,
      "loc": "drivers/nvdimm/core.c:320",
      "file": "drivers/nvdimm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585248192,
      "name": "commands_show",
      "external": false,
      "loc": "drivers/nvdimm/dimm_devs.c:295",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585236912,
      "name": "commands_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
    },
    {
      "addr": 18446744071585248192,
      "name": "commands_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 255
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t commands_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "commands_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585318384,
      "name": "commands_show",
      "external": false,
      "loc": "drivers/nvdimm/core.c:320",
      "file": "drivers/nvdimm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585330272,
      "name": "commands_show",
      "external": false,
      "loc": "drivers/nvdimm/dimm_devs.c:311",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585318384,
      "name": "commands_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
    },
    {
      "addr": 18446744071585330272,
      "name": "commands_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 257
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t commands_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "commands_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585747568,
      "name": "commands_show",
      "external": false,
      "loc": "drivers/nvdimm/core.c:320",
      "file": "drivers/nvdimm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585758272,
      "name": "commands_show",
      "external": false,
      "loc": "drivers/nvdimm/dimm_devs.c:318",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585747568,
      "name": "commands_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
    },
    {
      "addr": 18446744071585758272,
      "name": "commands_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 257
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t commands_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "commands_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585993632,
      "name": "commands_show",
      "external": false,
      "loc": "drivers/nvdimm/core.c:320",
      "file": "drivers/nvdimm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586004384,
      "name": "commands_show",
      "external": false,
      "loc": "drivers/nvdimm/dimm_devs.c:319",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585993632,
      "name": "commands_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 177
    },
    {
      "addr": 18446744071586004384,
      "name": "commands_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t commands_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "commands_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586130496,
      "name": "commands_show",
      "external": false,
      "loc": "drivers/nvdimm/core.c:320",
      "file": "drivers/nvdimm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586141808,
      "name": "commands_show",
      "external": false,
      "loc": "drivers/nvdimm/dimm_devs.c:307",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586130496,
      "name": "commands_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
    },
    {
      "addr": 18446744071586141808,
      "name": "commands_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
ssize_t commands_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "commands_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586365360,
      "name": "commands_show",
      "external": false,
      "loc": "drivers/nvdimm/core.c:312",
      "file": "drivers/nvdimm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586377472,
      "name": "commands_show",
      "external": false,
      "loc": "drivers/nvdimm/dimm_devs.c:304",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586365360,
      "name": "commands_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 161
    },
    {
      "addr": 18446744071586377424,
      "name": "commands_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 207
    },
    {
      "addr": 18446744071586382102,
      "name": "commands_show.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t commands_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "commands_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586513408,
      "name": "commands_show",
      "external": false,
      "loc": "drivers/nvdimm/core.c:312",
      "file": "drivers/nvdimm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586525728,
      "name": "commands_show",
      "external": false,
      "loc": "drivers/nvdimm/dimm_devs.c:304",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586513408,
      "name": "commands_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 161
    },
    {
      "addr": 18446744071586525728,
      "name": "commands_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t commands_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "commands_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587293424,
      "name": "commands_show",
      "external": false,
      "loc": "drivers/nvdimm/core.c:312",
      "file": "drivers/nvdimm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587307136,
      "name": "commands_show",
      "external": false,
      "loc": "drivers/nvdimm/dimm_devs.c:294",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587293424,
      "name": "commands_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 161
    },
    {
      "addr": 18446744071587307136,
      "name": "commands_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t commands_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "commands_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587353696,
      "name": "commands_show",
      "external": false,
      "loc": "drivers/nvdimm/core.c:312",
      "file": "drivers/nvdimm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587369504,
      "name": "commands_show",
      "external": false,
      "loc": "drivers/nvdimm/dimm_devs.c:294",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587353696,
      "name": "commands_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 161
    },
    {
      "addr": 18446744071587369504,
      "name": "commands_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t commands_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "commands_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587235984,
      "name": "commands_show",
      "external": false,
      "loc": "drivers/nvdimm/core.c:312",
      "file": "drivers/nvdimm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587251488,
      "name": "commands_show",
      "external": false,
      "loc": "drivers/nvdimm/dimm_devs.c:294",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587235984,
      "name": "commands_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 195
    },
    {
      "addr": 18446744071587251488,
      "name": "commands_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t commands_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "commands_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587802256,
      "name": "commands_show",
      "external": false,
      "loc": "drivers/nvdimm/core.c:312",
      "file": "drivers/nvdimm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587817120,
      "name": "commands_show",
      "external": false,
      "loc": "drivers/nvdimm/dimm_devs.c:294",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587802256,
      "name": "commands_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 195
    },
    {
      "addr": 18446744071587817120,
      "name": "commands_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t commands_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "commands_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589151680,
      "name": "commands_show",
      "external": false,
      "loc": "drivers/nvdimm/core.c:281",
      "file": "drivers/nvdimm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589166336,
      "name": "commands_show",
      "external": false,
      "loc": "drivers/nvdimm/dimm_devs.c:274",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589151680,
      "name": "commands_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
    },
    {
      "addr": 18446744071589166336,
      "name": "commands_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 265
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t commands_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "commands_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590702096,
      "name": "commands_show",
      "external": false,
      "loc": "drivers/nvdimm/core.c:281",
      "file": "drivers/nvdimm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590718368,
      "name": "commands_show",
      "external": false,
      "loc": "drivers/nvdimm/dimm_devs.c:274",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590702096,
      "name": "commands_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 181
    },
    {
      "addr": 18446744071590718368,
      "name": "commands_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t commands_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "commands_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591043168,
      "name": "commands_show",
      "external": false,
      "loc": "drivers/nvdimm/core.c:281",
      "file": "drivers/nvdimm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591059536,
      "name": "commands_show",
      "external": false,
      "loc": "drivers/nvdimm/dimm_devs.c:274",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591043168,
      "name": "commands_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 181
    },
    {
      "addr": 18446744071591059536,
      "name": "commands_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t commands_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "commands_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591387632,
      "name": "commands_show",
      "external": false,
      "loc": "drivers/nvdimm/core.c:281",
      "file": "drivers/nvdimm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591404240,
      "name": "commands_show",
      "external": false,
      "loc": "drivers/nvdimm/dimm_devs.c:276",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591387632,
      "name": "commands_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 181
    },
    {
      "addr": 18446744071591404240,
      "name": "commands_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
    }
  ]
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t commands_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "commands_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336499397208,
      "name": "commands_show",
      "external": false,
      "loc": "drivers/nvdimm/core.c:312",
      "file": "drivers/nvdimm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336499411640,
      "name": "commands_show",
      "external": false,
      "loc": "drivers/nvdimm/dimm_devs.c:304",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499397208,
      "name": "commands_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 268
    },
    {
      "addr": 18446603336499411640,
      "name": "commands_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 288
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Collision ❓</summary>

```c
ssize_t commands_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "commands_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292635008,
      "name": "commands_show",
      "external": false,
      "loc": "drivers/nvdimm/core.c:312",
      "file": "drivers/nvdimm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055292651696,
      "name": "commands_show",
      "external": false,
      "loc": "drivers/nvdimm/dimm_devs.c:304",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292635008,
      "name": "commands_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 352
    },
    {
      "addr": 13835058055292651696,
      "name": "commands_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 344
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t commands_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "commands_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276628786,
      "name": "commands_show",
      "external": false,
      "loc": "drivers/nvdimm/core.c:312",
      "file": "drivers/nvdimm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936276640740,
      "name": "commands_show",
      "external": false,
      "loc": "drivers/nvdimm/dimm_devs.c:304",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276628786,
      "name": "commands_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
    },
    {
      "addr": 18446743936276640740,
      "name": "commands_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 256
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t commands_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "commands_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586203888,
      "name": "commands_show",
      "external": false,
      "loc": "drivers/nvdimm/core.c:312",
      "file": "drivers/nvdimm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586216208,
      "name": "commands_show",
      "external": false,
      "loc": "drivers/nvdimm/dimm_devs.c:304",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586203888,
      "name": "commands_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 161
    },
    {
      "addr": 18446744071586216208,
      "name": "commands_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t commands_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "commands_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586022256,
      "name": "commands_show",
      "external": false,
      "loc": "drivers/nvdimm/core.c:312",
      "file": "drivers/nvdimm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586034576,
      "name": "commands_show",
      "external": false,
      "loc": "drivers/nvdimm/dimm_devs.c:304",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586022256,
      "name": "commands_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 161
    },
    {
      "addr": 18446744071586034576,
      "name": "commands_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t commands_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "commands_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586461376,
      "name": "commands_show",
      "external": false,
      "loc": "drivers/nvdimm/core.c:312",
      "file": "drivers/nvdimm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586473696,
      "name": "commands_show",
      "external": false,
      "loc": "drivers/nvdimm/dimm_devs.c:304",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586461376,
      "name": "commands_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 161
    },
    {
      "addr": 18446744071586473696,
      "name": "commands_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Collision, Selective Inline ❓</summary>

```c
ssize_t commands_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "commands_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586573072,
      "name": "commands_show",
      "external": false,
      "loc": "drivers/nvdimm/core.c:312",
      "file": "drivers/nvdimm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586585376,
      "name": "commands_show",
      "external": false,
      "loc": "drivers/nvdimm/dimm_devs.c:304",
      "file": "drivers/nvdimm/dimm_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586573072,
      "name": "commands_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 161
    },
    {
      "addr": 18446744071586585376,
      "name": "commands_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
    }
  ]
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
ssize_t commands_show(struct device * dev, struct device_attribute * attr, char * buf)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
