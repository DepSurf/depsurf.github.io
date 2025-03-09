# Function: <code>ec_pow2</code>

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
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ec_pow2(MPI w, const MPI b, struct mpi_ec_ctx * ctx)
```

```json
{
  "name": "ec_pow2",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585140679,
      "name": "ec_pow2",
      "external": false,
      "loc": "lib/mpi/ec.c:160",
      "file": "lib/mpi/ec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/mpi/ec.c:mpi_ec_curve_point",
        "lib/mpi/ec.c:mpi_ec_curve_point",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585133008,
      "name": "ec_pow2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ec_pow2(MPI w, const MPI b, struct mpi_ec_ctx * ctx)
```

```json
{
  "name": "ec_pow2",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585021271,
      "name": "ec_pow2",
      "external": false,
      "loc": "lib/mpi/ec.c:160",
      "file": "lib/mpi/ec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/mpi/ec.c:mpi_ec_curve_point",
        "lib/mpi/ec.c:mpi_ec_curve_point",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585013504,
      "name": "ec_pow2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ec_pow2(MPI w, const MPI b, struct mpi_ec_ctx * ctx)
```

```json
{
  "name": "ec_pow2",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585464199,
      "name": "ec_pow2",
      "external": false,
      "loc": "lib/mpi/ec.c:160",
      "file": "lib/mpi/ec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/mpi/ec.c:mpi_ec_curve_point",
        "lib/mpi/ec.c:mpi_ec_curve_point",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585456432,
      "name": "ec_pow2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ec_pow2(MPI w, const MPI b, struct mpi_ec_ctx * ctx)
```

```json
{
  "name": "ec_pow2",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586606874,
      "name": "ec_pow2",
      "external": false,
      "loc": "lib/mpi/ec.c:160",
      "file": "lib/mpi/ec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/mpi/ec.c:mpi_ec_curve_point",
        "lib/mpi/ec.c:mpi_ec_curve_point",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586598912,
      "name": "ec_pow2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
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
void ec_pow2(MPI w, const MPI b, struct mpi_ec_ctx * ctx)
```

```json
{
  "name": "ec_pow2",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587848682,
      "name": "ec_pow2",
      "external": false,
      "loc": "lib/mpi/ec.c:160",
      "file": "lib/mpi/ec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/mpi/ec.c:mpi_ec_curve_point",
        "lib/mpi/ec.c:mpi_ec_curve_point",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587840016,
      "name": "ec_pow2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
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
void ec_pow2(MPI w, const MPI b, struct mpi_ec_ctx * ctx)
```

```json
{
  "name": "ec_pow2",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588120202,
      "name": "ec_pow2",
      "external": false,
      "loc": "lib/mpi/ec.c:160",
      "file": "lib/mpi/ec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/mpi/ec.c:mpi_ec_curve_point",
        "lib/mpi/ec.c:mpi_ec_curve_point",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588111600,
      "name": "ec_pow2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
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
void ec_pow2(MPI w, const MPI b, struct mpi_ec_ctx * ctx)
```

```json
{
  "name": "ec_pow2",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587688938,
      "name": "ec_pow2",
      "external": false,
      "loc": "lib/crypto/mpi/ec.c:160",
      "file": "lib/crypto/mpi/ec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/crypto/mpi/ec.c:mpi_ec_curve_point",
        "lib/crypto/mpi/ec.c:mpi_ec_curve_point",
        "lib/crypto/mpi/ec.c:add_points_weierstrass",
        "lib/crypto/mpi/ec.c:add_points_weierstrass",
        "lib/crypto/mpi/ec.c:add_points_weierstrass",
        "lib/crypto/mpi/ec.c:add_points_weierstrass",
        "lib/crypto/mpi/ec.c:dup_point_weierstrass",
        "lib/crypto/mpi/ec.c:dup_point_weierstrass",
        "lib/crypto/mpi/ec.c:dup_point_weierstrass",
        "lib/crypto/mpi/ec.c:dup_point_weierstrass",
        "lib/crypto/mpi/ec.c:dup_point_weierstrass"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587680336,
      "name": "ec_pow2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
void ec_pow2(MPI w, const MPI b, struct mpi_ec_ctx * ctx)
```
</details>
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
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
