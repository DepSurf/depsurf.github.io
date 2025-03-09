# Function: <code>__audit_file</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void __audit_file(const struct file * file)
```

```json
{
  "name": "__audit_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580061008,
      "name": "__audit_file",
      "external": true,
      "loc": "kernel/auditsc.c:1832",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:SyS_fchmod",
        "fs/open.c:SyS_fchown",
        "fs/xattr.c:SyS_fsetxattr",
        "fs/xattr.c:SyS_fgetxattr",
        "fs/xattr.c:SyS_flistxattr",
        "fs/xattr.c:SyS_fremovexattr",
        "ipc/mqueue.c:SyS_mq_timedsend",
        "ipc/mqueue.c:SyS_mq_timedreceive"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580061008,
      "name": "__audit_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void __audit_file(const struct file * file)
```

```json
{
  "name": "__audit_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580094176,
      "name": "__audit_file",
      "external": true,
      "loc": "kernel/auditsc.c:1831",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:SyS_fchown",
        "fs/open.c:SyS_fchmod",
        "fs/xattr.c:SyS_fremovexattr",
        "fs/xattr.c:SyS_flistxattr",
        "fs/xattr.c:SyS_fgetxattr",
        "fs/xattr.c:SyS_fsetxattr",
        "ipc/mqueue.c:SyS_mq_timedreceive",
        "ipc/mqueue.c:SyS_mq_timedsend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580094176,
      "name": "__audit_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void __audit_file(const struct file * file)
```

```json
{
  "name": "__audit_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580134480,
      "name": "__audit_file",
      "external": true,
      "loc": "kernel/auditsc.c:1836",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:SyS_fchown",
        "fs/open.c:SyS_fchmod",
        "fs/xattr.c:SyS_fremovexattr",
        "fs/xattr.c:SyS_flistxattr",
        "fs/xattr.c:SyS_fgetxattr",
        "fs/xattr.c:SyS_fsetxattr",
        "ipc/mqueue.c:SyS_mq_timedreceive",
        "ipc/mqueue.c:SyS_mq_timedsend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580134480,
      "name": "__audit_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void __audit_file(const struct file * file)
```

```json
{
  "name": "__audit_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580140128,
      "name": "__audit_file",
      "external": true,
      "loc": "kernel/auditsc.c:1845",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:SyS_fchown",
        "fs/open.c:SyS_fchmod",
        "fs/xattr.c:SyS_fremovexattr",
        "fs/xattr.c:SyS_flistxattr",
        "fs/xattr.c:SyS_fgetxattr",
        "fs/xattr.c:SyS_fsetxattr",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:do_mq_timedsend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580140128,
      "name": "__audit_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void __audit_file(const struct file * file)
```

```json
{
  "name": "__audit_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580192736,
      "name": "__audit_file",
      "external": true,
      "loc": "kernel/auditsc.c:1845",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:SyS_fchown",
        "fs/open.c:SyS_fchmod",
        "fs/xattr.c:SyS_fremovexattr",
        "fs/xattr.c:SyS_flistxattr",
        "fs/xattr.c:SyS_fgetxattr",
        "fs/xattr.c:SyS_fsetxattr",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:do_mq_timedsend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580192736,
      "name": "__audit_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void __audit_file(const struct file * file)
```

```json
{
  "name": "__audit_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580252544,
      "name": "__audit_file",
      "external": true,
      "loc": "kernel/auditsc.c:1852",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:ksys_fchown",
        "fs/open.c:ksys_fchmod",
        "fs/xattr.c:__ia32_sys_fremovexattr",
        "fs/xattr.c:__x64_sys_fremovexattr",
        "fs/xattr.c:__ia32_sys_flistxattr",
        "fs/xattr.c:__x64_sys_flistxattr",
        "fs/xattr.c:__ia32_sys_fgetxattr",
        "fs/xattr.c:__x64_sys_fgetxattr",
        "fs/xattr.c:__ia32_sys_fsetxattr",
        "fs/xattr.c:__x64_sys_fsetxattr",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:do_mq_timedsend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580252544,
      "name": "__audit_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void __audit_file(const struct file * file)
```

```json
{
  "name": "__audit_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580305792,
      "name": "__audit_file",
      "external": true,
      "loc": "kernel/auditsc.c:1838",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:ksys_fchown",
        "fs/open.c:ksys_fchmod",
        "fs/xattr.c:__ia32_sys_fremovexattr",
        "fs/xattr.c:__x64_sys_fremovexattr",
        "fs/xattr.c:__ia32_sys_flistxattr",
        "fs/xattr.c:__x64_sys_flistxattr",
        "fs/xattr.c:__ia32_sys_fgetxattr",
        "fs/xattr.c:__x64_sys_fgetxattr",
        "fs/xattr.c:__ia32_sys_fsetxattr",
        "fs/xattr.c:__x64_sys_fsetxattr",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:do_mq_timedsend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580305792,
      "name": "__audit_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void __audit_file(const struct file * file)
```

```json
{
  "name": "__audit_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580358240,
      "name": "__audit_file",
      "external": true,
      "loc": "kernel/auditsc.c:2042",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:ksys_fchown",
        "fs/open.c:ksys_fchmod",
        "fs/xattr.c:__ia32_sys_fremovexattr",
        "fs/xattr.c:__x64_sys_fremovexattr",
        "fs/xattr.c:__ia32_sys_flistxattr",
        "fs/xattr.c:__x64_sys_flistxattr",
        "fs/xattr.c:__ia32_sys_fgetxattr",
        "fs/xattr.c:__x64_sys_fgetxattr",
        "fs/xattr.c:__ia32_sys_fsetxattr",
        "fs/xattr.c:__x64_sys_fsetxattr",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:do_mq_timedsend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580358240,
      "name": "__audit_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void __audit_file(const struct file * file)
```

```json
{
  "name": "__audit_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580407008,
      "name": "__audit_file",
      "external": true,
      "loc": "kernel/auditsc.c:2042",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:ksys_fchown",
        "fs/open.c:ksys_fchmod",
        "fs/xattr.c:__ia32_sys_fremovexattr",
        "fs/xattr.c:__x64_sys_fremovexattr",
        "fs/xattr.c:__ia32_sys_flistxattr",
        "fs/xattr.c:__x64_sys_flistxattr",
        "fs/xattr.c:__ia32_sys_fgetxattr",
        "fs/xattr.c:__x64_sys_fgetxattr",
        "fs/xattr.c:__ia32_sys_fsetxattr",
        "fs/xattr.c:__x64_sys_fsetxattr",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:do_mq_timedsend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580407008,
      "name": "__audit_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void __audit_file(const struct file * file)
```

```json
{
  "name": "__audit_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580485424,
      "name": "__audit_file",
      "external": true,
      "loc": "kernel/auditsc.c:2073",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:ksys_fchown",
        "fs/open.c:ksys_fchmod",
        "fs/xattr.c:__ia32_sys_fremovexattr",
        "fs/xattr.c:__x64_sys_fremovexattr",
        "fs/xattr.c:__ia32_sys_flistxattr",
        "fs/xattr.c:__x64_sys_flistxattr",
        "fs/xattr.c:__ia32_sys_fgetxattr",
        "fs/xattr.c:__x64_sys_fgetxattr",
        "fs/xattr.c:__ia32_sys_fsetxattr",
        "fs/xattr.c:__x64_sys_fsetxattr",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:do_mq_timedsend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580485424,
      "name": "__audit_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void __audit_file(const struct file * file)
```

```json
{
  "name": "__audit_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580473680,
      "name": "__audit_file",
      "external": true,
      "loc": "kernel/auditsc.c:2090",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:ksys_fchown",
        "fs/open.c:__ia32_sys_fchmod",
        "fs/open.c:__x64_sys_fchmod",
        "fs/xattr.c:__ia32_sys_fremovexattr",
        "fs/xattr.c:__x64_sys_fremovexattr",
        "fs/xattr.c:__ia32_sys_flistxattr",
        "fs/xattr.c:__x64_sys_flistxattr",
        "fs/xattr.c:__ia32_sys_fgetxattr",
        "fs/xattr.c:__x64_sys_fgetxattr",
        "fs/xattr.c:__ia32_sys_fsetxattr",
        "fs/xattr.c:__x64_sys_fsetxattr",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:do_mq_timedsend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580473680,
      "name": "__audit_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void __audit_file(const struct file * file)
```

```json
{
  "name": "__audit_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580477632,
      "name": "__audit_file",
      "external": true,
      "loc": "kernel/auditsc.c:2087",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:ksys_fchown",
        "fs/open.c:__ia32_sys_fchmod",
        "fs/open.c:__x64_sys_fchmod",
        "fs/xattr.c:__ia32_sys_fremovexattr",
        "fs/xattr.c:__x64_sys_fremovexattr",
        "fs/xattr.c:__ia32_sys_flistxattr",
        "fs/xattr.c:__x64_sys_flistxattr",
        "fs/xattr.c:__ia32_sys_fgetxattr",
        "fs/xattr.c:__x64_sys_fgetxattr",
        "fs/xattr.c:__ia32_sys_fsetxattr",
        "fs/xattr.c:__x64_sys_fsetxattr",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:do_mq_timedsend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580477632,
      "name": "__audit_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void __audit_file(const struct file * file)
```

```json
{
  "name": "__audit_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580645072,
      "name": "__audit_file",
      "external": true,
      "loc": "kernel/auditsc.c:2100",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:ksys_fchown",
        "fs/open.c:__ia32_sys_fchmod",
        "fs/open.c:__x64_sys_fchmod",
        "fs/xattr.c:__ia32_sys_fremovexattr",
        "fs/xattr.c:__x64_sys_fremovexattr",
        "fs/xattr.c:__ia32_sys_flistxattr",
        "fs/xattr.c:__x64_sys_flistxattr",
        "fs/xattr.c:__ia32_sys_fgetxattr",
        "fs/xattr.c:__x64_sys_fgetxattr",
        "fs/xattr.c:__ia32_sys_fsetxattr",
        "fs/xattr.c:__x64_sys_fsetxattr",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:do_mq_timedsend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580645072,
      "name": "__audit_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void __audit_file(const struct file * file)
```

```json
{
  "name": "__audit_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580853424,
      "name": "__audit_file",
      "external": true,
      "loc": "kernel/auditsc.c:2391",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:ksys_fchown",
        "fs/open.c:__ia32_sys_fchmod",
        "fs/open.c:__x64_sys_fchmod",
        "fs/xattr.c:__ia32_sys_fremovexattr",
        "fs/xattr.c:__x64_sys_fremovexattr",
        "fs/xattr.c:__ia32_sys_flistxattr",
        "fs/xattr.c:__x64_sys_flistxattr",
        "fs/xattr.c:__ia32_sys_fgetxattr",
        "fs/xattr.c:__x64_sys_fgetxattr",
        "fs/xattr.c:__ia32_sys_fsetxattr",
        "fs/xattr.c:__x64_sys_fsetxattr",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:do_mq_timedsend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580853424,
      "name": "__audit_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void __audit_file(const struct file * file)
```

```json
{
  "name": "__audit_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581140688,
      "name": "__audit_file",
      "external": true,
      "loc": "kernel/auditsc.c:2369",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:ksys_fchown",
        "fs/open.c:__ia32_sys_fchmod",
        "fs/open.c:__x64_sys_fchmod",
        "fs/xattr.c:__ia32_sys_fremovexattr",
        "fs/xattr.c:__x64_sys_fremovexattr",
        "fs/xattr.c:__ia32_sys_flistxattr",
        "fs/xattr.c:__x64_sys_flistxattr",
        "fs/xattr.c:__ia32_sys_fgetxattr",
        "fs/xattr.c:__x64_sys_fgetxattr",
        "fs/xattr.c:__ia32_sys_fsetxattr",
        "fs/xattr.c:__x64_sys_fsetxattr",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:do_mq_timedsend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581140688,
      "name": "__audit_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void __audit_file(const struct file * file)
```

```json
{
  "name": "__audit_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581233728,
      "name": "__audit_file",
      "external": true,
      "loc": "kernel/auditsc.c:2366",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:ksys_fchown",
        "fs/open.c:__ia32_sys_fchmod",
        "fs/open.c:__x64_sys_fchmod",
        "fs/xattr.c:__ia32_sys_fremovexattr",
        "fs/xattr.c:__x64_sys_fremovexattr",
        "fs/xattr.c:__ia32_sys_flistxattr",
        "fs/xattr.c:__x64_sys_flistxattr",
        "fs/xattr.c:__ia32_sys_fgetxattr",
        "fs/xattr.c:__x64_sys_fgetxattr",
        "fs/xattr.c:__ia32_sys_fsetxattr",
        "fs/xattr.c:__x64_sys_fsetxattr",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:do_mq_timedsend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581233728,
      "name": "__audit_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void __audit_file(const struct file * file)
```

```json
{
  "name": "__audit_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581339824,
      "name": "__audit_file",
      "external": true,
      "loc": "kernel/auditsc.c:2361",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:ksys_fchown",
        "fs/open.c:__ia32_sys_fchmod",
        "fs/open.c:__x64_sys_fchmod",
        "fs/xattr.c:__ia32_sys_fremovexattr",
        "fs/xattr.c:__x64_sys_fremovexattr",
        "fs/xattr.c:__ia32_sys_flistxattr",
        "fs/xattr.c:__x64_sys_flistxattr",
        "fs/xattr.c:__ia32_sys_fgetxattr",
        "fs/xattr.c:__x64_sys_fgetxattr",
        "fs/xattr.c:__ia32_sys_fsetxattr",
        "fs/xattr.c:__x64_sys_fsetxattr",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:do_mq_timedsend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581339824,
      "name": "__audit_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void __audit_file(const struct file * file)
```

```json
{
  "name": "__audit_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491672496,
      "name": "__audit_file",
      "external": true,
      "loc": "kernel/auditsc.c:2042",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:ksys_fchown",
        "fs/open.c:ksys_fchmod",
        "fs/xattr.c:__arm64_sys_fremovexattr",
        "fs/xattr.c:__arm64_sys_flistxattr",
        "fs/xattr.c:__arm64_sys_fgetxattr",
        "fs/xattr.c:__arm64_sys_fsetxattr",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:do_mq_timedsend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491672496,
      "name": "__audit_file",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void __audit_file(const struct file * file)
```

```json
{
  "name": "__audit_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225626844,
      "name": "__audit_file",
      "external": true,
      "loc": "kernel/auditsc.c:2042",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:ksys_fchown",
        "fs/open.c:ksys_fchmod",
        "fs/xattr.c:__se_sys_fremovexattr",
        "fs/xattr.c:__se_sys_flistxattr",
        "fs/xattr.c:__se_sys_fgetxattr",
        "fs/xattr.c:__se_sys_fsetxattr",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:do_mq_timedsend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225626844,
      "name": "__audit_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void __audit_file(const struct file * file)
```

```json
{
  "name": "__audit_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284681584,
      "name": "__audit_file",
      "external": true,
      "loc": "kernel/auditsc.c:2042",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:ksys_fchown",
        "fs/open.c:ksys_fchmod",
        "fs/xattr.c:__se_sys_fremovexattr",
        "fs/xattr.c:__se_sys_flistxattr",
        "fs/xattr.c:__se_sys_fgetxattr",
        "fs/xattr.c:__se_sys_fsetxattr",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:do_mq_timedsend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284681584,
      "name": "__audit_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void __audit_file(const struct file * file)
```

```json
{
  "name": "__audit_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272063174,
      "name": "__audit_file",
      "external": true,
      "loc": "kernel/auditsc.c:2042",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:ksys_fchown",
        "fs/open.c:ksys_fchmod",
        "fs/xattr.c:__se_sys_fremovexattr",
        "fs/xattr.c:__se_sys_flistxattr",
        "fs/xattr.c:__se_sys_fgetxattr",
        "fs/xattr.c:__se_sys_fsetxattr",
        "ipc/mqueue.c:__se_sys_mq_timedreceive",
        "ipc/mqueue.c:__se_sys_mq_timedsend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272063174,
      "name": "__audit_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void __audit_file(const struct file * file)
```

```json
{
  "name": "__audit_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580375808,
      "name": "__audit_file",
      "external": true,
      "loc": "kernel/auditsc.c:2042",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:ksys_fchown",
        "fs/open.c:ksys_fchmod",
        "fs/xattr.c:__ia32_sys_fremovexattr",
        "fs/xattr.c:__x64_sys_fremovexattr",
        "fs/xattr.c:__ia32_sys_flistxattr",
        "fs/xattr.c:__x64_sys_flistxattr",
        "fs/xattr.c:__ia32_sys_fgetxattr",
        "fs/xattr.c:__x64_sys_fgetxattr",
        "fs/xattr.c:__ia32_sys_fsetxattr",
        "fs/xattr.c:__x64_sys_fsetxattr",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:do_mq_timedsend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580375808,
      "name": "__audit_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void __audit_file(const struct file * file)
```

```json
{
  "name": "__audit_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580322976,
      "name": "__audit_file",
      "external": true,
      "loc": "kernel/auditsc.c:2042",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:ksys_fchown",
        "fs/open.c:ksys_fchmod",
        "fs/xattr.c:__ia32_sys_fremovexattr",
        "fs/xattr.c:__x64_sys_fremovexattr",
        "fs/xattr.c:__ia32_sys_flistxattr",
        "fs/xattr.c:__x64_sys_flistxattr",
        "fs/xattr.c:__ia32_sys_fgetxattr",
        "fs/xattr.c:__x64_sys_fgetxattr",
        "fs/xattr.c:__ia32_sys_fsetxattr",
        "fs/xattr.c:__x64_sys_fsetxattr",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:do_mq_timedsend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580322976,
      "name": "__audit_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void __audit_file(const struct file * file)
```

```json
{
  "name": "__audit_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580367056,
      "name": "__audit_file",
      "external": true,
      "loc": "kernel/auditsc.c:2042",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:ksys_fchown",
        "fs/open.c:ksys_fchmod",
        "fs/xattr.c:__ia32_sys_fremovexattr",
        "fs/xattr.c:__x64_sys_fremovexattr",
        "fs/xattr.c:__ia32_sys_flistxattr",
        "fs/xattr.c:__x64_sys_flistxattr",
        "fs/xattr.c:__ia32_sys_fgetxattr",
        "fs/xattr.c:__x64_sys_fgetxattr",
        "fs/xattr.c:__ia32_sys_fsetxattr",
        "fs/xattr.c:__x64_sys_fsetxattr",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:do_mq_timedsend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580367056,
      "name": "__audit_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void __audit_file(const struct file * file)
```

```json
{
  "name": "__audit_file",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580422544,
      "name": "__audit_file",
      "external": true,
      "loc": "kernel/auditsc.c:2042",
      "file": "kernel/auditsc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/open.c:ksys_fchown",
        "fs/open.c:ksys_fchmod",
        "fs/xattr.c:__ia32_sys_fremovexattr",
        "fs/xattr.c:__x64_sys_fremovexattr",
        "fs/xattr.c:__ia32_sys_flistxattr",
        "fs/xattr.c:__x64_sys_flistxattr",
        "fs/xattr.c:__ia32_sys_fgetxattr",
        "fs/xattr.c:__x64_sys_fgetxattr",
        "fs/xattr.c:__ia32_sys_fsetxattr",
        "fs/xattr.c:__x64_sys_fsetxattr",
        "ipc/mqueue.c:do_mq_timedreceive",
        "ipc/mqueue.c:do_mq_timedsend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580422544,
      "name": "__audit_file",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
