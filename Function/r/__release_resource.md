# Function: <code>__release_resource</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__release_resource",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579394089,
      "name": "__release_resource",
      "external": false,
      "loc": "kernel/resource.c:236",
      "file": "kernel/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/resource.c:release_resource",
        "kernel/resource.c:allocate_resource"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int __release_resource(struct resource * old, bool release_child)
```

```json
{
  "name": "__release_resource",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579405808,
      "name": "__release_resource",
      "external": false,
      "loc": "kernel/resource.c:245",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:remove_resource",
        "kernel/resource.c:reallocate_resource",
        "kernel/resource.c:release_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579405808,
      "name": "__release_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
int __release_resource(struct resource * old, bool release_child)
```

```json
{
  "name": "__release_resource",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579426112,
      "name": "__release_resource",
      "external": false,
      "loc": "kernel/resource.c:245",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:remove_resource",
        "kernel/resource.c:reallocate_resource",
        "kernel/resource.c:release_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579426112,
      "name": "__release_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int __release_resource(struct resource * old, bool release_child)
```

```json
{
  "name": "__release_resource",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579413872,
      "name": "__release_resource",
      "external": false,
      "loc": "kernel/resource.c:245",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:remove_resource",
        "kernel/resource.c:reallocate_resource",
        "kernel/resource.c:release_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579413872,
      "name": "__release_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int __release_resource(struct resource * old, bool release_child)
```

```json
{
  "name": "__release_resource",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579441744,
      "name": "__release_resource",
      "external": false,
      "loc": "kernel/resource.c:245",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:remove_resource",
        "kernel/resource.c:reallocate_resource",
        "kernel/resource.c:release_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579441744,
      "name": "__release_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int __release_resource(struct resource * old, bool release_child)
```

```json
{
  "name": "__release_resource",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579456832,
      "name": "__release_resource",
      "external": false,
      "loc": "kernel/resource.c:212",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:remove_resource",
        "kernel/resource.c:reallocate_resource",
        "kernel/resource.c:release_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579456832,
      "name": "__release_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
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
int __release_resource(struct resource * old, bool release_child)
```

```json
{
  "name": "__release_resource",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579490496,
      "name": "__release_resource",
      "external": false,
      "loc": "kernel/resource.c:212",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:remove_resource",
        "kernel/resource.c:reallocate_resource",
        "kernel/resource.c:release_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579490496,
      "name": "__release_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
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
int __release_resource(struct resource * old, bool release_child)
```

```json
{
  "name": "__release_resource",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579508336,
      "name": "__release_resource",
      "external": false,
      "loc": "kernel/resource.c:213",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:remove_resource",
        "kernel/resource.c:reallocate_resource",
        "kernel/resource.c:release_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579508336,
      "name": "__release_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
int __release_resource(struct resource * old, bool release_child)
```

```json
{
  "name": "__release_resource",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579534384,
      "name": "__release_resource",
      "external": false,
      "loc": "kernel/resource.c:213",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:remove_resource",
        "kernel/resource.c:reallocate_resource",
        "kernel/resource.c:release_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579534384,
      "name": "__release_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int __release_resource(struct resource * old, bool release_child)
```

```json
{
  "name": "__release_resource",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579565312,
      "name": "__release_resource",
      "external": false,
      "loc": "kernel/resource.c:213",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:devm_resource_release",
        "kernel/resource.c:remove_resource",
        "kernel/resource.c:reallocate_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579565312,
      "name": "__release_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int __release_resource(struct resource * old, bool release_child)
```

```json
{
  "name": "__release_resource",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579546688,
      "name": "__release_resource",
      "external": false,
      "loc": "kernel/resource.c:213",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:devm_resource_release",
        "kernel/resource.c:remove_resource",
        "kernel/resource.c:reallocate_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579546688,
      "name": "__release_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int __release_resource(struct resource * old, bool release_child)
```

```json
{
  "name": "__release_resource",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579551168,
      "name": "__release_resource",
      "external": false,
      "loc": "kernel/resource.c:212",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:devm_resource_release",
        "kernel/resource.c:remove_resource",
        "kernel/resource.c:reallocate_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579551168,
      "name": "__release_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
int __release_resource(struct resource * old, bool release_child)
```

```json
{
  "name": "__release_resource",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579623744,
      "name": "__release_resource",
      "external": false,
      "loc": "kernel/resource.c:212",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:devm_resource_release",
        "kernel/resource.c:remove_resource",
        "kernel/resource.c:reallocate_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579623744,
      "name": "__release_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
int __release_resource(struct resource * old, bool release_child)
```

```json
{
  "name": "__release_resource",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579718048,
      "name": "__release_resource",
      "external": false,
      "loc": "kernel/resource.c:199",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:devm_resource_release",
        "kernel/resource.c:remove_resource",
        "kernel/resource.c:reallocate_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579718048,
      "name": "__release_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 157
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
int __release_resource(struct resource * old, bool release_child)
```

```json
{
  "name": "__release_resource",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579845184,
      "name": "__release_resource",
      "external": false,
      "loc": "kernel/resource.c:199",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:get_free_mem_region",
        "kernel/resource.c:devm_resource_release",
        "kernel/resource.c:reallocate_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579845184,
      "name": "__release_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 157
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
int __release_resource(struct resource * old, bool release_child)
```

```json
{
  "name": "__release_resource",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579895408,
      "name": "__release_resource",
      "external": false,
      "loc": "kernel/resource.c:199",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:get_free_mem_region",
        "kernel/resource.c:devm_resource_release",
        "kernel/resource.c:reallocate_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579895408,
      "name": "__release_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 157
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
int __release_resource(struct resource * old, bool release_child)
```

```json
{
  "name": "__release_resource",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579934256,
      "name": "__release_resource",
      "external": false,
      "loc": "kernel/resource.c:199",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:get_free_mem_region",
        "kernel/resource.c:devm_resource_release",
        "kernel/resource.c:reallocate_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579934256,
      "name": "__release_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 157
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "__release_resource",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336490681500,
      "name": "__release_resource",
      "external": false,
      "loc": "kernel/resource.c:213",
      "file": "kernel/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/resource.c:remove_resource",
        "kernel/resource.c:reallocate_resource",
        "kernel/resource.c:release_resource"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "__release_resource",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3224751940,
      "name": "__release_resource",
      "external": false,
      "loc": "kernel/resource.c:213",
      "file": "kernel/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/resource.c:remove_resource",
        "kernel/resource.c:allocate_resource",
        "kernel/resource.c:release_resource"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "__release_resource",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055283507268,
      "name": "__release_resource",
      "external": false,
      "loc": "kernel/resource.c:213",
      "file": "kernel/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/resource.c:remove_resource",
        "kernel/resource.c:reallocate_resource",
        "kernel/resource.c:release_resource"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "__release_resource",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271417050,
      "name": "__release_resource",
      "external": false,
      "loc": "kernel/resource.c:213",
      "file": "kernel/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/resource.c:remove_resource",
        "kernel/resource.c:reallocate_resource",
        "kernel/resource.c:release_resource"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
int __release_resource(struct resource * old, bool release_child)
```

```json
{
  "name": "__release_resource",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579508048,
      "name": "__release_resource",
      "external": false,
      "loc": "kernel/resource.c:213",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:remove_resource",
        "kernel/resource.c:reallocate_resource",
        "kernel/resource.c:release_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579508048,
      "name": "__release_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
int __release_resource(struct resource * old, bool release_child)
```

```json
{
  "name": "__release_resource",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579436848,
      "name": "__release_resource",
      "external": false,
      "loc": "kernel/resource.c:213",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:remove_resource",
        "kernel/resource.c:reallocate_resource",
        "kernel/resource.c:release_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579436848,
      "name": "__release_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
int __release_resource(struct resource * old, bool release_child)
```

```json
{
  "name": "__release_resource",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579507968,
      "name": "__release_resource",
      "external": false,
      "loc": "kernel/resource.c:213",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:remove_resource",
        "kernel/resource.c:reallocate_resource",
        "kernel/resource.c:release_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579507968,
      "name": "__release_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
int __release_resource(struct resource * old, bool release_child)
```

```json
{
  "name": "__release_resource",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579540768,
      "name": "__release_resource",
      "external": false,
      "loc": "kernel/resource.c:213",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:remove_resource",
        "kernel/resource.c:reallocate_resource",
        "kernel/resource.c:release_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579540768,
      "name": "__release_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
int __release_resource(struct resource * old, bool release_child)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int __release_resource(struct resource * old, bool release_child)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int __release_resource(struct resource * old, bool release_child)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int __release_resource(struct resource * old, bool release_child)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int __release_resource(struct resource * old, bool release_child)
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
