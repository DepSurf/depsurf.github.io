# Function: <code>__vgic_v3_read_ap0rn</code>

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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
u32 __vgic_v3_read_ap0rn(int n)
```

```json
{
  "name": "__vgic_v3_read_ap0rn",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336503970220,
      "name": "__vgic_v3_read_ap0rn",
      "external": false,
      "loc": "virt/kvm/arm/hyp/vgic-v3-sr.c:149",
      "file": "virt/kvm/arm/hyp/vgic-v3-sr.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "virt/kvm/arm/hyp/vgic-v3-sr.c:__vgic_v3_save_aprs",
        "virt/kvm/arm/hyp/vgic-v3-sr.c:__vgic_v3_save_aprs",
        "virt/kvm/arm/hyp/vgic-v3-sr.c:__vgic_v3_save_aprs",
        "virt/kvm/arm/hyp/vgic-v3-sr.c:__vgic_v3_save_aprs"
      ],
      "caller_func": [
        "virt/kvm/arm/hyp/vgic-v3-sr.c:__vgic_v3_read_apxrn",
        "virt/kvm/arm/hyp/vgic-v3-sr.c:__vgic_v3_write_eoir",
        "virt/kvm/arm/hyp/vgic-v3-sr.c:__vgic_v3_read_iar",
        "virt/kvm/arm/hyp/vgic-v3-sr.c:__vgic_v3_get_highest_active_priority"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503967616,
      "name": "__vgic_v3_read_ap0rn",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    }
  ]
}
```
</details>
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
u32 __vgic_v3_read_ap0rn(int n)
```
</details>
</li>
</ul>
