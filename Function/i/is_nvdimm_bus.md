# Function: <code>is_nvdimm_bus</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "is_nvdimm_bus",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "is_nvdimm_bus",
      "external": false,
      "loc": "drivers/nvdimm/bus.c:244",
      "file": "drivers/nvdimm/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "is_nvdimm_bus",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "is_nvdimm_bus",
      "external": false,
      "loc": "drivers/nvdimm/bus.c:246",
      "file": "drivers/nvdimm/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "is_nvdimm_bus",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "is_nvdimm_bus",
      "external": false,
      "loc": "drivers/nvdimm/bus.c:308",
      "file": "drivers/nvdimm/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "is_nvdimm_bus",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "is_nvdimm_bus",
      "external": false,
      "loc": "drivers/nvdimm/bus.c:309",
      "file": "drivers/nvdimm/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "is_nvdimm_bus",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585997285,
      "name": "is_nvdimm_bus",
      "external": false,
      "loc": "drivers/nvdimm/bus.c:312",
      "file": "drivers/nvdimm/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/bus.c:nvdimm_bus_match",
        "drivers/nvdimm/bus.c:nd_bus_remove",
        "drivers/nvdimm/bus.c:walk_to_nvdimm_bus"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "is_nvdimm_bus",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586134645,
      "name": "is_nvdimm_bus",
      "external": false,
      "loc": "drivers/nvdimm/bus.c:306",
      "file": "drivers/nvdimm/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/bus.c:nvdimm_bus_match",
        "drivers/nvdimm/bus.c:nd_bus_remove",
        "drivers/nvdimm/bus.c:nvdimm_to_bus",
        "drivers/nvdimm/bus.c:walk_to_nvdimm_bus"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool is_nvdimm_bus(struct device * dev)
```

```json
{
  "name": "is_nvdimm_bus",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586369029,
      "name": "is_nvdimm_bus",
      "external": true,
      "loc": "drivers/nvdimm/bus.c:305",
      "file": "drivers/nvdimm/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/bus.c:nvdimm_bus_match",
        "drivers/nvdimm/bus.c:nd_bus_remove",
        "drivers/nvdimm/bus.c:nvdimm_to_bus",
        "drivers/nvdimm/bus.c:walk_to_nvdimm_bus"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586370688,
      "name": "is_nvdimm_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool is_nvdimm_bus(struct device * dev)
```

```json
{
  "name": "is_nvdimm_bus",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586518677,
      "name": "is_nvdimm_bus",
      "external": true,
      "loc": "drivers/nvdimm/bus.c:303",
      "file": "drivers/nvdimm/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/bus.c:nvdimm_bus_match",
        "drivers/nvdimm/bus.c:nd_bus_remove",
        "drivers/nvdimm/bus.c:nvdimm_to_bus",
        "drivers/nvdimm/bus.c:walk_to_nvdimm_bus"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586518752,
      "name": "is_nvdimm_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool is_nvdimm_bus(struct device * dev)
```

```json
{
  "name": "is_nvdimm_bus",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587299173,
      "name": "is_nvdimm_bus",
      "external": true,
      "loc": "drivers/nvdimm/bus.c:308",
      "file": "drivers/nvdimm/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/bus.c:nvdimm_bus_match",
        "drivers/nvdimm/bus.c:nd_bus_remove",
        "drivers/nvdimm/bus.c:nvdimm_to_bus",
        "drivers/nvdimm/bus.c:walk_to_nvdimm_bus"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587299232,
      "name": "is_nvdimm_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool is_nvdimm_bus(struct device * dev)
```

```json
{
  "name": "is_nvdimm_bus",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587360421,
      "name": "is_nvdimm_bus",
      "external": true,
      "loc": "drivers/nvdimm/bus.c:308",
      "file": "drivers/nvdimm/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/bus.c:nvdimm_bus_match",
        "drivers/nvdimm/bus.c:nd_bus_remove",
        "drivers/nvdimm/bus.c:nvdimm_to_bus",
        "drivers/nvdimm/bus.c:walk_to_nvdimm_bus"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587360480,
      "name": "is_nvdimm_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool is_nvdimm_bus(struct device * dev)
```

```json
{
  "name": "is_nvdimm_bus",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587242437,
      "name": "is_nvdimm_bus",
      "external": true,
      "loc": "drivers/nvdimm/bus.c:307",
      "file": "drivers/nvdimm/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/bus.c:nvdimm_bus_match",
        "drivers/nvdimm/bus.c:nd_bus_remove",
        "drivers/nvdimm/bus.c:nvdimm_to_bus",
        "drivers/nvdimm/bus.c:walk_to_nvdimm_bus"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587242496,
      "name": "is_nvdimm_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool is_nvdimm_bus(struct device * dev)
```

```json
{
  "name": "is_nvdimm_bus",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587808901,
      "name": "is_nvdimm_bus",
      "external": true,
      "loc": "drivers/nvdimm/bus.c:306",
      "file": "drivers/nvdimm/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/bus.c:nvdimm_bus_match",
        "drivers/nvdimm/bus.c:nd_bus_remove",
        "drivers/nvdimm/bus.c:nvdimm_to_bus",
        "drivers/nvdimm/bus.c:walk_to_nvdimm_bus"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587808960,
      "name": "is_nvdimm_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool is_nvdimm_bus(struct device * dev)
```

```json
{
  "name": "is_nvdimm_bus",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589157653,
      "name": "is_nvdimm_bus",
      "external": true,
      "loc": "drivers/nvdimm/bus.c:297",
      "file": "drivers/nvdimm/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/bus.c:nvdimm_bus_match",
        "drivers/nvdimm/bus.c:nd_bus_remove",
        "drivers/nvdimm/bus.c:nvdimm_to_bus",
        "drivers/nvdimm/bus.c:walk_to_nvdimm_bus"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589157728,
      "name": "is_nvdimm_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool is_nvdimm_bus(struct device * dev)
```

```json
{
  "name": "is_nvdimm_bus",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590708917,
      "name": "is_nvdimm_bus",
      "external": true,
      "loc": "drivers/nvdimm/bus.c:297",
      "file": "drivers/nvdimm/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/bus.c:nvdimm_bus_match",
        "drivers/nvdimm/bus.c:nd_bus_remove",
        "drivers/nvdimm/bus.c:nvdimm_to_bus",
        "drivers/nvdimm/bus.c:walk_to_nvdimm_bus"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590709008,
      "name": "is_nvdimm_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool is_nvdimm_bus(struct device * dev)
```

```json
{
  "name": "is_nvdimm_bus",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591050117,
      "name": "is_nvdimm_bus",
      "external": true,
      "loc": "drivers/nvdimm/bus.c:297",
      "file": "drivers/nvdimm/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/bus.c:nvdimm_bus_match",
        "drivers/nvdimm/bus.c:nd_bus_remove",
        "drivers/nvdimm/bus.c:nvdimm_to_bus",
        "drivers/nvdimm/bus.c:walk_to_nvdimm_bus",
        "drivers/nvdimm/bus.c:walk_to_nvdimm_bus"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591050208,
      "name": "is_nvdimm_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool is_nvdimm_bus(struct device * dev)
```

```json
{
  "name": "is_nvdimm_bus",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591394677,
      "name": "is_nvdimm_bus",
      "external": true,
      "loc": "drivers/nvdimm/bus.c:297",
      "file": "drivers/nvdimm/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/bus.c:nvdimm_bus_match",
        "drivers/nvdimm/bus.c:nd_bus_remove",
        "drivers/nvdimm/bus.c:nvdimm_to_bus",
        "drivers/nvdimm/bus.c:walk_to_nvdimm_bus",
        "drivers/nvdimm/bus.c:walk_to_nvdimm_bus"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591394768,
      "name": "is_nvdimm_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
bool is_nvdimm_bus(struct device * dev)
```

```json
{
  "name": "is_nvdimm_bus",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336499402420,
      "name": "is_nvdimm_bus",
      "external": true,
      "loc": "drivers/nvdimm/bus.c:303",
      "file": "drivers/nvdimm/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/bus.c:nvdimm_bus_match",
        "drivers/nvdimm/bus.c:nd_bus_remove",
        "drivers/nvdimm/bus.c:nvdimm_to_bus",
        "drivers/nvdimm/bus.c:walk_to_nvdimm_bus"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499404112,
      "name": "is_nvdimm_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
bool is_nvdimm_bus(struct device * dev)
```

```json
{
  "name": "is_nvdimm_bus",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055292641368,
      "name": "is_nvdimm_bus",
      "external": true,
      "loc": "drivers/nvdimm/bus.c:303",
      "file": "drivers/nvdimm/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/bus.c:nvdimm_bus_match",
        "drivers/nvdimm/bus.c:to_nvdimm_bus",
        "drivers/nvdimm/bus.c:walk_to_nvdimm_bus"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292643584,
      "name": "is_nvdimm_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
bool is_nvdimm_bus(struct device * dev)
```

```json
{
  "name": "is_nvdimm_bus",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276633890,
      "name": "is_nvdimm_bus",
      "external": true,
      "loc": "drivers/nvdimm/bus.c:303",
      "file": "drivers/nvdimm/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/bus.c:nvdimm_bus_match",
        "drivers/nvdimm/bus.c:nd_bus_remove",
        "drivers/nvdimm/bus.c:nvdimm_to_bus",
        "drivers/nvdimm/bus.c:walk_to_nvdimm_bus"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276633974,
      "name": "is_nvdimm_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
bool is_nvdimm_bus(struct device * dev)
```

```json
{
  "name": "is_nvdimm_bus",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586209157,
      "name": "is_nvdimm_bus",
      "external": true,
      "loc": "drivers/nvdimm/bus.c:303",
      "file": "drivers/nvdimm/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/bus.c:nvdimm_bus_match",
        "drivers/nvdimm/bus.c:nd_bus_remove",
        "drivers/nvdimm/bus.c:nvdimm_to_bus",
        "drivers/nvdimm/bus.c:walk_to_nvdimm_bus"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586209232,
      "name": "is_nvdimm_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
bool is_nvdimm_bus(struct device * dev)
```

```json
{
  "name": "is_nvdimm_bus",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586027525,
      "name": "is_nvdimm_bus",
      "external": true,
      "loc": "drivers/nvdimm/bus.c:303",
      "file": "drivers/nvdimm/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/bus.c:nvdimm_bus_match",
        "drivers/nvdimm/bus.c:nd_bus_remove",
        "drivers/nvdimm/bus.c:nvdimm_to_bus",
        "drivers/nvdimm/bus.c:walk_to_nvdimm_bus"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586027600,
      "name": "is_nvdimm_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
bool is_nvdimm_bus(struct device * dev)
```

```json
{
  "name": "is_nvdimm_bus",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586466645,
      "name": "is_nvdimm_bus",
      "external": true,
      "loc": "drivers/nvdimm/bus.c:303",
      "file": "drivers/nvdimm/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/bus.c:nvdimm_bus_match",
        "drivers/nvdimm/bus.c:nd_bus_remove",
        "drivers/nvdimm/bus.c:nvdimm_to_bus",
        "drivers/nvdimm/bus.c:walk_to_nvdimm_bus"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586466720,
      "name": "is_nvdimm_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
bool is_nvdimm_bus(struct device * dev)
```

```json
{
  "name": "is_nvdimm_bus",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586578325,
      "name": "is_nvdimm_bus",
      "external": true,
      "loc": "drivers/nvdimm/bus.c:303",
      "file": "drivers/nvdimm/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/bus.c:nvdimm_bus_match",
        "drivers/nvdimm/bus.c:nd_bus_remove",
        "drivers/nvdimm/bus.c:nvdimm_to_bus",
        "drivers/nvdimm/bus.c:walk_to_nvdimm_bus"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586578400,
      "name": "is_nvdimm_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
<details>
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
bool is_nvdimm_bus(struct device * dev)
```
</details>
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
bool is_nvdimm_bus(struct device * dev)
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
