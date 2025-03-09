# Function: <code>sgx_enclave_etrack</code>

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
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int sgx_enclave_etrack(struct sgx_encl * encl)
```

```json
{
  "name": "sgx_enclave_etrack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sgx_enclave_etrack",
      "external": false,
      "loc": "arch/x86/kernel/cpu/sgx/ioctl.c:693",
      "file": "arch/x86/kernel/cpu/sgx/ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_enclave_modify_types",
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_enclave_restrict_permissions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579442736,
      "name": "sgx_enclave_etrack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 323
    },
    {
      "addr": 18446744071595964382,
      "name": "sgx_enclave_etrack.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
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
int sgx_enclave_etrack(struct sgx_encl * encl)
```

```json
{
  "name": "sgx_enclave_etrack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sgx_enclave_etrack",
      "external": false,
      "loc": "arch/x86/kernel/cpu/sgx/ioctl.c:693",
      "file": "arch/x86/kernel/cpu/sgx/ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_enclave_modify_types",
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_enclave_restrict_permissions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579454832,
      "name": "sgx_enclave_etrack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 323
    },
    {
      "addr": 18446744071596481993,
      "name": "sgx_enclave_etrack.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
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
int sgx_enclave_etrack(struct sgx_encl * encl)
```

```json
{
  "name": "sgx_enclave_etrack",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sgx_enclave_etrack",
      "external": false,
      "loc": "arch/x86/kernel/cpu/sgx/ioctl.c:693",
      "file": "arch/x86/kernel/cpu/sgx/ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_enclave_modify_types",
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_enclave_restrict_permissions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579484800,
      "name": "sgx_enclave_etrack",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 323
    },
    {
      "addr": 18446744071597378093,
      "name": "sgx_enclave_etrack.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
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
int sgx_enclave_etrack(struct sgx_encl * encl)
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
