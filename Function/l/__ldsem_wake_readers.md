# Function: <code>__ldsem_wake_readers</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__ldsem_wake_readers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584005180,
      "name": "__ldsem_wake_readers",
      "external": false,
      "loc": "drivers/tty/tty_ldsem.c:119",
      "file": "drivers/tty/tty_ldsem.c",
      "inline": "not declared, inlined",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void __ldsem_wake_readers(struct ld_semaphore * sem)
```

```json
{
  "name": "__ldsem_wake_readers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584336944,
      "name": "__ldsem_wake_readers",
      "external": false,
      "loc": "drivers/tty/tty_ldsem.c:119",
      "file": "drivers/tty/tty_ldsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_ldsem.c:ldsem_down_read",
        "drivers/tty/tty_ldsem.c:ldsem_wake"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584336944,
      "name": "__ldsem_wake_readers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 195
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void __ldsem_wake_readers(struct ld_semaphore * sem)
```

```json
{
  "name": "__ldsem_wake_readers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584518784,
      "name": "__ldsem_wake_readers",
      "external": false,
      "loc": "drivers/tty/tty_ldsem.c:119",
      "file": "drivers/tty/tty_ldsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_ldsem.c:ldsem_down_read",
        "drivers/tty/tty_ldsem.c:ldsem_wake"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584518784,
      "name": "__ldsem_wake_readers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 195
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__ldsem_wake_readers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584598037,
      "name": "__ldsem_wake_readers",
      "external": false,
      "loc": "drivers/tty/tty_ldsem.c:121",
      "file": "drivers/tty/tty_ldsem.c",
      "inline": "not declared, inlined",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__ldsem_wake_readers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585010453,
      "name": "__ldsem_wake_readers",
      "external": false,
      "loc": "drivers/tty/tty_ldsem.c:119",
      "file": "drivers/tty/tty_ldsem.c",
      "inline": "not declared, inlined",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__ldsem_wake_readers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585244595,
      "name": "__ldsem_wake_readers",
      "external": false,
      "loc": "drivers/tty/tty_ldsem.c:119",
      "file": "drivers/tty/tty_ldsem.c",
      "inline": "not declared, inlined",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __ldsem_wake_readers(struct ld_semaphore * sem)
```

```json
{
  "name": "__ldsem_wake_readers",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585363952,
      "name": "__ldsem_wake_readers",
      "external": false,
      "loc": "drivers/tty/tty_ldsem.c:74",
      "file": "drivers/tty/tty_ldsem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_ldsem.c:ldsem_down_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585363952,
      "name": "__ldsem_wake_readers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 177
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
void __ldsem_wake_readers(struct ld_semaphore * sem)
```

```json
{
  "name": "__ldsem_wake_readers",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585577680,
      "name": "__ldsem_wake_readers",
      "external": false,
      "loc": "drivers/tty/tty_ldsem.c:74",
      "file": "drivers/tty/tty_ldsem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_ldsem.c:ldsem_down_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585577680,
      "name": "__ldsem_wake_readers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
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
void __ldsem_wake_readers(struct ld_semaphore * sem)
```

```json
{
  "name": "__ldsem_wake_readers",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585718592,
      "name": "__ldsem_wake_readers",
      "external": false,
      "loc": "drivers/tty/tty_ldsem.c:74",
      "file": "drivers/tty/tty_ldsem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_ldsem.c:ldsem_down_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585718592,
      "name": "__ldsem_wake_readers",
      "section": ".text",
      "bind": "STB_LOCAL",
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
void __ldsem_wake_readers(struct ld_semaphore * sem)
```

```json
{
  "name": "__ldsem_wake_readers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586448368,
      "name": "__ldsem_wake_readers",
      "external": false,
      "loc": "drivers/tty/tty_ldsem.c:74",
      "file": "drivers/tty/tty_ldsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_ldsem.c:down_write_failed",
        "drivers/tty/tty_ldsem.c:down_read_failed",
        "drivers/tty/tty_ldsem.c:ldsem_wake"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586448368,
      "name": "__ldsem_wake_readers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 199
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
void __ldsem_wake_readers(struct ld_semaphore * sem)
```

```json
{
  "name": "__ldsem_wake_readers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586562848,
      "name": "__ldsem_wake_readers",
      "external": false,
      "loc": "drivers/tty/tty_ldsem.c:74",
      "file": "drivers/tty/tty_ldsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_ldsem.c:down_write_failed",
        "drivers/tty/tty_ldsem.c:down_read_failed",
        "drivers/tty/tty_ldsem.c:ldsem_wake"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586562848,
      "name": "__ldsem_wake_readers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 199
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
void __ldsem_wake_readers(struct ld_semaphore * sem)
```

```json
{
  "name": "__ldsem_wake_readers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586447808,
      "name": "__ldsem_wake_readers",
      "external": false,
      "loc": "drivers/tty/tty_ldsem.c:74",
      "file": "drivers/tty/tty_ldsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_ldsem.c:down_write_failed",
        "drivers/tty/tty_ldsem.c:down_read_failed",
        "drivers/tty/tty_ldsem.c:ldsem_wake"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586447808,
      "name": "__ldsem_wake_readers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 199
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
void __ldsem_wake_readers(struct ld_semaphore * sem)
```

```json
{
  "name": "__ldsem_wake_readers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586974112,
      "name": "__ldsem_wake_readers",
      "external": false,
      "loc": "drivers/tty/tty_ldsem.c:74",
      "file": "drivers/tty/tty_ldsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_ldsem.c:down_write_failed",
        "drivers/tty/tty_ldsem.c:down_read_failed",
        "drivers/tty/tty_ldsem.c:ldsem_wake"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586974112,
      "name": "__ldsem_wake_readers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 199
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
void __ldsem_wake_readers(struct ld_semaphore * sem)
```

```json
{
  "name": "__ldsem_wake_readers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588270656,
      "name": "__ldsem_wake_readers",
      "external": false,
      "loc": "drivers/tty/tty_ldsem.c:74",
      "file": "drivers/tty/tty_ldsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_ldsem.c:down_write_failed",
        "drivers/tty/tty_ldsem.c:down_read_failed",
        "drivers/tty/tty_ldsem.c:ldsem_wake"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588270656,
      "name": "__ldsem_wake_readers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 213
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
void __ldsem_wake_readers(struct ld_semaphore * sem)
```

```json
{
  "name": "__ldsem_wake_readers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589685472,
      "name": "__ldsem_wake_readers",
      "external": false,
      "loc": "drivers/tty/tty_ldsem.c:74",
      "file": "drivers/tty/tty_ldsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_ldsem.c:down_write_failed",
        "drivers/tty/tty_ldsem.c:down_read_failed",
        "drivers/tty/tty_ldsem.c:ldsem_wake"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589685472,
      "name": "__ldsem_wake_readers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 213
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
void __ldsem_wake_readers(struct ld_semaphore * sem)
```

```json
{
  "name": "__ldsem_wake_readers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589990080,
      "name": "__ldsem_wake_readers",
      "external": false,
      "loc": "drivers/tty/tty_ldsem.c:74",
      "file": "drivers/tty/tty_ldsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_ldsem.c:down_write_failed",
        "drivers/tty/tty_ldsem.c:down_read_failed",
        "drivers/tty/tty_ldsem.c:ldsem_wake"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589990080,
      "name": "__ldsem_wake_readers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 213
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
void __ldsem_wake_readers(struct ld_semaphore * sem)
```

```json
{
  "name": "__ldsem_wake_readers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590328608,
      "name": "__ldsem_wake_readers",
      "external": false,
      "loc": "drivers/tty/tty_ldsem.c:74",
      "file": "drivers/tty/tty_ldsem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_ldsem.c:down_write_failed",
        "drivers/tty/tty_ldsem.c:down_read_failed",
        "drivers/tty/tty_ldsem.c:ldsem_wake"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590328608,
      "name": "__ldsem_wake_readers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 213
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
void __ldsem_wake_readers(struct ld_semaphore * sem)
```

```json
{
  "name": "__ldsem_wake_readers",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336498410392,
      "name": "__ldsem_wake_readers",
      "external": false,
      "loc": "drivers/tty/tty_ldsem.c:74",
      "file": "drivers/tty/tty_ldsem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_ldsem.c:ldsem_down_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498410392,
      "name": "__ldsem_wake_readers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
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
void __ldsem_wake_readers(struct ld_semaphore * sem)
```

```json
{
  "name": "__ldsem_wake_readers",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3231082568,
      "name": "__ldsem_wake_readers",
      "external": false,
      "loc": "drivers/tty/tty_ldsem.c:74",
      "file": "drivers/tty/tty_ldsem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_ldsem.c:ldsem_down_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231082568,
      "name": "__ldsem_wake_readers",
      "section": ".text",
      "bind": "STB_LOCAL",
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
void __ldsem_wake_readers(struct ld_semaphore * sem)
```

```json
{
  "name": "__ldsem_wake_readers",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055291595008,
      "name": "__ldsem_wake_readers",
      "external": false,
      "loc": "drivers/tty/tty_ldsem.c:74",
      "file": "drivers/tty/tty_ldsem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_ldsem.c:ldsem_down_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291595008,
      "name": "__ldsem_wake_readers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 364
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
void __ldsem_wake_readers(struct ld_semaphore * sem)
```

```json
{
  "name": "__ldsem_wake_readers",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276068470,
      "name": "__ldsem_wake_readers",
      "external": false,
      "loc": "drivers/tty/tty_ldsem.c:74",
      "file": "drivers/tty/tty_ldsem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_ldsem.c:ldsem_down_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276068470,
      "name": "__ldsem_wake_readers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
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
void __ldsem_wake_readers(struct ld_semaphore * sem)
```

```json
{
  "name": "__ldsem_wake_readers",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585479616,
      "name": "__ldsem_wake_readers",
      "external": false,
      "loc": "drivers/tty/tty_ldsem.c:74",
      "file": "drivers/tty/tty_ldsem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_ldsem.c:ldsem_down_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585479616,
      "name": "__ldsem_wake_readers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
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
void __ldsem_wake_readers(struct ld_semaphore * sem)
```

```json
{
  "name": "__ldsem_wake_readers",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585349536,
      "name": "__ldsem_wake_readers",
      "external": false,
      "loc": "drivers/tty/tty_ldsem.c:74",
      "file": "drivers/tty/tty_ldsem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_ldsem.c:ldsem_down_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585349536,
      "name": "__ldsem_wake_readers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
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
void __ldsem_wake_readers(struct ld_semaphore * sem)
```

```json
{
  "name": "__ldsem_wake_readers",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585668992,
      "name": "__ldsem_wake_readers",
      "external": false,
      "loc": "drivers/tty/tty_ldsem.c:74",
      "file": "drivers/tty/tty_ldsem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_ldsem.c:ldsem_down_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585668992,
      "name": "__ldsem_wake_readers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
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
void __ldsem_wake_readers(struct ld_semaphore * sem)
```

```json
{
  "name": "__ldsem_wake_readers",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585777088,
      "name": "__ldsem_wake_readers",
      "external": false,
      "loc": "drivers/tty/tty_ldsem.c:74",
      "file": "drivers/tty/tty_ldsem.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/tty_ldsem.c:ldsem_down_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585777088,
      "name": "__ldsem_wake_readers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
void __ldsem_wake_readers(struct ld_semaphore * sem)
```
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
void __ldsem_wake_readers(struct ld_semaphore * sem)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
void __ldsem_wake_readers(struct ld_semaphore * sem)
```
</details>
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
