# Function: <code>__xenbus_map_ring</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int __xenbus_map_ring(struct xenbus_device * dev, grant_ref_t * gnt_refs, unsigned int nr_grefs, grant_handle_t * handles, phys_addr_t * addrs, unsigned int flags, bool * leaked)
```

```json
{
  "name": "__xenbus_map_ring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583874240,
      "name": "__xenbus_map_ring",
      "external": false,
      "loc": "drivers/xen/xenbus/xenbus_client.c:479",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_pv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583874240,
      "name": "__xenbus_map_ring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 824
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int __xenbus_map_ring(struct xenbus_device * dev, grant_ref_t * gnt_refs, unsigned int nr_grefs, grant_handle_t * handles, phys_addr_t * addrs, unsigned int flags, bool * leaked)
```

```json
{
  "name": "__xenbus_map_ring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584204960,
      "name": "__xenbus_map_ring",
      "external": false,
      "loc": "drivers/xen/xenbus/xenbus_client.c:479",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_pv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584204960,
      "name": "__xenbus_map_ring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 830
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int __xenbus_map_ring(struct xenbus_device * dev, grant_ref_t * gnt_refs, unsigned int nr_grefs, grant_handle_t * handles, phys_addr_t * addrs, unsigned int flags, bool * leaked)
```

```json
{
  "name": "__xenbus_map_ring",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584386416,
      "name": "__xenbus_map_ring",
      "external": false,
      "loc": "drivers/xen/xenbus/xenbus_client.c:479",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_pv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584386416,
      "name": "__xenbus_map_ring",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 830
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__xenbus_map_ring",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584468906,
      "name": "__xenbus_map_ring",
      "external": false,
      "loc": "drivers/xen/xenbus/xenbus_client.c:460",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_pv"
      ],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_pv"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584467760,
      "name": "__xenbus_map_ring.part.5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 744
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__xenbus_map_ring",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584879874,
      "name": "__xenbus_map_ring",
      "external": false,
      "loc": "drivers/xen/xenbus/xenbus_client.c:460",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_pv",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm"
      ],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_pv",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584878128,
      "name": "__xenbus_map_ring.part.5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 744
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__xenbus_map_ring",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585111343,
      "name": "__xenbus_map_ring",
      "external": false,
      "loc": "drivers/xen/xenbus/xenbus_client.c:460",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_pv",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm"
      ],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_pv",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585108192,
      "name": "__xenbus_map_ring.part.6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 756
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__xenbus_map_ring",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585222703,
      "name": "__xenbus_map_ring",
      "external": false,
      "loc": "drivers/xen/xenbus/xenbus_client.c:458",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_pv",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm"
      ],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_pv",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585218960,
      "name": "__xenbus_map_ring.part.6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 756
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__xenbus_map_ring",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585434749,
      "name": "__xenbus_map_ring",
      "external": false,
      "loc": "drivers/xen/xenbus/xenbus_client.c:458",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_pv",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm"
      ],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_pv",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585431232,
      "name": "__xenbus_map_ring.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 696
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__xenbus_map_ring",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585575197,
      "name": "__xenbus_map_ring",
      "external": false,
      "loc": "drivers/xen/xenbus/xenbus_client.c:458",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_pv",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm"
      ],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_pv",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585571680,
      "name": "__xenbus_map_ring.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 696
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__xenbus_map_ring",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586296205,
      "name": "__xenbus_map_ring",
      "external": false,
      "loc": "drivers/xen/xenbus/xenbus_client.c:499",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_pv",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_hvm"
      ],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_pv",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_hvm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586292848,
      "name": "__xenbus_map_ring.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 574
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__xenbus_map_ring",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586415373,
      "name": "__xenbus_map_ring",
      "external": false,
      "loc": "drivers/xen/xenbus/xenbus_client.c:502",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_pv",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_hvm"
      ],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_pv",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_hvm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586411968,
      "name": "__xenbus_map_ring.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 582
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
  "name": "__xenbus_map_ring",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586299197,
      "name": "__xenbus_map_ring",
      "external": false,
      "loc": "drivers/xen/xenbus/xenbus_client.c:502",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_pv",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_hvm"
      ],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_pv",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_hvm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586295808,
      "name": "__xenbus_map_ring.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 580
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
  "name": "__xenbus_map_ring",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586818653,
      "name": "__xenbus_map_ring",
      "external": false,
      "loc": "drivers/xen/xenbus/xenbus_client.c:500",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_pv",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_hvm"
      ],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_pv",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_hvm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586814416,
      "name": "__xenbus_map_ring.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1056
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
  "name": "__xenbus_map_ring",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588098717,
      "name": "__xenbus_map_ring",
      "external": false,
      "loc": "drivers/xen/xenbus/xenbus_client.c:542",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_pv",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_hvm"
      ],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_pv",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_hvm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588097472,
      "name": "__xenbus_map_ring.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1095
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
  "name": "__xenbus_map_ring",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589483533,
      "name": "__xenbus_map_ring",
      "external": false,
      "loc": "drivers/xen/xenbus/xenbus_client.c:545",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_pv",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_hvm"
      ],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_pv",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_hvm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589482272,
      "name": "__xenbus_map_ring.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1095
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
  "name": "__xenbus_map_ring",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589783997,
      "name": "__xenbus_map_ring",
      "external": false,
      "loc": "drivers/xen/xenbus/xenbus_client.c:545",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_pv",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_hvm"
      ],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_pv",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_hvm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589782736,
      "name": "__xenbus_map_ring.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1099
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
  "name": "__xenbus_map_ring",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590120029,
      "name": "__xenbus_map_ring",
      "external": false,
      "loc": "drivers/xen/xenbus/xenbus_client.c:555",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_pv",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_hvm"
      ],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_pv",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_hvm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590118768,
      "name": "__xenbus_map_ring.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1099
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
  "name": "__xenbus_map_ring",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336498238412,
      "name": "__xenbus_map_ring",
      "external": false,
      "loc": "drivers/xen/xenbus/xenbus_client.c:458",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm"
      ],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498237080,
      "name": "__xenbus_map_ring.part.0.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 700
    }
  ]
}
```
</details>
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__xenbus_map_ring",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585337229,
      "name": "__xenbus_map_ring",
      "external": false,
      "loc": "drivers/xen/xenbus/xenbus_client.c:458",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_pv",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm"
      ],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_pv",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585333712,
      "name": "__xenbus_map_ring.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 696
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__xenbus_map_ring",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585525597,
      "name": "__xenbus_map_ring",
      "external": false,
      "loc": "drivers/xen/xenbus/xenbus_client.c:458",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_pv",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm"
      ],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_pv",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585522080,
      "name": "__xenbus_map_ring.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 696
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__xenbus_map_ring",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585632653,
      "name": "__xenbus_map_ring",
      "external": false,
      "loc": "drivers/xen/xenbus/xenbus_client.c:458",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_pv",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm"
      ],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_pv",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585630976,
      "name": "__xenbus_map_ring.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 696
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
int __xenbus_map_ring(struct xenbus_device * dev, grant_ref_t * gnt_refs, unsigned int nr_grefs, grant_handle_t * handles, phys_addr_t * addrs, unsigned int flags, bool * leaked)
```
</details>
</li>
</ul>
