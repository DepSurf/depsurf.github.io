# Function: <code>hlt_play_dead</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "hlt_play_dead",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579183246,
      "name": "hlt_play_dead",
      "external": false,
      "loc": "arch/x86/kernel/smpboot.c:1627",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/smpboot.c:native_play_dead"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void hlt_play_dead()
```

```json
{
  "name": "hlt_play_dead",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579183248,
      "name": "hlt_play_dead",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:1654",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:native_play_dead",
        "arch/x86/power/cpu.c:resume_play_dead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579183248,
      "name": "hlt_play_dead",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void hlt_play_dead()
```

```json
{
  "name": "hlt_play_dead",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579193760,
      "name": "hlt_play_dead",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:1681",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:native_play_dead",
        "arch/x86/power/cpu.c:resume_play_dead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579193760,
      "name": "hlt_play_dead",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void hlt_play_dead()
```

```json
{
  "name": "hlt_play_dead",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579191968,
      "name": "hlt_play_dead",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:1686",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:native_play_dead",
        "arch/x86/power/cpu.c:resume_play_dead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579191968,
      "name": "hlt_play_dead",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void hlt_play_dead()
```

```json
{
  "name": "hlt_play_dead",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579207776,
      "name": "hlt_play_dead",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:1599",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:native_play_dead",
        "arch/x86/power/cpu.c:resume_play_dead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579207776,
      "name": "hlt_play_dead",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void hlt_play_dead()
```

```json
{
  "name": "hlt_play_dead",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579219152,
      "name": "hlt_play_dead",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:1657",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:native_play_dead",
        "arch/x86/power/cpu.c:resume_play_dead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579219152,
      "name": "hlt_play_dead",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void hlt_play_dead()
```

```json
{
  "name": "hlt_play_dead",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579242832,
      "name": "hlt_play_dead",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:1659",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:native_play_dead",
        "arch/x86/power/cpu.c:resume_play_dead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579242832,
      "name": "hlt_play_dead",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
void hlt_play_dead()
```

```json
{
  "name": "hlt_play_dead",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579256832,
      "name": "hlt_play_dead",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:1724",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:native_play_dead",
        "arch/x86/power/cpu.c:resume_play_dead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579256832,
      "name": "hlt_play_dead",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
void hlt_play_dead()
```

```json
{
  "name": "hlt_play_dead",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579258496,
      "name": "hlt_play_dead",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:1724",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:native_play_dead",
        "arch/x86/power/cpu.c:resume_play_dead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579258496,
      "name": "hlt_play_dead",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
void hlt_play_dead()
```

```json
{
  "name": "hlt_play_dead",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579284912,
      "name": "hlt_play_dead",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:1751",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:native_play_dead",
        "arch/x86/power/cpu.c:resume_play_dead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579284912,
      "name": "hlt_play_dead",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void hlt_play_dead()
```

```json
{
  "name": "hlt_play_dead",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579292240,
      "name": "hlt_play_dead",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:1745",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:native_play_dead",
        "arch/x86/power/cpu.c:resume_play_dead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579292240,
      "name": "hlt_play_dead",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void hlt_play_dead()
```

```json
{
  "name": "hlt_play_dead",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579294912,
      "name": "hlt_play_dead",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:1747",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:native_play_dead",
        "arch/x86/power/cpu.c:resume_play_dead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579294912,
      "name": "hlt_play_dead",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void hlt_play_dead()
```

```json
{
  "name": "hlt_play_dead",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579342032,
      "name": "hlt_play_dead",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:1754",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:native_play_dead",
        "arch/x86/power/cpu.c:resume_play_dead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579342032,
      "name": "hlt_play_dead",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
void hlt_play_dead()
```

```json
{
  "name": "hlt_play_dead",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579403104,
      "name": "hlt_play_dead",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:1819",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:native_play_dead",
        "arch/x86/power/cpu.c:resume_play_dead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579403104,
      "name": "hlt_play_dead",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
void hlt_play_dead()
```

```json
{
  "name": "hlt_play_dead",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579483664,
      "name": "hlt_play_dead",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:1819",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:native_play_dead",
        "arch/x86/power/cpu.c:resume_play_dead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579483664,
      "name": "hlt_play_dead",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
void hlt_play_dead()
```

```json
{
  "name": "hlt_play_dead",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579496064,
      "name": "hlt_play_dead",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:1737",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:native_play_dead",
        "arch/x86/power/cpu.c:resume_play_dead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579496064,
      "name": "hlt_play_dead",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void hlt_play_dead()
```

```json
{
  "name": "hlt_play_dead",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579525808,
      "name": "hlt_play_dead",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:1601",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:native_play_dead",
        "arch/x86/power/cpu.c:resume_play_dead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579525808,
      "name": "hlt_play_dead",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void hlt_play_dead()
```

```json
{
  "name": "hlt_play_dead",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579257200,
      "name": "hlt_play_dead",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:1724",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:native_play_dead",
        "arch/x86/power/cpu.c:resume_play_dead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579257200,
      "name": "hlt_play_dead",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
void hlt_play_dead()
```

```json
{
  "name": "hlt_play_dead",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579192416,
      "name": "hlt_play_dead",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:1724",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:native_play_dead",
        "arch/x86/power/cpu.c:resume_play_dead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579192416,
      "name": "hlt_play_dead",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
void hlt_play_dead()
```

```json
{
  "name": "hlt_play_dead",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579258400,
      "name": "hlt_play_dead",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:1724",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:native_play_dead",
        "arch/x86/power/cpu.c:resume_play_dead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579258400,
      "name": "hlt_play_dead",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
void hlt_play_dead()
```

```json
{
  "name": "hlt_play_dead",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579264000,
      "name": "hlt_play_dead",
      "external": true,
      "loc": "arch/x86/kernel/smpboot.c:1724",
      "file": "arch/x86/kernel/smpboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:native_play_dead",
        "arch/x86/power/cpu.c:resume_play_dead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579264000,
      "name": "hlt_play_dead",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
void hlt_play_dead()
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void hlt_play_dead()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void hlt_play_dead()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void hlt_play_dead()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void hlt_play_dead()
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
