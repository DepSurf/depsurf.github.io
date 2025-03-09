# Function: <code>msi_insert_desc</code>

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
  "name": "msi_insert_desc",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580348254,
      "name": "msi_insert_desc",
      "external": false,
      "loc": "kernel/irq/msi.c:61",
      "file": "kernel/irq/msi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/msi.c:msi_add_simple_msi_descs",
        "kernel/irq/msi.c:msi_add_msi_desc"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int msi_insert_desc(struct device * dev, struct msi_desc * desc, unsigned int domid, unsigned int index)
```

```json
{
  "name": "msi_insert_desc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580565632,
      "name": "msi_insert_desc",
      "external": false,
      "loc": "kernel/irq/msi.c:84",
      "file": "kernel/irq/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/msi.c:msi_domain_alloc_irq_at",
        "kernel/irq/msi.c:msi_domain_add_simple_msi_descs",
        "kernel/irq/msi.c:msi_domain_insert_msi_desc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580565632,
      "name": "msi_insert_desc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 362
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
int msi_insert_desc(struct device * dev, struct msi_desc * desc, unsigned int domid, unsigned int index)
```

```json
{
  "name": "msi_insert_desc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580639968,
      "name": "msi_insert_desc",
      "external": false,
      "loc": "kernel/irq/msi.c:84",
      "file": "kernel/irq/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/msi.c:msi_domain_alloc_irq_at",
        "kernel/irq/msi.c:msi_domain_add_simple_msi_descs",
        "kernel/irq/msi.c:msi_domain_insert_msi_desc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580639968,
      "name": "msi_insert_desc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 419
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
int msi_insert_desc(struct device * dev, struct msi_desc * desc, unsigned int domid, unsigned int index)
```

```json
{
  "name": "msi_insert_desc",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580705168,
      "name": "msi_insert_desc",
      "external": false,
      "loc": "kernel/irq/msi.c:84",
      "file": "kernel/irq/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/msi.c:msi_domain_alloc_irq_at",
        "kernel/irq/msi.c:msi_domain_add_simple_msi_descs",
        "kernel/irq/msi.c:msi_domain_insert_msi_desc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580705168,
      "name": "msi_insert_desc",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 419
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
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
int msi_insert_desc(struct device * dev, struct msi_desc * desc, unsigned int domid, unsigned int index)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
