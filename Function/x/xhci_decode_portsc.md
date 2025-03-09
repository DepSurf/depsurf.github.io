# Function: <code>xhci_decode_portsc</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_decode_portsc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586651599,
      "name": "xhci_decode_portsc",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2454",
      "file": "drivers/usb/host/xhci-trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_portsc"
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
  "name": "xhci_decode_portsc",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586914832,
      "name": "xhci_decode_portsc",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2466",
      "file": "drivers/usb/host/xhci-trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_portsc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586930808,
      "name": "xhci_decode_portsc",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2466",
      "file": "drivers/usb/host/xhci-debugfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-debugfs.c:xhci_portsc_show"
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
  "name": "xhci_decode_portsc",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587072080,
      "name": "xhci_decode_portsc",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2474",
      "file": "drivers/usb/host/xhci-trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_portsc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587087976,
      "name": "xhci_decode_portsc",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2474",
      "file": "drivers/usb/host/xhci-debugfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-debugfs.c:xhci_portsc_show"
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
  "name": "xhci_decode_portsc",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587335808,
      "name": "xhci_decode_portsc",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2536",
      "file": "drivers/usb/host/xhci-trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_portsc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587350520,
      "name": "xhci_decode_portsc",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2536",
      "file": "drivers/usb/host/xhci-debugfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-debugfs.c:xhci_portsc_show"
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
  "name": "xhci_decode_portsc",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587537168,
      "name": "xhci_decode_portsc",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2547",
      "file": "drivers/usb/host/xhci-trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_portsc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587552184,
      "name": "xhci_decode_portsc",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2547",
      "file": "drivers/usb/host/xhci-debugfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-debugfs.c:xhci_portsc_show"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate ❓</summary>

```c
const char * xhci_decode_portsc(u32 portsc)
```

```json
{
  "name": "xhci_decode_portsc",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588399392,
      "name": "xhci_decode_portsc",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2550",
      "file": "drivers/usb/host/xhci-trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_portsc"
      ]
    },
    {
      "addr": 18446744071588417648,
      "name": "xhci_decode_portsc",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2550",
      "file": "drivers/usb/host/xhci-debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-debugfs.c:xhci_portsc_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588399392,
      "name": "xhci_decode_portsc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1029
    },
    {
      "addr": 18446744071588417648,
      "name": "xhci_decode_portsc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1029
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Duplicate ❓</summary>

```c
const char * xhci_decode_portsc(u32 portsc)
```

```json
{
  "name": "xhci_decode_portsc",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588429712,
      "name": "xhci_decode_portsc",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2565",
      "file": "drivers/usb/host/xhci-trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_portsc"
      ]
    },
    {
      "addr": 18446744071588447776,
      "name": "xhci_decode_portsc",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2565",
      "file": "drivers/usb/host/xhci-debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-debugfs.c:xhci_portsc_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588429712,
      "name": "xhci_decode_portsc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1024
    },
    {
      "addr": 18446744071588447776,
      "name": "xhci_decode_portsc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1024
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Duplicate ❓</summary>

```c
const char * xhci_decode_portsc(u32 portsc)
```

```json
{
  "name": "xhci_decode_portsc",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588312704,
      "name": "xhci_decode_portsc",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2571",
      "file": "drivers/usb/host/xhci-trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_portsc"
      ]
    },
    {
      "addr": 18446744071588330672,
      "name": "xhci_decode_portsc",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2571",
      "file": "drivers/usb/host/xhci-debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-debugfs.c:xhci_portsc_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588312704,
      "name": "xhci_decode_portsc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1021
    },
    {
      "addr": 18446744071588330672,
      "name": "xhci_decode_portsc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1021
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Duplicate ❓</summary>

```c
const char * xhci_decode_portsc(char * str, u32 portsc)
```

```json
{
  "name": "xhci_decode_portsc",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588967184,
      "name": "xhci_decode_portsc",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2578",
      "file": "drivers/usb/host/xhci-trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_portsc"
      ]
    },
    {
      "addr": 18446744071588985904,
      "name": "xhci_decode_portsc",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2578",
      "file": "drivers/usb/host/xhci-debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-debugfs.c:xhci_portsc_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588967184,
      "name": "xhci_decode_portsc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 952
    },
    {
      "addr": 18446744071588985904,
      "name": "xhci_decode_portsc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 952
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate ❓</summary>

```c
const char * xhci_decode_portsc(char * str, u32 portsc)
```

```json
{
  "name": "xhci_decode_portsc",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590403184,
      "name": "xhci_decode_portsc",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2607",
      "file": "drivers/usb/host/xhci-trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_portsc"
      ]
    },
    {
      "addr": 18446744071590421104,
      "name": "xhci_decode_portsc",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2607",
      "file": "drivers/usb/host/xhci-debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-debugfs.c:xhci_portsc_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590403184,
      "name": "xhci_decode_portsc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 985
    },
    {
      "addr": 18446744071590421104,
      "name": "xhci_decode_portsc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 985
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Duplicate ❓</summary>

```c
const char * xhci_decode_portsc(char * str, u32 portsc)
```

```json
{
  "name": "xhci_decode_portsc",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592038512,
      "name": "xhci_decode_portsc",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2608",
      "file": "drivers/usb/host/xhci-trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_portsc"
      ]
    },
    {
      "addr": 18446744071592059248,
      "name": "xhci_decode_portsc",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2608",
      "file": "drivers/usb/host/xhci-debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-debugfs.c:xhci_portsc_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592038512,
      "name": "xhci_decode_portsc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 985
    },
    {
      "addr": 18446744071592059248,
      "name": "xhci_decode_portsc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 985
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Duplicate ❓</summary>

```c
const char * xhci_decode_portsc(char * str, u32 portsc)
```

```json
{
  "name": "xhci_decode_portsc",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592458144,
      "name": "xhci_decode_portsc",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2618",
      "file": "drivers/usb/host/xhci-trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_portsc"
      ]
    },
    {
      "addr": 18446744071592482096,
      "name": "xhci_decode_portsc",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2618",
      "file": "drivers/usb/host/xhci-debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-debugfs.c:xhci_portsc_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592458144,
      "name": "xhci_decode_portsc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 983
    },
    {
      "addr": 18446744071592482096,
      "name": "xhci_decode_portsc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 983
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Duplicate ❓</summary>

```c
const char * xhci_decode_portsc(char * str, u32 portsc)
```

```json
{
  "name": "xhci_decode_portsc",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593201936,
      "name": "xhci_decode_portsc",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2595",
      "file": "drivers/usb/host/xhci-trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_portsc"
      ]
    },
    {
      "addr": 18446744071593227120,
      "name": "xhci_decode_portsc",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2595",
      "file": "drivers/usb/host/xhci-debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-debugfs.c:xhci_portsc_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593201936,
      "name": "xhci_decode_portsc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 983
    },
    {
      "addr": 18446744071593227120,
      "name": "xhci_decode_portsc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 983
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
  "name": "xhci_decode_portsc",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336500676724,
      "name": "xhci_decode_portsc",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2547",
      "file": "drivers/usb/host/xhci-trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_portsc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336500704872,
      "name": "xhci_decode_portsc",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2547",
      "file": "drivers/usb/host/xhci-debugfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-debugfs.c:xhci_portsc_show"
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
  "name": "xhci_decode_portsc",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3233136640,
      "name": "xhci_decode_portsc",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2547",
      "file": "drivers/usb/host/xhci-trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_portsc"
      ],
      "caller_func": []
    },
    {
      "addr": 3233158152,
      "name": "xhci_decode_portsc",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2547",
      "file": "drivers/usb/host/xhci-debugfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-debugfs.c:xhci_portsc_show"
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
  "name": "xhci_decode_portsc",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055294108356,
      "name": "xhci_decode_portsc",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2547",
      "file": "drivers/usb/host/xhci-trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_portsc"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055294137212,
      "name": "xhci_decode_portsc",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2547",
      "file": "drivers/usb/host/xhci-debugfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-debugfs.c:xhci_portsc_show"
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
  "name": "xhci_decode_portsc",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936277537792,
      "name": "xhci_decode_portsc",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2547",
      "file": "drivers/usb/host/xhci-trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_portsc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277552300,
      "name": "xhci_decode_portsc",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2547",
      "file": "drivers/usb/host/xhci-debugfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-debugfs.c:xhci_portsc_show"
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
  "name": "xhci_decode_portsc",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587243200,
      "name": "xhci_decode_portsc",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2547",
      "file": "drivers/usb/host/xhci-trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_portsc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587248520,
      "name": "xhci_decode_portsc",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2547",
      "file": "drivers/usb/host/xhci-debugfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-debugfs.c:xhci_portsc_show"
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
  "name": "xhci_decode_portsc",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587001952,
      "name": "xhci_decode_portsc",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2547",
      "file": "drivers/usb/host/xhci-trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_portsc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587016968,
      "name": "xhci_decode_portsc",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2547",
      "file": "drivers/usb/host/xhci-debugfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-debugfs.c:xhci_portsc_show"
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
  "name": "xhci_decode_portsc",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587491728,
      "name": "xhci_decode_portsc",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2547",
      "file": "drivers/usb/host/xhci-trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_portsc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587506744,
      "name": "xhci_decode_portsc",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2547",
      "file": "drivers/usb/host/xhci-debugfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-debugfs.c:xhci_portsc_show"
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
  "name": "xhci_decode_portsc",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587599456,
      "name": "xhci_decode_portsc",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2547",
      "file": "drivers/usb/host/xhci-trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_portsc"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587614616,
      "name": "xhci_decode_portsc",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2547",
      "file": "drivers/usb/host/xhci-debugfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-debugfs.c:xhci_portsc_show"
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
const char * xhci_decode_portsc(u32 portsc)
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
<code>portsc</code> ➡️ <code>str, portsc</code>
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
