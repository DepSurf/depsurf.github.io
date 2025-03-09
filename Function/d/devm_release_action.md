# Function: <code>devm_release_action</code>

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
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void devm_release_action(struct device * dev, void (*)(void *) action, void * data)
```

```json
{
  "name": "devm_release_action",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586056586,
      "name": "devm_release_action",
      "external": true,
      "loc": "drivers/base/devres.c:771",
      "file": "drivers/base/devres.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memremap.c:devm_memunmap_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586056586,
      "name": "devm_release_action.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071586056160,
      "name": "devm_release_action",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
void devm_release_action(struct device * dev, void (*)(void *) action, void * data)
```

```json
{
  "name": "devm_release_action",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586204304,
      "name": "devm_release_action",
      "external": true,
      "loc": "drivers/base/devres.c:771",
      "file": "drivers/base/devres.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memremap.c:devm_memunmap_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586204304,
      "name": "devm_release_action",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
void devm_release_action(struct device * dev, void (*)(void *) action, void * data)
```

```json
{
  "name": "devm_release_action",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586967488,
      "name": "devm_release_action",
      "external": true,
      "loc": "drivers/base/devres.c:771",
      "file": "drivers/base/devres.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memremap.c:devm_memunmap_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586967488,
      "name": "devm_release_action",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
void devm_release_action(struct device * dev, void (*)(void *) action, void * data)
```

```json
{
  "name": "devm_release_action",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587052560,
      "name": "devm_release_action",
      "external": true,
      "loc": "drivers/base/devres.c:787",
      "file": "drivers/base/devres.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memremap.c:devm_memunmap_pages",
        "drivers/dax/bus.c:dev_dax_shrink",
        "drivers/dax/bus.c:delete_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587052560,
      "name": "devm_release_action",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
void devm_release_action(struct device * dev, void (*)(void *) action, void * data)
```

```json
{
  "name": "devm_release_action",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586936352,
      "name": "devm_release_action",
      "external": true,
      "loc": "drivers/base/devres.c:787",
      "file": "drivers/base/devres.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memremap.c:devm_memunmap_pages",
        "drivers/dax/bus.c:dev_dax_shrink",
        "drivers/dax/bus.c:delete_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586936352,
      "name": "devm_release_action",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void devm_release_action(struct device * dev, void (*)(void *) action, void * data)
```

```json
{
  "name": "devm_release_action",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587499808,
      "name": "devm_release_action",
      "external": true,
      "loc": "drivers/base/devres.c:776",
      "file": "drivers/base/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memremap.c:devm_memunmap_pages",
        "drivers/dax/bus.c:dev_dax_shrink",
        "drivers/dax/bus.c:delete_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587499808,
      "name": "devm_release_action",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void devm_release_action(struct device * dev, void (*)(void *) action, void * data)
```

```json
{
  "name": "devm_release_action",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588823728,
      "name": "devm_release_action",
      "external": true,
      "loc": "drivers/base/devres.c:776",
      "file": "drivers/base/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memremap.c:devm_memunmap_pages",
        "drivers/dax/bus.c:dev_dax_shrink",
        "drivers/dax/bus.c:delete_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588823728,
      "name": "devm_release_action",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void devm_release_action(struct device * dev, void (*)(void *) action, void * data)
```

```json
{
  "name": "devm_release_action",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590323168,
      "name": "devm_release_action",
      "external": true,
      "loc": "drivers/base/devres.c:781",
      "file": "drivers/base/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:get_free_mem_region",
        "mm/memremap.c:devm_memunmap_pages",
        "drivers/dax/bus.c:dev_dax_shrink",
        "drivers/dax/bus.c:delete_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590323168,
      "name": "devm_release_action",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void devm_release_action(struct device * dev, void (*)(void *) action, void * data)
```

```json
{
  "name": "devm_release_action",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590643088,
      "name": "devm_release_action",
      "external": true,
      "loc": "drivers/base/devres.c:782",
      "file": "drivers/base/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:get_free_mem_region",
        "mm/memremap.c:devm_memunmap_pages",
        "drivers/dax/bus.c:dev_dax_shrink",
        "drivers/dax/bus.c:delete_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590643088,
      "name": "devm_release_action",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void devm_release_action(struct device * dev, void (*)(void *) action, void * data)
```

```json
{
  "name": "devm_release_action",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591003184,
      "name": "devm_release_action",
      "external": true,
      "loc": "drivers/base/devres.c:782",
      "file": "drivers/base/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:get_free_mem_region",
        "mm/memremap.c:devm_memunmap_pages",
        "drivers/dax/bus.c:dev_dax_shrink",
        "drivers/dax/bus.c:delete_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591003184,
      "name": "devm_release_action",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
void devm_release_action(struct device * dev, void (*)(void *) action, void * data)
```

```json
{
  "name": "devm_release_action",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336499005720,
      "name": "devm_release_action",
      "external": true,
      "loc": "drivers/base/devres.c:771",
      "file": "drivers/base/devres.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499005720,
      "name": "devm_release_action",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void devm_release_action(struct device * dev, void (*)(void *) action, void * data)
```

```json
{
  "name": "devm_release_action",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3231570828,
      "name": "devm_release_action",
      "external": true,
      "loc": "drivers/base/devres.c:771",
      "file": "drivers/base/devres.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3231570828,
      "name": "devm_release_action",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
void devm_release_action(struct device * dev, void (*)(void *) action, void * data)
```

```json
{
  "name": "devm_release_action",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292165520,
      "name": "devm_release_action",
      "external": true,
      "loc": "drivers/base/devres.c:771",
      "file": "drivers/base/devres.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memremap.c:devm_memunmap_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292165520,
      "name": "devm_release_action",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
void devm_release_action(struct device * dev, void (*)(void *) action, void * data)
```

```json
{
  "name": "devm_release_action",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276377192,
      "name": "devm_release_action",
      "external": true,
      "loc": "drivers/base/devres.c:771",
      "file": "drivers/base/devres.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276377192,
      "name": "devm_release_action",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
void devm_release_action(struct device * dev, void (*)(void *) action, void * data)
```

```json
{
  "name": "devm_release_action",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585964512,
      "name": "devm_release_action",
      "external": true,
      "loc": "drivers/base/devres.c:771",
      "file": "drivers/base/devres.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memremap.c:devm_memunmap_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585964512,
      "name": "devm_release_action",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
void devm_release_action(struct device * dev, void (*)(void *) action, void * data)
```

```json
{
  "name": "devm_release_action",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585813776,
      "name": "devm_release_action",
      "external": true,
      "loc": "drivers/base/devres.c:771",
      "file": "drivers/base/devres.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memremap.c:devm_memunmap_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585813776,
      "name": "devm_release_action",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
void devm_release_action(struct device * dev, void (*)(void *) action, void * data)
```

```json
{
  "name": "devm_release_action",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586154320,
      "name": "devm_release_action",
      "external": true,
      "loc": "drivers/base/devres.c:771",
      "file": "drivers/base/devres.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memremap.c:devm_memunmap_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586154320,
      "name": "devm_release_action",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
void devm_release_action(struct device * dev, void (*)(void *) action, void * data)
```

```json
{
  "name": "devm_release_action",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586263024,
      "name": "devm_release_action",
      "external": true,
      "loc": "drivers/base/devres.c:771",
      "file": "drivers/base/devres.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/memremap.c:devm_memunmap_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586263024,
      "name": "devm_release_action",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 89
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
void devm_release_action(struct device * dev, void (*)(void *) action, void * data)
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
