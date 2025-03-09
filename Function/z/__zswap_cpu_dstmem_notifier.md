# Function: <code>__zswap_cpu_dstmem_notifier</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __zswap_cpu_dstmem_notifier(long unsigned int action, long unsigned int cpu)
```

```json
{
  "name": "__zswap_cpu_dstmem_notifier",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580777344,
      "name": "__zswap_cpu_dstmem_notifier",
      "external": false,
      "loc": "mm/zswap.c:353",
      "file": "mm/zswap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/zswap.c:init_zswap"
      ],
      "caller_func": [
        "mm/zswap.c:zswap_cpu_dstmem_notifier",
        "mm/zswap.c:init_zswap",
        "mm/zswap.c:init_zswap",
        "mm/zswap.c:init_zswap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580777344,
      "name": "__zswap_cpu_dstmem_notifier.part.4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
    },
    {
      "addr": 18446744071580777456,
      "name": "__zswap_cpu_dstmem_notifier",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __zswap_cpu_dstmem_notifier(long unsigned int action, long unsigned int cpu)
```

```json
{
  "name": "__zswap_cpu_dstmem_notifier",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595316340,
      "name": "__zswap_cpu_dstmem_notifier",
      "external": false,
      "loc": "mm/zswap.c:355",
      "file": "mm/zswap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/zswap.c:init_zswap"
      ],
      "caller_func": [
        "mm/zswap.c:init_zswap",
        "mm/zswap.c:init_zswap",
        "mm/zswap.c:init_zswap",
        "mm/zswap.c:zswap_cpu_dstmem_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580900480,
      "name": "__zswap_cpu_dstmem_notifier.part.6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 107
    },
    {
      "addr": 18446744071580900592,
      "name": "__zswap_cpu_dstmem_notifier",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
    }
  ]
}
```
</details>
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
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➖</summary>

```c
int __zswap_cpu_dstmem_notifier(long unsigned int action, long unsigned int cpu)
```
</details>
</li>
</ul>
