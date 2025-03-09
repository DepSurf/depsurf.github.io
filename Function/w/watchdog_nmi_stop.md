# Function: <code>watchdog_nmi_stop</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void watchdog_nmi_stop()
```

```json
{
  "name": "watchdog_nmi_stop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580268368,
      "name": "watchdog_nmi_stop",
      "external": true,
      "loc": "kernel/watchdog.c:134",
      "file": "kernel/watchdog.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog.c:lockup_detector_reconfigure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580268368,
      "name": "watchdog_nmi_stop",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 11
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void watchdog_nmi_stop()
```

```json
{
  "name": "watchdog_nmi_stop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580328624,
      "name": "watchdog_nmi_stop",
      "external": true,
      "loc": "kernel/watchdog.c:134",
      "file": "kernel/watchdog.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog.c:lockup_detector_reconfigure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580328624,
      "name": "watchdog_nmi_stop",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 11
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void watchdog_nmi_stop()
```

```json
{
  "name": "watchdog_nmi_stop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580381824,
      "name": "watchdog_nmi_stop",
      "external": true,
      "loc": "kernel/watchdog.c:130",
      "file": "kernel/watchdog.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog.c:lockup_detector_reconfigure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580381824,
      "name": "watchdog_nmi_stop",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 11
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
void watchdog_nmi_stop()
```

```json
{
  "name": "watchdog_nmi_stop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580434528,
      "name": "watchdog_nmi_stop",
      "external": true,
      "loc": "kernel/watchdog.c:130",
      "file": "kernel/watchdog.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog.c:lockup_detector_reconfigure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580434528,
      "name": "watchdog_nmi_stop",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 11
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
void watchdog_nmi_stop()
```

```json
{
  "name": "watchdog_nmi_stop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580483296,
      "name": "watchdog_nmi_stop",
      "external": true,
      "loc": "kernel/watchdog.c:130",
      "file": "kernel/watchdog.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog.c:lockup_detector_reconfigure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580483296,
      "name": "watchdog_nmi_stop",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 11
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
void watchdog_nmi_stop()
```

```json
{
  "name": "watchdog_nmi_stop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580568160,
      "name": "watchdog_nmi_stop",
      "external": true,
      "loc": "kernel/watchdog.c:125",
      "file": "kernel/watchdog.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog.c:lockup_detector_reconfigure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580568160,
      "name": "watchdog_nmi_stop",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 11
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
void watchdog_nmi_stop()
```

```json
{
  "name": "watchdog_nmi_stop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580556032,
      "name": "watchdog_nmi_stop",
      "external": true,
      "loc": "kernel/watchdog.c:123",
      "file": "kernel/watchdog.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog.c:lockup_detector_reconfigure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580556032,
      "name": "watchdog_nmi_stop",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 11
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
void watchdog_nmi_stop()
```

```json
{
  "name": "watchdog_nmi_stop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580559344,
      "name": "watchdog_nmi_stop",
      "external": true,
      "loc": "kernel/watchdog.c:123",
      "file": "kernel/watchdog.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog.c:lockup_detector_reconfigure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580559344,
      "name": "watchdog_nmi_stop",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 11
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void watchdog_nmi_stop()
```

```json
{
  "name": "watchdog_nmi_stop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580729264,
      "name": "watchdog_nmi_stop",
      "external": true,
      "loc": "kernel/watchdog.c:123",
      "file": "kernel/watchdog.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog.c:lockup_detector_reconfigure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580729264,
      "name": "watchdog_nmi_stop",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 11
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void watchdog_nmi_stop()
```

```json
{
  "name": "watchdog_nmi_stop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580941680,
      "name": "watchdog_nmi_stop",
      "external": true,
      "loc": "kernel/watchdog.c:123",
      "file": "kernel/watchdog.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog.c:__lockup_detector_reconfigure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580941680,
      "name": "watchdog_nmi_stop",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 15
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void watchdog_nmi_stop()
```

```json
{
  "name": "watchdog_nmi_stop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581235216,
      "name": "watchdog_nmi_stop",
      "external": true,
      "loc": "kernel/watchdog.c:123",
      "file": "kernel/watchdog.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog.c:__lockup_detector_reconfigure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581235216,
      "name": "watchdog_nmi_stop",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 15
    }
  ]
}
```
</details>
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void watchdog_nmi_stop()
```

```json
{
  "name": "watchdog_nmi_stop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491759448,
      "name": "watchdog_nmi_stop",
      "external": true,
      "loc": "kernel/watchdog.c:130",
      "file": "kernel/watchdog.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog.c:lockup_detector_reconfigure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491759448,
      "name": "watchdog_nmi_stop",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void watchdog_nmi_stop()
```

```json
{
  "name": "watchdog_nmi_stop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225707856,
      "name": "watchdog_nmi_stop",
      "external": true,
      "loc": "kernel/watchdog.c:130",
      "file": "kernel/watchdog.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog.c:lockup_detector_reconfigure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225707856,
      "name": "watchdog_nmi_stop",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void watchdog_nmi_stop()
```

```json
{
  "name": "watchdog_nmi_stop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055282392688,
      "name": "watchdog_nmi_stop",
      "external": true,
      "loc": "arch/powerpc/kernel/watchdog.c:398",
      "file": "arch/powerpc/kernel/watchdog.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog.c:lockup_detector_reconfigure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055282392688,
      "name": "watchdog_nmi_stop",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void watchdog_nmi_stop()
```

```json
{
  "name": "watchdog_nmi_stop",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272080630,
      "name": "watchdog_nmi_stop",
      "external": true,
      "loc": "kernel/watchdog.c:130",
      "file": "kernel/watchdog.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog.c:lockup_detector_reconfigure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272080630,
      "name": "watchdog_nmi_stop",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 26
    }
  ]
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
void watchdog_nmi_stop()
```

```json
{
  "name": "watchdog_nmi_stop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580452096,
      "name": "watchdog_nmi_stop",
      "external": true,
      "loc": "kernel/watchdog.c:130",
      "file": "kernel/watchdog.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog.c:lockup_detector_reconfigure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580452096,
      "name": "watchdog_nmi_stop",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 11
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
void watchdog_nmi_stop()
```

```json
{
  "name": "watchdog_nmi_stop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580399168,
      "name": "watchdog_nmi_stop",
      "external": true,
      "loc": "kernel/watchdog.c:130",
      "file": "kernel/watchdog.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog.c:lockup_detector_reconfigure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580399168,
      "name": "watchdog_nmi_stop",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 11
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
void watchdog_nmi_stop()
```

```json
{
  "name": "watchdog_nmi_stop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580443344,
      "name": "watchdog_nmi_stop",
      "external": true,
      "loc": "kernel/watchdog.c:130",
      "file": "kernel/watchdog.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog.c:lockup_detector_reconfigure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580443344,
      "name": "watchdog_nmi_stop",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 11
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
void watchdog_nmi_stop()
```

```json
{
  "name": "watchdog_nmi_stop",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580498976,
      "name": "watchdog_nmi_stop",
      "external": true,
      "loc": "kernel/watchdog.c:130",
      "file": "kernel/watchdog.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/watchdog.c:lockup_detector_reconfigure"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580498976,
      "name": "watchdog_nmi_stop",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 11
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
void watchdog_nmi_stop()
```
</details>
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
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
void watchdog_nmi_stop()
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
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
