# Function: <code>virt_to_hvpfn</code>

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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "virt_to_hvpfn",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579104645,
      "name": "virt_to_hvpfn",
      "external": false,
      "loc": "include/linux/hyperv.h:1772",
      "file": "arch/x86/hyperv/ivm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/ivm.c:hv_set_mem_host_visibility"
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
  "name": "virt_to_hvpfn",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579141877,
      "name": "virt_to_hvpfn",
      "external": false,
      "loc": "include/linux/hyperv.h:1774",
      "file": "arch/x86/hyperv/ivm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/ivm.c:hv_set_mem_host_visibility"
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
  "name": "virt_to_hvpfn",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579142741,
      "name": "virt_to_hvpfn",
      "external": false,
      "loc": "include/linux/hyperv.h:1768",
      "file": "arch/x86/hyperv/ivm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/ivm.c:hv_vtom_set_host_visibility"
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
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
long unsigned int virt_to_hvpfn(void * addr)
```

```json
{
  "name": "virt_to_hvpfn",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587564032,
      "name": "virt_to_hvpfn",
      "external": false,
      "loc": "drivers/hv/channel.c:40",
      "file": "drivers/hv/channel.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hv/channel.c:vmbus_establish_gpadl",
        "drivers/hv/channel.c:vmbus_establish_gpadl",
        "drivers/hv/channel.c:vmbus_establish_gpadl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587564032,
      "name": "virt_to_hvpfn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Flavor</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➕</summary>

```c
long unsigned int virt_to_hvpfn(void * addr)
```
</details>
</li>
</ul>
