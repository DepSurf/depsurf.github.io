# Function: <code>ec_mulm_448</code>

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
void ec_mulm_448(MPI w, MPI u, MPI v, struct mpi_ec_ctx * ctx)
```

```json
{
  "name": "ec_mulm_448",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ec_mulm_448",
      "external": false,
      "loc": "lib/mpi/ec.c:346",
      "file": "lib/mpi/ec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/mpi/ec.c:ec_pow2_448"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585128800,
      "name": "ec_mulm_448",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 905
    },
    {
      "addr": 18446744071591380611,
      "name": "ec_mulm_448.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
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
void ec_mulm_448(MPI w, MPI u, MPI v, struct mpi_ec_ctx * ctx)
```

```json
{
  "name": "ec_mulm_448",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ec_mulm_448",
      "external": false,
      "loc": "lib/mpi/ec.c:346",
      "file": "lib/mpi/ec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/mpi/ec.c:ec_pow2_448"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585009360,
      "name": "ec_mulm_448",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 892
    },
    {
      "addr": 18446744071591322998,
      "name": "ec_mulm_448.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
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
void ec_mulm_448(MPI w, MPI u, MPI v, struct mpi_ec_ctx * ctx)
```

```json
{
  "name": "ec_mulm_448",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ec_mulm_448",
      "external": false,
      "loc": "lib/mpi/ec.c:346",
      "file": "lib/mpi/ec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/mpi/ec.c:ec_pow2_448"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585451136,
      "name": "ec_mulm_448",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1669
    },
    {
      "addr": 18446744071592337292,
      "name": "ec_mulm_448.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
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
void ec_mulm_448(MPI w, MPI u, MPI v, struct mpi_ec_ctx * ctx)
```

```json
{
  "name": "ec_mulm_448",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ec_mulm_448",
      "external": false,
      "loc": "lib/mpi/ec.c:346",
      "file": "lib/mpi/ec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/mpi/ec.c:ec_pow2_448"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586593008,
      "name": "ec_mulm_448",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1873
    },
    {
      "addr": 18446744071594197748,
      "name": "ec_mulm_448.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
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
void ec_mulm_448(MPI w, MPI u, MPI v, struct mpi_ec_ctx * ctx)
```

```json
{
  "name": "ec_mulm_448",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587834016,
      "name": "ec_mulm_448",
      "external": false,
      "loc": "lib/mpi/ec.c:346",
      "file": "lib/mpi/ec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/mpi/ec.c:ec_pow2_448"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587834016,
      "name": "ec_mulm_448",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1902
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
void ec_mulm_448(MPI w, MPI u, MPI v, struct mpi_ec_ctx * ctx)
```

```json
{
  "name": "ec_mulm_448",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588105504,
      "name": "ec_mulm_448",
      "external": false,
      "loc": "lib/mpi/ec.c:346",
      "file": "lib/mpi/ec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/mpi/ec.c:ec_pow2_448"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588105504,
      "name": "ec_mulm_448",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1913
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
void ec_mulm_448(MPI w, MPI u, MPI v, struct mpi_ec_ctx * ctx)
```

```json
{
  "name": "ec_mulm_448",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587674176,
      "name": "ec_mulm_448",
      "external": false,
      "loc": "lib/crypto/mpi/ec.c:346",
      "file": "lib/crypto/mpi/ec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/crypto/mpi/ec.c:ec_pow2_448"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587674176,
      "name": "ec_mulm_448",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1913
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
void ec_mulm_448(MPI w, MPI u, MPI v, struct mpi_ec_ctx * ctx)
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
