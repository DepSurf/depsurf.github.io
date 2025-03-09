# Function: <code>of_dma_controller_register</code>

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
  "name": "of_dma_controller_register",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "of_dma_controller_register",
      "external": false,
      "loc": "include/linux/of_dma.h:55",
      "file": "drivers/dma/lgm/lgm-dma.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "of_dma_controller_register",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "of_dma_controller_register",
      "external": false,
      "loc": "include/linux/of_dma.h:55",
      "file": "drivers/dma/lgm/lgm-dma.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "of_dma_controller_register",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "of_dma_controller_register",
      "external": false,
      "loc": "include/linux/of_dma.h:55",
      "file": "drivers/dma/lgm/lgm-dma.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "of_dma_controller_register",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "of_dma_controller_register",
      "external": false,
      "loc": "include/linux/of_dma.h:55",
      "file": "drivers/dma/lgm/lgm-dma.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "of_dma_controller_register",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "of_dma_controller_register",
      "external": false,
      "loc": "include/linux/of_dma.h:55",
      "file": "drivers/dma/lgm/lgm-dma.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "of_dma_controller_register",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "of_dma_controller_register",
      "external": false,
      "loc": "include/linux/of_dma.h:55",
      "file": "drivers/dma/lgm/lgm-dma.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int of_dma_controller_register(struct device_node * np, struct dma_chan * (*)(struct of_phandle_args *, struct of_dma *) of_dma_xlate, void * data)
```

```json
{
  "name": "of_dma_controller_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336498017464,
      "name": "of_dma_controller_register",
      "external": true,
      "loc": "drivers/dma/of-dma.c:101",
      "file": "drivers/dma/of-dma.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma/amba-pl08x.c:pl08x_probe",
        "drivers/dma/bcm2835-dma.c:bcm2835_dma_probe",
        "drivers/dma/mxs-dma.c:mxs_dma_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498017464,
      "name": "of_dma_controller_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int of_dma_controller_register(struct device_node * np, struct dma_chan * (*)(struct of_phandle_args *, struct of_dma *) of_dma_xlate, void * data)
```

```json
{
  "name": "of_dma_controller_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3230792984,
      "name": "of_dma_controller_register",
      "external": true,
      "loc": "drivers/dma/of-dma.c:101",
      "file": "drivers/dma/of-dma.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma/amba-pl08x.c:pl08x_probe",
        "drivers/dma/mxs-dma.c:mxs_dma_probe",
        "drivers/dma/tegra20-apb-dma.c:tegra_dma_probe",
        "drivers/dma/ti/edma.c:edma_probe",
        "drivers/dma/ti/omap-dma.c:omap_dma_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230792984,
      "name": "of_dma_controller_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int of_dma_controller_register(struct device_node * np, struct dma_chan * (*)(struct of_phandle_args *, struct of_dma *) of_dma_xlate, void * data)
```

```json
{
  "name": "of_dma_controller_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055291379296,
      "name": "of_dma_controller_register",
      "external": true,
      "loc": "drivers/dma/of-dma.c:101",
      "file": "drivers/dma/of-dma.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291379296,
      "name": "of_dma_controller_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
int of_dma_controller_register(struct device_node * np, struct dma_chan * (*)(struct of_phandle_args *, struct of_dma *) of_dma_xlate, void * data)
```

```json
{
  "name": "of_dma_controller_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275937100,
      "name": "of_dma_controller_register",
      "external": true,
      "loc": "drivers/dma/of-dma.c:101",
      "file": "drivers/dma/of-dma.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275937100,
      "name": "of_dma_controller_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 186
    }
  ]
}
```
</details>
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
int of_dma_controller_register(struct device_node * np, struct dma_chan * (*)(struct of_phandle_args *, struct of_dma *) of_dma_xlate, void * data)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int of_dma_controller_register(struct device_node * np, struct dma_chan * (*)(struct of_phandle_args *, struct of_dma *) of_dma_xlate, void * data)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
int of_dma_controller_register(struct device_node * np, struct dma_chan * (*)(struct of_phandle_args *, struct of_dma *) of_dma_xlate, void * data)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
int of_dma_controller_register(struct device_node * np, struct dma_chan * (*)(struct of_phandle_args *, struct of_dma *) of_dma_xlate, void * data)
```
</details>
</li>
</ul>
