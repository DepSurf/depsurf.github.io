# Function: <code>sgx_vma_access</code>

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
int sgx_vma_access(struct vm_area_struct * vma, long unsigned int addr, void * buf, int len, int write)
```

```json
{
  "name": "sgx_vma_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579264320,
      "name": "sgx_vma_access",
      "external": false,
      "loc": "arch/x86/kernel/cpu/sgx/encl.c:327",
      "file": "arch/x86/kernel/cpu/sgx/encl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579264320,
      "name": "sgx_vma_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 815
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
int sgx_vma_access(struct vm_area_struct * vma, long unsigned int addr, void * buf, int len, int write)
```

```json
{
  "name": "sgx_vma_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579266048,
      "name": "sgx_vma_access",
      "external": false,
      "loc": "arch/x86/kernel/cpu/sgx/encl.c:319",
      "file": "arch/x86/kernel/cpu/sgx/encl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579266048,
      "name": "sgx_vma_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 798
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
int sgx_vma_access(struct vm_area_struct * vma, long unsigned int addr, void * buf, int len, int write)
```

```json
{
  "name": "sgx_vma_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579307712,
      "name": "sgx_vma_access",
      "external": false,
      "loc": "arch/x86/kernel/cpu/sgx/encl.c:360",
      "file": "arch/x86/kernel/cpu/sgx/encl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579307712,
      "name": "sgx_vma_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 887
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
int sgx_vma_access(struct vm_area_struct * vma, long unsigned int addr, void * buf, int len, int write)
```

```json
{
  "name": "sgx_vma_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579365056,
      "name": "sgx_vma_access",
      "external": false,
      "loc": "arch/x86/kernel/cpu/sgx/encl.c:461",
      "file": "arch/x86/kernel/cpu/sgx/encl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579365056,
      "name": "sgx_vma_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 718
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
int sgx_vma_access(struct vm_area_struct * vma, long unsigned int addr, void * buf, int len, int write)
```

```json
{
  "name": "sgx_vma_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579436912,
      "name": "sgx_vma_access",
      "external": false,
      "loc": "arch/x86/kernel/cpu/sgx/encl.c:608",
      "file": "arch/x86/kernel/cpu/sgx/encl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579436912,
      "name": "sgx_vma_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 760
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
int sgx_vma_access(struct vm_area_struct * vma, long unsigned int addr, void * buf, int len, int write)
```

```json
{
  "name": "sgx_vma_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579448960,
      "name": "sgx_vma_access",
      "external": false,
      "loc": "arch/x86/kernel/cpu/sgx/encl.c:608",
      "file": "arch/x86/kernel/cpu/sgx/encl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579448960,
      "name": "sgx_vma_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 788
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
int sgx_vma_access(struct vm_area_struct * vma, long unsigned int addr, void * buf, int len, int write)
```

```json
{
  "name": "sgx_vma_access",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579478768,
      "name": "sgx_vma_access",
      "external": false,
      "loc": "arch/x86/kernel/cpu/sgx/encl.c:628",
      "file": "arch/x86/kernel/cpu/sgx/encl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579478768,
      "name": "sgx_vma_access",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 788
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
int sgx_vma_access(struct vm_area_struct * vma, long unsigned int addr, void * buf, int len, int write)
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
