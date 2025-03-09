# Function: <code>klp_patch_func</code>

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
  "name": "klp_patch_func",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579863403,
      "name": "klp_patch_func",
      "external": false,
      "loc": "kernel/livepatch/patch.c:171",
      "file": "kernel/livepatch/patch.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/patch.c:klp_patch_object"
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
  "name": "klp_patch_func",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579904939,
      "name": "klp_patch_func",
      "external": false,
      "loc": "kernel/livepatch/patch.c:172",
      "file": "kernel/livepatch/patch.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/patch.c:klp_patch_object"
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
  "name": "klp_patch_func",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579939228,
      "name": "klp_patch_func",
      "external": false,
      "loc": "kernel/livepatch/patch.c:172",
      "file": "kernel/livepatch/patch.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/patch.c:klp_patch_object"
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
  "name": "klp_patch_func",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579986316,
      "name": "klp_patch_func",
      "external": false,
      "loc": "kernel/livepatch/patch.c:172",
      "file": "kernel/livepatch/patch.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/patch.c:klp_patch_object"
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
  "name": "klp_patch_func",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580027884,
      "name": "klp_patch_func",
      "external": false,
      "loc": "kernel/livepatch/patch.c:169",
      "file": "kernel/livepatch/patch.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/patch.c:klp_patch_object"
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
  "name": "klp_patch_func",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580078780,
      "name": "klp_patch_func",
      "external": false,
      "loc": "kernel/livepatch/patch.c:169",
      "file": "kernel/livepatch/patch.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/patch.c:klp_patch_object"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int klp_patch_func(struct klp_func * func)
```

```json
{
  "name": "klp_patch_func",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "klp_patch_func",
      "external": false,
      "loc": "kernel/livepatch/patch.c:169",
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
      "addr": 18446744071580137584,
      "name": "klp_patch_func",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 349
    },
    {
      "addr": 18446744071580138466,
      "name": "klp_patch_func.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int klp_patch_func(struct klp_func * func)
```

```json
{
  "name": "klp_patch_func",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "klp_patch_func",
      "external": false,
      "loc": "kernel/livepatch/patch.c:174",
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
      "addr": 18446744071580114960,
      "name": "klp_patch_func",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 349
    },
    {
      "addr": 18446744071591310092,
      "name": "klp_patch_func.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int klp_patch_func(struct klp_func * func)
```

```json
{
  "name": "klp_patch_func",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "klp_patch_func",
      "external": false,
      "loc": "kernel/livepatch/patch.c:174",
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
      "addr": 18446744071580118544,
      "name": "klp_patch_func",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 349
    },
    {
      "addr": 18446744071591252444,
      "name": "klp_patch_func.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int klp_patch_func(struct klp_func * func)
```

```json
{
  "name": "klp_patch_func",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "klp_patch_func",
      "external": false,
      "loc": "kernel/livepatch/patch.c:174",
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
      "addr": 18446744071580261088,
      "name": "klp_patch_func",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 375
    },
    {
      "addr": 18446744071592148689,
      "name": "klp_patch_func.cold",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int klp_patch_func(struct klp_func * func)
```

```json
{
  "name": "klp_patch_func",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "klp_patch_func",
      "external": false,
      "loc": "kernel/livepatch/patch.c:160",
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
      "addr": 18446744071580430576,
      "name": "klp_patch_func",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 377
    },
    {
      "addr": 18446744071593921255,
      "name": "klp_patch_func.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
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
int klp_patch_func(struct klp_func * func)
```

```json
{
  "name": "klp_patch_func",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "klp_patch_func",
      "external": false,
      "loc": "kernel/livepatch/patch.c:160",
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
      "addr": 18446744071580672368,
      "name": "klp_patch_func",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 516
    },
    {
      "addr": 18446744071595992607,
      "name": "klp_patch_func.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int klp_patch_func(struct klp_func * func)
```

```json
{
  "name": "klp_patch_func",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "klp_patch_func",
      "external": false,
      "loc": "kernel/livepatch/patch.c:160",
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
      "addr": 18446744071580748704,
      "name": "klp_patch_func",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 516
    },
    {
      "addr": 18446744071596510867,
      "name": "klp_patch_func.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int klp_patch_func(struct klp_func * func)
```

```json
{
  "name": "klp_patch_func",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "klp_patch_func",
      "external": false,
      "loc": "kernel/livepatch/patch.c:160",
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
      "addr": 18446744071580833776,
      "name": "klp_patch_func",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 563
    },
    {
      "addr": 18446744071597409740,
      "name": "klp_patch_func.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
  "name": "klp_patch_func",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055284202704,
      "name": "klp_patch_func",
      "external": false,
      "loc": "kernel/livepatch/patch.c:169",
      "file": "kernel/livepatch/patch.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/patch.c:klp_patch_object"
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
  "name": "klp_patch_func",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580047516,
      "name": "klp_patch_func",
      "external": false,
      "loc": "kernel/livepatch/patch.c:169",
      "file": "kernel/livepatch/patch.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/patch.c:klp_patch_object"
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
  "name": "klp_patch_func",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579992828,
      "name": "klp_patch_func",
      "external": false,
      "loc": "kernel/livepatch/patch.c:169",
      "file": "kernel/livepatch/patch.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/patch.c:klp_patch_object"
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
  "name": "klp_patch_func",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580039052,
      "name": "klp_patch_func",
      "external": false,
      "loc": "kernel/livepatch/patch.c:169",
      "file": "kernel/livepatch/patch.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/patch.c:klp_patch_object"
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
  "name": "klp_patch_func",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580089772,
      "name": "klp_patch_func",
      "external": false,
      "loc": "kernel/livepatch/patch.c:169",
      "file": "kernel/livepatch/patch.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/patch.c:klp_patch_object"
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
int klp_patch_func(struct klp_func * func)
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
