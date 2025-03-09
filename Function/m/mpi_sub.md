# Function: <code>mpi_sub</code>

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
void mpi_sub(MPI w, MPI u, MPI v)
```

```json
{
  "name": "mpi_sub",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585146667,
      "name": "mpi_sub",
      "external": true,
      "loc": "lib/mpi/mpi-add.c:134",
      "file": "lib/mpi/mpi-add.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/mpi/mpi-add.c:mpi_subm"
      ],
      "caller_func": [
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
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/mpi-mod.c:mpi_mod_barrett",
        "lib/mpi/mpi-mod.c:mpi_mod_barrett"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585147168,
      "name": "mpi_sub",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void mpi_sub(MPI w, MPI u, MPI v)
```

```json
{
  "name": "mpi_sub",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585027259,
      "name": "mpi_sub",
      "external": true,
      "loc": "lib/mpi/mpi-add.c:134",
      "file": "lib/mpi/mpi-add.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/mpi/mpi-add.c:mpi_subm"
      ],
      "caller_func": [
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
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/mpi-mod.c:mpi_mod_barrett",
        "lib/mpi/mpi-mod.c:mpi_mod_barrett"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585027760,
      "name": "mpi_sub",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void mpi_sub(MPI w, MPI u, MPI v)
```

```json
{
  "name": "mpi_sub",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585470187,
      "name": "mpi_sub",
      "external": true,
      "loc": "lib/mpi/mpi-add.c:134",
      "file": "lib/mpi/mpi-add.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/mpi/mpi-add.c:mpi_subm"
      ],
      "caller_func": [
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
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/mpi-mod.c:mpi_mod_barrett",
        "lib/mpi/mpi-mod.c:mpi_mod_barrett"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585470688,
      "name": "mpi_sub",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void mpi_sub(MPI w, MPI u, MPI v)
```

```json
{
  "name": "mpi_sub",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586613179,
      "name": "mpi_sub",
      "external": true,
      "loc": "lib/mpi/mpi-add.c:134",
      "file": "lib/mpi/mpi-add.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/mpi/mpi-add.c:mpi_subm"
      ],
      "caller_func": [
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
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/mpi-mod.c:mpi_mod_barrett",
        "lib/mpi/mpi-mod.c:mpi_mod_barrett"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586613680,
      "name": "mpi_sub",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
void mpi_sub(MPI w, MPI u, MPI v)
```

```json
{
  "name": "mpi_sub",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587855419,
      "name": "mpi_sub",
      "external": true,
      "loc": "lib/mpi/mpi-add.c:134",
      "file": "lib/mpi/mpi-add.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/mpi/mpi-add.c:mpi_subm"
      ],
      "caller_func": [
        "crypto/rsa.c:rsa_dec",
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
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/mpi-mod.c:mpi_mod_barrett",
        "lib/mpi/mpi-mod.c:mpi_mod_barrett"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587855200,
      "name": "mpi_sub",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
void mpi_sub(MPI w, MPI u, MPI v)
```

```json
{
  "name": "mpi_sub",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588127067,
      "name": "mpi_sub",
      "external": true,
      "loc": "lib/mpi/mpi-add.c:134",
      "file": "lib/mpi/mpi-add.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/mpi/mpi-add.c:mpi_subm"
      ],
      "caller_func": [
        "crypto/rsa.c:rsa_dec",
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
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/mpi-mod.c:mpi_mod_barrett",
        "lib/mpi/mpi-mod.c:mpi_mod_barrett"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588126848,
      "name": "mpi_sub",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
void mpi_sub(MPI w, MPI u, MPI v)
```

```json
{
  "name": "mpi_sub",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587695803,
      "name": "mpi_sub",
      "external": true,
      "loc": "lib/crypto/mpi/mpi-add.c:134",
      "file": "lib/crypto/mpi/mpi-add.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/crypto/mpi/mpi-add.c:mpi_subm"
      ],
      "caller_func": [
        "crypto/rsa.c:rsa_dec",
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
        "lib/crypto/mpi/ec.c:dup_point_weierstrass",
        "lib/crypto/mpi/mpi-mod.c:mpi_mod_barrett",
        "lib/crypto/mpi/mpi-mod.c:mpi_mod_barrett"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587695584,
      "name": "mpi_sub",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
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
void mpi_sub(MPI w, MPI u, MPI v)
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
