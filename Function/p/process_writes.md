# Function: <code>process_writes</code>

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
  "name": "process_writes",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584471646,
      "name": "process_writes",
      "external": false,
      "loc": "drivers/xen/xenbus/xenbus_comms.c:335",
      "file": "drivers/xen/xenbus/xenbus_comms.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_comms.c:xenbus_thread"
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
  "name": "process_writes",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584882030,
      "name": "process_writes",
      "external": false,
      "loc": "drivers/xen/xenbus/xenbus_comms.c:336",
      "file": "drivers/xen/xenbus/xenbus_comms.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_comms.c:xenbus_thread"
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
  "name": "process_writes",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585113400,
      "name": "process_writes",
      "external": false,
      "loc": "drivers/xen/xenbus/xenbus_comms.c:336",
      "file": "drivers/xen/xenbus/xenbus_comms.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_comms.c:xenbus_thread"
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
  "name": "process_writes",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585224168,
      "name": "process_writes",
      "external": false,
      "loc": "drivers/xen/xenbus/xenbus_comms.c:336",
      "file": "drivers/xen/xenbus/xenbus_comms.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_comms.c:xenbus_thread"
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
  "name": "process_writes",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585436352,
      "name": "process_writes",
      "external": false,
      "loc": "drivers/xen/xenbus/xenbus_comms.c:336",
      "file": "drivers/xen/xenbus/xenbus_comms.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_comms.c:xenbus_thread"
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
  "name": "process_writes",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585576800,
      "name": "process_writes",
      "external": false,
      "loc": "drivers/xen/xenbus/xenbus_comms.c:338",
      "file": "drivers/xen/xenbus/xenbus_comms.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_comms.c:xenbus_thread"
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
int process_writes()
```

```json
{
  "name": "process_writes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586298368,
      "name": "process_writes",
      "external": false,
      "loc": "drivers/xen/xenbus/xenbus_comms.c:338",
      "file": "drivers/xen/xenbus/xenbus_comms.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_comms.c:xenbus_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586298368,
      "name": "process_writes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 514
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
int process_writes()
```

```json
{
  "name": "process_writes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586417216,
      "name": "process_writes",
      "external": false,
      "loc": "drivers/xen/xenbus/xenbus_comms.c:330",
      "file": "drivers/xen/xenbus/xenbus_comms.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_comms.c:xenbus_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586417216,
      "name": "process_writes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 514
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
int process_writes()
```

```json
{
  "name": "process_writes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586300608,
      "name": "process_writes",
      "external": false,
      "loc": "drivers/xen/xenbus/xenbus_comms.c:330",
      "file": "drivers/xen/xenbus/xenbus_comms.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_comms.c:xenbus_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586300608,
      "name": "process_writes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 934
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
int process_writes()
```

```json
{
  "name": "process_writes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586820144,
      "name": "process_writes",
      "external": false,
      "loc": "drivers/xen/xenbus/xenbus_comms.c:330",
      "file": "drivers/xen/xenbus/xenbus_comms.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_comms.c:xenbus_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586820144,
      "name": "process_writes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 934
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
int process_writes()
```

```json
{
  "name": "process_writes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588103872,
      "name": "process_writes",
      "external": false,
      "loc": "drivers/xen/xenbus/xenbus_comms.c:330",
      "file": "drivers/xen/xenbus/xenbus_comms.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_comms.c:xenbus_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588103872,
      "name": "process_writes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 530
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
int process_writes()
```

```json
{
  "name": "process_writes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589488960,
      "name": "process_writes",
      "external": false,
      "loc": "drivers/xen/xenbus/xenbus_comms.c:330",
      "file": "drivers/xen/xenbus/xenbus_comms.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_comms.c:xenbus_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589488960,
      "name": "process_writes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 530
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
int process_writes()
```

```json
{
  "name": "process_writes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589789616,
      "name": "process_writes",
      "external": false,
      "loc": "drivers/xen/xenbus/xenbus_comms.c:330",
      "file": "drivers/xen/xenbus/xenbus_comms.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_comms.c:xenbus_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589789616,
      "name": "process_writes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 530
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
int process_writes()
```

```json
{
  "name": "process_writes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590125744,
      "name": "process_writes",
      "external": false,
      "loc": "drivers/xen/xenbus/xenbus_comms.c:330",
      "file": "drivers/xen/xenbus/xenbus_comms.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/xen/xenbus/xenbus_comms.c:xenbus_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590125744,
      "name": "process_writes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 530
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
  "name": "process_writes",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336498240520,
      "name": "process_writes",
      "external": false,
      "loc": "drivers/xen/xenbus/xenbus_comms.c:338",
      "file": "drivers/xen/xenbus/xenbus_comms.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_comms.c:xenbus_thread"
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
  "name": "process_writes",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585338832,
      "name": "process_writes",
      "external": false,
      "loc": "drivers/xen/xenbus/xenbus_comms.c:338",
      "file": "drivers/xen/xenbus/xenbus_comms.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_comms.c:xenbus_thread"
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
  "name": "process_writes",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585527200,
      "name": "process_writes",
      "external": false,
      "loc": "drivers/xen/xenbus/xenbus_comms.c:338",
      "file": "drivers/xen/xenbus/xenbus_comms.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_comms.c:xenbus_thread"
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
  "name": "process_writes",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585635227,
      "name": "process_writes",
      "external": false,
      "loc": "drivers/xen/xenbus/xenbus_comms.c:338",
      "file": "drivers/xen/xenbus/xenbus_comms.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_comms.c:xenbus_thread"
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
int process_writes()
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
