# Function: <code>crypto_scomp_sg_free</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void crypto_scomp_sg_free(struct scatterlist * sgl)
```

```json
{
  "name": "crypto_scomp_sg_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583016624,
      "name": "crypto_scomp_sg_free",
      "external": false,
      "loc": "crypto/scompress.c:133",
      "file": "crypto/scompress.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/scompress.c:scomp_acomp_comp_decomp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583016624,
      "name": "crypto_scomp_sg_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void crypto_scomp_sg_free(struct scatterlist * sgl)
```

```json
{
  "name": "crypto_scomp_sg_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583069754,
      "name": "crypto_scomp_sg_free",
      "external": false,
      "loc": "crypto/scompress.c:134",
      "file": "crypto/scompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/scompress.c:scomp_acomp_comp_decomp"
      ],
      "caller_func": [
        "crypto/scompress.c:scomp_acomp_comp_decomp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583068304,
      "name": "crypto_scomp_sg_free.part.2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
    },
    {
      "addr": 18446744071583068400,
      "name": "crypto_scomp_sg_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void crypto_scomp_sg_free(struct scatterlist * sgl)
```

```json
{
  "name": "crypto_scomp_sg_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583235964,
      "name": "crypto_scomp_sg_free",
      "external": false,
      "loc": "crypto/scompress.c:143",
      "file": "crypto/scompress.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "crypto/scompress.c:scomp_acomp_comp_decomp"
      ],
      "caller_func": [
        "crypto/scompress.c:scomp_acomp_comp_decomp"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583234880,
      "name": "crypto_scomp_sg_free.part.2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 87
    },
    {
      "addr": 18446744071583234976,
      "name": "crypto_scomp_sg_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    }
  ]
}
```
</details>
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
<details>
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
void crypto_scomp_sg_free(struct scatterlist * sgl)
```
</details>
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
void crypto_scomp_sg_free(struct scatterlist * sgl)
```
</details>
</li>
</ul>
