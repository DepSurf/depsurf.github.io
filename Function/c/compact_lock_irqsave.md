# Function: <code>compact_lock_irqsave</code>

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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "compact_lock_irqsave",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581219904,
      "name": "compact_lock_irqsave",
      "external": false,
      "loc": "mm/compaction.c:481",
      "file": "mm/compaction.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_freepages_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581219904,
      "name": "compact_lock_irqsave.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "compact_lock_irqsave",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581278464,
      "name": "compact_lock_irqsave",
      "external": false,
      "loc": "mm/compaction.c:482",
      "file": "mm/compaction.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_freepages_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581278464,
      "name": "compact_lock_irqsave.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
bool compact_lock_irqsave(spinlock_t * lock, long unsigned int * flags, struct compact_control * cc)
```

```json
{
  "name": "compact_lock_irqsave",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581463600,
      "name": "compact_lock_irqsave",
      "external": false,
      "loc": "mm/compaction.c:482",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_freepages_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581463600,
      "name": "compact_lock_irqsave",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
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
bool compact_lock_irqsave(spinlock_t * lock, long unsigned int * flags, struct compact_control * cc)
```

```json
{
  "name": "compact_lock_irqsave",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581504720,
      "name": "compact_lock_irqsave",
      "external": false,
      "loc": "mm/compaction.c:499",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_freepages_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581504720,
      "name": "compact_lock_irqsave",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 106
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
bool compact_lock_irqsave(spinlock_t * lock, long unsigned int * flags, struct compact_control * cc)
```

```json
{
  "name": "compact_lock_irqsave",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581526816,
      "name": "compact_lock_irqsave",
      "external": false,
      "loc": "mm/compaction.c:498",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_freepages_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581526816,
      "name": "compact_lock_irqsave",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
bool compact_lock_irqsave(spinlock_t * lock, long unsigned int * flags, struct compact_control * cc)
```

```json
{
  "name": "compact_lock_irqsave",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "compact_lock_irqsave",
      "external": false,
      "loc": "mm/compaction.c:496",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_freepages_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581793472,
      "name": "compact_lock_irqsave",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
    },
    {
      "addr": 18446744071592195613,
      "name": "compact_lock_irqsave.cold",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
bool compact_lock_irqsave(spinlock_t * lock, long unsigned int * flags, struct compact_control * cc)
```

```json
{
  "name": "compact_lock_irqsave",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "compact_lock_irqsave",
      "external": false,
      "loc": "mm/compaction.c:495",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_freepages_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582181168,
      "name": "compact_lock_irqsave",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
    },
    {
      "addr": 18446744071593972189,
      "name": "compact_lock_irqsave.cold",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
bool compact_lock_irqsave(spinlock_t * lock, long unsigned int * flags, struct compact_control * cc)
```

```json
{
  "name": "compact_lock_irqsave",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "compact_lock_irqsave",
      "external": false,
      "loc": "mm/compaction.c:490",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_freepages_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582666512,
      "name": "compact_lock_irqsave",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
    },
    {
      "addr": 18446744071596029237,
      "name": "compact_lock_irqsave.cold",
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
bool compact_lock_irqsave(spinlock_t * lock, long unsigned int * flags, struct compact_control * cc)
```

```json
{
  "name": "compact_lock_irqsave",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "compact_lock_irqsave",
      "external": false,
      "loc": "mm/compaction.c:508",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_freepages_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582876800,
      "name": "compact_lock_irqsave",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
    },
    {
      "addr": 18446744071596551227,
      "name": "compact_lock_irqsave.cold",
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
bool compact_lock_irqsave(spinlock_t * lock, long unsigned int * flags, struct compact_control * cc)
```

```json
{
  "name": "compact_lock_irqsave",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "compact_lock_irqsave",
      "external": false,
      "loc": "mm/compaction.c:532",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_freepages_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583048032,
      "name": "compact_lock_irqsave",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
    },
    {
      "addr": 18446744071597454691,
      "name": "compact_lock_irqsave.cold",
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "compact_lock_irqsave",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492687504,
      "name": "compact_lock_irqsave",
      "external": false,
      "loc": "mm/compaction.c:482",
      "file": "mm/compaction.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_freepages_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492687504,
      "name": "compact_lock_irqsave.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 292
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
bool compact_lock_irqsave(spinlock_t * lock, long unsigned int * flags, struct compact_control * cc)
```

```json
{
  "name": "compact_lock_irqsave",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226517404,
      "name": "compact_lock_irqsave",
      "external": false,
      "loc": "mm/compaction.c:482",
      "file": "mm/compaction.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_freepages_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226517404,
      "name": "compact_lock_irqsave",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "compact_lock_irqsave",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055286014080,
      "name": "compact_lock_irqsave",
      "external": false,
      "loc": "mm/compaction.c:482",
      "file": "mm/compaction.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_freepages_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286014080,
      "name": "compact_lock_irqsave.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "compact_lock_irqsave",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272689232,
      "name": "compact_lock_irqsave",
      "external": false,
      "loc": "mm/compaction.c:482",
      "file": "mm/compaction.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_freepages_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272689232,
      "name": "compact_lock_irqsave.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "compact_lock_irqsave",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581247312,
      "name": "compact_lock_irqsave",
      "external": false,
      "loc": "mm/compaction.c:482",
      "file": "mm/compaction.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_freepages_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581247312,
      "name": "compact_lock_irqsave.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "compact_lock_irqsave",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581193984,
      "name": "compact_lock_irqsave",
      "external": false,
      "loc": "mm/compaction.c:482",
      "file": "mm/compaction.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_freepages_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581193984,
      "name": "compact_lock_irqsave.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "compact_lock_irqsave",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581238512,
      "name": "compact_lock_irqsave",
      "external": false,
      "loc": "mm/compaction.c:482",
      "file": "mm/compaction.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_freepages_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581238512,
      "name": "compact_lock_irqsave.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "compact_lock_irqsave",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581302048,
      "name": "compact_lock_irqsave",
      "external": false,
      "loc": "mm/compaction.c:482",
      "file": "mm/compaction.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "mm/compaction.c:isolate_migratepages_block",
        "mm/compaction.c:isolate_freepages_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581302048,
      "name": "compact_lock_irqsave.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
bool compact_lock_irqsave(spinlock_t * lock, long unsigned int * flags, struct compact_control * cc)
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
bool compact_lock_irqsave(spinlock_t * lock, long unsigned int * flags, struct compact_control * cc)
```
</details>
</li>
</ul>
