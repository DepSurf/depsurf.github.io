# Function: <code>fs_index</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fs_index",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581119498,
      "name": "fs_index",
      "external": false,
      "loc": "fs/filesystems.c:125",
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
  "name": "fs_index",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581285226,
      "name": "fs_index",
      "external": false,
      "loc": "fs/filesystems.c:125",
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
  "name": "fs_index",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581363642,
      "name": "fs_index",
      "external": false,
      "loc": "fs/filesystems.c:125",
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
  "name": "fs_index",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581419002,
      "name": "fs_index",
      "external": false,
      "loc": "fs/filesystems.c:126",
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
  "name": "fs_index",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581560570,
      "name": "fs_index",
      "external": false,
      "loc": "fs/filesystems.c:127",
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
int fs_index(const char * __name)
```

```json
{
  "name": "fs_index",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581716000,
      "name": "fs_index",
      "external": false,
      "loc": "fs/filesystems.c:127",
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
      "addr": 18446744071581716000,
      "name": "fs_index",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
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
int fs_index(const char * __name)
```

```json
{
  "name": "fs_index",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581802720,
      "name": "fs_index",
      "external": false,
      "loc": "fs/filesystems.c:127",
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
      "addr": 18446744071581802720,
      "name": "fs_index",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
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
int fs_index(const char * __name)
```

```json
{
  "name": "fs_index",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581921616,
      "name": "fs_index",
      "external": false,
      "loc": "fs/filesystems.c:131",
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
      "addr": 18446744071581921616,
      "name": "fs_index",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
int fs_index(const char * __name)
```

```json
{
  "name": "fs_index",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581994000,
      "name": "fs_index",
      "external": false,
      "loc": "fs/filesystems.c:131",
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
      "addr": 18446744071581994000,
      "name": "fs_index",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
int fs_index(const char * __name)
```

```json
{
  "name": "fs_index",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582228176,
      "name": "fs_index",
      "external": false,
      "loc": "fs/filesystems.c:132",
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
      "addr": 18446744071582228176,
      "name": "fs_index",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
int fs_index(const char * __name)
```

```json
{
  "name": "fs_index",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582276576,
      "name": "fs_index",
      "external": false,
      "loc": "fs/filesystems.c:132",
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
      "addr": 18446744071582276576,
      "name": "fs_index",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
int fs_index(const char * __name)
```

```json
{
  "name": "fs_index",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582302112,
      "name": "fs_index",
      "external": false,
      "loc": "fs/filesystems.c:132",
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
      "addr": 18446744071582302112,
      "name": "fs_index",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
int fs_index(const char * __name)
```

```json
{
  "name": "fs_index",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582621152,
      "name": "fs_index",
      "external": false,
      "loc": "fs/filesystems.c:132",
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
      "addr": 18446744071582621152,
      "name": "fs_index",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
int fs_index(const char * __name)
```

```json
{
  "name": "fs_index",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583156304,
      "name": "fs_index",
      "external": false,
      "loc": "fs/filesystems.c:132",
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
      "addr": 18446744071583156304,
      "name": "fs_index",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 143
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
int fs_index(const char * __name)
```

```json
{
  "name": "fs_index",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583730064,
      "name": "fs_index",
      "external": false,
      "loc": "fs/filesystems.c:132",
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
      "addr": 18446744071583730064,
      "name": "fs_index",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 143
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
int fs_index(const char * __name)
```

```json
{
  "name": "fs_index",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583947136,
      "name": "fs_index",
      "external": false,
      "loc": "fs/filesystems.c:132",
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
      "addr": 18446744071583947136,
      "name": "fs_index",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 143
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
int fs_index(const char * __name)
```

```json
{
  "name": "fs_index",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584154576,
      "name": "fs_index",
      "external": false,
      "loc": "fs/filesystems.c:132",
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
      "addr": 18446744071584154576,
      "name": "fs_index",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 143
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
  "name": "fs_index",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336493512200,
      "name": "fs_index",
      "external": false,
      "loc": "fs/filesystems.c:131",
      "file": "fs/filesystems.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/filesystems.c:__arm64_sys_sysfs"
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
  "name": "fs_index",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3227067108,
      "name": "fs_index",
      "external": false,
      "loc": "fs/filesystems.c:131",
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
  "name": "fs_index",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055287074348,
      "name": "fs_index",
      "external": false,
      "loc": "fs/filesystems.c:131",
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
  "name": "fs_index",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273182458,
      "name": "fs_index",
      "external": false,
      "loc": "fs/filesystems.c:131",
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
int fs_index(const char * __name)
```

```json
{
  "name": "fs_index",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581962736,
      "name": "fs_index",
      "external": false,
      "loc": "fs/filesystems.c:131",
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
      "addr": 18446744071581962736,
      "name": "fs_index",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
int fs_index(const char * __name)
```

```json
{
  "name": "fs_index",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581900304,
      "name": "fs_index",
      "external": false,
      "loc": "fs/filesystems.c:131",
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
      "addr": 18446744071581900304,
      "name": "fs_index",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
int fs_index(const char * __name)
```

```json
{
  "name": "fs_index",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581954016,
      "name": "fs_index",
      "external": false,
      "loc": "fs/filesystems.c:131",
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
      "addr": 18446744071581954016,
      "name": "fs_index",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
int fs_index(const char * __name)
```

```json
{
  "name": "fs_index",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582024432,
      "name": "fs_index",
      "external": false,
      "loc": "fs/filesystems.c:131",
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
      "addr": 18446744071582024432,
      "name": "fs_index",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
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
int fs_index(const char * __name)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int fs_index(const char * __name)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int fs_index(const char * __name)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int fs_index(const char * __name)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int fs_index(const char * __name)
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
