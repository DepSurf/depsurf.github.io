# Function: <code>__alloc_fd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int __alloc_fd(struct files_struct * files, unsigned int start, unsigned int end, unsigned int flags)
```

```json
{
  "name": "__alloc_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581116144,
      "name": "__alloc_fd",
      "external": true,
      "loc": "fs/file.c:496",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file.c:get_unused_fd_flags",
        "fs/file.c:f_dupfd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581116144,
      "name": "__alloc_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 386
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int __alloc_fd(struct files_struct * files, unsigned int start, unsigned int end, unsigned int flags)
```

```json
{
  "name": "__alloc_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581281888,
      "name": "__alloc_fd",
      "external": true,
      "loc": "fs/file.c:497",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file.c:f_dupfd",
        "fs/file.c:get_unused_fd_flags"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581281888,
      "name": "__alloc_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 370
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
int __alloc_fd(struct files_struct * files, unsigned int start, unsigned int end, unsigned int flags)
```

```json
{
  "name": "__alloc_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581360336,
      "name": "__alloc_fd",
      "external": true,
      "loc": "fs/file.c:497",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file.c:f_dupfd",
        "fs/file.c:get_unused_fd_flags"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581360336,
      "name": "__alloc_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 357
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int __alloc_fd(struct files_struct * files, unsigned int start, unsigned int end, unsigned int flags)
```

```json
{
  "name": "__alloc_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581415600,
      "name": "__alloc_fd",
      "external": true,
      "loc": "fs/file.c:483",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file.c:f_dupfd",
        "fs/file.c:get_unused_fd_flags"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581415600,
      "name": "__alloc_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 355
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int __alloc_fd(struct files_struct * files, unsigned int start, unsigned int end, unsigned int flags)
```

```json
{
  "name": "__alloc_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581557216,
      "name": "__alloc_fd",
      "external": true,
      "loc": "fs/file.c:484",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file.c:f_dupfd",
        "fs/file.c:get_unused_fd_flags"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581557216,
      "name": "__alloc_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 355
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
int __alloc_fd(struct files_struct * files, unsigned int start, unsigned int end, unsigned int flags)
```

```json
{
  "name": "__alloc_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__alloc_fd",
      "external": true,
      "loc": "fs/file.c:479",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file.c:f_dupfd",
        "fs/file.c:get_unused_fd_flags"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581715644,
      "name": "__alloc_fd.cold.15",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    },
    {
      "addr": 18446744071581714032,
      "name": "__alloc_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 318
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
int __alloc_fd(struct files_struct * files, unsigned int start, unsigned int end, unsigned int flags)
```

```json
{
  "name": "__alloc_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__alloc_fd",
      "external": true,
      "loc": "fs/file.c:479",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file.c:f_dupfd",
        "fs/file.c:get_unused_fd_flags"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581802364,
      "name": "__alloc_fd.cold.15",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    },
    {
      "addr": 18446744071581800752,
      "name": "__alloc_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 318
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
int __alloc_fd(struct files_struct * files, unsigned int start, unsigned int end, unsigned int flags)
```

```json
{
  "name": "__alloc_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__alloc_fd",
      "external": true,
      "loc": "fs/file.c:480",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file.c:f_dupfd",
        "fs/file.c:get_unused_fd_flags"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581921212,
      "name": "__alloc_fd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071581919536,
      "name": "__alloc_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 334
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
int __alloc_fd(struct files_struct * files, unsigned int start, unsigned int end, unsigned int flags)
```

```json
{
  "name": "__alloc_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__alloc_fd",
      "external": true,
      "loc": "fs/file.c:480",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file.c:f_dupfd",
        "fs/file.c:get_unused_fd_flags"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581993596,
      "name": "__alloc_fd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071581991920,
      "name": "__alloc_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 334
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
int __alloc_fd(struct files_struct * files, unsigned int start, unsigned int end, unsigned int flags)
```

```json
{
  "name": "__alloc_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__alloc_fd",
      "external": true,
      "loc": "fs/file.c:480",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file.c:f_dupfd",
        "fs/file.c:ksys_dup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582227644,
      "name": "__alloc_fd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071582225776,
      "name": "__alloc_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 330
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int __alloc_fd(struct files_struct * files, unsigned int start, unsigned int end, unsigned int flags)
```

```json
{
  "name": "__alloc_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493506536,
      "name": "__alloc_fd",
      "external": true,
      "loc": "fs/file.c:480",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file.c:f_dupfd",
        "fs/file.c:get_unused_fd_flags"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493506536,
      "name": "__alloc_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 544
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
int __alloc_fd(struct files_struct * files, unsigned int start, unsigned int end, unsigned int flags)
```

```json
{
  "name": "__alloc_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227063404,
      "name": "__alloc_fd",
      "external": true,
      "loc": "fs/file.c:480",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file.c:f_dupfd",
        "fs/file.c:get_unused_fd_flags"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227063404,
      "name": "__alloc_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 436
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
int __alloc_fd(struct files_struct * files, unsigned int start, unsigned int end, unsigned int flags)
```

```json
{
  "name": "__alloc_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287070176,
      "name": "__alloc_fd",
      "external": true,
      "loc": "fs/file.c:480",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file.c:f_dupfd",
        "fs/file.c:get_unused_fd_flags"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287070176,
      "name": "__alloc_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 640
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
int __alloc_fd(struct files_struct * files, unsigned int start, unsigned int end, unsigned int flags)
```

```json
{
  "name": "__alloc_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273178840,
      "name": "__alloc_fd",
      "external": true,
      "loc": "fs/file.c:480",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file.c:f_dupfd",
        "fs/file.c:get_unused_fd_flags"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273178840,
      "name": "__alloc_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 490
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
int __alloc_fd(struct files_struct * files, unsigned int start, unsigned int end, unsigned int flags)
```

```json
{
  "name": "__alloc_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__alloc_fd",
      "external": true,
      "loc": "fs/file.c:480",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file.c:f_dupfd",
        "fs/file.c:get_unused_fd_flags"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581962332,
      "name": "__alloc_fd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071581960656,
      "name": "__alloc_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 334
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
int __alloc_fd(struct files_struct * files, unsigned int start, unsigned int end, unsigned int flags)
```

```json
{
  "name": "__alloc_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__alloc_fd",
      "external": true,
      "loc": "fs/file.c:480",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file.c:f_dupfd",
        "fs/file.c:get_unused_fd_flags"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581899900,
      "name": "__alloc_fd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071581898224,
      "name": "__alloc_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 334
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
int __alloc_fd(struct files_struct * files, unsigned int start, unsigned int end, unsigned int flags)
```

```json
{
  "name": "__alloc_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__alloc_fd",
      "external": true,
      "loc": "fs/file.c:480",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file.c:f_dupfd",
        "fs/file.c:get_unused_fd_flags"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581953644,
      "name": "__alloc_fd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071581951968,
      "name": "__alloc_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 334
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
int __alloc_fd(struct files_struct * files, unsigned int start, unsigned int end, unsigned int flags)
```

```json
{
  "name": "__alloc_fd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__alloc_fd",
      "external": true,
      "loc": "fs/file.c:480",
      "file": "fs/file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/file.c:f_dupfd",
        "fs/file.c:get_unused_fd_flags"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582023900,
      "name": "__alloc_fd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071582022160,
      "name": "__alloc_fd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 327
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
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
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
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
int __alloc_fd(struct files_struct * files, unsigned int start, unsigned int end, unsigned int flags)
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
