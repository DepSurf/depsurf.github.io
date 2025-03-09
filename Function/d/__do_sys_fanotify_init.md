# Function: <code>__do_sys_fanotify_init</code>

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
  "name": "__do_sys_fanotify_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581899066,
      "name": "__do_sys_fanotify_init",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify_user.c:706",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_init",
        "fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_init"
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
  "name": "__do_sys_fanotify_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581983918,
      "name": "__do_sys_fanotify_init",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify_user.c:686",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_init",
        "fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_init"
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
  "name": "__do_sys_fanotify_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582119486,
      "name": "__do_sys_fanotify_init",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify_user.c:758",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_init",
        "fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_init"
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
  "name": "__do_sys_fanotify_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582196718,
      "name": "__do_sys_fanotify_init",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify_user.c:766",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_init",
        "fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_init"
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
long int __do_sys_fanotify_init(unsigned int flags, unsigned int event_f_flags)
```

```json
{
  "name": "__do_sys_fanotify_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582429360,
      "name": "__do_sys_fanotify_init",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify_user.c:835",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_init",
        "fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582429360,
      "name": "__do_sys_fanotify_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 800
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
long int __do_sys_fanotify_init(unsigned int flags, unsigned int event_f_flags)
```

```json
{
  "name": "__do_sys_fanotify_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582484800,
      "name": "__do_sys_fanotify_init",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify_user.c:923",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_init",
        "fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582484800,
      "name": "__do_sys_fanotify_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 906
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
long int __do_sys_fanotify_init(unsigned int flags, unsigned int event_f_flags)
```

```json
{
  "name": "__do_sys_fanotify_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582512064,
      "name": "__do_sys_fanotify_init",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify_user.c:1044",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_init",
        "fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582512064,
      "name": "__do_sys_fanotify_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 852
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
long int __do_sys_fanotify_init(unsigned int flags, unsigned int event_f_flags)
```

```json
{
  "name": "__do_sys_fanotify_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582827376,
      "name": "__do_sys_fanotify_init",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify_user.c:1144",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_init",
        "fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582827376,
      "name": "__do_sys_fanotify_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 867
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
long int __do_sys_fanotify_init(unsigned int flags, unsigned int event_f_flags)
```

```json
{
  "name": "__do_sys_fanotify_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583386400,
      "name": "__do_sys_fanotify_init",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify_user.c:1305",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_init",
        "fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583386400,
      "name": "__do_sys_fanotify_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 910
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
long int __do_sys_fanotify_init(unsigned int flags, unsigned int event_f_flags)
```

```json
{
  "name": "__do_sys_fanotify_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583971904,
      "name": "__do_sys_fanotify_init",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify_user.c:1344",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_init",
        "fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583971904,
      "name": "__do_sys_fanotify_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 904
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
long int __do_sys_fanotify_init(unsigned int flags, unsigned int event_f_flags)
```

```json
{
  "name": "__do_sys_fanotify_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584195424,
      "name": "__do_sys_fanotify_init",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify_user.c:1393",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_init",
        "fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584195424,
      "name": "__do_sys_fanotify_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 938
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
long int __do_sys_fanotify_init(unsigned int flags, unsigned int event_f_flags)
```

```json
{
  "name": "__do_sys_fanotify_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584409392,
      "name": "__do_sys_fanotify_init",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify_user.c:1460",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_init",
        "fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584409392,
      "name": "__do_sys_fanotify_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 938
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
  "name": "__do_sys_fanotify_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336493751860,
      "name": "__do_sys_fanotify_init",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify_user.c:766",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/fanotify/fanotify_user.c:__arm64_sys_fanotify_init"
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
  "name": "__do_sys_fanotify_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3227276896,
      "name": "__do_sys_fanotify_init",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify_user.c:766",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_init"
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
  "name": "__do_sys_fanotify_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055287363316,
      "name": "__do_sys_fanotify_init",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify_user.c:766",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_init"
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
  "name": "__do_sys_fanotify_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273360426,
      "name": "__do_sys_fanotify_init",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify_user.c:766",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_init"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__do_sys_fanotify_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582165454,
      "name": "__do_sys_fanotify_init",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify_user.c:766",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_init",
        "fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_init"
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
  "name": "__do_sys_fanotify_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582102894,
      "name": "__do_sys_fanotify_init",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify_user.c:766",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_init",
        "fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_init"
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
  "name": "__do_sys_fanotify_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582155934,
      "name": "__do_sys_fanotify_init",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify_user.c:766",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_init",
        "fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_init"
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
  "name": "__do_sys_fanotify_init",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582229182,
      "name": "__do_sys_fanotify_init",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify_user.c:766",
      "file": "fs/notify/fanotify/fanotify_user.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_init",
        "fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_init"
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
long int __do_sys_fanotify_init(unsigned int flags, unsigned int event_f_flags)
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
