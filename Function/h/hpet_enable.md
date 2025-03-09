# Function: <code>hpet_enable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int hpet_enable()
```

```json
{
  "name": "hpet_enable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595048793,
      "name": "hpet_enable",
      "external": true,
      "loc": "arch/x86/kernel/hpet.c:817",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/time.c:hpet_time_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595048793,
      "name": "hpet_enable.part.13",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 677
    },
    {
      "addr": 18446744071595049470,
      "name": "hpet_enable",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
int hpet_enable()
```

```json
{
  "name": "hpet_enable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595214738,
      "name": "hpet_enable",
      "external": true,
      "loc": "arch/x86/kernel/hpet.c:811",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/time.c:hpet_time_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595214738,
      "name": "hpet_enable",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 710
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int hpet_enable()
```

```json
{
  "name": "hpet_enable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595457757,
      "name": "hpet_enable",
      "external": true,
      "loc": "arch/x86/kernel/hpet.c:906",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/time.c:hpet_time_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595457757,
      "name": "hpet_enable",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 710
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int hpet_enable()
```

```json
{
  "name": "hpet_enable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596378902,
      "name": "hpet_enable",
      "external": true,
      "loc": "arch/x86/kernel/hpet.c:901",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/time.c:hpet_time_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596378902,
      "name": "hpet_enable",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 714
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int hpet_enable()
```

```json
{
  "name": "hpet_enable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071602697056,
      "name": "hpet_enable",
      "external": true,
      "loc": "arch/x86/kernel/hpet.c:901",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/time.c:hpet_time_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071602697056,
      "name": "hpet_enable",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 714
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
int hpet_enable()
```

```json
{
  "name": "hpet_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071602868543,
      "name": "hpet_enable",
      "external": true,
      "loc": "arch/x86/kernel/hpet.c:902",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/time.c:hpet_time_init",
        "arch/x86/kernel/hpet.c:hpet_late_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071602868543,
      "name": "hpet_enable",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 710
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
int hpet_enable()
```

```json
{
  "name": "hpet_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604665595,
      "name": "hpet_enable",
      "external": true,
      "loc": "arch/x86/kernel/hpet.c:898",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/time.c:hpet_time_init",
        "arch/x86/kernel/hpet.c:hpet_late_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604665595,
      "name": "hpet_enable",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 710
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
int hpet_enable()
```

```json
{
  "name": "hpet_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604763923,
      "name": "hpet_enable",
      "external": true,
      "loc": "arch/x86/kernel/hpet.c:812",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/time.c:hpet_time_init",
        "arch/x86/kernel/hpet.c:hpet_late_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604763923,
      "name": "hpet_enable",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 927
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
int hpet_enable()
```

```json
{
  "name": "hpet_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604789777,
      "name": "hpet_enable",
      "external": true,
      "loc": "arch/x86/kernel/hpet.c:812",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/time.c:hpet_time_init",
        "arch/x86/kernel/hpet.c:hpet_late_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604789777,
      "name": "hpet_enable",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 927
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
int hpet_enable()
```

```json
{
  "name": "hpet_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071609132961,
      "name": "hpet_enable",
      "external": true,
      "loc": "arch/x86/kernel/hpet.c:812",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/time.c:hpet_time_init",
        "arch/x86/kernel/hpet.c:hpet_late_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609132961,
      "name": "hpet_enable",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 696
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
int hpet_enable()
```

```json
{
  "name": "hpet_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071612201534,
      "name": "hpet_enable",
      "external": true,
      "loc": "arch/x86/kernel/hpet.c:922",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/time.c:hpet_time_init",
        "arch/x86/kernel/hpet.c:hpet_late_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612201534,
      "name": "hpet_enable",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 696
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
int hpet_enable()
```

```json
{
  "name": "hpet_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071614342452,
      "name": "hpet_enable",
      "external": true,
      "loc": "arch/x86/kernel/hpet.c:922",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/time.c:hpet_time_init",
        "arch/x86/kernel/hpet.c:hpet_late_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071614342452,
      "name": "hpet_enable",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 942
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
int hpet_enable()
```

```json
{
  "name": "hpet_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071615272497,
      "name": "hpet_enable",
      "external": true,
      "loc": "arch/x86/kernel/hpet.c:1000",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/time.c:hpet_time_init",
        "arch/x86/kernel/hpet.c:hpet_late_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615272497,
      "name": "hpet_enable",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 1233
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
int hpet_enable()
```

```json
{
  "name": "hpet_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071617048613,
      "name": "hpet_enable",
      "external": true,
      "loc": "arch/x86/kernel/hpet.c:1000",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/time.c:hpet_time_init",
        "arch/x86/kernel/hpet.c:hpet_late_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071617048613,
      "name": "hpet_enable",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 1246
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
int hpet_enable()
```

```json
{
  "name": "hpet_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071627691680,
      "name": "hpet_enable",
      "external": true,
      "loc": "arch/x86/kernel/hpet.c:1000",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/time.c:hpet_time_init",
        "arch/x86/kernel/hpet.c:hpet_late_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071627691680,
      "name": "hpet_enable",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 1170
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
int hpet_enable()
```

```json
{
  "name": "hpet_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071619449360,
      "name": "hpet_enable",
      "external": true,
      "loc": "arch/x86/kernel/hpet.c:1000",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/time.c:hpet_time_init",
        "arch/x86/kernel/hpet.c:hpet_late_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071619449360,
      "name": "hpet_enable",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 1187
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
int hpet_enable()
```

```json
{
  "name": "hpet_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071621745376,
      "name": "hpet_enable",
      "external": true,
      "loc": "arch/x86/kernel/hpet.c:1000",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/time.c:hpet_time_init",
        "arch/x86/kernel/hpet.c:hpet_late_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071621745376,
      "name": "hpet_enable",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 1289
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
int hpet_enable()
```

```json
{
  "name": "hpet_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604703719,
      "name": "hpet_enable",
      "external": true,
      "loc": "arch/x86/kernel/hpet.c:812",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/time.c:hpet_time_init",
        "arch/x86/kernel/hpet.c:hpet_late_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604703719,
      "name": "hpet_enable",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 927
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
int hpet_enable()
```

```json
{
  "name": "hpet_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604671123,
      "name": "hpet_enable",
      "external": true,
      "loc": "arch/x86/kernel/hpet.c:812",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/time.c:hpet_time_init",
        "arch/x86/kernel/hpet.c:hpet_late_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604671123,
      "name": "hpet_enable",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 927
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
int hpet_enable()
```

```json
{
  "name": "hpet_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604781286,
      "name": "hpet_enable",
      "external": true,
      "loc": "arch/x86/kernel/hpet.c:812",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/time.c:hpet_time_init",
        "arch/x86/kernel/hpet.c:hpet_late_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604781286,
      "name": "hpet_enable",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 927
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
int hpet_enable()
```

```json
{
  "name": "hpet_enable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604793918,
      "name": "hpet_enable",
      "external": true,
      "loc": "arch/x86/kernel/hpet.c:812",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/time.c:hpet_time_init",
        "arch/x86/kernel/hpet.c:hpet_late_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604793918,
      "name": "hpet_enable",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 927
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int hpet_enable()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int hpet_enable()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int hpet_enable()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int hpet_enable()
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
