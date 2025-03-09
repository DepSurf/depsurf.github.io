# Function: <code>pcc_chan_reg_init</code>

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
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int pcc_chan_reg_init(struct pcc_chan_reg * reg, struct acpi_generic_address * gas, u64 preserve_mask, u64 set_mask, u64 status_mask, char * name)
```

```json
{
  "name": "pcc_chan_reg_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pcc_chan_reg_init",
      "external": false,
      "loc": "drivers/mailbox/pcc.c:406",
      "file": "drivers/mailbox/pcc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mailbox/pcc.c:pcc_mbox_probe",
        "drivers/mailbox/pcc.c:pcc_mbox_probe",
        "drivers/mailbox/pcc.c:pcc_mbox_probe",
        "drivers/mailbox/pcc.c:pcc_mbox_probe",
        "drivers/mailbox/pcc.c:pcc_mbox_probe",
        "drivers/mailbox/pcc.c:pcc_mbox_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591209168,
      "name": "pcc_chan_reg_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
    },
    {
      "addr": 18446744071594564022,
      "name": "pcc_chan_reg_init.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
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
int pcc_chan_reg_init(struct pcc_chan_reg * reg, struct acpi_generic_address * gas, u64 preserve_mask, u64 set_mask, u64 status_mask, char * name)
```

```json
{
  "name": "pcc_chan_reg_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592951712,
      "name": "pcc_chan_reg_init",
      "external": false,
      "loc": "drivers/mailbox/pcc.c:406",
      "file": "drivers/mailbox/pcc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mailbox/pcc.c:pcc_mbox_probe",
        "drivers/mailbox/pcc.c:pcc_mbox_probe",
        "drivers/mailbox/pcc.c:pcc_mbox_probe",
        "drivers/mailbox/pcc.c:pcc_mbox_probe",
        "drivers/mailbox/pcc.c:pcc_mbox_probe",
        "drivers/mailbox/pcc.c:pcc_mbox_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592951712,
      "name": "pcc_chan_reg_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
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
int pcc_chan_reg_init(struct pcc_chan_reg * reg, struct acpi_generic_address * gas, u64 preserve_mask, u64 set_mask, u64 status_mask, char * name)
```

```json
{
  "name": "pcc_chan_reg_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593402304,
      "name": "pcc_chan_reg_init",
      "external": false,
      "loc": "drivers/mailbox/pcc.c:412",
      "file": "drivers/mailbox/pcc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mailbox/pcc.c:pcc_mbox_probe",
        "drivers/mailbox/pcc.c:pcc_mbox_probe",
        "drivers/mailbox/pcc.c:pcc_mbox_probe",
        "drivers/mailbox/pcc.c:pcc_mbox_probe",
        "drivers/mailbox/pcc.c:pcc_mbox_probe",
        "drivers/mailbox/pcc.c:pcc_mbox_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593402304,
      "name": "pcc_chan_reg_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
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
int pcc_chan_reg_init(struct pcc_chan_reg * reg, struct acpi_generic_address * gas, u64 preserve_mask, u64 set_mask, u64 status_mask, char * name)
```

```json
{
  "name": "pcc_chan_reg_init",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594147728,
      "name": "pcc_chan_reg_init",
      "external": false,
      "loc": "drivers/mailbox/pcc.c:473",
      "file": "drivers/mailbox/pcc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/mailbox/pcc.c:pcc_mbox_probe",
        "drivers/mailbox/pcc.c:pcc_mbox_probe",
        "drivers/mailbox/pcc.c:pcc_mbox_probe",
        "drivers/mailbox/pcc.c:pcc_mbox_probe",
        "drivers/mailbox/pcc.c:pcc_mbox_probe",
        "drivers/mailbox/pcc.c:pcc_mbox_probe",
        "drivers/mailbox/pcc.c:pcc_mbox_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594147728,
      "name": "pcc_chan_reg_init",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
int pcc_chan_reg_init(struct pcc_chan_reg * reg, struct acpi_generic_address * gas, u64 preserve_mask, u64 set_mask, u64 status_mask, char * name)
```
</details>
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
