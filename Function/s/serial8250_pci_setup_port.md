# Function: <code>serial8250_pci_setup_port</code>

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
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int serial8250_pci_setup_port(struct pci_dev * dev, struct uart_8250_port * port, u8 bar, unsigned int offset, int regshift)
```

```json
{
  "name": "serial8250_pci_setup_port",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590180208,
      "name": "serial8250_pci_setup_port",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_pcilib.c:15",
      "file": "drivers/tty/serial/8250/8250_pcilib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_pci.c:pci_moxa_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_moxa_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_sunix_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_sunix_setup",
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
        "drivers/tty/serial/8250/8250_pci.c:addidata_apci7800_setup",
        "drivers/tty/serial/8250/8250_pci.c:addidata_apci7800_setup",
        "drivers/tty/serial/8250/8250_pci.c:addidata_apci7800_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590180208,
      "name": "serial8250_pci_setup_port",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 379
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
int serial8250_pci_setup_port(struct pci_dev * dev, struct uart_8250_port * port, u8 bar, unsigned int offset, int regshift)
```

```json
{
  "name": "serial8250_pci_setup_port",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590520368,
      "name": "serial8250_pci_setup_port",
      "external": true,
      "loc": "drivers/tty/serial/8250/8250_pcilib.c:15",
      "file": "drivers/tty/serial/8250/8250_pcilib.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/8250/8250_pci.c:pci_moxa_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_moxa_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_sunix_setup",
        "drivers/tty/serial/8250/8250_pci.c:pci_sunix_setup",
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
        "drivers/tty/serial/8250/8250_pci.c:addidata_apci7800_setup",
        "drivers/tty/serial/8250/8250_pci.c:addidata_apci7800_setup",
        "drivers/tty/serial/8250/8250_pci.c:addidata_apci7800_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590520368,
      "name": "serial8250_pci_setup_port",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 379
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
<summary>Added between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➕</summary>

```c
int serial8250_pci_setup_port(struct pci_dev * dev, struct uart_8250_port * port, u8 bar, unsigned int offset, int regshift)
```
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
