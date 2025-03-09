# Function: <code>nd_region_interleave_set_cookie</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
u64 nd_region_interleave_set_cookie(struct nd_region * nd_region)
```

```json
{
  "name": "nd_region_interleave_set_cookie",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584721744,
      "name": "nd_region_interleave_set_cookie",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:373",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/label.c:nd_pmem_namespace_label_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584721744,
      "name": "nd_region_interleave_set_cookie",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
u64 nd_region_interleave_set_cookie(struct nd_region * nd_region)
```

```json
{
  "name": "nd_region_interleave_set_cookie",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585073968,
      "name": "nd_region_interleave_set_cookie",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:485",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces",
        "drivers/nvdimm/label.c:nd_pmem_namespace_label_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585073968,
      "name": "nd_region_interleave_set_cookie",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
u64 nd_region_interleave_set_cookie(struct nd_region * nd_region)
```

```json
{
  "name": "nd_region_interleave_set_cookie",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585258224,
      "name": "nd_region_interleave_set_cookie",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:499",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/label.c:nd_pmem_namespace_label_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585258224,
      "name": "nd_region_interleave_set_cookie",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
u64 nd_region_interleave_set_cookie(struct nd_region * nd_region, struct nd_namespace_index * nsindex)
```

```json
{
  "name": "nd_region_interleave_set_cookie",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585337983,
      "name": "nd_region_interleave_set_cookie",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:599",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:set_cookie_show"
      ],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/label.c:nd_pmem_namespace_label_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585341296,
      "name": "nd_region_interleave_set_cookie",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
u64 nd_region_interleave_set_cookie(struct nd_region * nd_region, struct nd_namespace_index * nsindex)
```

```json
{
  "name": "nd_region_interleave_set_cookie",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585766063,
      "name": "nd_region_interleave_set_cookie",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:618",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:set_cookie_show"
      ],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/label.c:nd_pmem_namespace_label_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585769680,
      "name": "nd_region_interleave_set_cookie",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
u64 nd_region_interleave_set_cookie(struct nd_region * nd_region, struct nd_namespace_index * nsindex)
```

```json
{
  "name": "nd_region_interleave_set_cookie",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586012494,
      "name": "nd_region_interleave_set_cookie",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:657",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:set_cookie_show"
      ],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/label.c:__pmem_label_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586016400,
      "name": "nd_region_interleave_set_cookie",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
u64 nd_region_interleave_set_cookie(struct nd_region * nd_region, struct nd_namespace_index * nsindex)
```

```json
{
  "name": "nd_region_interleave_set_cookie",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586151022,
      "name": "nd_region_interleave_set_cookie",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:685",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:set_cookie_show"
      ],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:scan_labels",
        "drivers/nvdimm/label.c:__pmem_label_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586155232,
      "name": "nd_region_interleave_set_cookie",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
u64 nd_region_interleave_set_cookie(struct nd_region * nd_region, struct nd_namespace_index * nsindex)
```

```json
{
  "name": "nd_region_interleave_set_cookie",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586386295,
      "name": "nd_region_interleave_set_cookie",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:683",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:set_cookie_show"
      ],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/label.c:__pmem_label_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586390480,
      "name": "nd_region_interleave_set_cookie",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
u64 nd_region_interleave_set_cookie(struct nd_region * nd_region, struct nd_namespace_index * nsindex)
```

```json
{
  "name": "nd_region_interleave_set_cookie",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586534007,
      "name": "nd_region_interleave_set_cookie",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:683",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:set_cookie_show"
      ],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/label.c:__pmem_label_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586538320,
      "name": "nd_region_interleave_set_cookie",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
u64 nd_region_interleave_set_cookie(struct nd_region * nd_region, struct nd_namespace_index * nsindex)
```

```json
{
  "name": "nd_region_interleave_set_cookie",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587320660,
      "name": "nd_region_interleave_set_cookie",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:857",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:set_cookie_show"
      ],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/label.c:__pmem_label_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587322160,
      "name": "nd_region_interleave_set_cookie",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
u64 nd_region_interleave_set_cookie(struct nd_region * nd_region, struct nd_namespace_index * nsindex)
```

```json
{
  "name": "nd_region_interleave_set_cookie",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587382596,
      "name": "nd_region_interleave_set_cookie",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:857",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:set_cookie_show"
      ],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/label.c:__pmem_label_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587384096,
      "name": "nd_region_interleave_set_cookie",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
u64 nd_region_interleave_set_cookie(struct nd_region * nd_region, struct nd_namespace_index * nsindex)
```

```json
{
  "name": "nd_region_interleave_set_cookie",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587264372,
      "name": "nd_region_interleave_set_cookie",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:864",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:set_cookie_show"
      ],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/label.c:__pmem_label_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587266224,
      "name": "nd_region_interleave_set_cookie",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
u64 nd_region_interleave_set_cookie(struct nd_region * nd_region, struct nd_namespace_index * nsindex)
```

```json
{
  "name": "nd_region_interleave_set_cookie",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587828020,
      "name": "nd_region_interleave_set_cookie",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:864",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:set_cookie_show"
      ],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/label.c:__pmem_label_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587833424,
      "name": "nd_region_interleave_set_cookie",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
u64 nd_region_interleave_set_cookie(struct nd_region * nd_region, struct nd_namespace_index * nsindex)
```

```json
{
  "name": "nd_region_interleave_set_cookie",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589175951,
      "name": "nd_region_interleave_set_cookie",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:807",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:set_cookie_show"
      ],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/label.c:__pmem_label_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589185584,
      "name": "nd_region_interleave_set_cookie",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
u64 nd_region_interleave_set_cookie(struct nd_region * nd_region, struct nd_namespace_index * nsindex)
```

```json
{
  "name": "nd_region_interleave_set_cookie",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590729055,
      "name": "nd_region_interleave_set_cookie",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:852",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:set_cookie_show"
      ],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/label.c:__pmem_label_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590739584,
      "name": "nd_region_interleave_set_cookie",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
u64 nd_region_interleave_set_cookie(struct nd_region * nd_region, struct nd_namespace_index * nsindex)
```

```json
{
  "name": "nd_region_interleave_set_cookie",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591070383,
      "name": "nd_region_interleave_set_cookie",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:852",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:set_cookie_show"
      ],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/label.c:__pmem_label_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591080944,
      "name": "nd_region_interleave_set_cookie",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
u64 nd_region_interleave_set_cookie(struct nd_region * nd_region, struct nd_namespace_index * nsindex)
```

```json
{
  "name": "nd_region_interleave_set_cookie",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591414863,
      "name": "nd_region_interleave_set_cookie",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:853",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:set_cookie_show"
      ],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/label.c:__pmem_label_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591425840,
      "name": "nd_region_interleave_set_cookie",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
u64 nd_region_interleave_set_cookie(struct nd_region * nd_region, struct nd_namespace_index * nsindex)
```

```json
{
  "name": "nd_region_interleave_set_cookie",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336499422104,
      "name": "nd_region_interleave_set_cookie",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:683",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:set_cookie_show"
      ],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/label.c:__pmem_label_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499427208,
      "name": "nd_region_interleave_set_cookie",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
u64 nd_region_interleave_set_cookie(struct nd_region * nd_region, struct nd_namespace_index * nsindex)
```

```json
{
  "name": "nd_region_interleave_set_cookie",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055292665616,
      "name": "nd_region_interleave_set_cookie",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:683",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:set_cookie_show"
      ],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/label.c:__pmem_label_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292672112,
      "name": "nd_region_interleave_set_cookie",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
u64 nd_region_interleave_set_cookie(struct nd_region * nd_region, struct nd_namespace_index * nsindex)
```

```json
{
  "name": "nd_region_interleave_set_cookie",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276649766,
      "name": "nd_region_interleave_set_cookie",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:683",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:set_cookie_show"
      ],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/label.c:__pmem_label_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276653878,
      "name": "nd_region_interleave_set_cookie",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
u64 nd_region_interleave_set_cookie(struct nd_region * nd_region, struct nd_namespace_index * nsindex)
```

```json
{
  "name": "nd_region_interleave_set_cookie",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586224487,
      "name": "nd_region_interleave_set_cookie",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:683",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:set_cookie_show"
      ],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/label.c:__pmem_label_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586228800,
      "name": "nd_region_interleave_set_cookie",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
u64 nd_region_interleave_set_cookie(struct nd_region * nd_region, struct nd_namespace_index * nsindex)
```

```json
{
  "name": "nd_region_interleave_set_cookie",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586042855,
      "name": "nd_region_interleave_set_cookie",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:683",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:set_cookie_show"
      ],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/label.c:__pmem_label_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586047168,
      "name": "nd_region_interleave_set_cookie",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
u64 nd_region_interleave_set_cookie(struct nd_region * nd_region, struct nd_namespace_index * nsindex)
```

```json
{
  "name": "nd_region_interleave_set_cookie",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586481975,
      "name": "nd_region_interleave_set_cookie",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:683",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:set_cookie_show"
      ],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/label.c:__pmem_label_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586486288,
      "name": "nd_region_interleave_set_cookie",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
u64 nd_region_interleave_set_cookie(struct nd_region * nd_region, struct nd_namespace_index * nsindex)
```

```json
{
  "name": "nd_region_interleave_set_cookie",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586593719,
      "name": "nd_region_interleave_set_cookie",
      "external": true,
      "loc": "drivers/nvdimm/region_devs.c:683",
      "file": "drivers/nvdimm/region_devs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/nvdimm/region_devs.c:set_cookie_show"
      ],
      "caller_func": [
        "drivers/nvdimm/namespace_devs.c:create_namespace_pmem",
        "drivers/nvdimm/label.c:__pmem_label_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586598032,
      "name": "nd_region_interleave_set_cookie",
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
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct nd_namespace_index * nsindex</code>
</li>
</ul>
</details>
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
u64 nd_region_interleave_set_cookie(struct nd_region * nd_region, struct nd_namespace_index * nsindex)
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
