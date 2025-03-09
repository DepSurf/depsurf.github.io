# Function: <code>__devm_ioremap</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void * __devm_ioremap(struct device * dev, resource_size_t offset, resource_size_t size, enum devm_ioremap_type type)
```

```json
{
  "name": "__devm_ioremap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583891728,
      "name": "__devm_ioremap",
      "external": false,
      "loc": "lib/devres.c:24",
      "file": "lib/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/devres.c:devm_ioremap_wc",
        "lib/devres.c:devm_ioremap_nocache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583891728,
      "name": "__devm_ioremap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 161
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void * __devm_ioremap(struct device * dev, resource_size_t offset, resource_size_t size, enum devm_ioremap_type type)
```

```json
{
  "name": "__devm_ioremap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583976000,
      "name": "__devm_ioremap",
      "external": false,
      "loc": "lib/devres.c:25",
      "file": "lib/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/devres.c:devm_ioremap_wc",
        "lib/devres.c:devm_ioremap_nocache"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583976000,
      "name": "__devm_ioremap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 161
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void * __devm_ioremap(struct device * dev, resource_size_t offset, resource_size_t size, enum devm_ioremap_type type)
```

```json
{
  "name": "__devm_ioremap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584158704,
      "name": "__devm_ioremap",
      "external": false,
      "loc": "lib/devres.c:26",
      "file": "lib/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/devres.c:devm_ioremap_resource",
        "lib/devres.c:devm_ioremap_wc",
        "lib/devres.c:devm_ioremap_nocache",
        "lib/devres.c:devm_ioremap_uc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584158704,
      "name": "__devm_ioremap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void * __devm_ioremap(struct device * dev, resource_size_t offset, resource_size_t size, enum devm_ioremap_type type)
```

```json
{
  "name": "__devm_ioremap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584292448,
      "name": "__devm_ioremap",
      "external": false,
      "loc": "lib/devres.c:26",
      "file": "lib/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/devres.c:devm_ioremap_resource",
        "lib/devres.c:devm_ioremap_wc",
        "lib/devres.c:devm_ioremap_nocache",
        "lib/devres.c:devm_ioremap_uc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584292448,
      "name": "__devm_ioremap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
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
void * __devm_ioremap(struct device * dev, resource_size_t offset, resource_size_t size, enum devm_ioremap_type type)
```

```json
{
  "name": "__devm_ioremap",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584705200,
      "name": "__devm_ioremap",
      "external": false,
      "loc": "lib/devres.c:25",
      "file": "lib/devres.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/devres.c:devm_ioremap_wc",
        "lib/devres.c:devm_ioremap_uc",
        "lib/devres.c:devm_ioremap"
      ],
      "caller_func": [
        "lib/devres.c:__devm_ioremap_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584703376,
      "name": "__devm_ioremap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
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
void * __devm_ioremap(struct device * dev, resource_size_t offset, resource_size_t size, enum devm_ioremap_type type)
```

```json
{
  "name": "__devm_ioremap",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584818532,
      "name": "__devm_ioremap",
      "external": false,
      "loc": "lib/devres.c:25",
      "file": "lib/devres.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/devres.c:devm_ioremap_wc",
        "lib/devres.c:devm_ioremap_uc",
        "lib/devres.c:devm_ioremap"
      ],
      "caller_func": [
        "lib/devres.c:__devm_ioremap_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584816672,
      "name": "__devm_ioremap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
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
void * __devm_ioremap(struct device * dev, resource_size_t offset, resource_size_t size, enum devm_ioremap_type type)
```

```json
{
  "name": "__devm_ioremap",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584862832,
      "name": "__devm_ioremap",
      "external": false,
      "loc": "lib/devres.c:26",
      "file": "lib/devres.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/devres.c:devm_ioremap_np",
        "lib/devres.c:devm_ioremap_wc",
        "lib/devres.c:devm_ioremap_uc",
        "lib/devres.c:devm_ioremap"
      ],
      "caller_func": [
        "lib/devres.c:__devm_ioremap_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584861232,
      "name": "__devm_ioremap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
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
void * __devm_ioremap(struct device * dev, resource_size_t offset, resource_size_t size, enum devm_ioremap_type type)
```

```json
{
  "name": "__devm_ioremap",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585285632,
      "name": "__devm_ioremap",
      "external": false,
      "loc": "lib/devres.c:26",
      "file": "lib/devres.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/devres.c:devm_ioremap_np",
        "lib/devres.c:devm_ioremap_wc",
        "lib/devres.c:devm_ioremap_uc",
        "lib/devres.c:devm_ioremap"
      ],
      "caller_func": [
        "lib/devres.c:__devm_ioremap_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585283824,
      "name": "__devm_ioremap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 190
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
void * __devm_ioremap(struct device * dev, resource_size_t offset, resource_size_t size, enum devm_ioremap_type type)
```

```json
{
  "name": "__devm_ioremap",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586139296,
      "name": "__devm_ioremap",
      "external": false,
      "loc": "lib/devres.c:26",
      "file": "lib/devres.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/devres.c:devm_ioremap_np",
        "lib/devres.c:devm_ioremap_wc",
        "lib/devres.c:devm_ioremap_uc",
        "lib/devres.c:devm_ioremap"
      ],
      "caller_func": [
        "lib/devres.c:__devm_ioremap_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586136816,
      "name": "__devm_ioremap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 213
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
void * __devm_ioremap(struct device * dev, resource_size_t offset, resource_size_t size, enum devm_ioremap_type type)
```

```json
{
  "name": "__devm_ioremap",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587131510,
      "name": "__devm_ioremap",
      "external": false,
      "loc": "lib/devres.c:26",
      "file": "lib/devres.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/devres.c:devm_ioremap_wc",
        "lib/devres.c:devm_ioremap_uc",
        "lib/devres.c:devm_ioremap"
      ],
      "caller_func": [
        "lib/devres.c:__devm_ioremap_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587128192,
      "name": "__devm_ioremap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
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
void * __devm_ioremap(struct device * dev, resource_size_t offset, resource_size_t size, enum devm_ioremap_type type)
```

```json
{
  "name": "__devm_ioremap",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587393654,
      "name": "__devm_ioremap",
      "external": false,
      "loc": "lib/devres.c:26",
      "file": "lib/devres.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/devres.c:devm_ioremap_wc",
        "lib/devres.c:devm_ioremap_uc",
        "lib/devres.c:devm_ioremap"
      ],
      "caller_func": [
        "lib/devres.c:__devm_ioremap_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587390288,
      "name": "__devm_ioremap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
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
void * __devm_ioremap(struct device * dev, resource_size_t offset, resource_size_t size, enum devm_ioremap_type type)
```

```json
{
  "name": "__devm_ioremap",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587728006,
      "name": "__devm_ioremap",
      "external": false,
      "loc": "lib/devres.c:26",
      "file": "lib/devres.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/devres.c:devm_ioremap_wc",
        "lib/devres.c:devm_ioremap_uc",
        "lib/devres.c:devm_ioremap"
      ],
      "caller_func": [
        "lib/devres.c:__devm_ioremap_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587724640,
      "name": "__devm_ioremap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void * __devm_ioremap(struct device * dev, resource_size_t offset, resource_size_t size, enum devm_ioremap_type type)
```

```json
{
  "name": "__devm_ioremap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496176384,
      "name": "__devm_ioremap",
      "external": false,
      "loc": "lib/devres.c:26",
      "file": "lib/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/devres.c:devm_ioremap_resource",
        "lib/devres.c:devm_ioremap_wc",
        "lib/devres.c:devm_ioremap_nocache",
        "lib/devres.c:devm_ioremap_uc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496176384,
      "name": "__devm_ioremap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 620
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void * __devm_ioremap(struct device * dev, resource_size_t offset, resource_size_t size, enum devm_ioremap_type type)
```

```json
{
  "name": "__devm_ioremap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229498164,
      "name": "__devm_ioremap",
      "external": false,
      "loc": "lib/devres.c:26",
      "file": "lib/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/devres.c:devm_ioremap_resource",
        "lib/devres.c:devm_ioremap_wc",
        "lib/devres.c:devm_ioremap_nocache",
        "lib/devres.c:devm_ioremap_uc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229498164,
      "name": "__devm_ioremap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void * __devm_ioremap(struct device * dev, resource_size_t offset, resource_size_t size, enum devm_ioremap_type type)
```

```json
{
  "name": "__devm_ioremap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290451312,
      "name": "__devm_ioremap",
      "external": false,
      "loc": "lib/devres.c:26",
      "file": "lib/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/devres.c:devm_ioremap_resource",
        "lib/devres.c:devm_ioremap_wc",
        "lib/devres.c:devm_ioremap_nocache",
        "lib/devres.c:devm_ioremap_uc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290451312,
      "name": "__devm_ioremap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 296
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void * __devm_ioremap(struct device * dev, resource_size_t offset, resource_size_t size, enum devm_ioremap_type type)
```

```json
{
  "name": "__devm_ioremap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275231730,
      "name": "__devm_ioremap",
      "external": false,
      "loc": "lib/devres.c:26",
      "file": "lib/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/devres.c:devm_ioremap_resource",
        "lib/devres.c:devm_ioremap_wc",
        "lib/devres.c:devm_ioremap_nocache",
        "lib/devres.c:devm_ioremap_uc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275231730,
      "name": "__devm_ioremap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void * __devm_ioremap(struct device * dev, resource_size_t offset, resource_size_t size, enum devm_ioremap_type type)
```

```json
{
  "name": "__devm_ioremap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584261184,
      "name": "__devm_ioremap",
      "external": false,
      "loc": "lib/devres.c:26",
      "file": "lib/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/devres.c:devm_ioremap_resource",
        "lib/devres.c:devm_ioremap_wc",
        "lib/devres.c:devm_ioremap_nocache",
        "lib/devres.c:devm_ioremap_uc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584261184,
      "name": "__devm_ioremap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void * __devm_ioremap(struct device * dev, resource_size_t offset, resource_size_t size, enum devm_ioremap_type type)
```

```json
{
  "name": "__devm_ioremap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584196384,
      "name": "__devm_ioremap",
      "external": false,
      "loc": "lib/devres.c:26",
      "file": "lib/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/devres.c:devm_ioremap_resource",
        "lib/devres.c:devm_ioremap_wc",
        "lib/devres.c:devm_ioremap_nocache",
        "lib/devres.c:devm_ioremap_uc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584196384,
      "name": "__devm_ioremap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void * __devm_ioremap(struct device * dev, resource_size_t offset, resource_size_t size, enum devm_ioremap_type type)
```

```json
{
  "name": "__devm_ioremap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584244944,
      "name": "__devm_ioremap",
      "external": false,
      "loc": "lib/devres.c:26",
      "file": "lib/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/devres.c:devm_ioremap_resource",
        "lib/devres.c:devm_ioremap_wc",
        "lib/devres.c:devm_ioremap_nocache",
        "lib/devres.c:devm_ioremap_uc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584244944,
      "name": "__devm_ioremap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void * __devm_ioremap(struct device * dev, resource_size_t offset, resource_size_t size, enum devm_ioremap_type type)
```

```json
{
  "name": "__devm_ioremap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584349776,
      "name": "__devm_ioremap",
      "external": false,
      "loc": "lib/devres.c:26",
      "file": "lib/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/devres.c:devm_ioremap_resource",
        "lib/devres.c:devm_ioremap_wc",
        "lib/devres.c:devm_ioremap_nocache",
        "lib/devres.c:devm_ioremap_uc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584349776,
      "name": "__devm_ioremap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
void * __devm_ioremap(struct device * dev, resource_size_t offset, resource_size_t size, enum devm_ioremap_type type)
```
</details>
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
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
