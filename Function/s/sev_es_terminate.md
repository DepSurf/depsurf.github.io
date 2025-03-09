# Function: <code>sev_es_terminate</code>

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
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sev_es_terminate",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591265407,
      "name": "sev_es_terminate",
      "external": false,
      "loc": "arch/x86/kernel/sev-es-shared.c:27",
      "file": "arch/x86/kernel/sev-es.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sev-es.c:handle_vc_boot_ghcb",
        "arch/x86/kernel/sev-es.c:safe_stack_exc_vmm_communication"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591265407,
      "name": "sev_es_terminate.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
  "name": "sev_es_terminate",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579384784,
      "name": "sev_es_terminate",
      "external": false,
      "loc": "arch/x86/kernel/sev-shared.c:27",
      "file": "arch/x86/kernel/sev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sev.c:handle_vc_boot_ghcb",
        "arch/x86/kernel/sev.c:do_vc_no_ghcb",
        "arch/x86/kernel/sev.c:kernel_exc_vmm_communication"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579384784,
      "name": "sev_es_terminate.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sev_es_terminate",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579445648,
      "name": "sev_es_terminate",
      "external": false,
      "loc": "arch/x86/kernel/sev-shared.c:27",
      "file": "arch/x86/kernel/sev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sev.c:handle_vc_boot_ghcb",
        "arch/x86/kernel/sev.c:do_vc_no_ghcb",
        "arch/x86/kernel/sev.c:kernel_exc_vmm_communication"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579445648,
      "name": "sev_es_terminate.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
void sev_es_terminate(unsigned int set, unsigned int reason)
```

```json
{
  "name": "sev_es_terminate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579514432,
      "name": "sev_es_terminate",
      "external": false,
      "loc": "arch/x86/kernel/sev-shared.c:89",
      "file": "arch/x86/kernel/sev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sev.c:snp_abort",
        "arch/x86/kernel/sev.c:handle_vc_boot_ghcb",
        "arch/x86/kernel/sev.c:setup_ghcb",
        "arch/x86/kernel/sev.c:early_set_pages_state",
        "arch/x86/kernel/sev.c:setup_cpuid_table",
        "arch/x86/kernel/sev.c:do_vc_no_ghcb",
        "arch/x86/kernel/sev.c:snp_register_ghcb_early",
        "arch/x86/kernel/sev.c:kernel_exc_vmm_communication",
        "arch/x86/kernel/sev.c:sev_es_init_vc_handling"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579514432,
      "name": "sev_es_terminate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
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
void sev_es_terminate(unsigned int set, unsigned int reason)
```

```json
{
  "name": "sev_es_terminate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579613792,
      "name": "sev_es_terminate",
      "external": false,
      "loc": "arch/x86/kernel/sev-shared.c:89",
      "file": "arch/x86/kernel/sev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sev.c:handle_vc_boot_ghcb",
        "arch/x86/kernel/sev.c:setup_ghcb",
        "arch/x86/kernel/sev.c:early_set_pages_state",
        "arch/x86/kernel/sev.c:setup_cpuid_table",
        "arch/x86/kernel/sev.c:do_vc_no_ghcb",
        "arch/x86/kernel/sev.c:snp_register_ghcb_early",
        "arch/x86/kernel/sev.c:kernel_exc_vmm_communication",
        "arch/x86/kernel/sev.c:snp_abort",
        "arch/x86/kernel/sev.c:sev_es_init_vc_handling"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579613792,
      "name": "sev_es_terminate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
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
void sev_es_terminate(unsigned int set, unsigned int reason)
```

```json
{
  "name": "sev_es_terminate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579626400,
      "name": "sev_es_terminate",
      "external": false,
      "loc": "arch/x86/kernel/sev-shared.c:92",
      "file": "arch/x86/kernel/sev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sev.c:handle_vc_boot_ghcb",
        "arch/x86/kernel/sev.c:setup_ghcb",
        "arch/x86/kernel/sev.c:__set_pages_state",
        "arch/x86/kernel/sev.c:early_set_pages_state",
        "arch/x86/kernel/sev.c:early_set_pages_state",
        "arch/x86/kernel/sev.c:early_set_pages_state",
        "arch/x86/kernel/sev.c:pvalidate_pages",
        "arch/x86/kernel/sev.c:setup_cpuid_table",
        "arch/x86/kernel/sev.c:do_vc_no_ghcb",
        "arch/x86/kernel/sev.c:snp_register_ghcb_early",
        "arch/x86/kernel/sev.c:kernel_exc_vmm_communication",
        "arch/x86/kernel/sev.c:snp_abort",
        "arch/x86/kernel/sev.c:sev_es_init_vc_handling"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579626400,
      "name": "sev_es_terminate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
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
void sev_es_terminate(unsigned int set, unsigned int reason)
```

```json
{
  "name": "sev_es_terminate",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579655456,
      "name": "sev_es_terminate",
      "external": false,
      "loc": "arch/x86/kernel/sev-shared.c:92",
      "file": "arch/x86/kernel/sev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sev.c:handle_vc_boot_ghcb",
        "arch/x86/kernel/sev.c:setup_ghcb",
        "arch/x86/kernel/sev.c:__set_pages_state",
        "arch/x86/kernel/sev.c:early_set_pages_state",
        "arch/x86/kernel/sev.c:early_set_pages_state",
        "arch/x86/kernel/sev.c:early_set_pages_state",
        "arch/x86/kernel/sev.c:pvalidate_pages",
        "arch/x86/kernel/sev.c:setup_cpuid_table",
        "arch/x86/kernel/sev.c:do_vc_no_ghcb",
        "arch/x86/kernel/sev.c:snp_register_ghcb_early",
        "arch/x86/kernel/sev.c:kernel_exc_vmm_communication",
        "arch/x86/kernel/sev.c:snp_abort",
        "arch/x86/kernel/sev.c:sev_es_init_vc_handling"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579655456,
      "name": "sev_es_terminate",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
void sev_es_terminate(unsigned int set, unsigned int reason)
```
</details>
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
