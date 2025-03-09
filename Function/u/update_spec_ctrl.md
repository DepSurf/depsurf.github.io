# Function: <code>update_spec_ctrl</code>

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
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void update_spec_ctrl(u64 val)
```

```json
{
  "name": "update_spec_ctrl",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579300372,
      "name": "update_spec_ctrl",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:64",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/bugs.c:x86_spec_ctrl_setup_ap",
        "arch/x86/kernel/cpu/bugs.c:update_stibp_msr"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:spectre_v2_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:spectre_v2_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:spectre_v2_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:spectre_v2_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:spectre_v2_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:spectre_v2_select_mitigation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579297248,
      "name": "update_spec_ctrl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
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
void update_spec_ctrl(u64 val)
```

```json
{
  "name": "update_spec_ctrl",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579306676,
      "name": "update_spec_ctrl",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:69",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/bugs.c:x86_spec_ctrl_setup_ap",
        "arch/x86/kernel/cpu/bugs.c:update_stibp_msr"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:spectre_v2_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:spectre_v2_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:spectre_v2_select_mitigation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579303376,
      "name": "update_spec_ctrl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
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
void update_spec_ctrl(u64 val)
```

```json
{
  "name": "update_spec_ctrl",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579337684,
      "name": "update_spec_ctrl",
      "external": false,
      "loc": "arch/x86/kernel/cpu/bugs.c:69",
      "file": "arch/x86/kernel/cpu/bugs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/bugs.c:x86_spec_ctrl_setup_ap",
        "arch/x86/kernel/cpu/bugs.c:update_stibp_msr",
        "arch/x86/kernel/cpu/bugs.c:bhi_select_mitigation"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:spectre_v2_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:spectre_v2_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:spectre_v2_select_mitigation"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579334320,
      "name": "update_spec_ctrl",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
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
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
void update_spec_ctrl(u64 val)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
