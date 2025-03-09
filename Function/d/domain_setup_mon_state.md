# Function: <code>domain_setup_mon_state</code>

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
  "name": "domain_setup_mon_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579113123,
      "name": "domain_setup_mon_state",
      "external": false,
      "loc": "arch/x86/kernel/cpu/intel_rdt.c:413",
      "file": "arch/x86/kernel/cpu/intel_rdt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_online_cpu"
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
  "name": "domain_setup_mon_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579126538,
      "name": "domain_setup_mon_state",
      "external": false,
      "loc": "arch/x86/kernel/cpu/intel_rdt.c:414",
      "file": "arch/x86/kernel/cpu/intel_rdt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_online_cpu"
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
  "name": "domain_setup_mon_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579135514,
      "name": "domain_setup_mon_state",
      "external": false,
      "loc": "arch/x86/kernel/cpu/intel_rdt.c:483",
      "file": "arch/x86/kernel/cpu/intel_rdt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_online_cpu"
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
  "name": "domain_setup_mon_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579196979,
      "name": "domain_setup_mon_state",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:516",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu"
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
  "name": "domain_setup_mon_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579209826,
      "name": "domain_setup_mon_state",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:508",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu"
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
  "name": "domain_setup_mon_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579212082,
      "name": "domain_setup_mon_state",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:508",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu"
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
int domain_setup_mon_state(struct rdt_resource * r, struct rdt_domain * d)
```

```json
{
  "name": "domain_setup_mon_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579232672,
      "name": "domain_setup_mon_state",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:508",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579232672,
      "name": "domain_setup_mon_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 493
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
int domain_setup_mon_state(struct rdt_resource * r, struct rdt_domain * d)
```

```json
{
  "name": "domain_setup_mon_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579225792,
      "name": "domain_setup_mon_state",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:510",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579225792,
      "name": "domain_setup_mon_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 493
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
  "name": "domain_setup_mon_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579228564,
      "name": "domain_setup_mon_state",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:510",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu"
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
  "name": "domain_setup_mon_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579267222,
      "name": "domain_setup_mon_state",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:450",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu"
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
  "name": "domain_setup_mon_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579319741,
      "name": "domain_setup_mon_state",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:450",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu"
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
  "name": "domain_setup_mon_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579410421,
      "name": "domain_setup_mon_state",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:3331",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_online_domain"
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
  "name": "domain_setup_mon_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579422849,
      "name": "domain_setup_mon_state",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:3746",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_online_domain"
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
  "name": "domain_setup_mon_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579452433,
      "name": "domain_setup_mon_state",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/rdtgroup.c:3884",
      "file": "arch/x86/kernel/cpu/resctrl/rdtgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_online_domain"
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "domain_setup_mon_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579210930,
      "name": "domain_setup_mon_state",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:508",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu"
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
  "name": "domain_setup_mon_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579145938,
      "name": "domain_setup_mon_state",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:508",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu"
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
  "name": "domain_setup_mon_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579212002,
      "name": "domain_setup_mon_state",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:508",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu"
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
  "name": "domain_setup_mon_state",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579217282,
      "name": "domain_setup_mon_state",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/core.c:508",
      "file": "arch/x86/kernel/cpu/resctrl/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu"
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
int domain_setup_mon_state(struct rdt_resource * r, struct rdt_domain * d)
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
int domain_setup_mon_state(struct rdt_resource * r, struct rdt_domain * d)
```
</details>
</li>
</ul>
