# Function: <code>ahci_do_softreset</code>

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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int ahci_do_softreset(struct ata_link * link, unsigned int * class, int pmp, long unsigned int deadline, int (*)(struct ata_link *) check_ready)
```

```json
{
  "name": "ahci_do_softreset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499835080,
      "name": "ahci_do_softreset",
      "external": true,
      "loc": "drivers/ata/libahci.c:1381",
      "file": "drivers/ata/libahci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libahci.c:ahci_pmp_retry_softreset",
        "drivers/ata/libahci.c:ahci_pmp_retry_softreset",
        "drivers/ata/libahci.c:ahci_softreset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499835080,
      "name": "ahci_do_softreset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 584
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
int ahci_do_softreset(struct ata_link * link, unsigned int * class, int pmp, long unsigned int deadline, int (*)(struct ata_link *) check_ready)
```

```json
{
  "name": "ahci_do_softreset",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3232263388,
      "name": "ahci_do_softreset",
      "external": true,
      "loc": "drivers/ata/libahci.c:1381",
      "file": "drivers/ata/libahci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libahci.c:ahci_pmp_retry_softreset",
        "drivers/ata/libahci.c:ahci_pmp_retry_softreset",
        "drivers/ata/libahci.c:ahci_softreset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232263388,
      "name": "ahci_do_softreset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 624
    }
  ]
}
```
</details>
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
int ahci_do_softreset(struct ata_link * link, unsigned int * class, int pmp, long unsigned int deadline, int (*)(struct ata_link *) check_ready)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int ahci_do_softreset(struct ata_link * link, unsigned int * class, int pmp, long unsigned int deadline, int (*)(struct ata_link *) check_ready)
```
</details>
</li>
</ul>
