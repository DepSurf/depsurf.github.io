# Function: <code>__do_compat_sys_ioctl</code>

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
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__do_compat_sys_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582002098,
      "name": "__do_compat_sys_ioctl",
      "external": false,
      "loc": "fs/compat_ioctl.c:1405",
      "file": "fs/compat_ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/compat_ioctl.c:__x32_compat_sys_ioctl",
        "fs/compat_ioctl.c:__ia32_compat_sys_ioctl"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__do_compat_sys_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582089794,
      "name": "__do_compat_sys_ioctl",
      "external": false,
      "loc": "fs/compat_ioctl.c:998",
      "file": "fs/compat_ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/compat_ioctl.c:__x32_compat_sys_ioctl",
        "fs/compat_ioctl.c:__ia32_compat_sys_ioctl"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__do_compat_sys_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582251250,
      "name": "__do_compat_sys_ioctl",
      "external": false,
      "loc": "fs/compat_ioctl.c:995",
      "file": "fs/compat_ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/compat_ioctl.c:__x32_compat_sys_ioctl",
        "fs/compat_ioctl.c:__ia32_compat_sys_ioctl"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__do_compat_sys_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582351618,
      "name": "__do_compat_sys_ioctl",
      "external": false,
      "loc": "fs/compat_ioctl.c:995",
      "file": "fs/compat_ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/compat_ioctl.c:__x32_compat_sys_ioctl",
        "fs/compat_ioctl.c:__ia32_compat_sys_ioctl"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
long int __do_compat_sys_ioctl(unsigned int fd, unsigned int cmd, compat_ulong_t arg)
```

```json
{
  "name": "__do_compat_sys_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582171120,
      "name": "__do_compat_sys_ioctl",
      "external": false,
      "loc": "fs/ioctl.c:798",
      "file": "fs/ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ioctl.c:__x32_compat_sys_ioctl",
        "fs/ioctl.c:__ia32_compat_sys_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582171120,
      "name": "__do_compat_sys_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 351
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
long int __do_compat_sys_ioctl(unsigned int fd, unsigned int cmd, compat_ulong_t arg)
```

```json
{
  "name": "__do_compat_sys_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582217840,
      "name": "__do_compat_sys_ioctl",
      "external": false,
      "loc": "fs/ioctl.c:793",
      "file": "fs/ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ioctl.c:__x32_compat_sys_ioctl",
        "fs/ioctl.c:__ia32_compat_sys_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582217840,
      "name": "__do_compat_sys_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 351
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
long int __do_compat_sys_ioctl(unsigned int fd, unsigned int cmd, compat_ulong_t arg)
```

```json
{
  "name": "__do_compat_sys_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582244000,
      "name": "__do_compat_sys_ioctl",
      "external": false,
      "loc": "fs/ioctl.c:1109",
      "file": "fs/ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ioctl.c:__x32_compat_sys_ioctl",
        "fs/ioctl.c:__ia32_compat_sys_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582244000,
      "name": "__do_compat_sys_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 390
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
long int __do_compat_sys_ioctl(unsigned int fd, unsigned int cmd, compat_ulong_t arg)
```

```json
{
  "name": "__do_compat_sys_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582561824,
      "name": "__do_compat_sys_ioctl",
      "external": false,
      "loc": "fs/ioctl.c:914",
      "file": "fs/ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ioctl.c:__x64_compat_sys_ioctl",
        "fs/ioctl.c:__ia32_compat_sys_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582561824,
      "name": "__do_compat_sys_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 390
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
long int __do_compat_sys_ioctl(unsigned int fd, unsigned int cmd, compat_ulong_t arg)
```

```json
{
  "name": "__do_compat_sys_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583091056,
      "name": "__do_compat_sys_ioctl",
      "external": false,
      "loc": "fs/ioctl.c:910",
      "file": "fs/ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ioctl.c:__ia32_compat_sys_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583091056,
      "name": "__do_compat_sys_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 420
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
long int __do_compat_sys_ioctl(unsigned int fd, unsigned int cmd, compat_ulong_t arg)
```

```json
{
  "name": "__do_compat_sys_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583659008,
      "name": "__do_compat_sys_ioctl",
      "external": false,
      "loc": "fs/ioctl.c:910",
      "file": "fs/ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ioctl.c:__ia32_compat_sys_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583659008,
      "name": "__do_compat_sys_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 420
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
long int __do_compat_sys_ioctl(unsigned int fd, unsigned int cmd, compat_ulong_t arg)
```

```json
{
  "name": "__do_compat_sys_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583876192,
      "name": "__do_compat_sys_ioctl",
      "external": false,
      "loc": "fs/ioctl.c:910",
      "file": "fs/ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ioctl.c:__ia32_compat_sys_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583876192,
      "name": "__do_compat_sys_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 455
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
long int __do_compat_sys_ioctl(unsigned int fd, unsigned int cmd, compat_ulong_t arg)
```

```json
{
  "name": "__do_compat_sys_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584083232,
      "name": "__do_compat_sys_ioctl",
      "external": false,
      "loc": "fs/ioctl.c:914",
      "file": "fs/ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/ioctl.c:__ia32_compat_sys_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584083232,
      "name": "__do_compat_sys_ioctl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 455
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
  "name": "__do_compat_sys_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336493945032,
      "name": "__do_compat_sys_ioctl",
      "external": false,
      "loc": "fs/compat_ioctl.c:995",
      "file": "fs/compat_ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/compat_ioctl.c:__arm64_compat_sys_ioctl"
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
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "__do_compat_sys_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055287582952,
      "name": "__do_compat_sys_ioctl",
      "external": false,
      "loc": "fs/compat_ioctl.c:995",
      "file": "fs/compat_ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/compat_ioctl.c:__se_compat_sys_ioctl"
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
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__do_compat_sys_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582320354,
      "name": "__do_compat_sys_ioctl",
      "external": false,
      "loc": "fs/compat_ioctl.c:995",
      "file": "fs/compat_ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/compat_ioctl.c:__x32_compat_sys_ioctl",
        "fs/compat_ioctl.c:__ia32_compat_sys_ioctl"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__do_compat_sys_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582258114,
      "name": "__do_compat_sys_ioctl",
      "external": false,
      "loc": "fs/compat_ioctl.c:995",
      "file": "fs/compat_ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/compat_ioctl.c:__x32_compat_sys_ioctl",
        "fs/compat_ioctl.c:__ia32_compat_sys_ioctl"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__do_compat_sys_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582310834,
      "name": "__do_compat_sys_ioctl",
      "external": false,
      "loc": "fs/compat_ioctl.c:995",
      "file": "fs/compat_ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/compat_ioctl.c:__x32_compat_sys_ioctl",
        "fs/compat_ioctl.c:__ia32_compat_sys_ioctl"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__do_compat_sys_ioctl",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582390066,
      "name": "__do_compat_sys_ioctl",
      "external": false,
      "loc": "fs/compat_ioctl.c:995",
      "file": "fs/compat_ioctl.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/compat_ioctl.c:__x32_compat_sys_ioctl",
        "fs/compat_ioctl.c:__ia32_compat_sys_ioctl"
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
long int __do_compat_sys_ioctl(unsigned int fd, unsigned int cmd, compat_ulong_t arg)
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
