# Function: <code>sgx_encl_create</code>

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
int sgx_encl_create(struct sgx_encl * encl, struct sgx_secs * secs)
```

```json
{
  "name": "sgx_encl_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579268048,
      "name": "sgx_encl_create",
      "external": false,
      "loc": "arch/x86/kernel/cpu/sgx/ioctl.c:56",
      "file": "arch/x86/kernel/cpu/sgx/ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioc_enclave_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579268048,
      "name": "sgx_encl_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 555
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
int sgx_encl_create(struct sgx_encl * encl, struct sgx_secs * secs)
```

```json
{
  "name": "sgx_encl_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579270560,
      "name": "sgx_encl_create",
      "external": false,
      "loc": "arch/x86/kernel/cpu/sgx/ioctl.c:57",
      "file": "arch/x86/kernel/cpu/sgx/ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579270560,
      "name": "sgx_encl_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 553
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
int sgx_encl_create(struct sgx_encl * encl, struct sgx_secs * secs)
```

```json
{
  "name": "sgx_encl_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579312640,
      "name": "sgx_encl_create",
      "external": false,
      "loc": "arch/x86/kernel/cpu/sgx/ioctl.c:57",
      "file": "arch/x86/kernel/cpu/sgx/ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579312640,
      "name": "sgx_encl_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 591
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
int sgx_encl_create(struct sgx_encl * encl, struct sgx_secs * secs)
```

```json
{
  "name": "sgx_encl_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579368592,
      "name": "sgx_encl_create",
      "external": false,
      "loc": "arch/x86/kernel/cpu/sgx/ioctl.c:57",
      "file": "arch/x86/kernel/cpu/sgx/ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579368592,
      "name": "sgx_encl_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 646
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
int sgx_encl_create(struct sgx_encl * encl, struct sgx_secs * secs)
```

```json
{
  "name": "sgx_encl_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579444672,
      "name": "sgx_encl_create",
      "external": false,
      "loc": "arch/x86/kernel/cpu/sgx/ioctl.c:57",
      "file": "arch/x86/kernel/cpu/sgx/ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579444672,
      "name": "sgx_encl_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 660
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
int sgx_encl_create(struct sgx_encl * encl, struct sgx_secs * secs)
```

```json
{
  "name": "sgx_encl_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579456752,
      "name": "sgx_encl_create",
      "external": false,
      "loc": "arch/x86/kernel/cpu/sgx/ioctl.c:57",
      "file": "arch/x86/kernel/cpu/sgx/ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579456752,
      "name": "sgx_encl_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 660
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
int sgx_encl_create(struct sgx_encl * encl, struct sgx_secs * secs)
```

```json
{
  "name": "sgx_encl_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579486768,
      "name": "sgx_encl_create",
      "external": false,
      "loc": "arch/x86/kernel/cpu/sgx/ioctl.c:57",
      "file": "arch/x86/kernel/cpu/sgx/ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579486768,
      "name": "sgx_encl_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 660
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
int sgx_encl_create(struct sgx_encl * encl, struct sgx_secs * secs)
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
