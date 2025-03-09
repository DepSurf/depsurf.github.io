# Function: <code>hv_ghcb_msr_write</code>

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
void hv_ghcb_msr_write(u64 msr, u64 value)
```

```json
{
  "name": "hv_ghcb_msr_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "hv_ghcb_msr_write",
      "external": true,
      "loc": "arch/x86/hyperv/ivm.c:175",
      "file": "arch/x86/hyperv/ivm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_init.c:hyperv_cleanup",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593816878,
      "name": "hv_ghcb_msr_write.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071579102928,
      "name": "hv_ghcb_msr_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 300
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
void hv_ghcb_msr_write(u64 msr, u64 value)
```

```json
{
  "name": "hv_ghcb_msr_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579139952,
      "name": "hv_ghcb_msr_write",
      "external": true,
      "loc": "arch/x86/hyperv/ivm.c:175",
      "file": "arch/x86/hyperv/ivm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_init.c:hyperv_cleanup",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579139952,
      "name": "hv_ghcb_msr_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
void hv_ghcb_msr_write(u64 msr, u64 value)
```

```json
{
  "name": "hv_ghcb_msr_write",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579140896,
      "name": "hv_ghcb_msr_write",
      "external": true,
      "loc": "arch/x86/hyperv/ivm.c:178",
      "file": "arch/x86/hyperv/ivm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_init.c:hyperv_cleanup",
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/hyperv/hv_init.c:hyperv_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579140896,
      "name": "hv_ghcb_msr_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
void hv_ghcb_msr_write(u64 msr, u64 value)
```

```json
{
  "name": "hv_ghcb_msr_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579168000,
      "name": "hv_ghcb_msr_write",
      "external": false,
      "loc": "arch/x86/hyperv/ivm.c:186",
      "file": "arch/x86/hyperv/ivm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/ivm.c:hv_ivm_msr_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579168000,
      "name": "hv_ghcb_msr_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
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
void hv_ghcb_msr_write(u64 msr, u64 value)
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
