# Function: <code>ksys_fchown</code>

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
int ksys_fchown(unsigned int fd, uid_t user, gid_t group)
```

```json
{
  "name": "ksys_fchown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581559024,
      "name": "ksys_fchown",
      "external": true,
      "loc": "fs/open.c:706",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:do_name",
        "kernel/uid16.c:__ia32_sys_fchown16",
        "kernel/uid16.c:__x64_sys_fchown16",
        "fs/open.c:__ia32_sys_fchown",
        "fs/open.c:__x64_sys_fchown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581559024,
      "name": "ksys_fchown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
int ksys_fchown(unsigned int fd, uid_t user, gid_t group)
```

```json
{
  "name": "ksys_fchown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581644512,
      "name": "ksys_fchown",
      "external": true,
      "loc": "fs/open.c:695",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:do_name",
        "kernel/uid16.c:__ia32_sys_fchown16",
        "kernel/uid16.c:__x64_sys_fchown16",
        "fs/open.c:__ia32_sys_fchown",
        "fs/open.c:__x64_sys_fchown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581644512,
      "name": "ksys_fchown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
int ksys_fchown(unsigned int fd, uid_t user, gid_t group)
```

```json
{
  "name": "ksys_fchown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581761248,
      "name": "ksys_fchown",
      "external": true,
      "loc": "fs/open.c:715",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:do_name",
        "kernel/uid16.c:__ia32_sys_fchown16",
        "kernel/uid16.c:__x64_sys_fchown16",
        "fs/open.c:__ia32_sys_fchown",
        "fs/open.c:__x64_sys_fchown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581761248,
      "name": "ksys_fchown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
int ksys_fchown(unsigned int fd, uid_t user, gid_t group)
```

```json
{
  "name": "ksys_fchown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581833456,
      "name": "ksys_fchown",
      "external": true,
      "loc": "fs/open.c:715",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:do_name",
        "kernel/uid16.c:__ia32_sys_fchown16",
        "kernel/uid16.c:__x64_sys_fchown16",
        "fs/open.c:__ia32_sys_fchown",
        "fs/open.c:__x64_sys_fchown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581833456,
      "name": "ksys_fchown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
int ksys_fchown(unsigned int fd, uid_t user, gid_t group)
```

```json
{
  "name": "ksys_fchown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582054064,
      "name": "ksys_fchown",
      "external": true,
      "loc": "fs/open.c:744",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:do_name",
        "kernel/uid16.c:__ia32_sys_fchown16",
        "kernel/uid16.c:__x64_sys_fchown16",
        "fs/open.c:__ia32_sys_fchown",
        "fs/open.c:__x64_sys_fchown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582054064,
      "name": "ksys_fchown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
int ksys_fchown(unsigned int fd, uid_t user, gid_t group)
```

```json
{
  "name": "ksys_fchown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582103904,
      "name": "ksys_fchown",
      "external": true,
      "loc": "fs/open.c:747",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/uid16.c:__ia32_sys_fchown16",
        "kernel/uid16.c:__x64_sys_fchown16",
        "fs/open.c:__ia32_sys_fchown",
        "fs/open.c:__x64_sys_fchown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582103904,
      "name": "ksys_fchown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
int ksys_fchown(unsigned int fd, uid_t user, gid_t group)
```

```json
{
  "name": "ksys_fchown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582128816,
      "name": "ksys_fchown",
      "external": true,
      "loc": "fs/open.c:755",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/uid16.c:__ia32_sys_fchown16",
        "kernel/uid16.c:__x64_sys_fchown16",
        "fs/open.c:__ia32_sys_fchown",
        "fs/open.c:__x64_sys_fchown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582128816,
      "name": "ksys_fchown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
int ksys_fchown(unsigned int fd, uid_t user, gid_t group)
```

```json
{
  "name": "ksys_fchown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582445456,
      "name": "ksys_fchown",
      "external": true,
      "loc": "fs/open.c:752",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/uid16.c:__ia32_sys_fchown16",
        "kernel/uid16.c:__x64_sys_fchown16",
        "fs/open.c:__ia32_sys_fchown",
        "fs/open.c:__x64_sys_fchown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582445456,
      "name": "ksys_fchown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
int ksys_fchown(unsigned int fd, uid_t user, gid_t group)
```

```json
{
  "name": "ksys_fchown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582963968,
      "name": "ksys_fchown",
      "external": true,
      "loc": "fs/open.c:777",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/uid16.c:__ia32_sys_fchown16",
        "kernel/uid16.c:__x64_sys_fchown16",
        "fs/open.c:__ia32_sys_fchown",
        "fs/open.c:__x64_sys_fchown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582963968,
      "name": "ksys_fchown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
int ksys_fchown(unsigned int fd, uid_t user, gid_t group)
```

```json
{
  "name": "ksys_fchown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583522848,
      "name": "ksys_fchown",
      "external": true,
      "loc": "fs/open.c:809",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/uid16.c:__ia32_sys_fchown16",
        "kernel/uid16.c:__x64_sys_fchown16",
        "fs/open.c:__ia32_sys_fchown",
        "fs/open.c:__x64_sys_fchown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583522848,
      "name": "ksys_fchown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
int ksys_fchown(unsigned int fd, uid_t user, gid_t group)
```

```json
{
  "name": "ksys_fchown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583738176,
      "name": "ksys_fchown",
      "external": true,
      "loc": "fs/open.c:841",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/uid16.c:__ia32_sys_fchown16",
        "kernel/uid16.c:__x64_sys_fchown16",
        "fs/open.c:__ia32_sys_fchown",
        "fs/open.c:__x64_sys_fchown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583738176,
      "name": "ksys_fchown",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int ksys_fchown(unsigned int fd, uid_t user, gid_t group)
```

```json
{
  "name": "ksys_fchown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583940064,
      "name": "ksys_fchown",
      "external": true,
      "loc": "fs/open.c:861",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/uid16.c:__ia32_sys_fchown16",
        "kernel/uid16.c:__x64_sys_fchown16",
        "fs/open.c:__ia32_sys_fchown",
        "fs/open.c:__x64_sys_fchown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583940064,
      "name": "ksys_fchown",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int ksys_fchown(unsigned int fd, uid_t user, gid_t group)
```

```json
{
  "name": "ksys_fchown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493296672,
      "name": "ksys_fchown",
      "external": true,
      "loc": "fs/open.c:715",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:do_name",
        "kernel/uid16.c:__arm64_sys_fchown16",
        "fs/open.c:__arm64_sys_fchown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493296672,
      "name": "ksys_fchown",
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
int ksys_fchown(unsigned int fd, uid_t user, gid_t group)
```

```json
{
  "name": "ksys_fchown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226899816,
      "name": "ksys_fchown",
      "external": true,
      "loc": "fs/open.c:715",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:do_name",
        "kernel/uid16.c:__se_sys_fchown16",
        "fs/open.c:__se_sys_fchown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226899816,
      "name": "ksys_fchown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
int ksys_fchown(unsigned int fd, uid_t user, gid_t group)
```

```json
{
  "name": "ksys_fchown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286835520,
      "name": "ksys_fchown",
      "external": true,
      "loc": "fs/open.c:715",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:do_name",
        "fs/open.c:__se_sys_fchown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286835520,
      "name": "ksys_fchown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 296
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
int ksys_fchown(unsigned int fd, uid_t user, gid_t group)
```

```json
{
  "name": "ksys_fchown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273041540,
      "name": "ksys_fchown",
      "external": true,
      "loc": "fs/open.c:715",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:do_name",
        "fs/open.c:__se_sys_fchown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273041540,
      "name": "ksys_fchown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
int ksys_fchown(unsigned int fd, uid_t user, gid_t group)
```

```json
{
  "name": "ksys_fchown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581802192,
      "name": "ksys_fchown",
      "external": true,
      "loc": "fs/open.c:715",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:do_name",
        "kernel/uid16.c:__ia32_sys_fchown16",
        "kernel/uid16.c:__x64_sys_fchown16",
        "fs/open.c:__ia32_sys_fchown",
        "fs/open.c:__x64_sys_fchown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581802192,
      "name": "ksys_fchown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
int ksys_fchown(unsigned int fd, uid_t user, gid_t group)
```

```json
{
  "name": "ksys_fchown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581739856,
      "name": "ksys_fchown",
      "external": true,
      "loc": "fs/open.c:715",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:do_name",
        "kernel/uid16.c:__ia32_sys_fchown16",
        "kernel/uid16.c:__x64_sys_fchown16",
        "fs/open.c:__ia32_sys_fchown",
        "fs/open.c:__x64_sys_fchown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581739856,
      "name": "ksys_fchown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
int ksys_fchown(unsigned int fd, uid_t user, gid_t group)
```

```json
{
  "name": "ksys_fchown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581793504,
      "name": "ksys_fchown",
      "external": true,
      "loc": "fs/open.c:715",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:do_name",
        "kernel/uid16.c:__ia32_sys_fchown16",
        "kernel/uid16.c:__x64_sys_fchown16",
        "fs/open.c:__ia32_sys_fchown",
        "fs/open.c:__x64_sys_fchown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581793504,
      "name": "ksys_fchown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
int ksys_fchown(unsigned int fd, uid_t user, gid_t group)
```

```json
{
  "name": "ksys_fchown",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581862640,
      "name": "ksys_fchown",
      "external": true,
      "loc": "fs/open.c:715",
      "file": "fs/open.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:do_name",
        "kernel/uid16.c:__ia32_sys_fchown16",
        "kernel/uid16.c:__x64_sys_fchown16",
        "fs/open.c:__ia32_sys_fchown",
        "fs/open.c:__x64_sys_fchown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581862640,
      "name": "ksys_fchown",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
int ksys_fchown(unsigned int fd, uid_t user, gid_t group)
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
