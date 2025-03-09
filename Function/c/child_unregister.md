# Function: <code>child_unregister</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Collision ❓</summary>

```c
int child_unregister(struct device * dev, void * data)
```

```json
{
  "name": "child_unregister",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584705712,
      "name": "child_unregister",
      "external": false,
      "loc": "drivers/nvdimm/core.c:362",
      "file": "drivers/nvdimm/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584722064,
      "name": "child_unregister",
      "external": false,
      "loc": "drivers/nvdimm/region.c:74",
      "file": "drivers/nvdimm/region.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584705712,
      "name": "child_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071584722064,
      "name": "child_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
int child_unregister(struct device * dev, void * data)
```

```json
{
  "name": "child_unregister",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585058224,
      "name": "child_unregister",
      "external": false,
      "loc": "drivers/nvdimm/bus.c:318",
      "file": "drivers/nvdimm/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585074384,
      "name": "child_unregister",
      "external": false,
      "loc": "drivers/nvdimm/region.c:75",
      "file": "drivers/nvdimm/region.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585058224,
      "name": "child_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071585074384,
      "name": "child_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
int child_unregister(struct device * dev, void * data)
```

```json
{
  "name": "child_unregister",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585242016,
      "name": "child_unregister",
      "external": false,
      "loc": "drivers/nvdimm/bus.c:320",
      "file": "drivers/nvdimm/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585259664,
      "name": "child_unregister",
      "external": false,
      "loc": "drivers/nvdimm/region.c:75",
      "file": "drivers/nvdimm/region.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585242016,
      "name": "child_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071585259664,
      "name": "child_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
int child_unregister(struct device * dev, void * data)
```

```json
{
  "name": "child_unregister",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585323920,
      "name": "child_unregister",
      "external": false,
      "loc": "drivers/nvdimm/bus.c:383",
      "file": "drivers/nvdimm/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585342816,
      "name": "child_unregister",
      "external": false,
      "loc": "drivers/nvdimm/region.c:91",
      "file": "drivers/nvdimm/region.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585323920,
      "name": "child_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071585342816,
      "name": "child_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
int child_unregister(struct device * dev, void * data)
```

```json
{
  "name": "child_unregister",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585751888,
      "name": "child_unregister",
      "external": false,
      "loc": "drivers/nvdimm/bus.c:383",
      "file": "drivers/nvdimm/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585771216,
      "name": "child_unregister",
      "external": false,
      "loc": "drivers/nvdimm/region.c:91",
      "file": "drivers/nvdimm/region.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585751888,
      "name": "child_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071585771216,
      "name": "child_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
int child_unregister(struct device * dev, void * data)
```

```json
{
  "name": "child_unregister",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585997888,
      "name": "child_unregister",
      "external": false,
      "loc": "drivers/nvdimm/bus.c:387",
      "file": "drivers/nvdimm/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586017952,
      "name": "child_unregister",
      "external": false,
      "loc": "drivers/nvdimm/region.c:91",
      "file": "drivers/nvdimm/region.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585997888,
      "name": "child_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    },
    {
      "addr": 18446744071586017952,
      "name": "child_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
int child_unregister(struct device * dev, void * data)
```

```json
{
  "name": "child_unregister",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586134848,
      "name": "child_unregister",
      "external": false,
      "loc": "drivers/nvdimm/bus.c:387",
      "file": "drivers/nvdimm/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586156912,
      "name": "child_unregister",
      "external": false,
      "loc": "drivers/nvdimm/region.c:91",
      "file": "drivers/nvdimm/region.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586134848,
      "name": "child_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 155
    },
    {
      "addr": 18446744071586156912,
      "name": "child_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int child_unregister(struct device * dev, void * data)
```

```json
{
  "name": "child_unregister",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586369264,
      "name": "child_unregister",
      "external": false,
      "loc": "drivers/nvdimm/bus.c:386",
      "file": "drivers/nvdimm/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586393088,
      "name": "child_unregister",
      "external": false,
      "loc": "drivers/nvdimm/region.c:83",
      "file": "drivers/nvdimm/region.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586369264,
      "name": "child_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    },
    {
      "addr": 18446744071586393088,
      "name": "child_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
int child_unregister(struct device * dev, void * data)
```

```json
{
  "name": "child_unregister",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586516752,
      "name": "child_unregister",
      "external": false,
      "loc": "drivers/nvdimm/bus.c:384",
      "file": "drivers/nvdimm/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586539552,
      "name": "child_unregister",
      "external": false,
      "loc": "drivers/nvdimm/region.c:83",
      "file": "drivers/nvdimm/region.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586516752,
      "name": "child_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
    },
    {
      "addr": 18446744071586539552,
      "name": "child_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
int child_unregister(struct device * dev, void * data)
```

```json
{
  "name": "child_unregister",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587298112,
      "name": "child_unregister",
      "external": false,
      "loc": "drivers/nvdimm/bus.c:389",
      "file": "drivers/nvdimm/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587323408,
      "name": "child_unregister",
      "external": false,
      "loc": "drivers/nvdimm/region.c:83",
      "file": "drivers/nvdimm/region.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587298304,
      "name": "child_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071587298112,
      "name": "child_unregister.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 181
    },
    {
      "addr": 18446744071587323408,
      "name": "child_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Collision, Selective Inline, Transformation ❓</summary>

```c
int child_unregister(struct device * dev, void * data)
```

```json
{
  "name": "child_unregister",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587359360,
      "name": "child_unregister",
      "external": false,
      "loc": "drivers/nvdimm/bus.c:389",
      "file": "drivers/nvdimm/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587385248,
      "name": "child_unregister",
      "external": false,
      "loc": "drivers/nvdimm/region.c:84",
      "file": "drivers/nvdimm/region.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587359552,
      "name": "child_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071587359360,
      "name": "child_unregister.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 181
    },
    {
      "addr": 18446744071587385248,
      "name": "child_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int child_unregister(struct device * dev, void * data)
```

```json
{
  "name": "child_unregister",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587240240,
      "name": "child_unregister",
      "external": false,
      "loc": "drivers/nvdimm/bus.c:388",
      "file": "drivers/nvdimm/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587267376,
      "name": "child_unregister",
      "external": false,
      "loc": "drivers/nvdimm/region.c:84",
      "file": "drivers/nvdimm/region.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587240240,
      "name": "child_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 205
    },
    {
      "addr": 18446744071587267376,
      "name": "child_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int child_unregister(struct device * dev, void * data)
```

```json
{
  "name": "child_unregister",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587806816,
      "name": "child_unregister",
      "external": false,
      "loc": "drivers/nvdimm/bus.c:392",
      "file": "drivers/nvdimm/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587834624,
      "name": "child_unregister",
      "external": false,
      "loc": "drivers/nvdimm/region.c:84",
      "file": "drivers/nvdimm/region.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587806816,
      "name": "child_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
    },
    {
      "addr": 18446744071587834624,
      "name": "child_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Collision, Selective Inline ❓</summary>

```c
int child_unregister(struct device * dev, void * data)
```

```json
{
  "name": "child_unregister",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589155456,
      "name": "child_unregister",
      "external": false,
      "loc": "drivers/nvdimm/bus.c:386",
      "file": "drivers/nvdimm/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589186992,
      "name": "child_unregister",
      "external": false,
      "loc": "drivers/nvdimm/region.c:76",
      "file": "drivers/nvdimm/region.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589155456,
      "name": "child_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
    },
    {
      "addr": 18446744071589186992,
      "name": "child_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
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
int child_unregister(struct device * dev, void * data)
```

```json
{
  "name": "child_unregister",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590706432,
      "name": "child_unregister",
      "external": false,
      "loc": "drivers/nvdimm/bus.c:386",
      "file": "drivers/nvdimm/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590741152,
      "name": "child_unregister",
      "external": false,
      "loc": "drivers/nvdimm/region.c:77",
      "file": "drivers/nvdimm/region.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590706432,
      "name": "child_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
    },
    {
      "addr": 18446744071590741152,
      "name": "child_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
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
int child_unregister(struct device * dev, void * data)
```

```json
{
  "name": "child_unregister",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591047632,
      "name": "child_unregister",
      "external": false,
      "loc": "drivers/nvdimm/bus.c:386",
      "file": "drivers/nvdimm/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591082512,
      "name": "child_unregister",
      "external": false,
      "loc": "drivers/nvdimm/region.c:77",
      "file": "drivers/nvdimm/region.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591047632,
      "name": "child_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
    },
    {
      "addr": 18446744071591082512,
      "name": "child_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
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
int child_unregister(struct device * dev, void * data)
```

```json
{
  "name": "child_unregister",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591392144,
      "name": "child_unregister",
      "external": false,
      "loc": "drivers/nvdimm/bus.c:386",
      "file": "drivers/nvdimm/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591427408,
      "name": "child_unregister",
      "external": false,
      "loc": "drivers/nvdimm/region.c:77",
      "file": "drivers/nvdimm/region.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591392144,
      "name": "child_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
    },
    {
      "addr": 18446744071591427408,
      "name": "child_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
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
int child_unregister(struct device * dev, void * data)
```

```json
{
  "name": "child_unregister",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336499403832,
      "name": "child_unregister",
      "external": false,
      "loc": "drivers/nvdimm/bus.c:384",
      "file": "drivers/nvdimm/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336499428576,
      "name": "child_unregister",
      "external": false,
      "loc": "drivers/nvdimm/region.c:83",
      "file": "drivers/nvdimm/region.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499403832,
      "name": "child_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 276
    },
    {
      "addr": 18446603336499428576,
      "name": "child_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Collision, Selective Inline ❓</summary>

```c
int child_unregister(struct device * dev, void * data)
```

```json
{
  "name": "child_unregister",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055292641824,
      "name": "child_unregister",
      "external": false,
      "loc": "drivers/nvdimm/bus.c:384",
      "file": "drivers/nvdimm/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055292674000,
      "name": "child_unregister",
      "external": false,
      "loc": "drivers/nvdimm/region.c:83",
      "file": "drivers/nvdimm/region.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292641824,
      "name": "child_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 300
    },
    {
      "addr": 13835058055292674000,
      "name": "child_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
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
int child_unregister(struct device * dev, void * data)
```

```json
{
  "name": "child_unregister",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276631850,
      "name": "child_unregister",
      "external": false,
      "loc": "drivers/nvdimm/bus.c:384",
      "file": "drivers/nvdimm/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936276655024,
      "name": "child_unregister",
      "external": false,
      "loc": "drivers/nvdimm/region.c:83",
      "file": "drivers/nvdimm/region.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276631850,
      "name": "child_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
    },
    {
      "addr": 18446743936276655024,
      "name": "child_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
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
int child_unregister(struct device * dev, void * data)
```

```json
{
  "name": "child_unregister",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586207232,
      "name": "child_unregister",
      "external": false,
      "loc": "drivers/nvdimm/bus.c:384",
      "file": "drivers/nvdimm/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586230032,
      "name": "child_unregister",
      "external": false,
      "loc": "drivers/nvdimm/region.c:83",
      "file": "drivers/nvdimm/region.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586207232,
      "name": "child_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
    },
    {
      "addr": 18446744071586230032,
      "name": "child_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
int child_unregister(struct device * dev, void * data)
```

```json
{
  "name": "child_unregister",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586025600,
      "name": "child_unregister",
      "external": false,
      "loc": "drivers/nvdimm/bus.c:384",
      "file": "drivers/nvdimm/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586048400,
      "name": "child_unregister",
      "external": false,
      "loc": "drivers/nvdimm/region.c:83",
      "file": "drivers/nvdimm/region.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586025600,
      "name": "child_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
    },
    {
      "addr": 18446744071586048400,
      "name": "child_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
int child_unregister(struct device * dev, void * data)
```

```json
{
  "name": "child_unregister",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586464720,
      "name": "child_unregister",
      "external": false,
      "loc": "drivers/nvdimm/bus.c:384",
      "file": "drivers/nvdimm/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586487520,
      "name": "child_unregister",
      "external": false,
      "loc": "drivers/nvdimm/region.c:83",
      "file": "drivers/nvdimm/region.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586464720,
      "name": "child_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
    },
    {
      "addr": 18446744071586487520,
      "name": "child_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
int child_unregister(struct device * dev, void * data)
```

```json
{
  "name": "child_unregister",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586576416,
      "name": "child_unregister",
      "external": false,
      "loc": "drivers/nvdimm/bus.c:384",
      "file": "drivers/nvdimm/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586599264,
      "name": "child_unregister",
      "external": false,
      "loc": "drivers/nvdimm/region.c:83",
      "file": "drivers/nvdimm/region.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586576416,
      "name": "child_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
    },
    {
      "addr": 18446744071586599264,
      "name": "child_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
int child_unregister(struct device * dev, void * data)
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
