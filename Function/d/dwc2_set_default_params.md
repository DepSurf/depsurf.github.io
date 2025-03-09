# Function: <code>dwc2_set_default_params</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dwc2_set_default_params",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585950265,
      "name": "dwc2_set_default_params",
      "external": false,
      "loc": "drivers/usb/dwc2/params.c:247",
      "file": "drivers/usb/dwc2/params.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/params.c:dwc2_init_params"
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
  "name": "dwc2_set_default_params",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586393609,
      "name": "dwc2_set_default_params",
      "external": false,
      "loc": "drivers/usb/dwc2/params.c:259",
      "file": "drivers/usb/dwc2/params.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/params.c:dwc2_init_params"
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
  "name": "dwc2_set_default_params",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586656645,
      "name": "dwc2_set_default_params",
      "external": false,
      "loc": "drivers/usb/dwc2/params.c:277",
      "file": "drivers/usb/dwc2/params.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/params.c:dwc2_init_params"
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
  "name": "dwc2_set_default_params",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586808709,
      "name": "dwc2_set_default_params",
      "external": false,
      "loc": "drivers/usb/dwc2/params.c:283",
      "file": "drivers/usb/dwc2/params.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/params.c:dwc2_init_params"
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
  "name": "dwc2_set_default_params",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587065605,
      "name": "dwc2_set_default_params",
      "external": false,
      "loc": "drivers/usb/dwc2/params.c:322",
      "file": "drivers/usb/dwc2/params.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/params.c:dwc2_init_params"
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
  "name": "dwc2_set_default_params",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587265941,
      "name": "dwc2_set_default_params",
      "external": false,
      "loc": "drivers/usb/dwc2/params.c:322",
      "file": "drivers/usb/dwc2/params.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/params.c:dwc2_init_params"
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
void dwc2_set_default_params(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_set_default_params",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588120128,
      "name": "dwc2_set_default_params",
      "external": false,
      "loc": "drivers/usb/dwc2/params.c:355",
      "file": "drivers/usb/dwc2/params.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/params.c:dwc2_init_params"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588120128,
      "name": "dwc2_set_default_params",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 644
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
void dwc2_set_default_params(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_set_default_params",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588162368,
      "name": "dwc2_set_default_params",
      "external": false,
      "loc": "drivers/usb/dwc2/params.c:356",
      "file": "drivers/usb/dwc2/params.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/params.c:dwc2_init_params"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588162368,
      "name": "dwc2_set_default_params",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 644
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
  "name": "dwc2_set_default_params",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588045077,
      "name": "dwc2_set_default_params",
      "external": false,
      "loc": "drivers/usb/dwc2/params.c:371",
      "file": "drivers/usb/dwc2/params.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/params.c:dwc2_init_params"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void dwc2_set_default_params(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_set_default_params",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588667136,
      "name": "dwc2_set_default_params",
      "external": false,
      "loc": "drivers/usb/dwc2/params.c:371",
      "file": "drivers/usb/dwc2/params.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/params.c:dwc2_init_params"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588667136,
      "name": "dwc2_set_default_params",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 641
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
void dwc2_set_default_params(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_set_default_params",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590085168,
      "name": "dwc2_set_default_params",
      "external": false,
      "loc": "drivers/usb/dwc2/params.c:438",
      "file": "drivers/usb/dwc2/params.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/params.c:dwc2_init_params"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590085168,
      "name": "dwc2_set_default_params",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 663
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
void dwc2_set_default_params(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_set_default_params",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591695488,
      "name": "dwc2_set_default_params",
      "external": false,
      "loc": "drivers/usb/dwc2/params.c:412",
      "file": "drivers/usb/dwc2/params.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/params.c:dwc2_init_params"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591695488,
      "name": "dwc2_set_default_params",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 663
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
void dwc2_set_default_params(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_set_default_params",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592118864,
      "name": "dwc2_set_default_params",
      "external": false,
      "loc": "drivers/usb/dwc2/params.c:433",
      "file": "drivers/usb/dwc2/params.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/params.c:dwc2_init_params"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592118864,
      "name": "dwc2_set_default_params",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 649
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
void dwc2_set_default_params(struct dwc2_hsotg * hsotg)
```

```json
{
  "name": "dwc2_set_default_params",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592859360,
      "name": "dwc2_set_default_params",
      "external": false,
      "loc": "drivers/usb/dwc2/params.c:464",
      "file": "drivers/usb/dwc2/params.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/params.c:dwc2_init_params"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592859360,
      "name": "dwc2_set_default_params",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 649
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
  "name": "dwc2_set_default_params",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336500378624,
      "name": "dwc2_set_default_params",
      "external": false,
      "loc": "drivers/usb/dwc2/params.c:322",
      "file": "drivers/usb/dwc2/params.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/params.c:dwc2_init_params"
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
  "name": "dwc2_set_default_params",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3232835428,
      "name": "dwc2_set_default_params",
      "external": false,
      "loc": "drivers/usb/dwc2/params.c:322",
      "file": "drivers/usb/dwc2/params.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/params.c:dwc2_init_params"
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
  "name": "dwc2_set_default_params",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055293699024,
      "name": "dwc2_set_default_params",
      "external": false,
      "loc": "drivers/usb/dwc2/params.c:322",
      "file": "drivers/usb/dwc2/params.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/params.c:dwc2_init_params"
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
  "name": "dwc2_set_default_params",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936277264898,
      "name": "dwc2_set_default_params",
      "external": false,
      "loc": "drivers/usb/dwc2/params.c:322",
      "file": "drivers/usb/dwc2/params.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/params.c:dwc2_init_params"
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
  "name": "dwc2_set_default_params",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586972021,
      "name": "dwc2_set_default_params",
      "external": false,
      "loc": "drivers/usb/dwc2/params.c:322",
      "file": "drivers/usb/dwc2/params.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/params.c:dwc2_init_params"
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
  "name": "dwc2_set_default_params",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587220501,
      "name": "dwc2_set_default_params",
      "external": false,
      "loc": "drivers/usb/dwc2/params.c:322",
      "file": "drivers/usb/dwc2/params.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/params.c:dwc2_init_params"
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
  "name": "dwc2_set_default_params",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587327269,
      "name": "dwc2_set_default_params",
      "external": false,
      "loc": "drivers/usb/dwc2/params.c:322",
      "file": "drivers/usb/dwc2/params.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/params.c:dwc2_init_params"
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
void dwc2_set_default_params(struct dwc2_hsotg * hsotg)
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
void dwc2_set_default_params(struct dwc2_hsotg * hsotg)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
void dwc2_set_default_params(struct dwc2_hsotg * hsotg)
```
</details>
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
