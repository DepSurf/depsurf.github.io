# Function: <code>mpihelp_divmod_1</code>

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
mpi_limb_t mpihelp_divmod_1(mpi_ptr_t quot_ptr, mpi_ptr_t dividend_ptr, mpi_size_t dividend_size, mpi_limb_t divisor_limb)
```

```json
{
  "name": "mpihelp_divmod_1",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585156912,
      "name": "mpihelp_divmod_1",
      "external": true,
      "loc": "lib/mpi/mpih-div.c:379",
      "file": "lib/mpi/mpih-div.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/mpi/mpi-div.c:mpi_tdiv_qr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585156912,
      "name": "mpihelp_divmod_1",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 789
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
mpi_limb_t mpihelp_divmod_1(mpi_ptr_t quot_ptr, mpi_ptr_t dividend_ptr, mpi_size_t dividend_size, mpi_limb_t divisor_limb)
```

```json
{
  "name": "mpihelp_divmod_1",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585037472,
      "name": "mpihelp_divmod_1",
      "external": true,
      "loc": "lib/mpi/mpih-div.c:379",
      "file": "lib/mpi/mpih-div.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/mpi/mpi-div.c:mpi_tdiv_qr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585037472,
      "name": "mpihelp_divmod_1",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 781
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
mpi_limb_t mpihelp_divmod_1(mpi_ptr_t quot_ptr, mpi_ptr_t dividend_ptr, mpi_size_t dividend_size, mpi_limb_t divisor_limb)
```

```json
{
  "name": "mpihelp_divmod_1",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mpihelp_divmod_1",
      "external": true,
      "loc": "lib/mpi/mpih-div.c:379",
      "file": "lib/mpi/mpih-div.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/mpi/mpi-div.c:mpi_tdiv_qr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592338329,
      "name": "mpihelp_divmod_1.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 491
    },
    {
      "addr": 18446744071585480608,
      "name": "mpihelp_divmod_1",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 941
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
mpi_limb_t mpihelp_divmod_1(mpi_ptr_t quot_ptr, mpi_ptr_t dividend_ptr, mpi_size_t dividend_size, mpi_limb_t divisor_limb)
```

```json
{
  "name": "mpihelp_divmod_1",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mpihelp_divmod_1",
      "external": true,
      "loc": "lib/mpi/mpih-div.c:379",
      "file": "lib/mpi/mpih-div.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/mpi/mpi-div.c:mpi_tdiv_qr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594198786,
      "name": "mpihelp_divmod_1.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 449
    },
    {
      "addr": 18446744071586624528,
      "name": "mpihelp_divmod_1",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 940
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
mpi_limb_t mpihelp_divmod_1(mpi_ptr_t quot_ptr, mpi_ptr_t dividend_ptr, mpi_size_t dividend_size, mpi_limb_t divisor_limb)
```

```json
{
  "name": "mpihelp_divmod_1",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mpihelp_divmod_1",
      "external": true,
      "loc": "lib/mpi/mpih-div.c:379",
      "file": "lib/mpi/mpih-div.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/mpi/mpi-div.c:mpi_tdiv_qr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596200701,
      "name": "mpihelp_divmod_1.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 449
    },
    {
      "addr": 18446744071587867232,
      "name": "mpihelp_divmod_1",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 940
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
mpi_limb_t mpihelp_divmod_1(mpi_ptr_t quot_ptr, mpi_ptr_t dividend_ptr, mpi_size_t dividend_size, mpi_limb_t divisor_limb)
```

```json
{
  "name": "mpihelp_divmod_1",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mpihelp_divmod_1",
      "external": true,
      "loc": "lib/mpi/mpih-div.c:379",
      "file": "lib/mpi/mpih-div.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/mpi/mpi-div.c:mpi_tdiv_qr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596725845,
      "name": "mpihelp_divmod_1.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 519
    },
    {
      "addr": 18446744071588138992,
      "name": "mpihelp_divmod_1",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1057
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
mpi_limb_t mpihelp_divmod_1(mpi_ptr_t quot_ptr, mpi_ptr_t dividend_ptr, mpi_size_t dividend_size, mpi_limb_t divisor_limb)
```

```json
{
  "name": "mpihelp_divmod_1",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mpihelp_divmod_1",
      "external": true,
      "loc": "lib/crypto/mpi/mpih-div.c:379",
      "file": "lib/crypto/mpi/mpih-div.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/crypto/mpi/mpi-div.c:mpi_tdiv_qr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597551731,
      "name": "mpihelp_divmod_1.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 519
    },
    {
      "addr": 18446744071587707856,
      "name": "mpihelp_divmod_1",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1052
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
mpi_limb_t mpihelp_divmod_1(mpi_ptr_t quot_ptr, mpi_ptr_t dividend_ptr, mpi_size_t dividend_size, mpi_limb_t divisor_limb)
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
