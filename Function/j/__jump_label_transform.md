# Function: <code>__jump_label_transform</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__jump_label_transform",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579056506,
      "name": "__jump_label_transform",
      "external": false,
      "loc": "arch/x86/kernel/jump_label.c:39",
      "file": "arch/x86/kernel/jump_label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/jump_label.c:arch_jump_label_transform",
        "arch/x86/kernel/jump_label.c:arch_jump_label_transform_static"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__jump_label_transform",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579053213,
      "name": "__jump_label_transform",
      "external": false,
      "loc": "arch/x86/kernel/jump_label.c:40",
      "file": "arch/x86/kernel/jump_label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/jump_label.c:arch_jump_label_transform_static",
        "arch/x86/kernel/jump_label.c:arch_jump_label_transform"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__jump_label_transform",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579052317,
      "name": "__jump_label_transform",
      "external": false,
      "loc": "arch/x86/kernel/jump_label.c:40",
      "file": "arch/x86/kernel/jump_label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/jump_label.c:arch_jump_label_transform_static",
        "arch/x86/kernel/jump_label.c:arch_jump_label_transform"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__jump_label_transform",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579044528,
      "name": "__jump_label_transform",
      "external": false,
      "loc": "arch/x86/kernel/jump_label.c:39",
      "file": "arch/x86/kernel/jump_label.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/jump_label.c:arch_jump_label_transform_static",
        "arch/x86/kernel/jump_label.c:arch_jump_label_transform"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579044528,
      "name": "__jump_label_transform.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 274
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__jump_label_transform",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579053248,
      "name": "__jump_label_transform",
      "external": false,
      "loc": "arch/x86/kernel/jump_label.c:40",
      "file": "arch/x86/kernel/jump_label.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/jump_label.c:arch_jump_label_transform_static",
        "arch/x86/kernel/jump_label.c:arch_jump_label_transform"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579053248,
      "name": "__jump_label_transform.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 277
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__jump_label_transform",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579058128,
      "name": "__jump_label_transform",
      "external": false,
      "loc": "arch/x86/kernel/jump_label.c:40",
      "file": "arch/x86/kernel/jump_label.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/jump_label.c:arch_jump_label_transform_static",
        "arch/x86/kernel/jump_label.c:arch_jump_label_transform"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579058128,
      "name": "__jump_label_transform.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 289
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
void __jump_label_transform(struct jump_entry * entry, enum jump_label_type type, void * (*)(void *, const void *, size_t) poker, int init)
```

```json
{
  "name": "__jump_label_transform",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589461424,
      "name": "__jump_label_transform",
      "external": false,
      "loc": "arch/x86/kernel/jump_label.c:38",
      "file": "arch/x86/kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/jump_label.c:arch_jump_label_transform_static",
        "arch/x86/kernel/jump_label.c:arch_jump_label_transform"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589461424,
      "name": "__jump_label_transform",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 268
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
void __jump_label_transform(struct jump_entry * entry, enum jump_label_type type, int init)
```

```json
{
  "name": "__jump_label_transform",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589922224,
      "name": "__jump_label_transform",
      "external": false,
      "loc": "arch/x86/kernel/jump_label.c:67",
      "file": "arch/x86/kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/jump_label.c:arch_jump_label_transform_static",
        "arch/x86/kernel/jump_label.c:arch_jump_label_transform"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589922224,
      "name": "__jump_label_transform",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
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
void __jump_label_transform(struct jump_entry * entry, enum jump_label_type type, int init)
```

```json
{
  "name": "__jump_label_transform",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590148400,
      "name": "__jump_label_transform",
      "external": false,
      "loc": "arch/x86/kernel/jump_label.c:67",
      "file": "arch/x86/kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/jump_label.c:arch_jump_label_transform_static",
        "arch/x86/kernel/jump_label.c:arch_jump_label_transform"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590148400,
      "name": "__jump_label_transform",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__jump_label_transform",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591166771,
      "name": "__jump_label_transform",
      "external": false,
      "loc": "arch/x86/kernel/jump_label.c:61",
      "file": "arch/x86/kernel/jump_label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/jump_label.c:jump_label_transform"
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
  "name": "__jump_label_transform",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591662323,
      "name": "__jump_label_transform",
      "external": false,
      "loc": "arch/x86/kernel/jump_label.c:61",
      "file": "arch/x86/kernel/jump_label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/jump_label.c:jump_label_transform"
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
  "name": "__jump_label_transform",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591606083,
      "name": "__jump_label_transform",
      "external": false,
      "loc": "arch/x86/kernel/jump_label.c:57",
      "file": "arch/x86/kernel/jump_label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/jump_label.c:jump_label_transform"
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
  "name": "__jump_label_transform",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592779299,
      "name": "__jump_label_transform",
      "external": false,
      "loc": "arch/x86/kernel/jump_label.c:83",
      "file": "arch/x86/kernel/jump_label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/jump_label.c:jump_label_transform"
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
  "name": "__jump_label_transform",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594677123,
      "name": "__jump_label_transform",
      "external": false,
      "loc": "arch/x86/kernel/jump_label.c:83",
      "file": "arch/x86/kernel/jump_label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/jump_label.c:jump_label_transform"
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
  "name": "__jump_label_transform",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596412542,
      "name": "__jump_label_transform",
      "external": false,
      "loc": "arch/x86/kernel/jump_label.c:83",
      "file": "arch/x86/kernel/jump_label.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "__jump_label_transform",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596952366,
      "name": "__jump_label_transform",
      "external": false,
      "loc": "arch/x86/kernel/jump_label.c:83",
      "file": "arch/x86/kernel/jump_label.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "__jump_label_transform",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071597879886,
      "name": "__jump_label_transform",
      "external": false,
      "loc": "arch/x86/kernel/jump_label.c:83",
      "file": "arch/x86/kernel/jump_label.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void __jump_label_transform(struct jump_entry * entry, enum jump_label_type type, int init)
```

```json
{
  "name": "__jump_label_transform",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589750688,
      "name": "__jump_label_transform",
      "external": false,
      "loc": "arch/x86/kernel/jump_label.c:67",
      "file": "arch/x86/kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/jump_label.c:arch_jump_label_transform_static",
        "arch/x86/kernel/jump_label.c:arch_jump_label_transform"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589750688,
      "name": "__jump_label_transform",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
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
void __jump_label_transform(struct jump_entry * entry, enum jump_label_type type, int init)
```

```json
{
  "name": "__jump_label_transform",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589474912,
      "name": "__jump_label_transform",
      "external": false,
      "loc": "arch/x86/kernel/jump_label.c:67",
      "file": "arch/x86/kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/jump_label.c:arch_jump_label_transform_static",
        "arch/x86/kernel/jump_label.c:arch_jump_label_transform"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589474912,
      "name": "__jump_label_transform",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
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
void __jump_label_transform(struct jump_entry * entry, enum jump_label_type type, int init)
```

```json
{
  "name": "__jump_label_transform",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590194096,
      "name": "__jump_label_transform",
      "external": false,
      "loc": "arch/x86/kernel/jump_label.c:67",
      "file": "arch/x86/kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/jump_label.c:arch_jump_label_transform_static",
        "arch/x86/kernel/jump_label.c:arch_jump_label_transform"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590194096,
      "name": "__jump_label_transform",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
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
void __jump_label_transform(struct jump_entry * entry, enum jump_label_type type, int init)
```

```json
{
  "name": "__jump_label_transform",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590244528,
      "name": "__jump_label_transform",
      "external": false,
      "loc": "arch/x86/kernel/jump_label.c:67",
      "file": "arch/x86/kernel/jump_label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/jump_label.c:arch_jump_label_transform_static",
        "arch/x86/kernel/jump_label.c:arch_jump_label_transform"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590244528,
      "name": "__jump_label_transform",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
void __jump_label_transform(struct jump_entry * entry, enum jump_label_type type, void * (*)(void *, const void *, size_t) poker, int init)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>void * (*)(void *, const void *, size_t) poker</code>
</li>
<li>
<b>Param reordered. </b>
<code>entry, type, poker, init</code> ➡️ <code>entry, type, init</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void __jump_label_transform(struct jump_entry * entry, enum jump_label_type type, int init)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void __jump_label_transform(struct jump_entry * entry, enum jump_label_type type, int init)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void __jump_label_transform(struct jump_entry * entry, enum jump_label_type type, int init)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void __jump_label_transform(struct jump_entry * entry, enum jump_label_type type, int init)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void __jump_label_transform(struct jump_entry * entry, enum jump_label_type type, int init)
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
