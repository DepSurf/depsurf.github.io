# Function: <code>setup_port</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int setup_port(struct serial_private * priv, struct uart_8250_port * port, int bar, int offset, int regshift)
```

```json
{
  "name": "setup_port",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584130880,
      "name": "setup_port",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_pci.c:79",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_pci.c:pci_omegapci_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_timedia_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_timedia_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_timedia_setup",
        "drivers/tty/serial/8250/8250_pci.c:titan_400l_800l_setup",
        "drivers/tty/serial/8250/8250_pci.c:titan_400l_800l_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_setup",
        "drivers/tty/serial/8250/8250_pci.c:sbs_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_pericom_setup",
        "drivers/tty/serial/8250/8250_pci.c:ce4100_serial_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_default_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_hp_diva_setup",
        "drivers/tty/serial/8250/8250_pci.c:afavlab_setup",
        "drivers/tty/serial/8250/8250_pci.c:addidata_apci7800_setup",
        "drivers/tty/serial/8250/8250_pci.c:addidata_apci7800_setup",
        "drivers/tty/serial/8250/8250_pci.c:addidata_apci7800_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584130880,
      "name": "setup_port",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 283
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "setup_port",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584470432,
      "name": "setup_port",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_pci.c:78",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_pci.c:pci_omegapci_setup",
        "drivers/tty/serial/8250/8250_pci.c:ce4100_serial_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_default_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_netmos_9900_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup",
        "drivers/tty/serial/8250/8250_pci.c:titan_400l_800l_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_timedia_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_setup",
        "drivers/tty/serial/8250/8250_pci.c:sbs_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_hp_diva_setup",
        "drivers/tty/serial/8250/8250_pci.c:afavlab_setup",
        "drivers/tty/serial/8250/8250_pci.c:addidata_apci7800_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584470432,
      "name": "setup_port.isra.16",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 243
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "setup_port",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584652496,
      "name": "setup_port",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_pci.c:75",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_pci.c:pci_omegapci_setup",
        "drivers/tty/serial/8250/8250_pci.c:ce4100_serial_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_pericom_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_default_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_netmos_9900_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup",
        "drivers/tty/serial/8250/8250_pci.c:titan_400l_800l_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_timedia_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_setup",
        "drivers/tty/serial/8250/8250_pci.c:sbs_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_hp_diva_setup",
        "drivers/tty/serial/8250/8250_pci.c:afavlab_setup",
        "drivers/tty/serial/8250/8250_pci.c:addidata_apci7800_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584652496,
      "name": "setup_port.isra.17",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 243
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "setup_port",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584735264,
      "name": "setup_port",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_pci.c:75",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_pci.c:pci_omegapci_setup",
        "drivers/tty/serial/8250/8250_pci.c:ce4100_serial_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_pericom_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_default_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_netmos_9900_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup",
        "drivers/tty/serial/8250/8250_pci.c:titan_400l_800l_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_timedia_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_setup",
        "drivers/tty/serial/8250/8250_pci.c:sbs_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_hp_diva_setup",
        "drivers/tty/serial/8250/8250_pci.c:afavlab_setup",
        "drivers/tty/serial/8250/8250_pci.c:addidata_apci7800_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584735264,
      "name": "setup_port.isra.9",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 245
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "setup_port",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585150224,
      "name": "setup_port",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_pci.c:72",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_pci.c:pci_omegapci_setup",
        "drivers/tty/serial/8250/8250_pci.c:ce4100_serial_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_pericom_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_default_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_netmos_9900_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup",
        "drivers/tty/serial/8250/8250_pci.c:titan_400l_800l_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_timedia_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_setup",
        "drivers/tty/serial/8250/8250_pci.c:sbs_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_hp_diva_setup",
        "drivers/tty/serial/8250/8250_pci.c:afavlab_setup",
        "drivers/tty/serial/8250/8250_pci.c:addidata_apci7800_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585150224,
      "name": "setup_port.isra.11",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 243
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "setup_port",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585384672,
      "name": "setup_port",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_pci.c:72",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_pci.c:pci_omegapci_setup",
        "drivers/tty/serial/8250/8250_pci.c:ce4100_serial_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_pericom_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_default_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_netmos_9900_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup",
        "drivers/tty/serial/8250/8250_pci.c:titan_400l_800l_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_timedia_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_setup",
        "drivers/tty/serial/8250/8250_pci.c:sbs_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_hp_diva_setup",
        "drivers/tty/serial/8250/8250_pci.c:afavlab_setup",
        "drivers/tty/serial/8250/8250_pci.c:addidata_apci7800_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585384672,
      "name": "setup_port.isra.11",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 243
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "setup_port",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585508192,
      "name": "setup_port",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_pci.c:72",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_pci.c:pci_omegapci_setup",
        "drivers/tty/serial/8250/8250_pci.c:ce4100_serial_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_pericom_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_default_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_netmos_9900_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup",
        "drivers/tty/serial/8250/8250_pci.c:titan_400l_800l_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_timedia_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_setup",
        "drivers/tty/serial/8250/8250_pci.c:sbs_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_hp_diva_setup",
        "drivers/tty/serial/8250/8250_pci.c:afavlab_setup",
        "drivers/tty/serial/8250/8250_pci.c:addidata_apci7800_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585508192,
      "name": "setup_port.isra.11",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 245
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "setup_port",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585726864,
      "name": "setup_port",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_pci.c:72",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_pci.c:pci_sunix_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_sunix_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_omegapci_setup",
        "drivers/tty/serial/8250/8250_pci.c:ce4100_serial_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_pericom_setup_four_at_eight",
        "drivers/tty/serial/8250/8250_pci.c:pci_pericom_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_default_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_netmos_9900_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup",
        "drivers/tty/serial/8250/8250_pci.c:titan_400l_800l_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_timedia_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_setup",
        "drivers/tty/serial/8250/8250_pci.c:sbs_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_hp_diva_setup",
        "drivers/tty/serial/8250/8250_pci.c:afavlab_setup",
        "drivers/tty/serial/8250/8250_pci.c:addidata_apci7800_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585726864,
      "name": "setup_port.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "setup_port",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585868640,
      "name": "setup_port",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_pci.c:87",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_pci.c:pci_moxa_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_moxa_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_sunix_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_sunix_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_omegapci_setup",
        "drivers/tty/serial/8250/8250_pci.c:ce4100_serial_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_pericom_setup_four_at_eight",
        "drivers/tty/serial/8250/8250_pci.c:pci_pericom_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_default_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_netmos_9900_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup",
        "drivers/tty/serial/8250/8250_pci.c:titan_400l_800l_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_timedia_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_setup",
        "drivers/tty/serial/8250/8250_pci.c:sbs_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_hp_diva_setup",
        "drivers/tty/serial/8250/8250_pci.c:afavlab_setup",
        "drivers/tty/serial/8250/8250_pci.c:addidata_apci7800_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585868640,
      "name": "setup_port.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 243
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
int setup_port(struct serial_private * priv, struct uart_8250_port * port, int bar, int offset, int regshift)
```

```json
{
  "name": "setup_port",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586608395,
      "name": "setup_port",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_pci.c:85",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_pci.c:pci_omegapci_setup",
        "drivers/tty/serial/8250/8250_pci.c:sbs_setup"
      ],
      "caller_func": [
        "drivers/tty/serial/8250/8250_pci.c:pci_moxa_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_moxa_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_sunix_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_sunix_setup",
        "drivers/tty/serial/8250/8250_pci.c:ce4100_serial_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_pericom_setup_four_at_eight",
        "drivers/tty/serial/8250/8250_pci.c:pci_pericom_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_default_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup",
        "drivers/tty/serial/8250/8250_pci.c:titan_400l_800l_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_timedia_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_hp_diva_setup",
        "drivers/tty/serial/8250/8250_pci.c:afavlab_setup",
        "drivers/tty/serial/8250/8250_pci.c:addidata_apci7800_setup",
        "drivers/tty/serial/8250/8250_pci.c:addidata_apci7800_setup",
        "drivers/tty/serial/8250/8250_pci.c:addidata_apci7800_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586599296,
      "name": "setup_port",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 257
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
int setup_port(struct serial_private * priv, struct uart_8250_port * port, int bar, int offset, int regshift)
```

```json
{
  "name": "setup_port",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586718795,
      "name": "setup_port",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_pci.c:85",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_pci.c:pci_omegapci_setup",
        "drivers/tty/serial/8250/8250_pci.c:sbs_setup"
      ],
      "caller_func": [
        "drivers/tty/serial/8250/8250_pci.c:pci_moxa_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_moxa_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_sunix_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_sunix_setup",
        "drivers/tty/serial/8250/8250_pci.c:ce4100_serial_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_pericom_setup_four_at_eight",
        "drivers/tty/serial/8250/8250_pci.c:pci_pericom_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_default_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup",
        "drivers/tty/serial/8250/8250_pci.c:titan_400l_800l_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_timedia_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_hp_diva_setup",
        "drivers/tty/serial/8250/8250_pci.c:afavlab_setup",
        "drivers/tty/serial/8250/8250_pci.c:addidata_apci7800_setup",
        "drivers/tty/serial/8250/8250_pci.c:addidata_apci7800_setup",
        "drivers/tty/serial/8250/8250_pci.c:addidata_apci7800_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586709728,
      "name": "setup_port",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 257
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
int setup_port(struct serial_private * priv, struct uart_8250_port * port, int bar, int offset, int regshift)
```

```json
{
  "name": "setup_port",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586602315,
      "name": "setup_port",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_pci.c:89",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_pci.c:pci_omegapci_setup",
        "drivers/tty/serial/8250/8250_pci.c:sbs_setup"
      ],
      "caller_func": [
        "drivers/tty/serial/8250/8250_pci.c:pci_moxa_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_moxa_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_sunix_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_sunix_setup",
        "drivers/tty/serial/8250/8250_pci.c:ce4100_serial_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_pericom_setup_four_at_eight",
        "drivers/tty/serial/8250/8250_pci.c:pci_pericom_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_default_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup",
        "drivers/tty/serial/8250/8250_pci.c:titan_400l_800l_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_timedia_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_timedia_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_timedia_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_hp_diva_setup",
        "drivers/tty/serial/8250/8250_pci.c:afavlab_setup",
        "drivers/tty/serial/8250/8250_pci.c:afavlab_setup",
        "drivers/tty/serial/8250/8250_pci.c:addidata_apci7800_setup",
        "drivers/tty/serial/8250/8250_pci.c:addidata_apci7800_setup",
        "drivers/tty/serial/8250/8250_pci.c:addidata_apci7800_setup",
        "drivers/tty/serial/8250/8250_pci.c:addidata_apci7800_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586593296,
      "name": "setup_port",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
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
int setup_port(struct serial_private * priv, struct uart_8250_port * port, u8 bar, unsigned int offset, int regshift)
```

```json
{
  "name": "setup_port",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587145307,
      "name": "setup_port",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_pci.c:89",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_pci.c:pci_omegapci_setup",
        "drivers/tty/serial/8250/8250_pci.c:sbs_setup"
      ],
      "caller_func": [
        "drivers/tty/serial/8250/8250_pci.c:pci_moxa_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_moxa_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_sunix_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_sunix_setup",
        "drivers/tty/serial/8250/8250_pci.c:ce4100_serial_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_pericom_setup_four_at_eight",
        "drivers/tty/serial/8250/8250_pci.c:pci_pericom_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_default_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup",
        "drivers/tty/serial/8250/8250_pci.c:titan_400l_800l_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_timedia_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_timedia_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_timedia_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_hp_diva_setup",
        "drivers/tty/serial/8250/8250_pci.c:afavlab_setup",
        "drivers/tty/serial/8250/8250_pci.c:afavlab_setup",
        "drivers/tty/serial/8250/8250_pci.c:addidata_apci7800_setup",
        "drivers/tty/serial/8250/8250_pci.c:addidata_apci7800_setup",
        "drivers/tty/serial/8250/8250_pci.c:addidata_apci7800_setup",
        "drivers/tty/serial/8250/8250_pci.c:addidata_apci7800_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587134960,
      "name": "setup_port",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 416
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
int setup_port(struct serial_private * priv, struct uart_8250_port * port, u8 bar, unsigned int offset, int regshift)
```

```json
{
  "name": "setup_port",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588455371,
      "name": "setup_port",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_pci.c:89",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_pci.c:pci_omegapci_setup",
        "drivers/tty/serial/8250/8250_pci.c:sbs_setup"
      ],
      "caller_func": [
        "drivers/tty/serial/8250/8250_pci.c:pci_moxa_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_moxa_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_sunix_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_sunix_setup",
        "drivers/tty/serial/8250/8250_pci.c:ce4100_serial_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_default_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup",
        "drivers/tty/serial/8250/8250_pci.c:titan_400l_800l_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_timedia_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_timedia_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_timedia_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_hp_diva_setup",
        "drivers/tty/serial/8250/8250_pci.c:afavlab_setup",
        "drivers/tty/serial/8250/8250_pci.c:afavlab_setup",
        "drivers/tty/serial/8250/8250_pci.c:addidata_apci7800_setup",
        "drivers/tty/serial/8250/8250_pci.c:addidata_apci7800_setup",
        "drivers/tty/serial/8250/8250_pci.c:addidata_apci7800_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588444576,
      "name": "setup_port",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
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
int setup_port(struct serial_private * priv, struct uart_8250_port * port, u8 bar, unsigned int offset, int regshift)
```

```json
{
  "name": "setup_port",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589885275,
      "name": "setup_port",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_pci.c:89",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_pci.c:pci_omegapci_setup",
        "drivers/tty/serial/8250/8250_pci.c:sbs_setup"
      ],
      "caller_func": [
        "drivers/tty/serial/8250/8250_pci.c:pci_moxa_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_moxa_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_sunix_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_sunix_setup",
        "drivers/tty/serial/8250/8250_pci.c:ce4100_serial_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_default_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup",
        "drivers/tty/serial/8250/8250_pci.c:titan_400l_800l_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_timedia_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_timedia_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_timedia_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_hp_diva_setup",
        "drivers/tty/serial/8250/8250_pci.c:afavlab_setup",
        "drivers/tty/serial/8250/8250_pci.c:afavlab_setup",
        "drivers/tty/serial/8250/8250_pci.c:addidata_apci7800_setup",
        "drivers/tty/serial/8250/8250_pci.c:addidata_apci7800_setup",
        "drivers/tty/serial/8250/8250_pci.c:addidata_apci7800_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589873840,
      "name": "setup_port",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 372
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "setup_port",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590183127,
      "name": "setup_port",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_pci.c:90",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_pci.c:pci_moxa_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_sunix_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_omegapci_setup",
        "drivers/tty/serial/8250/8250_pci.c:ce4100_serial_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_default_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_netmos_9900_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup",
        "drivers/tty/serial/8250/8250_pci.c:titan_400l_800l_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_timedia_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_setup",
        "drivers/tty/serial/8250/8250_pci.c:sbs_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_hp_diva_setup",
        "drivers/tty/serial/8250/8250_pci.c:afavlab_setup",
        "drivers/tty/serial/8250/8250_pci.c:addidata_apci7800_setup"
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
  "name": "setup_port",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590526775,
      "name": "setup_port",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_pci.c:171",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_pci.c:pci_moxa_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_sunix_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_omegapci_setup",
        "drivers/tty/serial/8250/8250_pci.c:ce4100_serial_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_default_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_netmos_9900_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup",
        "drivers/tty/serial/8250/8250_pci.c:titan_400l_800l_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_timedia_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_setup",
        "drivers/tty/serial/8250/8250_pci.c:sbs_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_hp_diva_setup",
        "drivers/tty/serial/8250/8250_pci.c:afavlab_setup",
        "drivers/tty/serial/8250/8250_pci.c:addidata_apci7800_setup"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "setup_port",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336498602624,
      "name": "setup_port",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_pci.c:87",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_pci.c:pci_moxa_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_sunix_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_sunix_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_omegapci_setup",
        "drivers/tty/serial/8250/8250_pci.c:ce4100_serial_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_pericom_setup_four_at_eight",
        "drivers/tty/serial/8250/8250_pci.c:pci_pericom_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_default_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_netmos_9900_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup",
        "drivers/tty/serial/8250/8250_pci.c:titan_400l_800l_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_timedia_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_timedia_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_timedia_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_setup",
        "drivers/tty/serial/8250/8250_pci.c:sbs_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_hp_diva_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_hp_diva_setup",
        "drivers/tty/serial/8250/8250_pci.c:afavlab_setup",
        "drivers/tty/serial/8250/8250_pci.c:afavlab_setup",
        "drivers/tty/serial/8250/8250_pci.c:addidata_apci7800_setup",
        "drivers/tty/serial/8250/8250_pci.c:addidata_apci7800_setup",
        "drivers/tty/serial/8250/8250_pci.c:addidata_apci7800_setup",
        "drivers/tty/serial/8250/8250_pci.c:addidata_apci7800_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498602624,
      "name": "setup_port.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 252
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
int setup_port(struct serial_private * priv, struct uart_8250_port * port, int bar, int offset, int regshift)
```

```json
{
  "name": "setup_port",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231229196,
      "name": "setup_port",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_pci.c:87",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_pci.c:pci_moxa_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_sunix_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_omegapci_setup",
        "drivers/tty/serial/8250/8250_pci.c:ce4100_serial_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_pericom_setup_four_at_eight",
        "drivers/tty/serial/8250/8250_pci.c:pci_pericom_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_default_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup",
        "drivers/tty/serial/8250/8250_pci.c:titan_400l_800l_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_timedia_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_setup",
        "drivers/tty/serial/8250/8250_pci.c:sbs_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_hp_diva_setup",
        "drivers/tty/serial/8250/8250_pci.c:afavlab_setup",
        "drivers/tty/serial/8250/8250_pci.c:addidata_apci7800_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231229196,
      "name": "setup_port",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "setup_port",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055291824848,
      "name": "setup_port",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_pci.c:87",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_pci.c:pci_moxa_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_moxa_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_sunix_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_sunix_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_omegapci_setup",
        "drivers/tty/serial/8250/8250_pci.c:ce4100_serial_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_pericom_setup_four_at_eight",
        "drivers/tty/serial/8250/8250_pci.c:pci_pericom_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_default_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_netmos_9900_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup",
        "drivers/tty/serial/8250/8250_pci.c:titan_400l_800l_setup",
        "drivers/tty/serial/8250/8250_pci.c:titan_400l_800l_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_timedia_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_timedia_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_timedia_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_setup",
        "drivers/tty/serial/8250/8250_pci.c:sbs_setup",
        "drivers/tty/serial/8250/8250_pci.c:sbs_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_hp_diva_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_hp_diva_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_hp_diva_setup",
        "drivers/tty/serial/8250/8250_pci.c:afavlab_setup",
        "drivers/tty/serial/8250/8250_pci.c:afavlab_setup",
        "drivers/tty/serial/8250/8250_pci.c:addidata_apci7800_setup",
        "drivers/tty/serial/8250/8250_pci.c:addidata_apci7800_setup",
        "drivers/tty/serial/8250/8250_pci.c:addidata_apci7800_setup",
        "drivers/tty/serial/8250/8250_pci.c:addidata_apci7800_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291824848,
      "name": "setup_port.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 360
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "setup_port",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276201654,
      "name": "setup_port",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_pci.c:87",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_pci.c:pci_moxa_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_sunix_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_omegapci_setup",
        "drivers/tty/serial/8250/8250_pci.c:ce4100_serial_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_pericom_setup_four_at_eight",
        "drivers/tty/serial/8250/8250_pci.c:pci_pericom_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_default_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_netmos_9900_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup",
        "drivers/tty/serial/8250/8250_pci.c:titan_400l_800l_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_timedia_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_setup",
        "drivers/tty/serial/8250/8250_pci.c:sbs_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_hp_diva_setup",
        "drivers/tty/serial/8250/8250_pci.c:afavlab_setup",
        "drivers/tty/serial/8250/8250_pci.c:addidata_apci7800_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276201654,
      "name": "setup_port.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "setup_port",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585629648,
      "name": "setup_port",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_pci.c:87",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_pci.c:pci_moxa_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_moxa_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_sunix_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_sunix_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_omegapci_setup",
        "drivers/tty/serial/8250/8250_pci.c:ce4100_serial_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_pericom_setup_four_at_eight",
        "drivers/tty/serial/8250/8250_pci.c:pci_pericom_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_default_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_netmos_9900_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup",
        "drivers/tty/serial/8250/8250_pci.c:titan_400l_800l_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_timedia_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_setup",
        "drivers/tty/serial/8250/8250_pci.c:sbs_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_hp_diva_setup",
        "drivers/tty/serial/8250/8250_pci.c:afavlab_setup",
        "drivers/tty/serial/8250/8250_pci.c:addidata_apci7800_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585629648,
      "name": "setup_port.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "setup_port",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585494704,
      "name": "setup_port",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_pci.c:87",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_pci.c:pci_moxa_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_moxa_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_sunix_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_sunix_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_omegapci_setup",
        "drivers/tty/serial/8250/8250_pci.c:ce4100_serial_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_pericom_setup_four_at_eight",
        "drivers/tty/serial/8250/8250_pci.c:pci_pericom_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_default_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_netmos_9900_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup",
        "drivers/tty/serial/8250/8250_pci.c:titan_400l_800l_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_timedia_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_setup",
        "drivers/tty/serial/8250/8250_pci.c:sbs_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_hp_diva_setup",
        "drivers/tty/serial/8250/8250_pci.c:afavlab_setup",
        "drivers/tty/serial/8250/8250_pci.c:addidata_apci7800_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585494704,
      "name": "setup_port.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 243
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "setup_port",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585819040,
      "name": "setup_port",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_pci.c:87",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_pci.c:pci_moxa_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_moxa_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_sunix_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_sunix_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_omegapci_setup",
        "drivers/tty/serial/8250/8250_pci.c:ce4100_serial_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_pericom_setup_four_at_eight",
        "drivers/tty/serial/8250/8250_pci.c:pci_pericom_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_default_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_netmos_9900_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup",
        "drivers/tty/serial/8250/8250_pci.c:titan_400l_800l_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_timedia_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_setup",
        "drivers/tty/serial/8250/8250_pci.c:sbs_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_hp_diva_setup",
        "drivers/tty/serial/8250/8250_pci.c:afavlab_setup",
        "drivers/tty/serial/8250/8250_pci.c:addidata_apci7800_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585819040,
      "name": "setup_port.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 243
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "setup_port",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585926656,
      "name": "setup_port",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_pci.c:87",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_pci.c:pci_moxa_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_moxa_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_sunix_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_sunix_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_omegapci_setup",
        "drivers/tty/serial/8250/8250_pci.c:ce4100_serial_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_pericom_setup_four_at_eight",
        "drivers/tty/serial/8250/8250_pci.c:pci_pericom_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_default_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_netmos_9900_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_ni8430_setup",
        "drivers/tty/serial/8250/8250_pci.c:titan_400l_800l_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_timedia_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_siig_setup",
        "drivers/tty/serial/8250/8250_pci.c:sbs_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_hp_diva_setup",
        "drivers/tty/serial/8250/8250_pci.c:afavlab_setup",
        "drivers/tty/serial/8250/8250_pci.c:addidata_apci7800_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585926656,
      "name": "setup_port.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 243
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
<summary>Removed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➖</summary>

```c
int setup_port(struct serial_private * priv, struct uart_8250_port * port, int bar, int offset, int regshift)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int setup_port(struct serial_private * priv, struct uart_8250_port * port, int bar, int offset, int regshift)
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
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int bar</code> ➡️ <code>u8 bar</code>
</li>
<li>
<b>Param type changed. </b>
<code>int offset</code> ➡️ <code>unsigned int offset</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
int setup_port(struct serial_private * priv, struct uart_8250_port * port, u8 bar, unsigned int offset, int regshift)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int setup_port(struct serial_private * priv, struct uart_8250_port * port, int bar, int offset, int regshift)
```
</details>
</li>
</ul>
