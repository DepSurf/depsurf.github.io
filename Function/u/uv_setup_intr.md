# Function: <code>uv_setup_intr</code>

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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int uv_setup_intr(int cpu, u64 expires)
```

```json
{
  "name": "uv_setup_intr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579470512,
      "name": "uv_setup_intr",
      "external": false,
      "loc": "arch/x86/platform/uv/uv_time.c:98",
      "file": "arch/x86/platform/uv/uv_time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/uv/uv_time.c:uv_rtc_next_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579470512,
      "name": "uv_setup_intr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 909
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
int uv_setup_intr(int cpu, u64 expires)
```

```json
{
  "name": "uv_setup_intr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579492768,
      "name": "uv_setup_intr",
      "external": false,
      "loc": "arch/x86/platform/uv/uv_time.c:98",
      "file": "arch/x86/platform/uv/uv_time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/uv/uv_time.c:uv_rtc_set_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579492768,
      "name": "uv_setup_intr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 766
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
int uv_setup_intr(int cpu, u64 expires)
```

```json
{
  "name": "uv_setup_intr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579475296,
      "name": "uv_setup_intr",
      "external": false,
      "loc": "arch/x86/platform/uv/uv_time.c:93",
      "file": "arch/x86/platform/uv/uv_time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/uv/uv_time.c:uv_rtc_set_timer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579475296,
      "name": "uv_setup_intr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 703
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
int uv_setup_intr(int cpu, u64 expires)
```

```json
{
  "name": "uv_setup_intr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579477328,
      "name": "uv_setup_intr",
      "external": false,
      "loc": "arch/x86/platform/uv/uv_time.c:93",
      "file": "arch/x86/platform/uv/uv_time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/uv/uv_time.c:uv_rtc_next_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579477328,
      "name": "uv_setup_intr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 660
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int uv_setup_intr(int cpu, u64 expires)
```

```json
{
  "name": "uv_setup_intr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "uv_setup_intr",
      "external": false,
      "loc": "arch/x86/platform/uv/uv_time.c:93",
      "file": "arch/x86/platform/uv/uv_time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/uv/uv_time.c:uv_rtc_next_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579542992,
      "name": "uv_setup_intr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 825
    },
    {
      "addr": 18446744071592094096,
      "name": "uv_setup_intr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int uv_setup_intr(int cpu, u64 expires)
```

```json
{
  "name": "uv_setup_intr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "uv_setup_intr",
      "external": false,
      "loc": "arch/x86/platform/uv/uv_time.c:93",
      "file": "arch/x86/platform/uv/uv_time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/uv/uv_time.c:uv_rtc_next_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579631648,
      "name": "uv_setup_intr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 764
    },
    {
      "addr": 18446744071593861618,
      "name": "uv_setup_intr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int uv_setup_intr(int cpu, u64 expires)
```

```json
{
  "name": "uv_setup_intr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "uv_setup_intr",
      "external": false,
      "loc": "arch/x86/platform/uv/uv_time.c:93",
      "file": "arch/x86/platform/uv/uv_time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/uv/uv_time.c:uv_rtc_next_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579746176,
      "name": "uv_setup_intr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 764
    },
    {
      "addr": 18446744071595972256,
      "name": "uv_setup_intr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int uv_setup_intr(int cpu, u64 expires)
```

```json
{
  "name": "uv_setup_intr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "uv_setup_intr",
      "external": false,
      "loc": "arch/x86/platform/uv/uv_time.c:93",
      "file": "arch/x86/platform/uv/uv_time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/uv/uv_time.c:uv_rtc_next_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579792720,
      "name": "uv_setup_intr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 764
    },
    {
      "addr": 18446744071596489883,
      "name": "uv_setup_intr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int uv_setup_intr(int cpu, u64 expires)
```

```json
{
  "name": "uv_setup_intr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "uv_setup_intr",
      "external": false,
      "loc": "arch/x86/platform/uv/uv_time.c:93",
      "file": "arch/x86/platform/uv/uv_time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/uv/uv_time.c:uv_rtc_next_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579826400,
      "name": "uv_setup_intr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 763
    },
    {
      "addr": 18446744071597386477,
      "name": "uv_setup_intr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int uv_setup_intr(int cpu, u64 expires)
```

```json
{
  "name": "uv_setup_intr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579475840,
      "name": "uv_setup_intr",
      "external": false,
      "loc": "arch/x86/platform/uv/uv_time.c:98",
      "file": "arch/x86/platform/uv/uv_time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/uv/uv_time.c:uv_rtc_next_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579475840,
      "name": "uv_setup_intr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 909
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
int uv_setup_intr(int cpu, u64 expires)
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
int uv_setup_intr(int cpu, u64 expires)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int uv_setup_intr(int cpu, u64 expires)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int uv_setup_intr(int cpu, u64 expires)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int uv_setup_intr(int cpu, u64 expires)
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
int uv_setup_intr(int cpu, u64 expires)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
int uv_setup_intr(int cpu, u64 expires)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ➖</summary>

```c
int uv_setup_intr(int cpu, u64 expires)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
