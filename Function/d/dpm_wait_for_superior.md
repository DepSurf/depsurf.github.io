# Function: <code>dpm_wait_for_superior</code>

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
  "name": "dpm_wait_for_superior",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584980485,
      "name": "dpm_wait_for_superior",
      "external": false,
      "loc": "drivers/base/power/main.c:270",
      "file": "drivers/base/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:device_resume",
        "drivers/base/power/main.c:device_resume_early",
        "drivers/base/power/main.c:device_resume_noirq"
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
  "name": "dpm_wait_for_superior",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585064965,
      "name": "dpm_wait_for_superior",
      "external": false,
      "loc": "drivers/base/power/main.c:272",
      "file": "drivers/base/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:device_resume",
        "drivers/base/power/main.c:device_resume_early",
        "drivers/base/power/main.c:device_resume_noirq"
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
  "name": "dpm_wait_for_superior",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585487477,
      "name": "dpm_wait_for_superior",
      "external": false,
      "loc": "drivers/base/power/main.c:272",
      "file": "drivers/base/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:device_resume",
        "drivers/base/power/main.c:device_resume_early",
        "drivers/base/power/main.c:device_resume_noirq"
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
  "name": "dpm_wait_for_superior",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585731752,
      "name": "dpm_wait_for_superior",
      "external": false,
      "loc": "drivers/base/power/main.c:268",
      "file": "drivers/base/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:device_resume",
        "drivers/base/power/main.c:device_resume_early",
        "drivers/base/power/main.c:device_resume_noirq"
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
  "name": "dpm_wait_for_superior",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585864344,
      "name": "dpm_wait_for_superior",
      "external": false,
      "loc": "drivers/base/power/main.c:269",
      "file": "drivers/base/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:device_resume",
        "drivers/base/power/main.c:device_resume_early",
        "drivers/base/power/main.c:device_resume_noirq"
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
  "name": "dpm_wait_for_superior",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586101480,
      "name": "dpm_wait_for_superior",
      "external": false,
      "loc": "drivers/base/power/main.c:276",
      "file": "drivers/base/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:device_resume",
        "drivers/base/power/main.c:device_resume_early",
        "drivers/base/power/main.c:device_resume_noirq"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool dpm_wait_for_superior(struct device * dev, bool async)
```

```json
{
  "name": "dpm_wait_for_superior",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586247776,
      "name": "dpm_wait_for_superior",
      "external": false,
      "loc": "drivers/base/power/main.c:276",
      "file": "drivers/base/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:device_resume",
        "drivers/base/power/main.c:device_resume_early",
        "drivers/base/power/main.c:device_resume_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586247776,
      "name": "dpm_wait_for_superior",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
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
bool dpm_wait_for_superior(struct device * dev, bool async)
```

```json
{
  "name": "dpm_wait_for_superior",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587016784,
      "name": "dpm_wait_for_superior",
      "external": false,
      "loc": "drivers/base/power/main.c:280",
      "file": "drivers/base/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:device_resume",
        "drivers/base/power/main.c:device_resume_early",
        "drivers/base/power/main.c:device_resume_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587016784,
      "name": "dpm_wait_for_superior",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 329
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
bool dpm_wait_for_superior(struct device * dev, bool async)
```

```json
{
  "name": "dpm_wait_for_superior",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587101408,
      "name": "dpm_wait_for_superior",
      "external": false,
      "loc": "drivers/base/power/main.c:280",
      "file": "drivers/base/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:device_resume",
        "drivers/base/power/main.c:device_resume_early",
        "drivers/base/power/main.c:device_resume_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587101408,
      "name": "dpm_wait_for_superior",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 332
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
bool dpm_wait_for_superior(struct device * dev, bool async)
```

```json
{
  "name": "dpm_wait_for_superior",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586987712,
      "name": "dpm_wait_for_superior",
      "external": false,
      "loc": "drivers/base/power/main.c:281",
      "file": "drivers/base/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:device_resume",
        "drivers/base/power/main.c:device_resume_early",
        "drivers/base/power/main.c:device_resume_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586987712,
      "name": "dpm_wait_for_superior",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 332
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
bool dpm_wait_for_superior(struct device * dev, bool async)
```

```json
{
  "name": "dpm_wait_for_superior",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587553936,
      "name": "dpm_wait_for_superior",
      "external": false,
      "loc": "drivers/base/power/main.c:278",
      "file": "drivers/base/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:device_resume",
        "drivers/base/power/main.c:device_resume_early",
        "drivers/base/power/main.c:device_resume_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587553936,
      "name": "dpm_wait_for_superior",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 332
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
bool dpm_wait_for_superior(struct device * dev, bool async)
```

```json
{
  "name": "dpm_wait_for_superior",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588888032,
      "name": "dpm_wait_for_superior",
      "external": false,
      "loc": "drivers/base/power/main.c:277",
      "file": "drivers/base/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:device_resume",
        "drivers/base/power/main.c:device_resume_early",
        "drivers/base/power/main.c:device_resume_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588888032,
      "name": "dpm_wait_for_superior",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 347
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
bool dpm_wait_for_superior(struct device * dev, bool async)
```

```json
{
  "name": "dpm_wait_for_superior",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590397760,
      "name": "dpm_wait_for_superior",
      "external": false,
      "loc": "drivers/base/power/main.c:277",
      "file": "drivers/base/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:device_resume",
        "drivers/base/power/main.c:device_resume_early",
        "drivers/base/power/main.c:device_resume_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590397760,
      "name": "dpm_wait_for_superior",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 347
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
bool dpm_wait_for_superior(struct device * dev, bool async)
```

```json
{
  "name": "dpm_wait_for_superior",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590715328,
      "name": "dpm_wait_for_superior",
      "external": false,
      "loc": "drivers/base/power/main.c:277",
      "file": "drivers/base/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:device_resume",
        "drivers/base/power/main.c:device_resume_early",
        "drivers/base/power/main.c:device_resume_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590715328,
      "name": "dpm_wait_for_superior",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 347
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
bool dpm_wait_for_superior(struct device * dev, bool async)
```

```json
{
  "name": "dpm_wait_for_superior",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591077296,
      "name": "dpm_wait_for_superior",
      "external": false,
      "loc": "drivers/base/power/main.c:277",
      "file": "drivers/base/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:device_resume",
        "drivers/base/power/main.c:device_resume_early",
        "drivers/base/power/main.c:device_resume_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591077296,
      "name": "dpm_wait_for_superior",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 347
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
bool dpm_wait_for_superior(struct device * dev, bool async)
```

```json
{
  "name": "dpm_wait_for_superior",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336499067608,
      "name": "dpm_wait_for_superior",
      "external": false,
      "loc": "drivers/base/power/main.c:276",
      "file": "drivers/base/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:device_resume",
        "drivers/base/power/main.c:device_resume_early",
        "drivers/base/power/main.c:device_resume_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499067608,
      "name": "dpm_wait_for_superior",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
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
bool dpm_wait_for_superior(struct device * dev, bool async)
```

```json
{
  "name": "dpm_wait_for_superior",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3231620640,
      "name": "dpm_wait_for_superior",
      "external": false,
      "loc": "drivers/base/power/main.c:276",
      "file": "drivers/base/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:device_resume",
        "drivers/base/power/main.c:device_resume_early",
        "drivers/base/power/main.c:device_resume_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231620640,
      "name": "dpm_wait_for_superior",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 232
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
bool dpm_wait_for_superior(struct device * dev, bool async)
```

```json
{
  "name": "dpm_wait_for_superior",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055292243504,
      "name": "dpm_wait_for_superior",
      "external": false,
      "loc": "drivers/base/power/main.c:276",
      "file": "drivers/base/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:device_resume",
        "drivers/base/power/main.c:device_resume_early",
        "drivers/base/power/main.c:device_resume_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292243504,
      "name": "dpm_wait_for_superior",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 352
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
bool dpm_wait_for_superior(struct device * dev, bool async)
```

```json
{
  "name": "dpm_wait_for_superior",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586009504,
      "name": "dpm_wait_for_superior",
      "external": false,
      "loc": "drivers/base/power/main.c:276",
      "file": "drivers/base/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:device_resume",
        "drivers/base/power/main.c:device_resume_early",
        "drivers/base/power/main.c:device_resume_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586009504,
      "name": "dpm_wait_for_superior",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
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
bool dpm_wait_for_superior(struct device * dev, bool async)
```

```json
{
  "name": "dpm_wait_for_superior",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585857104,
      "name": "dpm_wait_for_superior",
      "external": false,
      "loc": "drivers/base/power/main.c:276",
      "file": "drivers/base/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:device_resume",
        "drivers/base/power/main.c:device_resume_early",
        "drivers/base/power/main.c:device_resume_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585857104,
      "name": "dpm_wait_for_superior",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
bool dpm_wait_for_superior(struct device * dev, bool async)
```

```json
{
  "name": "dpm_wait_for_superior",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586197792,
      "name": "dpm_wait_for_superior",
      "external": false,
      "loc": "drivers/base/power/main.c:276",
      "file": "drivers/base/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:device_resume",
        "drivers/base/power/main.c:device_resume_early",
        "drivers/base/power/main.c:device_resume_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586197792,
      "name": "dpm_wait_for_superior",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
bool dpm_wait_for_superior(struct device * dev, bool async)
```

```json
{
  "name": "dpm_wait_for_superior",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586306464,
      "name": "dpm_wait_for_superior",
      "external": false,
      "loc": "drivers/base/power/main.c:276",
      "file": "drivers/base/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/main.c:device_resume",
        "drivers/base/power/main.c:device_resume_early",
        "drivers/base/power/main.c:device_resume_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586306464,
      "name": "dpm_wait_for_superior",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
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
bool dpm_wait_for_superior(struct device * dev, bool async)
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
bool dpm_wait_for_superior(struct device * dev, bool async)
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
