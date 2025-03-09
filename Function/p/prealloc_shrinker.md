# Function: <code>prealloc_shrinker</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int prealloc_shrinker(struct shrinker * shrinker)
```

```json
{
  "name": "prealloc_shrinker",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580975600,
      "name": "prealloc_shrinker",
      "external": true,
      "loc": "mm/vmscan.c:306",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:register_shrinker",
        "fs/super.c:sget_userns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580975600,
      "name": "prealloc_shrinker",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
int prealloc_shrinker(struct shrinker * shrinker)
```

```json
{
  "name": "prealloc_shrinker",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581052272,
      "name": "prealloc_shrinker",
      "external": true,
      "loc": "mm/vmscan.c:375",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:register_shrinker",
        "mm/workingset.c:workingset_init",
        "fs/super.c:sget_userns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581052272,
      "name": "prealloc_shrinker",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 273
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
int prealloc_shrinker(struct shrinker * shrinker)
```

```json
{
  "name": "prealloc_shrinker",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581116928,
      "name": "prealloc_shrinker",
      "external": true,
      "loc": "mm/vmscan.c:387",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:register_shrinker",
        "mm/workingset.c:workingset_init",
        "fs/super.c:alloc_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581116928,
      "name": "prealloc_shrinker",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 275
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
int prealloc_shrinker(struct shrinker * shrinker)
```

```json
{
  "name": "prealloc_shrinker",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581173968,
      "name": "prealloc_shrinker",
      "external": true,
      "loc": "mm/vmscan.c:385",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:register_shrinker",
        "mm/workingset.c:workingset_init",
        "fs/super.c:alloc_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581173968,
      "name": "prealloc_shrinker",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 275
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
int prealloc_shrinker(struct shrinker * shrinker)
```

```json
{
  "name": "prealloc_shrinker",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581364720,
      "name": "prealloc_shrinker",
      "external": true,
      "loc": "mm/vmscan.c:342",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:register_shrinker",
        "mm/workingset.c:workingset_init",
        "fs/super.c:alloc_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581364720,
      "name": "prealloc_shrinker",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 249
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
int prealloc_shrinker(struct shrinker * shrinker)
```

```json
{
  "name": "prealloc_shrinker",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581408320,
      "name": "prealloc_shrinker",
      "external": true,
      "loc": "mm/vmscan.c:335",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:register_shrinker",
        "mm/workingset.c:workingset_init",
        "fs/super.c:alloc_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581408320,
      "name": "prealloc_shrinker",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 249
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
int prealloc_shrinker(struct shrinker * shrinker)
```

```json
{
  "name": "prealloc_shrinker",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581429408,
      "name": "prealloc_shrinker",
      "external": true,
      "loc": "mm/vmscan.c:568",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:register_shrinker",
        "mm/workingset.c:workingset_init",
        "fs/super.c:alloc_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581429408,
      "name": "prealloc_shrinker",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 460
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
int prealloc_shrinker(struct shrinker * shrinker)
```

```json
{
  "name": "prealloc_shrinker",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581681632,
      "name": "prealloc_shrinker",
      "external": true,
      "loc": "mm/vmscan.c:614",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:register_shrinker",
        "mm/workingset.c:workingset_init",
        "fs/super.c:alloc_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581681632,
      "name": "prealloc_shrinker",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 457
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
int prealloc_shrinker(struct shrinker * shrinker)
```

```json
{
  "name": "prealloc_shrinker",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582058432,
      "name": "prealloc_shrinker",
      "external": true,
      "loc": "mm/vmscan.c:611",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:register_shrinker",
        "mm/workingset.c:workingset_init",
        "fs/super.c:alloc_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582058432,
      "name": "prealloc_shrinker",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 427
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
int prealloc_shrinker(struct shrinker * shrinker, const char * fmt, void (anon))
```

```json
{
  "name": "prealloc_shrinker",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582531136,
      "name": "prealloc_shrinker",
      "external": true,
      "loc": "mm/vmscan.c:670",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/workingset.c:workingset_init",
        "fs/super.c:alloc_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582531136,
      "name": "prealloc_shrinker",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
int prealloc_shrinker(struct shrinker * shrinker, const char * fmt, void (anon))
```

```json
{
  "name": "prealloc_shrinker",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582734576,
      "name": "prealloc_shrinker",
      "external": true,
      "loc": "mm/vmscan.c:722",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/workingset.c:workingset_init",
        "fs/super.c:alloc_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582734576,
      "name": "prealloc_shrinker",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int prealloc_shrinker(struct shrinker * shrinker)
```

```json
{
  "name": "prealloc_shrinker",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492553824,
      "name": "prealloc_shrinker",
      "external": true,
      "loc": "mm/vmscan.c:385",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:register_shrinker",
        "mm/workingset.c:workingset_init",
        "fs/super.c:alloc_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492553824,
      "name": "prealloc_shrinker",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 308
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
int prealloc_shrinker(struct shrinker * shrinker)
```

```json
{
  "name": "prealloc_shrinker",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226416708,
      "name": "prealloc_shrinker",
      "external": true,
      "loc": "mm/vmscan.c:385",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:register_shrinker",
        "mm/workingset.c:workingset_init",
        "fs/super.c:alloc_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226416708,
      "name": "prealloc_shrinker",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int prealloc_shrinker(struct shrinker * shrinker)
```

```json
{
  "name": "prealloc_shrinker",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285857152,
      "name": "prealloc_shrinker",
      "external": true,
      "loc": "mm/vmscan.c:385",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:register_shrinker",
        "mm/workingset.c:workingset_init",
        "fs/super.c:alloc_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285857152,
      "name": "prealloc_shrinker",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 444
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
int prealloc_shrinker(struct shrinker * shrinker)
```

```json
{
  "name": "prealloc_shrinker",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272599694,
      "name": "prealloc_shrinker",
      "external": true,
      "loc": "mm/vmscan.c:385",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:register_shrinker",
        "mm/workingset.c:workingset_init",
        "fs/super.c:alloc_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272599694,
      "name": "prealloc_shrinker",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
int prealloc_shrinker(struct shrinker * shrinker)
```

```json
{
  "name": "prealloc_shrinker",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581142816,
      "name": "prealloc_shrinker",
      "external": true,
      "loc": "mm/vmscan.c:385",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:register_shrinker",
        "mm/workingset.c:workingset_init",
        "fs/super.c:alloc_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581142816,
      "name": "prealloc_shrinker",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 275
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
int prealloc_shrinker(struct shrinker * shrinker)
```

```json
{
  "name": "prealloc_shrinker",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581089760,
      "name": "prealloc_shrinker",
      "external": true,
      "loc": "mm/vmscan.c:385",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:register_shrinker",
        "mm/workingset.c:workingset_init",
        "fs/super.c:alloc_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581089760,
      "name": "prealloc_shrinker",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 275
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
int prealloc_shrinker(struct shrinker * shrinker)
```

```json
{
  "name": "prealloc_shrinker",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581134016,
      "name": "prealloc_shrinker",
      "external": true,
      "loc": "mm/vmscan.c:385",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:register_shrinker",
        "mm/workingset.c:workingset_init",
        "fs/super.c:alloc_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581134016,
      "name": "prealloc_shrinker",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 275
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
int prealloc_shrinker(struct shrinker * shrinker)
```

```json
{
  "name": "prealloc_shrinker",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581196496,
      "name": "prealloc_shrinker",
      "external": true,
      "loc": "mm/vmscan.c:385",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:register_shrinker",
        "mm/workingset.c:workingset_init",
        "fs/super.c:alloc_super"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581196496,
      "name": "prealloc_shrinker",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 275
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
int prealloc_shrinker(struct shrinker * shrinker)
```
</details>
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const char * fmt</code>
</li>
<li>
<b>Param added. </b>
<code>void (anon)</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
int prealloc_shrinker(struct shrinker * shrinker, const char * fmt, void (anon))
```
</details>
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
