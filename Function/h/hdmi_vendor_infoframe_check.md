# Function: <code>hdmi_vendor_infoframe_check</code>

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
int hdmi_vendor_infoframe_check(struct hdmi_vendor_infoframe * frame)
```

```json
{
  "name": "hdmi_vendor_infoframe_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584503328,
      "name": "hdmi_vendor_infoframe_check",
      "external": true,
      "loc": "drivers/video/hdmi.c:545",
      "file": "drivers/video/hdmi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/hdmi.c:hdmi_vendor_any_infoframe_check",
        "drivers/video/hdmi.c:hdmi_vendor_infoframe_pack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584503328,
      "name": "hdmi_vendor_infoframe_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
int hdmi_vendor_infoframe_check(struct hdmi_vendor_infoframe * frame)
```

```json
{
  "name": "hdmi_vendor_infoframe_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584700864,
      "name": "hdmi_vendor_infoframe_check",
      "external": true,
      "loc": "drivers/video/hdmi.c:545",
      "file": "drivers/video/hdmi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/hdmi.c:hdmi_vendor_any_infoframe_check",
        "drivers/video/hdmi.c:hdmi_vendor_infoframe_pack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584700864,
      "name": "hdmi_vendor_infoframe_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
int hdmi_vendor_infoframe_check(struct hdmi_vendor_infoframe * frame)
```

```json
{
  "name": "hdmi_vendor_infoframe_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584836672,
      "name": "hdmi_vendor_infoframe_check",
      "external": true,
      "loc": "drivers/video/hdmi.c:545",
      "file": "drivers/video/hdmi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/hdmi.c:hdmi_vendor_any_infoframe_check",
        "drivers/video/hdmi.c:hdmi_vendor_infoframe_pack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584836672,
      "name": "hdmi_vendor_infoframe_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
int hdmi_vendor_infoframe_check(struct hdmi_vendor_infoframe * frame)
```

```json
{
  "name": "hdmi_vendor_infoframe_check",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585535125,
      "name": "hdmi_vendor_infoframe_check",
      "external": true,
      "loc": "drivers/video/hdmi.c:541",
      "file": "drivers/video/hdmi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/video/hdmi.c:hdmi_vendor_infoframe_pack"
      ],
      "caller_func": [
        "drivers/video/hdmi.c:hdmi_infoframe_pack",
        "drivers/video/hdmi.c:hdmi_infoframe_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585534800,
      "name": "hdmi_vendor_infoframe_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
int hdmi_vendor_infoframe_check(struct hdmi_vendor_infoframe * frame)
```

```json
{
  "name": "hdmi_vendor_infoframe_check",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585671317,
      "name": "hdmi_vendor_infoframe_check",
      "external": true,
      "loc": "drivers/video/hdmi.c:545",
      "file": "drivers/video/hdmi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/video/hdmi.c:hdmi_vendor_infoframe_pack"
      ],
      "caller_func": [
        "drivers/video/hdmi.c:hdmi_infoframe_pack",
        "drivers/video/hdmi.c:hdmi_infoframe_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585670992,
      "name": "hdmi_vendor_infoframe_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
int hdmi_vendor_infoframe_check(struct hdmi_vendor_infoframe * frame)
```

```json
{
  "name": "hdmi_vendor_infoframe_check",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585552085,
      "name": "hdmi_vendor_infoframe_check",
      "external": true,
      "loc": "drivers/video/hdmi.c:545",
      "file": "drivers/video/hdmi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/video/hdmi.c:hdmi_vendor_infoframe_pack"
      ],
      "caller_func": [
        "drivers/video/hdmi.c:hdmi_infoframe_pack",
        "drivers/video/hdmi.c:hdmi_infoframe_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585551568,
      "name": "hdmi_vendor_infoframe_check",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int hdmi_vendor_infoframe_check(struct hdmi_vendor_infoframe * frame)
```

```json
{
  "name": "hdmi_vendor_infoframe_check",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586023125,
      "name": "hdmi_vendor_infoframe_check",
      "external": true,
      "loc": "drivers/video/hdmi.c:545",
      "file": "drivers/video/hdmi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/video/hdmi.c:hdmi_vendor_infoframe_pack"
      ],
      "caller_func": [
        "drivers/video/hdmi.c:hdmi_infoframe_pack",
        "drivers/video/hdmi.c:hdmi_infoframe_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586022608,
      "name": "hdmi_vendor_infoframe_check",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int hdmi_vendor_infoframe_check(struct hdmi_vendor_infoframe * frame)
```

```json
{
  "name": "hdmi_vendor_infoframe_check",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587243973,
      "name": "hdmi_vendor_infoframe_check",
      "external": true,
      "loc": "drivers/video/hdmi.c:545",
      "file": "drivers/video/hdmi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/video/hdmi.c:hdmi_vendor_infoframe_pack"
      ],
      "caller_func": [
        "drivers/video/hdmi.c:hdmi_infoframe_pack",
        "drivers/video/hdmi.c:hdmi_infoframe_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587243616,
      "name": "hdmi_vendor_infoframe_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
int hdmi_vendor_infoframe_check(struct hdmi_vendor_infoframe * frame)
```

```json
{
  "name": "hdmi_vendor_infoframe_check",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588480325,
      "name": "hdmi_vendor_infoframe_check",
      "external": true,
      "loc": "drivers/video/hdmi.c:589",
      "file": "drivers/video/hdmi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/video/hdmi.c:hdmi_vendor_infoframe_pack"
      ],
      "caller_func": [
        "drivers/video/hdmi.c:hdmi_infoframe_pack",
        "drivers/video/hdmi.c:hdmi_infoframe_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588479936,
      "name": "hdmi_vendor_infoframe_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
int hdmi_vendor_infoframe_check(struct hdmi_vendor_infoframe * frame)
```

```json
{
  "name": "hdmi_vendor_infoframe_check",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588759957,
      "name": "hdmi_vendor_infoframe_check",
      "external": true,
      "loc": "drivers/video/hdmi.c:589",
      "file": "drivers/video/hdmi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/video/hdmi.c:hdmi_vendor_infoframe_pack"
      ],
      "caller_func": [
        "drivers/video/hdmi.c:hdmi_infoframe_pack",
        "drivers/video/hdmi.c:hdmi_infoframe_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588759568,
      "name": "hdmi_vendor_infoframe_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
int hdmi_vendor_infoframe_check(struct hdmi_vendor_infoframe * frame)
```

```json
{
  "name": "hdmi_vendor_infoframe_check",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589063173,
      "name": "hdmi_vendor_infoframe_check",
      "external": true,
      "loc": "drivers/video/hdmi.c:589",
      "file": "drivers/video/hdmi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/video/hdmi.c:hdmi_vendor_infoframe_pack"
      ],
      "caller_func": [
        "drivers/video/hdmi.c:hdmi_infoframe_pack",
        "drivers/video/hdmi.c:hdmi_infoframe_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589062784,
      "name": "hdmi_vendor_infoframe_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
int hdmi_vendor_infoframe_check(struct hdmi_vendor_infoframe * frame)
```

```json
{
  "name": "hdmi_vendor_infoframe_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497231096,
      "name": "hdmi_vendor_infoframe_check",
      "external": true,
      "loc": "drivers/video/hdmi.c:545",
      "file": "drivers/video/hdmi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/hdmi.c:hdmi_vendor_any_infoframe_check",
        "drivers/video/hdmi.c:hdmi_vendor_infoframe_pack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497231096,
      "name": "hdmi_vendor_infoframe_check",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int hdmi_vendor_infoframe_check(struct hdmi_vendor_infoframe * frame)
```

```json
{
  "name": "hdmi_vendor_infoframe_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230417564,
      "name": "hdmi_vendor_infoframe_check",
      "external": true,
      "loc": "drivers/video/hdmi.c:545",
      "file": "drivers/video/hdmi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/hdmi.c:hdmi_vendor_any_infoframe_check",
        "drivers/video/hdmi.c:hdmi_vendor_infoframe_pack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230417564,
      "name": "hdmi_vendor_infoframe_check",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int hdmi_vendor_infoframe_check(struct hdmi_vendor_infoframe * frame)
```

```json
{
  "name": "hdmi_vendor_infoframe_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291179104,
      "name": "hdmi_vendor_infoframe_check",
      "external": true,
      "loc": "drivers/video/hdmi.c:545",
      "file": "drivers/video/hdmi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/hdmi.c:hdmi_vendor_any_infoframe_check",
        "drivers/video/hdmi.c:hdmi_vendor_infoframe_pack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291179104,
      "name": "hdmi_vendor_infoframe_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
int hdmi_vendor_infoframe_check(struct hdmi_vendor_infoframe * frame)
```

```json
{
  "name": "hdmi_vendor_infoframe_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275769824,
      "name": "hdmi_vendor_infoframe_check",
      "external": true,
      "loc": "drivers/video/hdmi.c:545",
      "file": "drivers/video/hdmi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/hdmi.c:hdmi_vendor_any_infoframe_check",
        "drivers/video/hdmi.c:hdmi_vendor_infoframe_pack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275769824,
      "name": "hdmi_vendor_infoframe_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
int hdmi_vendor_infoframe_check(struct hdmi_vendor_infoframe * frame)
```

```json
{
  "name": "hdmi_vendor_infoframe_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584788144,
      "name": "hdmi_vendor_infoframe_check",
      "external": true,
      "loc": "drivers/video/hdmi.c:545",
      "file": "drivers/video/hdmi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/hdmi.c:hdmi_vendor_any_infoframe_check",
        "drivers/video/hdmi.c:hdmi_vendor_infoframe_pack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584788144,
      "name": "hdmi_vendor_infoframe_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
int hdmi_vendor_infoframe_check(struct hdmi_vendor_infoframe * frame)
```

```json
{
  "name": "hdmi_vendor_infoframe_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584718928,
      "name": "hdmi_vendor_infoframe_check",
      "external": true,
      "loc": "drivers/video/hdmi.c:545",
      "file": "drivers/video/hdmi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/hdmi.c:hdmi_vendor_any_infoframe_check",
        "drivers/video/hdmi.c:hdmi_vendor_infoframe_pack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584718928,
      "name": "hdmi_vendor_infoframe_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
int hdmi_vendor_infoframe_check(struct hdmi_vendor_infoframe * frame)
```

```json
{
  "name": "hdmi_vendor_infoframe_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584789568,
      "name": "hdmi_vendor_infoframe_check",
      "external": true,
      "loc": "drivers/video/hdmi.c:545",
      "file": "drivers/video/hdmi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/hdmi.c:hdmi_vendor_any_infoframe_check",
        "drivers/video/hdmi.c:hdmi_vendor_infoframe_pack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584789568,
      "name": "hdmi_vendor_infoframe_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
int hdmi_vendor_infoframe_check(struct hdmi_vendor_infoframe * frame)
```

```json
{
  "name": "hdmi_vendor_infoframe_check",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584894416,
      "name": "hdmi_vendor_infoframe_check",
      "external": true,
      "loc": "drivers/video/hdmi.c:545",
      "file": "drivers/video/hdmi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/hdmi.c:hdmi_vendor_any_infoframe_check",
        "drivers/video/hdmi.c:hdmi_vendor_infoframe_pack"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584894416,
      "name": "hdmi_vendor_infoframe_check",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
int hdmi_vendor_infoframe_check(struct hdmi_vendor_infoframe * frame)
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
