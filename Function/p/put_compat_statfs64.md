# Function: <code>put_compat_statfs64</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int put_compat_statfs64(struct compat_statfs64 * ubuf, struct kstatfs * kbuf)
```

```json
{
  "name": "put_compat_statfs64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581350496,
      "name": "put_compat_statfs64",
      "external": false,
      "loc": "fs/compat.c:268",
      "file": "fs/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/compat.c:C_SYSC_statfs64",
        "fs/compat.c:C_SYSC_fstatfs64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581350496,
      "name": "put_compat_statfs64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 308
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
int put_compat_statfs64(struct compat_statfs64 * ubuf, struct kstatfs * kbuf)
```

```json
{
  "name": "put_compat_statfs64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581531136,
      "name": "put_compat_statfs64",
      "external": false,
      "loc": "fs/compat.c:268",
      "file": "fs/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/compat.c:C_SYSC_fstatfs64",
        "fs/compat.c:C_SYSC_statfs64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581531136,
      "name": "put_compat_statfs64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 297
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
int put_compat_statfs64(struct compat_statfs64 * ubuf, struct kstatfs * kbuf)
```

```json
{
  "name": "put_compat_statfs64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581617120,
      "name": "put_compat_statfs64",
      "external": false,
      "loc": "fs/compat.c:254",
      "file": "fs/compat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/compat.c:C_SYSC_fstatfs64",
        "fs/compat.c:C_SYSC_statfs64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581617120,
      "name": "put_compat_statfs64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 390
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
int put_compat_statfs64(struct compat_statfs64 * ubuf, struct kstatfs * kbuf)
```

```json
{
  "name": "put_compat_statfs64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581508880,
      "name": "put_compat_statfs64",
      "external": false,
      "loc": "fs/statfs.c:303",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:C_SYSC_fstatfs64",
        "fs/statfs.c:C_SYSC_statfs64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581508880,
      "name": "put_compat_statfs64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
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
int put_compat_statfs64(struct compat_statfs64 * ubuf, struct kstatfs * kbuf)
```

```json
{
  "name": "put_compat_statfs64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581651024,
      "name": "put_compat_statfs64",
      "external": false,
      "loc": "fs/statfs.c:304",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:C_SYSC_fstatfs64",
        "fs/statfs.c:C_SYSC_statfs64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581651024,
      "name": "put_compat_statfs64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
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
int put_compat_statfs64(struct compat_statfs64 * ubuf, struct kstatfs * kbuf)
```

```json
{
  "name": "put_compat_statfs64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581813632,
      "name": "put_compat_statfs64",
      "external": false,
      "loc": "fs/statfs.c:304",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:__do_compat_sys_fstatfs64",
        "fs/statfs.c:__do_compat_sys_statfs64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581813632,
      "name": "put_compat_statfs64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
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
int put_compat_statfs64(struct compat_statfs64 * ubuf, struct kstatfs * kbuf)
```

```json
{
  "name": "put_compat_statfs64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581900624,
      "name": "put_compat_statfs64",
      "external": false,
      "loc": "fs/statfs.c:304",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:kcompat_sys_fstatfs64",
        "fs/statfs.c:kcompat_sys_statfs64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581900624,
      "name": "put_compat_statfs64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
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
int put_compat_statfs64(struct compat_statfs64 * ubuf, struct kstatfs * kbuf)
```

```json
{
  "name": "put_compat_statfs64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582026064,
      "name": "put_compat_statfs64",
      "external": false,
      "loc": "fs/statfs.c:318",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:kcompat_sys_fstatfs64",
        "fs/statfs.c:kcompat_sys_statfs64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582026064,
      "name": "put_compat_statfs64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 270
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
int put_compat_statfs64(struct compat_statfs64 * ubuf, struct kstatfs * kbuf)
```

```json
{
  "name": "put_compat_statfs64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582104048,
      "name": "put_compat_statfs64",
      "external": false,
      "loc": "fs/statfs.c:318",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:kcompat_sys_fstatfs64",
        "fs/statfs.c:kcompat_sys_statfs64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582104048,
      "name": "put_compat_statfs64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 213
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
int put_compat_statfs64(struct compat_statfs64 * ubuf, struct kstatfs * kbuf)
```

```json
{
  "name": "put_compat_statfs64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582341056,
      "name": "put_compat_statfs64",
      "external": false,
      "loc": "fs/statfs.c:318",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:kcompat_sys_fstatfs64",
        "fs/statfs.c:kcompat_sys_statfs64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582341056,
      "name": "put_compat_statfs64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 219
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
int put_compat_statfs64(struct compat_statfs64 * ubuf, struct kstatfs * kbuf)
```

```json
{
  "name": "put_compat_statfs64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582392544,
      "name": "put_compat_statfs64",
      "external": false,
      "loc": "fs/statfs.c:320",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:kcompat_sys_fstatfs64",
        "fs/statfs.c:kcompat_sys_statfs64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582392544,
      "name": "put_compat_statfs64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 219
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
int put_compat_statfs64(struct compat_statfs64 * ubuf, struct kstatfs * kbuf)
```

```json
{
  "name": "put_compat_statfs64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582419904,
      "name": "put_compat_statfs64",
      "external": false,
      "loc": "fs/statfs.c:323",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:kcompat_sys_fstatfs64",
        "fs/statfs.c:kcompat_sys_statfs64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582419904,
      "name": "put_compat_statfs64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 219
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
int put_compat_statfs64(struct compat_statfs64 * ubuf, struct kstatfs * kbuf)
```

```json
{
  "name": "put_compat_statfs64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582742720,
      "name": "put_compat_statfs64",
      "external": false,
      "loc": "fs/statfs.c:323",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:kcompat_sys_fstatfs64",
        "fs/statfs.c:kcompat_sys_statfs64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582742720,
      "name": "put_compat_statfs64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 219
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
int put_compat_statfs64(struct compat_statfs64 * ubuf, struct kstatfs * kbuf)
```

```json
{
  "name": "put_compat_statfs64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583288896,
      "name": "put_compat_statfs64",
      "external": false,
      "loc": "fs/statfs.c:323",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:kcompat_sys_fstatfs64",
        "fs/statfs.c:kcompat_sys_statfs64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583288896,
      "name": "put_compat_statfs64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 243
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
int put_compat_statfs64(struct compat_statfs64 * ubuf, struct kstatfs * kbuf)
```

```json
{
  "name": "put_compat_statfs64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583872480,
      "name": "put_compat_statfs64",
      "external": false,
      "loc": "fs/statfs.c:323",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:kcompat_sys_fstatfs64",
        "fs/statfs.c:kcompat_sys_statfs64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583872480,
      "name": "put_compat_statfs64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 243
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
int put_compat_statfs64(struct compat_statfs64 * ubuf, struct kstatfs * kbuf)
```

```json
{
  "name": "put_compat_statfs64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584094240,
      "name": "put_compat_statfs64",
      "external": false,
      "loc": "fs/statfs.c:323",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:kcompat_sys_fstatfs64",
        "fs/statfs.c:kcompat_sys_statfs64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584094240,
      "name": "put_compat_statfs64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 243
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
int put_compat_statfs64(struct compat_statfs64 * ubuf, struct kstatfs * kbuf)
```

```json
{
  "name": "put_compat_statfs64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584310384,
      "name": "put_compat_statfs64",
      "external": false,
      "loc": "fs/statfs.c:323",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:kcompat_sys_fstatfs64",
        "fs/statfs.c:kcompat_sys_statfs64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584310384,
      "name": "put_compat_statfs64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 243
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
int put_compat_statfs64(struct compat_statfs64 * ubuf, struct kstatfs * kbuf)
```

```json
{
  "name": "put_compat_statfs64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493642936,
      "name": "put_compat_statfs64",
      "external": false,
      "loc": "fs/statfs.c:318",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:kcompat_sys_fstatfs64",
        "fs/statfs.c:kcompat_sys_statfs64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493642936,
      "name": "put_compat_statfs64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 332
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
int put_compat_statfs64(struct compat_statfs64 * ubuf, struct kstatfs * kbuf)
```

```json
{
  "name": "put_compat_statfs64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287233632,
      "name": "put_compat_statfs64",
      "external": false,
      "loc": "fs/statfs.c:318",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:kcompat_sys_fstatfs64",
        "fs/statfs.c:kcompat_sys_statfs64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287233632,
      "name": "put_compat_statfs64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 272
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
int put_compat_statfs64(struct compat_statfs64 * ubuf, struct kstatfs * kbuf)
```

```json
{
  "name": "put_compat_statfs64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582072784,
      "name": "put_compat_statfs64",
      "external": false,
      "loc": "fs/statfs.c:318",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:kcompat_sys_fstatfs64",
        "fs/statfs.c:kcompat_sys_statfs64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582072784,
      "name": "put_compat_statfs64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 213
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
int put_compat_statfs64(struct compat_statfs64 * ubuf, struct kstatfs * kbuf)
```

```json
{
  "name": "put_compat_statfs64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582010336,
      "name": "put_compat_statfs64",
      "external": false,
      "loc": "fs/statfs.c:318",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:kcompat_sys_fstatfs64",
        "fs/statfs.c:kcompat_sys_statfs64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582010336,
      "name": "put_compat_statfs64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 213
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
int put_compat_statfs64(struct compat_statfs64 * ubuf, struct kstatfs * kbuf)
```

```json
{
  "name": "put_compat_statfs64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582064064,
      "name": "put_compat_statfs64",
      "external": false,
      "loc": "fs/statfs.c:318",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:kcompat_sys_fstatfs64",
        "fs/statfs.c:kcompat_sys_statfs64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582064064,
      "name": "put_compat_statfs64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 213
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
int put_compat_statfs64(struct compat_statfs64 * ubuf, struct kstatfs * kbuf)
```

```json
{
  "name": "put_compat_statfs64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582135808,
      "name": "put_compat_statfs64",
      "external": false,
      "loc": "fs/statfs.c:318",
      "file": "fs/statfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/statfs.c:kcompat_sys_fstatfs64",
        "fs/statfs.c:kcompat_sys_statfs64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582135808,
      "name": "put_compat_statfs64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 213
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
int put_compat_statfs64(struct compat_statfs64 * ubuf, struct kstatfs * kbuf)
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
int put_compat_statfs64(struct compat_statfs64 * ubuf, struct kstatfs * kbuf)
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
