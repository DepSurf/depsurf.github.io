# Function: <code>mp_register_ioapic_irq</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int mp_register_ioapic_irq(u8 bus_irq, u8 polarity, u8 trigger, u32 gsi)
```

```json
{
  "name": "mp_register_ioapic_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071602669799,
      "name": "mp_register_ioapic_irq",
      "external": false,
      "loc": "arch/x86/kernel/acpi/boot.c:415",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:acpi_sci_ioapic_setup",
        "arch/x86/kernel/acpi/boot.c:mp_override_legacy_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071602669799,
      "name": "mp_register_ioapic_irq",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 183
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
int mp_register_ioapic_irq(u8 bus_irq, u8 polarity, u8 trigger, u32 gsi)
```

```json
{
  "name": "mp_register_ioapic_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071602841646,
      "name": "mp_register_ioapic_irq",
      "external": false,
      "loc": "arch/x86/kernel/acpi/boot.c:422",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:acpi_sci_ioapic_setup",
        "arch/x86/kernel/acpi/boot.c:mp_override_legacy_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071602841646,
      "name": "mp_register_ioapic_irq",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 183
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
int mp_register_ioapic_irq(u8 bus_irq, u8 polarity, u8 trigger, u32 gsi)
```

```json
{
  "name": "mp_register_ioapic_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604637818,
      "name": "mp_register_ioapic_irq",
      "external": false,
      "loc": "arch/x86/kernel/acpi/boot.c:423",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:acpi_sci_ioapic_setup",
        "arch/x86/kernel/acpi/boot.c:mp_override_legacy_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604637818,
      "name": "mp_register_ioapic_irq",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 183
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
int mp_register_ioapic_irq(u8 bus_irq, u8 polarity, u8 trigger, u32 gsi)
```

```json
{
  "name": "mp_register_ioapic_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604735322,
      "name": "mp_register_ioapic_irq",
      "external": false,
      "loc": "arch/x86/kernel/acpi/boot.c:406",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:acpi_sci_ioapic_setup",
        "arch/x86/kernel/acpi/boot.c:mp_override_legacy_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604735322,
      "name": "mp_register_ioapic_irq",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 184
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
int mp_register_ioapic_irq(u8 bus_irq, u8 polarity, u8 trigger, u32 gsi)
```

```json
{
  "name": "mp_register_ioapic_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604748711,
      "name": "mp_register_ioapic_irq",
      "external": false,
      "loc": "arch/x86/kernel/acpi/boot.c:406",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:acpi_sci_ioapic_setup",
        "arch/x86/kernel/acpi/boot.c:mp_override_legacy_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604748711,
      "name": "mp_register_ioapic_irq",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 184
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
int mp_register_ioapic_irq(u8 bus_irq, u8 polarity, u8 trigger, u32 gsi)
```

```json
{
  "name": "mp_register_ioapic_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071609095561,
      "name": "mp_register_ioapic_irq",
      "external": false,
      "loc": "arch/x86/kernel/acpi/boot.c:407",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:acpi_sci_ioapic_setup",
        "arch/x86/kernel/acpi/boot.c:mp_override_legacy_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609095561,
      "name": "mp_register_ioapic_irq",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 184
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
int mp_register_ioapic_irq(u8 bus_irq, u8 polarity, u8 trigger, u32 gsi)
```

```json
{
  "name": "mp_register_ioapic_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071612160734,
      "name": "mp_register_ioapic_irq",
      "external": false,
      "loc": "arch/x86/kernel/acpi/boot.c:407",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:acpi_sci_ioapic_setup",
        "arch/x86/kernel/acpi/boot.c:mp_override_legacy_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612160734,
      "name": "mp_register_ioapic_irq",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 184
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
int mp_register_ioapic_irq(u8 bus_irq, u8 polarity, u8 trigger, u32 gsi)
```

```json
{
  "name": "mp_register_ioapic_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071614300679,
      "name": "mp_register_ioapic_irq",
      "external": false,
      "loc": "arch/x86/kernel/acpi/boot.c:407",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:acpi_sci_ioapic_setup",
        "arch/x86/kernel/acpi/boot.c:mp_override_legacy_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071614300679,
      "name": "mp_register_ioapic_irq",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 184
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
int mp_register_ioapic_irq(u8 bus_irq, u8 polarity, u8 trigger, u32 gsi)
```

```json
{
  "name": "mp_register_ioapic_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071615227230,
      "name": "mp_register_ioapic_irq",
      "external": false,
      "loc": "arch/x86/kernel/acpi/boot.c:405",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:acpi_sci_ioapic_setup",
        "arch/x86/kernel/acpi/boot.c:mp_override_legacy_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615227230,
      "name": "mp_register_ioapic_irq",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 184
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
int mp_register_ioapic_irq(u8 bus_irq, u8 polarity, u8 trigger, u32 gsi)
```

```json
{
  "name": "mp_register_ioapic_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071617001896,
      "name": "mp_register_ioapic_irq",
      "external": false,
      "loc": "arch/x86/kernel/acpi/boot.c:473",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:acpi_sci_ioapic_setup",
        "arch/x86/kernel/acpi/boot.c:mp_override_legacy_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071617001896,
      "name": "mp_register_ioapic_irq",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 210
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
int mp_register_ioapic_irq(u8 bus_irq, u8 polarity, u8 trigger, u32 gsi)
```

```json
{
  "name": "mp_register_ioapic_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071627629904,
      "name": "mp_register_ioapic_irq",
      "external": false,
      "loc": "arch/x86/kernel/acpi/boot.c:486",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:acpi_sci_ioapic_setup",
        "arch/x86/kernel/acpi/boot.c:mp_override_legacy_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071627629904,
      "name": "mp_register_ioapic_irq",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 210
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
int mp_register_ioapic_irq(u8 bus_irq, u8 polarity, u8 trigger, u32 gsi)
```

```json
{
  "name": "mp_register_ioapic_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071619386016,
      "name": "mp_register_ioapic_irq",
      "external": false,
      "loc": "arch/x86/kernel/acpi/boot.c:492",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:acpi_sci_ioapic_setup",
        "arch/x86/kernel/acpi/boot.c:mp_override_legacy_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071619386016,
      "name": "mp_register_ioapic_irq",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 208
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
int mp_register_ioapic_irq(u8 bus_irq, u8 polarity, u8 trigger, u32 gsi)
```

```json
{
  "name": "mp_register_ioapic_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071621681728,
      "name": "mp_register_ioapic_irq",
      "external": false,
      "loc": "arch/x86/kernel/acpi/boot.c:501",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:acpi_sci_ioapic_setup",
        "arch/x86/kernel/acpi/boot.c:mp_override_legacy_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071621681728,
      "name": "mp_register_ioapic_irq",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 208
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int mp_register_ioapic_irq(u8 bus_irq, u8 polarity, u8 trigger, u32 gsi)
```

```json
{
  "name": "mp_register_ioapic_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604675014,
      "name": "mp_register_ioapic_irq",
      "external": false,
      "loc": "arch/x86/kernel/acpi/boot.c:406",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:acpi_sci_ioapic_setup",
        "arch/x86/kernel/acpi/boot.c:mp_override_legacy_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604675014,
      "name": "mp_register_ioapic_irq",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 184
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
int mp_register_ioapic_irq(u8 bus_irq, u8 polarity, u8 trigger, u32 gsi)
```

```json
{
  "name": "mp_register_ioapic_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604642568,
      "name": "mp_register_ioapic_irq",
      "external": false,
      "loc": "arch/x86/kernel/acpi/boot.c:406",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:acpi_sci_ioapic_setup",
        "arch/x86/kernel/acpi/boot.c:mp_override_legacy_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604642568,
      "name": "mp_register_ioapic_irq",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 184
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
int mp_register_ioapic_irq(u8 bus_irq, u8 polarity, u8 trigger, u32 gsi)
```

```json
{
  "name": "mp_register_ioapic_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604752579,
      "name": "mp_register_ioapic_irq",
      "external": false,
      "loc": "arch/x86/kernel/acpi/boot.c:406",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:acpi_sci_ioapic_setup",
        "arch/x86/kernel/acpi/boot.c:mp_override_legacy_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604752579,
      "name": "mp_register_ioapic_irq",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 184
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
int mp_register_ioapic_irq(u8 bus_irq, u8 polarity, u8 trigger, u32 gsi)
```

```json
{
  "name": "mp_register_ioapic_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604752810,
      "name": "mp_register_ioapic_irq",
      "external": false,
      "loc": "arch/x86/kernel/acpi/boot.c:406",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/acpi/boot.c:acpi_sci_ioapic_setup",
        "arch/x86/kernel/acpi/boot.c:mp_override_legacy_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604752810,
      "name": "mp_register_ioapic_irq",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 184
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
int mp_register_ioapic_irq(u8 bus_irq, u8 polarity, u8 trigger, u32 gsi)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int mp_register_ioapic_irq(u8 bus_irq, u8 polarity, u8 trigger, u32 gsi)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int mp_register_ioapic_irq(u8 bus_irq, u8 polarity, u8 trigger, u32 gsi)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int mp_register_ioapic_irq(u8 bus_irq, u8 polarity, u8 trigger, u32 gsi)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int mp_register_ioapic_irq(u8 bus_irq, u8 polarity, u8 trigger, u32 gsi)
```
</details>
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
