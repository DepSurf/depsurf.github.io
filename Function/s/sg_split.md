# Function: <code>sg_split</code>

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
int sg_split(struct scatterlist * in, const int in_mapped_nents, const off_t skip, const int nb_splits, const size_t * split_sizes, struct scatterlist * * out, int * out_mapped_nents, gfp_t gfp_mask)
```

```json
{
  "name": "sg_split",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496346104,
      "name": "sg_split",
      "external": true,
      "loc": "lib/sg_split.c:148",
      "file": "lib/sg_split.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_rx_dma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496346104,
      "name": "sg_split",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 856
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
int sg_split(struct scatterlist * in, const int in_mapped_nents, const off_t skip, const int nb_splits, const size_t * split_sizes, struct scatterlist * * out, int * out_mapped_nents, gfp_t gfp_mask)
```

```json
{
  "name": "sg_split",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229678496,
      "name": "sg_split",
      "external": true,
      "loc": "lib/sg_split.c:148",
      "file": "lib/sg_split.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_rx_dma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229678496,
      "name": "sg_split",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 864
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
int sg_split(struct scatterlist * in, const int in_mapped_nents, const off_t skip, const int nb_splits, const size_t * split_sizes, struct scatterlist * * out, int * out_mapped_nents, gfp_t gfp_mask)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int sg_split(struct scatterlist * in, const int in_mapped_nents, const off_t skip, const int nb_splits, const size_t * split_sizes, struct scatterlist * * out, int * out_mapped_nents, gfp_t gfp_mask)
```
</details>
</li>
</ul>
