# Function: <code>do_mq_getsetattr</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int do_mq_getsetattr(int mqdes, struct mq_attr * new, struct mq_attr * old)
```

```json
{
  "name": "do_mq_getsetattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582560704,
      "name": "do_mq_getsetattr",
      "external": false,
      "loc": "ipc/mqueue.c:1354",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:C_SYSC_mq_getsetattr",
        "ipc/mqueue.c:C_SYSC_mq_getsetattr",
        "ipc/mqueue.c:SYSC_mq_getsetattr",
        "ipc/mqueue.c:SYSC_mq_getsetattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582560704,
      "name": "do_mq_getsetattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 414
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
int do_mq_getsetattr(int mqdes, struct mq_attr * new, struct mq_attr * old)
```

```json
{
  "name": "do_mq_getsetattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582713168,
      "name": "do_mq_getsetattr",
      "external": false,
      "loc": "ipc/mqueue.c:1354",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:C_SYSC_mq_getsetattr",
        "ipc/mqueue.c:C_SYSC_mq_getsetattr",
        "ipc/mqueue.c:SYSC_mq_getsetattr",
        "ipc/mqueue.c:SYSC_mq_getsetattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582713168,
      "name": "do_mq_getsetattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 414
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
int do_mq_getsetattr(int mqdes, struct mq_attr * new, struct mq_attr * old)
```

```json
{
  "name": "do_mq_getsetattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582913056,
      "name": "do_mq_getsetattr",
      "external": false,
      "loc": "ipc/mqueue.c:1300",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:__do_compat_sys_mq_getsetattr",
        "ipc/mqueue.c:__do_compat_sys_mq_getsetattr",
        "ipc/mqueue.c:__do_sys_mq_getsetattr",
        "ipc/mqueue.c:__do_sys_mq_getsetattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582913056,
      "name": "do_mq_getsetattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 404
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
int do_mq_getsetattr(int mqdes, struct mq_attr * new, struct mq_attr * old)
```

```json
{
  "name": "do_mq_getsetattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583022592,
      "name": "do_mq_getsetattr",
      "external": false,
      "loc": "ipc/mqueue.c:1300",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:__do_compat_sys_mq_getsetattr",
        "ipc/mqueue.c:__do_compat_sys_mq_getsetattr",
        "ipc/mqueue.c:__do_sys_mq_getsetattr",
        "ipc/mqueue.c:__do_sys_mq_getsetattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583022592,
      "name": "do_mq_getsetattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 404
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
int do_mq_getsetattr(int mqdes, struct mq_attr * new, struct mq_attr * old)
```

```json
{
  "name": "do_mq_getsetattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583203520,
      "name": "do_mq_getsetattr",
      "external": false,
      "loc": "ipc/mqueue.c:1355",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:__do_compat_sys_mq_getsetattr",
        "ipc/mqueue.c:__do_compat_sys_mq_getsetattr",
        "ipc/mqueue.c:__do_sys_mq_getsetattr",
        "ipc/mqueue.c:__do_sys_mq_getsetattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583203520,
      "name": "do_mq_getsetattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 430
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
int do_mq_getsetattr(int mqdes, struct mq_attr * new, struct mq_attr * old)
```

```json
{
  "name": "do_mq_getsetattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583309296,
      "name": "do_mq_getsetattr",
      "external": false,
      "loc": "ipc/mqueue.c:1350",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:__do_compat_sys_mq_getsetattr",
        "ipc/mqueue.c:__do_compat_sys_mq_getsetattr",
        "ipc/mqueue.c:__do_sys_mq_getsetattr",
        "ipc/mqueue.c:__do_sys_mq_getsetattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583309296,
      "name": "do_mq_getsetattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 430
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
int do_mq_getsetattr(int mqdes, struct mq_attr * new, struct mq_attr * old)
```

```json
{
  "name": "do_mq_getsetattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583640016,
      "name": "do_mq_getsetattr",
      "external": false,
      "loc": "ipc/mqueue.c:1436",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:__do_compat_sys_mq_getsetattr",
        "ipc/mqueue.c:__do_compat_sys_mq_getsetattr",
        "ipc/mqueue.c:__do_sys_mq_getsetattr",
        "ipc/mqueue.c:__do_sys_mq_getsetattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583640016,
      "name": "do_mq_getsetattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 430
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
int do_mq_getsetattr(int mqdes, struct mq_attr * new, struct mq_attr * old)
```

```json
{
  "name": "do_mq_getsetattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583761104,
      "name": "do_mq_getsetattr",
      "external": false,
      "loc": "ipc/mqueue.c:1436",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:__do_compat_sys_mq_getsetattr",
        "ipc/mqueue.c:__do_compat_sys_mq_getsetattr",
        "ipc/mqueue.c:__do_sys_mq_getsetattr",
        "ipc/mqueue.c:__do_sys_mq_getsetattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583761104,
      "name": "do_mq_getsetattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 430
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
int do_mq_getsetattr(int mqdes, struct mq_attr * new, struct mq_attr * old)
```

```json
{
  "name": "do_mq_getsetattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583785248,
      "name": "do_mq_getsetattr",
      "external": false,
      "loc": "ipc/mqueue.c:1439",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:__do_compat_sys_mq_getsetattr",
        "ipc/mqueue.c:__do_compat_sys_mq_getsetattr",
        "ipc/mqueue.c:__do_sys_mq_getsetattr",
        "ipc/mqueue.c:__do_sys_mq_getsetattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583785248,
      "name": "do_mq_getsetattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 430
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
int do_mq_getsetattr(int mqdes, struct mq_attr * new, struct mq_attr * old)
```

```json
{
  "name": "do_mq_getsetattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584148064,
      "name": "do_mq_getsetattr",
      "external": false,
      "loc": "ipc/mqueue.c:1441",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:__do_compat_sys_mq_getsetattr",
        "ipc/mqueue.c:__do_compat_sys_mq_getsetattr",
        "ipc/mqueue.c:__do_sys_mq_getsetattr",
        "ipc/mqueue.c:__do_sys_mq_getsetattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584148064,
      "name": "do_mq_getsetattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 430
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
int do_mq_getsetattr(int mqdes, struct mq_attr * new, struct mq_attr * old)
```

```json
{
  "name": "do_mq_getsetattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584743008,
      "name": "do_mq_getsetattr",
      "external": false,
      "loc": "ipc/mqueue.c:1453",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:__do_compat_sys_mq_getsetattr",
        "ipc/mqueue.c:__do_compat_sys_mq_getsetattr",
        "ipc/mqueue.c:__do_sys_mq_getsetattr",
        "ipc/mqueue.c:__do_sys_mq_getsetattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584743008,
      "name": "do_mq_getsetattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 422
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
int do_mq_getsetattr(int mqdes, struct mq_attr * new, struct mq_attr * old)
```

```json
{
  "name": "do_mq_getsetattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585437488,
      "name": "do_mq_getsetattr",
      "external": false,
      "loc": "ipc/mqueue.c:1452",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:__do_compat_sys_mq_getsetattr",
        "ipc/mqueue.c:__do_compat_sys_mq_getsetattr",
        "ipc/mqueue.c:__do_sys_mq_getsetattr",
        "ipc/mqueue.c:__do_sys_mq_getsetattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585437488,
      "name": "do_mq_getsetattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 422
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
int do_mq_getsetattr(int mqdes, struct mq_attr * new, struct mq_attr * old)
```

```json
{
  "name": "do_mq_getsetattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585668240,
      "name": "do_mq_getsetattr",
      "external": false,
      "loc": "ipc/mqueue.c:1452",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:__do_compat_sys_mq_getsetattr",
        "ipc/mqueue.c:__do_compat_sys_mq_getsetattr",
        "ipc/mqueue.c:__do_sys_mq_getsetattr",
        "ipc/mqueue.c:__do_sys_mq_getsetattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585668240,
      "name": "do_mq_getsetattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 428
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
int do_mq_getsetattr(int mqdes, struct mq_attr * new, struct mq_attr * old)
```

```json
{
  "name": "do_mq_getsetattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585915040,
      "name": "do_mq_getsetattr",
      "external": false,
      "loc": "ipc/mqueue.c:1452",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:__do_compat_sys_mq_getsetattr",
        "ipc/mqueue.c:__do_compat_sys_mq_getsetattr",
        "ipc/mqueue.c:__do_sys_mq_getsetattr",
        "ipc/mqueue.c:__do_sys_mq_getsetattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585915040,
      "name": "do_mq_getsetattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 409
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
int do_mq_getsetattr(int mqdes, struct mq_attr * new, struct mq_attr * old)
```

```json
{
  "name": "do_mq_getsetattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495048776,
      "name": "do_mq_getsetattr",
      "external": false,
      "loc": "ipc/mqueue.c:1350",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:__do_compat_sys_mq_getsetattr",
        "ipc/mqueue.c:__do_compat_sys_mq_getsetattr",
        "ipc/mqueue.c:__do_sys_mq_getsetattr",
        "ipc/mqueue.c:__do_sys_mq_getsetattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495048776,
      "name": "do_mq_getsetattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 520
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "do_mq_getsetattr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "do_mq_getsetattr",
      "external": false,
      "loc": "ipc/mqueue.c:1350",
      "file": "ipc/mqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/mqueue.c:__se_sys_mq_getsetattr"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int do_mq_getsetattr(int mqdes, struct mq_attr * new, struct mq_attr * old)
```

```json
{
  "name": "do_mq_getsetattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288935600,
      "name": "do_mq_getsetattr",
      "external": false,
      "loc": "ipc/mqueue.c:1350",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:__do_compat_sys_mq_getsetattr",
        "ipc/mqueue.c:__do_compat_sys_mq_getsetattr",
        "ipc/mqueue.c:__do_sys_mq_getsetattr",
        "ipc/mqueue.c:__do_sys_mq_getsetattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288935600,
      "name": "do_mq_getsetattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 684
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "do_mq_getsetattr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936274320922,
      "name": "do_mq_getsetattr",
      "external": false,
      "loc": "ipc/mqueue.c:1350",
      "file": "ipc/mqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "ipc/mqueue.c:__do_sys_mq_getsetattr"
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
int do_mq_getsetattr(int mqdes, struct mq_attr * new, struct mq_attr * old)
```

```json
{
  "name": "do_mq_getsetattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583278032,
      "name": "do_mq_getsetattr",
      "external": false,
      "loc": "ipc/mqueue.c:1350",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:__do_compat_sys_mq_getsetattr",
        "ipc/mqueue.c:__do_compat_sys_mq_getsetattr",
        "ipc/mqueue.c:__do_sys_mq_getsetattr",
        "ipc/mqueue.c:__do_sys_mq_getsetattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583278032,
      "name": "do_mq_getsetattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 430
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
int do_mq_getsetattr(int mqdes, struct mq_attr * new, struct mq_attr * old)
```

```json
{
  "name": "do_mq_getsetattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583215168,
      "name": "do_mq_getsetattr",
      "external": false,
      "loc": "ipc/mqueue.c:1350",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:__do_compat_sys_mq_getsetattr",
        "ipc/mqueue.c:__do_compat_sys_mq_getsetattr",
        "ipc/mqueue.c:__do_sys_mq_getsetattr",
        "ipc/mqueue.c:__do_sys_mq_getsetattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583215168,
      "name": "do_mq_getsetattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 430
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
int do_mq_getsetattr(int mqdes, struct mq_attr * new, struct mq_attr * old)
```

```json
{
  "name": "do_mq_getsetattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583262064,
      "name": "do_mq_getsetattr",
      "external": false,
      "loc": "ipc/mqueue.c:1350",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:__do_compat_sys_mq_getsetattr",
        "ipc/mqueue.c:__do_compat_sys_mq_getsetattr",
        "ipc/mqueue.c:__do_sys_mq_getsetattr",
        "ipc/mqueue.c:__do_sys_mq_getsetattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583262064,
      "name": "do_mq_getsetattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 430
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
int do_mq_getsetattr(int mqdes, struct mq_attr * new, struct mq_attr * old)
```

```json
{
  "name": "do_mq_getsetattr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583354128,
      "name": "do_mq_getsetattr",
      "external": false,
      "loc": "ipc/mqueue.c:1350",
      "file": "ipc/mqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "ipc/mqueue.c:__do_compat_sys_mq_getsetattr",
        "ipc/mqueue.c:__do_compat_sys_mq_getsetattr",
        "ipc/mqueue.c:__do_sys_mq_getsetattr",
        "ipc/mqueue.c:__do_sys_mq_getsetattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583354128,
      "name": "do_mq_getsetattr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 453
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
int do_mq_getsetattr(int mqdes, struct mq_attr * new, struct mq_attr * old)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int do_mq_getsetattr(int mqdes, struct mq_attr * new, struct mq_attr * old)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int do_mq_getsetattr(int mqdes, struct mq_attr * new, struct mq_attr * old)
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
