# Function: <code>__rt_mutex_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __rt_mutex_init(struct rt_mutex * lock, const char * name)
```

```json
{
  "name": "__rt_mutex_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579675648,
      "name": "__rt_mutex_init",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1534",
      "file": "kernel/locking/rtmutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:rt_mutex_init_proxy_locked"
      ],
      "caller_func": [
        "drivers/i2c/i2c-core.c:i2c_register_adapter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579675648,
      "name": "__rt_mutex_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __rt_mutex_init(struct rt_mutex * lock, const char * name)
```

```json
{
  "name": "__rt_mutex_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579697909,
      "name": "__rt_mutex_init",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1543",
      "file": "kernel/locking/rtmutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:rt_mutex_init_proxy_locked"
      ],
      "caller_func": [
        "drivers/i2c/i2c-core.c:i2c_register_adapter",
        "drivers/i2c/i2c-core.c:i2c_register_adapter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579694800,
      "name": "__rt_mutex_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __rt_mutex_init(struct rt_mutex * lock, const char * name)
```

```json
{
  "name": "__rt_mutex_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579725029,
      "name": "__rt_mutex_init",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1607",
      "file": "kernel/locking/rtmutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:rt_mutex_init_proxy_locked"
      ],
      "caller_func": [
        "drivers/i2c/i2c-core.c:i2c_register_adapter",
        "drivers/i2c/i2c-core.c:i2c_register_adapter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579721904,
      "name": "__rt_mutex_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __rt_mutex_init(struct rt_mutex * lock, const char * name, struct lock_class_key * key)
```

```json
{
  "name": "__rt_mutex_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579720885,
      "name": "__rt_mutex_init",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1655",
      "file": "kernel/locking/rtmutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:rt_mutex_init_proxy_locked"
      ],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579717632,
      "name": "__rt_mutex_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __rt_mutex_init(struct rt_mutex * lock, const char * name, struct lock_class_key * key)
```

```json
{
  "name": "__rt_mutex_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579753589,
      "name": "__rt_mutex_init",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1655",
      "file": "kernel/locking/rtmutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:rt_mutex_init_proxy_locked"
      ],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579750240,
      "name": "__rt_mutex_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __rt_mutex_init(struct rt_mutex * lock, const char * name, struct lock_class_key * key)
```

```json
{
  "name": "__rt_mutex_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579787973,
      "name": "__rt_mutex_init",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1676",
      "file": "kernel/locking/rtmutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:rt_mutex_init_proxy_locked"
      ],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579784688,
      "name": "__rt_mutex_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void __rt_mutex_init(struct rt_mutex * lock, const char * name, struct lock_class_key * key)
```

```json
{
  "name": "__rt_mutex_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579834437,
      "name": "__rt_mutex_init",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1676",
      "file": "kernel/locking/rtmutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:rt_mutex_init_proxy_locked"
      ],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579831168,
      "name": "__rt_mutex_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void __rt_mutex_init(struct rt_mutex * lock, const char * name, struct lock_class_key * key)
```

```json
{
  "name": "__rt_mutex_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579869493,
      "name": "__rt_mutex_init",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1677",
      "file": "kernel/locking/rtmutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:rt_mutex_init_proxy_locked"
      ],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579865696,
      "name": "__rt_mutex_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void __rt_mutex_init(struct rt_mutex * lock, const char * name, struct lock_class_key * key)
```

```json
{
  "name": "__rt_mutex_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579918117,
      "name": "__rt_mutex_init",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1675",
      "file": "kernel/locking/rtmutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:rt_mutex_init_proxy_locked"
      ],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579914320,
      "name": "__rt_mutex_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void __rt_mutex_init(struct rt_mutex * lock, const char * name, struct lock_class_key * key)
```

```json
{
  "name": "__rt_mutex_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579963029,
      "name": "__rt_mutex_init",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1673",
      "file": "kernel/locking/rtmutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:rt_mutex_init_proxy_locked"
      ],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579958848,
      "name": "__rt_mutex_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void __rt_mutex_init(struct rt_mutex * lock, const char * name, struct lock_class_key * key)
```

```json
{
  "name": "__rt_mutex_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579951173,
      "name": "__rt_mutex_init",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1673",
      "file": "kernel/locking/rtmutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:rt_mutex_init_proxy_locked"
      ],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579946992,
      "name": "__rt_mutex_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void __rt_mutex_init(struct rt_mutex * lock, const char * name, struct lock_class_key * key)
```

```json
{
  "name": "__rt_mutex_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591648336,
      "name": "__rt_mutex_init",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1555",
      "file": "kernel/locking/rtmutex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591648336,
      "name": "__rt_mutex_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void __rt_mutex_init(struct rt_mutex * lock, const char * name, struct lock_class_key * key)
```

```json
{
  "name": "__rt_mutex_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592821840,
      "name": "__rt_mutex_init",
      "external": true,
      "loc": "kernel/locking/rtmutex_api.c:191",
      "file": "kernel/locking/rtmutex_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592821840,
      "name": "__rt_mutex_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void __rt_mutex_init(struct rt_mutex * lock, const char * name, struct lock_class_key * key)
```

```json
{
  "name": "__rt_mutex_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594729328,
      "name": "__rt_mutex_init",
      "external": true,
      "loc": "kernel/locking/rtmutex_api.c:213",
      "file": "kernel/locking/rtmutex_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594729328,
      "name": "__rt_mutex_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void __rt_mutex_init(struct rt_mutex * lock, const char * name, struct lock_class_key * key)
```

```json
{
  "name": "__rt_mutex_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596481040,
      "name": "__rt_mutex_init",
      "external": true,
      "loc": "kernel/locking/rtmutex_api.c:213",
      "file": "kernel/locking/rtmutex_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596481040,
      "name": "__rt_mutex_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void __rt_mutex_init(struct rt_mutex * lock, const char * name, struct lock_class_key * key)
```

```json
{
  "name": "__rt_mutex_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597022592,
      "name": "__rt_mutex_init",
      "external": true,
      "loc": "kernel/locking/rtmutex_api.c:213",
      "file": "kernel/locking/rtmutex_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597022592,
      "name": "__rt_mutex_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void __rt_mutex_init(struct rt_mutex * lock, const char * name, struct lock_class_key * key)
```

```json
{
  "name": "__rt_mutex_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597951936,
      "name": "__rt_mutex_init",
      "external": true,
      "loc": "kernel/locking/rtmutex_api.c:213",
      "file": "kernel/locking/rtmutex_api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597951936,
      "name": "__rt_mutex_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
void __rt_mutex_init(struct rt_mutex * lock, const char * name, struct lock_class_key * key)
```

```json
{
  "name": "__rt_mutex_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491123004,
      "name": "__rt_mutex_init",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1675",
      "file": "kernel/locking/rtmutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:rt_mutex_init_proxy_locked"
      ],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491117736,
      "name": "__rt_mutex_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void __rt_mutex_init(struct rt_mutex * lock, const char * name, struct lock_class_key * key)
```

```json
{
  "name": "__rt_mutex_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225123384,
      "name": "__rt_mutex_init",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1675",
      "file": "kernel/locking/rtmutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:rt_mutex_init_proxy_locked"
      ],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225118888,
      "name": "__rt_mutex_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void __rt_mutex_init(struct rt_mutex * lock, const char * name, struct lock_class_key * key)
```

```json
{
  "name": "__rt_mutex_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284014216,
      "name": "__rt_mutex_init",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1675",
      "file": "kernel/locking/rtmutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:rt_mutex_init_proxy_locked"
      ],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284008256,
      "name": "__rt_mutex_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
void __rt_mutex_init(struct rt_mutex * lock, const char * name, struct lock_class_key * key)
```

```json
{
  "name": "__rt_mutex_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271696694,
      "name": "__rt_mutex_init",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1675",
      "file": "kernel/locking/rtmutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:rt_mutex_init_proxy_locked"
      ],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271692630,
      "name": "__rt_mutex_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void __rt_mutex_init(struct rt_mutex * lock, const char * name, struct lock_class_key * key)
```

```json
{
  "name": "__rt_mutex_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579890229,
      "name": "__rt_mutex_init",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1675",
      "file": "kernel/locking/rtmutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:rt_mutex_init_proxy_locked"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579886432,
      "name": "__rt_mutex_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void __rt_mutex_init(struct rt_mutex * lock, const char * name, struct lock_class_key * key)
```

```json
{
  "name": "__rt_mutex_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579825189,
      "name": "__rt_mutex_init",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1675",
      "file": "kernel/locking/rtmutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:rt_mutex_init_proxy_locked"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579821408,
      "name": "__rt_mutex_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void __rt_mutex_init(struct rt_mutex * lock, const char * name, struct lock_class_key * key)
```

```json
{
  "name": "__rt_mutex_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579878389,
      "name": "__rt_mutex_init",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1675",
      "file": "kernel/locking/rtmutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:rt_mutex_init_proxy_locked"
      ],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579874592,
      "name": "__rt_mutex_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void __rt_mutex_init(struct rt_mutex * lock, const char * name, struct lock_class_key * key)
```

```json
{
  "name": "__rt_mutex_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579924005,
      "name": "__rt_mutex_init",
      "external": true,
      "loc": "kernel/locking/rtmutex.c:1675",
      "file": "kernel/locking/rtmutex.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/locking/rtmutex.c:rt_mutex_init_proxy_locked"
      ],
      "caller_func": [
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter",
        "drivers/i2c/i2c-core-base.c:i2c_register_adapter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579920112,
      "name": "__rt_mutex_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct lock_class_key * key</code>
</li>
</ul>
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
