# Function: <code>msr_read</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int msr_read(u32 msr, struct msr * m)
```

```json
{
  "name": "msr_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583152720,
      "name": "msr_read",
      "external": true,
      "loc": "arch/x86/lib/msr.c:35",
      "file": "arch/x86/lib/msr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr.c:msr_set_bit",
        "arch/x86/lib/msr.c:msr_clear_bit"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583152720,
      "name": "msr_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
int msr_read(u32 msr, struct msr * m)
```

```json
{
  "name": "msr_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583449319,
      "name": "msr_read",
      "external": true,
      "loc": "arch/x86/lib/msr.c:38",
      "file": "arch/x86/lib/msr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr.c:msr_clear_bit",
        "arch/x86/lib/msr.c:msr_set_bit"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583448992,
      "name": "msr_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
int msr_read(u32 msr, struct msr * m)
```

```json
{
  "name": "msr_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583576967,
      "name": "msr_read",
      "external": true,
      "loc": "arch/x86/lib/msr.c:38",
      "file": "arch/x86/lib/msr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr.c:msr_clear_bit",
        "arch/x86/lib/msr.c:msr_set_bit"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583576640,
      "name": "msr_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
int msr_read(u32 msr, struct msr * m)
```

```json
{
  "name": "msr_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583615687,
      "name": "msr_read",
      "external": true,
      "loc": "arch/x86/lib/msr.c:38",
      "file": "arch/x86/lib/msr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr.c:msr_clear_bit",
        "arch/x86/lib/msr.c:msr_set_bit"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583615360,
      "name": "msr_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
int msr_read(u32 msr, struct msr * m)
```

```json
{
  "name": "msr_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583861360,
      "name": "msr_read",
      "external": true,
      "loc": "arch/x86/lib/msr.c:39",
      "file": "arch/x86/lib/msr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/lib/msr.c:msr_clear_bit",
        "arch/x86/lib/msr.c:msr_set_bit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583861360,
      "name": "msr_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
int msr_read(u32 msr, struct msr * m)
```

```json
{
  "name": "msr_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584061952,
      "name": "msr_read",
      "external": true,
      "loc": "arch/x86/lib/msr.c:39",
      "file": "arch/x86/lib/msr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/lib/msr.c:msr_clear_bit",
        "arch/x86/lib/msr.c:msr_set_bit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584061952,
      "name": "msr_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
int msr_read(u32 msr, struct msr * m)
```

```json
{
  "name": "msr_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584146080,
      "name": "msr_read",
      "external": true,
      "loc": "arch/x86/lib/msr.c:39",
      "file": "arch/x86/lib/msr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/lib/msr.c:msr_clear_bit",
        "arch/x86/lib/msr.c:msr_set_bit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584146080,
      "name": "msr_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
int msr_read(u32 msr, struct msr * m)
```

```json
{
  "name": "msr_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584336144,
      "name": "msr_read",
      "external": true,
      "loc": "arch/x86/lib/msr.c:39",
      "file": "arch/x86/lib/msr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/lib/msr.c:msr_clear_bit",
        "arch/x86/lib/msr.c:msr_set_bit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584336144,
      "name": "msr_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
int msr_read(u32 msr, struct msr * m)
```

```json
{
  "name": "msr_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584470816,
      "name": "msr_read",
      "external": true,
      "loc": "arch/x86/lib/msr.c:39",
      "file": "arch/x86/lib/msr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/lib/msr.c:msr_clear_bit",
        "arch/x86/lib/msr.c:msr_set_bit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584470816,
      "name": "msr_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
int msr_read(u32 msr, struct msr * m)
```

```json
{
  "name": "msr_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585034656,
      "name": "msr_read",
      "external": true,
      "loc": "arch/x86/lib/msr.c:39",
      "file": "arch/x86/lib/msr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/lib/msr.c:msr_clear_bit",
        "arch/x86/lib/msr.c:msr_set_bit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585034656,
      "name": "msr_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
int msr_read(u32 msr, struct msr * m)
```

```json
{
  "name": "msr_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585186736,
      "name": "msr_read",
      "external": true,
      "loc": "arch/x86/lib/msr.c:39",
      "file": "arch/x86/lib/msr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/lib/msr.c:msr_clear_bit",
        "arch/x86/lib/msr.c:msr_set_bit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585186736,
      "name": "msr_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
int msr_read(u32 msr, struct msr * m)
```

```json
{
  "name": "msr_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585067792,
      "name": "msr_read",
      "external": false,
      "loc": "arch/x86/lib/msr.c:39",
      "file": "arch/x86/lib/msr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/lib/msr.c:msr_clear_bit",
        "arch/x86/lib/msr.c:msr_set_bit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585067792,
      "name": "msr_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
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
int msr_read(u32 msr, struct msr * m)
```

```json
{
  "name": "msr_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585514528,
      "name": "msr_read",
      "external": false,
      "loc": "arch/x86/lib/msr.c:39",
      "file": "arch/x86/lib/msr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/lib/msr.c:msr_clear_bit",
        "arch/x86/lib/msr.c:msr_set_bit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585514528,
      "name": "msr_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
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
int msr_read(u32 msr, struct msr * m)
```

```json
{
  "name": "msr_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586665648,
      "name": "msr_read",
      "external": false,
      "loc": "arch/x86/lib/msr.c:39",
      "file": "arch/x86/lib/msr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/lib/msr.c:msr_clear_bit",
        "arch/x86/lib/msr.c:msr_set_bit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586665648,
      "name": "msr_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
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
int msr_read(u32 msr, struct msr * m)
```

```json
{
  "name": "msr_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587913936,
      "name": "msr_read",
      "external": false,
      "loc": "arch/x86/lib/msr.c:39",
      "file": "arch/x86/lib/msr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/lib/msr.c:msr_clear_bit",
        "arch/x86/lib/msr.c:msr_set_bit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587913936,
      "name": "msr_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
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
int msr_read(u32 msr, struct msr * m)
```

```json
{
  "name": "msr_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588187904,
      "name": "msr_read",
      "external": false,
      "loc": "arch/x86/lib/msr.c:39",
      "file": "arch/x86/lib/msr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/lib/msr.c:msr_clear_bit",
        "arch/x86/lib/msr.c:msr_set_bit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588187904,
      "name": "msr_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
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
int msr_read(u32 msr, struct msr * m)
```

```json
{
  "name": "msr_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588479904,
      "name": "msr_read",
      "external": false,
      "loc": "arch/x86/lib/msr.c:39",
      "file": "arch/x86/lib/msr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/lib/msr.c:msr_clear_bit",
        "arch/x86/lib/msr.c:msr_set_bit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588479904,
      "name": "msr_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
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
int msr_read(u32 msr, struct msr * m)
```

```json
{
  "name": "msr_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584439568,
      "name": "msr_read",
      "external": true,
      "loc": "arch/x86/lib/msr.c:39",
      "file": "arch/x86/lib/msr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/lib/msr.c:msr_clear_bit",
        "arch/x86/lib/msr.c:msr_set_bit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584439568,
      "name": "msr_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
int msr_read(u32 msr, struct msr * m)
```

```json
{
  "name": "msr_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584375397,
      "name": "msr_read",
      "external": true,
      "loc": "arch/x86/lib/msr.c:39",
      "file": "arch/x86/lib/msr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr.c:msr_clear_bit",
        "arch/x86/lib/msr.c:msr_set_bit"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584374736,
      "name": "msr_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
int msr_read(u32 msr, struct msr * m)
```

```json
{
  "name": "msr_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584422480,
      "name": "msr_read",
      "external": true,
      "loc": "arch/x86/lib/msr.c:39",
      "file": "arch/x86/lib/msr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/lib/msr.c:msr_clear_bit",
        "arch/x86/lib/msr.c:msr_set_bit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584422480,
      "name": "msr_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
int msr_read(u32 msr, struct msr * m)
```

```json
{
  "name": "msr_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584528608,
      "name": "msr_read",
      "external": true,
      "loc": "arch/x86/lib/msr.c:39",
      "file": "arch/x86/lib/msr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/lib/msr.c:msr_clear_bit",
        "arch/x86/lib/msr.c:msr_set_bit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584528608,
      "name": "msr_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
int msr_read(u32 msr, struct msr * m)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int msr_read(u32 msr, struct msr * m)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int msr_read(u32 msr, struct msr * m)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int msr_read(u32 msr, struct msr * m)
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
