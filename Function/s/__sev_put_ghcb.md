# Function: <code>__sev_put_ghcb</code>

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
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void __sev_put_ghcb(struct ghcb_state * state)
```

```json
{
  "name": "__sev_put_ghcb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591601472,
      "name": "__sev_put_ghcb",
      "external": false,
      "loc": "arch/x86/kernel/sev.c:491",
      "file": "arch/x86/kernel/sev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sev.c:vc_raw_handle_exception",
        "arch/x86/kernel/sev.c:sev_es_play_dead",
        "arch/x86/kernel/sev.c:get_jump_table_addr",
        "arch/x86/kernel/sev.c:get_jump_table_addr",
        "arch/x86/kernel/sev.c:__sev_es_nmi_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591601472,
      "name": "__sev_put_ghcb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
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
void __sev_put_ghcb(struct ghcb_state * state)
```

```json
{
  "name": "__sev_put_ghcb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592774176,
      "name": "__sev_put_ghcb",
      "external": false,
      "loc": "arch/x86/kernel/sev.c:488",
      "file": "arch/x86/kernel/sev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sev.c:vc_raw_handle_exception",
        "arch/x86/kernel/sev.c:sev_es_play_dead",
        "arch/x86/kernel/sev.c:get_jump_table_addr",
        "arch/x86/kernel/sev.c:get_jump_table_addr",
        "arch/x86/kernel/sev.c:__sev_es_nmi_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592774176,
      "name": "__sev_put_ghcb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
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
void __sev_put_ghcb(struct ghcb_state * state)
```

```json
{
  "name": "__sev_put_ghcb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594671296,
      "name": "__sev_put_ghcb",
      "external": false,
      "loc": "arch/x86/kernel/sev.c:518",
      "file": "arch/x86/kernel/sev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sev.c:snp_issue_guest_request",
        "arch/x86/kernel/sev.c:vc_raw_handle_exception",
        "arch/x86/kernel/sev.c:sev_es_play_dead",
        "arch/x86/kernel/sev.c:wakeup_cpu_via_vmgexit",
        "arch/x86/kernel/sev.c:wakeup_cpu_via_vmgexit",
        "arch/x86/kernel/sev.c:vmgexit_psc",
        "arch/x86/kernel/sev.c:get_jump_table_addr",
        "arch/x86/kernel/sev.c:__sev_es_nmi_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594671296,
      "name": "__sev_put_ghcb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
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
void __sev_put_ghcb(struct ghcb_state * state)
```

```json
{
  "name": "__sev_put_ghcb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596405856,
      "name": "__sev_put_ghcb",
      "external": false,
      "loc": "arch/x86/kernel/sev.c:518",
      "file": "arch/x86/kernel/sev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sev.c:snp_issue_guest_request",
        "arch/x86/kernel/sev.c:vc_raw_handle_exception",
        "arch/x86/kernel/sev.c:sev_es_play_dead",
        "arch/x86/kernel/sev.c:wakeup_cpu_via_vmgexit",
        "arch/x86/kernel/sev.c:wakeup_cpu_via_vmgexit",
        "arch/x86/kernel/sev.c:vmgexit_psc",
        "arch/x86/kernel/sev.c:get_jump_table_addr",
        "arch/x86/kernel/sev.c:__sev_es_nmi_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596405856,
      "name": "__sev_put_ghcb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
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
void __sev_put_ghcb(struct ghcb_state * state)
```

```json
{
  "name": "__sev_put_ghcb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596937568,
      "name": "__sev_put_ghcb",
      "external": false,
      "loc": "arch/x86/kernel/sev.c:530",
      "file": "arch/x86/kernel/sev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sev.c:snp_issue_guest_request",
        "arch/x86/kernel/sev.c:vc_raw_handle_exception",
        "arch/x86/kernel/sev.c:sev_es_play_dead",
        "arch/x86/kernel/sev.c:wakeup_cpu_via_vmgexit",
        "arch/x86/kernel/sev.c:wakeup_cpu_via_vmgexit",
        "arch/x86/kernel/sev.c:__set_pages_state",
        "arch/x86/kernel/sev.c:get_jump_table_addr",
        "arch/x86/kernel/sev.c:__sev_es_nmi_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596937568,
      "name": "__sev_put_ghcb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
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
void __sev_put_ghcb(struct ghcb_state * state)
```

```json
{
  "name": "__sev_put_ghcb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597863024,
      "name": "__sev_put_ghcb",
      "external": false,
      "loc": "arch/x86/kernel/sev.c:557",
      "file": "arch/x86/kernel/sev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sev.c:snp_issue_guest_request",
        "arch/x86/kernel/sev.c:vc_raw_handle_exception",
        "arch/x86/kernel/sev.c:sev_es_play_dead",
        "arch/x86/kernel/sev.c:wakeup_cpu_via_vmgexit",
        "arch/x86/kernel/sev.c:wakeup_cpu_via_vmgexit",
        "arch/x86/kernel/sev.c:__set_pages_state",
        "arch/x86/kernel/sev.c:get_jump_table_addr",
        "arch/x86/kernel/sev.c:__sev_es_nmi_complete"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597863024,
      "name": "__sev_put_ghcb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
void __sev_put_ghcb(struct ghcb_state * state)
```
</details>
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
