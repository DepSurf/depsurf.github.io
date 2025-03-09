# Function: <code>locks_translate_pid</code>

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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "locks_translate_pid",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581808736,
      "name": "locks_translate_pid",
      "external": false,
      "loc": "fs/locks.c:2068",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/locks.c:locks_show",
        "fs/locks.c:lock_get_status",
        "fs/locks.c:fcntl_getlk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581808736,
      "name": "locks_translate_pid.isra.41",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
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
  "name": "locks_translate_pid",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581981952,
      "name": "locks_translate_pid",
      "external": false,
      "loc": "fs/locks.c:2066",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/locks.c:locks_show",
        "fs/locks.c:lock_get_status",
        "fs/locks.c:fcntl_getlk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581981952,
      "name": "locks_translate_pid.isra.42",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "locks_translate_pid",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582070640,
      "name": "locks_translate_pid",
      "external": false,
      "loc": "fs/locks.c:2180",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/locks.c:locks_show",
        "fs/locks.c:lock_get_status",
        "fs/locks.c:fcntl_getlk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582070640,
      "name": "locks_translate_pid.isra.41",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "locks_translate_pid",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582233546,
      "name": "locks_translate_pid",
      "external": false,
      "loc": "fs/locks.c:2198",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/locks.c:locks_show",
        "fs/locks.c:lock_get_status",
        "fs/locks.c:fcntl_getlk"
      ],
      "caller_func": [
        "fs/locks.c:locks_show",
        "fs/locks.c:lock_get_status",
        "fs/locks.c:fcntl_getlk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582232448,
      "name": "locks_translate_pid.isra.0.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
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
  "name": "locks_translate_pid",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582333242,
      "name": "locks_translate_pid",
      "external": false,
      "loc": "fs/locks.c:2287",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/locks.c:locks_show",
        "fs/locks.c:lock_get_status",
        "fs/locks.c:fcntl_getlk"
      ],
      "caller_func": [
        "fs/locks.c:locks_show",
        "fs/locks.c:lock_get_status",
        "fs/locks.c:fcntl_getlk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582332128,
      "name": "locks_translate_pid.isra.0.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
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
pid_t locks_translate_pid(struct file_lock * fl, struct pid_namespace * ns)
```

```json
{
  "name": "locks_translate_pid",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582619776,
      "name": "locks_translate_pid",
      "external": false,
      "loc": "fs/locks.c:2290",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/locks.c:locks_show",
        "fs/locks.c:lock_get_status",
        "fs/locks.c:fcntl_getlk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582619776,
      "name": "locks_translate_pid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
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
pid_t locks_translate_pid(struct file_lock * fl, struct pid_namespace * ns)
```

```json
{
  "name": "locks_translate_pid",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582692192,
      "name": "locks_translate_pid",
      "external": false,
      "loc": "fs/locks.c:2291",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/locks.c:locks_show",
        "fs/locks.c:lock_get_status",
        "fs/locks.c:fcntl_getlk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582692192,
      "name": "locks_translate_pid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
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
pid_t locks_translate_pid(struct file_lock * fl, struct pid_namespace * ns)
```

```json
{
  "name": "locks_translate_pid",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582722096,
      "name": "locks_translate_pid",
      "external": false,
      "loc": "fs/locks.c:2294",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/locks.c:locks_show",
        "fs/locks.c:lock_get_status",
        "fs/locks.c:fcntl_getlk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582722096,
      "name": "locks_translate_pid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
pid_t locks_translate_pid(struct file_lock * fl, struct pid_namespace * ns)
```

```json
{
  "name": "locks_translate_pid",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583048992,
      "name": "locks_translate_pid",
      "external": false,
      "loc": "fs/locks.c:2197",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/locks.c:locks_show",
        "fs/locks.c:lock_get_status",
        "fs/locks.c:fcntl_getlk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583048992,
      "name": "locks_translate_pid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
pid_t locks_translate_pid(struct file_lock * fl, struct pid_namespace * ns)
```

```json
{
  "name": "locks_translate_pid",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583526736,
      "name": "locks_translate_pid",
      "external": false,
      "loc": "fs/locks.c:2183",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/locks.c:locks_show",
        "fs/locks.c:lock_get_status",
        "fs/locks.c:fcntl_getlk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583526736,
      "name": "locks_translate_pid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
pid_t locks_translate_pid(struct file_lock * fl, struct pid_namespace * ns)
```

```json
{
  "name": "locks_translate_pid",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584126752,
      "name": "locks_translate_pid",
      "external": false,
      "loc": "fs/locks.c:2164",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/locks.c:locks_show",
        "fs/locks.c:lock_get_status",
        "fs/locks.c:fcntl_getlk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584126752,
      "name": "locks_translate_pid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
pid_t locks_translate_pid(struct file_lock * fl, struct pid_namespace * ns)
```

```json
{
  "name": "locks_translate_pid",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584353504,
      "name": "locks_translate_pid",
      "external": false,
      "loc": "fs/locks.c:2141",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/locks.c:locks_show",
        "fs/locks.c:lock_get_status",
        "fs/locks.c:fcntl_getlk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584353504,
      "name": "locks_translate_pid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
pid_t locks_translate_pid(struct file_lock * fl, struct pid_namespace * ns)
```

```json
{
  "name": "locks_translate_pid",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584571840,
      "name": "locks_translate_pid",
      "external": false,
      "loc": "fs/locks.c:2148",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/locks.c:locks_show",
        "fs/locks.c:lock_get_status",
        "fs/locks.c:fcntl_getlk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584571840,
      "name": "locks_translate_pid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
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
  "name": "locks_translate_pid",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493913344,
      "name": "locks_translate_pid",
      "external": false,
      "loc": "fs/locks.c:2287",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/locks.c:locks_show",
        "fs/locks.c:lock_get_status",
        "fs/locks.c:fcntl_getlk"
      ],
      "caller_func": [
        "fs/locks.c:locks_show",
        "fs/locks.c:lock_get_status",
        "fs/locks.c:fcntl_getlk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493912104,
      "name": "locks_translate_pid.isra.0.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
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
pid_t locks_translate_pid(struct file_lock * fl, struct pid_namespace * ns)
```

```json
{
  "name": "locks_translate_pid",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227394524,
      "name": "locks_translate_pid",
      "external": false,
      "loc": "fs/locks.c:2287",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/locks.c:locks_show",
        "fs/locks.c:lock_get_status",
        "fs/locks.c:fcntl_getlk64",
        "fs/locks.c:fcntl_getlk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227394524,
      "name": "locks_translate_pid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
pid_t locks_translate_pid(struct file_lock * fl, struct pid_namespace * ns)
```

```json
{
  "name": "locks_translate_pid",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287556656,
      "name": "locks_translate_pid",
      "external": false,
      "loc": "fs/locks.c:2287",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/locks.c:locks_show",
        "fs/locks.c:lock_get_status",
        "fs/locks.c:fcntl_getlk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287556656,
      "name": "locks_translate_pid",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
pid_t locks_translate_pid(struct file_lock * fl, struct pid_namespace * ns)
```

```json
{
  "name": "locks_translate_pid",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273468426,
      "name": "locks_translate_pid",
      "external": false,
      "loc": "fs/locks.c:2287",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/locks.c:locks_show",
        "fs/locks.c:lock_get_status",
        "fs/locks.c:fcntl_getlk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273468426,
      "name": "locks_translate_pid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
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
  "name": "locks_translate_pid",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582301978,
      "name": "locks_translate_pid",
      "external": false,
      "loc": "fs/locks.c:2287",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/locks.c:locks_show",
        "fs/locks.c:lock_get_status",
        "fs/locks.c:fcntl_getlk"
      ],
      "caller_func": [
        "fs/locks.c:locks_show",
        "fs/locks.c:lock_get_status",
        "fs/locks.c:fcntl_getlk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582300864,
      "name": "locks_translate_pid.isra.0.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
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
  "name": "locks_translate_pid",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582239738,
      "name": "locks_translate_pid",
      "external": false,
      "loc": "fs/locks.c:2287",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/locks.c:locks_show",
        "fs/locks.c:lock_get_status",
        "fs/locks.c:fcntl_getlk"
      ],
      "caller_func": [
        "fs/locks.c:locks_show",
        "fs/locks.c:lock_get_status",
        "fs/locks.c:fcntl_getlk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582238624,
      "name": "locks_translate_pid.isra.0.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
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
  "name": "locks_translate_pid",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582292458,
      "name": "locks_translate_pid",
      "external": false,
      "loc": "fs/locks.c:2287",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/locks.c:locks_show",
        "fs/locks.c:lock_get_status",
        "fs/locks.c:fcntl_getlk"
      ],
      "caller_func": [
        "fs/locks.c:locks_show",
        "fs/locks.c:lock_get_status",
        "fs/locks.c:fcntl_getlk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582291344,
      "name": "locks_translate_pid.isra.0.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
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
  "name": "locks_translate_pid",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582372506,
      "name": "locks_translate_pid",
      "external": false,
      "loc": "fs/locks.c:2287",
      "file": "fs/locks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/locks.c:locks_show",
        "fs/locks.c:lock_get_status",
        "fs/locks.c:fcntl_getlk"
      ],
      "caller_func": [
        "fs/locks.c:locks_show",
        "fs/locks.c:lock_get_status",
        "fs/locks.c:fcntl_getlk"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582371376,
      "name": "locks_translate_pid.isra.0.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
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
pid_t locks_translate_pid(struct file_lock * fl, struct pid_namespace * ns)
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
pid_t locks_translate_pid(struct file_lock * fl, struct pid_namespace * ns)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
pid_t locks_translate_pid(struct file_lock * fl, struct pid_namespace * ns)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
pid_t locks_translate_pid(struct file_lock * fl, struct pid_namespace * ns)
```
</details>
</li>
</ul>
