# Function: <code>hv_get_partition_id</code>

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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "hv_get_partition_id",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071614255186,
      "name": "hv_get_partition_id",
      "external": false,
      "loc": "arch/x86/hyperv/hv_init.c:349",
      "file": "arch/x86/hyperv/hv_init.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/hyperv/hv_init.c:hyperv_init"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void hv_get_partition_id()
```

```json
{
  "name": "hv_get_partition_id",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071615175216,
      "name": "hv_get_partition_id",
      "external": false,
      "loc": "arch/x86/hyperv/hv_init.c:331",
      "file": "arch/x86/hyperv/hv_init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_init.c:hyperv_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615175216,
      "name": "hv_get_partition_id",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 167
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
void hv_get_partition_id()
```

```json
{
  "name": "hv_get_partition_id",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071616940749,
      "name": "hv_get_partition_id",
      "external": false,
      "loc": "arch/x86/hyperv/hv_init.c:371",
      "file": "arch/x86/hyperv/hv_init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_init.c:hyperv_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071616940749,
      "name": "hv_get_partition_id",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 190
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
void hv_get_partition_id()
```

```json
{
  "name": "hv_get_partition_id",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071627548272,
      "name": "hv_get_partition_id",
      "external": false,
      "loc": "arch/x86/hyperv/hv_init.c:361",
      "file": "arch/x86/hyperv/hv_init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_init.c:hyperv_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071627548272,
      "name": "hv_get_partition_id",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 195
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
void hv_get_partition_id()
```

```json
{
  "name": "hv_get_partition_id",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071619294608,
      "name": "hv_get_partition_id",
      "external": false,
      "loc": "arch/x86/hyperv/hv_init.c:364",
      "file": "arch/x86/hyperv/hv_init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_init.c:hyperv_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071619294608,
      "name": "hv_get_partition_id",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 195
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
void hv_get_partition_id()
```

```json
{
  "name": "hv_get_partition_id",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071621587216,
      "name": "hv_get_partition_id",
      "external": false,
      "loc": "arch/x86/hyperv/hv_init.c:398",
      "file": "arch/x86/hyperv/hv_init.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/hv_init.c:hyperv_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071621587216,
      "name": "hv_get_partition_id",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 119
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
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
void hv_get_partition_id()
```
</details>
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
