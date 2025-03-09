# Function: <code>rebuild_root_domains</code>

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
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rebuild_root_domains",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580347785,
      "name": "rebuild_root_domains",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:923",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked"
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
void rebuild_root_domains()
```

```json
{
  "name": "rebuild_root_domains",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580409664,
      "name": "rebuild_root_domains",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:927",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580409664,
      "name": "rebuild_root_domains",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
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
void rebuild_root_domains()
```

```json
{
  "name": "rebuild_root_domains",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580396944,
      "name": "rebuild_root_domains",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:927",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580396944,
      "name": "rebuild_root_domains",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 266
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
  "name": "rebuild_root_domains",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580402436,
      "name": "rebuild_root_domains",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:927",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked"
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
  "name": "rebuild_root_domains",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580565140,
      "name": "rebuild_root_domains",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:955",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked"
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
  "name": "rebuild_root_domains",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580768125,
      "name": "rebuild_root_domains",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:995",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked"
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
  "name": "rebuild_root_domains",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581048301,
      "name": "rebuild_root_domains",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:1082",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked"
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
  "name": "rebuild_root_domains",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336491603804,
      "name": "rebuild_root_domains",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:923",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked"
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
  "name": "rebuild_root_domains",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3225561672,
      "name": "rebuild_root_domains",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:923",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "rebuild_root_domains",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055284595776,
      "name": "rebuild_root_domains",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:923",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked"
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
  "name": "rebuild_root_domains",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936272006080,
      "name": "rebuild_root_domains",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:923",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "rebuild_root_domains",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580316585,
      "name": "rebuild_root_domains",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:923",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked"
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
  "name": "rebuild_root_domains",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580263897,
      "name": "rebuild_root_domains",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:923",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked"
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
  "name": "rebuild_root_domains",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580307833,
      "name": "rebuild_root_domains",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:923",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked"
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
  "name": "rebuild_root_domains",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580362281,
      "name": "rebuild_root_domains",
      "external": false,
      "loc": "kernel/cgroup/cpuset.c:923",
      "file": "kernel/cgroup/cpuset.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cpuset.c:rebuild_sched_domains_locked"
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
void rebuild_root_domains()
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
void rebuild_root_domains()
```
</details>
</li>
</ul>
