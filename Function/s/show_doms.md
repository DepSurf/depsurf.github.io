# Function: <code>show_doms</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "show_doms",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579127404,
      "name": "show_doms",
      "external": false,
      "loc": "arch/x86/kernel/cpu/intel_rdt_schemata.c:211",
      "file": "arch/x86/kernel/cpu/intel_rdt_schemata.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt_schemata.c:rdtgroup_schemata_show"
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
  "name": "show_doms",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579127501,
      "name": "show_doms",
      "external": false,
      "loc": "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:251",
      "file": "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_show"
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
  "name": "show_doms",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579142141,
      "name": "show_doms",
      "external": false,
      "loc": "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:281",
      "file": "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_show"
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
  "name": "show_doms",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579152679,
      "name": "show_doms",
      "external": false,
      "loc": "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:291",
      "file": "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_schemata_show"
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
  "name": "show_doms",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579220143,
      "name": "show_doms",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:448",
      "file": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show"
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
  "name": "show_doms",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579233310,
      "name": "show_doms",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:440",
      "file": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show"
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
  "name": "show_doms",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579235486,
      "name": "show_doms",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:440",
      "file": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show"
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
void show_doms(struct seq_file * s, struct rdt_resource * r, int closid)
```

```json
{
  "name": "show_doms",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579255728,
      "name": "show_doms",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:440",
      "file": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579255728,
      "name": "show_doms",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 187
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
void show_doms(struct seq_file * s, struct rdt_resource * r, int closid)
```

```json
{
  "name": "show_doms",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579248800,
      "name": "show_doms",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:374",
      "file": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579248800,
      "name": "show_doms",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 187
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
  "name": "show_doms",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579252915,
      "name": "show_doms",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:374",
      "file": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show"
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
  "name": "show_doms",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579293877,
      "name": "show_doms",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:441",
      "file": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show"
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
  "name": "show_doms",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579348556,
      "name": "show_doms",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:441",
      "file": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show"
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
  "name": "show_doms",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579418916,
      "name": "show_doms",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:467",
      "file": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show"
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
  "name": "show_doms",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579430796,
      "name": "show_doms",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:459",
      "file": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show"
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
  "name": "show_doms",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579460380,
      "name": "show_doms",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:461",
      "file": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show"
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
  "name": "show_doms",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579234334,
      "name": "show_doms",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:440",
      "file": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show"
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
  "name": "show_doms",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579169614,
      "name": "show_doms",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:440",
      "file": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show"
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
  "name": "show_doms",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579235406,
      "name": "show_doms",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:440",
      "file": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show"
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
  "name": "show_doms",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579240878,
      "name": "show_doms",
      "external": false,
      "loc": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:440",
      "file": "arch/x86/kernel/cpu/resctrl/ctrlmondata.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_schemata_show"
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
void show_doms(struct seq_file * s, struct rdt_resource * r, int closid)
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
void show_doms(struct seq_file * s, struct rdt_resource * r, int closid)
```
</details>
</li>
</ul>
