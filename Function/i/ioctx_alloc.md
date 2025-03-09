# Function: <code>ioctx_alloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ioctx_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581321548,
      "name": "ioctx_alloc",
      "external": false,
      "loc": "fs/aio.c:690",
      "file": "fs/aio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/aio.c:SyS_io_setup"
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
  "name": "ioctx_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581489677,
      "name": "ioctx_alloc",
      "external": false,
      "loc": "fs/aio.c:700",
      "file": "fs/aio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/aio.c:SyS_io_setup"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct kioctx * ioctx_alloc(unsigned int nr_events)
```

```json
{
  "name": "ioctx_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581571920,
      "name": "ioctx_alloc",
      "external": false,
      "loc": "fs/aio.c:703",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:compat_SyS_io_setup",
        "fs/aio.c:SyS_io_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581571920,
      "name": "ioctx_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1270
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
struct kioctx * ioctx_alloc(unsigned int nr_events)
```

```json
{
  "name": "ioctx_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581628592,
      "name": "ioctx_alloc",
      "external": false,
      "loc": "fs/aio.c:702",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:compat_SyS_io_setup",
        "fs/aio.c:SyS_io_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581628592,
      "name": "ioctx_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1241
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
struct kioctx * ioctx_alloc(unsigned int nr_events)
```

```json
{
  "name": "ioctx_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581773376,
      "name": "ioctx_alloc",
      "external": false,
      "loc": "fs/aio.c:725",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:compat_SyS_io_setup",
        "fs/aio.c:SyS_io_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581773376,
      "name": "ioctx_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1249
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
struct kioctx * ioctx_alloc(unsigned int nr_events)
```

```json
{
  "name": "ioctx_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581946688,
      "name": "ioctx_alloc",
      "external": false,
      "loc": "fs/aio.c:688",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:__x32_compat_sys_io_setup",
        "fs/aio.c:__ia32_compat_sys_io_setup",
        "fs/aio.c:__ia32_sys_io_setup",
        "fs/aio.c:__x64_sys_io_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581946688,
      "name": "ioctx_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1303
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
struct kioctx * ioctx_alloc(unsigned int nr_events)
```

```json
{
  "name": "ioctx_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582032944,
      "name": "ioctx_alloc",
      "external": false,
      "loc": "fs/aio.c:704",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:__x32_compat_sys_io_setup",
        "fs/aio.c:__ia32_compat_sys_io_setup",
        "fs/aio.c:__ia32_sys_io_setup",
        "fs/aio.c:__x64_sys_io_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582032944,
      "name": "ioctx_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1303
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
struct kioctx * ioctx_alloc(unsigned int nr_events)
```

```json
{
  "name": "ioctx_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582172800,
      "name": "ioctx_alloc",
      "external": false,
      "loc": "fs/aio.c:701",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:__x32_compat_sys_io_setup",
        "fs/aio.c:__ia32_compat_sys_io_setup",
        "fs/aio.c:__ia32_sys_io_setup",
        "fs/aio.c:__x64_sys_io_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582172800,
      "name": "ioctx_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1323
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
struct kioctx * ioctx_alloc(unsigned int nr_events)
```

```json
{
  "name": "ioctx_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582250192,
      "name": "ioctx_alloc",
      "external": false,
      "loc": "fs/aio.c:701",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:__x32_compat_sys_io_setup",
        "fs/aio.c:__ia32_compat_sys_io_setup",
        "fs/aio.c:__ia32_sys_io_setup",
        "fs/aio.c:__x64_sys_io_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582250192,
      "name": "ioctx_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1323
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
struct kioctx * ioctx_alloc(unsigned int nr_events)
```

```json
{
  "name": "ioctx_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582486560,
      "name": "ioctx_alloc",
      "external": false,
      "loc": "fs/aio.c:701",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:__x32_compat_sys_io_setup",
        "fs/aio.c:__ia32_compat_sys_io_setup",
        "fs/aio.c:__ia32_sys_io_setup",
        "fs/aio.c:__x64_sys_io_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582486560,
      "name": "ioctx_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 955
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
struct kioctx * ioctx_alloc(unsigned int nr_events)
```

```json
{
  "name": "ioctx_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582543216,
      "name": "ioctx_alloc",
      "external": false,
      "loc": "fs/aio.c:703",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:__x32_compat_sys_io_setup",
        "fs/aio.c:__ia32_compat_sys_io_setup",
        "fs/aio.c:__ia32_sys_io_setup",
        "fs/aio.c:__x64_sys_io_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582543216,
      "name": "ioctx_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 938
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
struct kioctx * ioctx_alloc(unsigned int nr_events)
```

```json
{
  "name": "ioctx_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582571344,
      "name": "ioctx_alloc",
      "external": false,
      "loc": "fs/aio.c:700",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:__x32_compat_sys_io_setup",
        "fs/aio.c:__ia32_compat_sys_io_setup",
        "fs/aio.c:__ia32_sys_io_setup",
        "fs/aio.c:__x64_sys_io_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582571344,
      "name": "ioctx_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 926
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
struct kioctx * ioctx_alloc(unsigned int nr_events)
```

```json
{
  "name": "ioctx_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582888768,
      "name": "ioctx_alloc",
      "external": false,
      "loc": "fs/aio.c:701",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:__x64_compat_sys_io_setup",
        "fs/aio.c:__ia32_compat_sys_io_setup",
        "fs/aio.c:__ia32_sys_io_setup",
        "fs/aio.c:__x64_sys_io_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582888768,
      "name": "ioctx_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 987
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
struct kioctx * ioctx_alloc(unsigned int nr_events)
```

```json
{
  "name": "ioctx_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583447216,
      "name": "ioctx_alloc",
      "external": false,
      "loc": "fs/aio.c:727",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:__ia32_compat_sys_io_setup",
        "fs/aio.c:__ia32_sys_io_setup",
        "fs/aio.c:__x64_sys_io_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583447216,
      "name": "ioctx_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 955
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
struct kioctx * ioctx_alloc(unsigned int nr_events)
```

```json
{
  "name": "ioctx_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584037744,
      "name": "ioctx_alloc",
      "external": false,
      "loc": "fs/aio.c:731",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:__ia32_compat_sys_io_setup",
        "fs/aio.c:__ia32_sys_io_setup",
        "fs/aio.c:__x64_sys_io_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584037744,
      "name": "ioctx_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 962
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
struct kioctx * ioctx_alloc(unsigned int nr_events)
```

```json
{
  "name": "ioctx_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584262464,
      "name": "ioctx_alloc",
      "external": false,
      "loc": "fs/aio.c:729",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:__ia32_compat_sys_io_setup",
        "fs/aio.c:__ia32_sys_io_setup",
        "fs/aio.c:__x64_sys_io_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584262464,
      "name": "ioctx_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 961
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
struct kioctx * ioctx_alloc(unsigned int nr_events)
```

```json
{
  "name": "ioctx_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584479248,
      "name": "ioctx_alloc",
      "external": false,
      "loc": "fs/aio.c:739",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:__ia32_compat_sys_io_setup",
        "fs/aio.c:__ia32_sys_io_setup",
        "fs/aio.c:__x64_sys_io_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584479248,
      "name": "ioctx_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 961
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
struct kioctx * ioctx_alloc(unsigned int nr_events)
```

```json
{
  "name": "ioctx_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493820496,
      "name": "ioctx_alloc",
      "external": false,
      "loc": "fs/aio.c:701",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:__arm64_compat_sys_io_setup",
        "fs/aio.c:__arm64_sys_io_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493820496,
      "name": "ioctx_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1512
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
  "name": "ioctx_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3227322696,
      "name": "ioctx_alloc",
      "external": false,
      "loc": "fs/aio.c:701",
      "file": "fs/aio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/aio.c:__se_sys_io_setup"
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
struct kioctx * ioctx_alloc(unsigned int nr_events)
```

```json
{
  "name": "ioctx_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287440528,
      "name": "ioctx_alloc",
      "external": false,
      "loc": "fs/aio.c:701",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:__se_compat_sys_io_setup",
        "fs/aio.c:__se_sys_io_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287440528,
      "name": "ioctx_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1912
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
  "name": "ioctx_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273398352,
      "name": "ioctx_alloc",
      "external": false,
      "loc": "fs/aio.c:701",
      "file": "fs/aio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/aio.c:__se_sys_io_setup"
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
struct kioctx * ioctx_alloc(unsigned int nr_events)
```

```json
{
  "name": "ioctx_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582218928,
      "name": "ioctx_alloc",
      "external": false,
      "loc": "fs/aio.c:701",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:__x32_compat_sys_io_setup",
        "fs/aio.c:__ia32_compat_sys_io_setup",
        "fs/aio.c:__ia32_sys_io_setup",
        "fs/aio.c:__x64_sys_io_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582218928,
      "name": "ioctx_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1323
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
struct kioctx * ioctx_alloc(unsigned int nr_events)
```

```json
{
  "name": "ioctx_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582156768,
      "name": "ioctx_alloc",
      "external": false,
      "loc": "fs/aio.c:701",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:__x32_compat_sys_io_setup",
        "fs/aio.c:__ia32_compat_sys_io_setup",
        "fs/aio.c:__ia32_sys_io_setup",
        "fs/aio.c:__x64_sys_io_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582156768,
      "name": "ioctx_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1323
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
struct kioctx * ioctx_alloc(unsigned int nr_events)
```

```json
{
  "name": "ioctx_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582209408,
      "name": "ioctx_alloc",
      "external": false,
      "loc": "fs/aio.c:701",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:__x32_compat_sys_io_setup",
        "fs/aio.c:__ia32_compat_sys_io_setup",
        "fs/aio.c:__ia32_sys_io_setup",
        "fs/aio.c:__x64_sys_io_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582209408,
      "name": "ioctx_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1323
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
struct kioctx * ioctx_alloc(unsigned int nr_events)
```

```json
{
  "name": "ioctx_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582287248,
      "name": "ioctx_alloc",
      "external": false,
      "loc": "fs/aio.c:701",
      "file": "fs/aio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/aio.c:__x32_compat_sys_io_setup",
        "fs/aio.c:__ia32_compat_sys_io_setup",
        "fs/aio.c:__ia32_sys_io_setup",
        "fs/aio.c:__x64_sys_io_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582287248,
      "name": "ioctx_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1397
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
struct kioctx * ioctx_alloc(unsigned int nr_events)
```
</details>
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
struct kioctx * ioctx_alloc(unsigned int nr_events)
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
struct kioctx * ioctx_alloc(unsigned int nr_events)
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
