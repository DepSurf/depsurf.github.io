# Function: <code>__klp_disable_patch</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__klp_disable_patch",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579798192,
      "name": "__klp_disable_patch",
      "external": false,
      "loc": "kernel/livepatch/core.c:420",
      "file": "kernel/livepatch/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/core.c:klp_disable_patch",
        "kernel/livepatch/core.c:enabled_store"
      ],
      "caller_func": [
        "kernel/livepatch/core.c:klp_disable_patch",
        "kernel/livepatch/core.c:enabled_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579798192,
      "name": "__klp_disable_patch.part.6",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__klp_disable_patch",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579828390,
      "name": "__klp_disable_patch",
      "external": false,
      "loc": "kernel/livepatch/core.c:484",
      "file": "kernel/livepatch/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/core.c:enabled_store",
        "kernel/livepatch/core.c:klp_disable_patch"
      ],
      "caller_func": [
        "kernel/livepatch/core.c:enabled_store",
        "kernel/livepatch/core.c:klp_disable_patch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579824560,
      "name": "__klp_disable_patch.part.7",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__klp_disable_patch",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579855958,
      "name": "__klp_disable_patch",
      "external": false,
      "loc": "kernel/livepatch/core.c:482",
      "file": "kernel/livepatch/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/core.c:enabled_store",
        "kernel/livepatch/core.c:klp_disable_patch"
      ],
      "caller_func": [
        "kernel/livepatch/core.c:enabled_store",
        "kernel/livepatch/core.c:klp_disable_patch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579853600,
      "name": "__klp_disable_patch.part.9",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
int __klp_disable_patch(struct klp_patch * patch)
```

```json
{
  "name": "__klp_disable_patch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579858288,
      "name": "__klp_disable_patch",
      "external": false,
      "loc": "kernel/livepatch/core.c:286",
      "file": "kernel/livepatch/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:enabled_store",
        "kernel/livepatch/core.c:klp_disable_patch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579858288,
      "name": "__klp_disable_patch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
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
int __klp_disable_patch(struct klp_patch * patch)
```

```json
{
  "name": "__klp_disable_patch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579899408,
      "name": "__klp_disable_patch",
      "external": false,
      "loc": "kernel/livepatch/core.c:281",
      "file": "kernel/livepatch/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:enabled_store",
        "kernel/livepatch/core.c:klp_disable_patch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579899408,
      "name": "__klp_disable_patch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
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
int __klp_disable_patch(struct klp_patch * patch)
```

```json
{
  "name": "__klp_disable_patch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579933280,
      "name": "__klp_disable_patch",
      "external": false,
      "loc": "kernel/livepatch/core.c:281",
      "file": "kernel/livepatch/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:enabled_store",
        "kernel/livepatch/core.c:klp_disable_patch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579933280,
      "name": "__klp_disable_patch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
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
int __klp_disable_patch(struct klp_patch * patch)
```

```json
{
  "name": "__klp_disable_patch",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579980336,
      "name": "__klp_disable_patch",
      "external": false,
      "loc": "kernel/livepatch/core.c:281",
      "file": "kernel/livepatch/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/core.c:enabled_store",
        "kernel/livepatch/core.c:klp_disable_patch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579980336,
      "name": "__klp_disable_patch",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__klp_disable_patch",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580021392,
      "name": "__klp_disable_patch",
      "external": false,
      "loc": "kernel/livepatch/core.c:872",
      "file": "kernel/livepatch/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/core.c:enabled_store"
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
  "name": "__klp_disable_patch",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580072400,
      "name": "__klp_disable_patch",
      "external": false,
      "loc": "kernel/livepatch/core.c:872",
      "file": "kernel/livepatch/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/core.c:enabled_store"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__klp_disable_patch",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580131600,
      "name": "__klp_disable_patch",
      "external": false,
      "loc": "kernel/livepatch/core.c:925",
      "file": "kernel/livepatch/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/core.c:enabled_store"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__klp_disable_patch",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580109824,
      "name": "__klp_disable_patch",
      "external": false,
      "loc": "kernel/livepatch/core.c:925",
      "file": "kernel/livepatch/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/core.c:enabled_store"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__klp_disable_patch",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580113616,
      "name": "__klp_disable_patch",
      "external": false,
      "loc": "kernel/livepatch/core.c:924",
      "file": "kernel/livepatch/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/core.c:enabled_store"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__klp_disable_patch",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580255988,
      "name": "__klp_disable_patch",
      "external": false,
      "loc": "kernel/livepatch/core.c:924",
      "file": "kernel/livepatch/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/core.c:enabled_store"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__klp_disable_patch",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580425252,
      "name": "__klp_disable_patch",
      "external": false,
      "loc": "kernel/livepatch/core.c:913",
      "file": "kernel/livepatch/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/core.c:enabled_store"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__klp_disable_patch",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580665124,
      "name": "__klp_disable_patch",
      "external": false,
      "loc": "kernel/livepatch/core.c:938",
      "file": "kernel/livepatch/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/core.c:enabled_store"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__klp_disable_patch",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580741316,
      "name": "__klp_disable_patch",
      "external": false,
      "loc": "kernel/livepatch/core.c:966",
      "file": "kernel/livepatch/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/core.c:enabled_store"
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
  "name": "__klp_disable_patch",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580826276,
      "name": "__klp_disable_patch",
      "external": false,
      "loc": "kernel/livepatch/core.c:966",
      "file": "kernel/livepatch/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/core.c:enabled_store"
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
  "name": "__klp_disable_patch",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055284190688,
      "name": "__klp_disable_patch",
      "external": false,
      "loc": "kernel/livepatch/core.c:872",
      "file": "kernel/livepatch/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/core.c:enabled_store"
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
  "name": "__klp_disable_patch",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580041136,
      "name": "__klp_disable_patch",
      "external": false,
      "loc": "kernel/livepatch/core.c:872",
      "file": "kernel/livepatch/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/core.c:enabled_store"
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
  "name": "__klp_disable_patch",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579986448,
      "name": "__klp_disable_patch",
      "external": false,
      "loc": "kernel/livepatch/core.c:872",
      "file": "kernel/livepatch/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/core.c:enabled_store"
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
  "name": "__klp_disable_patch",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580032672,
      "name": "__klp_disable_patch",
      "external": false,
      "loc": "kernel/livepatch/core.c:872",
      "file": "kernel/livepatch/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/core.c:enabled_store"
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
  "name": "__klp_disable_patch",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580083376,
      "name": "__klp_disable_patch",
      "external": false,
      "loc": "kernel/livepatch/core.c:872",
      "file": "kernel/livepatch/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/core.c:enabled_store"
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
int __klp_disable_patch(struct klp_patch * patch)
```
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
<details>
<summary>Removed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➖</summary>

```c
int __klp_disable_patch(struct klp_patch * patch)
```
</details>
</li>
</ul>
