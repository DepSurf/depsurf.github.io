# Function: <code>fs_name</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fs_name",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581119479,
      "name": "fs_name",
      "external": false,
      "loc": "fs/filesystems.c:149",
      "file": "fs/filesystems.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/filesystems.c:SyS_sysfs"
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
  "name": "fs_name",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581285207,
      "name": "fs_name",
      "external": false,
      "loc": "fs/filesystems.c:149",
      "file": "fs/filesystems.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/filesystems.c:SyS_sysfs"
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
  "name": "fs_name",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581363623,
      "name": "fs_name",
      "external": false,
      "loc": "fs/filesystems.c:149",
      "file": "fs/filesystems.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/filesystems.c:SyS_sysfs"
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
  "name": "fs_name",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581418983,
      "name": "fs_name",
      "external": false,
      "loc": "fs/filesystems.c:150",
      "file": "fs/filesystems.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/filesystems.c:SyS_sysfs"
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
  "name": "fs_name",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581560551,
      "name": "fs_name",
      "external": false,
      "loc": "fs/filesystems.c:151",
      "file": "fs/filesystems.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/filesystems.c:SyS_sysfs"
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
int fs_name(unsigned int index, char * buf)
```

```json
{
  "name": "fs_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581716256,
      "name": "fs_name",
      "external": false,
      "loc": "fs/filesystems.c:151",
      "file": "fs/filesystems.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/filesystems.c:__ia32_sys_sysfs",
        "fs/filesystems.c:__x64_sys_sysfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581716256,
      "name": "fs_name",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int fs_name(unsigned int index, char * buf)
```

```json
{
  "name": "fs_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581802976,
      "name": "fs_name",
      "external": false,
      "loc": "fs/filesystems.c:151",
      "file": "fs/filesystems.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/filesystems.c:__ia32_sys_sysfs",
        "fs/filesystems.c:__x64_sys_sysfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581802976,
      "name": "fs_name",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int fs_name(unsigned int index, char * buf)
```

```json
{
  "name": "fs_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581921856,
      "name": "fs_name",
      "external": false,
      "loc": "fs/filesystems.c:155",
      "file": "fs/filesystems.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/filesystems.c:__ia32_sys_sysfs",
        "fs/filesystems.c:__x64_sys_sysfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581921856,
      "name": "fs_name",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int fs_name(unsigned int index, char * buf)
```

```json
{
  "name": "fs_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581994240,
      "name": "fs_name",
      "external": false,
      "loc": "fs/filesystems.c:155",
      "file": "fs/filesystems.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/filesystems.c:__ia32_sys_sysfs",
        "fs/filesystems.c:__x64_sys_sysfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581994240,
      "name": "fs_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 218
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
int fs_name(unsigned int index, char * buf)
```

```json
{
  "name": "fs_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582228672,
      "name": "fs_name",
      "external": false,
      "loc": "fs/filesystems.c:156",
      "file": "fs/filesystems.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/filesystems.c:__ia32_sys_sysfs",
        "fs/filesystems.c:__x64_sys_sysfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582228672,
      "name": "fs_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 218
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
int fs_name(unsigned int index, char * buf)
```

```json
{
  "name": "fs_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582277072,
      "name": "fs_name",
      "external": false,
      "loc": "fs/filesystems.c:156",
      "file": "fs/filesystems.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/filesystems.c:__ia32_sys_sysfs",
        "fs/filesystems.c:__x64_sys_sysfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582277072,
      "name": "fs_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 218
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
int fs_name(unsigned int index, char * buf)
```

```json
{
  "name": "fs_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582302608,
      "name": "fs_name",
      "external": false,
      "loc": "fs/filesystems.c:156",
      "file": "fs/filesystems.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/filesystems.c:__ia32_sys_sysfs",
        "fs/filesystems.c:__x64_sys_sysfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582302608,
      "name": "fs_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 210
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
int fs_name(unsigned int index, char * buf)
```

```json
{
  "name": "fs_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582621664,
      "name": "fs_name",
      "external": false,
      "loc": "fs/filesystems.c:156",
      "file": "fs/filesystems.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/filesystems.c:__ia32_sys_sysfs",
        "fs/filesystems.c:__x64_sys_sysfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582621664,
      "name": "fs_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 210
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
int fs_name(unsigned int index, char * buf)
```

```json
{
  "name": "fs_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583156448,
      "name": "fs_name",
      "external": false,
      "loc": "fs/filesystems.c:156",
      "file": "fs/filesystems.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/filesystems.c:__ia32_sys_sysfs",
        "fs/filesystems.c:__x64_sys_sysfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583156448,
      "name": "fs_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
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
int fs_name(unsigned int index, char * buf)
```

```json
{
  "name": "fs_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583730224,
      "name": "fs_name",
      "external": false,
      "loc": "fs/filesystems.c:156",
      "file": "fs/filesystems.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/filesystems.c:__ia32_sys_sysfs",
        "fs/filesystems.c:__x64_sys_sysfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583730224,
      "name": "fs_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
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
int fs_name(unsigned int index, char * buf)
```

```json
{
  "name": "fs_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583947296,
      "name": "fs_name",
      "external": false,
      "loc": "fs/filesystems.c:156",
      "file": "fs/filesystems.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/filesystems.c:__ia32_sys_sysfs",
        "fs/filesystems.c:__x64_sys_sysfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583947296,
      "name": "fs_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
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
int fs_name(unsigned int index, char * buf)
```

```json
{
  "name": "fs_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584154736,
      "name": "fs_name",
      "external": false,
      "loc": "fs/filesystems.c:156",
      "file": "fs/filesystems.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/filesystems.c:__ia32_sys_sysfs",
        "fs/filesystems.c:__x64_sys_sysfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584154736,
      "name": "fs_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
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
int fs_name(unsigned int index, char * buf)
```

```json
{
  "name": "fs_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493511472,
      "name": "fs_name",
      "external": false,
      "loc": "fs/filesystems.c:155",
      "file": "fs/filesystems.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/filesystems.c:__arm64_sys_sysfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493511472,
      "name": "fs_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 620
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
  "name": "fs_name",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3227066900,
      "name": "fs_name",
      "external": false,
      "loc": "fs/filesystems.c:155",
      "file": "fs/filesystems.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/filesystems.c:__se_sys_sysfs"
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
  "name": "fs_name",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055287074048,
      "name": "fs_name",
      "external": false,
      "loc": "fs/filesystems.c:155",
      "file": "fs/filesystems.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/filesystems.c:__se_sys_sysfs"
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
  "name": "fs_name",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273182294,
      "name": "fs_name",
      "external": false,
      "loc": "fs/filesystems.c:155",
      "file": "fs/filesystems.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/filesystems.c:__se_sys_sysfs"
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
int fs_name(unsigned int index, char * buf)
```

```json
{
  "name": "fs_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581962976,
      "name": "fs_name",
      "external": false,
      "loc": "fs/filesystems.c:155",
      "file": "fs/filesystems.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/filesystems.c:__ia32_sys_sysfs",
        "fs/filesystems.c:__x64_sys_sysfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581962976,
      "name": "fs_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 218
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
int fs_name(unsigned int index, char * buf)
```

```json
{
  "name": "fs_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581900544,
      "name": "fs_name",
      "external": false,
      "loc": "fs/filesystems.c:155",
      "file": "fs/filesystems.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/filesystems.c:__ia32_sys_sysfs",
        "fs/filesystems.c:__x64_sys_sysfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581900544,
      "name": "fs_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 218
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
int fs_name(unsigned int index, char * buf)
```

```json
{
  "name": "fs_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581954256,
      "name": "fs_name",
      "external": false,
      "loc": "fs/filesystems.c:155",
      "file": "fs/filesystems.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/filesystems.c:__ia32_sys_sysfs",
        "fs/filesystems.c:__x64_sys_sysfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581954256,
      "name": "fs_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 218
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
int fs_name(unsigned int index, char * buf)
```

```json
{
  "name": "fs_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582024672,
      "name": "fs_name",
      "external": false,
      "loc": "fs/filesystems.c:155",
      "file": "fs/filesystems.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/filesystems.c:__ia32_sys_sysfs",
        "fs/filesystems.c:__x64_sys_sysfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582024672,
      "name": "fs_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
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
int fs_name(unsigned int index, char * buf)
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
int fs_name(unsigned int index, char * buf)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int fs_name(unsigned int index, char * buf)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int fs_name(unsigned int index, char * buf)
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
