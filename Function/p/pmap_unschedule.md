# Function: <code>pmap_unschedule</code>

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
  "name": "pmap_unschedule",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585716141,
      "name": "pmap_unschedule",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_queue.c:337",
      "file": "drivers/usb/dwc2/hcd_queue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hs_pmap_unschedule"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pmap_unschedule",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585904765,
      "name": "pmap_unschedule",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_queue.c:337",
      "file": "drivers/usb/dwc2/hcd_queue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hs_pmap_unschedule"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void pmap_unschedule(long unsigned int * map, int bits_per_period, int periods_in_map, int num_bits, int interval, int start)
```

```json
{
  "name": "pmap_unschedule",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585985840,
      "name": "pmap_unschedule",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_queue.c:336",
      "file": "drivers/usb/dwc2/hcd_queue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hs_pmap_unschedule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585985840,
      "name": "pmap_unschedule",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void pmap_unschedule(long unsigned int * map, int bits_per_period, int periods_in_map, int num_bits, int interval, int start)
```

```json
{
  "name": "pmap_unschedule",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586429824,
      "name": "pmap_unschedule",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_queue.c:337",
      "file": "drivers/usb/dwc2/hcd_queue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hs_pmap_unschedule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586429824,
      "name": "pmap_unschedule",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void pmap_unschedule(long unsigned int * map, int bits_per_period, int periods_in_map, int num_bits, int interval, int start)
```

```json
{
  "name": "pmap_unschedule",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586694128,
      "name": "pmap_unschedule",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_queue.c:340",
      "file": "drivers/usb/dwc2/hcd_queue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hs_pmap_unschedule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586694128,
      "name": "pmap_unschedule",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void pmap_unschedule(long unsigned int * map, int bits_per_period, int periods_in_map, int num_bits, int interval, int start)
```

```json
{
  "name": "pmap_unschedule",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586851152,
      "name": "pmap_unschedule",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_queue.c:340",
      "file": "drivers/usb/dwc2/hcd_queue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hs_pmap_unschedule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586851152,
      "name": "pmap_unschedule",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void pmap_unschedule(long unsigned int * map, int bits_per_period, int periods_in_map, int num_bits, int interval, int start)
```

```json
{
  "name": "pmap_unschedule",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587109456,
      "name": "pmap_unschedule",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_queue.c:340",
      "file": "drivers/usb/dwc2/hcd_queue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hs_pmap_unschedule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587109456,
      "name": "pmap_unschedule",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void pmap_unschedule(long unsigned int * map, int bits_per_period, int periods_in_map, int num_bits, int interval, int start)
```

```json
{
  "name": "pmap_unschedule",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587309856,
      "name": "pmap_unschedule",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_queue.c:340",
      "file": "drivers/usb/dwc2/hcd_queue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hs_pmap_unschedule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587309856,
      "name": "pmap_unschedule",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void pmap_unschedule(long unsigned int * map, int bits_per_period, int periods_in_map, int num_bits, int interval, int start)
```

```json
{
  "name": "pmap_unschedule",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588166000,
      "name": "pmap_unschedule",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_queue.c:340",
      "file": "drivers/usb/dwc2/hcd_queue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_queue.c:dwc2_do_unreserve",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_uframe_schedule_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588166000,
      "name": "pmap_unschedule",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
void pmap_unschedule(long unsigned int * map, int bits_per_period, int periods_in_map, int num_bits, int interval, int start)
```

```json
{
  "name": "pmap_unschedule",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588204112,
      "name": "pmap_unschedule",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_queue.c:340",
      "file": "drivers/usb/dwc2/hcd_queue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_queue.c:dwc2_do_unreserve",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_uframe_schedule_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588204112,
      "name": "pmap_unschedule",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
void pmap_unschedule(long unsigned int * map, int bits_per_period, int periods_in_map, int num_bits, int interval, int start)
```

```json
{
  "name": "pmap_unschedule",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588087376,
      "name": "pmap_unschedule",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_queue.c:340",
      "file": "drivers/usb/dwc2/hcd_queue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_queue.c:dwc2_do_unreserve",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_uframe_schedule_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588087376,
      "name": "pmap_unschedule",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
void pmap_unschedule(long unsigned int * map, int bits_per_period, int periods_in_map, int num_bits, int interval, int start)
```

```json
{
  "name": "pmap_unschedule",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588720336,
      "name": "pmap_unschedule",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_queue.c:340",
      "file": "drivers/usb/dwc2/hcd_queue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_queue.c:dwc2_do_unreserve",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_uframe_schedule_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588720336,
      "name": "pmap_unschedule",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
void pmap_unschedule(long unsigned int * map, int bits_per_period, int periods_in_map, int num_bits, int interval, int start)
```

```json
{
  "name": "pmap_unschedule",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590138400,
      "name": "pmap_unschedule",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_queue.c:340",
      "file": "drivers/usb/dwc2/hcd_queue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_queue.c:dwc2_do_unreserve",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_uframe_schedule_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590138400,
      "name": "pmap_unschedule",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
void pmap_unschedule(long unsigned int * map, int bits_per_period, int periods_in_map, int num_bits, int interval, int start)
```

```json
{
  "name": "pmap_unschedule",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591752352,
      "name": "pmap_unschedule",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_queue.c:310",
      "file": "drivers/usb/dwc2/hcd_queue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_queue.c:dwc2_do_unreserve",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_uframe_schedule_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591752352,
      "name": "pmap_unschedule",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
void pmap_unschedule(long unsigned int * map, int bits_per_period, int periods_in_map, int num_bits, int interval, int start)
```

```json
{
  "name": "pmap_unschedule",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592175680,
      "name": "pmap_unschedule",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_queue.c:310",
      "file": "drivers/usb/dwc2/hcd_queue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_queue.c:dwc2_do_unreserve",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_uframe_schedule_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592175680,
      "name": "pmap_unschedule",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
void pmap_unschedule(long unsigned int * map, int bits_per_period, int periods_in_map, int num_bits, int interval, int start)
```

```json
{
  "name": "pmap_unschedule",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592916368,
      "name": "pmap_unschedule",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_queue.c:310",
      "file": "drivers/usb/dwc2/hcd_queue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_queue.c:dwc2_do_unreserve",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_uframe_schedule_split"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592916368,
      "name": "pmap_unschedule",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void pmap_unschedule(long unsigned int * map, int bits_per_period, int periods_in_map, int num_bits, int interval, int start)
```

```json
{
  "name": "pmap_unschedule",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500427056,
      "name": "pmap_unschedule",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_queue.c:340",
      "file": "drivers/usb/dwc2/hcd_queue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hs_pmap_unschedule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500427056,
      "name": "pmap_unschedule",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void pmap_unschedule(long unsigned int * map, int bits_per_period, int periods_in_map, int num_bits, int interval, int start)
```

```json
{
  "name": "pmap_unschedule",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232881640,
      "name": "pmap_unschedule",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_queue.c:340",
      "file": "drivers/usb/dwc2/hcd_queue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hs_pmap_unschedule",
        "drivers/usb/dwc2/hcd_queue.c:dwc2_ls_pmap_unschedule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232881640,
      "name": "pmap_unschedule",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void pmap_unschedule(long unsigned int * map, int bits_per_period, int periods_in_map, int num_bits, int interval, int start)
```

```json
{
  "name": "pmap_unschedule",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293773680,
      "name": "pmap_unschedule",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_queue.c:340",
      "file": "drivers/usb/dwc2/hcd_queue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hs_pmap_unschedule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293773680,
      "name": "pmap_unschedule",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void pmap_unschedule(long unsigned int * map, int bits_per_period, int periods_in_map, int num_bits, int interval, int start)
```

```json
{
  "name": "pmap_unschedule",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277317786,
      "name": "pmap_unschedule",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_queue.c:340",
      "file": "drivers/usb/dwc2/hcd_queue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hs_pmap_unschedule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277317786,
      "name": "pmap_unschedule",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void pmap_unschedule(long unsigned int * map, int bits_per_period, int periods_in_map, int num_bits, int interval, int start)
```

```json
{
  "name": "pmap_unschedule",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587015936,
      "name": "pmap_unschedule",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_queue.c:340",
      "file": "drivers/usb/dwc2/hcd_queue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hs_pmap_unschedule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587015936,
      "name": "pmap_unschedule",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void pmap_unschedule(long unsigned int * map, int bits_per_period, int periods_in_map, int num_bits, int interval, int start)
```

```json
{
  "name": "pmap_unschedule",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587264416,
      "name": "pmap_unschedule",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_queue.c:340",
      "file": "drivers/usb/dwc2/hcd_queue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hs_pmap_unschedule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587264416,
      "name": "pmap_unschedule",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void pmap_unschedule(long unsigned int * map, int bits_per_period, int periods_in_map, int num_bits, int interval, int start)
```

```json
{
  "name": "pmap_unschedule",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587371184,
      "name": "pmap_unschedule",
      "external": false,
      "loc": "drivers/usb/dwc2/hcd_queue.c:340",
      "file": "drivers/usb/dwc2/hcd_queue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/dwc2/hcd_queue.c:dwc2_hs_pmap_unschedule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587371184,
      "name": "pmap_unschedule",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void pmap_unschedule(long unsigned int * map, int bits_per_period, int periods_in_map, int num_bits, int interval, int start)
```
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
void pmap_unschedule(long unsigned int * map, int bits_per_period, int periods_in_map, int num_bits, int interval, int start)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
