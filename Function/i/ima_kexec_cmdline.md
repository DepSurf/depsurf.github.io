# Function: <code>ima_kexec_cmdline</code>

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
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void ima_kexec_cmdline(const void * buf, int size)
```

```json
{
  "name": "ima_kexec_cmdline",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583681120,
      "name": "ima_kexec_cmdline",
      "external": true,
      "loc": "security/integrity/ima/ima_main.c:671",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:kimage_file_alloc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583681120,
      "name": "ima_kexec_cmdline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
void ima_kexec_cmdline(const void * buf, int size)
```

```json
{
  "name": "ima_kexec_cmdline",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583788528,
      "name": "ima_kexec_cmdline",
      "external": true,
      "loc": "security/integrity/ima/ima_main.c:717",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:kimage_file_alloc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583788528,
      "name": "ima_kexec_cmdline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void ima_kexec_cmdline(const void * buf, int size)
```

```json
{
  "name": "ima_kexec_cmdline",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584179696,
      "name": "ima_kexec_cmdline",
      "external": true,
      "loc": "security/integrity/ima/ima_main.c:823",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:kimage_file_alloc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584179696,
      "name": "ima_kexec_cmdline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void ima_kexec_cmdline(int kernel_fd, const void * buf, int size)
```

```json
{
  "name": "ima_kexec_cmdline",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584298928,
      "name": "ima_kexec_cmdline",
      "external": true,
      "loc": "security/integrity/ima/ima_main.c:911",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:kimage_file_alloc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584298928,
      "name": "ima_kexec_cmdline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
void ima_kexec_cmdline(int kernel_fd, const void * buf, int size)
```

```json
{
  "name": "ima_kexec_cmdline",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584333232,
      "name": "ima_kexec_cmdline",
      "external": true,
      "loc": "security/integrity/ima/ima_main.c:946",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:kimage_file_alloc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584333232,
      "name": "ima_kexec_cmdline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
void ima_kexec_cmdline(int kernel_fd, const void * buf, int size)
```

```json
{
  "name": "ima_kexec_cmdline",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584721424,
      "name": "ima_kexec_cmdline",
      "external": true,
      "loc": "security/integrity/ima/ima_main.c:978",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:kimage_file_alloc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584721424,
      "name": "ima_kexec_cmdline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
void ima_kexec_cmdline(int kernel_fd, const void * buf, int size)
```

```json
{
  "name": "ima_kexec_cmdline",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585396672,
      "name": "ima_kexec_cmdline",
      "external": true,
      "loc": "security/integrity/ima/ima_main.c:998",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:kimage_file_alloc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585396672,
      "name": "ima_kexec_cmdline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
void ima_kexec_cmdline(int kernel_fd, const void * buf, int size)
```

```json
{
  "name": "ima_kexec_cmdline",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586149728,
      "name": "ima_kexec_cmdline",
      "external": true,
      "loc": "security/integrity/ima/ima_main.c:1008",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:kimage_file_alloc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586149728,
      "name": "ima_kexec_cmdline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
void ima_kexec_cmdline(int kernel_fd, const void * buf, int size)
```

```json
{
  "name": "ima_kexec_cmdline",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586387936,
      "name": "ima_kexec_cmdline",
      "external": true,
      "loc": "security/integrity/ima/ima_main.c:1027",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:kimage_file_alloc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586387936,
      "name": "ima_kexec_cmdline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
void ima_kexec_cmdline(int kernel_fd, const void * buf, int size)
```

```json
{
  "name": "ima_kexec_cmdline",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586652672,
      "name": "ima_kexec_cmdline",
      "external": true,
      "loc": "security/integrity/ima/ima_main.c:1041",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:kimage_file_prepare_segments"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586652672,
      "name": "ima_kexec_cmdline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
void ima_kexec_cmdline(const void * buf, int size)
```

```json
{
  "name": "ima_kexec_cmdline",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495591704,
      "name": "ima_kexec_cmdline",
      "external": true,
      "loc": "security/integrity/ima/ima_main.c:717",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:__arm64_sys_kexec_file_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495591704,
      "name": "ima_kexec_cmdline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void ima_kexec_cmdline(const void * buf, int size)
```

```json
{
  "name": "ima_kexec_cmdline",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228952636,
      "name": "ima_kexec_cmdline",
      "external": true,
      "loc": "security/integrity/ima/ima_main.c:717",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3228952636,
      "name": "ima_kexec_cmdline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void ima_kexec_cmdline(const void * buf, int size)
```

```json
{
  "name": "ima_kexec_cmdline",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289693104,
      "name": "ima_kexec_cmdline",
      "external": true,
      "loc": "security/integrity/ima/ima_main.c:717",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:__se_sys_kexec_file_load"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289693104,
      "name": "ima_kexec_cmdline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
void ima_kexec_cmdline(const void * buf, int size)
```

```json
{
  "name": "ima_kexec_cmdline",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274755740,
      "name": "ima_kexec_cmdline",
      "external": true,
      "loc": "security/integrity/ima/ima_main.c:717",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274755740,
      "name": "ima_kexec_cmdline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
void ima_kexec_cmdline(const void * buf, int size)
```

```json
{
  "name": "ima_kexec_cmdline",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583757264,
      "name": "ima_kexec_cmdline",
      "external": true,
      "loc": "security/integrity/ima/ima_main.c:717",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:kimage_file_alloc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583757264,
      "name": "ima_kexec_cmdline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void ima_kexec_cmdline(const void * buf, int size)
```

```json
{
  "name": "ima_kexec_cmdline",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583694320,
      "name": "ima_kexec_cmdline",
      "external": true,
      "loc": "security/integrity/ima/ima_main.c:717",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:kimage_file_alloc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583694320,
      "name": "ima_kexec_cmdline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void ima_kexec_cmdline(const void * buf, int size)
```

```json
{
  "name": "ima_kexec_cmdline",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583741024,
      "name": "ima_kexec_cmdline",
      "external": true,
      "loc": "security/integrity/ima/ima_main.c:717",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:kimage_file_alloc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583741024,
      "name": "ima_kexec_cmdline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
void ima_kexec_cmdline(const void * buf, int size)
```

```json
{
  "name": "ima_kexec_cmdline",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583841968,
      "name": "ima_kexec_cmdline",
      "external": true,
      "loc": "security/integrity/ima/ima_main.c:717",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/kexec_file.c:kimage_file_alloc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583841968,
      "name": "ima_kexec_cmdline",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 41
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
void ima_kexec_cmdline(const void * buf, int size)
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>int kernel_fd</code>
</li>
<li>
<b>Param reordered. </b>
<code>buf, size</code> ➡️ <code>kernel_fd, buf, size</code>
</li>
</ul>
</details>
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
