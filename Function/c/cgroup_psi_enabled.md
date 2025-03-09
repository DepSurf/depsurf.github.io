# Function: <code>cgroup_psi_enabled</code>

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
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool cgroup_psi_enabled()
```

```json
{
  "name": "cgroup_psi_enabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580490369,
      "name": "cgroup_psi_enabled",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:3700",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:show_delegatable_files",
        "kernel/cgroup/cgroup.c:cgroup_init_cftypes",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files"
      ],
      "caller_func": [
        "kernel/sched/psi.c:psi_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580515232,
      "name": "cgroup_psi_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 23
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
bool cgroup_psi_enabled()
```

```json
{
  "name": "cgroup_psi_enabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580685329,
      "name": "cgroup_psi_enabled",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:3711",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:show_delegatable_files",
        "kernel/cgroup/cgroup.c:cgroup_init_cftypes",
        "kernel/cgroup/cgroup.c:cgroup_addrm_files"
      ],
      "caller_func": [
        "kernel/sched/build_utility.c:psi_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580711952,
      "name": "cgroup_psi_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
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
bool cgroup_psi_enabled()
```

```json
{
  "name": "cgroup_psi_enabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580970146,
      "name": "cgroup_psi_enabled",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:3877",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:delegate_show",
        "kernel/cgroup/cgroup.c:delegate_show",
        "kernel/cgroup/cgroup.c:css_populate_dir",
        "kernel/cgroup/cgroup.c:css_populate_dir",
        "kernel/cgroup/cgroup.c:css_clear_dir",
        "kernel/cgroup/cgroup.c:css_clear_dir"
      ],
      "caller_func": [
        "kernel/sched/build_utility.c:psi_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580986208,
      "name": "cgroup_psi_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool cgroup_psi_enabled()
```

```json
{
  "name": "cgroup_psi_enabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581059170,
      "name": "cgroup_psi_enabled",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:3854",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:delegate_show",
        "kernel/cgroup/cgroup.c:delegate_show",
        "kernel/cgroup/cgroup.c:css_populate_dir",
        "kernel/cgroup/cgroup.c:css_populate_dir",
        "kernel/cgroup/cgroup.c:css_clear_dir",
        "kernel/cgroup/cgroup.c:css_clear_dir"
      ],
      "caller_func": [
        "kernel/sched/build_utility.c:psi_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581073728,
      "name": "cgroup_psi_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool cgroup_psi_enabled()
```

```json
{
  "name": "cgroup_psi_enabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581156338,
      "name": "cgroup_psi_enabled",
      "external": true,
      "loc": "kernel/cgroup/cgroup.c:3908",
      "file": "kernel/cgroup/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cgroup/cgroup.c:delegate_show",
        "kernel/cgroup/cgroup.c:delegate_show",
        "kernel/cgroup/cgroup.c:css_populate_dir",
        "kernel/cgroup/cgroup.c:css_populate_dir",
        "kernel/cgroup/cgroup.c:css_clear_dir",
        "kernel/cgroup/cgroup.c:css_clear_dir"
      ],
      "caller_func": [
        "kernel/sched/build_utility.c:psi_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581171344,
      "name": "cgroup_psi_enabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
bool cgroup_psi_enabled()
```
</details>
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
