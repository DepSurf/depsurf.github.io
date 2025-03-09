# Function: <code>hv_is_isolation_supported</code>

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
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
bool hv_is_isolation_supported()
```

```json
{
  "name": "hv_is_isolation_supported",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579046224,
      "name": "hv_is_isolation_supported",
      "external": true,
      "loc": "arch/x86/hyperv/hv_init.c:620",
      "file": "arch/x86/hyperv/hv_init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579046224,
      "name": "hv_is_isolation_supported",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
bool hv_is_isolation_supported()
```

```json
{
  "name": "hv_is_isolation_supported",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579069024,
      "name": "hv_is_isolation_supported",
      "external": true,
      "loc": "arch/x86/hyperv/hv_init.c:565",
      "file": "arch/x86/hyperv/hv_init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579069024,
      "name": "hv_is_isolation_supported",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
bool hv_is_isolation_supported()
```

```json
{
  "name": "hv_is_isolation_supported",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579103744,
      "name": "hv_is_isolation_supported",
      "external": true,
      "loc": "arch/x86/hyperv/ivm.c:250",
      "file": "arch/x86/hyperv/ivm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/hyperv/ivm.c:hv_set_mem_host_visibility",
        "arch/x86/hyperv/ivm.c:hv_mark_gpa_visibility",
        "arch/x86/mm/pat/set_memory.c:set_memory_decrypted",
        "arch/x86/mm/pat/set_memory.c:set_memory_encrypted"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579103744,
      "name": "hv_is_isolation_supported",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
bool hv_is_isolation_supported()
```

```json
{
  "name": "hv_is_isolation_supported",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579140912,
      "name": "hv_is_isolation_supported",
      "external": true,
      "loc": "arch/x86/hyperv/ivm.c:250",
      "file": "arch/x86/hyperv/ivm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_init.c:hyperv_init",
        "arch/x86/hyperv/ivm.c:hv_set_mem_host_visibility",
        "arch/x86/hyperv/ivm.c:hv_mark_gpa_visibility",
        "arch/x86/mm/pat/set_memory.c:set_memory_decrypted",
        "arch/x86/mm/pat/set_memory.c:set_memory_encrypted"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579140912,
      "name": "hv_is_isolation_supported",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
bool hv_is_isolation_supported()
```

```json
{
  "name": "hv_is_isolation_supported",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579141856,
      "name": "hv_is_isolation_supported",
      "external": true,
      "loc": "arch/x86/hyperv/ivm.c:394",
      "file": "arch/x86/hyperv/ivm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/ivm.c:hv_mark_gpa_visibility",
        "arch/x86/kernel/cpu/mtrr/generic.c:mtrr_overwrite_state",
        "drivers/hv/hv_common.c:hv_common_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579141856,
      "name": "hv_is_isolation_supported",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
bool hv_is_isolation_supported()
```

```json
{
  "name": "hv_is_isolation_supported",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579170768,
      "name": "hv_is_isolation_supported",
      "external": true,
      "loc": "arch/x86/hyperv/ivm.c:686",
      "file": "arch/x86/hyperv/ivm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/ivm.c:hv_mark_gpa_visibility",
        "arch/x86/kernel/cpu/mtrr/generic.c:mtrr_overwrite_state",
        "drivers/hv/hv_common.c:hv_common_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579170768,
      "name": "hv_is_isolation_supported",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
bool hv_is_isolation_supported()
```
</details>
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
