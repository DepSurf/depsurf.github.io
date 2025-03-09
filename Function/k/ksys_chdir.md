# Function: <code>ksys_chdir</code>

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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int ksys_chdir(const char * filename)
```

```json
{
  "name": "ksys_chdir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581557376,
      "name": "ksys_chdir",
      "external": true,
      "loc": "fs/open.c:448",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:mount_block_root",
        "fs/open.c:__ia32_sys_chdir",
        "fs/open.c:__x64_sys_chdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581557376,
      "name": "ksys_chdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
int ksys_chdir(const char * filename)
```

```json
{
  "name": "ksys_chdir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581642864,
      "name": "ksys_chdir",
      "external": true,
      "loc": "fs/open.c:437",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:mount_block_root",
        "fs/open.c:__ia32_sys_chdir",
        "fs/open.c:__x64_sys_chdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581642864,
      "name": "ksys_chdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
int ksys_chdir(const char * filename)
```

```json
{
  "name": "ksys_chdir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581759600,
      "name": "ksys_chdir",
      "external": true,
      "loc": "fs/open.c:457",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:mount_block_root",
        "fs/open.c:__ia32_sys_chdir",
        "fs/open.c:__x64_sys_chdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581759600,
      "name": "ksys_chdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
int ksys_chdir(const char * filename)
```

```json
{
  "name": "ksys_chdir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581831808,
      "name": "ksys_chdir",
      "external": true,
      "loc": "fs/open.c:457",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:mount_block_root",
        "fs/open.c:__ia32_sys_chdir",
        "fs/open.c:__x64_sys_chdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581831808,
      "name": "ksys_chdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
int ksys_chdir(const char * filename)
```

```json
{
  "name": "ksys_chdir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582052416,
      "name": "ksys_chdir",
      "external": true,
      "loc": "fs/open.c:486",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:mount_block_root",
        "fs/open.c:__ia32_sys_chdir",
        "fs/open.c:__x64_sys_chdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582052416,
      "name": "ksys_chdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
int ksys_chdir(const char * filename)
```

```json
{
  "name": "ksys_chdir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493295112,
      "name": "ksys_chdir",
      "external": true,
      "loc": "fs/open.c:457",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:mount_block_root",
        "fs/open.c:__arm64_sys_chdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493295112,
      "name": "ksys_chdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
int ksys_chdir(const char * filename)
```

```json
{
  "name": "ksys_chdir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226898224,
      "name": "ksys_chdir",
      "external": true,
      "loc": "fs/open.c:457",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:mount_block_root",
        "fs/open.c:__se_sys_chdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226898224,
      "name": "ksys_chdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
int ksys_chdir(const char * filename)
```

```json
{
  "name": "ksys_chdir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286833504,
      "name": "ksys_chdir",
      "external": true,
      "loc": "fs/open.c:457",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:mount_block_root",
        "fs/open.c:__se_sys_chdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286833504,
      "name": "ksys_chdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
int ksys_chdir(const char * filename)
```

```json
{
  "name": "ksys_chdir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273040012,
      "name": "ksys_chdir",
      "external": true,
      "loc": "fs/open.c:457",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:mount_block_root",
        "fs/open.c:__se_sys_chdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273040012,
      "name": "ksys_chdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
int ksys_chdir(const char * filename)
```

```json
{
  "name": "ksys_chdir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581800544,
      "name": "ksys_chdir",
      "external": true,
      "loc": "fs/open.c:457",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:mount_block_root",
        "fs/open.c:__ia32_sys_chdir",
        "fs/open.c:__x64_sys_chdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581800544,
      "name": "ksys_chdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
int ksys_chdir(const char * filename)
```

```json
{
  "name": "ksys_chdir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581738208,
      "name": "ksys_chdir",
      "external": true,
      "loc": "fs/open.c:457",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:mount_block_root",
        "fs/open.c:__ia32_sys_chdir",
        "fs/open.c:__x64_sys_chdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581738208,
      "name": "ksys_chdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
int ksys_chdir(const char * filename)
```

```json
{
  "name": "ksys_chdir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581791856,
      "name": "ksys_chdir",
      "external": true,
      "loc": "fs/open.c:457",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:mount_block_root",
        "fs/open.c:__ia32_sys_chdir",
        "fs/open.c:__x64_sys_chdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581791856,
      "name": "ksys_chdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
int ksys_chdir(const char * filename)
```

```json
{
  "name": "ksys_chdir",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581860992,
      "name": "ksys_chdir",
      "external": true,
      "loc": "fs/open.c:457",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:mount_block_root",
        "fs/open.c:__ia32_sys_chdir",
        "fs/open.c:__x64_sys_chdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581860992,
      "name": "ksys_chdir",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
int ksys_chdir(const char * filename)
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
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
int ksys_chdir(const char * filename)
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
