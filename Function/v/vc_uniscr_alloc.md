# Function: <code>vc_uniscr_alloc</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct uni_screen * vc_uniscr_alloc(unsigned int cols, unsigned int rows)
```

```json
{
  "name": "vc_uniscr_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585413584,
      "name": "vc_uniscr_alloc",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:348",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:vc_uniscr_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585413584,
      "name": "vc_uniscr_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
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
struct uni_screen * vc_uniscr_alloc(unsigned int cols, unsigned int rows)
```

```json
{
  "name": "vc_uniscr_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585637984,
      "name": "vc_uniscr_alloc",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:348",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:vc_uniscr_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585637984,
      "name": "vc_uniscr_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
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
struct uni_screen * vc_uniscr_alloc(unsigned int cols, unsigned int rows)
```

```json
{
  "name": "vc_uniscr_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585779280,
      "name": "vc_uniscr_alloc",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:348",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:vc_uniscr_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585779280,
      "name": "vc_uniscr_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vc_uniscr_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586510580,
      "name": "vc_uniscr_alloc",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:349",
      "file": "drivers/tty/vt/vt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:vc_uniscr_check"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vc_uniscr_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586625588,
      "name": "vc_uniscr_alloc",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:342",
      "file": "drivers/tty/vt/vt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:vc_uniscr_check"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vc_uniscr_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586506587,
      "name": "vc_uniscr_alloc",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:342",
      "file": "drivers/tty/vt/vt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:vc_uniscr_check"
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
  "name": "vc_uniscr_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587038605,
      "name": "vc_uniscr_alloc",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:338",
      "file": "drivers/tty/vt/vt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:vc_uniscr_check"
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
  "name": "vc_uniscr_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588340795,
      "name": "vc_uniscr_alloc",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:338",
      "file": "drivers/tty/vt/vt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:vc_uniscr_check"
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
  "name": "vc_uniscr_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589762137,
      "name": "vc_uniscr_alloc",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:338",
      "file": "drivers/tty/vt/vt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:vc_uniscr_check"
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
  "name": "vc_uniscr_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590066999,
      "name": "vc_uniscr_alloc",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:328",
      "file": "drivers/tty/vt/vt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:vc_uniscr_check"
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
  "name": "vc_uniscr_alloc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590406167,
      "name": "vc_uniscr_alloc",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:327",
      "file": "drivers/tty/vt/vt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:vc_uniscr_check"
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct uni_screen * vc_uniscr_alloc(unsigned int cols, unsigned int rows)
```

```json
{
  "name": "vc_uniscr_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498491624,
      "name": "vc_uniscr_alloc",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:348",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:vc_uniscr_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498491624,
      "name": "vc_uniscr_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct uni_screen * vc_uniscr_alloc(unsigned int cols, unsigned int rows)
```

```json
{
  "name": "vc_uniscr_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231151224,
      "name": "vc_uniscr_alloc",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:348",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:vc_uniscr_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231151224,
      "name": "vc_uniscr_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
struct uni_screen * vc_uniscr_alloc(unsigned int cols, unsigned int rows)
```

```json
{
  "name": "vc_uniscr_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291689456,
      "name": "vc_uniscr_alloc",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:348",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:vc_uniscr_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291689456,
      "name": "vc_uniscr_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct uni_screen * vc_uniscr_alloc(unsigned int cols, unsigned int rows)
```

```json
{
  "name": "vc_uniscr_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276125786,
      "name": "vc_uniscr_alloc",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:348",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:vc_uniscr_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276125786,
      "name": "vc_uniscr_alloc",
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct uni_screen * vc_uniscr_alloc(unsigned int cols, unsigned int rows)
```

```json
{
  "name": "vc_uniscr_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585540272,
      "name": "vc_uniscr_alloc",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:348",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:vc_uniscr_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585540272,
      "name": "vc_uniscr_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
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
struct uni_screen * vc_uniscr_alloc(unsigned int cols, unsigned int rows)
```

```json
{
  "name": "vc_uniscr_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585410096,
      "name": "vc_uniscr_alloc",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:348",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:vc_uniscr_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585410096,
      "name": "vc_uniscr_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
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
struct uni_screen * vc_uniscr_alloc(unsigned int cols, unsigned int rows)
```

```json
{
  "name": "vc_uniscr_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585729680,
      "name": "vc_uniscr_alloc",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:348",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:vc_uniscr_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585729680,
      "name": "vc_uniscr_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
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
struct uni_screen * vc_uniscr_alloc(unsigned int cols, unsigned int rows)
```

```json
{
  "name": "vc_uniscr_alloc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585837696,
      "name": "vc_uniscr_alloc",
      "external": false,
      "loc": "drivers/tty/vt/vt.c:348",
      "file": "drivers/tty/vt/vt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:vc_uniscr_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585837696,
      "name": "vc_uniscr_alloc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
struct uni_screen * vc_uniscr_alloc(unsigned int cols, unsigned int rows)
```
</details>
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
struct uni_screen * vc_uniscr_alloc(unsigned int cols, unsigned int rows)
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
