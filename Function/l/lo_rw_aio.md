# Function: <code>lo_rw_aio</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "lo_rw_aio",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584551089,
      "name": "lo_rw_aio",
      "external": false,
      "loc": "drivers/block/loop.c:476",
      "file": "drivers/block/loop.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:loop_queue_work"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int lo_rw_aio(struct loop_device * lo, struct loop_cmd * cmd, loff_t pos, bool rw)
```

```json
{
  "name": "lo_rw_aio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584898896,
      "name": "lo_rw_aio",
      "external": false,
      "loc": "drivers/block/loop.c:476",
      "file": "drivers/block/loop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:loop_queue_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584898896,
      "name": "lo_rw_aio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 628
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
int lo_rw_aio(struct loop_device * lo, struct loop_cmd * cmd, loff_t pos, bool rw)
```

```json
{
  "name": "lo_rw_aio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585088688,
      "name": "lo_rw_aio",
      "external": false,
      "loc": "drivers/block/loop.c:476",
      "file": "drivers/block/loop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:loop_queue_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585088688,
      "name": "lo_rw_aio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 650
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int lo_rw_aio(struct loop_device * lo, struct loop_cmd * cmd, loff_t pos, bool rw)
```

```json
{
  "name": "lo_rw_aio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585171424,
      "name": "lo_rw_aio",
      "external": false,
      "loc": "drivers/block/loop.c:471",
      "file": "drivers/block/loop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:loop_queue_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585171424,
      "name": "lo_rw_aio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 511
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
int lo_rw_aio(struct loop_device * lo, struct loop_cmd * cmd, loff_t pos, bool rw)
```

```json
{
  "name": "lo_rw_aio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585596384,
      "name": "lo_rw_aio",
      "external": false,
      "loc": "drivers/block/loop.c:485",
      "file": "drivers/block/loop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:loop_queue_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585596384,
      "name": "lo_rw_aio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1175
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
int lo_rw_aio(struct loop_device * lo, struct loop_cmd * cmd, loff_t pos, bool rw)
```

```json
{
  "name": "lo_rw_aio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585843456,
      "name": "lo_rw_aio",
      "external": false,
      "loc": "drivers/block/loop.c:509",
      "file": "drivers/block/loop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:loop_queue_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585843456,
      "name": "lo_rw_aio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1233
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
int lo_rw_aio(struct loop_device * lo, struct loop_cmd * cmd, loff_t pos, bool rw)
```

```json
{
  "name": "lo_rw_aio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585975392,
      "name": "lo_rw_aio",
      "external": false,
      "loc": "drivers/block/loop.c:510",
      "file": "drivers/block/loop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:loop_queue_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585975392,
      "name": "lo_rw_aio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1230
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
int lo_rw_aio(struct loop_device * lo, struct loop_cmd * cmd, loff_t pos, bool rw)
```

```json
{
  "name": "lo_rw_aio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586218656,
      "name": "lo_rw_aio",
      "external": false,
      "loc": "drivers/block/loop.c:510",
      "file": "drivers/block/loop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:loop_queue_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586218656,
      "name": "lo_rw_aio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 927
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
int lo_rw_aio(struct loop_device * lo, struct loop_cmd * cmd, loff_t pos, bool rw)
```

```json
{
  "name": "lo_rw_aio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586366704,
      "name": "lo_rw_aio",
      "external": false,
      "loc": "drivers/block/loop.c:512",
      "file": "drivers/block/loop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:loop_queue_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586366704,
      "name": "lo_rw_aio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 927
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
  "name": "lo_rw_aio",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587138256,
      "name": "lo_rw_aio",
      "external": false,
      "loc": "drivers/block/loop.c:525",
      "file": "drivers/block/loop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:do_req_filebacked",
        "drivers/block/loop.c:do_req_filebacked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587138256,
      "name": "lo_rw_aio.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 897
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
  "name": "lo_rw_aio",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587224240,
      "name": "lo_rw_aio",
      "external": false,
      "loc": "drivers/block/loop.c:523",
      "file": "drivers/block/loop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:do_req_filebacked",
        "drivers/block/loop.c:do_req_filebacked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587224240,
      "name": "lo_rw_aio.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 692
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
  "name": "lo_rw_aio",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587111440,
      "name": "lo_rw_aio",
      "external": false,
      "loc": "drivers/block/loop.c:565",
      "file": "drivers/block/loop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:do_req_filebacked",
        "drivers/block/loop.c:do_req_filebacked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587111440,
      "name": "lo_rw_aio.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 692
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
  "name": "lo_rw_aio",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587685904,
      "name": "lo_rw_aio",
      "external": false,
      "loc": "drivers/block/loop.c:553",
      "file": "drivers/block/loop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:do_req_filebacked",
        "drivers/block/loop.c:do_req_filebacked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587685904,
      "name": "lo_rw_aio.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 668
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
  "name": "lo_rw_aio",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589031616,
      "name": "lo_rw_aio",
      "external": false,
      "loc": "drivers/block/loop.c:394",
      "file": "drivers/block/loop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:do_req_filebacked",
        "drivers/block/loop.c:do_req_filebacked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589031616,
      "name": "lo_rw_aio.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 745
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
  "name": "lo_rw_aio",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590560112,
      "name": "lo_rw_aio",
      "external": false,
      "loc": "drivers/block/loop.c:394",
      "file": "drivers/block/loop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:do_req_filebacked",
        "drivers/block/loop.c:do_req_filebacked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590560112,
      "name": "lo_rw_aio.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 753
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
  "name": "lo_rw_aio",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590888528,
      "name": "lo_rw_aio",
      "external": false,
      "loc": "drivers/block/loop.c:394",
      "file": "drivers/block/loop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:do_req_filebacked",
        "drivers/block/loop.c:do_req_filebacked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590888528,
      "name": "lo_rw_aio.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 688
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
  "name": "lo_rw_aio",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591232384,
      "name": "lo_rw_aio",
      "external": false,
      "loc": "drivers/block/loop.c:390",
      "file": "drivers/block/loop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:do_req_filebacked",
        "drivers/block/loop.c:do_req_filebacked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591232384,
      "name": "lo_rw_aio.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 688
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
  "name": "lo_rw_aio",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336499209040,
      "name": "lo_rw_aio",
      "external": false,
      "loc": "drivers/block/loop.c:512",
      "file": "drivers/block/loop.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:loop_queue_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499209040,
      "name": "lo_rw_aio.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 944
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
int lo_rw_aio(struct loop_device * lo, struct loop_cmd * cmd, loff_t pos, bool rw)
```

```json
{
  "name": "lo_rw_aio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231745204,
      "name": "lo_rw_aio",
      "external": false,
      "loc": "drivers/block/loop.c:512",
      "file": "drivers/block/loop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:loop_queue_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231745204,
      "name": "lo_rw_aio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1148
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
int lo_rw_aio(struct loop_device * lo, struct loop_cmd * cmd, loff_t pos, bool rw)
```

```json
{
  "name": "lo_rw_aio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292418816,
      "name": "lo_rw_aio",
      "external": false,
      "loc": "drivers/block/loop.c:512",
      "file": "drivers/block/loop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:loop_queue_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292418816,
      "name": "lo_rw_aio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1296
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
int lo_rw_aio(struct loop_device * lo, struct loop_cmd * cmd, loff_t pos, bool rw)
```

```json
{
  "name": "lo_rw_aio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276500902,
      "name": "lo_rw_aio",
      "external": false,
      "loc": "drivers/block/loop.c:512",
      "file": "drivers/block/loop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_queue_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276500902,
      "name": "lo_rw_aio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 802
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
int lo_rw_aio(struct loop_device * lo, struct loop_cmd * cmd, loff_t pos, bool rw)
```

```json
{
  "name": "lo_rw_aio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586128592,
      "name": "lo_rw_aio",
      "external": false,
      "loc": "drivers/block/loop.c:512",
      "file": "drivers/block/loop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:loop_queue_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586128592,
      "name": "lo_rw_aio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 927
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int lo_rw_aio(struct loop_device * lo, struct loop_cmd * cmd, loff_t pos, bool rw)
```

```json
{
  "name": "lo_rw_aio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585973200,
      "name": "lo_rw_aio",
      "external": false,
      "loc": "drivers/block/loop.c:512",
      "file": "drivers/block/loop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:loop_queue_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585973200,
      "name": "lo_rw_aio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 927
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int lo_rw_aio(struct loop_device * lo, struct loop_cmd * cmd, loff_t pos, bool rw)
```

```json
{
  "name": "lo_rw_aio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586314672,
      "name": "lo_rw_aio",
      "external": false,
      "loc": "drivers/block/loop.c:512",
      "file": "drivers/block/loop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:loop_queue_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586314672,
      "name": "lo_rw_aio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 927
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
int lo_rw_aio(struct loop_device * lo, struct loop_cmd * cmd, loff_t pos, bool rw)
```

```json
{
  "name": "lo_rw_aio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586426224,
      "name": "lo_rw_aio",
      "external": false,
      "loc": "drivers/block/loop.c:512",
      "file": "drivers/block/loop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/block/loop.c:loop_queue_work",
        "drivers/block/loop.c:loop_queue_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586426224,
      "name": "lo_rw_aio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 927
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
int lo_rw_aio(struct loop_device * lo, struct loop_cmd * cmd, loff_t pos, bool rw)
```
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int lo_rw_aio(struct loop_device * lo, struct loop_cmd * cmd, loff_t pos, bool rw)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int lo_rw_aio(struct loop_device * lo, struct loop_cmd * cmd, loff_t pos, bool rw)
```
</details>
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
