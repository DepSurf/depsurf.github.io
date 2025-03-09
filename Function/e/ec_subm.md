# Function: <code>ec_subm</code>

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
void ec_subm(MPI w, MPI u, MPI v, struct mpi_ec_ctx * ec)
```

```json
{
  "name": "ec_subm",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585141560,
      "name": "ec_subm",
      "external": false,
      "loc": "lib/mpi/ec.c:128",
      "file": "lib/mpi/ec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/mpi/ec.c:mpi_ec_curve_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
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
      "addr": 18446744071585128736,
      "name": "ec_subm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
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
void ec_subm(MPI w, MPI u, MPI v, struct mpi_ec_ctx * ec)
```

```json
{
  "name": "ec_subm",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585022152,
      "name": "ec_subm",
      "external": false,
      "loc": "lib/mpi/ec.c:128",
      "file": "lib/mpi/ec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/mpi/ec.c:mpi_ec_curve_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
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
      "addr": 18446744071585009296,
      "name": "ec_subm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
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
void ec_subm(MPI w, MPI u, MPI v, struct mpi_ec_ctx * ec)
```

```json
{
  "name": "ec_subm",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585465080,
      "name": "ec_subm",
      "external": false,
      "loc": "lib/mpi/ec.c:128",
      "file": "lib/mpi/ec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/mpi/ec.c:mpi_ec_curve_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
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
      "addr": 18446744071585451072,
      "name": "ec_subm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
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
void ec_subm(MPI w, MPI u, MPI v, struct mpi_ec_ctx * ec)
```

```json
{
  "name": "ec_subm",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586607716,
      "name": "ec_subm",
      "external": false,
      "loc": "lib/mpi/ec.c:128",
      "file": "lib/mpi/ec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/mpi/ec.c:mpi_ec_curve_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
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
      "addr": 18446744071586592928,
      "name": "ec_subm",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ec_subm(MPI w, MPI u, MPI v, struct mpi_ec_ctx * ec)
```

```json
{
  "name": "ec_subm",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587849524,
      "name": "ec_subm",
      "external": false,
      "loc": "lib/mpi/ec.c:128",
      "file": "lib/mpi/ec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/mpi/ec.c:mpi_ec_curve_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
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
      "addr": 18446744071587833920,
      "name": "ec_subm",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ec_subm(MPI w, MPI u, MPI v, struct mpi_ec_ctx * ec)
```

```json
{
  "name": "ec_subm",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588121044,
      "name": "ec_subm",
      "external": false,
      "loc": "lib/mpi/ec.c:128",
      "file": "lib/mpi/ec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/mpi/ec.c:mpi_ec_curve_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
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
      "addr": 18446744071588105408,
      "name": "ec_subm",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void ec_subm(MPI w, MPI u, MPI v, struct mpi_ec_ctx * ec)
```

```json
{
  "name": "ec_subm",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587689780,
      "name": "ec_subm",
      "external": false,
      "loc": "lib/crypto/mpi/ec.c:128",
      "file": "lib/crypto/mpi/ec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/crypto/mpi/ec.c:mpi_ec_curve_point",
        "lib/crypto/mpi/ec.c:mpi_ec_mul_point",
        "lib/crypto/mpi/ec.c:add_points_weierstrass",
        "lib/crypto/mpi/ec.c:add_points_weierstrass",
        "lib/crypto/mpi/ec.c:add_points_weierstrass",
        "lib/crypto/mpi/ec.c:add_points_weierstrass",
        "lib/crypto/mpi/ec.c:add_points_weierstrass",
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
      "addr": 18446744071587674080,
      "name": "ec_subm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
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
void ec_subm(MPI w, MPI u, MPI v, struct mpi_ec_ctx * ec)
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
