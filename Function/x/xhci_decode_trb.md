# Function: <code>xhci_decode_trb</code>

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
  "name": "xhci_decode_trb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586202155,
      "name": "xhci_decode_trb",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2125",
      "file": "drivers/usb/host/xhci-trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_trb"
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
  "name": "xhci_decode_trb",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586648555,
      "name": "xhci_decode_trb",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2148",
      "file": "drivers/usb/host/xhci-trace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_trb"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586666407,
      "name": "xhci_decode_trb",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2148",
      "file": "drivers/usb/host/xhci-debugfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-debugfs.c:xhci_ring_trb_show"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Duplicate ❓</summary>

```c
const char * xhci_decode_trb(u32 field0, u32 field1, u32 field2, u32 field3)
```

```json
{
  "name": "xhci_decode_trb",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586911696,
      "name": "xhci_decode_trb",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2160",
      "file": "drivers/usb/host/xhci-trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_trb"
      ]
    },
    {
      "addr": 18446744071586928752,
      "name": "xhci_decode_trb",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2160",
      "file": "drivers/usb/host/xhci-debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-debugfs.c:xhci_ring_trb_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586911696,
      "name": "xhci_decode_trb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2027
    },
    {
      "addr": 18446744071586928752,
      "name": "xhci_decode_trb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2027
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Duplicate ❓</summary>

```c
const char * xhci_decode_trb(u32 field0, u32 field1, u32 field2, u32 field3)
```

```json
{
  "name": "xhci_decode_trb",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587068752,
      "name": "xhci_decode_trb",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2168",
      "file": "drivers/usb/host/xhci-trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_trb"
      ]
    },
    {
      "addr": 18446744071587085728,
      "name": "xhci_decode_trb",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2168",
      "file": "drivers/usb/host/xhci-debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-debugfs.c:xhci_ring_trb_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587068752,
      "name": "xhci_decode_trb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2224
    },
    {
      "addr": 18446744071587085728,
      "name": "xhci_decode_trb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2224
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
const char * xhci_decode_trb(u32 field0, u32 field1, u32 field2, u32 field3)
```

```json
{
  "name": "xhci_decode_trb",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587332464,
      "name": "xhci_decode_trb",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2201",
      "file": "drivers/usb/host/xhci-trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_trb"
      ]
    },
    {
      "addr": 18446744071587353739,
      "name": "xhci_decode_trb",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2201",
      "file": "drivers/usb/host/xhci-debugfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-debugfs.c:xhci_ring_trb_show"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587332464,
      "name": "xhci_decode_trb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2229
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
const char * xhci_decode_trb(u32 field0, u32 field1, u32 field2, u32 field3)
```

```json
{
  "name": "xhci_decode_trb",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587533808,
      "name": "xhci_decode_trb",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2211",
      "file": "drivers/usb/host/xhci-trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_trb"
      ]
    },
    {
      "addr": 18446744071587555405,
      "name": "xhci_decode_trb",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2211",
      "file": "drivers/usb/host/xhci-debugfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-debugfs.c:xhci_ring_trb_show"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587533808,
      "name": "xhci_decode_trb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2248
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate ❓</summary>

```c
const char * xhci_decode_trb(u32 field0, u32 field1, u32 field2, u32 field3)
```

```json
{
  "name": "xhci_decode_trb",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588396080,
      "name": "xhci_decode_trb",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2214",
      "file": "drivers/usb/host/xhci-trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_trb"
      ]
    },
    {
      "addr": 18446744071588415200,
      "name": "xhci_decode_trb",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2214",
      "file": "drivers/usb/host/xhci-debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-debugfs.c:xhci_ring_trb_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588396080,
      "name": "xhci_decode_trb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2246
    },
    {
      "addr": 18446744071588415200,
      "name": "xhci_decode_trb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2246
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
const char * xhci_decode_trb(u32 field0, u32 field1, u32 field2, u32 field3)
```

```json
{
  "name": "xhci_decode_trb",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588426400,
      "name": "xhci_decode_trb",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2229",
      "file": "drivers/usb/host/xhci-trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_trb"
      ]
    },
    {
      "addr": 18446744071588445328,
      "name": "xhci_decode_trb",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2229",
      "file": "drivers/usb/host/xhci-debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-debugfs.c:xhci_ring_trb_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588426400,
      "name": "xhci_decode_trb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2246
    },
    {
      "addr": 18446744071588445328,
      "name": "xhci_decode_trb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2246
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
const char * xhci_decode_trb(u32 field0, u32 field1, u32 field2, u32 field3)
```

```json
{
  "name": "xhci_decode_trb",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588309392,
      "name": "xhci_decode_trb",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2235",
      "file": "drivers/usb/host/xhci-trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_trb"
      ]
    },
    {
      "addr": 18446744071588328208,
      "name": "xhci_decode_trb",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2235",
      "file": "drivers/usb/host/xhci-debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-debugfs.c:xhci_ring_trb_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588309392,
      "name": "xhci_decode_trb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2265
    },
    {
      "addr": 18446744071588328208,
      "name": "xhci_decode_trb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2265
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_decode_trb",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588969840,
      "name": "xhci_decode_trb",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2242",
      "file": "drivers/usb/host/xhci-trace.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_trb"
      ]
    },
    {
      "addr": 18446744071588988912,
      "name": "xhci_decode_trb",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2242",
      "file": "drivers/usb/host/xhci-debugfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-debugfs.c:xhci_ring_dump_segment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588969840,
      "name": "xhci_decode_trb.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2261
    },
    {
      "addr": 18446744071588988912,
      "name": "xhci_decode_trb.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2261
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_decode_trb",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590406096,
      "name": "xhci_decode_trb",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2269",
      "file": "drivers/usb/host/xhci-trace.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_trb"
      ]
    },
    {
      "addr": 18446744071590423984,
      "name": "xhci_decode_trb",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2269",
      "file": "drivers/usb/host/xhci-debugfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-debugfs.c:xhci_ring_dump_segment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590406096,
      "name": "xhci_decode_trb.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2265
    },
    {
      "addr": 18446744071590423984,
      "name": "xhci_decode_trb.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2265
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_decode_trb",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592042432,
      "name": "xhci_decode_trb",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2270",
      "file": "drivers/usb/host/xhci-trace.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_trb"
      ]
    },
    {
      "addr": 18446744071592062208,
      "name": "xhci_decode_trb",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2270",
      "file": "drivers/usb/host/xhci-debugfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-debugfs.c:xhci_ring_dump_segment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592042432,
      "name": "xhci_decode_trb.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2265
    },
    {
      "addr": 18446744071592062208,
      "name": "xhci_decode_trb.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2265
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_decode_trb",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592462176,
      "name": "xhci_decode_trb",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2280",
      "file": "drivers/usb/host/xhci-trace.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_trb"
      ]
    },
    {
      "addr": 18446744071592485040,
      "name": "xhci_decode_trb",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2280",
      "file": "drivers/usb/host/xhci-debugfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-debugfs.c:xhci_ring_dump_segment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592462176,
      "name": "xhci_decode_trb.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2307
    },
    {
      "addr": 18446744071592485040,
      "name": "xhci_decode_trb.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2307
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "xhci_decode_trb",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593206064,
      "name": "xhci_decode_trb",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2257",
      "file": "drivers/usb/host/xhci-trace.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_trb"
      ]
    },
    {
      "addr": 18446744071593229280,
      "name": "xhci_decode_trb",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2257",
      "file": "drivers/usb/host/xhci-debugfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-debugfs.c:xhci_ring_dump_segment"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593206064,
      "name": "xhci_decode_trb.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2307
    },
    {
      "addr": 18446744071593229280,
      "name": "xhci_decode_trb.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2307
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Duplicate, Selective Inline ❓</summary>

```c
const char * xhci_decode_trb(u32 field0, u32 field1, u32 field2, u32 field3)
```

```json
{
  "name": "xhci_decode_trb",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336500673592,
      "name": "xhci_decode_trb",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2211",
      "file": "drivers/usb/host/xhci-trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_trb"
      ]
    },
    {
      "addr": 18446603336500702888,
      "name": "xhci_decode_trb",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2211",
      "file": "drivers/usb/host/xhci-debugfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-debugfs.c:xhci_ring_trb_show"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500673592,
      "name": "xhci_decode_trb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2004
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Duplicate, Selective Inline ❓</summary>

```c
const char * xhci_decode_trb(u32 field0, u32 field1, u32 field2, u32 field3)
```

```json
{
  "name": "xhci_decode_trb",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3233133448,
      "name": "xhci_decode_trb",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2211",
      "file": "drivers/usb/host/xhci-trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_trb"
      ]
    },
    {
      "addr": 3233156044,
      "name": "xhci_decode_trb",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2211",
      "file": "drivers/usb/host/xhci-debugfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-debugfs.c:xhci_ring_trb_show"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3233133448,
      "name": "xhci_decode_trb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2124
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Duplicate, Selective Inline ❓</summary>

```c
const char * xhci_decode_trb(u32 field0, u32 field1, u32 field2, u32 field3)
```

```json
{
  "name": "xhci_decode_trb",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055294103536,
      "name": "xhci_decode_trb",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2211",
      "file": "drivers/usb/host/xhci-trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_trb"
      ]
    },
    {
      "addr": 13835058055294134296,
      "name": "xhci_decode_trb",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2211",
      "file": "drivers/usb/host/xhci-debugfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-debugfs.c:xhci_ring_trb_show"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294103536,
      "name": "xhci_decode_trb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3156
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Duplicate, Selective Inline ❓</summary>

```c
const char * xhci_decode_trb(u32 field0, u32 field1, u32 field2, u32 field3)
```

```json
{
  "name": "xhci_decode_trb",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936277534624,
      "name": "xhci_decode_trb",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2211",
      "file": "drivers/usb/host/xhci-trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_trb"
      ]
    },
    {
      "addr": 18446743936277555456,
      "name": "xhci_decode_trb",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2211",
      "file": "drivers/usb/host/xhci-debugfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-debugfs.c:xhci_ring_trb_show"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277534624,
      "name": "xhci_decode_trb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2004
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
const char * xhci_decode_trb(u32 field0, u32 field1, u32 field2, u32 field3)
```

```json
{
  "name": "xhci_decode_trb",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587239840,
      "name": "xhci_decode_trb",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2211",
      "file": "drivers/usb/host/xhci-trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_trb"
      ]
    },
    {
      "addr": 18446744071587251741,
      "name": "xhci_decode_trb",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2211",
      "file": "drivers/usb/host/xhci-debugfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-debugfs.c:xhci_ring_trb_show"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587239840,
      "name": "xhci_decode_trb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2248
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
const char * xhci_decode_trb(u32 field0, u32 field1, u32 field2, u32 field3)
```

```json
{
  "name": "xhci_decode_trb",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586998592,
      "name": "xhci_decode_trb",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2211",
      "file": "drivers/usb/host/xhci-trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_trb"
      ]
    },
    {
      "addr": 18446744071587020189,
      "name": "xhci_decode_trb",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2211",
      "file": "drivers/usb/host/xhci-debugfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-debugfs.c:xhci_ring_trb_show"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586998592,
      "name": "xhci_decode_trb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2248
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
const char * xhci_decode_trb(u32 field0, u32 field1, u32 field2, u32 field3)
```

```json
{
  "name": "xhci_decode_trb",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587488368,
      "name": "xhci_decode_trb",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2211",
      "file": "drivers/usb/host/xhci-trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_trb"
      ]
    },
    {
      "addr": 18446744071587509965,
      "name": "xhci_decode_trb",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2211",
      "file": "drivers/usb/host/xhci-debugfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-debugfs.c:xhci_ring_trb_show"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587488368,
      "name": "xhci_decode_trb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2248
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
const char * xhci_decode_trb(u32 field0, u32 field1, u32 field2, u32 field3)
```

```json
{
  "name": "xhci_decode_trb",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587596096,
      "name": "xhci_decode_trb",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2211",
      "file": "drivers/usb/host/xhci-trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/host/xhci-trace.c:trace_raw_output_xhci_log_trb"
      ]
    },
    {
      "addr": 18446744071587617837,
      "name": "xhci_decode_trb",
      "external": false,
      "loc": "drivers/usb/host/xhci.h:2211",
      "file": "drivers/usb/host/xhci-debugfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci-debugfs.c:xhci_ring_trb_show"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587596096,
      "name": "xhci_decode_trb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2248
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
const char * xhci_decode_trb(u32 field0, u32 field1, u32 field2, u32 field3)
```
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
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
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
const char * xhci_decode_trb(u32 field0, u32 field1, u32 field2, u32 field3)
```
</details>
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
