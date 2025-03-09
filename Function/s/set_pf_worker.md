# Function: <code>set_pf_worker</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void set_pf_worker(bool val)
```

```json
{
  "name": "set_pf_worker",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579540768,
      "name": "set_pf_worker",
      "external": false,
      "loc": "kernel/workqueue.c:2216",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:rescuer_thread",
        "kernel/workqueue.c:rescuer_thread",
        "kernel/workqueue.c:worker_thread",
        "kernel/workqueue.c:worker_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579540768,
      "name": "set_pf_worker",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
void set_pf_worker(bool val)
```

```json
{
  "name": "set_pf_worker",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579577760,
      "name": "set_pf_worker",
      "external": false,
      "loc": "kernel/workqueue.c:2239",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:rescuer_thread",
        "kernel/workqueue.c:rescuer_thread",
        "kernel/workqueue.c:worker_thread",
        "kernel/workqueue.c:worker_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579577760,
      "name": "set_pf_worker",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
void set_pf_worker(bool val)
```

```json
{
  "name": "set_pf_worker",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579601264,
      "name": "set_pf_worker",
      "external": false,
      "loc": "kernel/workqueue.c:2335",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:rescuer_thread",
        "kernel/workqueue.c:rescuer_thread",
        "kernel/workqueue.c:worker_thread",
        "kernel/workqueue.c:worker_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579601264,
      "name": "set_pf_worker",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
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
void set_pf_worker(bool val)
```

```json
{
  "name": "set_pf_worker",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579627072,
      "name": "set_pf_worker",
      "external": false,
      "loc": "kernel/workqueue.c:2338",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:rescuer_thread",
        "kernel/workqueue.c:rescuer_thread",
        "kernel/workqueue.c:worker_thread",
        "kernel/workqueue.c:worker_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579627072,
      "name": "set_pf_worker",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
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
  "name": "set_pf_worker",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579671879,
      "name": "set_pf_worker",
      "external": false,
      "loc": "kernel/workqueue.c:2335",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:rescuer_thread",
        "kernel/workqueue.c:rescuer_thread",
        "kernel/workqueue.c:worker_thread",
        "kernel/workqueue.c:worker_thread"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_pf_worker",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579651735,
      "name": "set_pf_worker",
      "external": false,
      "loc": "kernel/workqueue.c:2341",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:rescuer_thread",
        "kernel/workqueue.c:rescuer_thread",
        "kernel/workqueue.c:worker_thread",
        "kernel/workqueue.c:worker_thread"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_pf_worker",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579658199,
      "name": "set_pf_worker",
      "external": false,
      "loc": "kernel/workqueue.c:2342",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:rescuer_thread",
        "kernel/workqueue.c:rescuer_thread",
        "kernel/workqueue.c:worker_thread",
        "kernel/workqueue.c:worker_thread"
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
  "name": "set_pf_worker",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579735175,
      "name": "set_pf_worker",
      "external": false,
      "loc": "kernel/workqueue.c:2373",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:rescuer_thread",
        "kernel/workqueue.c:rescuer_thread",
        "kernel/workqueue.c:worker_thread",
        "kernel/workqueue.c:worker_thread"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_pf_worker",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579838647,
      "name": "set_pf_worker",
      "external": false,
      "loc": "kernel/workqueue.c:2356",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:rescuer_thread",
        "kernel/workqueue.c:rescuer_thread",
        "kernel/workqueue.c:worker_thread",
        "kernel/workqueue.c:worker_thread"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_pf_worker",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579978631,
      "name": "set_pf_worker",
      "external": false,
      "loc": "kernel/workqueue.c:2356",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:rescuer_thread",
        "kernel/workqueue.c:rescuer_thread",
        "kernel/workqueue.c:worker_thread",
        "kernel/workqueue.c:worker_thread"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_pf_worker",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580031559,
      "name": "set_pf_worker",
      "external": false,
      "loc": "kernel/workqueue.c:2671",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:rescuer_thread",
        "kernel/workqueue.c:rescuer_thread",
        "kernel/workqueue.c:worker_thread",
        "kernel/workqueue.c:worker_thread"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "set_pf_worker",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580067903,
      "name": "set_pf_worker",
      "external": false,
      "loc": "kernel/workqueue.c:2710",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:rescuer_thread",
        "kernel/workqueue.c:rescuer_thread",
        "kernel/workqueue.c:worker_thread",
        "kernel/workqueue.c:worker_thread"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void set_pf_worker(bool val)
```

```json
{
  "name": "set_pf_worker",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490793216,
      "name": "set_pf_worker",
      "external": false,
      "loc": "kernel/workqueue.c:2338",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:rescuer_thread",
        "kernel/workqueue.c:rescuer_thread",
        "kernel/workqueue.c:worker_thread",
        "kernel/workqueue.c:worker_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490793216,
      "name": "set_pf_worker",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
void set_pf_worker(bool val)
```

```json
{
  "name": "set_pf_worker",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224829328,
      "name": "set_pf_worker",
      "external": false,
      "loc": "kernel/workqueue.c:2338",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:rescuer_thread",
        "kernel/workqueue.c:rescuer_thread",
        "kernel/workqueue.c:worker_thread",
        "kernel/workqueue.c:worker_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224829328,
      "name": "set_pf_worker",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
void set_pf_worker(bool val)
```

```json
{
  "name": "set_pf_worker",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283619792,
      "name": "set_pf_worker",
      "external": false,
      "loc": "kernel/workqueue.c:2338",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:rescuer_thread",
        "kernel/workqueue.c:rescuer_thread",
        "kernel/workqueue.c:worker_thread",
        "kernel/workqueue.c:worker_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283619792,
      "name": "set_pf_worker",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void set_pf_worker(bool val)
```

```json
{
  "name": "set_pf_worker",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271474138,
      "name": "set_pf_worker",
      "external": false,
      "loc": "kernel/workqueue.c:2338",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:rescuer_thread",
        "kernel/workqueue.c:rescuer_thread",
        "kernel/workqueue.c:worker_thread",
        "kernel/workqueue.c:worker_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271474138,
      "name": "set_pf_worker",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
void set_pf_worker(bool val)
```

```json
{
  "name": "set_pf_worker",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579603376,
      "name": "set_pf_worker",
      "external": false,
      "loc": "kernel/workqueue.c:2338",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:rescuer_thread",
        "kernel/workqueue.c:rescuer_thread",
        "kernel/workqueue.c:worker_thread",
        "kernel/workqueue.c:worker_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579603376,
      "name": "set_pf_worker",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
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
void set_pf_worker(bool val)
```

```json
{
  "name": "set_pf_worker",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579532016,
      "name": "set_pf_worker",
      "external": false,
      "loc": "kernel/workqueue.c:2338",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:rescuer_thread",
        "kernel/workqueue.c:rescuer_thread",
        "kernel/workqueue.c:worker_thread",
        "kernel/workqueue.c:worker_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579532016,
      "name": "set_pf_worker",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
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
void set_pf_worker(bool val)
```

```json
{
  "name": "set_pf_worker",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579600656,
      "name": "set_pf_worker",
      "external": false,
      "loc": "kernel/workqueue.c:2338",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:rescuer_thread",
        "kernel/workqueue.c:rescuer_thread",
        "kernel/workqueue.c:worker_thread",
        "kernel/workqueue.c:worker_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579600656,
      "name": "set_pf_worker",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
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
void set_pf_worker(bool val)
```

```json
{
  "name": "set_pf_worker",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579634144,
      "name": "set_pf_worker",
      "external": false,
      "loc": "kernel/workqueue.c:2338",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:rescuer_thread",
        "kernel/workqueue.c:rescuer_thread",
        "kernel/workqueue.c:worker_thread",
        "kernel/workqueue.c:worker_thread"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579634144,
      "name": "set_pf_worker",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
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
void set_pf_worker(bool val)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void set_pf_worker(bool val)
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
