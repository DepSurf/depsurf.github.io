# Function: <code>sgx_zap_enclave_ptes</code>

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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void sgx_zap_enclave_ptes(struct sgx_encl * encl, long unsigned int addr)
```

```json
{
  "name": "sgx_zap_enclave_ptes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579435616,
      "name": "sgx_zap_enclave_ptes",
      "external": true,
      "loc": "arch/x86/kernel/cpu/sgx/encl.c:1177",
      "file": "arch/x86/kernel/cpu/sgx/encl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_remove_pages",
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_enclave_modify_types",
        "arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579435616,
      "name": "sgx_zap_enclave_ptes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 362
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
void sgx_zap_enclave_ptes(struct sgx_encl * encl, long unsigned int addr)
```

```json
{
  "name": "sgx_zap_enclave_ptes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579447664,
      "name": "sgx_zap_enclave_ptes",
      "external": true,
      "loc": "arch/x86/kernel/cpu/sgx/encl.c:1179",
      "file": "arch/x86/kernel/cpu/sgx/encl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_remove_pages",
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_enclave_modify_types",
        "arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579447664,
      "name": "sgx_zap_enclave_ptes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 386
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
void sgx_zap_enclave_ptes(struct sgx_encl * encl, long unsigned int addr)
```

```json
{
  "name": "sgx_zap_enclave_ptes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579477472,
      "name": "sgx_zap_enclave_ptes",
      "external": true,
      "loc": "arch/x86/kernel/cpu/sgx/encl.c:1199",
      "file": "arch/x86/kernel/cpu/sgx/encl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_remove_pages",
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_enclave_modify_types",
        "arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579477472,
      "name": "sgx_zap_enclave_ptes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 386
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
void sgx_zap_enclave_ptes(struct sgx_encl * encl, long unsigned int addr)
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
