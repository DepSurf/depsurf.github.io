# Function: <code>cgroup_css_set_put_fork</code>

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
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void cgroup_css_set_put_fork(struct kernel_clone_args * kargs)
```

```json
{
  "name": "cgroup_css_set_put_fork",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580364320,
      "name": "cgroup_css_set_put_fork",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:6019",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_post_fork",
        "kernel/cgroup/cgroup.c:cgroup_cancel_fork",
        "kernel/cgroup/cgroup.c:cgroup_can_fork"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580364320,
      "name": "cgroup_css_set_put_fork",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 242
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void cgroup_css_set_put_fork(struct kernel_clone_args * kargs)
```

```json
{
  "name": "cgroup_css_set_put_fork",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580351200,
      "name": "cgroup_css_set_put_fork",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:6011",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_post_fork",
        "kernel/cgroup/cgroup.c:cgroup_cancel_fork",
        "kernel/cgroup/cgroup.c:cgroup_can_fork"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580351200,
      "name": "cgroup_css_set_put_fork",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 254
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
void cgroup_css_set_put_fork(struct kernel_clone_args * kargs)
```

```json
{
  "name": "cgroup_css_set_put_fork",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580354320,
      "name": "cgroup_css_set_put_fork",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:5986",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_post_fork",
        "kernel/cgroup/cgroup.c:cgroup_cancel_fork",
        "kernel/cgroup/cgroup.c:cgroup_can_fork"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580354320,
      "name": "cgroup_css_set_put_fork",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 254
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
void cgroup_css_set_put_fork(struct kernel_clone_args * kargs)
```

```json
{
  "name": "cgroup_css_set_put_fork",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580511296,
      "name": "cgroup_css_set_put_fork",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:6202",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_post_fork",
        "kernel/cgroup/cgroup.c:cgroup_cancel_fork",
        "kernel/cgroup/cgroup.c:cgroup_can_fork"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580511296,
      "name": "cgroup_css_set_put_fork",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 254
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void cgroup_css_set_put_fork(struct kernel_clone_args * kargs)
```

```json
{
  "name": "cgroup_css_set_put_fork",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580707760,
      "name": "cgroup_css_set_put_fork",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:6230",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_post_fork",
        "kernel/cgroup/cgroup.c:cgroup_cancel_fork",
        "kernel/cgroup/cgroup.c:cgroup_can_fork"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580707760,
      "name": "cgroup_css_set_put_fork",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 309
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void cgroup_css_set_put_fork(struct kernel_clone_args * kargs)
```

```json
{
  "name": "cgroup_css_set_put_fork",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580980912,
      "name": "cgroup_css_set_put_fork",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:6476",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_post_fork",
        "kernel/cgroup/cgroup.c:cgroup_cancel_fork",
        "kernel/cgroup/cgroup.c:cgroup_can_fork"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580980912,
      "name": "cgroup_css_set_put_fork",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 309
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
void cgroup_css_set_put_fork(struct kernel_clone_args * kargs)
```

```json
{
  "name": "cgroup_css_set_put_fork",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581068800,
      "name": "cgroup_css_set_put_fork",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:6457",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_post_fork",
        "kernel/cgroup/cgroup.c:cgroup_cancel_fork",
        "kernel/cgroup/cgroup.c:cgroup_can_fork"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581068800,
      "name": "cgroup_css_set_put_fork",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 311
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
void cgroup_css_set_put_fork(struct kernel_clone_args * kargs)
```

```json
{
  "name": "cgroup_css_set_put_fork",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581166224,
      "name": "cgroup_css_set_put_fork",
      "external": false,
      "loc": "kernel/cgroup/cgroup.c:6492",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cgroup/cgroup.c:cgroup_post_fork",
        "kernel/cgroup/cgroup.c:cgroup_cancel_fork",
        "kernel/cgroup/cgroup.c:cgroup_can_fork"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581166224,
      "name": "cgroup_css_set_put_fork",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 311
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
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
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void cgroup_css_set_put_fork(struct kernel_clone_args * kargs)
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
