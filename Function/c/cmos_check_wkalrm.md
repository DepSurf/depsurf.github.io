# Function: <code>cmos_check_wkalrm</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cmos_check_wkalrm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586218994,
      "name": "cmos_check_wkalrm",
      "external": false,
      "loc": "drivers/rtc/rtc-cmos.c:981",
      "file": "drivers/rtc/rtc-cmos.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/rtc/rtc-cmos.c:cmos_resume"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cmos_check_wkalrm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586308114,
      "name": "cmos_check_wkalrm",
      "external": false,
      "loc": "drivers/rtc/rtc-cmos.c:984",
      "file": "drivers/rtc/rtc-cmos.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/rtc/rtc-cmos.c:cmos_resume"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cmos_check_wkalrm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586771605,
      "name": "cmos_check_wkalrm",
      "external": false,
      "loc": "drivers/rtc/rtc-cmos.c:984",
      "file": "drivers/rtc/rtc-cmos.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/rtc/rtc-cmos.c:cmos_resume"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cmos_check_wkalrm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587044035,
      "name": "cmos_check_wkalrm",
      "external": false,
      "loc": "drivers/rtc/rtc-cmos.c:1014",
      "file": "drivers/rtc/rtc-cmos.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/rtc/rtc-cmos.c:cmos_resume"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cmos_check_wkalrm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587204117,
      "name": "cmos_check_wkalrm",
      "external": false,
      "loc": "drivers/rtc/rtc-cmos.c:1035",
      "file": "drivers/rtc/rtc-cmos.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/rtc/rtc-cmos.c:cmos_resume"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cmos_check_wkalrm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587469362,
      "name": "cmos_check_wkalrm",
      "external": false,
      "loc": "drivers/rtc/rtc-cmos.c:1031",
      "file": "drivers/rtc/rtc-cmos.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/rtc/rtc-cmos.c:cmos_resume"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cmos_check_wkalrm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587672482,
      "name": "cmos_check_wkalrm",
      "external": false,
      "loc": "drivers/rtc/rtc-cmos.c:1031",
      "file": "drivers/rtc/rtc-cmos.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/rtc/rtc-cmos.c:cmos_resume"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void cmos_check_wkalrm(struct device * dev)
```

```json
{
  "name": "cmos_check_wkalrm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588539920,
      "name": "cmos_check_wkalrm",
      "external": false,
      "loc": "drivers/rtc/rtc-cmos.c:1032",
      "file": "drivers/rtc/rtc-cmos.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/rtc-cmos.c:cmos_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588539920,
      "name": "cmos_check_wkalrm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
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
void cmos_check_wkalrm(struct device * dev)
```

```json
{
  "name": "cmos_check_wkalrm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588563312,
      "name": "cmos_check_wkalrm",
      "external": false,
      "loc": "drivers/rtc/rtc-cmos.c:1042",
      "file": "drivers/rtc/rtc-cmos.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/rtc-cmos.c:cmos_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588563312,
      "name": "cmos_check_wkalrm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
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
  "name": "cmos_check_wkalrm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588446689,
      "name": "cmos_check_wkalrm",
      "external": false,
      "loc": "drivers/rtc/rtc-cmos.c:1035",
      "file": "drivers/rtc/rtc-cmos.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/rtc/rtc-cmos.c:cmos_resume"
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
  "name": "cmos_check_wkalrm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589116458,
      "name": "cmos_check_wkalrm",
      "external": false,
      "loc": "drivers/rtc/rtc-cmos.c:1032",
      "file": "drivers/rtc/rtc-cmos.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/rtc/rtc-cmos.c:cmos_resume"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void cmos_check_wkalrm(struct device * dev)
```

```json
{
  "name": "cmos_check_wkalrm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cmos_check_wkalrm",
      "external": false,
      "loc": "drivers/rtc/rtc-cmos.c:1088",
      "file": "drivers/rtc/rtc-cmos.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/rtc-cmos.c:cmos_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590561888,
      "name": "cmos_check_wkalrm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 361
    },
    {
      "addr": 18446744071594512652,
      "name": "cmos_check_wkalrm.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
void cmos_check_wkalrm(struct device * dev)
```

```json
{
  "name": "cmos_check_wkalrm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cmos_check_wkalrm",
      "external": false,
      "loc": "drivers/rtc/rtc-cmos.c:1268",
      "file": "drivers/rtc/rtc-cmos.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/rtc-cmos.c:cmos_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592216256,
      "name": "cmos_check_wkalrm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 365
    },
    {
      "addr": 18446744071596307703,
      "name": "cmos_check_wkalrm.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
void cmos_check_wkalrm(struct device * dev)
```

```json
{
  "name": "cmos_check_wkalrm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cmos_check_wkalrm",
      "external": false,
      "loc": "drivers/rtc/rtc-cmos.c:1268",
      "file": "drivers/rtc/rtc-cmos.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/rtc-cmos.c:cmos_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592640544,
      "name": "cmos_check_wkalrm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 365
    },
    {
      "addr": 18446744071596837114,
      "name": "cmos_check_wkalrm.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
void cmos_check_wkalrm(struct device * dev)
```

```json
{
  "name": "cmos_check_wkalrm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "cmos_check_wkalrm",
      "external": false,
      "loc": "drivers/rtc/rtc-cmos.c:1285",
      "file": "drivers/rtc/rtc-cmos.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/rtc/rtc-cmos.c:cmos_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593385536,
      "name": "cmos_check_wkalrm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 365
    },
    {
      "addr": 18446744071597761164,
      "name": "cmos_check_wkalrm.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cmos_check_wkalrm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587356242,
      "name": "cmos_check_wkalrm",
      "external": false,
      "loc": "drivers/rtc/rtc-cmos.c:1031",
      "file": "drivers/rtc/rtc-cmos.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/rtc/rtc-cmos.c:cmos_resume"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cmos_check_wkalrm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587124482,
      "name": "cmos_check_wkalrm",
      "external": false,
      "loc": "drivers/rtc/rtc-cmos.c:1031",
      "file": "drivers/rtc/rtc-cmos.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/rtc/rtc-cmos.c:cmos_resume"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cmos_check_wkalrm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587623730,
      "name": "cmos_check_wkalrm",
      "external": false,
      "loc": "drivers/rtc/rtc-cmos.c:1031",
      "file": "drivers/rtc/rtc-cmos.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/rtc/rtc-cmos.c:cmos_resume"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cmos_check_wkalrm",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587733938,
      "name": "cmos_check_wkalrm",
      "external": false,
      "loc": "drivers/rtc/rtc-cmos.c:1031",
      "file": "drivers/rtc/rtc-cmos.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/rtc/rtc-cmos.c:cmos_resume"
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void cmos_check_wkalrm(struct device * dev)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
void cmos_check_wkalrm(struct device * dev)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
void cmos_check_wkalrm(struct device * dev)
```
</details>
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
