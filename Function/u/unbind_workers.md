# Function: <code>unbind_workers</code>

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
  "name": "unbind_workers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579537169,
      "name": "unbind_workers",
      "external": false,
      "loc": "kernel/workqueue.c:4542",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:workqueue_offline_cpu"
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
  "name": "unbind_workers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579563571,
      "name": "unbind_workers",
      "external": false,
      "loc": "kernel/workqueue.c:4661",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:workqueue_offline_cpu"
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
  "name": "unbind_workers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579600803,
      "name": "unbind_workers",
      "external": false,
      "loc": "kernel/workqueue.c:4684",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:workqueue_offline_cpu"
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
  "name": "unbind_workers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579624113,
      "name": "unbind_workers",
      "external": false,
      "loc": "kernel/workqueue.c:4829",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:workqueue_offline_cpu"
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
  "name": "unbind_workers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579650129,
      "name": "unbind_workers",
      "external": false,
      "loc": "kernel/workqueue.c:4863",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:workqueue_offline_cpu"
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
void unbind_workers(int cpu)
```

```json
{
  "name": "unbind_workers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579664624,
      "name": "unbind_workers",
      "external": false,
      "loc": "kernel/workqueue.c:4886",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:workqueue_offline_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579664624,
      "name": "unbind_workers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 279
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
void unbind_workers(int cpu)
```

```json
{
  "name": "unbind_workers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579644432,
      "name": "unbind_workers",
      "external": false,
      "loc": "kernel/workqueue.c:4899",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:workqueue_offline_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579644432,
      "name": "unbind_workers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 349
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
  "name": "unbind_workers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579668007,
      "name": "unbind_workers",
      "external": false,
      "loc": "kernel/workqueue.c:4906",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:workqueue_offline_cpu"
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
  "name": "unbind_workers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579744855,
      "name": "unbind_workers",
      "external": false,
      "loc": "kernel/workqueue.c:4959",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:workqueue_offline_cpu"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void unbind_workers(int cpu)
```

```json
{
  "name": "unbind_workers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579829120,
      "name": "unbind_workers",
      "external": false,
      "loc": "kernel/workqueue.c:4961",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:workqueue_offline_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579829120,
      "name": "unbind_workers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 492
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
void unbind_workers(int cpu)
```

```json
{
  "name": "unbind_workers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579966528,
      "name": "unbind_workers",
      "external": false,
      "loc": "kernel/workqueue.c:4970",
      "file": "kernel/workqueue.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/workqueue.c:workqueue_offline_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579966528,
      "name": "unbind_workers",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 492
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
  "name": "unbind_workers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580043399,
      "name": "unbind_workers",
      "external": false,
      "loc": "kernel/workqueue.c:5368",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:workqueue_offline_cpu"
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
  "name": "unbind_workers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580086445,
      "name": "unbind_workers",
      "external": false,
      "loc": "kernel/workqueue.c:5391",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:workqueue_offline_cpu"
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
  "name": "unbind_workers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336490822724,
      "name": "unbind_workers",
      "external": false,
      "loc": "kernel/workqueue.c:4863",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:workqueue_offline_cpu"
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
  "name": "unbind_workers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3224856008,
      "name": "unbind_workers",
      "external": false,
      "loc": "kernel/workqueue.c:4863",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:workqueue_offline_cpu"
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
  "name": "unbind_workers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055283657088,
      "name": "unbind_workers",
      "external": false,
      "loc": "kernel/workqueue.c:4863",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:workqueue_offline_cpu"
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
  "name": "unbind_workers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271496582,
      "name": "unbind_workers",
      "external": false,
      "loc": "kernel/workqueue.c:4863",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:workqueue_offline_cpu"
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
  "name": "unbind_workers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579626433,
      "name": "unbind_workers",
      "external": false,
      "loc": "kernel/workqueue.c:4863",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:workqueue_offline_cpu"
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
  "name": "unbind_workers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579554801,
      "name": "unbind_workers",
      "external": false,
      "loc": "kernel/workqueue.c:4863",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:workqueue_offline_cpu"
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
  "name": "unbind_workers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579623713,
      "name": "unbind_workers",
      "external": false,
      "loc": "kernel/workqueue.c:4863",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:workqueue_offline_cpu"
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
  "name": "unbind_workers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579657361,
      "name": "unbind_workers",
      "external": false,
      "loc": "kernel/workqueue.c:4863",
      "file": "kernel/workqueue.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/workqueue.c:workqueue_offline_cpu"
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
void unbind_workers(int cpu)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
void unbind_workers(int cpu)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
void unbind_workers(int cpu)
```
</details>
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
void unbind_workers(int cpu)
```
</details>
</li>
</ul>
