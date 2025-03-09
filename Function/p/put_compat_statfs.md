# Function: <code>put_compat_statfs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int put_compat_statfs(struct compat_statfs * ubuf, struct kstatfs * kbuf)
```

```json
{
  "name": "put_compat_statfs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581350016,
      "name": "put_compat_statfs",
      "external": false,
      "loc": "fs/compat.c:212",
      "file": "fs/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/compat.c:C_SYSC_statfs",
        "fs/compat.c:C_SYSC_fstatfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581350016,
      "name": "put_compat_statfs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 383
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
int put_compat_statfs(struct compat_statfs * ubuf, struct kstatfs * kbuf)
```

```json
{
  "name": "put_compat_statfs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581530640,
      "name": "put_compat_statfs",
      "external": false,
      "loc": "fs/compat.c:212",
      "file": "fs/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/compat.c:C_SYSC_fstatfs",
        "fs/compat.c:C_SYSC_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581530640,
      "name": "put_compat_statfs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 386
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
int put_compat_statfs(struct compat_statfs * ubuf, struct kstatfs * kbuf)
```

```json
{
  "name": "put_compat_statfs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581616624,
      "name": "put_compat_statfs",
      "external": false,
      "loc": "fs/compat.c:198",
      "file": "fs/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/compat.c:C_SYSC_fstatfs",
        "fs/compat.c:C_SYSC_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581616624,
      "name": "put_compat_statfs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 386
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
int put_compat_statfs(struct compat_statfs * ubuf, struct kstatfs * kbuf)
```

```json
{
  "name": "put_compat_statfs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581508608,
      "name": "put_compat_statfs",
      "external": false,
      "loc": "fs/statfs.c:247",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:C_SYSC_fstatfs",
        "fs/statfs.c:C_SYSC_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581508608,
      "name": "put_compat_statfs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 259
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
int put_compat_statfs(struct compat_statfs * ubuf, struct kstatfs * kbuf)
```

```json
{
  "name": "put_compat_statfs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581650752,
      "name": "put_compat_statfs",
      "external": false,
      "loc": "fs/statfs.c:248",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:C_SYSC_fstatfs",
        "fs/statfs.c:C_SYSC_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581650752,
      "name": "put_compat_statfs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 259
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
int put_compat_statfs(struct compat_statfs * ubuf, struct kstatfs * kbuf)
```

```json
{
  "name": "put_compat_statfs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581813376,
      "name": "put_compat_statfs",
      "external": false,
      "loc": "fs/statfs.c:248",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:__do_compat_sys_fstatfs",
        "fs/statfs.c:__do_compat_sys_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581813376,
      "name": "put_compat_statfs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 255
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
int put_compat_statfs(struct compat_statfs * ubuf, struct kstatfs * kbuf)
```

```json
{
  "name": "put_compat_statfs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581900368,
      "name": "put_compat_statfs",
      "external": false,
      "loc": "fs/statfs.c:248",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:__do_compat_sys_fstatfs",
        "fs/statfs.c:__do_compat_sys_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581900368,
      "name": "put_compat_statfs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 255
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
int put_compat_statfs(struct compat_statfs * ubuf, struct kstatfs * kbuf)
```

```json
{
  "name": "put_compat_statfs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582025808,
      "name": "put_compat_statfs",
      "external": false,
      "loc": "fs/statfs.c:262",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:__do_compat_sys_fstatfs",
        "fs/statfs.c:__do_compat_sys_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582025808,
      "name": "put_compat_statfs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 255
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
int put_compat_statfs(struct compat_statfs * ubuf, struct kstatfs * kbuf)
```

```json
{
  "name": "put_compat_statfs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582103792,
      "name": "put_compat_statfs",
      "external": false,
      "loc": "fs/statfs.c:262",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:__do_compat_sys_fstatfs",
        "fs/statfs.c:__do_compat_sys_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582103792,
      "name": "put_compat_statfs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 255
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
int put_compat_statfs(struct compat_statfs * ubuf, struct kstatfs * kbuf)
```

```json
{
  "name": "put_compat_statfs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582340800,
      "name": "put_compat_statfs",
      "external": false,
      "loc": "fs/statfs.c:262",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:__do_compat_sys_fstatfs",
        "fs/statfs.c:__do_compat_sys_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582340800,
      "name": "put_compat_statfs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 254
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
int put_compat_statfs(struct compat_statfs * ubuf, struct kstatfs * kbuf)
```

```json
{
  "name": "put_compat_statfs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582392288,
      "name": "put_compat_statfs",
      "external": false,
      "loc": "fs/statfs.c:264",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:__do_compat_sys_fstatfs",
        "fs/statfs.c:__do_compat_sys_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582392288,
      "name": "put_compat_statfs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 254
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
int put_compat_statfs(struct compat_statfs * ubuf, struct kstatfs * kbuf)
```

```json
{
  "name": "put_compat_statfs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582419648,
      "name": "put_compat_statfs",
      "external": false,
      "loc": "fs/statfs.c:267",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:__do_compat_sys_fstatfs",
        "fs/statfs.c:__do_compat_sys_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582419648,
      "name": "put_compat_statfs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 254
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
int put_compat_statfs(struct compat_statfs * ubuf, struct kstatfs * kbuf)
```

```json
{
  "name": "put_compat_statfs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582742464,
      "name": "put_compat_statfs",
      "external": false,
      "loc": "fs/statfs.c:267",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:__do_compat_sys_fstatfs",
        "fs/statfs.c:__do_compat_sys_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582742464,
      "name": "put_compat_statfs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 254
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
int put_compat_statfs(struct compat_statfs * ubuf, struct kstatfs * kbuf)
```

```json
{
  "name": "put_compat_statfs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583288576,
      "name": "put_compat_statfs",
      "external": false,
      "loc": "fs/statfs.c:267",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:__do_compat_sys_fstatfs",
        "fs/statfs.c:__do_compat_sys_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583288576,
      "name": "put_compat_statfs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 305
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
int put_compat_statfs(struct compat_statfs * ubuf, struct kstatfs * kbuf)
```

```json
{
  "name": "put_compat_statfs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583872144,
      "name": "put_compat_statfs",
      "external": false,
      "loc": "fs/statfs.c:267",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:__do_compat_sys_fstatfs",
        "fs/statfs.c:__do_compat_sys_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583872144,
      "name": "put_compat_statfs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 305
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
int put_compat_statfs(struct compat_statfs * ubuf, struct kstatfs * kbuf)
```

```json
{
  "name": "put_compat_statfs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584093904,
      "name": "put_compat_statfs",
      "external": false,
      "loc": "fs/statfs.c:267",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:__do_compat_sys_fstatfs",
        "fs/statfs.c:__do_compat_sys_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584093904,
      "name": "put_compat_statfs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 305
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
int put_compat_statfs(struct compat_statfs * ubuf, struct kstatfs * kbuf)
```

```json
{
  "name": "put_compat_statfs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584310048,
      "name": "put_compat_statfs",
      "external": false,
      "loc": "fs/statfs.c:267",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:__do_compat_sys_fstatfs",
        "fs/statfs.c:__do_compat_sys_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584310048,
      "name": "put_compat_statfs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 305
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
int put_compat_statfs(struct compat_statfs * ubuf, struct kstatfs * kbuf)
```

```json
{
  "name": "put_compat_statfs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493643272,
      "name": "put_compat_statfs",
      "external": false,
      "loc": "fs/statfs.c:262",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:__do_compat_sys_fstatfs",
        "fs/statfs.c:__do_compat_sys_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493643272,
      "name": "put_compat_statfs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 340
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int put_compat_statfs(struct compat_statfs * ubuf, struct kstatfs * kbuf)
```

```json
{
  "name": "put_compat_statfs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287233312,
      "name": "put_compat_statfs",
      "external": false,
      "loc": "fs/statfs.c:262",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:__do_compat_sys_fstatfs",
        "fs/statfs.c:__do_compat_sys_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287233312,
      "name": "put_compat_statfs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 320
    }
  ]
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int put_compat_statfs(struct compat_statfs * ubuf, struct kstatfs * kbuf)
```

```json
{
  "name": "put_compat_statfs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582072528,
      "name": "put_compat_statfs",
      "external": false,
      "loc": "fs/statfs.c:262",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:__do_compat_sys_fstatfs",
        "fs/statfs.c:__do_compat_sys_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582072528,
      "name": "put_compat_statfs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 255
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
int put_compat_statfs(struct compat_statfs * ubuf, struct kstatfs * kbuf)
```

```json
{
  "name": "put_compat_statfs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582010080,
      "name": "put_compat_statfs",
      "external": false,
      "loc": "fs/statfs.c:262",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:__do_compat_sys_fstatfs",
        "fs/statfs.c:__do_compat_sys_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582010080,
      "name": "put_compat_statfs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 255
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
int put_compat_statfs(struct compat_statfs * ubuf, struct kstatfs * kbuf)
```

```json
{
  "name": "put_compat_statfs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582063808,
      "name": "put_compat_statfs",
      "external": false,
      "loc": "fs/statfs.c:262",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:__do_compat_sys_fstatfs",
        "fs/statfs.c:__do_compat_sys_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582063808,
      "name": "put_compat_statfs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 255
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
int put_compat_statfs(struct compat_statfs * ubuf, struct kstatfs * kbuf)
```

```json
{
  "name": "put_compat_statfs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582135552,
      "name": "put_compat_statfs",
      "external": false,
      "loc": "fs/statfs.c:262",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:__do_compat_sys_fstatfs",
        "fs/statfs.c:__do_compat_sys_statfs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582135552,
      "name": "put_compat_statfs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 255
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int put_compat_statfs(struct compat_statfs * ubuf, struct kstatfs * kbuf)
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
int put_compat_statfs(struct compat_statfs * ubuf, struct kstatfs * kbuf)
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
