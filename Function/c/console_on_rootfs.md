# Function: <code>console_on_rootfs</code>

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
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void console_on_rootfs()
```

```json
{
  "name": "console_on_rootfs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "console_on_rootfs",
      "external": true,
      "loc": "init/main.c:1464",
      "file": "init/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:kernel_init_freeable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578860641,
      "name": "console_on_rootfs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071578860112,
      "name": "console_on_rootfs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
void console_on_rootfs()
```

```json
{
  "name": "console_on_rootfs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071612070146,
      "name": "console_on_rootfs",
      "external": true,
      "loc": "init/main.c:1485",
      "file": "init/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:kernel_init_freeable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612070146,
      "name": "console_on_rootfs",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 91
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
void console_on_rootfs()
```

```json
{
  "name": "console_on_rootfs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071614208293,
      "name": "console_on_rootfs",
      "external": true,
      "loc": "init/main.c:1507",
      "file": "init/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:kernel_init_freeable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071614208293,
      "name": "console_on_rootfs",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 91
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
void console_on_rootfs()
```

```json
{
  "name": "console_on_rootfs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071615126797,
      "name": "console_on_rootfs",
      "external": true,
      "loc": "init/main.c:1573",
      "file": "init/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:kernel_init_freeable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615126797,
      "name": "console_on_rootfs",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 91
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
void console_on_rootfs()
```

```json
{
  "name": "console_on_rootfs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071616888690,
      "name": "console_on_rootfs",
      "external": true,
      "loc": "init/main.c:1579",
      "file": "init/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:kernel_init_freeable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071616888690,
      "name": "console_on_rootfs",
      "section": ".init.text",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void console_on_rootfs()
```

```json
{
  "name": "console_on_rootfs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071627479104,
      "name": "console_on_rootfs",
      "external": true,
      "loc": "init/main.c:1589",
      "file": "init/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:kernel_init_freeable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071627479104,
      "name": "console_on_rootfs",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 120
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
void console_on_rootfs()
```

```json
{
  "name": "console_on_rootfs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071619222624,
      "name": "console_on_rootfs",
      "external": true,
      "loc": "init/main.c:1504",
      "file": "init/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:kernel_init_freeable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071619222624,
      "name": "console_on_rootfs",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 120
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
void console_on_rootfs()
```

```json
{
  "name": "console_on_rootfs",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071621512336,
      "name": "console_on_rootfs",
      "external": true,
      "loc": "init/main.c:1508",
      "file": "init/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:kernel_init_freeable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071621512336,
      "name": "console_on_rootfs",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 120
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void console_on_rootfs()
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
