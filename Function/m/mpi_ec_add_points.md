# Function: <code>mpi_ec_add_points</code>

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
void mpi_ec_add_points(MPI_POINT result, MPI_POINT p1, MPI_POINT p2, struct mpi_ec_ctx * ctx)
```

```json
{
  "name": "mpi_ec_add_points",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591380950,
      "name": "mpi_ec_add_points",
      "external": true,
      "loc": "lib/mpi/ec.c:1188",
      "file": "lib/mpi/ec.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591380950,
      "name": "mpi_ec_add_points.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071585137600,
      "name": "mpi_ec_add_points",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void mpi_ec_add_points(MPI_POINT result, MPI_POINT p1, MPI_POINT p2, struct mpi_ec_ctx * ctx)
```

```json
{
  "name": "mpi_ec_add_points",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591323342,
      "name": "mpi_ec_add_points",
      "external": true,
      "loc": "lib/mpi/ec.c:1188",
      "file": "lib/mpi/ec.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591323342,
      "name": "mpi_ec_add_points.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071585018096,
      "name": "mpi_ec_add_points",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void mpi_ec_add_points(MPI_POINT result, MPI_POINT p1, MPI_POINT p2, struct mpi_ec_ctx * ctx)
```

```json
{
  "name": "mpi_ec_add_points",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592337636,
      "name": "mpi_ec_add_points",
      "external": true,
      "loc": "lib/mpi/ec.c:1188",
      "file": "lib/mpi/ec.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592337636,
      "name": "mpi_ec_add_points.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071585461024,
      "name": "mpi_ec_add_points",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void mpi_ec_add_points(MPI_POINT result, MPI_POINT p1, MPI_POINT p2, struct mpi_ec_ctx * ctx)
```

```json
{
  "name": "mpi_ec_add_points",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594198090,
      "name": "mpi_ec_add_points",
      "external": true,
      "loc": "lib/mpi/ec.c:1188",
      "file": "lib/mpi/ec.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594198090,
      "name": "mpi_ec_add_points.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071586603568,
      "name": "mpi_ec_add_points",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void mpi_ec_add_points(MPI_POINT result, MPI_POINT p1, MPI_POINT p2, struct mpi_ec_ctx * ctx)
```

```json
{
  "name": "mpi_ec_add_points",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587845248,
      "name": "mpi_ec_add_points",
      "external": true,
      "loc": "lib/mpi/ec.c:1188",
      "file": "lib/mpi/ec.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587845248,
      "name": "mpi_ec_add_points",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
void mpi_ec_add_points(MPI_POINT result, MPI_POINT p1, MPI_POINT p2, struct mpi_ec_ctx * ctx)
```

```json
{
  "name": "mpi_ec_add_points",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588116784,
      "name": "mpi_ec_add_points",
      "external": true,
      "loc": "lib/mpi/ec.c:1188",
      "file": "lib/mpi/ec.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588116784,
      "name": "mpi_ec_add_points",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
void mpi_ec_add_points(MPI_POINT result, MPI_POINT p1, MPI_POINT p2, struct mpi_ec_ctx * ctx)
```

```json
{
  "name": "mpi_ec_add_points",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587685520,
      "name": "mpi_ec_add_points",
      "external": true,
      "loc": "lib/crypto/mpi/ec.c:1191",
      "file": "lib/crypto/mpi/ec.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/crypto/mpi/ec.c:mpi_ec_mul_point",
        "lib/crypto/mpi/ec.c:mpi_ec_mul_point",
        "lib/crypto/mpi/ec.c:mpi_ec_mul_point"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587685520,
      "name": "mpi_ec_add_points",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 109
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
void mpi_ec_add_points(MPI_POINT result, MPI_POINT p1, MPI_POINT p2, struct mpi_ec_ctx * ctx)
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
