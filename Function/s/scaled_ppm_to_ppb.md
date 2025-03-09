# Function: <code>scaled_ppm_to_ppb</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "scaled_ppm_to_ppb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587097799,
      "name": "scaled_ppm_to_ppb",
      "external": false,
      "loc": "drivers/ptp/ptp_clock.c:79",
      "file": "drivers/ptp/ptp_clock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ptp/ptp_clock.c:ptp_clock_adjtime"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "scaled_ppm_to_ppb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587275015,
      "name": "scaled_ppm_to_ppb",
      "external": false,
      "loc": "drivers/ptp/ptp_clock.c:79",
      "file": "drivers/ptp/ptp_clock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ptp/ptp_clock.c:ptp_clock_adjtime"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
s32 scaled_ppm_to_ppb(long int ppm)
```

```json
{
  "name": "scaled_ppm_to_ppb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587544718,
      "name": "scaled_ppm_to_ppb",
      "external": true,
      "loc": "drivers/ptp/ptp_clock.c:66",
      "file": "drivers/ptp/ptp_clock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ptp/ptp_clock.c:ptp_clock_adjtime"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587544288,
      "name": "scaled_ppm_to_ppb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
s32 scaled_ppm_to_ppb(long int ppm)
```

```json
{
  "name": "scaled_ppm_to_ppb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587747518,
      "name": "scaled_ppm_to_ppb",
      "external": true,
      "loc": "drivers/ptp/ptp_clock.c:66",
      "file": "drivers/ptp/ptp_clock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ptp/ptp_clock.c:ptp_clock_adjtime"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587747056,
      "name": "scaled_ppm_to_ppb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
s32 scaled_ppm_to_ppb(long int ppm)
```

```json
{
  "name": "scaled_ppm_to_ppb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588592363,
      "name": "scaled_ppm_to_ppb",
      "external": true,
      "loc": "drivers/ptp/ptp_clock.c:66",
      "file": "drivers/ptp/ptp_clock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ptp/ptp_clock.c:ptp_clock_adjtime"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588591808,
      "name": "scaled_ppm_to_ppb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
s32 scaled_ppm_to_ppb(long int ppm)
```

```json
{
  "name": "scaled_ppm_to_ppb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588615419,
      "name": "scaled_ppm_to_ppb",
      "external": true,
      "loc": "drivers/ptp/ptp_clock.c:66",
      "file": "drivers/ptp/ptp_clock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ptp/ptp_clock.c:ptp_clock_adjtime"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588614864,
      "name": "scaled_ppm_to_ppb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
long int scaled_ppm_to_ppb(long int ppm)
```

```json
{
  "name": "scaled_ppm_to_ppb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588500347,
      "name": "scaled_ppm_to_ppb",
      "external": true,
      "loc": "drivers/ptp/ptp_clock.c:66",
      "file": "drivers/ptp/ptp_clock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ptp/ptp_clock.c:ptp_clock_adjtime"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588499792,
      "name": "scaled_ppm_to_ppb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "scaled_ppm_to_ppb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589169684,
      "name": "scaled_ppm_to_ppb",
      "external": false,
      "loc": "include/linux/ptp_clock_kernel.h:197",
      "file": "drivers/ptp/ptp_clock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ptp/ptp_clock.c:ptp_clock_adjtime"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "scaled_ppm_to_ppb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590624976,
      "name": "scaled_ppm_to_ppb",
      "external": false,
      "loc": "include/linux/ptp_clock_kernel.h:228",
      "file": "drivers/ptp/ptp_clock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ptp/ptp_clock.c:ptp_clock_adjtime"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "scaled_ppm_to_ppb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592287780,
      "name": "scaled_ppm_to_ppb",
      "external": false,
      "loc": "include/linux/ptp_clock_kernel.h:223",
      "file": "drivers/ptp/ptp_clock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ptp/ptp_clock.c:ptp_clock_adjtime"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "scaled_ppm_to_ppb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592712300,
      "name": "scaled_ppm_to_ppb",
      "external": false,
      "loc": "include/linux/ptp_clock_kernel.h:230",
      "file": "drivers/ptp/ptp_clock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ptp/ptp_clock.c:ptp_clock_adjtime"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "scaled_ppm_to_ppb",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593458732,
      "name": "scaled_ppm_to_ppb",
      "external": false,
      "loc": "include/linux/ptp_clock_kernel.h:230",
      "file": "drivers/ptp/ptp_clock.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ptp/ptp_clock.c:ptp_clock_adjtime"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
s32 scaled_ppm_to_ppb(long int ppm)
```

```json
{
  "name": "scaled_ppm_to_ppb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336500932456,
      "name": "scaled_ppm_to_ppb",
      "external": true,
      "loc": "drivers/ptp/ptp_clock.c:66",
      "file": "drivers/ptp/ptp_clock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ptp/ptp_clock.c:ptp_clock_adjtime"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500931856,
      "name": "scaled_ppm_to_ppb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
s32 scaled_ppm_to_ppb(long int ppm)
```

```json
{
  "name": "scaled_ppm_to_ppb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3233442268,
      "name": "scaled_ppm_to_ppb",
      "external": true,
      "loc": "drivers/ptp/ptp_clock.c:66",
      "file": "drivers/ptp/ptp_clock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ptp/ptp_clock.c:ptp_clock_adjtime"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3233441760,
      "name": "scaled_ppm_to_ppb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
s32 scaled_ppm_to_ppb(long int ppm)
```

```json
{
  "name": "scaled_ppm_to_ppb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055294387868,
      "name": "scaled_ppm_to_ppb",
      "external": true,
      "loc": "drivers/ptp/ptp_clock.c:66",
      "file": "drivers/ptp/ptp_clock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ptp/ptp_clock.c:ptp_clock_adjtime"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294387136,
      "name": "scaled_ppm_to_ppb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
s32 scaled_ppm_to_ppb(long int ppm)
```

```json
{
  "name": "scaled_ppm_to_ppb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936277699008,
      "name": "scaled_ppm_to_ppb",
      "external": true,
      "loc": "drivers/ptp/ptp_clock.c:66",
      "file": "drivers/ptp/ptp_clock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ptp/ptp_clock.c:ptp_clock_adjtime"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277698484,
      "name": "scaled_ppm_to_ppb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
s32 scaled_ppm_to_ppb(long int ppm)
```

```json
{
  "name": "scaled_ppm_to_ppb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587388462,
      "name": "scaled_ppm_to_ppb",
      "external": true,
      "loc": "drivers/ptp/ptp_clock.c:66",
      "file": "drivers/ptp/ptp_clock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ptp/ptp_clock.c:ptp_clock_adjtime"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587388000,
      "name": "scaled_ppm_to_ppb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
s32 scaled_ppm_to_ppb(long int ppm)
```

```json
{
  "name": "scaled_ppm_to_ppb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587156670,
      "name": "scaled_ppm_to_ppb",
      "external": true,
      "loc": "drivers/ptp/ptp_clock.c:66",
      "file": "drivers/ptp/ptp_clock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ptp/ptp_clock.c:ptp_clock_adjtime"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587156208,
      "name": "scaled_ppm_to_ppb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
s32 scaled_ppm_to_ppb(long int ppm)
```

```json
{
  "name": "scaled_ppm_to_ppb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587703662,
      "name": "scaled_ppm_to_ppb",
      "external": true,
      "loc": "drivers/ptp/ptp_clock.c:66",
      "file": "drivers/ptp/ptp_clock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ptp/ptp_clock.c:ptp_clock_adjtime"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587703200,
      "name": "scaled_ppm_to_ppb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
s32 scaled_ppm_to_ppb(long int ppm)
```

```json
{
  "name": "scaled_ppm_to_ppb",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587816734,
      "name": "scaled_ppm_to_ppb",
      "external": true,
      "loc": "drivers/ptp/ptp_clock.c:66",
      "file": "drivers/ptp/ptp_clock.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ptp/ptp_clock.c:ptp_clock_adjtime"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587816272,
      "name": "scaled_ppm_to_ppb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
    }
  ]
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
s32 scaled_ppm_to_ppb(long int ppm)
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>s32</code> ➡️ <code>long int</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
long int scaled_ppm_to_ppb(long int ppm)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
