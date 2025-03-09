# Function: <code>sev_cpuid_hv</code>

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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int sev_cpuid_hv(struct cpuid_leaf * leaf)
```

```json
{
  "name": "sev_cpuid_hv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579519168,
      "name": "sev_cpuid_hv",
      "external": false,
      "loc": "arch/x86/kernel/sev-shared.c:256",
      "file": "arch/x86/kernel/sev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sev.c:do_vc_no_ghcb",
        "arch/x86/kernel/sev.c:snp_cpuid_postprocess",
        "arch/x86/kernel/sev.c:snp_cpuid_postprocess",
        "arch/x86/kernel/sev.c:snp_cpuid_postprocess"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579519168,
      "name": "sev_cpuid_hv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 169
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
int sev_cpuid_hv(struct cpuid_leaf * leaf)
```

```json
{
  "name": "sev_cpuid_hv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579618800,
      "name": "sev_cpuid_hv",
      "external": false,
      "loc": "arch/x86/kernel/sev-shared.c:256",
      "file": "arch/x86/kernel/sev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sev.c:do_vc_no_ghcb",
        "arch/x86/kernel/sev.c:snp_cpuid_postprocess",
        "arch/x86/kernel/sev.c:snp_cpuid_postprocess",
        "arch/x86/kernel/sev.c:snp_cpuid_postprocess"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579618800,
      "name": "sev_cpuid_hv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
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
int sev_cpuid_hv(struct cpuid_leaf * leaf)
```

```json
{
  "name": "sev_cpuid_hv",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579632656,
      "name": "sev_cpuid_hv",
      "external": false,
      "loc": "arch/x86/kernel/sev-shared.c:259",
      "file": "arch/x86/kernel/sev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sev.c:do_vc_no_ghcb",
        "arch/x86/kernel/sev.c:snp_cpuid_postprocess",
        "arch/x86/kernel/sev.c:snp_cpuid_postprocess",
        "arch/x86/kernel/sev.c:snp_cpuid_postprocess"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579632656,
      "name": "sev_cpuid_hv",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sev_cpuid_hv",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579662581,
      "name": "sev_cpuid_hv",
      "external": false,
      "loc": "arch/x86/kernel/sev-shared.c:315",
      "file": "arch/x86/kernel/sev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/sev.c:snp_cpuid_postprocess",
        "arch/x86/kernel/sev.c:snp_cpuid_postprocess",
        "arch/x86/kernel/sev.c:snp_cpuid_postprocess"
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
int sev_cpuid_hv(struct cpuid_leaf * leaf)
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
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
int sev_cpuid_hv(struct cpuid_leaf * leaf)
```
</details>
</li>
</ul>
