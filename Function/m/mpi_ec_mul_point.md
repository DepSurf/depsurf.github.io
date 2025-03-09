# Function: <code>mpi_ec_mul_point</code>

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
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
void mpi_ec_mul_point(MPI_POINT result, MPI scalar, MPI_POINT point, struct mpi_ec_ctx * ctx)
```

```json
{
  "name": "mpi_ec_mul_point",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mpi_ec_mul_point",
      "external": true,
      "loc": "lib/mpi/ec.c:1210",
      "file": "lib/mpi/ec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591380981,
      "name": "mpi_ec_mul_point.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 18446744071585137648,
      "name": "mpi_ec_mul_point",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2796
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
void mpi_ec_mul_point(MPI_POINT result, MPI scalar, MPI_POINT point, struct mpi_ec_ctx * ctx)
```

```json
{
  "name": "mpi_ec_mul_point",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mpi_ec_mul_point",
      "external": true,
      "loc": "lib/mpi/ec.c:1210",
      "file": "lib/mpi/ec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591323373,
      "name": "mpi_ec_mul_point.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 18446744071585018144,
      "name": "mpi_ec_mul_point",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2884
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void mpi_ec_mul_point(MPI_POINT result, MPI scalar, MPI_POINT point, struct mpi_ec_ctx * ctx)
```

```json
{
  "name": "mpi_ec_mul_point",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mpi_ec_mul_point",
      "external": true,
      "loc": "lib/mpi/ec.c:1210",
      "file": "lib/mpi/ec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592337667,
      "name": "mpi_ec_mul_point.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 18446744071585461072,
      "name": "mpi_ec_mul_point",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2884
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void mpi_ec_mul_point(MPI_POINT result, MPI scalar, MPI_POINT point, struct mpi_ec_ctx * ctx)
```

```json
{
  "name": "mpi_ec_mul_point",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mpi_ec_mul_point",
      "external": true,
      "loc": "lib/mpi/ec.c:1210",
      "file": "lib/mpi/ec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594198121,
      "name": "mpi_ec_mul_point.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 18446744071586603648,
      "name": "mpi_ec_mul_point",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 2982
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void mpi_ec_mul_point(MPI_POINT result, MPI scalar, MPI_POINT point, struct mpi_ec_ctx * ctx)
```

```json
{
  "name": "mpi_ec_mul_point",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587845392,
      "name": "mpi_ec_mul_point",
      "external": true,
      "loc": "lib/mpi/ec.c:1210",
      "file": "lib/mpi/ec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587845392,
      "name": "mpi_ec_mul_point",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3038
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void mpi_ec_mul_point(MPI_POINT result, MPI scalar, MPI_POINT point, struct mpi_ec_ctx * ctx)
```

```json
{
  "name": "mpi_ec_mul_point",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588116912,
      "name": "mpi_ec_mul_point",
      "external": true,
      "loc": "lib/mpi/ec.c:1210",
      "file": "lib/mpi/ec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588116912,
      "name": "mpi_ec_mul_point",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3038
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void mpi_ec_mul_point(MPI_POINT result, MPI scalar, MPI_POINT point, struct mpi_ec_ctx * ctx)
```

```json
{
  "name": "mpi_ec_mul_point",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587685648,
      "name": "mpi_ec_mul_point",
      "external": true,
      "loc": "lib/crypto/mpi/ec.c:1213",
      "file": "lib/crypto/mpi/ec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587685648,
      "name": "mpi_ec_mul_point",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 3038
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
void mpi_ec_mul_point(MPI_POINT result, MPI scalar, MPI_POINT point, struct mpi_ec_ctx * ctx)
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
