# Function: <code>spi_set_cs_timing</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void spi_set_cs_timing(struct spi_device * spi, u8 setup, u8 hold, u8 inactive_dly)
```

```json
{
  "name": "spi_set_cs_timing",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586761104,
      "name": "spi_set_cs_timing",
      "external": true,
      "loc": "drivers/spi/spi.c:3118",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586761104,
      "name": "spi_set_cs_timing",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void spi_set_cs_timing(struct spi_device * spi, u8 setup, u8 hold, u8 inactive_dly)
```

```json
{
  "name": "spi_set_cs_timing",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586907552,
      "name": "spi_set_cs_timing",
      "external": true,
      "loc": "drivers/spi/spi.c:3122",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586907552,
      "name": "spi_set_cs_timing",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int spi_set_cs_timing(struct spi_device * spi, struct spi_delay * setup, struct spi_delay * hold, struct spi_delay * inactive)
```

```json
{
  "name": "spi_set_cs_timing",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "spi_set_cs_timing",
      "external": true,
      "loc": "drivers/spi/spi.c:3353",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587745952,
      "name": "spi_set_cs_timing.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071587725024,
      "name": "spi_set_cs_timing",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 197
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int spi_set_cs_timing(struct spi_device * spi, struct spi_delay * setup, struct spi_delay * hold, struct spi_delay * inactive)
```

```json
{
  "name": "spi_set_cs_timing",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "spi_set_cs_timing",
      "external": true,
      "loc": "drivers/spi/spi.c:3449",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591529219,
      "name": "spi_set_cs_timing.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071587784688,
      "name": "spi_set_cs_timing",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 197
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
int spi_set_cs_timing(struct spi_device * spi, struct spi_delay * setup, struct spi_delay * hold, struct spi_delay * inactive)
```

```json
{
  "name": "spi_set_cs_timing",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "spi_set_cs_timing",
      "external": true,
      "loc": "drivers/spi/spi.c:3467",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591471351,
      "name": "spi_set_cs_timing.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071587663936,
      "name": "spi_set_cs_timing",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 488
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "spi_set_cs_timing",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591261975,
      "name": "spi_set_cs_timing",
      "external": false,
      "loc": "drivers/spi/spi.c:3643",
      "file": "drivers/spi/spi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:spi_setup"
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
  "name": "spi_set_cs_timing",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591616867,
      "name": "spi_set_cs_timing",
      "external": false,
      "loc": "drivers/spi/spi.c:3698",
      "file": "drivers/spi/spi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:spi_setup"
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
  "name": "spi_set_cs_timing",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592348595,
      "name": "spi_set_cs_timing",
      "external": false,
      "loc": "drivers/spi/spi.c:3864",
      "file": "drivers/spi/spi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:spi_setup"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void spi_set_cs_timing(struct spi_device * spi, u8 setup, u8 hold, u8 inactive_dly)
```

```json
{
  "name": "spi_set_cs_timing",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499862272,
      "name": "spi_set_cs_timing",
      "external": true,
      "loc": "drivers/spi/spi.c:3122",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499862272,
      "name": "spi_set_cs_timing",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void spi_set_cs_timing(struct spi_device * spi, u8 setup, u8 hold, u8 inactive_dly)
```

```json
{
  "name": "spi_set_cs_timing",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232420848,
      "name": "spi_set_cs_timing",
      "external": true,
      "loc": "drivers/spi/spi.c:3122",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3232420848,
      "name": "spi_set_cs_timing",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void spi_set_cs_timing(struct spi_device * spi, u8 setup, u8 hold, u8 inactive_dly)
```

```json
{
  "name": "spi_set_cs_timing",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055293185344,
      "name": "spi_set_cs_timing",
      "external": true,
      "loc": "drivers/spi/spi.c:3122",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293185344,
      "name": "spi_set_cs_timing",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void spi_set_cs_timing(struct spi_device * spi, u8 setup, u8 hold, u8 inactive_dly)
```

```json
{
  "name": "spi_set_cs_timing",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276971714,
      "name": "spi_set_cs_timing",
      "external": true,
      "loc": "drivers/spi/spi.c:3122",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276971714,
      "name": "spi_set_cs_timing",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void spi_set_cs_timing(struct spi_device * spi, u8 setup, u8 hold, u8 inactive_dly)
```

```json
{
  "name": "spi_set_cs_timing",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586664576,
      "name": "spi_set_cs_timing",
      "external": true,
      "loc": "drivers/spi/spi.c:3122",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586664576,
      "name": "spi_set_cs_timing",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void spi_set_cs_timing(struct spi_device * spi, u8 setup, u8 hold, u8 inactive_dly)
```

```json
{
  "name": "spi_set_cs_timing",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586532912,
      "name": "spi_set_cs_timing",
      "external": true,
      "loc": "drivers/spi/spi.c:3122",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586532912,
      "name": "spi_set_cs_timing",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void spi_set_cs_timing(struct spi_device * spi, u8 setup, u8 hold, u8 inactive_dly)
```

```json
{
  "name": "spi_set_cs_timing",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586862112,
      "name": "spi_set_cs_timing",
      "external": true,
      "loc": "drivers/spi/spi.c:3122",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586862112,
      "name": "spi_set_cs_timing",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void spi_set_cs_timing(struct spi_device * spi, u8 setup, u8 hold, u8 inactive_dly)
```

```json
{
  "name": "spi_set_cs_timing",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586968224,
      "name": "spi_set_cs_timing",
      "external": true,
      "loc": "drivers/spi/spi.c:3122",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586968224,
      "name": "spi_set_cs_timing",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
void spi_set_cs_timing(struct spi_device * spi, u8 setup, u8 hold, u8 inactive_dly)
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct spi_delay * inactive</code>
</li>
<li>
<b>Param removed. </b>
<code>u8 inactive_dly</code>
</li>
<li>
<b>Param type changed. </b>
<code>u8 setup</code> ➡️ <code>struct spi_delay * setup</code>
</li>
<li>
<b>Param type changed. </b>
<code>u8 hold</code> ➡️ <code>struct spi_delay * hold</code>
</li>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
int spi_set_cs_timing(struct spi_device * spi, struct spi_delay * setup, struct spi_delay * hold, struct spi_delay * inactive)
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
