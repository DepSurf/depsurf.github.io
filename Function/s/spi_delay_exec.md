# Function: <code>spi_delay_exec</code>

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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int spi_delay_exec(struct spi_delay * _delay, struct spi_transfer * xfer)
```

```json
{
  "name": "spi_delay_exec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587735216,
      "name": "spi_delay_exec",
      "external": true,
      "loc": "drivers/spi/spi.c:1172",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:spi_transfer_one_message",
        "drivers/spi/spi.c:spi_transfer_one_message",
        "drivers/spi/spi.c:spi_transfer_one_message",
        "drivers/spi/spi.c:spi_set_cs",
        "drivers/spi/spi.c:spi_set_cs",
        "drivers/spi/spi.c:spi_set_cs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587735216,
      "name": "spi_delay_exec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 241
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int spi_delay_exec(struct spi_delay * _delay, struct spi_transfer * xfer)
```

```json
{
  "name": "spi_delay_exec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587795712,
      "name": "spi_delay_exec",
      "external": true,
      "loc": "drivers/spi/spi.c:1196",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:spi_transfer_one_message",
        "drivers/spi/spi.c:spi_transfer_one_message",
        "drivers/spi/spi.c:spi_transfer_one_message",
        "drivers/spi/spi.c:spi_set_cs",
        "drivers/spi/spi.c:spi_set_cs",
        "drivers/spi/spi.c:spi_set_cs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587795712,
      "name": "spi_delay_exec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 241
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
int spi_delay_exec(struct spi_delay * _delay, struct spi_transfer * xfer)
```

```json
{
  "name": "spi_delay_exec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587674880,
      "name": "spi_delay_exec",
      "external": true,
      "loc": "drivers/spi/spi.c:1208",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:spi_transfer_one_message",
        "drivers/spi/spi.c:spi_transfer_one_message",
        "drivers/spi/spi.c:spi_set_cs",
        "drivers/spi/spi.c:spi_set_cs",
        "drivers/spi/spi.c:spi_set_cs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587674880,
      "name": "spi_delay_exec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 241
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
int spi_delay_exec(struct spi_delay * _delay, struct spi_transfer * xfer)
```

```json
{
  "name": "spi_delay_exec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588264288,
      "name": "spi_delay_exec",
      "external": true,
      "loc": "drivers/spi/spi.c:1286",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:spi_transfer_one_message",
        "drivers/spi/spi.c:spi_transfer_one_message",
        "drivers/spi/spi.c:spi_set_cs",
        "drivers/spi/spi.c:spi_set_cs",
        "drivers/spi/spi.c:spi_set_cs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588264288,
      "name": "spi_delay_exec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 258
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
int spi_delay_exec(struct spi_delay * _delay, struct spi_transfer * xfer)
```

```json
{
  "name": "spi_delay_exec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589646272,
      "name": "spi_delay_exec",
      "external": true,
      "loc": "drivers/spi/spi.c:1329",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:spi_transfer_one_message",
        "drivers/spi/spi.c:spi_transfer_one_message",
        "drivers/spi/spi.c:spi_set_cs",
        "drivers/spi/spi.c:spi_set_cs",
        "drivers/spi/spi.c:spi_set_cs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589646272,
      "name": "spi_delay_exec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
int spi_delay_exec(struct spi_delay * _delay, struct spi_transfer * xfer)
```

```json
{
  "name": "spi_delay_exec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591254368,
      "name": "spi_delay_exec",
      "external": true,
      "loc": "drivers/spi/spi.c:1444",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:spi_transfer_one_message",
        "drivers/spi/spi.c:spi_transfer_one_message",
        "drivers/spi/spi.c:spi_set_cs",
        "drivers/spi/spi.c:spi_set_cs",
        "drivers/spi/spi.c:spi_set_cs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591254368,
      "name": "spi_delay_exec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
int spi_delay_exec(struct spi_delay * _delay, struct spi_transfer * xfer)
```

```json
{
  "name": "spi_delay_exec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591610000,
      "name": "spi_delay_exec",
      "external": true,
      "loc": "drivers/spi/spi.c:1444",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:spi_transfer_one_message",
        "drivers/spi/spi.c:spi_transfer_cs_change_delay_exec",
        "drivers/spi/spi.c:spi_set_cs",
        "drivers/spi/spi.c:spi_set_cs",
        "drivers/spi/spi.c:spi_set_cs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591610000,
      "name": "spi_delay_exec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
int spi_delay_exec(struct spi_delay * _delay, struct spi_transfer * xfer)
```

```json
{
  "name": "spi_delay_exec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592341424,
      "name": "spi_delay_exec",
      "external": true,
      "loc": "drivers/spi/spi.c:1517",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:spi_transfer_one_message",
        "drivers/spi/spi.c:spi_transfer_cs_change_delay_exec",
        "drivers/spi/spi.c:spi_set_cs",
        "drivers/spi/spi.c:spi_set_cs",
        "drivers/spi/spi.c:spi_set_cs",
        "drivers/spi/spi.c:spi_set_cs",
        "drivers/spi/spi.c:spi_set_cs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592341424,
      "name": "spi_delay_exec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int spi_delay_exec(struct spi_delay * _delay, struct spi_transfer * xfer)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
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
