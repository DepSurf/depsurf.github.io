# Function: <code>dwc2_handle_lpm_intr</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dwc2_handle_lpm_intr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586647482,
      "name": "dwc2_handle_lpm_intr",
      "external": false,
      "loc": "drivers/usb/dwc2/core_intr.c:556",
      "file": "drivers/usb/dwc2/core_intr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr"
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
  "name": "dwc2_handle_lpm_intr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586798310,
      "name": "dwc2_handle_lpm_intr",
      "external": false,
      "loc": "drivers/usb/dwc2/core_intr.c:556",
      "file": "drivers/usb/dwc2/core_intr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr"
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
  "name": "dwc2_handle_lpm_intr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587058925,
      "name": "dwc2_handle_lpm_intr",
      "external": false,
      "loc": "drivers/usb/dwc2/core_intr.c:568",
      "file": "drivers/usb/dwc2/core_intr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr"
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
  "name": "dwc2_handle_lpm_intr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587259293,
      "name": "dwc2_handle_lpm_intr",
      "external": false,
      "loc": "drivers/usb/dwc2/core_intr.c:568",
      "file": "drivers/usb/dwc2/core_intr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void dwc2_handle_lpm_intr(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_handle_lpm_intr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_handle_lpm_intr",
      "external": false,
      "loc": "drivers/usb/dwc2/core_intr.c:566",
      "file": "drivers/usb/dwc2/core_intr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588110608,
      "name": "dwc2_handle_lpm_intr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 427
    },
    {
      "addr": 18446744071588114607,
      "name": "dwc2_handle_lpm_intr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
void dwc2_handle_lpm_intr(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_handle_lpm_intr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_handle_lpm_intr",
      "external": false,
      "loc": "drivers/usb/dwc2/core_intr.c:566",
      "file": "drivers/usb/dwc2/core_intr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588152048,
      "name": "dwc2_handle_lpm_intr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 427
    },
    {
      "addr": 18446744071591554318,
      "name": "dwc2_handle_lpm_intr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
void dwc2_handle_lpm_intr(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_handle_lpm_intr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_handle_lpm_intr",
      "external": false,
      "loc": "drivers/usb/dwc2/core_intr.c:593",
      "file": "drivers/usb/dwc2/core_intr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588032528,
      "name": "dwc2_handle_lpm_intr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 440
    },
    {
      "addr": 18446744071591496478,
      "name": "dwc2_handle_lpm_intr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
void dwc2_handle_lpm_intr(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_handle_lpm_intr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_handle_lpm_intr",
      "external": false,
      "loc": "drivers/usb/dwc2/core_intr.c:593",
      "file": "drivers/usb/dwc2/core_intr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588653904,
      "name": "dwc2_handle_lpm_intr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 581
    },
    {
      "addr": 18446744071592578285,
      "name": "dwc2_handle_lpm_intr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
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
void dwc2_handle_lpm_intr(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_handle_lpm_intr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_handle_lpm_intr",
      "external": false,
      "loc": "drivers/usb/dwc2/core_intr.c:593",
      "file": "drivers/usb/dwc2/core_intr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590070736,
      "name": "dwc2_handle_lpm_intr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 592
    },
    {
      "addr": 18446744071594458770,
      "name": "dwc2_handle_lpm_intr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
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
void dwc2_handle_lpm_intr(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_handle_lpm_intr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_handle_lpm_intr",
      "external": false,
      "loc": "drivers/usb/dwc2/core_intr.c:563",
      "file": "drivers/usb/dwc2/core_intr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591678496,
      "name": "dwc2_handle_lpm_intr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 605
    },
    {
      "addr": 18446744071596277645,
      "name": "dwc2_handle_lpm_intr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 191
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
void dwc2_handle_lpm_intr(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_handle_lpm_intr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_handle_lpm_intr",
      "external": false,
      "loc": "drivers/usb/dwc2/core_intr.c:563",
      "file": "drivers/usb/dwc2/core_intr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592101376,
      "name": "dwc2_handle_lpm_intr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 605
    },
    {
      "addr": 18446744071596807491,
      "name": "dwc2_handle_lpm_intr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 191
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
void dwc2_handle_lpm_intr(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_handle_lpm_intr",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_handle_lpm_intr",
      "external": false,
      "loc": "drivers/usb/dwc2/core_intr.c:563",
      "file": "drivers/usb/dwc2/core_intr.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592841808,
      "name": "dwc2_handle_lpm_intr",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 605
    },
    {
      "addr": 18446744071597731098,
      "name": "dwc2_handle_lpm_intr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 191
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "dwc2_handle_lpm_intr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336500369788,
      "name": "dwc2_handle_lpm_intr",
      "external": false,
      "loc": "drivers/usb/dwc2/core_intr.c:568",
      "file": "drivers/usb/dwc2/core_intr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "dwc2_handle_lpm_intr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3232827240,
      "name": "dwc2_handle_lpm_intr",
      "external": false,
      "loc": "drivers/usb/dwc2/core_intr.c:568",
      "file": "drivers/usb/dwc2/core_intr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "dwc2_handle_lpm_intr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055293686720,
      "name": "dwc2_handle_lpm_intr",
      "external": false,
      "loc": "drivers/usb/dwc2/core_intr.c:568",
      "file": "drivers/usb/dwc2/core_intr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "dwc2_handle_lpm_intr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936277256356,
      "name": "dwc2_handle_lpm_intr",
      "external": false,
      "loc": "drivers/usb/dwc2/core_intr.c:568",
      "file": "drivers/usb/dwc2/core_intr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dwc2_handle_lpm_intr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586965373,
      "name": "dwc2_handle_lpm_intr",
      "external": false,
      "loc": "drivers/usb/dwc2/core_intr.c:568",
      "file": "drivers/usb/dwc2/core_intr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr"
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
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dwc2_handle_lpm_intr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587213853,
      "name": "dwc2_handle_lpm_intr",
      "external": false,
      "loc": "drivers/usb/dwc2/core_intr.c:568",
      "file": "drivers/usb/dwc2/core_intr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr"
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
  "name": "dwc2_handle_lpm_intr",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587320811,
      "name": "dwc2_handle_lpm_intr",
      "external": false,
      "loc": "drivers/usb/dwc2/core_intr.c:568",
      "file": "drivers/usb/dwc2/core_intr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/core_intr.c:dwc2_handle_common_intr"
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
void dwc2_handle_lpm_intr(struct dwc2_hsotg * hsotg)
```
</details>
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
