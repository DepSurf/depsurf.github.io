# Function: <code>hwspin_lock_unregister_single</code>

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
struct hwspinlock * hwspin_lock_unregister_single(unsigned int id)
```

```json
{
  "name": "hwspin_lock_unregister_single",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587304784,
      "name": "hwspin_lock_unregister_single",
      "external": false,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:368",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587304784,
      "name": "hwspin_lock_unregister_single",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
struct hwspinlock * hwspin_lock_unregister_single(unsigned int id)
```

```json
{
  "name": "hwspin_lock_unregister_single",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hwspin_lock_unregister_single",
      "external": false,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:395",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587607488,
      "name": "hwspin_lock_unregister_single",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
    },
    {
      "addr": 18446744071587609530,
      "name": "hwspin_lock_unregister_single.cold.7",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
struct hwspinlock * hwspin_lock_unregister_single(unsigned int id)
```

```json
{
  "name": "hwspin_lock_unregister_single",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hwspin_lock_unregister_single",
      "external": false,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:424",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587735712,
      "name": "hwspin_lock_unregister_single",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 101
    },
    {
      "addr": 18446744071587738330,
      "name": "hwspin_lock_unregister_single.cold.11",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
struct hwspinlock * hwspin_lock_unregister_single(unsigned int id)
```

```json
{
  "name": "hwspin_lock_unregister_single",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hwspin_lock_unregister_single",
      "external": false,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:446",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588019952,
      "name": "hwspin_lock_unregister_single",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
    },
    {
      "addr": 18446744071588022542,
      "name": "hwspin_lock_unregister_single.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
struct hwspinlock * hwspin_lock_unregister_single(unsigned int id)
```

```json
{
  "name": "hwspin_lock_unregister_single",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hwspin_lock_unregister_single",
      "external": false,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:446",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588227600,
      "name": "hwspin_lock_unregister_single",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
    },
    {
      "addr": 18446744071588230114,
      "name": "hwspin_lock_unregister_single.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
struct hwspinlock * hwspin_lock_unregister_single(unsigned int id)
```

```json
{
  "name": "hwspin_lock_unregister_single",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hwspin_lock_unregister_single",
      "external": false,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:446",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589102416,
      "name": "hwspin_lock_unregister_single",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
    },
    {
      "addr": 18446744071589104938,
      "name": "hwspin_lock_unregister_single.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
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
struct hwspinlock * hwspin_lock_unregister_single(unsigned int id)
```

```json
{
  "name": "hwspin_lock_unregister_single",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hwspin_lock_unregister_single",
      "external": false,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:446",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589101728,
      "name": "hwspin_lock_unregister_single",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
    },
    {
      "addr": 18446744071591615262,
      "name": "hwspin_lock_unregister_single.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
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
struct hwspinlock * hwspin_lock_unregister_single(unsigned int id)
```

```json
{
  "name": "hwspin_lock_unregister_single",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hwspin_lock_unregister_single",
      "external": false,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:446",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588990960,
      "name": "hwspin_lock_unregister_single",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
    },
    {
      "addr": 18446744071591558349,
      "name": "hwspin_lock_unregister_single.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
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
struct hwspinlock * hwspin_lock_unregister_single(unsigned int id)
```

```json
{
  "name": "hwspin_lock_unregister_single",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hwspin_lock_unregister_single",
      "external": false,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:446",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_unreg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589704960,
      "name": "hwspin_lock_unregister_single",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
    },
    {
      "addr": 18446744071592678959,
      "name": "hwspin_lock_unregister_single.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
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
struct hwspinlock * hwspin_lock_unregister_single(unsigned int id)
```

```json
{
  "name": "hwspin_lock_unregister_single",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hwspin_lock_unregister_single",
      "external": false,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:446",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_unreg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591212624,
      "name": "hwspin_lock_unregister_single",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
    },
    {
      "addr": 18446744071594564345,
      "name": "hwspin_lock_unregister_single.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
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
struct hwspinlock * hwspin_lock_unregister_single(unsigned int id)
```

```json
{
  "name": "hwspin_lock_unregister_single",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592955616,
      "name": "hwspin_lock_unregister_single",
      "external": false,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:446",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_unreg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592955616,
      "name": "hwspin_lock_unregister_single",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
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
struct hwspinlock * hwspin_lock_unregister_single(unsigned int id)
```

```json
{
  "name": "hwspin_lock_unregister_single",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593405984,
      "name": "hwspin_lock_unregister_single",
      "external": false,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:446",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_unreg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593405984,
      "name": "hwspin_lock_unregister_single",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
struct hwspinlock * hwspin_lock_unregister_single(unsigned int id)
```

```json
{
  "name": "hwspin_lock_unregister_single",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594151696,
      "name": "hwspin_lock_unregister_single",
      "external": false,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:450",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:devm_hwspin_lock_unreg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594151696,
      "name": "hwspin_lock_unregister_single",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
struct hwspinlock * hwspin_lock_unregister_single(unsigned int id)
```

```json
{
  "name": "hwspin_lock_unregister_single",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501682848,
      "name": "hwspin_lock_unregister_single",
      "external": false,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:446",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501682848,
      "name": "hwspin_lock_unregister_single",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
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
struct hwspinlock * hwspin_lock_unregister_single(unsigned int id)
```

```json
{
  "name": "hwspin_lock_unregister_single",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234209760,
      "name": "hwspin_lock_unregister_single",
      "external": false,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:446",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234209760,
      "name": "hwspin_lock_unregister_single",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
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
struct hwspinlock * hwspin_lock_unregister_single(unsigned int id)
```

```json
{
  "name": "hwspin_lock_unregister_single",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295115616,
      "name": "hwspin_lock_unregister_single",
      "external": false,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:446",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295115616,
      "name": "hwspin_lock_unregister_single",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 232
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
struct hwspinlock * hwspin_lock_unregister_single(unsigned int id)
```

```json
{
  "name": "hwspin_lock_unregister_single",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278120470,
      "name": "hwspin_lock_unregister_single",
      "external": false,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:446",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278120470,
      "name": "hwspin_lock_unregister_single",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 178
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
struct hwspinlock * hwspin_lock_unregister_single(unsigned int id)
```

```json
{
  "name": "hwspin_lock_unregister_single",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hwspin_lock_unregister_single",
      "external": false,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:446",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587839296,
      "name": "hwspin_lock_unregister_single",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
    },
    {
      "addr": 18446744071587841810,
      "name": "hwspin_lock_unregister_single.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
struct hwspinlock * hwspin_lock_unregister_single(unsigned int id)
```

```json
{
  "name": "hwspin_lock_unregister_single",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hwspin_lock_unregister_single",
      "external": false,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:446",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587546208,
      "name": "hwspin_lock_unregister_single",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
    },
    {
      "addr": 18446744071587548140,
      "name": "hwspin_lock_unregister_single.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
struct hwspinlock * hwspin_lock_unregister_single(unsigned int id)
```

```json
{
  "name": "hwspin_lock_unregister_single",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hwspin_lock_unregister_single",
      "external": false,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:446",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588182080,
      "name": "hwspin_lock_unregister_single",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
    },
    {
      "addr": 18446744071588184594,
      "name": "hwspin_lock_unregister_single.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
struct hwspinlock * hwspin_lock_unregister_single(unsigned int id)
```

```json
{
  "name": "hwspin_lock_unregister_single",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hwspin_lock_unregister_single",
      "external": false,
      "loc": "drivers/hwspinlock/hwspinlock_core.c:446",
      "file": "drivers/hwspinlock/hwspinlock_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588300128,
      "name": "hwspin_lock_unregister_single",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
    },
    {
      "addr": 18446744071588302458,
      "name": "hwspin_lock_unregister_single.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
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
struct hwspinlock * hwspin_lock_unregister_single(unsigned int id)
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
