# Function: <code>pidfd_create</code>

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
int pidfd_create(struct pid * pid)
```

```json
{
  "name": "pidfd_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579629792,
      "name": "pidfd_create",
      "external": false,
      "loc": "kernel/pid.c:470",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid.c:__ia32_sys_pidfd_open",
        "kernel/pid.c:__x64_sys_pidfd_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579629792,
      "name": "pidfd_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
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
int pidfd_create(struct pid * pid)
```

```json
{
  "name": "pidfd_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579655344,
      "name": "pidfd_create",
      "external": false,
      "loc": "kernel/pid.c:470",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid.c:__ia32_sys_pidfd_open",
        "kernel/pid.c:__x64_sys_pidfd_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579655344,
      "name": "pidfd_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
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
  "name": "pidfd_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579686728,
      "name": "pidfd_create",
      "external": false,
      "loc": "kernel/pid.c:535",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:__ia32_sys_pidfd_open",
        "kernel/pid.c:__x64_sys_pidfd_open"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int pidfd_create(struct pid * pid, unsigned int flags)
```

```json
{
  "name": "pidfd_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579664656,
      "name": "pidfd_create",
      "external": false,
      "loc": "kernel/pid.c:556",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid.c:__ia32_sys_pidfd_open",
        "kernel/pid.c:__x64_sys_pidfd_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579664656,
      "name": "pidfd_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
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
int pidfd_create(struct pid * pid, unsigned int flags)
```

```json
{
  "name": "pidfd_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579671472,
      "name": "pidfd_create",
      "external": false,
      "loc": "kernel/pid.c:556",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid.c:__ia32_sys_pidfd_open",
        "kernel/pid.c:__x64_sys_pidfd_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579671472,
      "name": "pidfd_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
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
int pidfd_create(struct pid * pid, unsigned int flags)
```

```json
{
  "name": "pidfd_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579752832,
      "name": "pidfd_create",
      "external": true,
      "loc": "kernel/pid.c:558",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid.c:__ia32_sys_pidfd_open",
        "kernel/pid.c:__x64_sys_pidfd_open",
        "fs/notify/fanotify/fanotify_user.c:copy_event_to_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579752832,
      "name": "pidfd_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 175
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
int pidfd_create(struct pid * pid, unsigned int flags)
```

```json
{
  "name": "pidfd_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579857984,
      "name": "pidfd_create",
      "external": true,
      "loc": "kernel/pid.c:594",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid.c:__ia32_sys_pidfd_open",
        "kernel/pid.c:__x64_sys_pidfd_open",
        "fs/notify/fanotify/fanotify_user.c:copy_event_to_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579857984,
      "name": "pidfd_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
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
int pidfd_create(struct pid * pid, unsigned int flags)
```

```json
{
  "name": "pidfd_create",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579999152,
      "name": "pidfd_create",
      "external": true,
      "loc": "kernel/pid.c:595",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid.c:__ia32_sys_pidfd_open",
        "kernel/pid.c:__x64_sys_pidfd_open",
        "fs/notify/fanotify/fanotify_user.c:copy_event_to_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579999152,
      "name": "pidfd_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
int pidfd_create(struct pid * pid, unsigned int flags)
```

```json
{
  "name": "pidfd_create",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580048940,
      "name": "pidfd_create",
      "external": true,
      "loc": "kernel/pid.c:598",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:__ia32_sys_pidfd_open",
        "kernel/pid.c:__x64_sys_pidfd_open"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580053648,
      "name": "pidfd_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
int pidfd_create(struct pid * pid, unsigned int flags)
```

```json
{
  "name": "pidfd_create",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580091436,
      "name": "pidfd_create",
      "external": true,
      "loc": "kernel/pid.c:598",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:__ia32_sys_pidfd_open",
        "kernel/pid.c:__x64_sys_pidfd_open"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580096112,
      "name": "pidfd_create",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
  "name": "pidfd_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336490828684,
      "name": "pidfd_create",
      "external": false,
      "loc": "kernel/pid.c:470",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:__arm64_sys_pidfd_open"
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
  "name": "pidfd_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3224862008,
      "name": "pidfd_create",
      "external": false,
      "loc": "kernel/pid.c:470",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:__se_sys_pidfd_open"
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
  "name": "pidfd_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055283662792,
      "name": "pidfd_create",
      "external": false,
      "loc": "kernel/pid.c:470",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:__se_sys_pidfd_open"
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
  "name": "pidfd_create",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271502618,
      "name": "pidfd_create",
      "external": false,
      "loc": "kernel/pid.c:470",
      "file": "kernel/pid.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/pid.c:__se_sys_pidfd_open"
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
int pidfd_create(struct pid * pid)
```

```json
{
  "name": "pidfd_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579631664,
      "name": "pidfd_create",
      "external": false,
      "loc": "kernel/pid.c:470",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid.c:__ia32_sys_pidfd_open",
        "kernel/pid.c:__x64_sys_pidfd_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579631664,
      "name": "pidfd_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
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
int pidfd_create(struct pid * pid)
```

```json
{
  "name": "pidfd_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579560000,
      "name": "pidfd_create",
      "external": false,
      "loc": "kernel/pid.c:470",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid.c:__ia32_sys_pidfd_open",
        "kernel/pid.c:__x64_sys_pidfd_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579560000,
      "name": "pidfd_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
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
int pidfd_create(struct pid * pid)
```

```json
{
  "name": "pidfd_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579628928,
      "name": "pidfd_create",
      "external": false,
      "loc": "kernel/pid.c:470",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid.c:__ia32_sys_pidfd_open",
        "kernel/pid.c:__x64_sys_pidfd_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579628928,
      "name": "pidfd_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
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
int pidfd_create(struct pid * pid)
```

```json
{
  "name": "pidfd_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579662704,
      "name": "pidfd_create",
      "external": false,
      "loc": "kernel/pid.c:470",
      "file": "kernel/pid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/pid.c:__ia32_sys_pidfd_open",
        "kernel/pid.c:__x64_sys_pidfd_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579662704,
      "name": "pidfd_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
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
int pidfd_create(struct pid * pid)
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int pidfd_create(struct pid * pid)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
int pidfd_create(struct pid * pid, unsigned int flags)
```
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int pidfd_create(struct pid * pid)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int pidfd_create(struct pid * pid)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int pidfd_create(struct pid * pid)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int pidfd_create(struct pid * pid)
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
