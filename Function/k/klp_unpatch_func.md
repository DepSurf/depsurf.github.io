# Function: <code>klp_unpatch_func</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "klp_unpatch_func",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579863009,
      "name": "klp_unpatch_func",
      "external": false,
      "loc": "kernel/livepatch/patch.c:138",
      "file": "kernel/livepatch/patch.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/patch.c:klp_unpatch_object"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "klp_unpatch_func",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579904529,
      "name": "klp_unpatch_func",
      "external": false,
      "loc": "kernel/livepatch/patch.c:139",
      "file": "kernel/livepatch/patch.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/patch.c:klp_unpatch_object"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "klp_unpatch_func",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579938855,
      "name": "klp_unpatch_func",
      "external": false,
      "loc": "kernel/livepatch/patch.c:139",
      "file": "kernel/livepatch/patch.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/patch.c:klp_unpatch_object"
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
  "name": "klp_unpatch_func",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579985943,
      "name": "klp_unpatch_func",
      "external": false,
      "loc": "kernel/livepatch/patch.c:139",
      "file": "kernel/livepatch/patch.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/patch.c:klp_unpatch_object"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "klp_unpatch_func",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580027239,
      "name": "klp_unpatch_func",
      "external": false,
      "loc": "kernel/livepatch/patch.c:135",
      "file": "kernel/livepatch/patch.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/patch.c:__klp_unpatch_object"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "klp_unpatch_func",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580078167,
      "name": "klp_unpatch_func",
      "external": false,
      "loc": "kernel/livepatch/patch.c:135",
      "file": "kernel/livepatch/patch.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/patch.c:__klp_unpatch_object"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void klp_unpatch_func(struct klp_func * func)
```

```json
{
  "name": "klp_unpatch_func",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580137120,
      "name": "klp_unpatch_func",
      "external": false,
      "loc": "kernel/livepatch/patch.c:135",
      "file": "kernel/livepatch/patch.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/patch.c:klp_patch_object"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580137120,
      "name": "klp_unpatch_func",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 311
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
void klp_unpatch_func(struct klp_func * func)
```

```json
{
  "name": "klp_unpatch_func",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580114496,
      "name": "klp_unpatch_func",
      "external": false,
      "loc": "kernel/livepatch/patch.c:140",
      "file": "kernel/livepatch/patch.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/patch.c:klp_patch_object"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580114496,
      "name": "klp_unpatch_func",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 311
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
void klp_unpatch_func(struct klp_func * func)
```

```json
{
  "name": "klp_unpatch_func",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580118080,
      "name": "klp_unpatch_func",
      "external": false,
      "loc": "kernel/livepatch/patch.c:140",
      "file": "kernel/livepatch/patch.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/patch.c:klp_patch_object"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580118080,
      "name": "klp_unpatch_func",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 311
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "klp_unpatch_func",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592148624,
      "name": "klp_unpatch_func",
      "external": false,
      "loc": "kernel/livepatch/patch.c:140",
      "file": "kernel/livepatch/patch.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/patch.c:__klp_unpatch_object"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void klp_unpatch_func(struct klp_func * func)
```

```json
{
  "name": "klp_unpatch_func",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "klp_unpatch_func",
      "external": false,
      "loc": "kernel/livepatch/patch.c:127",
      "file": "kernel/livepatch/patch.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/patch.c:__klp_unpatch_object"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580429968,
      "name": "klp_unpatch_func",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 389
    },
    {
      "addr": 18446744071593921173,
      "name": "klp_unpatch_func.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
void klp_unpatch_func(struct klp_func * func)
```

```json
{
  "name": "klp_unpatch_func",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "klp_unpatch_func",
      "external": false,
      "loc": "kernel/livepatch/patch.c:127",
      "file": "kernel/livepatch/patch.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/patch.c:__klp_unpatch_object"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580671728,
      "name": "klp_unpatch_func",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 389
    },
    {
      "addr": 18446744071595992525,
      "name": "klp_unpatch_func.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "klp_unpatch_func",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596510808,
      "name": "klp_unpatch_func",
      "external": false,
      "loc": "kernel/livepatch/patch.c:127",
      "file": "kernel/livepatch/patch.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/patch.c:__klp_unpatch_object"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "klp_unpatch_func",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071597409681,
      "name": "klp_unpatch_func",
      "external": false,
      "loc": "kernel/livepatch/patch.c:127",
      "file": "kernel/livepatch/patch.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/patch.c:__klp_unpatch_object"
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
<b>Arch</b>
<ul>
<li>
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "klp_unpatch_func",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055284201796,
      "name": "klp_unpatch_func",
      "external": false,
      "loc": "kernel/livepatch/patch.c:135",
      "file": "kernel/livepatch/patch.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/patch.c:__klp_unpatch_object"
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
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "klp_unpatch_func",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580046903,
      "name": "klp_unpatch_func",
      "external": false,
      "loc": "kernel/livepatch/patch.c:135",
      "file": "kernel/livepatch/patch.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/patch.c:__klp_unpatch_object"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "klp_unpatch_func",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579992215,
      "name": "klp_unpatch_func",
      "external": false,
      "loc": "kernel/livepatch/patch.c:135",
      "file": "kernel/livepatch/patch.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/patch.c:__klp_unpatch_object"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "klp_unpatch_func",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580038439,
      "name": "klp_unpatch_func",
      "external": false,
      "loc": "kernel/livepatch/patch.c:135",
      "file": "kernel/livepatch/patch.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/patch.c:__klp_unpatch_object"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "klp_unpatch_func",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580089159,
      "name": "klp_unpatch_func",
      "external": false,
      "loc": "kernel/livepatch/patch.c:135",
      "file": "kernel/livepatch/patch.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/patch.c:__klp_unpatch_object"
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void klp_unpatch_func(struct klp_func * func)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
void klp_unpatch_func(struct klp_func * func)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
void klp_unpatch_func(struct klp_func * func)
```
</details>
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
void klp_unpatch_func(struct klp_func * func)
```
</details>
</li>
</ul>
