# Function: <code>ksys_chroot</code>

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
int ksys_chroot(const char * filename)
```

```json
{
  "name": "ksys_chroot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581557648,
      "name": "ksys_chroot",
      "external": true,
      "loc": "fs/open.c:501",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:prepare_namespace",
        "fs/open.c:__ia32_sys_chroot",
        "fs/open.c:__x64_sys_chroot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581557648,
      "name": "ksys_chroot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 259
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
int ksys_chroot(const char * filename)
```

```json
{
  "name": "ksys_chroot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581643136,
      "name": "ksys_chroot",
      "external": true,
      "loc": "fs/open.c:490",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:prepare_namespace",
        "fs/open.c:__ia32_sys_chroot",
        "fs/open.c:__x64_sys_chroot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581643136,
      "name": "ksys_chroot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 259
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
int ksys_chroot(const char * filename)
```

```json
{
  "name": "ksys_chroot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581759872,
      "name": "ksys_chroot",
      "external": true,
      "loc": "fs/open.c:510",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:prepare_namespace",
        "fs/open.c:__ia32_sys_chroot",
        "fs/open.c:__x64_sys_chroot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581759872,
      "name": "ksys_chroot",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int ksys_chroot(const char * filename)
```

```json
{
  "name": "ksys_chroot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581832080,
      "name": "ksys_chroot",
      "external": true,
      "loc": "fs/open.c:510",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:prepare_namespace",
        "fs/open.c:__ia32_sys_chroot",
        "fs/open.c:__x64_sys_chroot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581832080,
      "name": "ksys_chroot",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int ksys_chroot(const char * filename)
```

```json
{
  "name": "ksys_chroot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582052688,
      "name": "ksys_chroot",
      "external": true,
      "loc": "fs/open.c:539",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:prepare_namespace",
        "fs/open.c:__ia32_sys_chroot",
        "fs/open.c:__x64_sys_chroot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582052688,
      "name": "ksys_chroot",
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
int ksys_chroot(const char * filename)
```

```json
{
  "name": "ksys_chroot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493295368,
      "name": "ksys_chroot",
      "external": true,
      "loc": "fs/open.c:510",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:prepare_namespace",
        "fs/open.c:__arm64_sys_chroot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493295368,
      "name": "ksys_chroot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
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
int ksys_chroot(const char * filename)
```

```json
{
  "name": "ksys_chroot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226898632,
      "name": "ksys_chroot",
      "external": true,
      "loc": "fs/open.c:510",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:prepare_namespace",
        "fs/open.c:__se_sys_chroot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226898632,
      "name": "ksys_chroot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 292
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
int ksys_chroot(const char * filename)
```

```json
{
  "name": "ksys_chroot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286833808,
      "name": "ksys_chroot",
      "external": true,
      "loc": "fs/open.c:510",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:prepare_namespace",
        "fs/open.c:__se_sys_chroot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286833808,
      "name": "ksys_chroot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 344
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
int ksys_chroot(const char * filename)
```

```json
{
  "name": "ksys_chroot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273040392,
      "name": "ksys_chroot",
      "external": true,
      "loc": "fs/open.c:510",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:prepare_namespace",
        "fs/open.c:__se_sys_chroot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273040392,
      "name": "ksys_chroot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
int ksys_chroot(const char * filename)
```

```json
{
  "name": "ksys_chroot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581800816,
      "name": "ksys_chroot",
      "external": true,
      "loc": "fs/open.c:510",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:prepare_namespace",
        "fs/open.c:__ia32_sys_chroot",
        "fs/open.c:__x64_sys_chroot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581800816,
      "name": "ksys_chroot",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int ksys_chroot(const char * filename)
```

```json
{
  "name": "ksys_chroot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581738480,
      "name": "ksys_chroot",
      "external": true,
      "loc": "fs/open.c:510",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:prepare_namespace",
        "fs/open.c:__ia32_sys_chroot",
        "fs/open.c:__x64_sys_chroot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581738480,
      "name": "ksys_chroot",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int ksys_chroot(const char * filename)
```

```json
{
  "name": "ksys_chroot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581792128,
      "name": "ksys_chroot",
      "external": true,
      "loc": "fs/open.c:510",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:prepare_namespace",
        "fs/open.c:__ia32_sys_chroot",
        "fs/open.c:__x64_sys_chroot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581792128,
      "name": "ksys_chroot",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int ksys_chroot(const char * filename)
```

```json
{
  "name": "ksys_chroot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581861264,
      "name": "ksys_chroot",
      "external": true,
      "loc": "fs/open.c:510",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/do_mounts.c:prepare_namespace",
        "fs/open.c:__ia32_sys_chroot",
        "fs/open.c:__x64_sys_chroot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581861264,
      "name": "ksys_chroot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 265
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
int ksys_chroot(const char * filename)
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
int ksys_chroot(const char * filename)
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
