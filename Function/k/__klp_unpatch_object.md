# Function: <code>__klp_unpatch_object</code>

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
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void __klp_unpatch_object(struct klp_object * obj, bool nops_only)
```

```json
{
  "name": "__klp_unpatch_object",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__klp_unpatch_object",
      "external": false,
      "loc": "kernel/livepatch/patch.c:237",
      "file": "kernel/livepatch/patch.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/patch.c:__klp_unpatch_objects",
        "kernel/livepatch/patch.c:klp_patch_object"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580027136,
      "name": "__klp_unpatch_object",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 486
    },
    {
      "addr": 18446744071580028293,
      "name": "__klp_unpatch_object.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
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
void __klp_unpatch_object(struct klp_object * obj, bool nops_only)
```

```json
{
  "name": "__klp_unpatch_object",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580078064,
      "name": "__klp_unpatch_object",
      "external": false,
      "loc": "kernel/livepatch/patch.c:237",
      "file": "kernel/livepatch/patch.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/patch.c:__klp_unpatch_objects",
        "kernel/livepatch/patch.c:klp_patch_object"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580078064,
      "name": "__klp_unpatch_object",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 463
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
void __klp_unpatch_object(struct klp_object * obj, bool nops_only)
```

```json
{
  "name": "__klp_unpatch_object",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580138175,
      "name": "__klp_unpatch_object",
      "external": false,
      "loc": "kernel/livepatch/patch.c:238",
      "file": "kernel/livepatch/patch.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/patch.c:klp_patch_object"
      ],
      "caller_func": [
        "kernel/livepatch/patch.c:klp_unpatch_objects_dynamic",
        "kernel/livepatch/patch.c:klp_unpatch_objects"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580137440,
      "name": "__klp_unpatch_object",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
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
void __klp_unpatch_object(struct klp_object * obj, bool nops_only)
```

```json
{
  "name": "__klp_unpatch_object",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580115551,
      "name": "__klp_unpatch_object",
      "external": false,
      "loc": "kernel/livepatch/patch.c:245",
      "file": "kernel/livepatch/patch.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/patch.c:klp_patch_object"
      ],
      "caller_func": [
        "kernel/livepatch/patch.c:klp_unpatch_objects_dynamic",
        "kernel/livepatch/patch.c:klp_unpatch_objects"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580114816,
      "name": "__klp_unpatch_object",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
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
void __klp_unpatch_object(struct klp_object * obj, bool nops_only)
```

```json
{
  "name": "__klp_unpatch_object",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580119135,
      "name": "__klp_unpatch_object",
      "external": false,
      "loc": "kernel/livepatch/patch.c:245",
      "file": "kernel/livepatch/patch.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/livepatch/patch.c:klp_patch_object"
      ],
      "caller_func": [
        "kernel/livepatch/patch.c:klp_unpatch_objects_dynamic",
        "kernel/livepatch/patch.c:klp_unpatch_objects"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580118400,
      "name": "__klp_unpatch_object",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
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
void __klp_unpatch_object(struct klp_object * obj, bool nops_only)
```

```json
{
  "name": "__klp_unpatch_object",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__klp_unpatch_object",
      "external": false,
      "loc": "kernel/livepatch/patch.c:245",
      "file": "kernel/livepatch/patch.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/patch.c:klp_unpatch_objects_dynamic",
        "kernel/livepatch/patch.c:klp_unpatch_objects",
        "kernel/livepatch/patch.c:klp_patch_object"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580260560,
      "name": "__klp_unpatch_object",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 518
    },
    {
      "addr": 18446744071592148515,
      "name": "__klp_unpatch_object.cold",
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
void __klp_unpatch_object(struct klp_object * obj, bool nops_only)
```

```json
{
  "name": "__klp_unpatch_object",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__klp_unpatch_object",
      "external": false,
      "loc": "kernel/livepatch/patch.c:230",
      "file": "kernel/livepatch/patch.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/patch.c:klp_unpatch_objects_dynamic",
        "kernel/livepatch/patch.c:klp_unpatch_objects",
        "kernel/livepatch/patch.c:klp_patch_object"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580430368,
      "name": "__klp_unpatch_object",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 205
    },
    {
      "addr": 18446744071593921193,
      "name": "__klp_unpatch_object.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
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
void __klp_unpatch_object(struct klp_object * obj, bool nops_only)
```

```json
{
  "name": "__klp_unpatch_object",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__klp_unpatch_object",
      "external": false,
      "loc": "kernel/livepatch/patch.c:230",
      "file": "kernel/livepatch/patch.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/patch.c:klp_unpatch_objects_dynamic",
        "kernel/livepatch/patch.c:klp_unpatch_objects",
        "kernel/livepatch/patch.c:klp_patch_object"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580672144,
      "name": "__klp_unpatch_object",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 205
    },
    {
      "addr": 18446744071595992545,
      "name": "__klp_unpatch_object.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
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
void __klp_unpatch_object(struct klp_object * obj, bool nops_only)
```

```json
{
  "name": "__klp_unpatch_object",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__klp_unpatch_object",
      "external": false,
      "loc": "kernel/livepatch/patch.c:230",
      "file": "kernel/livepatch/patch.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/patch.c:klp_unpatch_objects_dynamic",
        "kernel/livepatch/patch.c:klp_unpatch_objects",
        "kernel/livepatch/patch.c:klp_patch_object"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580748128,
      "name": "__klp_unpatch_object",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 551
    },
    {
      "addr": 18446744071596510727,
      "name": "__klp_unpatch_object.cold",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void __klp_unpatch_object(struct klp_object * obj, bool nops_only)
```

```json
{
  "name": "__klp_unpatch_object",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__klp_unpatch_object",
      "external": false,
      "loc": "kernel/livepatch/patch.c:230",
      "file": "kernel/livepatch/patch.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/patch.c:klp_unpatch_objects_dynamic",
        "kernel/livepatch/patch.c:klp_unpatch_objects",
        "kernel/livepatch/patch.c:klp_patch_object"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580833200,
      "name": "__klp_unpatch_object",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 551
    },
    {
      "addr": 18446744071597409600,
      "name": "__klp_unpatch_object.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void __klp_unpatch_object(struct klp_object * obj, bool nops_only)
```

```json
{
  "name": "__klp_unpatch_object",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284201536,
      "name": "__klp_unpatch_object",
      "external": false,
      "loc": "kernel/livepatch/patch.c:237",
      "file": "kernel/livepatch/patch.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/patch.c:__klp_unpatch_objects",
        "kernel/livepatch/patch.c:klp_patch_object"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284201536,
      "name": "__klp_unpatch_object",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 696
    }
  ]
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void __klp_unpatch_object(struct klp_object * obj, bool nops_only)
```

```json
{
  "name": "__klp_unpatch_object",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580046800,
      "name": "__klp_unpatch_object",
      "external": false,
      "loc": "kernel/livepatch/patch.c:237",
      "file": "kernel/livepatch/patch.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/patch.c:__klp_unpatch_objects",
        "kernel/livepatch/patch.c:klp_patch_object"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580046800,
      "name": "__klp_unpatch_object",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 463
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
void __klp_unpatch_object(struct klp_object * obj, bool nops_only)
```

```json
{
  "name": "__klp_unpatch_object",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579992112,
      "name": "__klp_unpatch_object",
      "external": false,
      "loc": "kernel/livepatch/patch.c:237",
      "file": "kernel/livepatch/patch.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/patch.c:__klp_unpatch_objects",
        "kernel/livepatch/patch.c:klp_patch_object"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579992112,
      "name": "__klp_unpatch_object",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 463
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
void __klp_unpatch_object(struct klp_object * obj, bool nops_only)
```

```json
{
  "name": "__klp_unpatch_object",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580038336,
      "name": "__klp_unpatch_object",
      "external": false,
      "loc": "kernel/livepatch/patch.c:237",
      "file": "kernel/livepatch/patch.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/patch.c:__klp_unpatch_objects",
        "kernel/livepatch/patch.c:klp_patch_object"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580038336,
      "name": "__klp_unpatch_object",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 463
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
void __klp_unpatch_object(struct klp_object * obj, bool nops_only)
```

```json
{
  "name": "__klp_unpatch_object",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580089056,
      "name": "__klp_unpatch_object",
      "external": false,
      "loc": "kernel/livepatch/patch.c:237",
      "file": "kernel/livepatch/patch.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/livepatch/patch.c:__klp_unpatch_objects",
        "kernel/livepatch/patch.c:klp_patch_object"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580089056,
      "name": "__klp_unpatch_object",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 463
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
void __klp_unpatch_object(struct klp_object * obj, bool nops_only)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void __klp_unpatch_object(struct klp_object * obj, bool nops_only)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void __klp_unpatch_object(struct klp_object * obj, bool nops_only)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void __klp_unpatch_object(struct klp_object * obj, bool nops_only)
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
