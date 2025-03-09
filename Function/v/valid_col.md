# Function: <code>valid_col</code>

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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct its_collection * valid_col(struct its_collection * col)
```

```json
{
  "name": "valid_col",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496381920,
      "name": "valid_col",
      "external": false,
      "loc": "drivers/irqchip/irq-gic-v3-its.c:202",
      "file": "drivers/irqchip/irq-gic-v3-its.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/irqchip/irq-gic-v3-its.c:its_build_vmovp_cmd",
        "drivers/irqchip/irq-gic-v3-its.c:its_build_vmovi_cmd",
        "drivers/irqchip/irq-gic-v3-its.c:its_build_vmapti_cmd",
        "drivers/irqchip/irq-gic-v3-its.c:its_build_vmapp_cmd",
        "drivers/irqchip/irq-gic-v3-its.c:its_build_vinvall_cmd",
        "drivers/irqchip/irq-gic-v3-its.c:its_build_clear_cmd",
        "drivers/irqchip/irq-gic-v3-its.c:its_build_int_cmd",
        "drivers/irqchip/irq-gic-v3-its.c:its_build_inv_cmd",
        "drivers/irqchip/irq-gic-v3-its.c:its_build_discard_cmd",
        "drivers/irqchip/irq-gic-v3-its.c:its_build_movi_cmd",
        "drivers/irqchip/irq-gic-v3-its.c:its_build_mapti_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496381920,
      "name": "valid_col",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct its_collection * valid_col(struct its_collection * col)
```

```json
{
  "name": "valid_col",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229714224,
      "name": "valid_col",
      "external": false,
      "loc": "drivers/irqchip/irq-gic-v3-its.c:202",
      "file": "drivers/irqchip/irq-gic-v3-its.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/irqchip/irq-gic-v3-its.c:its_build_vmovp_cmd",
        "drivers/irqchip/irq-gic-v3-its.c:its_build_vmovi_cmd",
        "drivers/irqchip/irq-gic-v3-its.c:its_build_vmapti_cmd",
        "drivers/irqchip/irq-gic-v3-its.c:its_build_vmapp_cmd",
        "drivers/irqchip/irq-gic-v3-its.c:its_build_vinvall_cmd",
        "drivers/irqchip/irq-gic-v3-its.c:its_build_clear_cmd",
        "drivers/irqchip/irq-gic-v3-its.c:its_build_int_cmd",
        "drivers/irqchip/irq-gic-v3-its.c:its_build_inv_cmd",
        "drivers/irqchip/irq-gic-v3-its.c:its_build_discard_cmd",
        "drivers/irqchip/irq-gic-v3-its.c:its_build_movi_cmd",
        "drivers/irqchip/irq-gic-v3-its.c:its_build_mapti_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229714224,
      "name": "valid_col",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
    }
  ]
}
```
</details>
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
struct its_collection * valid_col(struct its_collection * col)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
struct its_collection * valid_col(struct its_collection * col)
```
</details>
</li>
</ul>
