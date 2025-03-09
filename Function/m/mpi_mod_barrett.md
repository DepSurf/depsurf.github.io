# Function: <code>mpi_mod_barrett</code>

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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void mpi_mod_barrett(MPI r, MPI x, mpi_barrett_t ctx)
```

```json
{
  "name": "mpi_mod_barrett",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585153024,
      "name": "mpi_mod_barrett",
      "external": true,
      "loc": "lib/mpi/mpi-mod.c:93",
      "file": "lib/mpi/mpi-mod.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/mpi/ec.c:mpi_ec_curve_point",
        "lib/mpi/ec.c:mpi_ec_curve_point",
        "lib/mpi/ec.c:mpi_ec_curve_point",
        "lib/mpi/ec.c:mpi_ec_curve_point",
        "lib/mpi/ec.c:mpi_ec_curve_point",
        "lib/mpi/ec.c:mpi_ec_curve_point",
        "lib/mpi/ec.c:mpi_ec_curve_point",
        "lib/mpi/ec.c:mpi_ec_curve_point",
        "lib/mpi/ec.c:mpi_ec_curve_point",
        "lib/mpi/ec.c:mpi_ec_curve_point",
        "lib/mpi/ec.c:mpi_ec_curve_point",
        "lib/mpi/ec.c:mpi_ec_curve_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:mpi_ec_get_affine",
        "lib/mpi/ec.c:mpi_ec_get_affine",
        "lib/mpi/ec.c:mpi_ec_get_affine",
        "lib/mpi/ec.c:mpi_ec_get_affine",
        "lib/mpi/mpi-mod.c:mpi_mul_barrett"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585153024,
      "name": "mpi_mod_barrett",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 397
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void mpi_mod_barrett(MPI r, MPI x, mpi_barrett_t ctx)
```

```json
{
  "name": "mpi_mod_barrett",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585033600,
      "name": "mpi_mod_barrett",
      "external": true,
      "loc": "lib/mpi/mpi-mod.c:93",
      "file": "lib/mpi/mpi-mod.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/mpi/ec.c:mpi_ec_curve_point",
        "lib/mpi/ec.c:mpi_ec_curve_point",
        "lib/mpi/ec.c:mpi_ec_curve_point",
        "lib/mpi/ec.c:mpi_ec_curve_point",
        "lib/mpi/ec.c:mpi_ec_curve_point",
        "lib/mpi/ec.c:mpi_ec_curve_point",
        "lib/mpi/ec.c:mpi_ec_curve_point",
        "lib/mpi/ec.c:mpi_ec_curve_point",
        "lib/mpi/ec.c:mpi_ec_curve_point",
        "lib/mpi/ec.c:mpi_ec_curve_point",
        "lib/mpi/ec.c:mpi_ec_curve_point",
        "lib/mpi/ec.c:mpi_ec_curve_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:mpi_ec_get_affine",
        "lib/mpi/ec.c:mpi_ec_get_affine",
        "lib/mpi/ec.c:mpi_ec_get_affine",
        "lib/mpi/ec.c:mpi_ec_get_affine",
        "lib/mpi/mpi-mod.c:mpi_mul_barrett"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585033600,
      "name": "mpi_mod_barrett",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 397
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void mpi_mod_barrett(MPI r, MPI x, mpi_barrett_t ctx)
```

```json
{
  "name": "mpi_mod_barrett",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585476560,
      "name": "mpi_mod_barrett",
      "external": true,
      "loc": "lib/mpi/mpi-mod.c:95",
      "file": "lib/mpi/mpi-mod.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/mpi/ec.c:mpi_ec_curve_point",
        "lib/mpi/ec.c:mpi_ec_curve_point",
        "lib/mpi/ec.c:mpi_ec_curve_point",
        "lib/mpi/ec.c:mpi_ec_curve_point",
        "lib/mpi/ec.c:mpi_ec_curve_point",
        "lib/mpi/ec.c:mpi_ec_curve_point",
        "lib/mpi/ec.c:mpi_ec_curve_point",
        "lib/mpi/ec.c:mpi_ec_curve_point",
        "lib/mpi/ec.c:mpi_ec_curve_point",
        "lib/mpi/ec.c:mpi_ec_curve_point",
        "lib/mpi/ec.c:mpi_ec_curve_point",
        "lib/mpi/ec.c:mpi_ec_curve_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:mpi_ec_get_affine",
        "lib/mpi/ec.c:mpi_ec_get_affine",
        "lib/mpi/ec.c:mpi_ec_get_affine",
        "lib/mpi/ec.c:mpi_ec_get_affine",
        "lib/mpi/mpi-mod.c:mpi_mul_barrett"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585476560,
      "name": "mpi_mod_barrett",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 397
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void mpi_mod_barrett(MPI r, MPI x, mpi_barrett_t ctx)
```

```json
{
  "name": "mpi_mod_barrett",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586620368,
      "name": "mpi_mod_barrett",
      "external": true,
      "loc": "lib/mpi/mpi-mod.c:95",
      "file": "lib/mpi/mpi-mod.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/mpi/ec.c:mpi_ec_curve_point",
        "lib/mpi/ec.c:mpi_ec_curve_point",
        "lib/mpi/ec.c:mpi_ec_curve_point",
        "lib/mpi/ec.c:mpi_ec_curve_point",
        "lib/mpi/ec.c:mpi_ec_curve_point",
        "lib/mpi/ec.c:mpi_ec_curve_point",
        "lib/mpi/ec.c:mpi_ec_curve_point",
        "lib/mpi/ec.c:mpi_ec_curve_point",
        "lib/mpi/ec.c:mpi_ec_curve_point",
        "lib/mpi/ec.c:mpi_ec_curve_point",
        "lib/mpi/ec.c:mpi_ec_curve_point",
        "lib/mpi/ec.c:mpi_ec_curve_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:mpi_ec_get_affine",
        "lib/mpi/ec.c:mpi_ec_get_affine",
        "lib/mpi/ec.c:mpi_ec_get_affine",
        "lib/mpi/ec.c:mpi_ec_get_affine",
        "lib/mpi/mpi-mod.c:mpi_mul_barrett"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586620368,
      "name": "mpi_mod_barrett",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 429
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
void mpi_mod_barrett(MPI r, MPI x, mpi_barrett_t ctx)
```

```json
{
  "name": "mpi_mod_barrett",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587862960,
      "name": "mpi_mod_barrett",
      "external": true,
      "loc": "lib/mpi/mpi-mod.c:95",
      "file": "lib/mpi/mpi-mod.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/mpi/ec.c:mpi_ec_curve_point",
        "lib/mpi/ec.c:mpi_ec_curve_point",
        "lib/mpi/ec.c:mpi_ec_curve_point",
        "lib/mpi/ec.c:mpi_ec_curve_point",
        "lib/mpi/ec.c:mpi_ec_curve_point",
        "lib/mpi/ec.c:mpi_ec_curve_point",
        "lib/mpi/ec.c:mpi_ec_curve_point",
        "lib/mpi/ec.c:mpi_ec_curve_point",
        "lib/mpi/ec.c:mpi_ec_curve_point",
        "lib/mpi/ec.c:mpi_ec_curve_point",
        "lib/mpi/ec.c:mpi_ec_curve_point",
        "lib/mpi/ec.c:mpi_ec_curve_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:mpi_ec_get_affine",
        "lib/mpi/ec.c:mpi_ec_get_affine",
        "lib/mpi/ec.c:mpi_ec_get_affine",
        "lib/mpi/ec.c:mpi_ec_get_affine",
        "lib/mpi/mpi-mod.c:mpi_mul_barrett"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587862960,
      "name": "mpi_mod_barrett",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 429
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
void mpi_mod_barrett(MPI r, MPI x, mpi_barrett_t ctx)
```

```json
{
  "name": "mpi_mod_barrett",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588134704,
      "name": "mpi_mod_barrett",
      "external": true,
      "loc": "lib/mpi/mpi-mod.c:95",
      "file": "lib/mpi/mpi-mod.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/mpi/ec.c:mpi_ec_curve_point",
        "lib/mpi/ec.c:mpi_ec_curve_point",
        "lib/mpi/ec.c:mpi_ec_curve_point",
        "lib/mpi/ec.c:mpi_ec_curve_point",
        "lib/mpi/ec.c:mpi_ec_curve_point",
        "lib/mpi/ec.c:mpi_ec_curve_point",
        "lib/mpi/ec.c:mpi_ec_curve_point",
        "lib/mpi/ec.c:mpi_ec_curve_point",
        "lib/mpi/ec.c:mpi_ec_curve_point",
        "lib/mpi/ec.c:mpi_ec_curve_point",
        "lib/mpi/ec.c:mpi_ec_curve_point",
        "lib/mpi/ec.c:mpi_ec_curve_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:mpi_ec_mul_point",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:add_points_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:dup_point_weierstrass",
        "lib/mpi/ec.c:mpi_ec_get_affine",
        "lib/mpi/ec.c:mpi_ec_get_affine",
        "lib/mpi/ec.c:mpi_ec_get_affine",
        "lib/mpi/ec.c:mpi_ec_get_affine",
        "lib/mpi/mpi-mod.c:mpi_mul_barrett"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588134704,
      "name": "mpi_mod_barrett",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 429
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
void mpi_mod_barrett(MPI r, MPI x, mpi_barrett_t ctx)
```

```json
{
  "name": "mpi_mod_barrett",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587703584,
      "name": "mpi_mod_barrett",
      "external": true,
      "loc": "lib/crypto/mpi/mpi-mod.c:95",
      "file": "lib/crypto/mpi/mpi-mod.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/crypto/mpi/ec.c:mpi_ec_curve_point",
        "lib/crypto/mpi/ec.c:mpi_ec_curve_point",
        "lib/crypto/mpi/ec.c:mpi_ec_curve_point",
        "lib/crypto/mpi/ec.c:mpi_ec_curve_point",
        "lib/crypto/mpi/ec.c:mpi_ec_curve_point",
        "lib/crypto/mpi/ec.c:mpi_ec_curve_point",
        "lib/crypto/mpi/ec.c:mpi_ec_curve_point",
        "lib/crypto/mpi/ec.c:mpi_ec_curve_point",
        "lib/crypto/mpi/ec.c:mpi_ec_curve_point",
        "lib/crypto/mpi/ec.c:mpi_ec_curve_point",
        "lib/crypto/mpi/ec.c:mpi_ec_curve_point",
        "lib/crypto/mpi/ec.c:mpi_ec_curve_point",
        "lib/crypto/mpi/ec.c:mpi_ec_mul_point",
        "lib/crypto/mpi/ec.c:mpi_ec_mul_point",
        "lib/crypto/mpi/ec.c:mpi_ec_mul_point",
        "lib/crypto/mpi/ec.c:mpi_ec_mul_point",
        "lib/crypto/mpi/ec.c:mpi_ec_mul_point",
        "lib/crypto/mpi/ec.c:add_points_weierstrass",
        "lib/crypto/mpi/ec.c:add_points_weierstrass",
        "lib/crypto/mpi/ec.c:add_points_weierstrass",
        "lib/crypto/mpi/ec.c:add_points_weierstrass",
        "lib/crypto/mpi/ec.c:add_points_weierstrass",
        "lib/crypto/mpi/ec.c:add_points_weierstrass",
        "lib/crypto/mpi/ec.c:add_points_weierstrass",
        "lib/crypto/mpi/ec.c:add_points_weierstrass",
        "lib/crypto/mpi/ec.c:add_points_weierstrass",
        "lib/crypto/mpi/ec.c:add_points_weierstrass",
        "lib/crypto/mpi/ec.c:add_points_weierstrass",
        "lib/crypto/mpi/ec.c:add_points_weierstrass",
        "lib/crypto/mpi/ec.c:add_points_weierstrass",
        "lib/crypto/mpi/ec.c:add_points_weierstrass",
        "lib/crypto/mpi/ec.c:add_points_weierstrass",
        "lib/crypto/mpi/ec.c:add_points_weierstrass",
        "lib/crypto/mpi/ec.c:add_points_weierstrass",
        "lib/crypto/mpi/ec.c:dup_point_weierstrass",
        "lib/crypto/mpi/ec.c:dup_point_weierstrass",
        "lib/crypto/mpi/ec.c:dup_point_weierstrass",
        "lib/crypto/mpi/ec.c:dup_point_weierstrass",
        "lib/crypto/mpi/ec.c:dup_point_weierstrass",
        "lib/crypto/mpi/ec.c:dup_point_weierstrass",
        "lib/crypto/mpi/ec.c:dup_point_weierstrass",
        "lib/crypto/mpi/ec.c:dup_point_weierstrass",
        "lib/crypto/mpi/ec.c:dup_point_weierstrass",
        "lib/crypto/mpi/ec.c:dup_point_weierstrass",
        "lib/crypto/mpi/ec.c:dup_point_weierstrass",
        "lib/crypto/mpi/ec.c:dup_point_weierstrass",
        "lib/crypto/mpi/ec.c:dup_point_weierstrass",
        "lib/crypto/mpi/ec.c:dup_point_weierstrass",
        "lib/crypto/mpi/ec.c:dup_point_weierstrass",
        "lib/crypto/mpi/ec.c:dup_point_weierstrass",
        "lib/crypto/mpi/ec.c:dup_point_weierstrass",
        "lib/crypto/mpi/ec.c:mpi_ec_get_affine",
        "lib/crypto/mpi/ec.c:mpi_ec_get_affine",
        "lib/crypto/mpi/ec.c:mpi_ec_get_affine",
        "lib/crypto/mpi/ec.c:mpi_ec_get_affine",
        "lib/crypto/mpi/mpi-mod.c:mpi_mul_barrett"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587703584,
      "name": "mpi_mod_barrett",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 429
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
void mpi_mod_barrett(MPI r, MPI x, mpi_barrett_t ctx)
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
