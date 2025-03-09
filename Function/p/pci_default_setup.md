# Function: <code>pci_default_setup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int pci_default_setup(struct serial_private * priv, const struct pciserial_board * board, struct uart_8250_port * port, int idx)
```

```json
{
  "name": "pci_default_setup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584131776,
      "name": "pci_default_setup",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_pci.c:1316",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_pci.c:pci_brcm_trumanage_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_asix_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_wch_ch38x_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_wch_ch353_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_xr17c154_setup",
        "drivers/tty/serial/8250/8250_pci.c:skip_tx_en_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_fastcom335_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_xr17v35x_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:byt_serial_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584131776,
      "name": "pci_default_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int pci_default_setup(struct serial_private * priv, const struct pciserial_board * board, struct uart_8250_port * port, int idx)
```

```json
{
  "name": "pci_default_setup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584471280,
      "name": "pci_default_setup",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_pci.c:1315",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_pci.c:pci_wch_ch38x_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_wch_ch355_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_fastcom335_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_xr17v35x_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_xr17c154_setup",
        "drivers/tty/serial/8250/8250_pci.c:skip_tx_en_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_brcm_trumanage_setup",
        "drivers/tty/serial/8250/8250_pci.c:byt_serial_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_asix_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_netmos_9900_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584471280,
      "name": "pci_default_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int pci_default_setup(struct serial_private * priv, const struct pciserial_board * board, struct uart_8250_port * port, int idx)
```

```json
{
  "name": "pci_default_setup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584653504,
      "name": "pci_default_setup",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_pci.c:1312",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_pci.c:pci_wch_ch38x_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_wch_ch355_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_fastcom335_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_xr17v35x_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_xr17c154_setup",
        "drivers/tty/serial/8250/8250_pci.c:skip_tx_en_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_brcm_trumanage_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_asix_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_netmos_9900_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584653504,
      "name": "pci_default_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int pci_default_setup(struct serial_private * priv, const struct pciserial_board * board, struct uart_8250_port * port, int idx)
```

```json
{
  "name": "pci_default_setup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584736128,
      "name": "pci_default_setup",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_pci.c:1312",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_pci.c:pci_wch_ch38x_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_wch_ch353_setup",
        "drivers/tty/serial/8250/8250_pci.c:skip_tx_en_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_brcm_trumanage_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_asix_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_netmos_9900_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584736128,
      "name": "pci_default_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int pci_default_setup(struct serial_private * priv, const struct pciserial_board * board, struct uart_8250_port * port, int idx)
```

```json
{
  "name": "pci_default_setup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585151088,
      "name": "pci_default_setup",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_pci.c:1309",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_pci.c:pci_wch_ch38x_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_wch_ch353_setup",
        "drivers/tty/serial/8250/8250_pci.c:skip_tx_en_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_brcm_trumanage_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_asix_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_netmos_9900_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585151088,
      "name": "pci_default_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int pci_default_setup(struct serial_private * priv, const struct pciserial_board * board, struct uart_8250_port * port, int idx)
```

```json
{
  "name": "pci_default_setup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585385552,
      "name": "pci_default_setup",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_pci.c:1309",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_pci.c:pci_wch_ch38x_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_wch_ch353_setup",
        "drivers/tty/serial/8250/8250_pci.c:skip_tx_en_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_brcm_trumanage_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_asix_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_netmos_9900_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585385552,
      "name": "pci_default_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 149
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int pci_default_setup(struct serial_private * priv, const struct pciserial_board * board, struct uart_8250_port * port, int idx)
```

```json
{
  "name": "pci_default_setup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585509072,
      "name": "pci_default_setup",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_pci.c:1309",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_pci.c:pci_wch_ch38x_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_wch_ch353_setup",
        "drivers/tty/serial/8250/8250_pci.c:skip_tx_en_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_brcm_trumanage_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_asix_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_netmos_9900_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585509072,
      "name": "pci_default_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 149
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int pci_default_setup(struct serial_private * priv, const struct pciserial_board * board, struct uart_8250_port * port, int idx)
```

```json
{
  "name": "pci_default_setup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585728048,
      "name": "pci_default_setup",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_pci.c:1309",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_pci.c:pci_wch_ch38x_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_wch_ch355_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_wch_ch353_setup",
        "drivers/tty/serial/8250/8250_pci.c:skip_tx_en_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_brcm_trumanage_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_asix_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_netmos_9900_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585728048,
      "name": "pci_default_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
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
int pci_default_setup(struct serial_private * priv, const struct pciserial_board * board, struct uart_8250_port * port, int idx)
```

```json
{
  "name": "pci_default_setup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585869936,
      "name": "pci_default_setup",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_pci.c:1324",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_pci.c:pci_wch_ch38x_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_wch_ch355_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_wch_ch353_setup",
        "drivers/tty/serial/8250/8250_pci.c:skip_tx_en_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_brcm_trumanage_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_asix_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_netmos_9900_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585869936,
      "name": "pci_default_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int pci_default_setup(struct serial_private * priv, const struct pciserial_board * board, struct uart_8250_port * port, int idx)
```

```json
{
  "name": "pci_default_setup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586600400,
      "name": "pci_default_setup",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_pci.c:1322",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_pci.c:pci_wch_ch38x_setup",
        "drivers/tty/serial/8250/8250_pci.c:kt_serial_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_brcm_trumanage_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_asix_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586600400,
      "name": "pci_default_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
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
int pci_default_setup(struct serial_private * priv, const struct pciserial_board * board, struct uart_8250_port * port, int idx)
```

```json
{
  "name": "pci_default_setup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586710832,
      "name": "pci_default_setup",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_pci.c:1322",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_pci.c:pci_wch_ch38x_setup",
        "drivers/tty/serial/8250/8250_pci.c:kt_serial_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_brcm_trumanage_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_asix_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586710832,
      "name": "pci_default_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
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
int pci_default_setup(struct serial_private * priv, const struct pciserial_board * board, struct uart_8250_port * port, int idx)
```

```json
{
  "name": "pci_default_setup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586594432,
      "name": "pci_default_setup",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_pci.c:1326",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_pci.c:pci_wch_ch38x_setup",
        "drivers/tty/serial/8250/8250_pci.c:kt_serial_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_brcm_trumanage_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_asix_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586594432,
      "name": "pci_default_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
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
int pci_default_setup(struct serial_private * priv, const struct pciserial_board * board, struct uart_8250_port * port, int idx)
```

```json
{
  "name": "pci_default_setup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_default_setup",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_pci.c:1326",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_pci.c:pci_wch_ch38x_setup",
        "drivers/tty/serial/8250/8250_pci.c:kt_serial_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_brcm_trumanage_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_asix_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587138352,
      "name": "pci_default_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 388
    },
    {
      "addr": 18446744071592452520,
      "name": "pci_default_setup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
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
int pci_default_setup(struct serial_private * priv, const struct pciserial_board * board, struct uart_8250_port * port, int idx)
```

```json
{
  "name": "pci_default_setup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_default_setup",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_pci.c:1493",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_pci.c:pci_wch_ch38x_setup",
        "drivers/tty/serial/8250/8250_pci.c:kt_serial_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_brcm_trumanage_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_asix_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588448320,
      "name": "pci_default_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 412
    },
    {
      "addr": 18446744071594320899,
      "name": "pci_default_setup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
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
int pci_default_setup(struct serial_private * priv, const struct pciserial_board * board, struct uart_8250_port * port, int idx)
```

```json
{
  "name": "pci_default_setup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_default_setup",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_pci.c:1498",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_pci.c:pci_wch_ch38x_setup",
        "drivers/tty/serial/8250/8250_pci.c:kt_serial_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_brcm_trumanage_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_asix_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589876944,
      "name": "pci_default_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 412
    },
    {
      "addr": 18446744071596237059,
      "name": "pci_default_setup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
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
int pci_default_setup(struct serial_private * priv, const struct pciserial_board * board, struct uart_8250_port * port, int idx)
```

```json
{
  "name": "pci_default_setup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_default_setup",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_pci.c:1470",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_pci.c:pci_wch_ch38x_setup",
        "drivers/tty/serial/8250/8250_pci.c:skip_tx_en_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_brcm_trumanage_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_netmos_9900_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590185952,
      "name": "pci_default_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 344
    },
    {
      "addr": 18446744071596765076,
      "name": "pci_default_setup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
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
int pci_default_setup(struct serial_private * priv, const struct pciserial_board * board, struct uart_8250_port * port, int idx)
```

```json
{
  "name": "pci_default_setup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_default_setup",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_pci.c:1551",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_pci.c:pci_wch_ch38x_setup",
        "drivers/tty/serial/8250/8250_pci.c:skip_tx_en_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_brcm_trumanage_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_netmos_9900_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590529600,
      "name": "pci_default_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 344
    },
    {
      "addr": 18446744071597673817,
      "name": "pci_default_setup.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int pci_default_setup(struct serial_private * priv, const struct pciserial_board * board, struct uart_8250_port * port, int idx)
```

```json
{
  "name": "pci_default_setup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498604344,
      "name": "pci_default_setup",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_pci.c:1324",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_pci.c:pci_wch_ch38x_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_wch_ch353_setup",
        "drivers/tty/serial/8250/8250_pci.c:skip_tx_en_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_brcm_trumanage_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_asix_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_netmos_9900_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498604344,
      "name": "pci_default_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
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
int pci_default_setup(struct serial_private * priv, const struct pciserial_board * board, struct uart_8250_port * port, int idx)
```

```json
{
  "name": "pci_default_setup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231230400,
      "name": "pci_default_setup",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_pci.c:1324",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_pci.c:pci_wch_ch38x_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_wch_ch353_setup",
        "drivers/tty/serial/8250/8250_pci.c:skip_tx_en_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_brcm_trumanage_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_asix_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231230400,
      "name": "pci_default_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
int pci_default_setup(struct serial_private * priv, const struct pciserial_board * board, struct uart_8250_port * port, int idx)
```

```json
{
  "name": "pci_default_setup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291826624,
      "name": "pci_default_setup",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_pci.c:1324",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_pci.c:pci_wch_ch38x_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_wch_ch355_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_wch_ch353_setup",
        "drivers/tty/serial/8250/8250_pci.c:skip_tx_en_setup",
        "drivers/tty/serial/8250/8250_pci.c:skip_tx_en_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_brcm_trumanage_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_asix_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_netmos_9900_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291826624,
      "name": "pci_default_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
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
int pci_default_setup(struct serial_private * priv, const struct pciserial_board * board, struct uart_8250_port * port, int idx)
```

```json
{
  "name": "pci_default_setup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276203056,
      "name": "pci_default_setup",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_pci.c:1324",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_pci.c:pci_wch_ch38x_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_wch_ch353_setup",
        "drivers/tty/serial/8250/8250_pci.c:skip_tx_en_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_brcm_trumanage_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_asix_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_netmos_9900_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276203056,
      "name": "pci_default_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
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
int pci_default_setup(struct serial_private * priv, const struct pciserial_board * board, struct uart_8250_port * port, int idx)
```

```json
{
  "name": "pci_default_setup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585630928,
      "name": "pci_default_setup",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_pci.c:1324",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_pci.c:pci_wch_ch38x_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_wch_ch355_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_wch_ch353_setup",
        "drivers/tty/serial/8250/8250_pci.c:skip_tx_en_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_brcm_trumanage_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_asix_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_netmos_9900_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585630928,
      "name": "pci_default_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
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
int pci_default_setup(struct serial_private * priv, const struct pciserial_board * board, struct uart_8250_port * port, int idx)
```

```json
{
  "name": "pci_default_setup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585496000,
      "name": "pci_default_setup",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_pci.c:1324",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_pci.c:pci_wch_ch38x_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_wch_ch355_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_wch_ch353_setup",
        "drivers/tty/serial/8250/8250_pci.c:skip_tx_en_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_brcm_trumanage_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_asix_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_netmos_9900_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585496000,
      "name": "pci_default_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
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
int pci_default_setup(struct serial_private * priv, const struct pciserial_board * board, struct uart_8250_port * port, int idx)
```

```json
{
  "name": "pci_default_setup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585820336,
      "name": "pci_default_setup",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_pci.c:1324",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_pci.c:pci_wch_ch38x_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_wch_ch355_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_wch_ch353_setup",
        "drivers/tty/serial/8250/8250_pci.c:skip_tx_en_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_brcm_trumanage_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_asix_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_netmos_9900_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585820336,
      "name": "pci_default_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
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
int pci_default_setup(struct serial_private * priv, const struct pciserial_board * board, struct uart_8250_port * port, int idx)
```

```json
{
  "name": "pci_default_setup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585927952,
      "name": "pci_default_setup",
      "external": false,
      "loc": "drivers/tty/serial/8250/8250_pci.c:1324",
      "file": "drivers/tty/serial/8250/8250_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_pci.c:pci_wch_ch38x_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_wch_ch355_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_wch_ch353_setup",
        "drivers/tty/serial/8250/8250_pci.c:skip_tx_en_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_brcm_trumanage_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_quatech_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_asix_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_netmos_9900_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585927952,
      "name": "pci_default_setup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 154
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
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
