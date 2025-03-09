# Function: <code>uv_rtc_find_next_timer</code>

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
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void uv_rtc_find_next_timer(struct uv_rtc_timer_head * head, int pnode)
```

```json
{
  "name": "uv_rtc_find_next_timer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579471424,
      "name": "uv_rtc_find_next_timer",
      "external": false,
      "loc": "arch/x86/platform/uv/uv_time.c:181",
      "file": "arch/x86/platform/uv/uv_time.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/uv/uv_time.c:uv_rtc_next_event",
        "arch/x86/platform/uv/uv_time.c:uv_rtc_unset_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579471424,
      "name": "uv_rtc_find_next_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 360
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void uv_rtc_find_next_timer(struct uv_rtc_timer_head * head, int pnode)
```

```json
{
  "name": "uv_rtc_find_next_timer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579493536,
      "name": "uv_rtc_find_next_timer",
      "external": false,
      "loc": "arch/x86/platform/uv/uv_time.c:181",
      "file": "arch/x86/platform/uv/uv_time.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/uv/uv_time.c:uv_rtc_unset_timer",
        "arch/x86/platform/uv/uv_time.c:uv_rtc_set_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579493536,
      "name": "uv_rtc_find_next_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 363
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void uv_rtc_find_next_timer(struct uv_rtc_timer_head * head, int pnode)
```

```json
{
  "name": "uv_rtc_find_next_timer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579476000,
      "name": "uv_rtc_find_next_timer",
      "external": false,
      "loc": "arch/x86/platform/uv/uv_time.c:171",
      "file": "arch/x86/platform/uv/uv_time.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/uv/uv_time.c:uv_rtc_unset_timer",
        "arch/x86/platform/uv/uv_time.c:uv_rtc_set_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579476000,
      "name": "uv_rtc_find_next_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 355
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void uv_rtc_find_next_timer(struct uv_rtc_timer_head * head, int pnode)
```

```json
{
  "name": "uv_rtc_find_next_timer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579478000,
      "name": "uv_rtc_find_next_timer",
      "external": false,
      "loc": "arch/x86/platform/uv/uv_time.c:171",
      "file": "arch/x86/platform/uv/uv_time.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/uv/uv_time.c:uv_rtc_next_event",
        "arch/x86/platform/uv/uv_time.c:uv_rtc_unset_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579478000,
      "name": "uv_rtc_find_next_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 355
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void uv_rtc_find_next_timer(struct uv_rtc_timer_head * head, int pnode)
```

```json
{
  "name": "uv_rtc_find_next_timer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579543944,
      "name": "uv_rtc_find_next_timer",
      "external": false,
      "loc": "arch/x86/platform/uv/uv_time.c:171",
      "file": "arch/x86/platform/uv/uv_time.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/uv/uv_time.c:uv_rtc_next_event",
        "arch/x86/platform/uv/uv_time.c:uv_rtc_unset_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579543824,
      "name": "uv_rtc_find_next_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 438
    },
    {
      "addr": 18446744071592094282,
      "name": "uv_rtc_find_next_timer.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void uv_rtc_find_next_timer(struct uv_rtc_timer_head * head, int pnode)
```

```json
{
  "name": "uv_rtc_find_next_timer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579632562,
      "name": "uv_rtc_find_next_timer",
      "external": false,
      "loc": "arch/x86/platform/uv/uv_time.c:171",
      "file": "arch/x86/platform/uv/uv_time.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/uv/uv_time.c:uv_rtc_next_event",
        "arch/x86/platform/uv/uv_time.c:uv_rtc_unset_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579632416,
      "name": "uv_rtc_find_next_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 496
    },
    {
      "addr": 18446744071593861804,
      "name": "uv_rtc_find_next_timer.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void uv_rtc_find_next_timer(struct uv_rtc_timer_head * head, int pnode)
```

```json
{
  "name": "uv_rtc_find_next_timer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579747106,
      "name": "uv_rtc_find_next_timer",
      "external": false,
      "loc": "arch/x86/platform/uv/uv_time.c:171",
      "file": "arch/x86/platform/uv/uv_time.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/uv/uv_time.c:uv_rtc_next_event",
        "arch/x86/platform/uv/uv_time.c:uv_rtc_unset_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579746960,
      "name": "uv_rtc_find_next_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 496
    },
    {
      "addr": 18446744071595972442,
      "name": "uv_rtc_find_next_timer.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void uv_rtc_find_next_timer(struct uv_rtc_timer_head * head, int pnode)
```

```json
{
  "name": "uv_rtc_find_next_timer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579793650,
      "name": "uv_rtc_find_next_timer",
      "external": false,
      "loc": "arch/x86/platform/uv/uv_time.c:171",
      "file": "arch/x86/platform/uv/uv_time.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/uv/uv_time.c:uv_rtc_next_event",
        "arch/x86/platform/uv/uv_time.c:uv_rtc_unset_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579793504,
      "name": "uv_rtc_find_next_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 496
    },
    {
      "addr": 18446744071596490069,
      "name": "uv_rtc_find_next_timer.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void uv_rtc_find_next_timer(struct uv_rtc_timer_head * head, int pnode)
```

```json
{
  "name": "uv_rtc_find_next_timer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579827330,
      "name": "uv_rtc_find_next_timer",
      "external": false,
      "loc": "arch/x86/platform/uv/uv_time.c:171",
      "file": "arch/x86/platform/uv/uv_time.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/uv/uv_time.c:uv_rtc_next_event",
        "arch/x86/platform/uv/uv_time.c:uv_rtc_unset_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579827184,
      "name": "uv_rtc_find_next_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 495
    },
    {
      "addr": 18446744071597386663,
      "name": "uv_rtc_find_next_timer.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void uv_rtc_find_next_timer(struct uv_rtc_timer_head * head, int pnode)
```

```json
{
  "name": "uv_rtc_find_next_timer",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579476752,
      "name": "uv_rtc_find_next_timer",
      "external": false,
      "loc": "arch/x86/platform/uv/uv_time.c:181",
      "file": "arch/x86/platform/uv/uv_time.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/uv/uv_time.c:uv_rtc_next_event",
        "arch/x86/platform/uv/uv_time.c:uv_rtc_unset_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579476752,
      "name": "uv_rtc_find_next_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 360
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
void uv_rtc_find_next_timer(struct uv_rtc_timer_head * head, int pnode)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void uv_rtc_find_next_timer(struct uv_rtc_timer_head * head, int pnode)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void uv_rtc_find_next_timer(struct uv_rtc_timer_head * head, int pnode)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void uv_rtc_find_next_timer(struct uv_rtc_timer_head * head, int pnode)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void uv_rtc_find_next_timer(struct uv_rtc_timer_head * head, int pnode)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ➖</summary>

```c
void uv_rtc_find_next_timer(struct uv_rtc_timer_head * head, int pnode)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
void uv_rtc_find_next_timer(struct uv_rtc_timer_head * head, int pnode)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ➖</summary>

```c
void uv_rtc_find_next_timer(struct uv_rtc_timer_head * head, int pnode)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
