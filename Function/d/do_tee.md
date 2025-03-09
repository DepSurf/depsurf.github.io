# Function: <code>do_tee</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_tee",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581204800,
      "name": "do_tee",
      "external": false,
      "loc": "fs/splice.c:1994",
      "file": "fs/splice.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/splice.c:SyS_tee"
      ],
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_tee",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581369366,
      "name": "do_tee",
      "external": false,
      "loc": "fs/splice.c:1998",
      "file": "fs/splice.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/splice.c:SyS_tee"
      ],
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_tee",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581447142,
      "name": "do_tee",
      "external": false,
      "loc": "fs/splice.c:1708",
      "file": "fs/splice.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/splice.c:SyS_tee"
      ],
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_tee",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581501330,
      "name": "do_tee",
      "external": false,
      "loc": "fs/splice.c:1709",
      "file": "fs/splice.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/splice.c:SyS_tee"
      ],
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
  "name": "do_tee",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581643458,
      "name": "do_tee",
      "external": false,
      "loc": "fs/splice.c:1693",
      "file": "fs/splice.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/splice.c:SyS_tee"
      ],
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
long int do_tee(struct file * in, struct file * out, size_t len, unsigned int flags)
```

```json
{
  "name": "do_tee",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581798240,
      "name": "do_tee",
      "external": false,
      "loc": "fs/splice.c:1706",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:__ia32_sys_tee",
        "fs/splice.c:__x64_sys_tee"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581798240,
      "name": "do_tee",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 575
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
long int do_tee(struct file * in, struct file * out, size_t len, unsigned int flags)
```

```json
{
  "name": "do_tee",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581884816,
      "name": "do_tee",
      "external": false,
      "loc": "fs/splice.c:1714",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:__ia32_sys_tee",
        "fs/splice.c:__x64_sys_tee"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581884816,
      "name": "do_tee",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 589
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
long int do_tee(struct file * in, struct file * out, size_t len, unsigned int flags)
```

```json
{
  "name": "do_tee",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582010784,
      "name": "do_tee",
      "external": false,
      "loc": "fs/splice.c:1728",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:__ia32_sys_tee",
        "fs/splice.c:__x64_sys_tee"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582010784,
      "name": "do_tee",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 657
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
long int do_tee(struct file * in, struct file * out, size_t len, unsigned int flags)
```

```json
{
  "name": "do_tee",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582088752,
      "name": "do_tee",
      "external": false,
      "loc": "fs/splice.c:1736",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:__ia32_sys_tee",
        "fs/splice.c:__x64_sys_tee"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582088752,
      "name": "do_tee",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 657
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
long int do_tee(struct file * in, struct file * out, size_t len, unsigned int flags)
```

```json
{
  "name": "do_tee",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582329184,
      "name": "do_tee",
      "external": true,
      "loc": "fs/splice.c:1736",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:__ia32_sys_tee",
        "fs/splice.c:__x64_sys_tee",
        "fs/io_uring.c:io_issue_sqe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582329184,
      "name": "do_tee",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 265
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
long int do_tee(struct file * in, struct file * out, size_t len, unsigned int flags)
```

```json
{
  "name": "do_tee",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582380608,
      "name": "do_tee",
      "external": true,
      "loc": "fs/splice.c:1660",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:__ia32_sys_tee",
        "fs/splice.c:__x64_sys_tee",
        "fs/io_uring.c:io_issue_sqe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582380608,
      "name": "do_tee",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 265
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
long int do_tee(struct file * in, struct file * out, size_t len, unsigned int flags)
```

```json
{
  "name": "do_tee",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582407504,
      "name": "do_tee",
      "external": true,
      "loc": "fs/splice.c:1665",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:__ia32_sys_tee",
        "fs/splice.c:__x64_sys_tee",
        "fs/io_uring.c:io_issue_sqe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582407504,
      "name": "do_tee",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 741
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
long int do_tee(struct file * in, struct file * out, size_t len, unsigned int flags)
```

```json
{
  "name": "do_tee",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582729280,
      "name": "do_tee",
      "external": true,
      "loc": "fs/splice.c:1667",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:__ia32_sys_tee",
        "fs/splice.c:__x64_sys_tee",
        "fs/io_uring.c:io_issue_sqe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582729280,
      "name": "do_tee",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 741
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
long int do_tee(struct file * in, struct file * out, size_t len, unsigned int flags)
```

```json
{
  "name": "do_tee",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583275040,
      "name": "do_tee",
      "external": true,
      "loc": "fs/splice.c:1663",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:__ia32_sys_tee",
        "fs/splice.c:__x64_sys_tee",
        "io_uring/io_uring.c:io_tee"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583275040,
      "name": "do_tee",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 755
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
long int do_tee(struct file * in, struct file * out, size_t len, unsigned int flags)
```

```json
{
  "name": "do_tee",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583857488,
      "name": "do_tee",
      "external": true,
      "loc": "fs/splice.c:1663",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:__ia32_sys_tee",
        "fs/splice.c:__x64_sys_tee",
        "io_uring/splice.c:io_tee"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583857488,
      "name": "do_tee",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 755
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
long int do_tee(struct file * in, struct file * out, size_t len, unsigned int flags)
```

```json
{
  "name": "do_tee",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584078752,
      "name": "do_tee",
      "external": true,
      "loc": "fs/splice.c:1904",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:__ia32_sys_tee",
        "fs/splice.c:__x64_sys_tee",
        "io_uring/splice.c:io_tee"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584078752,
      "name": "do_tee",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1244
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
ssize_t do_tee(struct file * in, struct file * out, size_t len, unsigned int flags)
```

```json
{
  "name": "do_tee",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584294816,
      "name": "do_tee",
      "external": true,
      "loc": "fs/splice.c:1967",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:__ia32_sys_tee",
        "fs/splice.c:__x64_sys_tee",
        "io_uring/splice.c:io_tee"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584294816,
      "name": "do_tee",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1120
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
  "name": "do_tee",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336493621040,
      "name": "do_tee",
      "external": false,
      "loc": "fs/splice.c:1736",
      "file": "fs/splice.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/splice.c:__arm64_sys_tee"
      ],
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "do_tee",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3227168872,
      "name": "do_tee",
      "external": false,
      "loc": "fs/splice.c:1736",
      "file": "fs/splice.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/splice.c:__se_sys_tee"
      ],
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "do_tee",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055287214316,
      "name": "do_tee",
      "external": false,
      "loc": "fs/splice.c:1736",
      "file": "fs/splice.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/splice.c:__se_sys_tee"
      ],
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "do_tee",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273268752,
      "name": "do_tee",
      "external": false,
      "loc": "fs/splice.c:1736",
      "file": "fs/splice.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/splice.c:__se_sys_tee"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
long int do_tee(struct file * in, struct file * out, size_t len, unsigned int flags)
```

```json
{
  "name": "do_tee",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582057488,
      "name": "do_tee",
      "external": false,
      "loc": "fs/splice.c:1736",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:__ia32_sys_tee",
        "fs/splice.c:__x64_sys_tee"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582057488,
      "name": "do_tee",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 657
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
long int do_tee(struct file * in, struct file * out, size_t len, unsigned int flags)
```

```json
{
  "name": "do_tee",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581995040,
      "name": "do_tee",
      "external": false,
      "loc": "fs/splice.c:1736",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:__ia32_sys_tee",
        "fs/splice.c:__x64_sys_tee"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581995040,
      "name": "do_tee",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 657
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
long int do_tee(struct file * in, struct file * out, size_t len, unsigned int flags)
```

```json
{
  "name": "do_tee",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582048768,
      "name": "do_tee",
      "external": false,
      "loc": "fs/splice.c:1736",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:__ia32_sys_tee",
        "fs/splice.c:__x64_sys_tee"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582048768,
      "name": "do_tee",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 657
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
long int do_tee(struct file * in, struct file * out, size_t len, unsigned int flags)
```

```json
{
  "name": "do_tee",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582120448,
      "name": "do_tee",
      "external": false,
      "loc": "fs/splice.c:1736",
      "file": "fs/splice.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/splice.c:__ia32_sys_tee",
        "fs/splice.c:__x64_sys_tee"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582120448,
      "name": "do_tee",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 657
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
long int do_tee(struct file * in, struct file * out, size_t len, unsigned int flags)
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
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>long int</code> ➡️ <code>ssize_t</code>
</li>
</ul>
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
long int do_tee(struct file * in, struct file * out, size_t len, unsigned int flags)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
long int do_tee(struct file * in, struct file * out, size_t len, unsigned int flags)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
long int do_tee(struct file * in, struct file * out, size_t len, unsigned int flags)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
long int do_tee(struct file * in, struct file * out, size_t len, unsigned int flags)
```
</details>
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
