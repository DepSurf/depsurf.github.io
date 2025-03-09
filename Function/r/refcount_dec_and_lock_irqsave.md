# Function: <code>refcount_dec_and_lock_irqsave</code>

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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool refcount_dec_and_lock_irqsave(refcount_t * r, spinlock_t * lock, long unsigned int * flags)
```

```json
{
  "name": "refcount_dec_and_lock_irqsave",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583881856,
      "name": "refcount_dec_and_lock_irqsave",
      "external": true,
      "loc": "lib/refcount.c:366",
      "file": "lib/refcount.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583881856,
      "name": "refcount_dec_and_lock_irqsave",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
bool refcount_dec_and_lock_irqsave(refcount_t * r, spinlock_t * lock, long unsigned int * flags)
```

```json
{
  "name": "refcount_dec_and_lock_irqsave",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583966032,
      "name": "refcount_dec_and_lock_irqsave",
      "external": true,
      "loc": "lib/refcount.c:365",
      "file": "lib/refcount.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/user.c:free_uid",
        "mm/backing-dev.c:wb_congested_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583966032,
      "name": "refcount_dec_and_lock_irqsave",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
bool refcount_dec_and_lock_irqsave(refcount_t * r, spinlock_t * lock, long unsigned int * flags)
```

```json
{
  "name": "refcount_dec_and_lock_irqsave",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584145904,
      "name": "refcount_dec_and_lock_irqsave",
      "external": true,
      "loc": "lib/refcount.c:373",
      "file": "lib/refcount.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/user.c:free_uid",
        "mm/backing-dev.c:wb_congested_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584145904,
      "name": "refcount_dec_and_lock_irqsave",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
bool refcount_dec_and_lock_irqsave(refcount_t * r, spinlock_t * lock, long unsigned int * flags)
```

```json
{
  "name": "refcount_dec_and_lock_irqsave",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584268352,
      "name": "refcount_dec_and_lock_irqsave",
      "external": true,
      "loc": "lib/refcount.c:373",
      "file": "lib/refcount.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/user.c:free_uid",
        "mm/backing-dev.c:wb_congested_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584268352,
      "name": "refcount_dec_and_lock_irqsave",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
bool refcount_dec_and_lock_irqsave(refcount_t * r, spinlock_t * lock, long unsigned int * flags)
```

```json
{
  "name": "refcount_dec_and_lock_irqsave",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584676160,
      "name": "refcount_dec_and_lock_irqsave",
      "external": true,
      "loc": "lib/refcount.c:172",
      "file": "lib/refcount.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/user.c:free_uid",
        "mm/backing-dev.c:wb_congested_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584676160,
      "name": "refcount_dec_and_lock_irqsave",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
bool refcount_dec_and_lock_irqsave(refcount_t * r, spinlock_t * lock, long unsigned int * flags)
```

```json
{
  "name": "refcount_dec_and_lock_irqsave",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584793712,
      "name": "refcount_dec_and_lock_irqsave",
      "external": true,
      "loc": "lib/refcount.c:172",
      "file": "lib/refcount.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/user.c:free_uid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584793712,
      "name": "refcount_dec_and_lock_irqsave",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
bool refcount_dec_and_lock_irqsave(refcount_t * r, spinlock_t * lock, long unsigned int * flags)
```

```json
{
  "name": "refcount_dec_and_lock_irqsave",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584837952,
      "name": "refcount_dec_and_lock_irqsave",
      "external": true,
      "loc": "lib/refcount.c:172",
      "file": "lib/refcount.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/user.c:free_uid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584837952,
      "name": "refcount_dec_and_lock_irqsave",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool refcount_dec_and_lock_irqsave(refcount_t * r, spinlock_t * lock, long unsigned int * flags)
```

```json
{
  "name": "refcount_dec_and_lock_irqsave",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585257378,
      "name": "refcount_dec_and_lock_irqsave",
      "external": true,
      "loc": "lib/refcount.c:172",
      "file": "lib/refcount.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/user.c:free_uid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592324598,
      "name": "refcount_dec_and_lock_irqsave.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071585257328,
      "name": "refcount_dec_and_lock_irqsave",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
bool refcount_dec_and_lock_irqsave(refcount_t * r, spinlock_t * lock, long unsigned int * flags)
```

```json
{
  "name": "refcount_dec_and_lock_irqsave",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "refcount_dec_and_lock_irqsave",
      "external": true,
      "loc": "lib/refcount.c:172",
      "file": "lib/refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/user.c:free_uid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594129094,
      "name": "refcount_dec_and_lock_irqsave.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071586099968,
      "name": "refcount_dec_and_lock_irqsave",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
bool refcount_dec_and_lock_irqsave(refcount_t * r, spinlock_t * lock, long unsigned int * flags)
```

```json
{
  "name": "refcount_dec_and_lock_irqsave",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "refcount_dec_and_lock_irqsave",
      "external": true,
      "loc": "lib/refcount.c:172",
      "file": "lib/refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/user.c:free_uid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596116110,
      "name": "refcount_dec_and_lock_irqsave.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071587084720,
      "name": "refcount_dec_and_lock_irqsave",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
bool refcount_dec_and_lock_irqsave(refcount_t * r, spinlock_t * lock, long unsigned int * flags)
```

```json
{
  "name": "refcount_dec_and_lock_irqsave",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "refcount_dec_and_lock_irqsave",
      "external": true,
      "loc": "lib/refcount.c:172",
      "file": "lib/refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/user.c:free_uid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596641849,
      "name": "refcount_dec_and_lock_irqsave.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071587343392,
      "name": "refcount_dec_and_lock_irqsave",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
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
bool refcount_dec_and_lock_irqsave(refcount_t * r, spinlock_t * lock, long unsigned int * flags)
```

```json
{
  "name": "refcount_dec_and_lock_irqsave",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "refcount_dec_and_lock_irqsave",
      "external": true,
      "loc": "lib/refcount.c:172",
      "file": "lib/refcount.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/user.c:free_uid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597549914,
      "name": "refcount_dec_and_lock_irqsave.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071587626912,
      "name": "refcount_dec_and_lock_irqsave",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
bool refcount_dec_and_lock_irqsave(refcount_t * r, spinlock_t * lock, long unsigned int * flags)
```

```json
{
  "name": "refcount_dec_and_lock_irqsave",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336496150936,
      "name": "refcount_dec_and_lock_irqsave",
      "external": true,
      "loc": "lib/refcount.c:373",
      "file": "lib/refcount.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/user.c:free_uid",
        "mm/backing-dev.c:wb_congested_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496150936,
      "name": "refcount_dec_and_lock_irqsave",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
bool refcount_dec_and_lock_irqsave(refcount_t * r, spinlock_t * lock, long unsigned int * flags)
```

```json
{
  "name": "refcount_dec_and_lock_irqsave",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3229472944,
      "name": "refcount_dec_and_lock_irqsave",
      "external": true,
      "loc": "lib/refcount.c:373",
      "file": "lib/refcount.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/user.c:free_uid",
        "mm/backing-dev.c:wb_congested_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229472944,
      "name": "refcount_dec_and_lock_irqsave",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
bool refcount_dec_and_lock_irqsave(refcount_t * r, spinlock_t * lock, long unsigned int * flags)
```

```json
{
  "name": "refcount_dec_and_lock_irqsave",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290412608,
      "name": "refcount_dec_and_lock_irqsave",
      "external": true,
      "loc": "lib/refcount.c:373",
      "file": "lib/refcount.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/user.c:free_uid",
        "mm/backing-dev.c:wb_congested_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290412608,
      "name": "refcount_dec_and_lock_irqsave",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
bool refcount_dec_and_lock_irqsave(refcount_t * r, spinlock_t * lock, long unsigned int * flags)
```

```json
{
  "name": "refcount_dec_and_lock_irqsave",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275205530,
      "name": "refcount_dec_and_lock_irqsave",
      "external": true,
      "loc": "lib/refcount.c:373",
      "file": "lib/refcount.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/user.c:free_uid",
        "mm/backing-dev.c:wb_congested_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275205530,
      "name": "refcount_dec_and_lock_irqsave",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
bool refcount_dec_and_lock_irqsave(refcount_t * r, spinlock_t * lock, long unsigned int * flags)
```

```json
{
  "name": "refcount_dec_and_lock_irqsave",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584237088,
      "name": "refcount_dec_and_lock_irqsave",
      "external": true,
      "loc": "lib/refcount.c:373",
      "file": "lib/refcount.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/user.c:free_uid",
        "mm/backing-dev.c:wb_congested_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584237088,
      "name": "refcount_dec_and_lock_irqsave",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
bool refcount_dec_and_lock_irqsave(refcount_t * r, spinlock_t * lock, long unsigned int * flags)
```

```json
{
  "name": "refcount_dec_and_lock_irqsave",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584172288,
      "name": "refcount_dec_and_lock_irqsave",
      "external": true,
      "loc": "lib/refcount.c:373",
      "file": "lib/refcount.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/user.c:free_uid",
        "mm/backing-dev.c:wb_congested_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584172288,
      "name": "refcount_dec_and_lock_irqsave",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
bool refcount_dec_and_lock_irqsave(refcount_t * r, spinlock_t * lock, long unsigned int * flags)
```

```json
{
  "name": "refcount_dec_and_lock_irqsave",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584220848,
      "name": "refcount_dec_and_lock_irqsave",
      "external": true,
      "loc": "lib/refcount.c:373",
      "file": "lib/refcount.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/user.c:free_uid",
        "mm/backing-dev.c:wb_congested_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584220848,
      "name": "refcount_dec_and_lock_irqsave",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
bool refcount_dec_and_lock_irqsave(refcount_t * r, spinlock_t * lock, long unsigned int * flags)
```

```json
{
  "name": "refcount_dec_and_lock_irqsave",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584325680,
      "name": "refcount_dec_and_lock_irqsave",
      "external": true,
      "loc": "lib/refcount.c:373",
      "file": "lib/refcount.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/user.c:free_uid",
        "mm/backing-dev.c:wb_congested_put"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584325680,
      "name": "refcount_dec_and_lock_irqsave",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
bool refcount_dec_and_lock_irqsave(refcount_t * r, spinlock_t * lock, long unsigned int * flags)
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
