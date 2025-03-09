# Function: <code>sev_es_ghcb_hv_call</code>

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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
enum es_result sev_es_ghcb_hv_call(struct ghcb * ghcb, struct es_em_ctxt * ctxt, u64 exit_code, u64 exit_info_1, u64 exit_info_2)
```

```json
{
  "name": "sev_es_ghcb_hv_call",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579378784,
      "name": "sev_es_ghcb_hv_call",
      "external": false,
      "loc": "arch/x86/kernel/sev-es-shared.c:96",
      "file": "arch/x86/kernel/sev-es.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sev-es.c:vc_handle_exitcode",
        "arch/x86/kernel/sev-es.c:vc_handle_exitcode",
        "arch/x86/kernel/sev-es.c:vc_handle_exitcode",
        "arch/x86/kernel/sev-es.c:vc_handle_exitcode",
        "arch/x86/kernel/sev-es.c:vc_handle_exitcode",
        "arch/x86/kernel/sev-es.c:vc_handle_vmmcall",
        "arch/x86/kernel/sev-es.c:vc_handle_dr7_write",
        "arch/x86/kernel/sev-es.c:vc_do_mmio",
        "arch/x86/kernel/sev-es.c:vc_handle_cpuid",
        "arch/x86/kernel/sev-es.c:vc_handle_ioio",
        "arch/x86/kernel/sev-es.c:vc_handle_ioio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579378784,
      "name": "sev_es_ghcb_hv_call",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
enum es_result sev_es_ghcb_hv_call(struct ghcb * ghcb, struct es_em_ctxt * ctxt, u64 exit_code, u64 exit_info_1, u64 exit_info_2)
```

```json
{
  "name": "sev_es_ghcb_hv_call",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579382400,
      "name": "sev_es_ghcb_hv_call",
      "external": false,
      "loc": "arch/x86/kernel/sev-shared.c:97",
      "file": "arch/x86/kernel/sev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sev.c:vc_handle_exitcode",
        "arch/x86/kernel/sev.c:vc_handle_exitcode",
        "arch/x86/kernel/sev.c:vc_handle_exitcode",
        "arch/x86/kernel/sev.c:vc_handle_exitcode",
        "arch/x86/kernel/sev.c:vc_handle_exitcode",
        "arch/x86/kernel/sev.c:vc_handle_exitcode",
        "arch/x86/kernel/sev.c:vc_handle_exitcode",
        "arch/x86/kernel/sev.c:vc_handle_exitcode",
        "arch/x86/kernel/sev.c:vc_do_mmio",
        "arch/x86/kernel/sev.c:vc_handle_ioio",
        "arch/x86/kernel/sev.c:vc_handle_ioio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579382400,
      "name": "sev_es_ghcb_hv_call",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 232
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
enum es_result sev_es_ghcb_hv_call(struct ghcb * ghcb, struct es_em_ctxt * ctxt, u64 exit_code, u64 exit_info_1, u64 exit_info_2)
```

```json
{
  "name": "sev_es_ghcb_hv_call",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579444096,
      "name": "sev_es_ghcb_hv_call",
      "external": false,
      "loc": "arch/x86/kernel/sev-shared.c:97",
      "file": "arch/x86/kernel/sev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sev.c:vc_handle_exitcode",
        "arch/x86/kernel/sev.c:vc_handle_exitcode",
        "arch/x86/kernel/sev.c:vc_handle_exitcode",
        "arch/x86/kernel/sev.c:vc_handle_exitcode",
        "arch/x86/kernel/sev.c:vc_handle_exitcode",
        "arch/x86/kernel/sev.c:vc_handle_exitcode",
        "arch/x86/kernel/sev.c:vc_handle_exitcode",
        "arch/x86/kernel/sev.c:vc_handle_exitcode",
        "arch/x86/kernel/sev.c:vc_do_mmio",
        "arch/x86/kernel/sev.c:vc_handle_ioio",
        "arch/x86/kernel/sev.c:vc_handle_ioio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579444096,
      "name": "sev_es_ghcb_hv_call",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 247
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
enum es_result sev_es_ghcb_hv_call(struct ghcb * ghcb, struct es_em_ctxt * ctxt, u64 exit_code, u64 exit_info_1, u64 exit_info_2)
```

```json
{
  "name": "sev_es_ghcb_hv_call",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579514480,
      "name": "sev_es_ghcb_hv_call",
      "external": false,
      "loc": "arch/x86/kernel/sev-shared.c:222",
      "file": "arch/x86/kernel/sev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sev.c:snp_issue_guest_request",
        "arch/x86/kernel/sev.c:vc_handle_exitcode",
        "arch/x86/kernel/sev.c:vc_handle_exitcode",
        "arch/x86/kernel/sev.c:vc_handle_exitcode",
        "arch/x86/kernel/sev.c:vc_handle_exitcode",
        "arch/x86/kernel/sev.c:vc_handle_exitcode",
        "arch/x86/kernel/sev.c:vc_handle_exitcode",
        "arch/x86/kernel/sev.c:vc_handle_exitcode",
        "arch/x86/kernel/sev.c:vc_handle_exitcode",
        "arch/x86/kernel/sev.c:vc_do_mmio",
        "arch/x86/kernel/sev.c:vmgexit_psc",
        "arch/x86/kernel/sev.c:vc_handle_ioio",
        "arch/x86/kernel/sev.c:vc_handle_ioio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579514480,
      "name": "sev_es_ghcb_hv_call",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 263
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
enum es_result sev_es_ghcb_hv_call(struct ghcb * ghcb, struct es_em_ctxt * ctxt, u64 exit_code, u64 exit_info_1, u64 exit_info_2)
```

```json
{
  "name": "sev_es_ghcb_hv_call",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579613856,
      "name": "sev_es_ghcb_hv_call",
      "external": false,
      "loc": "arch/x86/kernel/sev-shared.c:222",
      "file": "arch/x86/kernel/sev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sev.c:snp_issue_guest_request",
        "arch/x86/kernel/sev.c:vc_handle_exitcode",
        "arch/x86/kernel/sev.c:vc_handle_exitcode",
        "arch/x86/kernel/sev.c:vc_handle_exitcode",
        "arch/x86/kernel/sev.c:vc_handle_exitcode",
        "arch/x86/kernel/sev.c:vc_handle_exitcode",
        "arch/x86/kernel/sev.c:vc_handle_exitcode",
        "arch/x86/kernel/sev.c:vc_handle_exitcode",
        "arch/x86/kernel/sev.c:vc_do_mmio",
        "arch/x86/kernel/sev.c:vmgexit_psc",
        "arch/x86/kernel/sev.c:vc_handle_cpuid",
        "arch/x86/kernel/sev.c:vc_handle_ioio",
        "arch/x86/kernel/sev.c:vc_handle_ioio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579613856,
      "name": "sev_es_ghcb_hv_call",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 263
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
enum es_result sev_es_ghcb_hv_call(struct ghcb * ghcb, struct es_em_ctxt * ctxt, u64 exit_code, u64 exit_info_1, u64 exit_info_2)
```

```json
{
  "name": "sev_es_ghcb_hv_call",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579626464,
      "name": "sev_es_ghcb_hv_call",
      "external": false,
      "loc": "arch/x86/kernel/sev-shared.c:225",
      "file": "arch/x86/kernel/sev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sev.c:snp_issue_guest_request",
        "arch/x86/kernel/sev.c:vc_handle_exitcode",
        "arch/x86/kernel/sev.c:vc_handle_exitcode",
        "arch/x86/kernel/sev.c:vc_handle_exitcode",
        "arch/x86/kernel/sev.c:vc_handle_exitcode",
        "arch/x86/kernel/sev.c:vc_handle_exitcode",
        "arch/x86/kernel/sev.c:vc_handle_exitcode",
        "arch/x86/kernel/sev.c:vc_handle_exitcode",
        "arch/x86/kernel/sev.c:vc_do_mmio",
        "arch/x86/kernel/sev.c:vmgexit_psc",
        "arch/x86/kernel/sev.c:vc_handle_cpuid",
        "arch/x86/kernel/sev.c:vc_handle_ioio",
        "arch/x86/kernel/sev.c:vc_handle_ioio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579626464,
      "name": "sev_es_ghcb_hv_call",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 263
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
enum es_result sev_es_ghcb_hv_call(struct ghcb * ghcb, struct es_em_ctxt * ctxt, u64 exit_code, u64 exit_info_1, u64 exit_info_2)
```

```json
{
  "name": "sev_es_ghcb_hv_call",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579655520,
      "name": "sev_es_ghcb_hv_call",
      "external": false,
      "loc": "arch/x86/kernel/sev-shared.c:225",
      "file": "arch/x86/kernel/sev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sev.c:snp_issue_guest_request",
        "arch/x86/kernel/sev.c:vc_handle_exitcode",
        "arch/x86/kernel/sev.c:vc_handle_exitcode",
        "arch/x86/kernel/sev.c:vc_handle_exitcode",
        "arch/x86/kernel/sev.c:vc_handle_exitcode",
        "arch/x86/kernel/sev.c:vc_handle_exitcode",
        "arch/x86/kernel/sev.c:vc_handle_exitcode",
        "arch/x86/kernel/sev.c:vc_handle_exitcode",
        "arch/x86/kernel/sev.c:vc_do_mmio",
        "arch/x86/kernel/sev.c:vmgexit_psc",
        "arch/x86/kernel/sev.c:vc_handle_cpuid",
        "arch/x86/kernel/sev.c:vc_handle_ioio",
        "arch/x86/kernel/sev.c:vc_handle_ioio",
        "arch/x86/kernel/sev.c:__sev_cpuid_hv_ghcb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579655520,
      "name": "sev_es_ghcb_hv_call",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 263
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
enum es_result sev_es_ghcb_hv_call(struct ghcb * ghcb, struct es_em_ctxt * ctxt, u64 exit_code, u64 exit_info_1, u64 exit_info_2)
```
</details>
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
