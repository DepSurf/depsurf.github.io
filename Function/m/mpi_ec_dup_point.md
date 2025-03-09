# Function: <code>mpi_ec_dup_point</code>

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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void mpi_ec_dup_point(MPI_POINT result, MPI_POINT point, struct mpi_ec_ctx * ctx)
```

```json
{
  "name": "mpi_ec_dup_point",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591380902,
      "name": "mpi_ec_dup_point",
      "external": false,
      "loc": "lib/mpi/ec.c:915",
      "file": "lib/mpi/ec.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:add_points_weierstrass"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585135424,
      "name": "mpi_ec_dup_point",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071591380902,
      "name": "mpi_ec_dup_point.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void mpi_ec_dup_point(MPI_POINT result, MPI_POINT point, struct mpi_ec_ctx * ctx)
```

```json
{
  "name": "mpi_ec_dup_point",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591323289,
      "name": "mpi_ec_dup_point",
      "external": false,
      "loc": "lib/mpi/ec.c:915",
      "file": "lib/mpi/ec.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:add_points_weierstrass"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585015920,
      "name": "mpi_ec_dup_point",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071591323289,
      "name": "mpi_ec_dup_point.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void mpi_ec_dup_point(MPI_POINT result, MPI_POINT point, struct mpi_ec_ctx * ctx)
```

```json
{
  "name": "mpi_ec_dup_point",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592337583,
      "name": "mpi_ec_dup_point",
      "external": false,
      "loc": "lib/mpi/ec.c:915",
      "file": "lib/mpi/ec.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:add_points_weierstrass"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585458848,
      "name": "mpi_ec_dup_point",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071592337583,
      "name": "mpi_ec_dup_point.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void mpi_ec_dup_point(MPI_POINT result, MPI_POINT point, struct mpi_ec_ctx * ctx)
```

```json
{
  "name": "mpi_ec_dup_point",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594198038,
      "name": "mpi_ec_dup_point",
      "external": false,
      "loc": "lib/mpi/ec.c:915",
      "file": "lib/mpi/ec.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:add_points_weierstrass"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586601376,
      "name": "mpi_ec_dup_point",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 18446744071594198038,
      "name": "mpi_ec_dup_point.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
void mpi_ec_dup_point(MPI_POINT result, MPI_POINT point, struct mpi_ec_ctx * ctx)
```

```json
{
  "name": "mpi_ec_dup_point",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587842944,
      "name": "mpi_ec_dup_point",
      "external": false,
      "loc": "lib/mpi/ec.c:915",
      "file": "lib/mpi/ec.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:add_points_weierstrass"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587842944,
      "name": "mpi_ec_dup_point",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
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
void mpi_ec_dup_point(MPI_POINT result, MPI_POINT point, struct mpi_ec_ctx * ctx)
```

```json
{
  "name": "mpi_ec_dup_point",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588114496,
      "name": "mpi_ec_dup_point",
      "external": false,
      "loc": "lib/mpi/ec.c:915",
      "file": "lib/mpi/ec.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:add_points_weierstrass"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588114496,
      "name": "mpi_ec_dup_point",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
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
void mpi_ec_dup_point(MPI_POINT result, MPI_POINT point, struct mpi_ec_ctx * ctx)
```

```json
{
  "name": "mpi_ec_dup_point",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587683232,
      "name": "mpi_ec_dup_point",
      "external": false,
      "loc": "lib/crypto/mpi/ec.c:918",
      "file": "lib/crypto/mpi/ec.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/crypto/mpi/ec.c:mpi_ec_mul_point",
        "lib/crypto/mpi/ec.c:mpi_ec_mul_point",
        "lib/crypto/mpi/ec.c:add_points_weierstrass"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587683232,
      "name": "mpi_ec_dup_point",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 103
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
void mpi_ec_dup_point(MPI_POINT result, MPI_POINT point, struct mpi_ec_ctx * ctx)
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
