# Function: <code>__hwspin_lock_timeout</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int __hwspin_lock_timeout(struct hwspinlock * hwlock, unsigned int to, int mode, long unsigned int * flags)
```

```json
{
  "name": "__hwspin_lock_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587306688,
      "name": "__hwspin_lock_timeout",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:178",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587306688,
      "name": "__hwspin_lock_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
int __hwspin_lock_timeout(struct hwspinlock * hwlock, unsigned int to, int mode, long unsigned int * flags)
```

```json
{
  "name": "__hwspin_lock_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587609264,
      "name": "__hwspin_lock_timeout",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:197",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:regmap_lock_hwlock_irqsave",
        "drivers/base/regmap/regmap.c:regmap_lock_hwlock_irq",
        "drivers/base/regmap/regmap.c:regmap_lock_hwlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587609264,
      "name": "__hwspin_lock_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
int __hwspin_lock_timeout(struct hwspinlock * hwlock, unsigned int to, int mode, long unsigned int * flags)
```

```json
{
  "name": "__hwspin_lock_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587738064,
      "name": "__hwspin_lock_timeout",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:197",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:regmap_lock_hwlock_irqsave",
        "drivers/base/regmap/regmap.c:regmap_lock_hwlock_irq",
        "drivers/base/regmap/regmap.c:regmap_lock_hwlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587738064,
      "name": "__hwspin_lock_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
int __hwspin_lock_timeout(struct hwspinlock * hwlock, unsigned int to, int mode, long unsigned int * flags)
```

```json
{
  "name": "__hwspin_lock_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588022160,
      "name": "__hwspin_lock_timeout",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:206",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:regmap_lock_hwlock_irqsave",
        "drivers/base/regmap/regmap.c:regmap_lock_hwlock_irq",
        "drivers/base/regmap/regmap.c:regmap_lock_hwlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588022160,
      "name": "__hwspin_lock_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
int __hwspin_lock_timeout(struct hwspinlock * hwlock, unsigned int to, int mode, long unsigned int * flags)
```

```json
{
  "name": "__hwspin_lock_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588229776,
      "name": "__hwspin_lock_timeout",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:206",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:regmap_lock_hwlock_irqsave",
        "drivers/base/regmap/regmap.c:regmap_lock_hwlock_irq",
        "drivers/base/regmap/regmap.c:regmap_lock_hwlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588229776,
      "name": "__hwspin_lock_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
int __hwspin_lock_timeout(struct hwspinlock * hwlock, unsigned int to, int mode, long unsigned int * flags)
```

```json
{
  "name": "__hwspin_lock_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589104768,
      "name": "__hwspin_lock_timeout",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:206",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:regmap_lock_hwlock_irqsave",
        "drivers/base/regmap/regmap.c:regmap_lock_hwlock_irq",
        "drivers/base/regmap/regmap.c:regmap_lock_hwlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589104768,
      "name": "__hwspin_lock_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
int __hwspin_lock_timeout(struct hwspinlock * hwlock, unsigned int to, int mode, long unsigned int * flags)
```

```json
{
  "name": "__hwspin_lock_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589104080,
      "name": "__hwspin_lock_timeout",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:206",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:regmap_lock_hwlock_irqsave",
        "drivers/base/regmap/regmap.c:regmap_lock_hwlock_irq",
        "drivers/base/regmap/regmap.c:regmap_lock_hwlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589104080,
      "name": "__hwspin_lock_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
int __hwspin_lock_timeout(struct hwspinlock * hwlock, unsigned int to, int mode, long unsigned int * flags)
```

```json
{
  "name": "__hwspin_lock_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588993312,
      "name": "__hwspin_lock_timeout",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:206",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:regmap_lock_hwlock_irqsave",
        "drivers/base/regmap/regmap.c:regmap_lock_hwlock_irq",
        "drivers/base/regmap/regmap.c:regmap_lock_hwlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588993312,
      "name": "__hwspin_lock_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
int __hwspin_lock_timeout(struct hwspinlock * hwlock, unsigned int to, int mode, long unsigned int * flags)
```

```json
{
  "name": "__hwspin_lock_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589707392,
      "name": "__hwspin_lock_timeout",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:206",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:regmap_lock_hwlock_irqsave",
        "drivers/base/regmap/regmap.c:regmap_lock_hwlock_irq",
        "drivers/base/regmap/regmap.c:regmap_lock_hwlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589707392,
      "name": "__hwspin_lock_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
int __hwspin_lock_timeout(struct hwspinlock * hwlock, unsigned int to, int mode, long unsigned int * flags)
```

```json
{
  "name": "__hwspin_lock_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591212432,
      "name": "__hwspin_lock_timeout",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:206",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:regmap_lock_hwlock_irqsave",
        "drivers/base/regmap/regmap.c:regmap_lock_hwlock_irq",
        "drivers/base/regmap/regmap.c:regmap_lock_hwlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591212432,
      "name": "__hwspin_lock_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
int __hwspin_lock_timeout(struct hwspinlock * hwlock, unsigned int to, int mode, long unsigned int * flags)
```

```json
{
  "name": "__hwspin_lock_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592955408,
      "name": "__hwspin_lock_timeout",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:206",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:regmap_lock_hwlock_irqsave",
        "drivers/base/regmap/regmap.c:regmap_lock_hwlock_irq",
        "drivers/base/regmap/regmap.c:regmap_lock_hwlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592955408,
      "name": "__hwspin_lock_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
int __hwspin_lock_timeout(struct hwspinlock * hwlock, unsigned int to, int mode, long unsigned int * flags)
```

```json
{
  "name": "__hwspin_lock_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593405776,
      "name": "__hwspin_lock_timeout",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:206",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:regmap_lock_hwlock_irqsave",
        "drivers/base/regmap/regmap.c:regmap_lock_hwlock_irq",
        "drivers/base/regmap/regmap.c:regmap_lock_hwlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593405776,
      "name": "__hwspin_lock_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
int __hwspin_lock_timeout(struct hwspinlock * hwlock, unsigned int to, int mode, long unsigned int * flags)
```

```json
{
  "name": "__hwspin_lock_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594151488,
      "name": "__hwspin_lock_timeout",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:209",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:regmap_lock_hwlock_irqsave",
        "drivers/base/regmap/regmap.c:regmap_lock_hwlock_irq",
        "drivers/base/regmap/regmap.c:regmap_lock_hwlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594151488,
      "name": "__hwspin_lock_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
int __hwspin_lock_timeout(struct hwspinlock * hwlock, unsigned int to, int mode, long unsigned int * flags)
```

```json
{
  "name": "__hwspin_lock_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501686344,
      "name": "__hwspin_lock_timeout",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:206",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:regmap_lock_hwlock_irqsave",
        "drivers/base/regmap/regmap.c:regmap_lock_hwlock_irq",
        "drivers/base/regmap/regmap.c:regmap_lock_hwlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501686344,
      "name": "__hwspin_lock_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
int __hwspin_lock_timeout(struct hwspinlock * hwlock, unsigned int to, int mode, long unsigned int * flags)
```

```json
{
  "name": "__hwspin_lock_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234208848,
      "name": "__hwspin_lock_timeout",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:206",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:regmap_lock_hwlock_irqsave",
        "drivers/base/regmap/regmap.c:regmap_lock_hwlock_irq",
        "drivers/base/regmap/regmap.c:regmap_lock_hwlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234208848,
      "name": "__hwspin_lock_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
int __hwspin_lock_timeout(struct hwspinlock * hwlock, unsigned int to, int mode, long unsigned int * flags)
```

```json
{
  "name": "__hwspin_lock_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295115248,
      "name": "__hwspin_lock_timeout",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:206",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:regmap_lock_hwlock_irqsave",
        "drivers/base/regmap/regmap.c:regmap_lock_hwlock_irq",
        "drivers/base/regmap/regmap.c:regmap_lock_hwlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295115248,
      "name": "__hwspin_lock_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 368
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
int __hwspin_lock_timeout(struct hwspinlock * hwlock, unsigned int to, int mode, long unsigned int * flags)
```

```json
{
  "name": "__hwspin_lock_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278123466,
      "name": "__hwspin_lock_timeout",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:206",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:regmap_lock_hwlock_irqsave",
        "drivers/base/regmap/regmap.c:regmap_lock_hwlock_irq",
        "drivers/base/regmap/regmap.c:regmap_lock_hwlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278123466,
      "name": "__hwspin_lock_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
int __hwspin_lock_timeout(struct hwspinlock * hwlock, unsigned int to, int mode, long unsigned int * flags)
```

```json
{
  "name": "__hwspin_lock_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587841472,
      "name": "__hwspin_lock_timeout",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:206",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:regmap_lock_hwlock_irqsave",
        "drivers/base/regmap/regmap.c:regmap_lock_hwlock_irq",
        "drivers/base/regmap/regmap.c:regmap_lock_hwlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587841472,
      "name": "__hwspin_lock_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
int __hwspin_lock_timeout(struct hwspinlock * hwlock, unsigned int to, int mode, long unsigned int * flags)
```

```json
{
  "name": "__hwspin_lock_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587546032,
      "name": "__hwspin_lock_timeout",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:206",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:regmap_lock_hwlock_irqsave",
        "drivers/base/regmap/regmap.c:regmap_lock_hwlock_irq",
        "drivers/base/regmap/regmap.c:regmap_lock_hwlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587546032,
      "name": "__hwspin_lock_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
int __hwspin_lock_timeout(struct hwspinlock * hwlock, unsigned int to, int mode, long unsigned int * flags)
```

```json
{
  "name": "__hwspin_lock_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588184256,
      "name": "__hwspin_lock_timeout",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:206",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:regmap_lock_hwlock_irqsave",
        "drivers/base/regmap/regmap.c:regmap_lock_hwlock_irq",
        "drivers/base/regmap/regmap.c:regmap_lock_hwlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588184256,
      "name": "__hwspin_lock_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
int __hwspin_lock_timeout(struct hwspinlock * hwlock, unsigned int to, int mode, long unsigned int * flags)
```

```json
{
  "name": "__hwspin_lock_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588302288,
      "name": "__hwspin_lock_timeout",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:206",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:regmap_lock_hwlock_irqsave",
        "drivers/base/regmap/regmap.c:regmap_lock_hwlock_irq",
        "drivers/base/regmap/regmap.c:regmap_lock_hwlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588302288,
      "name": "__hwspin_lock_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
int __hwspin_lock_timeout(struct hwspinlock * hwlock, unsigned int to, int mode, long unsigned int * flags)
```
</details>
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
