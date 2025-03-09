# Function: <code>sgx_encl_init</code>

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
int sgx_encl_init(struct sgx_encl * encl, struct sgx_sigstruct * sigstruct, void * token)
```

```json
{
  "name": "sgx_encl_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579266864,
      "name": "sgx_encl_init",
      "external": false,
      "loc": "arch/x86/kernel/cpu/sgx/ioctl.c:494",
      "file": "arch/x86/kernel/cpu/sgx/ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioc_enclave_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579266864,
      "name": "sgx_encl_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 650
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
int sgx_encl_init(struct sgx_encl * encl, struct sgx_sigstruct * sigstruct, void * token)
```

```json
{
  "name": "sgx_encl_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579268304,
      "name": "sgx_encl_init",
      "external": false,
      "loc": "arch/x86/kernel/cpu/sgx/ioctl.c:495",
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
      "addr": 18446744071579268304,
      "name": "sgx_encl_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 597
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int sgx_encl_init(struct sgx_encl * encl, struct sgx_sigstruct * sigstruct, void * token)
```

```json
{
  "name": "sgx_encl_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sgx_encl_init",
      "external": false,
      "loc": "arch/x86/kernel/cpu/sgx/ioctl.c:495",
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
      "addr": 18446744071579310208,
      "name": "sgx_encl_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 653
    },
    {
      "addr": 18446744071592070714,
      "name": "sgx_encl_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int sgx_encl_init(struct sgx_encl * encl, struct sgx_sigstruct * sigstruct, void * token)
```

```json
{
  "name": "sgx_encl_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sgx_encl_init",
      "external": false,
      "loc": "arch/x86/kernel/cpu/sgx/ioctl.c:495",
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
      "addr": 18446744071579367696,
      "name": "sgx_encl_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 724
    },
    {
      "addr": 18446744071593837013,
      "name": "sgx_encl_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
int sgx_encl_init(struct sgx_encl * encl, struct sgx_sigstruct * sigstruct, void * token)
```

```json
{
  "name": "sgx_encl_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sgx_encl_init",
      "external": false,
      "loc": "arch/x86/kernel/cpu/sgx/ioctl.c:484",
      "file": "arch/x86/kernel/cpu/sgx/ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioc_enclave_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579441664,
      "name": "sgx_encl_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 724
    },
    {
      "addr": 18446744071595964362,
      "name": "sgx_encl_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
int sgx_encl_init(struct sgx_encl * encl, struct sgx_sigstruct * sigstruct, void * token)
```

```json
{
  "name": "sgx_encl_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sgx_encl_init",
      "external": false,
      "loc": "arch/x86/kernel/cpu/sgx/ioctl.c:484",
      "file": "arch/x86/kernel/cpu/sgx/ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioc_enclave_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579453744,
      "name": "sgx_encl_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 749
    },
    {
      "addr": 18446744071596481973,
      "name": "sgx_encl_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
int sgx_encl_init(struct sgx_encl * encl, struct sgx_sigstruct * sigstruct, void * token)
```

```json
{
  "name": "sgx_encl_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "sgx_encl_init",
      "external": false,
      "loc": "arch/x86/kernel/cpu/sgx/ioctl.c:484",
      "file": "arch/x86/kernel/cpu/sgx/ioctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioc_enclave_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579483664,
      "name": "sgx_encl_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 749
    },
    {
      "addr": 18446744071597378073,
      "name": "sgx_encl_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
int sgx_encl_init(struct sgx_encl * encl, struct sgx_sigstruct * sigstruct, void * token)
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
