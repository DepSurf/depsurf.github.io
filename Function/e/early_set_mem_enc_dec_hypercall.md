# Function: <code>early_set_mem_enc_dec_hypercall</code>

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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void early_set_mem_enc_dec_hypercall(long unsigned int vaddr, int npages, bool enc)
```

```json
{
  "name": "early_set_mem_enc_dec_hypercall",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071617080787,
      "name": "early_set_mem_enc_dec_hypercall",
      "external": true,
      "loc": "arch/x86/mm/mem_encrypt_amd.c:482",
      "file": "arch/x86/mm/mem_encrypt_amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_amd.c:early_set_memory_enc_dec"
      ],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_init_platform"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071617081414,
      "name": "early_set_mem_enc_dec_hypercall",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void early_set_mem_enc_dec_hypercall(long unsigned int vaddr, int npages, bool enc)
```

```json
{
  "name": "early_set_mem_enc_dec_hypercall",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071627735102,
      "name": "early_set_mem_enc_dec_hypercall",
      "external": true,
      "loc": "arch/x86/mm/mem_encrypt_amd.c:483",
      "file": "arch/x86/mm/mem_encrypt_amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_amd.c:early_set_memory_enc_dec"
      ],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_init_platform"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071627736192,
      "name": "early_set_mem_enc_dec_hypercall",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void early_set_mem_enc_dec_hypercall(long unsigned int vaddr, long unsigned int size, bool enc)
```

```json
{
  "name": "early_set_mem_enc_dec_hypercall",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071619494337,
      "name": "early_set_mem_enc_dec_hypercall",
      "external": true,
      "loc": "arch/x86/mm/mem_encrypt_amd.c:484",
      "file": "arch/x86/mm/mem_encrypt_amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_amd.c:early_set_memory_enc_dec"
      ],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_init_platform"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071619495424,
      "name": "early_set_mem_enc_dec_hypercall",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void early_set_mem_enc_dec_hypercall(long unsigned int vaddr, long unsigned int size, bool enc)
```

```json
{
  "name": "early_set_mem_enc_dec_hypercall",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071621791297,
      "name": "early_set_mem_enc_dec_hypercall",
      "external": true,
      "loc": "arch/x86/mm/mem_encrypt_amd.c:449",
      "file": "arch/x86/mm/mem_encrypt_amd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/mem_encrypt_amd.c:early_set_memory_enc_dec"
      ],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_init_platform"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071621792256,
      "name": "early_set_mem_enc_dec_hypercall",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void early_set_mem_enc_dec_hypercall(long unsigned int vaddr, int npages, bool enc)
```
</details>
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int size</code>
</li>
<li>
<b>Param removed. </b>
<code>int npages</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
