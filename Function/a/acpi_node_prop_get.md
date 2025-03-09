# Function: <code>acpi_node_prop_get</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int acpi_node_prop_get(struct fwnode_handle * fwnode, const char * propname, void * * valptr)
```

```json
{
  "name": "acpi_node_prop_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583608437,
      "name": "acpi_node_prop_get",
      "external": true,
      "loc": "drivers/acpi/property.c:419",
      "file": "drivers/acpi/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583608437,
      "name": "acpi_node_prop_get",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int acpi_node_prop_get(struct fwnode_handle * fwnode, const char * propname, void * * valptr)
```

```json
{
  "name": "acpi_node_prop_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583931531,
      "name": "acpi_node_prop_get",
      "external": true,
      "loc": "drivers/acpi/property.c:419",
      "file": "drivers/acpi/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/property.c:__fwnode_property_present"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583931531,
      "name": "acpi_node_prop_get",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int acpi_node_prop_get(struct fwnode_handle * fwnode, const char * propname, void * * valptr)
```

```json
{
  "name": "acpi_node_prop_get",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584073015,
      "name": "acpi_node_prop_get",
      "external": true,
      "loc": "drivers/acpi/property.c:472",
      "file": "drivers/acpi/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/property.c:__fwnode_property_present"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584073015,
      "name": "acpi_node_prop_get",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int acpi_node_prop_get(struct fwnode_handle * fwnode, const char * propname, void * * valptr)
```

```json
{
  "name": "acpi_node_prop_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584136557,
      "name": "acpi_node_prop_get",
      "external": true,
      "loc": "drivers/acpi/property.c:488",
      "file": "drivers/acpi/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/property.c:acpi_fwnode_property_present"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584138656,
      "name": "acpi_node_prop_get",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int acpi_node_prop_get(const struct fwnode_handle * fwnode, const char * propname, void * * valptr)
```

```json
{
  "name": "acpi_node_prop_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584406845,
      "name": "acpi_node_prop_get",
      "external": true,
      "loc": "drivers/acpi/property.c:494",
      "file": "drivers/acpi/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/property.c:acpi_fwnode_property_present"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584412064,
      "name": "acpi_node_prop_get",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int acpi_node_prop_get(const struct fwnode_handle * fwnode, const char * propname, void * * valptr)
```

```json
{
  "name": "acpi_node_prop_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584633253,
      "name": "acpi_node_prop_get",
      "external": true,
      "loc": "drivers/acpi/property.c:494",
      "file": "drivers/acpi/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/property.c:acpi_fwnode_property_present"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584635456,
      "name": "acpi_node_prop_get",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int acpi_node_prop_get(const struct fwnode_handle * fwnode, const char * propname, void * * valptr)
```

```json
{
  "name": "acpi_node_prop_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584731253,
      "name": "acpi_node_prop_get",
      "external": true,
      "loc": "drivers/acpi/property.c:550",
      "file": "drivers/acpi/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/property.c:acpi_fwnode_property_present"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584735168,
      "name": "acpi_node_prop_get",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
int acpi_node_prop_get(const struct fwnode_handle * fwnode, const char * propname, void * * valptr)
```

```json
{
  "name": "acpi_node_prop_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584931621,
      "name": "acpi_node_prop_get",
      "external": true,
      "loc": "drivers/acpi/property.c:554",
      "file": "drivers/acpi/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/property.c:acpi_fwnode_property_present"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584937184,
      "name": "acpi_node_prop_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
int acpi_node_prop_get(const struct fwnode_handle * fwnode, const char * propname, void * * valptr)
```

```json
{
  "name": "acpi_node_prop_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585067429,
      "name": "acpi_node_prop_get",
      "external": true,
      "loc": "drivers/acpi/property.c:554",
      "file": "drivers/acpi/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/property.c:acpi_fwnode_property_present"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585072992,
      "name": "acpi_node_prop_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
int acpi_node_prop_get(const struct fwnode_handle * fwnode, const char * propname, void * * valptr)
```

```json
{
  "name": "acpi_node_prop_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585775685,
      "name": "acpi_node_prop_get",
      "external": true,
      "loc": "drivers/acpi/property.c:554",
      "file": "drivers/acpi/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/property.c:acpi_fwnode_property_present"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585778144,
      "name": "acpi_node_prop_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
int acpi_node_prop_get(const struct fwnode_handle * fwnode, const char * propname, void * * valptr)
```

```json
{
  "name": "acpi_node_prop_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585894046,
      "name": "acpi_node_prop_get",
      "external": true,
      "loc": "drivers/acpi/property.c:557",
      "file": "drivers/acpi/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/property.c:acpi_fwnode_property_present"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585896576,
      "name": "acpi_node_prop_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
int acpi_node_prop_get(const struct fwnode_handle * fwnode, const char * propname, void * * valptr)
```

```json
{
  "name": "acpi_node_prop_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585771198,
      "name": "acpi_node_prop_get",
      "external": true,
      "loc": "drivers/acpi/property.c:557",
      "file": "drivers/acpi/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/property.c:acpi_fwnode_property_present"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585773632,
      "name": "acpi_node_prop_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
int acpi_node_prop_get(const struct fwnode_handle * fwnode, const char * propname, void * * valptr)
```

```json
{
  "name": "acpi_node_prop_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586254110,
      "name": "acpi_node_prop_get",
      "external": true,
      "loc": "drivers/acpi/property.c:557",
      "file": "drivers/acpi/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/property.c:acpi_fwnode_property_present"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586256608,
      "name": "acpi_node_prop_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
int acpi_node_prop_get(const struct fwnode_handle * fwnode, const char * propname, void * * valptr)
```

```json
{
  "name": "acpi_node_prop_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587496389,
      "name": "acpi_node_prop_get",
      "external": true,
      "loc": "drivers/acpi/property.c:564",
      "file": "drivers/acpi/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/property.c:acpi_fwnode_property_present"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587497760,
      "name": "acpi_node_prop_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
int acpi_node_prop_get(const struct fwnode_handle * fwnode, const char * propname, void * * valptr)
```

```json
{
  "name": "acpi_node_prop_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588767589,
      "name": "acpi_node_prop_get",
      "external": true,
      "loc": "drivers/acpi/property.c:723",
      "file": "drivers/acpi/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/property.c:acpi_fwnode_property_present"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588770032,
      "name": "acpi_node_prop_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
int acpi_node_prop_get(const struct fwnode_handle * fwnode, const char * propname, void * * valptr)
```

```json
{
  "name": "acpi_node_prop_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589056725,
      "name": "acpi_node_prop_get",
      "external": true,
      "loc": "drivers/acpi/property.c:723",
      "file": "drivers/acpi/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/property.c:acpi_fwnode_property_present"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589059056,
      "name": "acpi_node_prop_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
int acpi_node_prop_get(const struct fwnode_handle * fwnode, const char * propname, void * * valptr)
```

```json
{
  "name": "acpi_node_prop_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589360181,
      "name": "acpi_node_prop_get",
      "external": true,
      "loc": "drivers/acpi/property.c:727",
      "file": "drivers/acpi/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/property.c:acpi_fwnode_property_present"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589364416,
      "name": "acpi_node_prop_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
int acpi_node_prop_get(const struct fwnode_handle * fwnode, const char * propname, void * * valptr)
```

```json
{
  "name": "acpi_node_prop_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336497470492,
      "name": "acpi_node_prop_get",
      "external": true,
      "loc": "drivers/acpi/property.c:554",
      "file": "drivers/acpi/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/property.c:acpi_fwnode_property_present"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497477472,
      "name": "acpi_node_prop_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int acpi_node_prop_get(const struct fwnode_handle * fwnode, const char * propname, void * * valptr)
```

```json
{
  "name": "acpi_node_prop_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584996917,
      "name": "acpi_node_prop_get",
      "external": true,
      "loc": "drivers/acpi/property.c:554",
      "file": "drivers/acpi/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/property.c:acpi_fwnode_property_present"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585002480,
      "name": "acpi_node_prop_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
int acpi_node_prop_get(const struct fwnode_handle * fwnode, const char * propname, void * * valptr)
```

```json
{
  "name": "acpi_node_prop_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584912501,
      "name": "acpi_node_prop_get",
      "external": true,
      "loc": "drivers/acpi/property.c:554",
      "file": "drivers/acpi/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/property.c:acpi_fwnode_property_present"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584918064,
      "name": "acpi_node_prop_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
int acpi_node_prop_get(const struct fwnode_handle * fwnode, const char * propname, void * * valptr)
```

```json
{
  "name": "acpi_node_prop_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585019013,
      "name": "acpi_node_prop_get",
      "external": true,
      "loc": "drivers/acpi/property.c:554",
      "file": "drivers/acpi/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/property.c:acpi_fwnode_property_present"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585024576,
      "name": "acpi_node_prop_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
int acpi_node_prop_get(const struct fwnode_handle * fwnode, const char * propname, void * * valptr)
```

```json
{
  "name": "acpi_node_prop_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585125189,
      "name": "acpi_node_prop_get",
      "external": true,
      "loc": "drivers/acpi/property.c:554",
      "file": "drivers/acpi/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/property.c:acpi_fwnode_property_present"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585130752,
      "name": "acpi_node_prop_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct fwnode_handle * fwnode</code> ➡️ <code>const struct fwnode_handle * fwnode</code>
</li>
</ul>
</details>
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
int acpi_node_prop_get(const struct fwnode_handle * fwnode, const char * propname, void * * valptr)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int acpi_node_prop_get(const struct fwnode_handle * fwnode, const char * propname, void * * valptr)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int acpi_node_prop_get(const struct fwnode_handle * fwnode, const char * propname, void * * valptr)
```
</details>
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
