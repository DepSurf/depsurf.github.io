# Function: <code>xhci_decode_ctrl_ctx</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_decode_ctrl_ctx",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587336997,
      "name": "xhci_decode_ctrl_ctx",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2420",
      "file": "drivers/usb/host/xhci-trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ctrl_ctx"
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
  "name": "xhci_decode_ctrl_ctx",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587538629,
      "name": "xhci_decode_ctrl_ctx",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2431",
      "file": "drivers/usb/host/xhci-trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ctrl_ctx"
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
const char * xhci_decode_ctrl_ctx(long unsigned int drop, long unsigned int add)
```

```json
{
  "name": "xhci_decode_ctrl_ctx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588401104,
      "name": "xhci_decode_ctrl_ctx",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2434",
      "file": "drivers/usb/host/xhci-trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ctrl_ctx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588401104,
      "name": "xhci_decode_ctrl_ctx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 382
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
const char * xhci_decode_ctrl_ctx(long unsigned int drop, long unsigned int add)
```

```json
{
  "name": "xhci_decode_ctrl_ctx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588431408,
      "name": "xhci_decode_ctrl_ctx",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2449",
      "file": "drivers/usb/host/xhci-trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ctrl_ctx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588431408,
      "name": "xhci_decode_ctrl_ctx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 382
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
const char * xhci_decode_ctrl_ctx(long unsigned int drop, long unsigned int add)
```

```json
{
  "name": "xhci_decode_ctrl_ctx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588314944,
      "name": "xhci_decode_ctrl_ctx",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2455",
      "file": "drivers/usb/host/xhci-trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ctrl_ctx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588314944,
      "name": "xhci_decode_ctrl_ctx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 393
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
const char * xhci_decode_ctrl_ctx(char * str, long unsigned int drop, long unsigned int add)
```

```json
{
  "name": "xhci_decode_ctrl_ctx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588972400,
      "name": "xhci_decode_ctrl_ctx",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2464",
      "file": "drivers/usb/host/xhci-trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ctrl_ctx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588972400,
      "name": "xhci_decode_ctrl_ctx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 369
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
const char * xhci_decode_ctrl_ctx(char * str, long unsigned int drop, long unsigned int add)
```

```json
{
  "name": "xhci_decode_ctrl_ctx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590408832,
      "name": "xhci_decode_ctrl_ctx",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2491",
      "file": "drivers/usb/host/xhci-trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ctrl_ctx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590408832,
      "name": "xhci_decode_ctrl_ctx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 388
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
const char * xhci_decode_ctrl_ctx(char * str, long unsigned int drop, long unsigned int add)
```

```json
{
  "name": "xhci_decode_ctrl_ctx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592045344,
      "name": "xhci_decode_ctrl_ctx",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2492",
      "file": "drivers/usb/host/xhci-trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ctrl_ctx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592045344,
      "name": "xhci_decode_ctrl_ctx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 382
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
const char * xhci_decode_ctrl_ctx(char * str, long unsigned int drop, long unsigned int add)
```

```json
{
  "name": "xhci_decode_ctrl_ctx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592466656,
      "name": "xhci_decode_ctrl_ctx",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2502",
      "file": "drivers/usb/host/xhci-trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ctrl_ctx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592466656,
      "name": "xhci_decode_ctrl_ctx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 382
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
const char * xhci_decode_ctrl_ctx(char * str, long unsigned int drop, long unsigned int add)
```

```json
{
  "name": "xhci_decode_ctrl_ctx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593210432,
      "name": "xhci_decode_ctrl_ctx",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2479",
      "file": "drivers/usb/host/xhci-trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ctrl_ctx"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593210432,
      "name": "xhci_decode_ctrl_ctx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 382
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
  "name": "xhci_decode_ctrl_ctx",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336500678128,
      "name": "xhci_decode_ctrl_ctx",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2431",
      "file": "drivers/usb/host/xhci-trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ctrl_ctx"
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
  "name": "xhci_decode_ctrl_ctx",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3233138108,
      "name": "xhci_decode_ctrl_ctx",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2431",
      "file": "drivers/usb/host/xhci-trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ctrl_ctx"
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
  "name": "xhci_decode_ctrl_ctx",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055294110268,
      "name": "xhci_decode_ctrl_ctx",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2431",
      "file": "drivers/usb/host/xhci-trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ctrl_ctx"
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
  "name": "xhci_decode_ctrl_ctx",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936277539494,
      "name": "xhci_decode_ctrl_ctx",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2431",
      "file": "drivers/usb/host/xhci-trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ctrl_ctx"
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
  "name": "xhci_decode_ctrl_ctx",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587244661,
      "name": "xhci_decode_ctrl_ctx",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2431",
      "file": "drivers/usb/host/xhci-trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ctrl_ctx"
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
  "name": "xhci_decode_ctrl_ctx",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587003413,
      "name": "xhci_decode_ctrl_ctx",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2431",
      "file": "drivers/usb/host/xhci-trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ctrl_ctx"
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
  "name": "xhci_decode_ctrl_ctx",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587493189,
      "name": "xhci_decode_ctrl_ctx",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2431",
      "file": "drivers/usb/host/xhci-trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ctrl_ctx"
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
  "name": "xhci_decode_ctrl_ctx",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587600917,
      "name": "xhci_decode_ctrl_ctx",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2431",
      "file": "drivers/usb/host/xhci-trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_ctrl_ctx"
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
const char * xhci_decode_ctrl_ctx(long unsigned int drop, long unsigned int add)
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
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>char * str</code>
</li>
<li>
<b>Param reordered. </b>
<code>drop, add</code> ➡️ <code>str, drop, add</code>
</li>
</ul>
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
