# Function: <code>__spi_pump_transfer_message</code>

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
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int __spi_pump_transfer_message(struct spi_controller * ctlr, struct spi_message * msg, bool was_busy)
```

```json
{
  "name": "__spi_pump_transfer_message",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__spi_pump_transfer_message",
      "external": false,
      "loc": "drivers/spi/spi.c:1628",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:__spi_sync",
        "drivers/spi/spi.c:__spi_pump_messages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591258240,
      "name": "__spi_pump_transfer_message",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 856
    },
    {
      "addr": 18446744071596266093,
      "name": "__spi_pump_transfer_message.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
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
int __spi_pump_transfer_message(struct spi_controller * ctlr, struct spi_message * msg, bool was_busy)
```

```json
{
  "name": "__spi_pump_transfer_message",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__spi_pump_transfer_message",
      "external": false,
      "loc": "drivers/spi/spi.c:1635",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:__spi_sync",
        "drivers/spi/spi.c:__spi_pump_messages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591613104,
      "name": "__spi_pump_transfer_message",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 856
    },
    {
      "addr": 18446744071596794154,
      "name": "__spi_pump_transfer_message.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
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
int __spi_pump_transfer_message(struct spi_controller * ctlr, struct spi_message * msg, bool was_busy)
```

```json
{
  "name": "__spi_pump_transfer_message",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__spi_pump_transfer_message",
      "external": false,
      "loc": "drivers/spi/spi.c:1708",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:__spi_sync",
        "drivers/spi/spi.c:__spi_pump_messages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592344752,
      "name": "__spi_pump_transfer_message",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 848
    },
    {
      "addr": 18446744071597717159,
      "name": "__spi_pump_transfer_message.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
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
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
int __spi_pump_transfer_message(struct spi_controller * ctlr, struct spi_message * msg, bool was_busy)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
