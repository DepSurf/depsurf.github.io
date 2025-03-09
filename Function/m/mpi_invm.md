# Function: <code>mpi_invm</code>

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
int mpi_invm(MPI x, MPI a, MPI n)
```

```json
{
  "name": "mpi_invm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585151376,
      "name": "mpi_invm",
      "external": true,
      "loc": "lib/mpi/mpi-inv.c:27",
      "file": "lib/mpi/mpi-inv.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:mpi_ec_get_affine",
        "lib/mpi/ec.c:mpi_ec_get_affine"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585151376,
      "name": "mpi_invm.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1209
    },
    {
      "addr": 18446744071585152592,
      "name": "mpi_invm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
int mpi_invm(MPI x, MPI a, MPI n)
```

```json
{
  "name": "mpi_invm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585031952,
      "name": "mpi_invm",
      "external": true,
      "loc": "lib/mpi/mpi-inv.c:27",
      "file": "lib/mpi/mpi-inv.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:mpi_ec_get_affine",
        "lib/mpi/ec.c:mpi_ec_get_affine"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585031952,
      "name": "mpi_invm.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1209
    },
    {
      "addr": 18446744071585033168,
      "name": "mpi_invm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
int mpi_invm(MPI x, MPI a, MPI n)
```

```json
{
  "name": "mpi_invm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585474912,
      "name": "mpi_invm",
      "external": true,
      "loc": "lib/mpi/mpi-inv.c:27",
      "file": "lib/mpi/mpi-inv.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:mpi_ec_get_affine",
        "lib/mpi/ec.c:mpi_ec_get_affine"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585474912,
      "name": "mpi_invm.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1209
    },
    {
      "addr": 18446744071585476128,
      "name": "mpi_invm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
int mpi_invm(MPI x, MPI a, MPI n)
```

```json
{
  "name": "mpi_invm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586618512,
      "name": "mpi_invm",
      "external": true,
      "loc": "lib/mpi/mpi-inv.c:27",
      "file": "lib/mpi/mpi-inv.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:mpi_ec_get_affine",
        "lib/mpi/ec.c:mpi_ec_get_affine"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586618512,
      "name": "mpi_invm.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1376
    },
    {
      "addr": 18446744071586619888,
      "name": "mpi_invm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int mpi_invm(MPI x, MPI a, MPI n)
```

```json
{
  "name": "mpi_invm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587861024,
      "name": "mpi_invm",
      "external": true,
      "loc": "lib/mpi/mpi-inv.c:27",
      "file": "lib/mpi/mpi-inv.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:mpi_ec_get_affine",
        "lib/mpi/ec.c:mpi_ec_get_affine"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587861024,
      "name": "mpi_invm.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1376
    },
    {
      "addr": 18446744071587862416,
      "name": "mpi_invm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int mpi_invm(MPI x, MPI a, MPI n)
```

```json
{
  "name": "mpi_invm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588132768,
      "name": "mpi_invm",
      "external": true,
      "loc": "lib/mpi/mpi-inv.c:27",
      "file": "lib/mpi/mpi-inv.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:mpi_ec_get_affine",
        "lib/mpi/ec.c:mpi_ec_get_affine"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588132768,
      "name": "mpi_invm.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1376
    },
    {
      "addr": 18446744071588134160,
      "name": "mpi_invm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int mpi_invm(MPI x, MPI a, MPI n)
```

```json
{
  "name": "mpi_invm",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587701600,
      "name": "mpi_invm",
      "external": true,
      "loc": "lib/crypto/mpi/mpi-inv.c:27",
      "file": "lib/crypto/mpi/mpi-inv.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/crypto/mpi/ec.c:mpi_ec_mul_point",
        "lib/crypto/mpi/ec.c:mpi_ec_mul_point",
        "lib/crypto/mpi/ec.c:mpi_ec_mul_point",
        "lib/crypto/mpi/ec.c:mpi_ec_mul_point",
        "lib/crypto/mpi/ec.c:add_points_weierstrass",
        "lib/crypto/mpi/ec.c:mpi_ec_get_affine",
        "lib/crypto/mpi/ec.c:mpi_ec_get_affine"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587701600,
      "name": "mpi_invm.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1376
    },
    {
      "addr": 18446744071587702992,
      "name": "mpi_invm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int mpi_invm(MPI x, MPI a, MPI n)
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
