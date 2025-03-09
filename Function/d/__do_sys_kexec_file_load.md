# Function: <code>__do_sys_kexec_file_load</code>

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
  "name": "__do_sys_kexec_file_load",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580129682,
      "name": "__do_sys_kexec_file_load",
      "external": false,
      "loc": "kernel/kexec_file.c:320",
      "file": "kernel/kexec_file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_file.c:__ia32_sys_kexec_file_load",
        "kernel/kexec_file.c:__x64_sys_kexec_file_load"
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
  "name": "__do_sys_kexec_file_load",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580176994,
      "name": "__do_sys_kexec_file_load",
      "external": false,
      "loc": "kernel/kexec_file.c:319",
      "file": "kernel/kexec_file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_file.c:__ia32_sys_kexec_file_load",
        "kernel/kexec_file.c:__x64_sys_kexec_file_load"
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
  "name": "__do_sys_kexec_file_load",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580223058,
      "name": "__do_sys_kexec_file_load",
      "external": false,
      "loc": "kernel/kexec_file.c:365",
      "file": "kernel/kexec_file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_file.c:__ia32_sys_kexec_file_load",
        "kernel/kexec_file.c:__x64_sys_kexec_file_load"
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
  "name": "__do_sys_kexec_file_load",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580271330,
      "name": "__do_sys_kexec_file_load",
      "external": false,
      "loc": "kernel/kexec_file.c:370",
      "file": "kernel/kexec_file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_file.c:__ia32_sys_kexec_file_load",
        "kernel/kexec_file.c:__x64_sys_kexec_file_load"
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
long int __do_sys_kexec_file_load(int kernel_fd, int initrd_fd, long unsigned int cmdline_len, const char * cmdline_ptr, long unsigned int flags)
```

```json
{
  "name": "__do_sys_kexec_file_load",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580340736,
      "name": "__do_sys_kexec_file_load",
      "external": false,
      "loc": "kernel/kexec_file.c:348",
      "file": "kernel/kexec_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:__ia32_sys_kexec_file_load",
        "kernel/kexec_file.c:__x64_sys_kexec_file_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580340736,
      "name": "__do_sys_kexec_file_load",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 654
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
long int __do_sys_kexec_file_load(int kernel_fd, int initrd_fd, long unsigned int cmdline_len, const char * cmdline_ptr, long unsigned int flags)
```

```json
{
  "name": "__do_sys_kexec_file_load",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580326016,
      "name": "__do_sys_kexec_file_load",
      "external": false,
      "loc": "kernel/kexec_file.c:354",
      "file": "kernel/kexec_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:__ia32_sys_kexec_file_load",
        "kernel/kexec_file.c:__x64_sys_kexec_file_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580326016,
      "name": "__do_sys_kexec_file_load",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 654
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
long int __do_sys_kexec_file_load(int kernel_fd, int initrd_fd, long unsigned int cmdline_len, const char * cmdline_ptr, long unsigned int flags)
```

```json
{
  "name": "__do_sys_kexec_file_load",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580329344,
      "name": "__do_sys_kexec_file_load",
      "external": false,
      "loc": "kernel/kexec_file.c:354",
      "file": "kernel/kexec_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:__ia32_sys_kexec_file_load",
        "kernel/kexec_file.c:__x64_sys_kexec_file_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580329344,
      "name": "__do_sys_kexec_file_load",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 650
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
long int __do_sys_kexec_file_load(int kernel_fd, int initrd_fd, long unsigned int cmdline_len, const char * cmdline_ptr, long unsigned int flags)
```

```json
{
  "name": "__do_sys_kexec_file_load",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580483952,
      "name": "__do_sys_kexec_file_load",
      "external": false,
      "loc": "kernel/kexec_file.c:354",
      "file": "kernel/kexec_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:__ia32_sys_kexec_file_load",
        "kernel/kexec_file.c:__x64_sys_kexec_file_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580483952,
      "name": "__do_sys_kexec_file_load",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 714
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
long int __do_sys_kexec_file_load(int kernel_fd, int initrd_fd, long unsigned int cmdline_len, const char * cmdline_ptr, long unsigned int flags)
```

```json
{
  "name": "__do_sys_kexec_file_load",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580678576,
      "name": "__do_sys_kexec_file_load",
      "external": false,
      "loc": "kernel/kexec_file.c:321",
      "file": "kernel/kexec_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:__ia32_sys_kexec_file_load",
        "kernel/kexec_file.c:__x64_sys_kexec_file_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580678576,
      "name": "__do_sys_kexec_file_load",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 737
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
long int __do_sys_kexec_file_load(int kernel_fd, int initrd_fd, long unsigned int cmdline_len, const char * cmdline_ptr, long unsigned int flags)
```

```json
{
  "name": "__do_sys_kexec_file_load",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580949728,
      "name": "__do_sys_kexec_file_load",
      "external": false,
      "loc": "kernel/kexec_file.c:325",
      "file": "kernel/kexec_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:__ia32_sys_kexec_file_load",
        "kernel/kexec_file.c:__x64_sys_kexec_file_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580949728,
      "name": "__do_sys_kexec_file_load",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 741
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
long int __do_sys_kexec_file_load(int kernel_fd, int initrd_fd, long unsigned int cmdline_len, const char * cmdline_ptr, long unsigned int flags)
```

```json
{
  "name": "__do_sys_kexec_file_load",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581036720,
      "name": "__do_sys_kexec_file_load",
      "external": false,
      "loc": "kernel/kexec_file.c:325",
      "file": "kernel/kexec_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:__ia32_sys_kexec_file_load",
        "kernel/kexec_file.c:__x64_sys_kexec_file_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581036720,
      "name": "__do_sys_kexec_file_load",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 759
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
long int __do_sys_kexec_file_load(int kernel_fd, int initrd_fd, long unsigned int cmdline_len, const char * cmdline_ptr, long unsigned int flags)
```

```json
{
  "name": "__do_sys_kexec_file_load",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__do_sys_kexec_file_load",
      "external": false,
      "loc": "kernel/kexec_file.c:330",
      "file": "kernel/kexec_file.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:__ia32_sys_kexec_file_load",
        "kernel/kexec_file.c:__x64_sys_kexec_file_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581134784,
      "name": "__do_sys_kexec_file_load",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1076
    },
    {
      "addr": 18446744071597417608,
      "name": "__do_sys_kexec_file_load.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
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
  "name": "__do_sys_kexec_file_load",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336491511188,
      "name": "__do_sys_kexec_file_load",
      "external": false,
      "loc": "kernel/kexec_file.c:370",
      "file": "kernel/kexec_file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_file.c:__arm64_sys_kexec_file_load"
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
  "name": "__do_sys_kexec_file_load",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055284475980,
      "name": "__do_sys_kexec_file_load",
      "external": false,
      "loc": "kernel/kexec_file.c:370",
      "file": "kernel/kexec_file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_file.c:__se_sys_kexec_file_load"
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
  "name": "__do_sys_kexec_file_load",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580240130,
      "name": "__do_sys_kexec_file_load",
      "external": false,
      "loc": "kernel/kexec_file.c:370",
      "file": "kernel/kexec_file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_file.c:__ia32_sys_kexec_file_load",
        "kernel/kexec_file.c:__x64_sys_kexec_file_load"
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
  "name": "__do_sys_kexec_file_load",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580187682,
      "name": "__do_sys_kexec_file_load",
      "external": false,
      "loc": "kernel/kexec_file.c:370",
      "file": "kernel/kexec_file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_file.c:__ia32_sys_kexec_file_load",
        "kernel/kexec_file.c:__x64_sys_kexec_file_load"
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
  "name": "__do_sys_kexec_file_load",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580231394,
      "name": "__do_sys_kexec_file_load",
      "external": false,
      "loc": "kernel/kexec_file.c:370",
      "file": "kernel/kexec_file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_file.c:__ia32_sys_kexec_file_load",
        "kernel/kexec_file.c:__x64_sys_kexec_file_load"
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
  "name": "__do_sys_kexec_file_load",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580284370,
      "name": "__do_sys_kexec_file_load",
      "external": false,
      "loc": "kernel/kexec_file.c:370",
      "file": "kernel/kexec_file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kexec_file.c:__ia32_sys_kexec_file_load",
        "kernel/kexec_file.c:__x64_sys_kexec_file_load"
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
long int __do_sys_kexec_file_load(int kernel_fd, int initrd_fd, long unsigned int cmdline_len, const char * cmdline_ptr, long unsigned int flags)
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
