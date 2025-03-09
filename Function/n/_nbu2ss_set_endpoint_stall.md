# Function: <code>_nbu2ss_set_endpoint_stall</code>

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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void _nbu2ss_set_endpoint_stall(struct nbu2ss_udc * udc, u8 ep_adrs, bool bstall)
```

```json
{
  "name": "_nbu2ss_set_endpoint_stall",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3234192560,
      "name": "_nbu2ss_set_endpoint_stall",
      "external": false,
      "loc": "drivers/staging/emxx_udc/emxx_udc.c:1260",
      "file": "drivers/staging/emxx_udc/emxx_udc.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_udc_irq"
      ],
      "caller_func": [
        "drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_udc_irq",
        "drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_udc_irq",
        "drivers/staging/emxx_udc/emxx_udc.c:_nbu2ss_epn_set_stall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234187148,
      "name": "_nbu2ss_set_endpoint_stall",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
void _nbu2ss_set_endpoint_stall(struct nbu2ss_udc * udc, u8 ep_adrs, bool bstall)
```
</details>
</li>
</ul>
