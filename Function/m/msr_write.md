# Function: <code>msr_write</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int msr_write(u32 msr, struct msr * m)
```

```json
{
  "name": "msr_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583152816,
      "name": "msr_write",
      "external": true,
      "loc": "arch/x86/lib/msr.c:53",
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
      "addr": 18446744071583152816,
      "name": "msr_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
int msr_write(u32 msr, struct msr * m)
```

```json
{
  "name": "msr_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583449395,
      "name": "msr_write",
      "external": true,
      "loc": "arch/x86/lib/msr.c:56",
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
      "addr": 18446744071583449088,
      "name": "msr_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
int msr_write(u32 msr, struct msr * m)
```

```json
{
  "name": "msr_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583577043,
      "name": "msr_write",
      "external": true,
      "loc": "arch/x86/lib/msr.c:56",
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
      "addr": 18446744071583576736,
      "name": "msr_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
int msr_write(u32 msr, struct msr * m)
```

```json
{
  "name": "msr_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583615763,
      "name": "msr_write",
      "external": true,
      "loc": "arch/x86/lib/msr.c:56",
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
      "addr": 18446744071583615456,
      "name": "msr_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
int msr_write(u32 msr, struct msr * m)
```

```json
{
  "name": "msr_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583861456,
      "name": "msr_write",
      "external": true,
      "loc": "arch/x86/lib/msr.c:57",
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
      "addr": 18446744071583861456,
      "name": "msr_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
int msr_write(u32 msr, struct msr * m)
```

```json
{
  "name": "msr_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584062048,
      "name": "msr_write",
      "external": true,
      "loc": "arch/x86/lib/msr.c:57",
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
      "addr": 18446744071584062048,
      "name": "msr_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
int msr_write(u32 msr, struct msr * m)
```

```json
{
  "name": "msr_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584146176,
      "name": "msr_write",
      "external": true,
      "loc": "arch/x86/lib/msr.c:57",
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
      "addr": 18446744071584146176,
      "name": "msr_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
int msr_write(u32 msr, struct msr * m)
```

```json
{
  "name": "msr_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584336240,
      "name": "msr_write",
      "external": true,
      "loc": "arch/x86/lib/msr.c:57",
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
      "addr": 18446744071584336240,
      "name": "msr_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
int msr_write(u32 msr, struct msr * m)
```

```json
{
  "name": "msr_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584470912,
      "name": "msr_write",
      "external": true,
      "loc": "arch/x86/lib/msr.c:57",
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
      "addr": 18446744071584470912,
      "name": "msr_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
int msr_write(u32 msr, struct msr * m)
```

```json
{
  "name": "msr_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585034999,
      "name": "msr_write",
      "external": true,
      "loc": "arch/x86/lib/msr.c:57",
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
      "addr": 18446744071585034752,
      "name": "msr_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
int msr_write(u32 msr, struct msr * m)
```

```json
{
  "name": "msr_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585187079,
      "name": "msr_write",
      "external": true,
      "loc": "arch/x86/lib/msr.c:57",
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
      "addr": 18446744071585186832,
      "name": "msr_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "msr_write",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585068967,
      "name": "msr_write",
      "external": false,
      "loc": "arch/x86/lib/msr.c:57",
      "file": "arch/x86/lib/msr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr.c:msr_clear_bit",
        "arch/x86/lib/msr.c:msr_set_bit"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "msr_write",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585515703,
      "name": "msr_write",
      "external": false,
      "loc": "arch/x86/lib/msr.c:57",
      "file": "arch/x86/lib/msr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr.c:msr_clear_bit",
        "arch/x86/lib/msr.c:msr_set_bit"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "msr_write",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586667179,
      "name": "msr_write",
      "external": false,
      "loc": "arch/x86/lib/msr.c:57",
      "file": "arch/x86/lib/msr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr.c:msr_clear_bit",
        "arch/x86/lib/msr.c:msr_set_bit"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "msr_write",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587915659,
      "name": "msr_write",
      "external": false,
      "loc": "arch/x86/lib/msr.c:57",
      "file": "arch/x86/lib/msr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr.c:msr_clear_bit",
        "arch/x86/lib/msr.c:msr_set_bit"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "msr_write",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588189691,
      "name": "msr_write",
      "external": false,
      "loc": "arch/x86/lib/msr.c:59",
      "file": "arch/x86/lib/msr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr.c:msr_clear_bit",
        "arch/x86/lib/msr.c:msr_set_bit"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "msr_write",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588481691,
      "name": "msr_write",
      "external": false,
      "loc": "arch/x86/lib/msr.c:59",
      "file": "arch/x86/lib/msr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/lib/msr.c:msr_clear_bit",
        "arch/x86/lib/msr.c:msr_set_bit"
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
int msr_write(u32 msr, struct msr * m)
```

```json
{
  "name": "msr_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584439664,
      "name": "msr_write",
      "external": true,
      "loc": "arch/x86/lib/msr.c:57",
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
      "addr": 18446744071584439664,
      "name": "msr_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
int msr_write(u32 msr, struct msr * m)
```

```json
{
  "name": "msr_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584375437,
      "name": "msr_write",
      "external": true,
      "loc": "arch/x86/lib/msr.c:57",
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
      "addr": 18446744071584374896,
      "name": "msr_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
int msr_write(u32 msr, struct msr * m)
```

```json
{
  "name": "msr_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584422576,
      "name": "msr_write",
      "external": true,
      "loc": "arch/x86/lib/msr.c:57",
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
      "addr": 18446744071584422576,
      "name": "msr_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
int msr_write(u32 msr, struct msr * m)
```

```json
{
  "name": "msr_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584528704,
      "name": "msr_write",
      "external": true,
      "loc": "arch/x86/lib/msr.c:57",
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
      "addr": 18446744071584528704,
      "name": "msr_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
int msr_write(u32 msr, struct msr * m)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int msr_write(u32 msr, struct msr * m)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int msr_write(u32 msr, struct msr * m)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int msr_write(u32 msr, struct msr * m)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int msr_write(u32 msr, struct msr * m)
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
