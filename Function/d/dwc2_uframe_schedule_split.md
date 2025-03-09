# Function: <code>dwc2_uframe_schedule_split</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dwc2_uframe_schedule_split",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585717836,
      "name": "dwc2_uframe_schedule_split",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_queue.c:703",
      "file": "drivers/usb/dwc2/hcd_queue.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dwc2_uframe_schedule_split",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585906456,
      "name": "dwc2_uframe_schedule_split",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_queue.c:706",
      "file": "drivers/usb/dwc2/hcd_queue.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "dwc2_uframe_schedule_split",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585988939,
      "name": "dwc2_uframe_schedule_split",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_queue.c:703",
      "file": "drivers/usb/dwc2/hcd_queue.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "dwc2_uframe_schedule_split",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586432913,
      "name": "dwc2_uframe_schedule_split",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_queue.c:704",
      "file": "drivers/usb/dwc2/hcd_queue.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "dwc2_uframe_schedule_split",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586697859,
      "name": "dwc2_uframe_schedule_split",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_queue.c:708",
      "file": "drivers/usb/dwc2/hcd_queue.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "dwc2_uframe_schedule_split",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586854975,
      "name": "dwc2_uframe_schedule_split",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_queue.c:708",
      "file": "drivers/usb/dwc2/hcd_queue.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "dwc2_uframe_schedule_split",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587111146,
      "name": "dwc2_uframe_schedule_split",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_queue.c:708",
      "file": "drivers/usb/dwc2/hcd_queue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_queue.c:dwc2_do_reserve"
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
  "name": "dwc2_uframe_schedule_split",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587311550,
      "name": "dwc2_uframe_schedule_split",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_queue.c:708",
      "file": "drivers/usb/dwc2/hcd_queue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_queue.c:dwc2_do_reserve"
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
int dwc2_uframe_schedule_split(struct dwc2_hsotg * hsotg, struct dwc2_qh * qh)
```

```json
{
  "name": "dwc2_uframe_schedule_split",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588168096,
      "name": "dwc2_uframe_schedule_split",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_queue.c:708",
      "file": "drivers/usb/dwc2/hcd_queue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_queue.c:dwc2_do_reserve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588168096,
      "name": "dwc2_uframe_schedule_split",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1332
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
int dwc2_uframe_schedule_split(struct dwc2_hsotg * hsotg, struct dwc2_qh * qh)
```

```json
{
  "name": "dwc2_uframe_schedule_split",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588206208,
      "name": "dwc2_uframe_schedule_split",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_queue.c:708",
      "file": "drivers/usb/dwc2/hcd_queue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_queue.c:dwc2_do_reserve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588206208,
      "name": "dwc2_uframe_schedule_split",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1332
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
int dwc2_uframe_schedule_split(struct dwc2_hsotg * hsotg, struct dwc2_qh * qh)
```

```json
{
  "name": "dwc2_uframe_schedule_split",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588089424,
      "name": "dwc2_uframe_schedule_split",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_queue.c:708",
      "file": "drivers/usb/dwc2/hcd_queue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_queue.c:dwc2_do_reserve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588089424,
      "name": "dwc2_uframe_schedule_split",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1328
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
int dwc2_uframe_schedule_split(struct dwc2_hsotg * hsotg, struct dwc2_qh * qh)
```

```json
{
  "name": "dwc2_uframe_schedule_split",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588721456,
      "name": "dwc2_uframe_schedule_split",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_queue.c:708",
      "file": "drivers/usb/dwc2/hcd_queue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_queue.c:dwc2_do_reserve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588721456,
      "name": "dwc2_uframe_schedule_split",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1496
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
int dwc2_uframe_schedule_split(struct dwc2_hsotg * hsotg, struct dwc2_qh * qh)
```

```json
{
  "name": "dwc2_uframe_schedule_split",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590139744,
      "name": "dwc2_uframe_schedule_split",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_queue.c:708",
      "file": "drivers/usb/dwc2/hcd_queue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_queue.c:dwc2_do_reserve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590139744,
      "name": "dwc2_uframe_schedule_split",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1535
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
int dwc2_uframe_schedule_split(struct dwc2_hsotg * hsotg, struct dwc2_qh * qh)
```

```json
{
  "name": "dwc2_uframe_schedule_split",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591753776,
      "name": "dwc2_uframe_schedule_split",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_queue.c:678",
      "file": "drivers/usb/dwc2/hcd_queue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_queue.c:dwc2_do_reserve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591753776,
      "name": "dwc2_uframe_schedule_split",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1535
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
int dwc2_uframe_schedule_split(struct dwc2_hsotg * hsotg, struct dwc2_qh * qh)
```

```json
{
  "name": "dwc2_uframe_schedule_split",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592177104,
      "name": "dwc2_uframe_schedule_split",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_queue.c:678",
      "file": "drivers/usb/dwc2/hcd_queue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_queue.c:dwc2_do_reserve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592177104,
      "name": "dwc2_uframe_schedule_split",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1547
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
int dwc2_uframe_schedule_split(struct dwc2_hsotg * hsotg, struct dwc2_qh * qh)
```

```json
{
  "name": "dwc2_uframe_schedule_split",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592917792,
      "name": "dwc2_uframe_schedule_split",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_queue.c:678",
      "file": "drivers/usb/dwc2/hcd_queue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_queue.c:dwc2_do_reserve"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592917792,
      "name": "dwc2_uframe_schedule_split",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1547
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
  "name": "dwc2_uframe_schedule_split",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336500428876,
      "name": "dwc2_uframe_schedule_split",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_queue.c:708",
      "file": "drivers/usb/dwc2/hcd_queue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_queue.c:dwc2_do_reserve"
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
  "name": "dwc2_uframe_schedule_split",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3232883640,
      "name": "dwc2_uframe_schedule_split",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_queue.c:708",
      "file": "drivers/usb/dwc2/hcd_queue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_queue.c:dwc2_do_reserve"
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
  "name": "dwc2_uframe_schedule_split",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055293776420,
      "name": "dwc2_uframe_schedule_split",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_queue.c:708",
      "file": "drivers/usb/dwc2/hcd_queue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_queue.c:dwc2_do_reserve"
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
  "name": "dwc2_uframe_schedule_split",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936277319366,
      "name": "dwc2_uframe_schedule_split",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_queue.c:708",
      "file": "drivers/usb/dwc2/hcd_queue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_queue.c:dwc2_do_reserve"
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
  "name": "dwc2_uframe_schedule_split",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587017630,
      "name": "dwc2_uframe_schedule_split",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_queue.c:708",
      "file": "drivers/usb/dwc2/hcd_queue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_queue.c:dwc2_do_reserve"
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
  "name": "dwc2_uframe_schedule_split",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587266110,
      "name": "dwc2_uframe_schedule_split",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_queue.c:708",
      "file": "drivers/usb/dwc2/hcd_queue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_queue.c:dwc2_do_reserve"
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
  "name": "dwc2_uframe_schedule_split",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587372878,
      "name": "dwc2_uframe_schedule_split",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_queue.c:708",
      "file": "drivers/usb/dwc2/hcd_queue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_queue.c:dwc2_do_reserve"
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
int dwc2_uframe_schedule_split(struct dwc2_hsotg * hsotg, struct dwc2_qh * qh)
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
