# Function: <code>put_pwq_unlocked</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void put_pwq_unlocked(struct pool_workqueue * pwq)
```

```json
{
  "name": "put_pwq_unlocked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579473088,
      "name": "put_pwq_unlocked",
      "external": false,
      "loc": "kernel/workqueue.c:1078",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:apply_wqattrs_cleanup",
        "kernel/workqueue.c:apply_wqattrs_cleanup",
        "kernel/workqueue.c:wq_update_unbound_numa"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579473088,
      "name": "put_pwq_unlocked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
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
void put_pwq_unlocked(struct pool_workqueue * pwq)
```

```json
{
  "name": "put_pwq_unlocked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579486784,
      "name": "put_pwq_unlocked",
      "external": false,
      "loc": "kernel/workqueue.c:1097",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:wq_update_unbound_numa",
        "kernel/workqueue.c:apply_wqattrs_cleanup",
        "kernel/workqueue.c:apply_wqattrs_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579486784,
      "name": "put_pwq_unlocked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
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
void put_pwq_unlocked(struct pool_workqueue * pwq)
```

```json
{
  "name": "put_pwq_unlocked",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579507616,
      "name": "put_pwq_unlocked",
      "external": false,
      "loc": "kernel/workqueue.c:1099",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:wq_update_unbound_numa",
        "kernel/workqueue.c:apply_wqattrs_cleanup",
        "kernel/workqueue.c:apply_wqattrs_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579507616,
      "name": "put_pwq_unlocked",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
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
  "name": "put_pwq_unlocked",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579509552,
      "name": "put_pwq_unlocked",
      "external": false,
      "loc": "kernel/workqueue.c:1099",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:wq_update_unbound_numa"
      ],
      "caller_func": [
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:wq_update_unbound_numa"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579495888,
      "name": "put_pwq_unlocked.part.26",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
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
  "name": "put_pwq_unlocked",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579536320,
      "name": "put_pwq_unlocked",
      "external": false,
      "loc": "kernel/workqueue.c:1101",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:wq_update_unbound_numa"
      ],
      "caller_func": [
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:wq_update_unbound_numa"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579522576,
      "name": "put_pwq_unlocked.part.27",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
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
  "name": "put_pwq_unlocked",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579562578,
      "name": "put_pwq_unlocked",
      "external": false,
      "loc": "kernel/workqueue.c:1099",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:wq_update_unbound_numa"
      ],
      "caller_func": [
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:wq_update_unbound_numa"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579550384,
      "name": "put_pwq_unlocked.part.32",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
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
  "name": "put_pwq_unlocked",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579599810,
      "name": "put_pwq_unlocked",
      "external": false,
      "loc": "kernel/workqueue.c:1119",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:wq_update_unbound_numa"
      ],
      "caller_func": [
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:wq_update_unbound_numa"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579586960,
      "name": "put_pwq_unlocked.part.33",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
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
  "name": "put_pwq_unlocked",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579623084,
      "name": "put_pwq_unlocked",
      "external": false,
      "loc": "kernel/workqueue.c:1127",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:wq_update_unbound_numa"
      ],
      "caller_func": [
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:wq_update_unbound_numa"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579611040,
      "name": "put_pwq_unlocked.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
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
  "name": "put_pwq_unlocked",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579649118,
      "name": "put_pwq_unlocked",
      "external": false,
      "loc": "kernel/workqueue.c:1128",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:wq_update_unbound_numa"
      ],
      "caller_func": [
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:wq_update_unbound_numa"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579636224,
      "name": "put_pwq_unlocked.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
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
  "name": "put_pwq_unlocked",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579680970,
      "name": "put_pwq_unlocked",
      "external": false,
      "loc": "kernel/workqueue.c:1125",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:wq_update_unbound_numa"
      ],
      "caller_func": [
        "kernel/workqueue.c:wq_update_unbound_numa"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579672800,
      "name": "put_pwq_unlocked.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
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
  "name": "put_pwq_unlocked",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579660810,
      "name": "put_pwq_unlocked",
      "external": false,
      "loc": "kernel/workqueue.c:1125",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:wq_update_unbound_numa"
      ],
      "caller_func": [
        "kernel/workqueue.c:wq_update_unbound_numa"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579652624,
      "name": "put_pwq_unlocked.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
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
  "name": "put_pwq_unlocked",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579666830,
      "name": "put_pwq_unlocked",
      "external": false,
      "loc": "kernel/workqueue.c:1126",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:wq_update_unbound_numa",
        "kernel/workqueue.c:wq_update_unbound_numa"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "put_pwq_unlocked",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579743658,
      "name": "put_pwq_unlocked",
      "external": false,
      "loc": "kernel/workqueue.c:1152",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:wq_update_unbound_numa"
      ],
      "caller_func": [
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:wq_update_unbound_numa"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579736064,
      "name": "put_pwq_unlocked.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
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
  "name": "put_pwq_unlocked",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579847953,
      "name": "put_pwq_unlocked",
      "external": false,
      "loc": "kernel/workqueue.c:1148",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:wq_update_unbound_numa"
      ],
      "caller_func": [
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:wq_update_unbound_numa"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579834608,
      "name": "put_pwq_unlocked.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
  "name": "put_pwq_unlocked",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579988313,
      "name": "put_pwq_unlocked",
      "external": false,
      "loc": "kernel/workqueue.c:1148",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:wq_update_unbound_numa"
      ],
      "caller_func": [
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:wq_update_unbound_numa"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579979536,
      "name": "put_pwq_unlocked.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
  "name": "put_pwq_unlocked",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580041476,
      "name": "put_pwq_unlocked",
      "external": false,
      "loc": "kernel/workqueue.c:1346",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:wq_update_unbound_numa"
      ],
      "caller_func": [
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:wq_update_unbound_numa"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580028640,
      "name": "put_pwq_unlocked.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
  "name": "put_pwq_unlocked",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580084134,
      "name": "put_pwq_unlocked",
      "external": false,
      "loc": "kernel/workqueue.c:1443",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:wq_update_pod",
        "kernel/workqueue.c:wq_update_pod"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "put_pwq_unlocked",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490821480,
      "name": "put_pwq_unlocked",
      "external": false,
      "loc": "kernel/workqueue.c:1128",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:wq_update_unbound_numa"
      ],
      "caller_func": [
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:wq_update_unbound_numa"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490807608,
      "name": "put_pwq_unlocked.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "put_pwq_unlocked",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3224854708,
      "name": "put_pwq_unlocked",
      "external": false,
      "loc": "kernel/workqueue.c:1128",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:apply_wqattrs_cleanup",
        "kernel/workqueue.c:apply_wqattrs_cleanup"
      ],
      "caller_func": [
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:apply_wqattrs_cleanup",
        "kernel/workqueue.c:apply_wqattrs_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224839324,
      "name": "put_pwq_unlocked.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "put_pwq_unlocked",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055283655296,
      "name": "put_pwq_unlocked",
      "external": false,
      "loc": "kernel/workqueue.c:1128",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:wq_update_unbound_numa"
      ],
      "caller_func": [
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:wq_update_unbound_numa"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283636464,
      "name": "put_pwq_unlocked.part.0",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "put_pwq_unlocked",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271495464,
      "name": "put_pwq_unlocked",
      "external": false,
      "loc": "kernel/workqueue.c:1128",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:apply_wqattrs_cleanup",
        "kernel/workqueue.c:apply_wqattrs_cleanup"
      ],
      "caller_func": [
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:apply_wqattrs_cleanup",
        "kernel/workqueue.c:apply_wqattrs_cleanup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271485786,
      "name": "put_pwq_unlocked.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "put_pwq_unlocked",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579625422,
      "name": "put_pwq_unlocked",
      "external": false,
      "loc": "kernel/workqueue.c:1128",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:wq_update_unbound_numa"
      ],
      "caller_func": [
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:wq_update_unbound_numa"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579612528,
      "name": "put_pwq_unlocked.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "put_pwq_unlocked",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579553784,
      "name": "put_pwq_unlocked",
      "external": false,
      "loc": "kernel/workqueue.c:1128",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:wq_update_unbound_numa"
      ],
      "caller_func": [
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:wq_update_unbound_numa"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579541568,
      "name": "put_pwq_unlocked.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "put_pwq_unlocked",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579622702,
      "name": "put_pwq_unlocked",
      "external": false,
      "loc": "kernel/workqueue.c:1128",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:wq_update_unbound_numa"
      ],
      "caller_func": [
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:wq_update_unbound_numa"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579609808,
      "name": "put_pwq_unlocked.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
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
  "name": "put_pwq_unlocked",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579656373,
      "name": "put_pwq_unlocked",
      "external": false,
      "loc": "kernel/workqueue.c:1128",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:wq_update_unbound_numa"
      ],
      "caller_func": [
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:destroy_workqueue",
        "kernel/workqueue.c:wq_update_unbound_numa"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579645312,
      "name": "put_pwq_unlocked.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
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
void put_pwq_unlocked(struct pool_workqueue * pwq)
```
</details>
</li>
</ul>
