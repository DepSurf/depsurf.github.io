# Function: <code>__hwspin_unlock</code>

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
void __hwspin_unlock(struct hwspinlock * hwlock, int mode, long unsigned int * flags)
```

```json
{
  "name": "__hwspin_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587306816,
      "name": "__hwspin_unlock",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:230",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587306816,
      "name": "__hwspin_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
void __hwspin_unlock(struct hwspinlock * hwlock, int mode, long unsigned int * flags)
```

```json
{
  "name": "__hwspin_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587609392,
      "name": "__hwspin_unlock",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:249",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:regmap_unlock_hwlock_irqrestore",
        "drivers/base/regmap/regmap.c:regmap_unlock_hwlock_irq",
        "drivers/base/regmap/regmap.c:regmap_unlock_hwlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587609392,
      "name": "__hwspin_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
void __hwspin_unlock(struct hwspinlock * hwlock, int mode, long unsigned int * flags)
```

```json
{
  "name": "__hwspin_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587738192,
      "name": "__hwspin_unlock",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:249",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:regmap_unlock_hwlock_irqrestore",
        "drivers/base/regmap/regmap.c:regmap_unlock_hwlock_irq",
        "drivers/base/regmap/regmap.c:regmap_unlock_hwlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587738192,
      "name": "__hwspin_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
void __hwspin_unlock(struct hwspinlock * hwlock, int mode, long unsigned int * flags)
```

```json
{
  "name": "__hwspin_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588022336,
      "name": "__hwspin_unlock",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:265",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:regmap_unlock_hwlock_irqrestore",
        "drivers/base/regmap/regmap.c:regmap_unlock_hwlock_irq",
        "drivers/base/regmap/regmap.c:regmap_unlock_hwlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588022336,
      "name": "__hwspin_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
void __hwspin_unlock(struct hwspinlock * hwlock, int mode, long unsigned int * flags)
```

```json
{
  "name": "__hwspin_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588229952,
      "name": "__hwspin_unlock",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:265",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:regmap_unlock_hwlock_irqrestore",
        "drivers/base/regmap/regmap.c:regmap_unlock_hwlock_irq",
        "drivers/base/regmap/regmap.c:regmap_unlock_hwlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588229952,
      "name": "__hwspin_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
void __hwspin_unlock(struct hwspinlock * hwlock, int mode, long unsigned int * flags)
```

```json
{
  "name": "__hwspin_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589104192,
      "name": "__hwspin_unlock",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:265",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:regmap_unlock_hwlock_irqrestore",
        "drivers/base/regmap/regmap.c:regmap_unlock_hwlock_irq",
        "drivers/base/regmap/regmap.c:regmap_unlock_hwlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589104192,
      "name": "__hwspin_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
void __hwspin_unlock(struct hwspinlock * hwlock, int mode, long unsigned int * flags)
```

```json
{
  "name": "__hwspin_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589103504,
      "name": "__hwspin_unlock",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:265",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:regmap_unlock_hwlock_irqrestore",
        "drivers/base/regmap/regmap.c:regmap_unlock_hwlock_irq",
        "drivers/base/regmap/regmap.c:regmap_unlock_hwlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589103504,
      "name": "__hwspin_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
void __hwspin_unlock(struct hwspinlock * hwlock, int mode, long unsigned int * flags)
```

```json
{
  "name": "__hwspin_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588992736,
      "name": "__hwspin_unlock",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:265",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:regmap_unlock_hwlock_irqrestore",
        "drivers/base/regmap/regmap.c:regmap_unlock_hwlock_irq",
        "drivers/base/regmap/regmap.c:regmap_unlock_hwlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588992736,
      "name": "__hwspin_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
void __hwspin_unlock(struct hwspinlock * hwlock, int mode, long unsigned int * flags)
```

```json
{
  "name": "__hwspin_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589706816,
      "name": "__hwspin_unlock",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:265",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:regmap_unlock_hwlock_irqrestore",
        "drivers/base/regmap/regmap.c:regmap_unlock_hwlock_irq",
        "drivers/base/regmap/regmap.c:regmap_unlock_hwlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589706816,
      "name": "__hwspin_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 163
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
void __hwspin_unlock(struct hwspinlock * hwlock, int mode, long unsigned int * flags)
```

```json
{
  "name": "__hwspin_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591212112,
      "name": "__hwspin_unlock",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:265",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:regmap_unlock_hwlock_irqrestore",
        "drivers/base/regmap/regmap.c:regmap_unlock_hwlock_irq",
        "drivers/base/regmap/regmap.c:regmap_unlock_hwlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591212112,
      "name": "__hwspin_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
void __hwspin_unlock(struct hwspinlock * hwlock, int mode, long unsigned int * flags)
```

```json
{
  "name": "__hwspin_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592955040,
      "name": "__hwspin_unlock",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:265",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:regmap_unlock_hwlock_irqrestore",
        "drivers/base/regmap/regmap.c:regmap_unlock_hwlock_irq",
        "drivers/base/regmap/regmap.c:regmap_unlock_hwlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592955040,
      "name": "__hwspin_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
void __hwspin_unlock(struct hwspinlock * hwlock, int mode, long unsigned int * flags)
```

```json
{
  "name": "__hwspin_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593405392,
      "name": "__hwspin_unlock",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:265",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:regmap_unlock_hwlock_irqrestore",
        "drivers/base/regmap/regmap.c:regmap_unlock_hwlock_irq",
        "drivers/base/regmap/regmap.c:regmap_unlock_hwlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593405392,
      "name": "__hwspin_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
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
void __hwspin_unlock(struct hwspinlock * hwlock, int mode, long unsigned int * flags)
```

```json
{
  "name": "__hwspin_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594151104,
      "name": "__hwspin_unlock",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:268",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:regmap_unlock_hwlock_irqrestore",
        "drivers/base/regmap/regmap.c:regmap_unlock_hwlock_irq",
        "drivers/base/regmap/regmap.c:regmap_unlock_hwlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594151104,
      "name": "__hwspin_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 193
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
void __hwspin_unlock(struct hwspinlock * hwlock, int mode, long unsigned int * flags)
```

```json
{
  "name": "__hwspin_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501685512,
      "name": "__hwspin_unlock",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:265",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:regmap_unlock_hwlock_irqrestore",
        "drivers/base/regmap/regmap.c:regmap_unlock_hwlock_irq",
        "drivers/base/regmap/regmap.c:regmap_unlock_hwlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501685512,
      "name": "__hwspin_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
void __hwspin_unlock(struct hwspinlock * hwlock, int mode, long unsigned int * flags)
```

```json
{
  "name": "__hwspin_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234208656,
      "name": "__hwspin_unlock",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:265",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:regmap_unlock_hwlock_irqrestore",
        "drivers/base/regmap/regmap.c:regmap_unlock_hwlock_irq",
        "drivers/base/regmap/regmap.c:regmap_unlock_hwlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234208656,
      "name": "__hwspin_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
void __hwspin_unlock(struct hwspinlock * hwlock, int mode, long unsigned int * flags)
```

```json
{
  "name": "__hwspin_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295119760,
      "name": "__hwspin_unlock",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:265",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:regmap_unlock_hwlock_irqrestore",
        "drivers/base/regmap/regmap.c:regmap_unlock_hwlock_irq",
        "drivers/base/regmap/regmap.c:regmap_unlock_hwlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295119760,
      "name": "__hwspin_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 432
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
void __hwspin_unlock(struct hwspinlock * hwlock, int mode, long unsigned int * flags)
```

```json
{
  "name": "__hwspin_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278122770,
      "name": "__hwspin_unlock",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:265",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:regmap_unlock_hwlock_irqrestore",
        "drivers/base/regmap/regmap.c:regmap_unlock_hwlock_irq",
        "drivers/base/regmap/regmap.c:regmap_unlock_hwlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278122770,
      "name": "__hwspin_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 292
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
void __hwspin_unlock(struct hwspinlock * hwlock, int mode, long unsigned int * flags)
```

```json
{
  "name": "__hwspin_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587841648,
      "name": "__hwspin_unlock",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:265",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:regmap_unlock_hwlock_irqrestore",
        "drivers/base/regmap/regmap.c:regmap_unlock_hwlock_irq",
        "drivers/base/regmap/regmap.c:regmap_unlock_hwlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587841648,
      "name": "__hwspin_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
void __hwspin_unlock(struct hwspinlock * hwlock, int mode, long unsigned int * flags)
```

```json
{
  "name": "__hwspin_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587547984,
      "name": "__hwspin_unlock",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:265",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:regmap_unlock_hwlock_irqrestore",
        "drivers/base/regmap/regmap.c:regmap_unlock_hwlock_irq",
        "drivers/base/regmap/regmap.c:regmap_unlock_hwlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587547984,
      "name": "__hwspin_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
void __hwspin_unlock(struct hwspinlock * hwlock, int mode, long unsigned int * flags)
```

```json
{
  "name": "__hwspin_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588184432,
      "name": "__hwspin_unlock",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:265",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:regmap_unlock_hwlock_irqrestore",
        "drivers/base/regmap/regmap.c:regmap_unlock_hwlock_irq",
        "drivers/base/regmap/regmap.c:regmap_unlock_hwlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588184432,
      "name": "__hwspin_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
void __hwspin_unlock(struct hwspinlock * hwlock, int mode, long unsigned int * flags)
```

```json
{
  "name": "__hwspin_unlock",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588299968,
      "name": "__hwspin_unlock",
      "external": true,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:265",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/regmap/regmap.c:regmap_unlock_hwlock_irqrestore",
        "drivers/base/regmap/regmap.c:regmap_unlock_hwlock_irq",
        "drivers/base/regmap/regmap.c:regmap_unlock_hwlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588299968,
      "name": "__hwspin_unlock",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
void __hwspin_unlock(struct hwspinlock * hwlock, int mode, long unsigned int * flags)
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
