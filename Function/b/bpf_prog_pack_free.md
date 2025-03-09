# Function: <code>bpf_prog_pack_free</code>

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
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void bpf_prog_pack_free(struct bpf_binary_header * hdr)
```

```json
{
  "name": "bpf_prog_pack_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_prog_pack_free",
      "external": false,
      "loc": "kernel/bpf/core.c:939",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_jit_binary_pack_free",
        "kernel/bpf/core.c:bpf_jit_binary_pack_finalize",
        "kernel/bpf/core.c:bpf_jit_binary_pack_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581395184,
      "name": "bpf_prog_pack_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 440
    },
    {
      "addr": 18446744071593953997,
      "name": "bpf_prog_pack_free.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
void bpf_prog_pack_free(struct bpf_binary_header * hdr)
```

```json
{
  "name": "bpf_prog_pack_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_prog_pack_free",
      "external": true,
      "loc": "kernel/bpf/core.c:916",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_jit_binary_pack_free",
        "kernel/bpf/core.c:bpf_jit_binary_pack_finalize",
        "kernel/bpf/core.c:bpf_jit_binary_pack_alloc",
        "kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596013497,
      "name": "bpf_prog_pack_free.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071581745280,
      "name": "bpf_prog_pack_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 508
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
void bpf_prog_pack_free(struct bpf_binary_header * hdr)
```

```json
{
  "name": "bpf_prog_pack_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_prog_pack_free",
      "external": true,
      "loc": "kernel/bpf/core.c:917",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_jit_binary_pack_free",
        "kernel/bpf/core.c:bpf_jit_binary_pack_finalize",
        "kernel/bpf/core.c:bpf_jit_binary_pack_alloc",
        "kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596533493,
      "name": "bpf_prog_pack_free.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071581904944,
      "name": "bpf_prog_pack_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 508
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void bpf_prog_pack_free(void * ptr, u32 size)
```

```json
{
  "name": "bpf_prog_pack_free",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_prog_pack_free",
      "external": true,
      "loc": "kernel/bpf/core.c:960",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/net/bpf_jit_comp.c:arch_free_bpf_trampoline",
        "kernel/bpf/core.c:bpf_jit_binary_pack_free",
        "kernel/bpf/core.c:bpf_jit_binary_pack_finalize",
        "kernel/bpf/core.c:bpf_jit_binary_pack_alloc",
        "kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597434282,
      "name": "bpf_prog_pack_free.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
    },
    {
      "addr": 18446744071582029136,
      "name": "bpf_prog_pack_free",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 513
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
void bpf_prog_pack_free(struct bpf_binary_header * hdr)
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
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>void * ptr</code>
</li>
<li>
<b>Param added. </b>
<code>u32 size</code>
</li>
<li>
<b>Param removed. </b>
<code>struct bpf_binary_header * hdr</code>
</li>
</ul>
</details>
</li>
</ul>
