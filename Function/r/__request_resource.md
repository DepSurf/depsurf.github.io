# Function: <code>__request_resource</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct resource * __request_resource(struct resource * root, struct resource * new)
```

```json
{
  "name": "__request_resource",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579393888,
      "name": "__request_resource",
      "external": false,
      "loc": "kernel/resource.c:208",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:request_resource",
        "kernel/resource.c:__insert_resource",
        "kernel/resource.c:__insert_resource",
        "kernel/resource.c:devm_request_resource",
        "kernel/resource.c:__request_region",
        "kernel/resource.c:__request_region",
        "kernel/resource.c:allocate_resource",
        "kernel/resource.c:allocate_resource",
        "kernel/resource.c:reserve_region_with_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579393888,
      "name": "__request_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
struct resource * __request_resource(struct resource * root, struct resource * new)
```

```json
{
  "name": "__request_resource",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579405696,
      "name": "__request_resource",
      "external": false,
      "loc": "kernel/resource.c:217",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:devm_request_resource",
        "kernel/resource.c:__request_region",
        "kernel/resource.c:reserve_region_with_split",
        "kernel/resource.c:__insert_resource",
        "kernel/resource.c:__insert_resource",
        "kernel/resource.c:allocate_resource",
        "kernel/resource.c:reallocate_resource",
        "kernel/resource.c:request_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579405696,
      "name": "__request_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
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
struct resource * __request_resource(struct resource * root, struct resource * new)
```

```json
{
  "name": "__request_resource",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579426000,
      "name": "__request_resource",
      "external": false,
      "loc": "kernel/resource.c:217",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:devm_request_resource",
        "kernel/resource.c:__request_region",
        "kernel/resource.c:reserve_region_with_split",
        "kernel/resource.c:__insert_resource",
        "kernel/resource.c:__insert_resource",
        "kernel/resource.c:allocate_resource",
        "kernel/resource.c:reallocate_resource",
        "kernel/resource.c:request_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579426000,
      "name": "__request_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
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
struct resource * __request_resource(struct resource * root, struct resource * new)
```

```json
{
  "name": "__request_resource",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579413760,
      "name": "__request_resource",
      "external": false,
      "loc": "kernel/resource.c:217",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:devm_request_resource",
        "kernel/resource.c:__request_region",
        "kernel/resource.c:reserve_region_with_split",
        "kernel/resource.c:__insert_resource",
        "kernel/resource.c:allocate_resource",
        "kernel/resource.c:reallocate_resource",
        "kernel/resource.c:request_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579413760,
      "name": "__request_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
struct resource * __request_resource(struct resource * root, struct resource * new)
```

```json
{
  "name": "__request_resource",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579441632,
      "name": "__request_resource",
      "external": false,
      "loc": "kernel/resource.c:217",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:devm_request_resource",
        "kernel/resource.c:__request_region",
        "kernel/resource.c:reserve_region_with_split",
        "kernel/resource.c:__insert_resource",
        "kernel/resource.c:allocate_resource",
        "kernel/resource.c:reallocate_resource",
        "kernel/resource.c:request_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579441632,
      "name": "__request_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
struct resource * __request_resource(struct resource * root, struct resource * new)
```

```json
{
  "name": "__request_resource",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579456720,
      "name": "__request_resource",
      "external": false,
      "loc": "kernel/resource.c:184",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:__request_region",
        "kernel/resource.c:reserve_region_with_split",
        "kernel/resource.c:__insert_resource",
        "kernel/resource.c:allocate_resource",
        "kernel/resource.c:reallocate_resource",
        "kernel/resource.c:request_resource_conflict"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579456720,
      "name": "__request_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
struct resource * __request_resource(struct resource * root, struct resource * new)
```

```json
{
  "name": "__request_resource",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579490384,
      "name": "__request_resource",
      "external": false,
      "loc": "kernel/resource.c:184",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:__request_region",
        "kernel/resource.c:reserve_region_with_split",
        "kernel/resource.c:__insert_resource",
        "kernel/resource.c:allocate_resource",
        "kernel/resource.c:reallocate_resource",
        "kernel/resource.c:request_resource_conflict"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579490384,
      "name": "__request_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
struct resource * __request_resource(struct resource * root, struct resource * new)
```

```json
{
  "name": "__request_resource",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579508240,
      "name": "__request_resource",
      "external": false,
      "loc": "kernel/resource.c:185",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:__request_region",
        "kernel/resource.c:reserve_region_with_split",
        "kernel/resource.c:__insert_resource",
        "kernel/resource.c:allocate_resource",
        "kernel/resource.c:reallocate_resource",
        "kernel/resource.c:request_resource_conflict"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579508240,
      "name": "__request_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
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
struct resource * __request_resource(struct resource * root, struct resource * new)
```

```json
{
  "name": "__request_resource",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579534288,
      "name": "__request_resource",
      "external": false,
      "loc": "kernel/resource.c:185",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:__request_region",
        "kernel/resource.c:reserve_region_with_split",
        "kernel/resource.c:__insert_resource",
        "kernel/resource.c:allocate_resource",
        "kernel/resource.c:reallocate_resource",
        "kernel/resource.c:request_resource_conflict"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579534288,
      "name": "__request_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
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
struct resource * __request_resource(struct resource * root, struct resource * new)
```

```json
{
  "name": "__request_resource",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579569410,
      "name": "__request_resource",
      "external": false,
      "loc": "kernel/resource.c:185",
      "file": "kernel/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/resource.c:__insert_resource"
      ],
      "caller_func": [
        "kernel/resource.c:devm_request_resource",
        "kernel/resource.c:__request_region",
        "kernel/resource.c:__reserve_region_with_split",
        "kernel/resource.c:allocate_resource",
        "kernel/resource.c:reallocate_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579565216,
      "name": "__request_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
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
struct resource * __request_resource(struct resource * root, struct resource * new)
```

```json
{
  "name": "__request_resource",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579550818,
      "name": "__request_resource",
      "external": false,
      "loc": "kernel/resource.c:185",
      "file": "kernel/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/resource.c:__insert_resource"
      ],
      "caller_func": [
        "kernel/resource.c:devm_request_resource",
        "kernel/resource.c:__request_region",
        "kernel/resource.c:__reserve_region_with_split",
        "kernel/resource.c:allocate_resource",
        "kernel/resource.c:reallocate_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579546592,
      "name": "__request_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
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
struct resource * __request_resource(struct resource * root, struct resource * new)
```

```json
{
  "name": "__request_resource",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579555474,
      "name": "__request_resource",
      "external": false,
      "loc": "kernel/resource.c:184",
      "file": "kernel/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/resource.c:__insert_resource"
      ],
      "caller_func": [
        "kernel/resource.c:devm_request_resource",
        "kernel/resource.c:__request_region_locked",
        "kernel/resource.c:reserve_region_with_split",
        "kernel/resource.c:allocate_resource",
        "kernel/resource.c:reallocate_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579551072,
      "name": "__request_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
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
struct resource * __request_resource(struct resource * root, struct resource * new)
```

```json
{
  "name": "__request_resource",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579628050,
      "name": "__request_resource",
      "external": false,
      "loc": "kernel/resource.c:184",
      "file": "kernel/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/resource.c:__insert_resource"
      ],
      "caller_func": [
        "kernel/resource.c:devm_request_resource",
        "kernel/resource.c:__request_region_locked",
        "kernel/resource.c:reserve_region_with_split",
        "kernel/resource.c:allocate_resource",
        "kernel/resource.c:reallocate_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579623648,
      "name": "__request_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
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
struct resource * __request_resource(struct resource * root, struct resource * new)
```

```json
{
  "name": "__request_resource",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579723031,
      "name": "__request_resource",
      "external": false,
      "loc": "kernel/resource.c:171",
      "file": "kernel/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/resource.c:__insert_resource"
      ],
      "caller_func": [
        "kernel/resource.c:devm_request_resource",
        "kernel/resource.c:__request_region_locked",
        "kernel/resource.c:reserve_region_with_split",
        "kernel/resource.c:allocate_resource",
        "kernel/resource.c:reallocate_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579717920,
      "name": "__request_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
struct resource * __request_resource(struct resource * root, struct resource * new)
```

```json
{
  "name": "__request_resource",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579850135,
      "name": "__request_resource",
      "external": false,
      "loc": "kernel/resource.c:171",
      "file": "kernel/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/resource.c:__insert_resource"
      ],
      "caller_func": [
        "kernel/resource.c:reserve_setup",
        "kernel/resource.c:devm_request_resource",
        "kernel/resource.c:__request_region_locked",
        "kernel/resource.c:reserve_region_with_split",
        "kernel/resource.c:allocate_resource",
        "kernel/resource.c:reallocate_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579845040,
      "name": "__request_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
struct resource * __request_resource(struct resource * root, struct resource * new)
```

```json
{
  "name": "__request_resource",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579900386,
      "name": "__request_resource",
      "external": false,
      "loc": "kernel/resource.c:171",
      "file": "kernel/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/resource.c:__insert_resource"
      ],
      "caller_func": [
        "kernel/resource.c:reserve_setup",
        "kernel/resource.c:devm_request_resource",
        "kernel/resource.c:__request_region_locked",
        "kernel/resource.c:reserve_region_with_split",
        "kernel/resource.c:reserve_region_with_split",
        "kernel/resource.c:allocate_resource",
        "kernel/resource.c:reallocate_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579895264,
      "name": "__request_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
struct resource * __request_resource(struct resource * root, struct resource * new)
```

```json
{
  "name": "__request_resource",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579939122,
      "name": "__request_resource",
      "external": false,
      "loc": "kernel/resource.c:171",
      "file": "kernel/resource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/resource.c:__insert_resource"
      ],
      "caller_func": [
        "kernel/resource.c:reserve_setup",
        "kernel/resource.c:devm_request_resource",
        "kernel/resource.c:__request_region_locked",
        "kernel/resource.c:reserve_region_with_split",
        "kernel/resource.c:reserve_region_with_split",
        "kernel/resource.c:allocate_resource",
        "kernel/resource.c:reallocate_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579934112,
      "name": "__request_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
struct resource * __request_resource(struct resource * root, struct resource * new)
```

```json
{
  "name": "__request_resource",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490678712,
      "name": "__request_resource",
      "external": false,
      "loc": "kernel/resource.c:185",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:__request_region",
        "kernel/resource.c:reserve_region_with_split",
        "kernel/resource.c:__insert_resource",
        "kernel/resource.c:allocate_resource",
        "kernel/resource.c:reallocate_resource",
        "kernel/resource.c:request_resource_conflict"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490678712,
      "name": "__request_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
struct resource * __request_resource(struct resource * root, struct resource * new)
```

```json
{
  "name": "__request_resource",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224749316,
      "name": "__request_resource",
      "external": false,
      "loc": "kernel/resource.c:185",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:__request_region",
        "kernel/resource.c:reserve_region_with_split",
        "kernel/resource.c:__insert_resource",
        "kernel/resource.c:allocate_resource",
        "kernel/resource.c:allocate_resource",
        "kernel/resource.c:request_resource_conflict"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224749316,
      "name": "__request_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
struct resource * __request_resource(struct resource * root, struct resource * new)
```

```json
{
  "name": "__request_resource",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283502368,
      "name": "__request_resource",
      "external": false,
      "loc": "kernel/resource.c:185",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:__request_region",
        "kernel/resource.c:reserve_region_with_split",
        "kernel/resource.c:__insert_resource",
        "kernel/resource.c:__insert_resource",
        "kernel/resource.c:allocate_resource",
        "kernel/resource.c:reallocate_resource",
        "kernel/resource.c:request_resource_conflict"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283502368,
      "name": "__request_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
struct resource * __request_resource(struct resource * root, struct resource * new)
```

```json
{
  "name": "__request_resource",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271414586,
      "name": "__request_resource",
      "external": false,
      "loc": "kernel/resource.c:185",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:__request_region",
        "kernel/resource.c:reserve_region_with_split",
        "kernel/resource.c:__insert_resource",
        "kernel/resource.c:__insert_resource",
        "kernel/resource.c:allocate_resource",
        "kernel/resource.c:reallocate_resource",
        "kernel/resource.c:request_resource_conflict"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271414586,
      "name": "__request_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
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
struct resource * __request_resource(struct resource * root, struct resource * new)
```

```json
{
  "name": "__request_resource",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579507952,
      "name": "__request_resource",
      "external": false,
      "loc": "kernel/resource.c:185",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:__request_region",
        "kernel/resource.c:reserve_region_with_split",
        "kernel/resource.c:__insert_resource",
        "kernel/resource.c:allocate_resource",
        "kernel/resource.c:reallocate_resource",
        "kernel/resource.c:request_resource_conflict"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579507952,
      "name": "__request_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
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
struct resource * __request_resource(struct resource * root, struct resource * new)
```

```json
{
  "name": "__request_resource",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579436752,
      "name": "__request_resource",
      "external": false,
      "loc": "kernel/resource.c:185",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:__request_region",
        "kernel/resource.c:reserve_region_with_split",
        "kernel/resource.c:__insert_resource",
        "kernel/resource.c:allocate_resource",
        "kernel/resource.c:reallocate_resource",
        "kernel/resource.c:request_resource_conflict"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579436752,
      "name": "__request_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
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
struct resource * __request_resource(struct resource * root, struct resource * new)
```

```json
{
  "name": "__request_resource",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579507872,
      "name": "__request_resource",
      "external": false,
      "loc": "kernel/resource.c:185",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:__request_region",
        "kernel/resource.c:reserve_region_with_split",
        "kernel/resource.c:__insert_resource",
        "kernel/resource.c:allocate_resource",
        "kernel/resource.c:reallocate_resource",
        "kernel/resource.c:request_resource_conflict"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579507872,
      "name": "__request_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
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
struct resource * __request_resource(struct resource * root, struct resource * new)
```

```json
{
  "name": "__request_resource",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579540672,
      "name": "__request_resource",
      "external": false,
      "loc": "kernel/resource.c:185",
      "file": "kernel/resource.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/resource.c:__request_region",
        "kernel/resource.c:reserve_region_with_split",
        "kernel/resource.c:__insert_resource",
        "kernel/resource.c:allocate_resource",
        "kernel/resource.c:reallocate_resource",
        "kernel/resource.c:request_resource_conflict"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579540672,
      "name": "__request_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
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
