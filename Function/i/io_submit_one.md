# Function: <code>io_submit_one</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "io_submit_one",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581324510,
      "name": "io_submit_one",
      "external": false,
      "loc": "fs/aio.c:1496",
      "file": "fs/aio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/aio.c:do_io_submit"
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
  "name": "io_submit_one",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581491663,
      "name": "io_submit_one",
      "external": false,
      "loc": "fs/aio.c:1504",
      "file": "fs/aio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/aio.c:do_io_submit"
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
  "name": "io_submit_one",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581570543,
      "name": "io_submit_one",
      "external": false,
      "loc": "fs/aio.c:1536",
      "file": "fs/aio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/aio.c:do_io_submit"
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
  "name": "io_submit_one",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581627050,
      "name": "io_submit_one",
      "external": false,
      "loc": "fs/aio.c:1541",
      "file": "fs/aio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/aio.c:do_io_submit"
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
  "name": "io_submit_one",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581771392,
      "name": "io_submit_one",
      "external": false,
      "loc": "fs/aio.c:1555",
      "file": "fs/aio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/aio.c:do_io_submit"
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
int io_submit_one(struct kioctx * ctx, struct iocb * user_iocb, bool compat)
```

```json
{
  "name": "io_submit_one",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581943280,
      "name": "io_submit_one",
      "external": false,
      "loc": "fs/aio.c:1595",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:__x32_compat_sys_io_submit",
        "fs/aio.c:__ia32_compat_sys_io_submit",
        "fs/aio.c:__ia32_sys_io_submit",
        "fs/aio.c:__x64_sys_io_submit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581943280,
      "name": "io_submit_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 934
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
int io_submit_one(struct kioctx * ctx, struct iocb * user_iocb, bool compat)
```

```json
{
  "name": "io_submit_one",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582028896,
      "name": "io_submit_one",
      "external": false,
      "loc": "fs/aio.c:1893",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:__x32_compat_sys_io_submit",
        "fs/aio.c:__ia32_compat_sys_io_submit",
        "fs/aio.c:__ia32_sys_io_submit",
        "fs/aio.c:__x64_sys_io_submit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582028896,
      "name": "io_submit_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1759
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
int io_submit_one(struct kioctx * ctx, struct iocb * user_iocb, bool compat)
```

```json
{
  "name": "io_submit_one",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582168304,
      "name": "io_submit_one",
      "external": false,
      "loc": "fs/aio.c:1832",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:__x32_compat_sys_io_submit",
        "fs/aio.c:__ia32_compat_sys_io_submit",
        "fs/aio.c:__ia32_sys_io_submit",
        "fs/aio.c:__x64_sys_io_submit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582168304,
      "name": "io_submit_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1305
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
int io_submit_one(struct kioctx * ctx, struct iocb * user_iocb, bool compat)
```

```json
{
  "name": "io_submit_one",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582245696,
      "name": "io_submit_one",
      "external": false,
      "loc": "fs/aio.c:1848",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:__x32_compat_sys_io_submit",
        "fs/aio.c:__ia32_compat_sys_io_submit",
        "fs/aio.c:__ia32_sys_io_submit",
        "fs/aio.c:__x64_sys_io_submit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582245696,
      "name": "io_submit_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1305
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
int io_submit_one(struct kioctx * ctx, struct iocb * user_iocb, bool compat)
```

```json
{
  "name": "io_submit_one",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582482864,
      "name": "io_submit_one",
      "external": false,
      "loc": "fs/aio.c:1855",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:__x32_compat_sys_io_submit",
        "fs/aio.c:__ia32_compat_sys_io_submit",
        "fs/aio.c:__ia32_sys_io_submit",
        "fs/aio.c:__x64_sys_io_submit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582482864,
      "name": "io_submit_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 901
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
int io_submit_one(struct kioctx * ctx, struct iocb * user_iocb, bool compat)
```

```json
{
  "name": "io_submit_one",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582539440,
      "name": "io_submit_one",
      "external": false,
      "loc": "fs/aio.c:1853",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:__x32_compat_sys_io_submit",
        "fs/aio.c:__ia32_compat_sys_io_submit",
        "fs/aio.c:__ia32_sys_io_submit",
        "fs/aio.c:__x64_sys_io_submit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582539440,
      "name": "io_submit_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 927
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
int io_submit_one(struct kioctx * ctx, struct iocb * user_iocb, bool compat)
```

```json
{
  "name": "io_submit_one",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582568448,
      "name": "io_submit_one",
      "external": false,
      "loc": "fs/aio.c:1850",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:__x32_compat_sys_io_submit",
        "fs/aio.c:__ia32_compat_sys_io_submit",
        "fs/aio.c:__ia32_sys_io_submit",
        "fs/aio.c:__x64_sys_io_submit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582568448,
      "name": "io_submit_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 927
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
int io_submit_one(struct kioctx * ctx, struct iocb * user_iocb, bool compat)
```

```json
{
  "name": "io_submit_one",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582885728,
      "name": "io_submit_one",
      "external": false,
      "loc": "fs/aio.c:1968",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:__x64_compat_sys_io_submit",
        "fs/aio.c:__ia32_compat_sys_io_submit",
        "fs/aio.c:__ia32_sys_io_submit",
        "fs/aio.c:__x64_sys_io_submit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582885728,
      "name": "io_submit_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 927
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
int io_submit_one(struct kioctx * ctx, struct iocb * user_iocb, bool compat)
```

```json
{
  "name": "io_submit_one",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583453504,
      "name": "io_submit_one",
      "external": false,
      "loc": "fs/aio.c:1992",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:__ia32_compat_sys_io_submit",
        "fs/aio.c:__ia32_sys_io_submit",
        "fs/aio.c:__x64_sys_io_submit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583453504,
      "name": "io_submit_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 979
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
int io_submit_one(struct kioctx * ctx, struct iocb * user_iocb, bool compat)
```

```json
{
  "name": "io_submit_one",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584043392,
      "name": "io_submit_one",
      "external": false,
      "loc": "fs/aio.c:1993",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:__ia32_compat_sys_io_submit",
        "fs/aio.c:__ia32_sys_io_submit",
        "fs/aio.c:__x64_sys_io_submit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584043392,
      "name": "io_submit_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 979
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
int io_submit_one(struct kioctx * ctx, struct iocb * user_iocb, bool compat)
```

```json
{
  "name": "io_submit_one",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584268112,
      "name": "io_submit_one",
      "external": false,
      "loc": "fs/aio.c:1985",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:__ia32_compat_sys_io_submit",
        "fs/aio.c:__ia32_sys_io_submit",
        "fs/aio.c:__x64_sys_io_submit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584268112,
      "name": "io_submit_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 914
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
int io_submit_one(struct kioctx * ctx, struct iocb * user_iocb, bool compat)
```

```json
{
  "name": "io_submit_one",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584484912,
      "name": "io_submit_one",
      "external": false,
      "loc": "fs/aio.c:2028",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:__ia32_compat_sys_io_submit",
        "fs/aio.c:__ia32_sys_io_submit",
        "fs/aio.c:__x64_sys_io_submit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584484912,
      "name": "io_submit_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 914
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
int io_submit_one(struct kioctx * ctx, struct iocb * user_iocb, bool compat)
```

```json
{
  "name": "io_submit_one",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493815576,
      "name": "io_submit_one",
      "external": false,
      "loc": "fs/aio.c:1848",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:__arm64_compat_sys_io_submit",
        "fs/aio.c:__arm64_sys_io_submit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493815576,
      "name": "io_submit_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2800
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "io_submit_one",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3227324896,
      "name": "io_submit_one",
      "external": false,
      "loc": "fs/aio.c:1848",
      "file": "fs/aio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/aio.c:__se_sys_io_submit"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int io_submit_one(struct kioctx * ctx, struct iocb * user_iocb, bool compat)
```

```json
{
  "name": "io_submit_one",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287433872,
      "name": "io_submit_one",
      "external": false,
      "loc": "fs/aio.c:1848",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:__se_compat_sys_io_submit",
        "fs/aio.c:__se_sys_io_submit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287433872,
      "name": "io_submit_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3796
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
  "name": "io_submit_one",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273396232,
      "name": "io_submit_one",
      "external": false,
      "loc": "fs/aio.c:1848",
      "file": "fs/aio.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:__se_sys_io_submit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273396232,
      "name": "io_submit_one.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1792
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
int io_submit_one(struct kioctx * ctx, struct iocb * user_iocb, bool compat)
```

```json
{
  "name": "io_submit_one",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582214432,
      "name": "io_submit_one",
      "external": false,
      "loc": "fs/aio.c:1848",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:__x32_compat_sys_io_submit",
        "fs/aio.c:__ia32_compat_sys_io_submit",
        "fs/aio.c:__ia32_sys_io_submit",
        "fs/aio.c:__x64_sys_io_submit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582214432,
      "name": "io_submit_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1305
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
int io_submit_one(struct kioctx * ctx, struct iocb * user_iocb, bool compat)
```

```json
{
  "name": "io_submit_one",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582151328,
      "name": "io_submit_one",
      "external": false,
      "loc": "fs/aio.c:1848",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:__x32_compat_sys_io_submit",
        "fs/aio.c:__ia32_compat_sys_io_submit",
        "fs/aio.c:__ia32_sys_io_submit",
        "fs/aio.c:__x64_sys_io_submit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582151328,
      "name": "io_submit_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1295
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
int io_submit_one(struct kioctx * ctx, struct iocb * user_iocb, bool compat)
```

```json
{
  "name": "io_submit_one",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582204912,
      "name": "io_submit_one",
      "external": false,
      "loc": "fs/aio.c:1848",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:__x32_compat_sys_io_submit",
        "fs/aio.c:__ia32_compat_sys_io_submit",
        "fs/aio.c:__ia32_sys_io_submit",
        "fs/aio.c:__x64_sys_io_submit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582204912,
      "name": "io_submit_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1305
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
int io_submit_one(struct kioctx * ctx, struct iocb * user_iocb, bool compat)
```

```json
{
  "name": "io_submit_one",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582279760,
      "name": "io_submit_one",
      "external": false,
      "loc": "fs/aio.c:1848",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:__x32_compat_sys_io_submit",
        "fs/aio.c:__ia32_compat_sys_io_submit",
        "fs/aio.c:__ia32_sys_io_submit",
        "fs/aio.c:__x64_sys_io_submit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582279760,
      "name": "io_submit_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1470
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
int io_submit_one(struct kioctx * ctx, struct iocb * user_iocb, bool compat)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int io_submit_one(struct kioctx * ctx, struct iocb * user_iocb, bool compat)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int io_submit_one(struct kioctx * ctx, struct iocb * user_iocb, bool compat)
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
