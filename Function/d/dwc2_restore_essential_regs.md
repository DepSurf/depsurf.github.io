# Function: <code>dwc2_restore_essential_regs</code>

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
  "name": "dwc2_restore_essential_regs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586644345,
      "name": "dwc2_restore_essential_regs",
      "external": false,
      "loc": "drivers/usb/dwc2/core.c:251",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/core.c:dwc2_hib_restore_common"
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
  "name": "dwc2_restore_essential_regs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586795457,
      "name": "dwc2_restore_essential_regs",
      "external": false,
      "loc": "drivers/usb/dwc2/core.c:251",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/core.c:dwc2_hib_restore_common"
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
  "name": "dwc2_restore_essential_regs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587051571,
      "name": "dwc2_restore_essential_regs",
      "external": false,
      "loc": "drivers/usb/dwc2/core.c:251",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/core.c:dwc2_hib_restore_common"
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
  "name": "dwc2_restore_essential_regs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587251971,
      "name": "dwc2_restore_essential_regs",
      "external": false,
      "loc": "drivers/usb/dwc2/core.c:251",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/core.c:dwc2_hib_restore_common"
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
void dwc2_restore_essential_regs(struct dwc2_hsotg * hsotg, int rmode, int is_host)
```

```json
{
  "name": "dwc2_restore_essential_regs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588102752,
      "name": "dwc2_restore_essential_regs",
      "external": false,
      "loc": "drivers/usb/dwc2/core.c:251",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core.c:dwc2_hib_restore_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588102752,
      "name": "dwc2_restore_essential_regs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 510
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
void dwc2_restore_essential_regs(struct dwc2_hsotg * hsotg, int rmode, int is_host)
```

```json
{
  "name": "dwc2_restore_essential_regs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588144512,
      "name": "dwc2_restore_essential_regs",
      "external": false,
      "loc": "drivers/usb/dwc2/core.c:251",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core.c:dwc2_hib_restore_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588144512,
      "name": "dwc2_restore_essential_regs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 510
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
void dwc2_restore_essential_regs(struct dwc2_hsotg * hsotg, int rmode, int is_host)
```

```json
{
  "name": "dwc2_restore_essential_regs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588026528,
      "name": "dwc2_restore_essential_regs",
      "external": false,
      "loc": "drivers/usb/dwc2/core.c:176",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core.c:dwc2_hib_restore_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588026528,
      "name": "dwc2_restore_essential_regs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 517
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
void dwc2_restore_essential_regs(struct dwc2_hsotg * hsotg, int rmode, int is_host)
```

```json
{
  "name": "dwc2_restore_essential_regs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_restore_essential_regs",
      "external": false,
      "loc": "drivers/usb/dwc2/core.c:176",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core.c:dwc2_hib_restore_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588643152,
      "name": "dwc2_restore_essential_regs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 781
    },
    {
      "addr": 18446744071592574448,
      "name": "dwc2_restore_essential_regs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 243
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
void dwc2_restore_essential_regs(struct dwc2_hsotg * hsotg, int rmode, int is_host)
```

```json
{
  "name": "dwc2_restore_essential_regs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_restore_essential_regs",
      "external": false,
      "loc": "drivers/usb/dwc2/core.c:176",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core.c:dwc2_hib_restore_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590059968,
      "name": "dwc2_restore_essential_regs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 795
    },
    {
      "addr": 18446744071594454167,
      "name": "dwc2_restore_essential_regs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 243
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
void dwc2_restore_essential_regs(struct dwc2_hsotg * hsotg, int rmode, int is_host)
```

```json
{
  "name": "dwc2_restore_essential_regs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_restore_essential_regs",
      "external": false,
      "loc": "drivers/usb/dwc2/core.c:146",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core.c:dwc2_hib_restore_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591667280,
      "name": "dwc2_restore_essential_regs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 795
    },
    {
      "addr": 18446744071596273272,
      "name": "dwc2_restore_essential_regs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 243
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
void dwc2_restore_essential_regs(struct dwc2_hsotg * hsotg, int rmode, int is_host)
```

```json
{
  "name": "dwc2_restore_essential_regs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_restore_essential_regs",
      "external": false,
      "loc": "drivers/usb/dwc2/core.c:146",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core.c:dwc2_hib_restore_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592090112,
      "name": "dwc2_restore_essential_regs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 795
    },
    {
      "addr": 18446744071596803112,
      "name": "dwc2_restore_essential_regs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 243
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
void dwc2_restore_essential_regs(struct dwc2_hsotg * hsotg, int rmode, int is_host)
```

```json
{
  "name": "dwc2_restore_essential_regs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_restore_essential_regs",
      "external": false,
      "loc": "drivers/usb/dwc2/core.c:146",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/core.c:dwc2_hib_restore_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592830544,
      "name": "dwc2_restore_essential_regs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 795
    },
    {
      "addr": 18446744071597726719,
      "name": "dwc2_restore_essential_regs.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 243
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
  "name": "dwc2_restore_essential_regs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336500360780,
      "name": "dwc2_restore_essential_regs",
      "external": false,
      "loc": "drivers/usb/dwc2/core.c:251",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/core.c:dwc2_hib_restore_common"
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
  "name": "dwc2_restore_essential_regs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3232817144,
      "name": "dwc2_restore_essential_regs",
      "external": false,
      "loc": "drivers/usb/dwc2/core.c:251",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/core.c:dwc2_hib_restore_common"
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
  "name": "dwc2_restore_essential_regs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055293671676,
      "name": "dwc2_restore_essential_regs",
      "external": false,
      "loc": "drivers/usb/dwc2/core.c:251",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/core.c:dwc2_hib_restore_common"
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
  "name": "dwc2_restore_essential_regs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936277245066,
      "name": "dwc2_restore_essential_regs",
      "external": false,
      "loc": "drivers/usb/dwc2/core.c:251",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/core.c:dwc2_hib_restore_common"
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
  "name": "dwc2_restore_essential_regs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586958051,
      "name": "dwc2_restore_essential_regs",
      "external": false,
      "loc": "drivers/usb/dwc2/core.c:251",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/core.c:dwc2_hib_restore_common"
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
  "name": "dwc2_restore_essential_regs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587206531,
      "name": "dwc2_restore_essential_regs",
      "external": false,
      "loc": "drivers/usb/dwc2/core.c:251",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/core.c:dwc2_hib_restore_common"
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
  "name": "dwc2_restore_essential_regs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587313603,
      "name": "dwc2_restore_essential_regs",
      "external": false,
      "loc": "drivers/usb/dwc2/core.c:251",
      "file": "drivers/usb/dwc2/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/core.c:dwc2_hib_restore_common"
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
void dwc2_restore_essential_regs(struct dwc2_hsotg * hsotg, int rmode, int is_host)
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
