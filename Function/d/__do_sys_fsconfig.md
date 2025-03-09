# Function: <code>__do_sys_fsconfig</code>

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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__do_sys_fsconfig",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582038225,
      "name": "__do_sys_fsconfig",
      "external": false,
      "loc": "fs/fsopen.c:314",
      "file": "fs/fsopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fsopen.c:__ia32_sys_fsconfig",
        "fs/fsopen.c:__x64_sys_fsconfig"
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
  "name": "__do_sys_fsconfig",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582116065,
      "name": "__do_sys_fsconfig",
      "external": false,
      "loc": "fs/fsopen.c:314",
      "file": "fs/fsopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fsopen.c:__ia32_sys_fsconfig",
        "fs/fsopen.c:__x64_sys_fsconfig"
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
long int __do_sys_fsconfig(int fd, unsigned int cmd, const char * _key, const void * _value, int aux)
```

```json
{
  "name": "__do_sys_fsconfig",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582353104,
      "name": "__do_sys_fsconfig",
      "external": false,
      "loc": "fs/fsopen.c:314",
      "file": "fs/fsopen.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fsopen.c:__ia32_sys_fsconfig",
        "fs/fsopen.c:__x64_sys_fsconfig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582353104,
      "name": "__do_sys_fsconfig",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1450
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
long int __do_sys_fsconfig(int fd, unsigned int cmd, const char * _key, const void * _value, int aux)
```

```json
{
  "name": "__do_sys_fsconfig",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582404688,
      "name": "__do_sys_fsconfig",
      "external": false,
      "loc": "fs/fsopen.c:314",
      "file": "fs/fsopen.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fsopen.c:__ia32_sys_fsconfig",
        "fs/fsopen.c:__x64_sys_fsconfig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582404688,
      "name": "__do_sys_fsconfig",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1450
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
long int __do_sys_fsconfig(int fd, unsigned int cmd, const char * _key, const void * _value, int aux)
```

```json
{
  "name": "__do_sys_fsconfig",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582431904,
      "name": "__do_sys_fsconfig",
      "external": false,
      "loc": "fs/fsopen.c:314",
      "file": "fs/fsopen.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fsopen.c:__ia32_sys_fsconfig",
        "fs/fsopen.c:__x64_sys_fsconfig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582431904,
      "name": "__do_sys_fsconfig",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1447
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
long int __do_sys_fsconfig(int fd, unsigned int cmd, const char * _key, const void * _value, int aux)
```

```json
{
  "name": "__do_sys_fsconfig",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582754672,
      "name": "__do_sys_fsconfig",
      "external": false,
      "loc": "fs/fsopen.c:314",
      "file": "fs/fsopen.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fsopen.c:__ia32_sys_fsconfig",
        "fs/fsopen.c:__x64_sys_fsconfig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582754672,
      "name": "__do_sys_fsconfig",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1447
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
long int __do_sys_fsconfig(int fd, unsigned int cmd, const char * _key, const void * _value, int aux)
```

```json
{
  "name": "__do_sys_fsconfig",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583302816,
      "name": "__do_sys_fsconfig",
      "external": false,
      "loc": "fs/fsopen.c:314",
      "file": "fs/fsopen.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fsopen.c:__ia32_sys_fsconfig",
        "fs/fsopen.c:__x64_sys_fsconfig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583302816,
      "name": "__do_sys_fsconfig",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1590
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
long int __do_sys_fsconfig(int fd, unsigned int cmd, const char * _key, const void * _value, int aux)
```

```json
{
  "name": "__do_sys_fsconfig",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583888240,
      "name": "__do_sys_fsconfig",
      "external": false,
      "loc": "fs/fsopen.c:314",
      "file": "fs/fsopen.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fsopen.c:__ia32_sys_fsconfig",
        "fs/fsopen.c:__x64_sys_fsconfig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583888240,
      "name": "__do_sys_fsconfig",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1590
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
long int __do_sys_fsconfig(int fd, unsigned int cmd, const char * _key, const void * _value, int aux)
```

```json
{
  "name": "__do_sys_fsconfig",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584110048,
      "name": "__do_sys_fsconfig",
      "external": false,
      "loc": "fs/fsopen.c:314",
      "file": "fs/fsopen.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fsopen.c:__ia32_sys_fsconfig",
        "fs/fsopen.c:__x64_sys_fsconfig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584110048,
      "name": "__do_sys_fsconfig",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1673
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
long int __do_sys_fsconfig(int fd, unsigned int cmd, const char * _key, const void * _value, int aux)
```

```json
{
  "name": "__do_sys_fsconfig",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584326576,
      "name": "__do_sys_fsconfig",
      "external": false,
      "loc": "fs/fsopen.c:349",
      "file": "fs/fsopen.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/fsopen.c:__ia32_sys_fsconfig",
        "fs/fsopen.c:__x64_sys_fsconfig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584326576,
      "name": "__do_sys_fsconfig",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1568
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
  "name": "__do_sys_fsconfig",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336493656808,
      "name": "__do_sys_fsconfig",
      "external": false,
      "loc": "fs/fsopen.c:314",
      "file": "fs/fsopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fsopen.c:__arm64_sys_fsconfig"
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
  "name": "__do_sys_fsconfig",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3227192048,
      "name": "__do_sys_fsconfig",
      "external": false,
      "loc": "fs/fsopen.c:314",
      "file": "fs/fsopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fsopen.c:__se_sys_fsconfig"
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
  "name": "__do_sys_fsconfig",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055287254712,
      "name": "__do_sys_fsconfig",
      "external": false,
      "loc": "fs/fsopen.c:314",
      "file": "fs/fsopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fsopen.c:__se_sys_fsconfig"
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
  "name": "__do_sys_fsconfig",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273287706,
      "name": "__do_sys_fsconfig",
      "external": false,
      "loc": "fs/fsopen.c:314",
      "file": "fs/fsopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fsopen.c:__se_sys_fsconfig"
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
  "name": "__do_sys_fsconfig",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582084801,
      "name": "__do_sys_fsconfig",
      "external": false,
      "loc": "fs/fsopen.c:314",
      "file": "fs/fsopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fsopen.c:__ia32_sys_fsconfig",
        "fs/fsopen.c:__x64_sys_fsconfig"
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
  "name": "__do_sys_fsconfig",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582022321,
      "name": "__do_sys_fsconfig",
      "external": false,
      "loc": "fs/fsopen.c:314",
      "file": "fs/fsopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fsopen.c:__ia32_sys_fsconfig",
        "fs/fsopen.c:__x64_sys_fsconfig"
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
  "name": "__do_sys_fsconfig",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582075281,
      "name": "__do_sys_fsconfig",
      "external": false,
      "loc": "fs/fsopen.c:314",
      "file": "fs/fsopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fsopen.c:__ia32_sys_fsconfig",
        "fs/fsopen.c:__x64_sys_fsconfig"
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
  "name": "__do_sys_fsconfig",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582147841,
      "name": "__do_sys_fsconfig",
      "external": false,
      "loc": "fs/fsopen.c:314",
      "file": "fs/fsopen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fsopen.c:__ia32_sys_fsconfig",
        "fs/fsopen.c:__x64_sys_fsconfig"
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
long int __do_sys_fsconfig(int fd, unsigned int cmd, const char * _key, const void * _value, int aux)
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
