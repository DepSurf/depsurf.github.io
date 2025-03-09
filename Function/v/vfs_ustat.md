# Function: <code>vfs_ustat</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int vfs_ustat(dev_t dev, struct kstatfs * sbuf)
```

```json
{
  "name": "vfs_ustat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581212128,
      "name": "vfs_ustat",
      "external": true,
      "loc": "fs/statfs.c:216",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:SYSC_ustat",
        "fs/compat.c:C_SYSC_ustat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581212128,
      "name": "vfs_ustat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
int vfs_ustat(dev_t dev, struct kstatfs * sbuf)
```

```json
{
  "name": "vfs_ustat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581376816,
      "name": "vfs_ustat",
      "external": true,
      "loc": "fs/statfs.c:216",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:SYSC_ustat",
        "fs/compat.c:C_SYSC_ustat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581376816,
      "name": "vfs_ustat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
int vfs_ustat(dev_t dev, struct kstatfs * sbuf)
```

```json
{
  "name": "vfs_ustat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581454560,
      "name": "vfs_ustat",
      "external": true,
      "loc": "fs/statfs.c:216",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:SYSC_ustat",
        "fs/compat.c:C_SYSC_ustat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581454560,
      "name": "vfs_ustat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
int vfs_ustat(dev_t dev, struct kstatfs * sbuf)
```

```json
{
  "name": "vfs_ustat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581510496,
      "name": "vfs_ustat",
      "external": true,
      "loc": "fs/statfs.c:219",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:C_SYSC_ustat",
        "fs/statfs.c:SYSC_ustat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581510496,
      "name": "vfs_ustat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
int vfs_ustat(dev_t dev, struct kstatfs * sbuf)
```

```json
{
  "name": "vfs_ustat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581651296,
      "name": "vfs_ustat",
      "external": false,
      "loc": "fs/statfs.c:220",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:C_SYSC_ustat",
        "fs/statfs.c:SYSC_ustat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581651296,
      "name": "vfs_ustat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
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
int vfs_ustat(dev_t dev, struct kstatfs * sbuf)
```

```json
{
  "name": "vfs_ustat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581814048,
      "name": "vfs_ustat",
      "external": false,
      "loc": "fs/statfs.c:220",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:__do_compat_sys_ustat",
        "fs/statfs.c:__do_sys_ustat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581814048,
      "name": "vfs_ustat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
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
int vfs_ustat(dev_t dev, struct kstatfs * sbuf)
```

```json
{
  "name": "vfs_ustat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581901040,
      "name": "vfs_ustat",
      "external": false,
      "loc": "fs/statfs.c:220",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:__do_compat_sys_ustat",
        "fs/statfs.c:__do_sys_ustat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581901040,
      "name": "vfs_ustat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
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
int vfs_ustat(dev_t dev, struct kstatfs * sbuf)
```

```json
{
  "name": "vfs_ustat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582026576,
      "name": "vfs_ustat",
      "external": false,
      "loc": "fs/statfs.c:234",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:__do_compat_sys_ustat",
        "fs/statfs.c:__do_sys_ustat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582026576,
      "name": "vfs_ustat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
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
int vfs_ustat(dev_t dev, struct kstatfs * sbuf)
```

```json
{
  "name": "vfs_ustat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582104512,
      "name": "vfs_ustat",
      "external": false,
      "loc": "fs/statfs.c:234",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:__do_compat_sys_ustat",
        "fs/statfs.c:__do_sys_ustat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582104512,
      "name": "vfs_ustat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vfs_ustat",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582341340,
      "name": "vfs_ustat",
      "external": false,
      "loc": "fs/statfs.c:234",
      "file": "fs/statfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/statfs.c:__do_compat_sys_ustat",
        "fs/statfs.c:__do_sys_ustat"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vfs_ustat",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582392830,
      "name": "vfs_ustat",
      "external": false,
      "loc": "fs/statfs.c:236",
      "file": "fs/statfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/statfs.c:__do_compat_sys_ustat",
        "fs/statfs.c:__do_sys_ustat"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vfs_ustat",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582420175,
      "name": "vfs_ustat",
      "external": false,
      "loc": "fs/statfs.c:236",
      "file": "fs/statfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/statfs.c:__do_compat_sys_ustat",
        "fs/statfs.c:__do_sys_ustat"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vfs_ustat",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582742991,
      "name": "vfs_ustat",
      "external": false,
      "loc": "fs/statfs.c:236",
      "file": "fs/statfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/statfs.c:__do_compat_sys_ustat",
        "fs/statfs.c:__do_sys_ustat"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vfs_ustat",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583289656,
      "name": "vfs_ustat",
      "external": false,
      "loc": "fs/statfs.c:236",
      "file": "fs/statfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/statfs.c:__do_compat_sys_ustat",
        "fs/statfs.c:__do_sys_ustat"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vfs_ustat",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583873288,
      "name": "vfs_ustat",
      "external": false,
      "loc": "fs/statfs.c:236",
      "file": "fs/statfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/statfs.c:__do_compat_sys_ustat",
        "fs/statfs.c:__do_sys_ustat"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vfs_ustat",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584095048,
      "name": "vfs_ustat",
      "external": false,
      "loc": "fs/statfs.c:236",
      "file": "fs/statfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/statfs.c:__do_compat_sys_ustat",
        "fs/statfs.c:__do_sys_ustat"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vfs_ustat",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584311192,
      "name": "vfs_ustat",
      "external": false,
      "loc": "fs/statfs.c:236",
      "file": "fs/statfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/statfs.c:__do_compat_sys_ustat",
        "fs/statfs.c:__do_sys_ustat"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int vfs_ustat(dev_t dev, struct kstatfs * sbuf)
```

```json
{
  "name": "vfs_ustat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493641680,
      "name": "vfs_ustat",
      "external": false,
      "loc": "fs/statfs.c:234",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:__do_compat_sys_ustat",
        "fs/statfs.c:__do_sys_ustat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493641680,
      "name": "vfs_ustat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
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
  "name": "vfs_ustat",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3227179396,
      "name": "vfs_ustat",
      "external": false,
      "loc": "fs/statfs.c:234",
      "file": "fs/statfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/statfs.c:__do_sys_ustat"
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
int vfs_ustat(dev_t dev, struct kstatfs * sbuf)
```

```json
{
  "name": "vfs_ustat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287234240,
      "name": "vfs_ustat",
      "external": false,
      "loc": "fs/statfs.c:234",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:__do_compat_sys_ustat",
        "fs/statfs.c:__do_sys_ustat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287234240,
      "name": "vfs_ustat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
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
  "name": "vfs_ustat",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273277210,
      "name": "vfs_ustat",
      "external": false,
      "loc": "fs/statfs.c:234",
      "file": "fs/statfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/statfs.c:__do_sys_ustat"
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
int vfs_ustat(dev_t dev, struct kstatfs * sbuf)
```

```json
{
  "name": "vfs_ustat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582073248,
      "name": "vfs_ustat",
      "external": false,
      "loc": "fs/statfs.c:234",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:__do_compat_sys_ustat",
        "fs/statfs.c:__do_sys_ustat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582073248,
      "name": "vfs_ustat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
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
int vfs_ustat(dev_t dev, struct kstatfs * sbuf)
```

```json
{
  "name": "vfs_ustat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582010800,
      "name": "vfs_ustat",
      "external": false,
      "loc": "fs/statfs.c:234",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:__do_compat_sys_ustat",
        "fs/statfs.c:__do_sys_ustat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582010800,
      "name": "vfs_ustat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
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
int vfs_ustat(dev_t dev, struct kstatfs * sbuf)
```

```json
{
  "name": "vfs_ustat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582064528,
      "name": "vfs_ustat",
      "external": false,
      "loc": "fs/statfs.c:234",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:__do_compat_sys_ustat",
        "fs/statfs.c:__do_sys_ustat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582064528,
      "name": "vfs_ustat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
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
int vfs_ustat(dev_t dev, struct kstatfs * sbuf)
```

```json
{
  "name": "vfs_ustat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582136272,
      "name": "vfs_ustat",
      "external": false,
      "loc": "fs/statfs.c:234",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:__do_compat_sys_ustat",
        "fs/statfs.c:__do_sys_ustat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582136272,
      "name": "vfs_ustat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int vfs_ustat(dev_t dev, struct kstatfs * sbuf)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int vfs_ustat(dev_t dev, struct kstatfs * sbuf)
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
int vfs_ustat(dev_t dev, struct kstatfs * sbuf)
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
