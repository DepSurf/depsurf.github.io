# Function: <code>msi_find_desc</code>

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
struct msi_desc * msi_find_desc(struct msi_device_data * md, enum msi_desc_filter filter)
```

```json
{
  "name": "msi_find_desc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580347178,
      "name": "msi_find_desc",
      "external": false,
      "loc": "kernel/irq/msi.c:244",
      "file": "kernel/irq/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/msi.c:__msi_domain_free_irqs",
        "kernel/irq/msi.c:__msi_domain_free_irqs",
        "kernel/irq/msi.c:__msi_domain_alloc_irqs",
        "kernel/irq/msi.c:__msi_domain_alloc_irqs",
        "kernel/irq/msi.c:__msi_domain_alloc_irqs"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580346768,
      "name": "msi_find_desc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 173
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
struct msi_desc * msi_find_desc(struct msi_device_data * md, unsigned int domid, enum msi_desc_filter filter)
```

```json
{
  "name": "msi_find_desc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580568626,
      "name": "msi_find_desc",
      "external": false,
      "loc": "kernel/irq/msi.c:350",
      "file": "kernel/irq/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/msi.c:__msi_domain_alloc_irqs"
      ],
      "caller_func": [
        "kernel/irq/msi.c:msi_next_desc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580562560,
      "name": "msi_find_desc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 209
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
struct msi_desc * msi_find_desc(struct msi_device_data * md, unsigned int domid, enum msi_desc_filter filter)
```

```json
{
  "name": "msi_find_desc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580642145,
      "name": "msi_find_desc",
      "external": false,
      "loc": "kernel/irq/msi.c:350",
      "file": "kernel/irq/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/msi.c:__msi_domain_alloc_irqs",
        "kernel/irq/msi.c:msi_device_destroy_sysfs",
        "kernel/irq/msi.c:msi_device_destroy_sysfs",
        "kernel/irq/msi.c:msi_device_populate_sysfs",
        "kernel/irq/msi.c:msi_device_populate_sysfs"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580635984,
      "name": "msi_find_desc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
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
struct msi_desc * msi_find_desc(struct msi_device_data * md, unsigned int domid, enum msi_desc_filter filter)
```

```json
{
  "name": "msi_find_desc",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580707376,
      "name": "msi_find_desc",
      "external": false,
      "loc": "kernel/irq/msi.c:350",
      "file": "kernel/irq/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/msi.c:__msi_domain_alloc_irqs",
        "kernel/irq/msi.c:msi_device_destroy_sysfs",
        "kernel/irq/msi.c:msi_device_destroy_sysfs",
        "kernel/irq/msi.c:msi_device_populate_sysfs",
        "kernel/irq/msi.c:msi_device_populate_sysfs"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580701136,
      "name": "msi_find_desc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
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
struct msi_desc * msi_find_desc(struct msi_device_data * md, enum msi_desc_filter filter)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int domid</code>
</li>
<li>
<b>Param reordered. </b>
<code>md, filter</code> ➡️ <code>md, domid, filter</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
