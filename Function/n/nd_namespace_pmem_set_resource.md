# Function: <code>nd_namespace_pmem_set_resource</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void nd_namespace_pmem_set_resource(struct nd_region * nd_region, struct nd_namespace_pmem * nspm, resource_size_t size)
```

```json
{
  "name": "nd_namespace_pmem_set_resource",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585261856,
      "name": "nd_namespace_pmem_set_resource",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:906",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed",
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/namespace_devs.c:size_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585261856,
      "name": "nd_namespace_pmem_set_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 341
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
void nd_namespace_pmem_set_resource(struct nd_region * nd_region, struct nd_namespace_pmem * nspm, resource_size_t size)
```

```json
{
  "name": "nd_namespace_pmem_set_resource",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585362390,
      "name": "nd_namespace_pmem_set_resource",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:925",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed"
      ],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/namespace_devs.c:size_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585345120,
      "name": "nd_namespace_pmem_set_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 263
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
void nd_namespace_pmem_set_resource(struct nd_region * nd_region, struct nd_namespace_pmem * nspm, resource_size_t size)
```

```json
{
  "name": "nd_namespace_pmem_set_resource",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585788297,
      "name": "nd_namespace_pmem_set_resource",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:925",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed"
      ],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:size_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585773824,
      "name": "nd_namespace_pmem_set_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 263
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
void nd_namespace_pmem_set_resource(struct nd_region * nd_region, struct nd_namespace_pmem * nspm, resource_size_t size)
```

```json
{
  "name": "nd_namespace_pmem_set_resource",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586034974,
      "name": "nd_namespace_pmem_set_resource",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:925",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed"
      ],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:size_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586020624,
      "name": "nd_namespace_pmem_set_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 263
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
void nd_namespace_pmem_set_resource(struct nd_region * nd_region, struct nd_namespace_pmem * nspm, resource_size_t size)
```

```json
{
  "name": "nd_namespace_pmem_set_resource",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586173449,
      "name": "nd_namespace_pmem_set_resource",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:928",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed"
      ],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:size_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586159584,
      "name": "nd_namespace_pmem_set_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 263
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
void nd_namespace_pmem_set_resource(struct nd_region * nd_region, struct nd_namespace_pmem * nspm, resource_size_t size)
```

```json
{
  "name": "nd_namespace_pmem_set_resource",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586410690,
      "name": "nd_namespace_pmem_set_resource",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:920",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed"
      ],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/namespace_devs.c:__size_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586395792,
      "name": "nd_namespace_pmem_set_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 263
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
void nd_namespace_pmem_set_resource(struct nd_region * nd_region, struct nd_namespace_pmem * nspm, resource_size_t size)
```

```json
{
  "name": "nd_namespace_pmem_set_resource",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586557544,
      "name": "nd_namespace_pmem_set_resource",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:920",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed"
      ],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/namespace_devs.c:__size_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586542432,
      "name": "nd_namespace_pmem_set_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 263
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
void nd_namespace_pmem_set_resource(struct nd_region * nd_region, struct nd_namespace_pmem * nspm, resource_size_t size)
```

```json
{
  "name": "nd_namespace_pmem_set_resource",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587342498,
      "name": "nd_namespace_pmem_set_resource",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:900",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_pmem_create"
      ],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/namespace_devs.c:__size_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587325504,
      "name": "nd_namespace_pmem_set_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 263
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
void nd_namespace_pmem_set_resource(struct nd_region * nd_region, struct nd_namespace_pmem * nspm, resource_size_t size)
```

```json
{
  "name": "nd_namespace_pmem_set_resource",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587404226,
      "name": "nd_namespace_pmem_set_resource",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:900",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:nd_namespace_pmem_create"
      ],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/namespace_devs.c:__size_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587387280,
      "name": "nd_namespace_pmem_set_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 263
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
void nd_namespace_pmem_set_resource(struct nd_region * nd_region, struct nd_namespace_pmem * nspm, resource_size_t size)
```

```json
{
  "name": "nd_namespace_pmem_set_resource",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587285970,
      "name": "nd_namespace_pmem_set_resource",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:900",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed"
      ],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/namespace_devs.c:__size_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587269424,
      "name": "nd_namespace_pmem_set_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 263
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
void nd_namespace_pmem_set_resource(struct nd_region * nd_region, struct nd_namespace_pmem * nspm, resource_size_t size)
```

```json
{
  "name": "nd_namespace_pmem_set_resource",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587852605,
      "name": "nd_namespace_pmem_set_resource",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:900",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed"
      ],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/namespace_devs.c:__size_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587836352,
      "name": "nd_namespace_pmem_set_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 263
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
void nd_namespace_pmem_set_resource(struct nd_region * nd_region, struct nd_namespace_pmem * nspm, resource_size_t size)
```

```json
{
  "name": "nd_namespace_pmem_set_resource",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589200622,
      "name": "nd_namespace_pmem_set_resource",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:694",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed"
      ],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/namespace_devs.c:__size_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589189408,
      "name": "nd_namespace_pmem_set_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 302
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
void nd_namespace_pmem_set_resource(struct nd_region * nd_region, struct nd_namespace_pmem * nspm, resource_size_t size)
```

```json
{
  "name": "nd_namespace_pmem_set_resource",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590755554,
      "name": "nd_namespace_pmem_set_resource",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:691",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed"
      ],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/namespace_devs.c:__size_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590743888,
      "name": "nd_namespace_pmem_set_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 302
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
void nd_namespace_pmem_set_resource(struct nd_region * nd_region, struct nd_namespace_pmem * nspm, resource_size_t size)
```

```json
{
  "name": "nd_namespace_pmem_set_resource",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591096983,
      "name": "nd_namespace_pmem_set_resource",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:691",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed"
      ],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/namespace_devs.c:__size_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591085248,
      "name": "nd_namespace_pmem_set_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 302
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
void nd_namespace_pmem_set_resource(struct nd_region * nd_region, struct nd_namespace_pmem * nspm, resource_size_t size)
```

```json
{
  "name": "nd_namespace_pmem_set_resource",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591442117,
      "name": "nd_namespace_pmem_set_resource",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:698",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed"
      ],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/namespace_devs.c:__size_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591430144,
      "name": "nd_namespace_pmem_set_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 302
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
void nd_namespace_pmem_set_resource(struct nd_region * nd_region, struct nd_namespace_pmem * nspm, resource_size_t size)
```

```json
{
  "name": "nd_namespace_pmem_set_resource",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336499446376,
      "name": "nd_namespace_pmem_set_resource",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:920",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed"
      ],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/namespace_devs.c:__size_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499431784,
      "name": "nd_namespace_pmem_set_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 280
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
void nd_namespace_pmem_set_resource(struct nd_region * nd_region, struct nd_namespace_pmem * nspm, resource_size_t size)
```

```json
{
  "name": "nd_namespace_pmem_set_resource",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055292704544,
      "name": "nd_namespace_pmem_set_resource",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:920",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed"
      ],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/namespace_devs.c:__size_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292680176,
      "name": "nd_namespace_pmem_set_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 876
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
void nd_namespace_pmem_set_resource(struct nd_region * nd_region, struct nd_namespace_pmem * nspm, resource_size_t size)
```

```json
{
  "name": "nd_namespace_pmem_set_resource",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276670504,
      "name": "nd_namespace_pmem_set_resource",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:920",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed"
      ],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/namespace_devs.c:__size_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276657804,
      "name": "nd_namespace_pmem_set_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
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
void nd_namespace_pmem_set_resource(struct nd_region * nd_region, struct nd_namespace_pmem * nspm, resource_size_t size)
```

```json
{
  "name": "nd_namespace_pmem_set_resource",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586248024,
      "name": "nd_namespace_pmem_set_resource",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:920",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed"
      ],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/namespace_devs.c:__size_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586232912,
      "name": "nd_namespace_pmem_set_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 263
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
void nd_namespace_pmem_set_resource(struct nd_region * nd_region, struct nd_namespace_pmem * nspm, resource_size_t size)
```

```json
{
  "name": "nd_namespace_pmem_set_resource",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586066392,
      "name": "nd_namespace_pmem_set_resource",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:920",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed"
      ],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/namespace_devs.c:__size_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586051280,
      "name": "nd_namespace_pmem_set_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 263
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
void nd_namespace_pmem_set_resource(struct nd_region * nd_region, struct nd_namespace_pmem * nspm, resource_size_t size)
```

```json
{
  "name": "nd_namespace_pmem_set_resource",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586505512,
      "name": "nd_namespace_pmem_set_resource",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:920",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed"
      ],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/namespace_devs.c:__size_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586490400,
      "name": "nd_namespace_pmem_set_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 263
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
void nd_namespace_pmem_set_resource(struct nd_region * nd_region, struct nd_namespace_pmem * nspm, resource_size_t size)
```

```json
{
  "name": "nd_namespace_pmem_set_resource",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586617256,
      "name": "nd_namespace_pmem_set_resource",
      "external": false,
      "loc": "drivers/nvdimm/namespace_devs.c:920",
      "file": "drivers/nvdimm/namespace_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed"
      ],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/namespace_devs.c:__size_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586602144,
      "name": "nd_namespace_pmem_set_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 263
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
void nd_namespace_pmem_set_resource(struct nd_region * nd_region, struct nd_namespace_pmem * nspm, resource_size_t size)
```
</details>
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
void nd_namespace_pmem_set_resource(struct nd_region * nd_region, struct nd_namespace_pmem * nspm, resource_size_t size)
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
