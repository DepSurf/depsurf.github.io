# Function: <code>sev_map_percpu_data</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sev_map_percpu_data",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602698649,
      "name": "sev_map_percpu_data",
      "external": false,
      "loc": "arch/x86/kernel/kvm.c:442",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sev_map_percpu_data",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602870177,
      "name": "sev_map_percpu_data",
      "external": false,
      "loc": "arch/x86/kernel/kvm.c:442",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sev_map_percpu_data",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604667375,
      "name": "sev_map_percpu_data",
      "external": false,
      "loc": "arch/x86/kernel/kvm.c:433",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sev_map_percpu_data",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604766146,
      "name": "sev_map_percpu_data",
      "external": false,
      "loc": "arch/x86/kernel/kvm.c:417",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sev_map_percpu_data",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604791965,
      "name": "sev_map_percpu_data",
      "external": false,
      "loc": "arch/x86/kernel/kvm.c:417",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void sev_map_percpu_data()
```

```json
{
  "name": "sev_map_percpu_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071609134219,
      "name": "sev_map_percpu_data",
      "external": false,
      "loc": "arch/x86/kernel/kvm.c:419",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609134219,
      "name": "sev_map_percpu_data",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 150
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void sev_map_percpu_data()
```

```json
{
  "name": "sev_map_percpu_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071612202792,
      "name": "sev_map_percpu_data",
      "external": false,
      "loc": "arch/x86/kernel/kvm.c:440",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612202792,
      "name": "sev_map_percpu_data",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 150
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sev_map_percpu_data",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071614344616,
      "name": "sev_map_percpu_data",
      "external": false,
      "loc": "arch/x86/kernel/kvm.c:417",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sev_map_percpu_data",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071615275095,
      "name": "sev_map_percpu_data",
      "external": false,
      "loc": "arch/x86/kernel/kvm.c:417",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sev_map_percpu_data",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071617051667,
      "name": "sev_map_percpu_data",
      "external": false,
      "loc": "arch/x86/kernel/kvm.c:434",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sev_map_percpu_data",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071627695253,
      "name": "sev_map_percpu_data",
      "external": false,
      "loc": "arch/x86/kernel/kvm.c:433",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sev_map_percpu_data",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071619452949,
      "name": "sev_map_percpu_data",
      "external": false,
      "loc": "arch/x86/kernel/kvm.c:433",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sev_map_percpu_data",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071621749061,
      "name": "sev_map_percpu_data",
      "external": false,
      "loc": "arch/x86/kernel/kvm.c:433",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu"
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sev_map_percpu_data",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604705907,
      "name": "sev_map_percpu_data",
      "external": false,
      "loc": "arch/x86/kernel/kvm.c:417",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sev_map_percpu_data",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604674410,
      "name": "sev_map_percpu_data",
      "external": false,
      "loc": "arch/x86/kernel/kvm.c:417",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sev_map_percpu_data",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604783474,
      "name": "sev_map_percpu_data",
      "external": false,
      "loc": "arch/x86/kernel/kvm.c:417",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sev_map_percpu_data",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604796106,
      "name": "sev_map_percpu_data",
      "external": false,
      "loc": "arch/x86/kernel/kvm.c:417",
      "file": "arch/x86/kernel/kvm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu"
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void sev_map_percpu_data()
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
void sev_map_percpu_data()
```
</details>
</li>
</ul>
