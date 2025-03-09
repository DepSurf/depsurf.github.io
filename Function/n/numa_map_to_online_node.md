# Function: <code>numa_map_to_online_node</code>

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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int numa_map_to_online_node(int node)
```

```json
{
  "name": "numa_map_to_online_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581780256,
      "name": "numa_map_to_online_node",
      "external": true,
      "loc": "mm/mempolicy.c:136",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/e820.c:e820_register_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581780256,
      "name": "numa_map_to_online_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int numa_map_to_online_node(int node)
```

```json
{
  "name": "numa_map_to_online_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581827776,
      "name": "numa_map_to_online_node",
      "external": true,
      "loc": "mm/mempolicy.c:136",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/nvdimm/e820.c:e820_register_one",
        "drivers/dax/hmem/device.c:hmem_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581827776,
      "name": "numa_map_to_online_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int numa_map_to_online_node(int node)
```

```json
{
  "name": "numa_map_to_online_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581856560,
      "name": "numa_map_to_online_node",
      "external": true,
      "loc": "mm/mempolicy.c:136",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/main.c:sgx_page_cache_init",
        "drivers/nvdimm/e820.c:e820_register_one",
        "drivers/dax/hmem/device.c:hmem_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581856560,
      "name": "numa_map_to_online_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int numa_map_to_online_node(int node)
```

```json
{
  "name": "numa_map_to_online_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582149776,
      "name": "numa_map_to_online_node",
      "external": true,
      "loc": "mm/mempolicy.c:138",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/main.c:sgx_page_cache_init",
        "drivers/nvdimm/e820.c:e820_register_one",
        "drivers/dax/hmem/device.c:hmem_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582149776,
      "name": "numa_map_to_online_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int numa_map_to_online_node(int node)
```

```json
{
  "name": "numa_map_to_online_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582602784,
      "name": "numa_map_to_online_node",
      "external": true,
      "loc": "mm/mempolicy.c:141",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/main.c:sgx_page_cache_init",
        "drivers/nvdimm/e820.c:e820_register_one",
        "drivers/dax/hmem/device.c:hmem_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582602784,
      "name": "numa_map_to_online_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
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
int numa_map_to_online_node(int node)
```

```json
{
  "name": "numa_map_to_online_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583126992,
      "name": "numa_map_to_online_node",
      "external": true,
      "loc": "mm/mempolicy.c:141",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/main.c:sgx_page_cache_init",
        "drivers/nvdimm/e820.c:e820_register_one",
        "drivers/dax/hmem/device.c:hmem_register_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583126992,
      "name": "numa_map_to_online_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
int numa_map_to_online_node(int node)
```

```json
{
  "name": "numa_map_to_online_node",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583337392,
      "name": "numa_map_to_online_node",
      "external": true,
      "loc": "mm/mempolicy.c:141",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/main.c:sgx_page_cache_init",
        "drivers/nvdimm/e820.c:e820_register_one"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583337392,
      "name": "numa_map_to_online_node",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
    }
  ]
}
```
</details>
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int numa_map_to_online_node(int node)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
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
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
int numa_map_to_online_node(int node)
```
</details>
</li>
</ul>
