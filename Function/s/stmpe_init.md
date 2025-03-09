# Function: <code>stmpe_init</code>

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
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Collision ❓</summary>

```c
int stmpe_init()
```

```json
{
  "name": "stmpe_init",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336511228472,
      "name": "stmpe_init",
      "external": false,
      "loc": "drivers/mfd/stmpe-i2c.c:127",
      "file": "drivers/mfd/stmpe-i2c.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336511228512,
      "name": "stmpe_init",
      "external": false,
      "loc": "drivers/mfd/stmpe-spi.c:147",
      "file": "drivers/mfd/stmpe-spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336511228472,
      "name": "stmpe_init",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446603336511228512,
      "name": "stmpe_init",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Collision ❓</summary>

```c
int stmpe_init()
```

```json
{
  "name": "stmpe_init",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3243874444,
      "name": "stmpe_init",
      "external": false,
      "loc": "drivers/mfd/stmpe-i2c.c:127",
      "file": "drivers/mfd/stmpe-i2c.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3243874484,
      "name": "stmpe_init",
      "external": false,
      "loc": "drivers/mfd/stmpe-spi.c:147",
      "file": "drivers/mfd/stmpe-spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3243874444,
      "name": "stmpe_init",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 3243874484,
      "name": "stmpe_init",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Collision ❓</summary>

```c
int stmpe_init()
```

```json
{
  "name": "stmpe_init",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055302790868,
      "name": "stmpe_init",
      "external": false,
      "loc": "drivers/mfd/stmpe-i2c.c:127",
      "file": "drivers/mfd/stmpe-i2c.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055302790932,
      "name": "stmpe_init",
      "external": false,
      "loc": "drivers/mfd/stmpe-spi.c:147",
      "file": "drivers/mfd/stmpe-spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055302790868,
      "name": "stmpe_init",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 13835058055302790932,
      "name": "stmpe_init",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Collision ❓</summary>

```c
int stmpe_init()
```

```json
{
  "name": "stmpe_init",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936270802856,
      "name": "stmpe_init",
      "external": false,
      "loc": "drivers/mfd/stmpe-i2c.c:127",
      "file": "drivers/mfd/stmpe-i2c.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936270802900,
      "name": "stmpe_init",
      "external": false,
      "loc": "drivers/mfd/stmpe-spi.c:147",
      "file": "drivers/mfd/stmpe-spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936270802856,
      "name": "stmpe_init",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 18446743936270802900,
      "name": "stmpe_init",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 44
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
int stmpe_init()
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int stmpe_init()
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
int stmpe_init()
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
int stmpe_init()
```
</details>
</li>
</ul>
