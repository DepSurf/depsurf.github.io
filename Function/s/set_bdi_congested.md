# Function: <code>set_bdi_congested</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_bdi_congested",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582061970,
      "name": "set_bdi_congested",
      "external": false,
      "loc": "include/linux/backing-dev-defs.h:188",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_request_send_background_locked",
        "fs/fuse/dev.c:fuse_request_send_background_locked"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_bdi_congested",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582276098,
      "name": "set_bdi_congested",
      "external": false,
      "loc": "include/linux/backing-dev-defs.h:189",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_request_send_background_locked",
        "fs/fuse/dev.c:fuse_request_send_background_locked"
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
  "name": "set_bdi_congested",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582365474,
      "name": "set_bdi_congested",
      "external": false,
      "loc": "include/linux/backing-dev-defs.h:192",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_request_send_background_locked",
        "fs/fuse/dev.c:fuse_request_send_background_locked"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_bdi_congested",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582449836,
      "name": "set_bdi_congested",
      "external": false,
      "loc": "include/linux/backing-dev-defs.h:196",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_request_send_background_locked",
        "fs/fuse/dev.c:fuse_request_send_background_locked"
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
  "name": "set_bdi_congested",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582600627,
      "name": "set_bdi_congested",
      "external": false,
      "loc": "include/linux/backing-dev-defs.h:221",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_request_send_background_locked",
        "fs/fuse/dev.c:fuse_request_send_background_locked"
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
  "name": "set_bdi_congested",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582793422,
      "name": "set_bdi_congested",
      "external": false,
      "loc": "include/linux/backing-dev-defs.h:221",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_request_send_background_locked",
        "fs/fuse/dev.c:fuse_request_send_background_locked"
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
  "name": "set_bdi_congested",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582897841,
      "name": "set_bdi_congested",
      "external": false,
      "loc": "include/linux/backing-dev-defs.h:223",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_request_queue_background",
        "fs/fuse/dev.c:fuse_request_queue_background"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582945547,
      "name": "set_bdi_congested",
      "external": false,
      "loc": "include/linux/backing-dev-defs.h:223",
      "file": "fs/fuse/control.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/control.c:fuse_conn_congestion_threshold_write",
        "fs/fuse/control.c:fuse_conn_congestion_threshold_write"
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
  "name": "set_bdi_congested",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583076849,
      "name": "set_bdi_congested",
      "external": false,
      "loc": "include/linux/backing-dev-defs.h:222",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_request_queue_background",
        "fs/fuse/dev.c:fuse_request_queue_background"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583126127,
      "name": "set_bdi_congested",
      "external": false,
      "loc": "include/linux/backing-dev-defs.h:222",
      "file": "fs/fuse/control.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/control.c:fuse_conn_congestion_threshold_write",
        "fs/fuse/control.c:fuse_conn_congestion_threshold_write"
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
  "name": "set_bdi_congested",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583170245,
      "name": "set_bdi_congested",
      "external": false,
      "loc": "include/linux/backing-dev-defs.h:245",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_simple_background",
        "fs/fuse/dev.c:fuse_simple_background"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583232159,
      "name": "set_bdi_congested",
      "external": false,
      "loc": "include/linux/backing-dev-defs.h:245",
      "file": "fs/fuse/control.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/control.c:fuse_conn_congestion_threshold_write",
        "fs/fuse/control.c:fuse_conn_congestion_threshold_write"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_bdi_congested",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583490913,
      "name": "set_bdi_congested",
      "external": false,
      "loc": "include/linux/backing-dev-defs.h:243",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_request_queue_background",
        "fs/fuse/dev.c:fuse_request_queue_background"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583559430,
      "name": "set_bdi_congested",
      "external": false,
      "loc": "include/linux/backing-dev-defs.h:243",
      "file": "fs/fuse/control.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/control.c:fuse_conn_congestion_threshold_write",
        "fs/fuse/control.c:fuse_conn_congestion_threshold_write"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void set_bdi_congested(struct backing_dev_info * bdi, int sync)
```

```json
{
  "name": "set_bdi_congested",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581471200,
      "name": "set_bdi_congested",
      "external": true,
      "loc": "mm/backing-dev.c:933",
      "file": "mm/backing-dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_request_queue_background",
        "fs/fuse/dev.c:fuse_request_queue_background",
        "fs/fuse/control.c:fuse_conn_congestion_threshold_write",
        "fs/fuse/control.c:fuse_conn_congestion_threshold_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581471200,
      "name": "set_bdi_congested",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void set_bdi_congested(struct backing_dev_info * bdi, int sync)
```

```json
{
  "name": "set_bdi_congested",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581491984,
      "name": "set_bdi_congested",
      "external": true,
      "loc": "mm/backing-dev.c:932",
      "file": "mm/backing-dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_simple_background",
        "fs/fuse/dev.c:fuse_simple_background",
        "fs/fuse/control.c:fuse_conn_congestion_threshold_write",
        "fs/fuse/control.c:fuse_conn_congestion_threshold_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581491984,
      "name": "set_bdi_congested",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void set_bdi_congested(struct backing_dev_info * bdi, int sync)
```

```json
{
  "name": "set_bdi_congested",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581750816,
      "name": "set_bdi_congested",
      "external": true,
      "loc": "mm/backing-dev.c:1015",
      "file": "mm/backing-dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_simple_background",
        "fs/fuse/dev.c:fuse_simple_background",
        "fs/fuse/control.c:fuse_conn_congestion_threshold_write",
        "fs/fuse/control.c:fuse_conn_congestion_threshold_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581750816,
      "name": "set_bdi_congested",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "set_bdi_congested",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336494884772,
      "name": "set_bdi_congested",
      "external": false,
      "loc": "include/linux/backing-dev-defs.h:245",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_simple_background",
        "fs/fuse/dev.c:fuse_simple_background"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494954968,
      "name": "set_bdi_congested",
      "external": false,
      "loc": "include/linux/backing-dev-defs.h:245",
      "file": "fs/fuse/control.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/control.c:fuse_conn_congestion_threshold_write",
        "fs/fuse/control.c:fuse_conn_congestion_threshold_write"
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
  "name": "set_bdi_congested",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3228298836,
      "name": "set_bdi_congested",
      "external": false,
      "loc": "include/linux/backing-dev-defs.h:245",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_simple_background",
        "fs/fuse/dev.c:fuse_simple_background"
      ],
      "caller_func": []
    },
    {
      "addr": 3228362632,
      "name": "set_bdi_congested",
      "external": false,
      "loc": "include/linux/backing-dev-defs.h:245",
      "file": "fs/fuse/control.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/control.c:fuse_conn_congestion_threshold_write",
        "fs/fuse/control.c:fuse_conn_congestion_threshold_write"
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
  "name": "set_bdi_congested",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055288745836,
      "name": "set_bdi_congested",
      "external": false,
      "loc": "include/linux/backing-dev-defs.h:245",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_simple_background",
        "fs/fuse/dev.c:fuse_simple_background"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055288829728,
      "name": "set_bdi_congested",
      "external": false,
      "loc": "include/linux/backing-dev-defs.h:245",
      "file": "fs/fuse/control.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/control.c:fuse_conn_congestion_threshold_write",
        "fs/fuse/control.c:fuse_conn_congestion_threshold_write"
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
  "name": "set_bdi_congested",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936274200508,
      "name": "set_bdi_congested",
      "external": false,
      "loc": "include/linux/backing-dev-defs.h:245",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_simple_background",
        "fs/fuse/dev.c:fuse_simple_background"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274257612,
      "name": "set_bdi_congested",
      "external": false,
      "loc": "include/linux/backing-dev-defs.h:245",
      "file": "fs/fuse/control.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/control.c:fuse_conn_congestion_threshold_write",
        "fs/fuse/control.c:fuse_conn_congestion_threshold_write"
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
  "name": "set_bdi_congested",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583138981,
      "name": "set_bdi_congested",
      "external": false,
      "loc": "include/linux/backing-dev-defs.h:245",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_simple_background",
        "fs/fuse/dev.c:fuse_simple_background"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583200895,
      "name": "set_bdi_congested",
      "external": false,
      "loc": "include/linux/backing-dev-defs.h:245",
      "file": "fs/fuse/control.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/control.c:fuse_conn_congestion_threshold_write",
        "fs/fuse/control.c:fuse_conn_congestion_threshold_write"
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
  "name": "set_bdi_congested",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583076133,
      "name": "set_bdi_congested",
      "external": false,
      "loc": "include/linux/backing-dev-defs.h:245",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_simple_background",
        "fs/fuse/dev.c:fuse_simple_background"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583138047,
      "name": "set_bdi_congested",
      "external": false,
      "loc": "include/linux/backing-dev-defs.h:245",
      "file": "fs/fuse/control.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/control.c:fuse_conn_congestion_threshold_write",
        "fs/fuse/control.c:fuse_conn_congestion_threshold_write"
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
  "name": "set_bdi_congested",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583123013,
      "name": "set_bdi_congested",
      "external": false,
      "loc": "include/linux/backing-dev-defs.h:245",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_simple_background",
        "fs/fuse/dev.c:fuse_simple_background"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583184927,
      "name": "set_bdi_congested",
      "external": false,
      "loc": "include/linux/backing-dev-defs.h:245",
      "file": "fs/fuse/control.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/control.c:fuse_conn_congestion_threshold_write",
        "fs/fuse/control.c:fuse_conn_congestion_threshold_write"
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
  "name": "set_bdi_congested",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583217969,
      "name": "set_bdi_congested",
      "external": false,
      "loc": "include/linux/backing-dev-defs.h:245",
      "file": "fs/fuse/dev.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_simple_background",
        "fs/fuse/dev.c:fuse_simple_background"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583278125,
      "name": "set_bdi_congested",
      "external": false,
      "loc": "include/linux/backing-dev-defs.h:245",
      "file": "fs/fuse/control.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/fuse/control.c:fuse_conn_congestion_threshold_write",
        "fs/fuse/control.c:fuse_conn_congestion_threshold_write"
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
void set_bdi_congested(struct backing_dev_info * bdi, int sync)
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
void set_bdi_congested(struct backing_dev_info * bdi, int sync)
```
</details>
</li>
</ul>
