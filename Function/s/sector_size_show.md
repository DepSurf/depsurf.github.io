# Function: <code>sector_size_show</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t sector_size_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "sector_size_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584724224,
      "name": "sector_size_show",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1171",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584748560,
      "name": "sector_size_show",
      "external": false,
      "loc": "drivers/nvdimm/btt_devs.c:59",
      "file": "drivers/nvdimm/btt_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584724224,
      "name": "sector_size_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071584748560,
      "name": "sector_size_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t sector_size_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "sector_size_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585076800,
      "name": "sector_size_show",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1181",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585101872,
      "name": "sector_size_show",
      "external": false,
      "loc": "drivers/nvdimm/btt_devs.c:59",
      "file": "drivers/nvdimm/btt_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585076800,
      "name": "sector_size_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071585101872,
      "name": "sector_size_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t sector_size_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "sector_size_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585263040,
      "name": "sector_size_show",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1289",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585290912,
      "name": "sector_size_show",
      "external": false,
      "loc": "drivers/nvdimm/btt_devs.c:59",
      "file": "drivers/nvdimm/btt_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585263040,
      "name": "sector_size_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071585290912,
      "name": "sector_size_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
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
ssize_t sector_size_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "sector_size_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585348144,
      "name": "sector_size_show",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1310",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585376992,
      "name": "sector_size_show",
      "external": false,
      "loc": "drivers/nvdimm/btt_devs.c:59",
      "file": "drivers/nvdimm/btt_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585348144,
      "name": "sector_size_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
    },
    {
      "addr": 18446744071585376992,
      "name": "sector_size_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
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
ssize_t sector_size_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "sector_size_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585776560,
      "name": "sector_size_show",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1310",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585806048,
      "name": "sector_size_show",
      "external": false,
      "loc": "drivers/nvdimm/btt_devs.c:59",
      "file": "drivers/nvdimm/btt_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585776560,
      "name": "sector_size_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
    },
    {
      "addr": 18446744071585806048,
      "name": "sector_size_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
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
ssize_t sector_size_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "sector_size_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586025168,
      "name": "sector_size_show",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1309",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586052176,
      "name": "sector_size_show",
      "external": false,
      "loc": "drivers/nvdimm/btt_devs.c:59",
      "file": "drivers/nvdimm/btt_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586025168,
      "name": "sector_size_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    },
    {
      "addr": 18446744071586052176,
      "name": "sector_size_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
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
ssize_t sector_size_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "sector_size_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586165152,
      "name": "sector_size_show",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1332",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586192384,
      "name": "sector_size_show",
      "external": false,
      "loc": "drivers/nvdimm/btt_devs.c:59",
      "file": "drivers/nvdimm/btt_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586165152,
      "name": "sector_size_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    },
    {
      "addr": 18446744071586192384,
      "name": "sector_size_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
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
ssize_t sector_size_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "sector_size_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586401280,
      "name": "sector_size_show",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1339",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "sector_size_show",
      "external": false,
      "loc": "drivers/nvdimm/btt_devs.c:51",
      "file": "drivers/nvdimm/btt_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586401280,
      "name": "sector_size_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    },
    {
      "addr": 18446744071586429600,
      "name": "sector_size_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446744071586431227,
      "name": "sector_size_show.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
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
ssize_t sector_size_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "sector_size_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586548112,
      "name": "sector_size_show",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1339",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586576272,
      "name": "sector_size_show",
      "external": false,
      "loc": "drivers/nvdimm/btt_devs.c:51",
      "file": "drivers/nvdimm/btt_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586548112,
      "name": "sector_size_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    },
    {
      "addr": 18446744071586576272,
      "name": "sector_size_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t sector_size_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "sector_size_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587327648,
      "name": "sector_size_show",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1319",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587361312,
      "name": "sector_size_show",
      "external": false,
      "loc": "drivers/nvdimm/btt_devs.c:40",
      "file": "drivers/nvdimm/btt_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587327648,
      "name": "sector_size_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    },
    {
      "addr": 18446744071587361312,
      "name": "sector_size_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Collision ❓</summary>

```c
ssize_t sector_size_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "sector_size_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587389424,
      "name": "sector_size_show",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1319",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587422560,
      "name": "sector_size_show",
      "external": false,
      "loc": "drivers/nvdimm/btt_devs.c:40",
      "file": "drivers/nvdimm/btt_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587389424,
      "name": "sector_size_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    },
    {
      "addr": 18446744071587422560,
      "name": "sector_size_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
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
ssize_t sector_size_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "sector_size_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587271536,
      "name": "sector_size_show",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1319",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587304496,
      "name": "sector_size_show",
      "external": false,
      "loc": "drivers/nvdimm/btt_devs.c:40",
      "file": "drivers/nvdimm/btt_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587271536,
      "name": "sector_size_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    },
    {
      "addr": 18446744071587304496,
      "name": "sector_size_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
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
ssize_t sector_size_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "sector_size_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587838112,
      "name": "sector_size_show",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1319",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587871680,
      "name": "sector_size_show",
      "external": false,
      "loc": "drivers/nvdimm/btt_devs.c:40",
      "file": "drivers/nvdimm/btt_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587838112,
      "name": "sector_size_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    },
    {
      "addr": 18446744071587871680,
      "name": "sector_size_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
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
ssize_t sector_size_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "sector_size_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589192528,
      "name": "sector_size_show",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1093",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071589221296,
      "name": "sector_size_show",
      "external": false,
      "loc": "drivers/nvdimm/btt_devs.c:39",
      "file": "drivers/nvdimm/btt_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589192528,
      "name": "sector_size_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
    },
    {
      "addr": 18446744071589221296,
      "name": "sector_size_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
ssize_t sector_size_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "sector_size_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590747216,
      "name": "sector_size_show",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1085",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071590777376,
      "name": "sector_size_show",
      "external": false,
      "loc": "drivers/nvdimm/btt_devs.c:39",
      "file": "drivers/nvdimm/btt_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590747216,
      "name": "sector_size_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
    },
    {
      "addr": 18446744071590777376,
      "name": "sector_size_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
ssize_t sector_size_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "sector_size_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591088592,
      "name": "sector_size_show",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1085",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591118752,
      "name": "sector_size_show",
      "external": false,
      "loc": "drivers/nvdimm/btt_devs.c:39",
      "file": "drivers/nvdimm/btt_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591088592,
      "name": "sector_size_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
    },
    {
      "addr": 18446744071591118752,
      "name": "sector_size_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
ssize_t sector_size_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "sector_size_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591433488,
      "name": "sector_size_show",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1094",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071591464176,
      "name": "sector_size_show",
      "external": false,
      "loc": "drivers/nvdimm/btt_devs.c:39",
      "file": "drivers/nvdimm/btt_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591433488,
      "name": "sector_size_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
    },
    {
      "addr": 18446744071591464176,
      "name": "sector_size_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
ssize_t sector_size_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "sector_size_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336499437640,
      "name": "sector_size_show",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1339",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336499466176,
      "name": "sector_size_show",
      "external": false,
      "loc": "drivers/nvdimm/btt_devs.c:51",
      "file": "drivers/nvdimm/btt_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499437640,
      "name": "sector_size_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    },
    {
      "addr": 18446603336499466176,
      "name": "sector_size_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
ssize_t sector_size_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "sector_size_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055292689552,
      "name": "sector_size_show",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1339",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055292732544,
      "name": "sector_size_show",
      "external": false,
      "loc": "drivers/nvdimm/btt_devs.c:51",
      "file": "drivers/nvdimm/btt_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292689552,
      "name": "sector_size_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    },
    {
      "addr": 13835058055292732544,
      "name": "sector_size_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
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
ssize_t sector_size_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "sector_size_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276663262,
      "name": "sector_size_show",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1339",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936276687170,
      "name": "sector_size_show",
      "external": false,
      "loc": "drivers/nvdimm/btt_devs.c:51",
      "file": "drivers/nvdimm/btt_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276663262,
      "name": "sector_size_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
    },
    {
      "addr": 18446743936276687170,
      "name": "sector_size_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
ssize_t sector_size_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "sector_size_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586238592,
      "name": "sector_size_show",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1339",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586266752,
      "name": "sector_size_show",
      "external": false,
      "loc": "drivers/nvdimm/btt_devs.c:51",
      "file": "drivers/nvdimm/btt_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586238592,
      "name": "sector_size_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    },
    {
      "addr": 18446744071586266752,
      "name": "sector_size_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
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
ssize_t sector_size_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "sector_size_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586056960,
      "name": "sector_size_show",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1339",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586085120,
      "name": "sector_size_show",
      "external": false,
      "loc": "drivers/nvdimm/btt_devs.c:51",
      "file": "drivers/nvdimm/btt_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586056960,
      "name": "sector_size_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    },
    {
      "addr": 18446744071586085120,
      "name": "sector_size_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
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
ssize_t sector_size_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "sector_size_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586496080,
      "name": "sector_size_show",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1339",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586524240,
      "name": "sector_size_show",
      "external": false,
      "loc": "drivers/nvdimm/btt_devs.c:51",
      "file": "drivers/nvdimm/btt_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586496080,
      "name": "sector_size_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    },
    {
      "addr": 18446744071586524240,
      "name": "sector_size_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
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
ssize_t sector_size_show(struct device * dev, struct device_attribute * attr, char * buf)
```

```json
{
  "name": "sector_size_show",
  "collision_type": "Static-Static Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586607824,
      "name": "sector_size_show",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:1339",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586635968,
      "name": "sector_size_show",
      "external": false,
      "loc": "drivers/nvdimm/btt_devs.c:51",
      "file": "drivers/nvdimm/btt_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586607824,
      "name": "sector_size_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    },
    {
      "addr": 18446744071586635968,
      "name": "sector_size_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
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
ssize_t sector_size_show(struct device * dev, struct device_attribute * attr, char * buf)
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
