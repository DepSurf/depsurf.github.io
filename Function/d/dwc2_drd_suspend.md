# Function: <code>dwc2_drd_suspend</code>

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
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void dwc2_drd_suspend(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_drd_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588160016,
      "name": "dwc2_drd_suspend",
      "external": true,
      "loc": "drivers/usb/dwc2/drd.c:150",
      "file": "drivers/usb/dwc2/drd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/platform.c:dwc2_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588160016,
      "name": "dwc2_drd_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
void dwc2_drd_suspend(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_drd_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588042016,
      "name": "dwc2_drd_suspend",
      "external": true,
      "loc": "drivers/usb/dwc2/drd.c:150",
      "file": "drivers/usb/dwc2/drd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/platform.c:dwc2_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588042016,
      "name": "dwc2_drd_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
void dwc2_drd_suspend(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_drd_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_drd_suspend",
      "external": true,
      "loc": "drivers/usb/dwc2/drd.c:172",
      "file": "drivers/usb/dwc2/drd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/platform.c:dwc2_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592581696,
      "name": "dwc2_drd_suspend.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 161
    },
    {
      "addr": 18446744071588664128,
      "name": "dwc2_drd_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 303
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
void dwc2_drd_suspend(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_drd_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_drd_suspend",
      "external": true,
      "loc": "drivers/usb/dwc2/drd.c:194",
      "file": "drivers/usb/dwc2/drd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/platform.c:dwc2_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594461822,
      "name": "dwc2_drd_suspend.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
    },
    {
      "addr": 18446744071590081216,
      "name": "dwc2_drd_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 293
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
void dwc2_drd_suspend(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_drd_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_drd_suspend",
      "external": true,
      "loc": "drivers/usb/dwc2/drd.c:194",
      "file": "drivers/usb/dwc2/drd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/platform.c:dwc2_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596280431,
      "name": "dwc2_drd_suspend.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
    },
    {
      "addr": 18446744071591689648,
      "name": "dwc2_drd_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 293
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
void dwc2_drd_suspend(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_drd_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_drd_suspend",
      "external": true,
      "loc": "drivers/usb/dwc2/drd.c:195",
      "file": "drivers/usb/dwc2/drd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/platform.c:dwc2_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596810295,
      "name": "dwc2_drd_suspend.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
    },
    {
      "addr": 18446744071592112944,
      "name": "dwc2_drd_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 293
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
void dwc2_drd_suspend(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_drd_suspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dwc2_drd_suspend",
      "external": true,
      "loc": "drivers/usb/dwc2/drd.c:195",
      "file": "drivers/usb/dwc2/drd.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/platform.c:dwc2_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597733902,
      "name": "dwc2_drd_suspend.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
    },
    {
      "addr": 18446744071592853376,
      "name": "dwc2_drd_suspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 293
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
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
void dwc2_drd_suspend(struct dwc2_hsotg * hsotg)
```
</details>
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
