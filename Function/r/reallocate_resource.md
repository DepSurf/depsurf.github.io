# Function: <code>reallocate_resource</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "reallocate_resource",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579399167,
      "name": "reallocate_resource",
      "external": false,
      "loc": "kernel/resource.c:642",
      "file": "kernel/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
int reallocate_resource(struct resource * root, struct resource * old, resource_size_t newsize, struct resource_constraint * constraint)
```

```json
{
  "name": "reallocate_resource",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579411088,
      "name": "reallocate_resource",
      "external": false,
      "loc": "kernel/resource.c:673",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:allocate_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579411088,
      "name": "reallocate_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 418
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
int reallocate_resource(struct resource * root, struct resource * old, resource_size_t newsize, struct resource_constraint * constraint)
```

```json
{
  "name": "reallocate_resource",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579431392,
      "name": "reallocate_resource",
      "external": false,
      "loc": "kernel/resource.c:673",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:allocate_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579431392,
      "name": "reallocate_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 418
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
int reallocate_resource(struct resource * root, struct resource * old, resource_size_t newsize, struct resource_constraint * constraint)
```

```json
{
  "name": "reallocate_resource",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579419008,
      "name": "reallocate_resource",
      "external": false,
      "loc": "kernel/resource.c:673",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:allocate_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579419008,
      "name": "reallocate_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 419
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
int reallocate_resource(struct resource * root, struct resource * old, resource_size_t newsize, struct resource_constraint * constraint)
```

```json
{
  "name": "reallocate_resource",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579446976,
      "name": "reallocate_resource",
      "external": false,
      "loc": "kernel/resource.c:691",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:allocate_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579446976,
      "name": "reallocate_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 419
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
int reallocate_resource(struct resource * root, struct resource * old, resource_size_t newsize, struct resource_constraint * constraint)
```

```json
{
  "name": "reallocate_resource",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579461872,
      "name": "reallocate_resource",
      "external": false,
      "loc": "kernel/resource.c:660",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:allocate_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579461872,
      "name": "reallocate_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 432
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
int reallocate_resource(struct resource * root, struct resource * old, resource_size_t newsize, struct resource_constraint * constraint)
```

```json
{
  "name": "reallocate_resource",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579495424,
      "name": "reallocate_resource",
      "external": false,
      "loc": "kernel/resource.c:654",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:allocate_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579495424,
      "name": "reallocate_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 436
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
int reallocate_resource(struct resource * root, struct resource * old, resource_size_t newsize, struct resource_constraint * constraint)
```

```json
{
  "name": "reallocate_resource",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579513376,
      "name": "reallocate_resource",
      "external": false,
      "loc": "kernel/resource.c:668",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:allocate_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579513376,
      "name": "reallocate_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 450
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
int reallocate_resource(struct resource * root, struct resource * old, resource_size_t newsize, struct resource_constraint * constraint)
```

```json
{
  "name": "reallocate_resource",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579539536,
      "name": "reallocate_resource",
      "external": false,
      "loc": "kernel/resource.c:668",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:allocate_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579539536,
      "name": "reallocate_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 450
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
int reallocate_resource(struct resource * root, struct resource * old, resource_size_t newsize, struct resource_constraint * constraint)
```

```json
{
  "name": "reallocate_resource",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579571216,
      "name": "reallocate_resource",
      "external": false,
      "loc": "kernel/resource.c:668",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:allocate_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579571216,
      "name": "reallocate_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 453
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
int reallocate_resource(struct resource * root, struct resource * old, resource_size_t newsize, struct resource_constraint * constraint)
```

```json
{
  "name": "reallocate_resource",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579552624,
      "name": "reallocate_resource",
      "external": false,
      "loc": "kernel/resource.c:675",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:allocate_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579552624,
      "name": "reallocate_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 453
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
int reallocate_resource(struct resource * root, struct resource * old, resource_size_t newsize, struct resource_constraint * constraint)
```

```json
{
  "name": "reallocate_resource",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579557216,
      "name": "reallocate_resource",
      "external": false,
      "loc": "kernel/resource.c:667",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:allocate_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579557216,
      "name": "reallocate_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 434
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
int reallocate_resource(struct resource * root, struct resource * old, resource_size_t newsize, struct resource_constraint * constraint)
```

```json
{
  "name": "reallocate_resource",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579629792,
      "name": "reallocate_resource",
      "external": false,
      "loc": "kernel/resource.c:667",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:allocate_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579629792,
      "name": "reallocate_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 434
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
int reallocate_resource(struct resource * root, struct resource * old, resource_size_t newsize, struct resource_constraint * constraint)
```

```json
{
  "name": "reallocate_resource",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579725152,
      "name": "reallocate_resource",
      "external": false,
      "loc": "kernel/resource.c:654",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:allocate_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579725152,
      "name": "reallocate_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 454
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
int reallocate_resource(struct resource * root, struct resource * old, resource_size_t newsize, struct resource_constraint * constraint)
```

```json
{
  "name": "reallocate_resource",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579854768,
      "name": "reallocate_resource",
      "external": false,
      "loc": "kernel/resource.c:655",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:allocate_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579854768,
      "name": "reallocate_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 454
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
int reallocate_resource(struct resource * root, struct resource * old, resource_size_t newsize, struct resource_constraint * constraint)
```

```json
{
  "name": "reallocate_resource",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579904976,
      "name": "reallocate_resource",
      "external": false,
      "loc": "kernel/resource.c:655",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:allocate_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579904976,
      "name": "reallocate_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 437
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
int reallocate_resource(struct resource * root, struct resource * old, resource_size_t newsize, struct resource_constraint * constraint)
```

```json
{
  "name": "reallocate_resource",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579944192,
      "name": "reallocate_resource",
      "external": false,
      "loc": "kernel/resource.c:710",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:allocate_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579944192,
      "name": "reallocate_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 437
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
int reallocate_resource(struct resource * root, struct resource * old, resource_size_t newsize, struct resource_constraint * constraint)
```

```json
{
  "name": "reallocate_resource",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490686016,
      "name": "reallocate_resource",
      "external": false,
      "loc": "kernel/resource.c:668",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:allocate_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490686016,
      "name": "reallocate_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 540
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "reallocate_resource",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3224755396,
      "name": "reallocate_resource",
      "external": false,
      "loc": "kernel/resource.c:668",
      "file": "kernel/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int reallocate_resource(struct resource * root, struct resource * old, resource_size_t newsize, struct resource_constraint * constraint)
```

```json
{
  "name": "reallocate_resource",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283510864,
      "name": "reallocate_resource",
      "external": false,
      "loc": "kernel/resource.c:668",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:allocate_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283510864,
      "name": "reallocate_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 596
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
int reallocate_resource(struct resource * root, struct resource * old, resource_size_t newsize, struct resource_constraint * constraint)
```

```json
{
  "name": "reallocate_resource",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271419690,
      "name": "reallocate_resource",
      "external": false,
      "loc": "kernel/resource.c:668",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:allocate_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271419690,
      "name": "reallocate_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 350
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
int reallocate_resource(struct resource * root, struct resource * old, resource_size_t newsize, struct resource_constraint * constraint)
```

```json
{
  "name": "reallocate_resource",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579513200,
      "name": "reallocate_resource",
      "external": false,
      "loc": "kernel/resource.c:668",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:allocate_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579513200,
      "name": "reallocate_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 450
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
int reallocate_resource(struct resource * root, struct resource * old, resource_size_t newsize, struct resource_constraint * constraint)
```

```json
{
  "name": "reallocate_resource",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579442000,
      "name": "reallocate_resource",
      "external": false,
      "loc": "kernel/resource.c:668",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:allocate_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579442000,
      "name": "reallocate_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 450
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
int reallocate_resource(struct resource * root, struct resource * old, resource_size_t newsize, struct resource_constraint * constraint)
```

```json
{
  "name": "reallocate_resource",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579513120,
      "name": "reallocate_resource",
      "external": false,
      "loc": "kernel/resource.c:668",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:allocate_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579513120,
      "name": "reallocate_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 450
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
int reallocate_resource(struct resource * root, struct resource * old, resource_size_t newsize, struct resource_constraint * constraint)
```

```json
{
  "name": "reallocate_resource",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579546048,
      "name": "reallocate_resource",
      "external": false,
      "loc": "kernel/resource.c:668",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:allocate_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579546048,
      "name": "reallocate_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 455
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
int reallocate_resource(struct resource * root, struct resource * old, resource_size_t newsize, struct resource_constraint * constraint)
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int reallocate_resource(struct resource * root, struct resource * old, resource_size_t newsize, struct resource_constraint * constraint)
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
