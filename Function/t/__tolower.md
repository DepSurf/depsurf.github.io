# Function: <code>__tolower</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__tolower",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579938498,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:38",
      "file": "kernel/kallsyms.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kallsyms.c:s_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595150677,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:38",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:setup_slub_debug"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582128012,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:38",
      "file": "fs/efivarfs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/efivarfs/super.c:efivarfs_d_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582979890,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:38",
      "file": "lib/string.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/string.c:strcasecmp",
        "lib/string.c:strcasecmp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583044828,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:38",
      "file": "lib/hexdump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/hexdump.c:hex2bin",
        "lib/hexdump.c:hex2bin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583546938,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:38",
      "file": "drivers/acpi/device_sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/device_sysfs.c:create_of_modalias"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583730926,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:38",
      "file": "drivers/acpi/acpica/utnonansi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_strlwr",
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_stricmp",
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_stricmp",
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_strtoul64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583791663,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:38",
      "file": "drivers/pnp/card.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/card.c:pnp_alloc_card",
        "drivers/pnp/card.c:pnp_alloc_card",
        "drivers/pnp/card.c:pnp_alloc_card",
        "drivers/pnp/card.c:pnp_alloc_card"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583794168,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:38",
      "file": "drivers/pnp/driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/driver.c:pnp_add_id",
        "drivers/pnp/driver.c:pnp_add_id",
        "drivers/pnp/driver.c:pnp_add_id",
        "drivers/pnp/driver.c:pnp_add_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583980980,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:38",
      "file": "drivers/tty/n_tty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/n_tty.c:n_tty_receive_char_lnext",
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_buf_common"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__tolower",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579969151,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:38",
      "file": "kernel/kallsyms.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kallsyms.c:s_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595322064,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:38",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:setup_slub_debug"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582346083,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:38",
      "file": "fs/efivarfs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/efivarfs/super.c:efivarfs_d_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583269065,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:38",
      "file": "lib/string.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/string.c:strcasecmp",
        "lib/string.c:strcasecmp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583338290,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:38",
      "file": "lib/hexdump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/hexdump.c:hex2bin",
        "lib/hexdump.c:hex2bin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583868177,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:38",
      "file": "drivers/acpi/device_sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/device_sysfs.c:create_of_modalias"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584055826,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:38",
      "file": "drivers/acpi/acpica/utnonansi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_strtoul64",
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_stricmp",
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_stricmp",
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_strlwr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584117855,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:38",
      "file": "drivers/pnp/card.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/card.c:pnp_alloc_card",
        "drivers/pnp/card.c:pnp_alloc_card",
        "drivers/pnp/card.c:pnp_alloc_card",
        "drivers/pnp/card.c:pnp_alloc_card"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584120410,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:38",
      "file": "drivers/pnp/driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/driver.c:pnp_add_id",
        "drivers/pnp/driver.c:pnp_add_id",
        "drivers/pnp/driver.c:pnp_add_id",
        "drivers/pnp/driver.c:pnp_add_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584319559,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:38",
      "file": "drivers/tty/n_tty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_char_lnext"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__tolower",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579999644,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:41",
      "file": "kernel/kallsyms.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kallsyms.c:s_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595570399,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:41",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:setup_slub_debug"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582437315,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:41",
      "file": "fs/efivarfs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/efivarfs/super.c:efivarfs_d_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583387833,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:41",
      "file": "lib/string.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/string.c:strcasecmp",
        "lib/string.c:strcasecmp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583463714,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:41",
      "file": "lib/hexdump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/hexdump.c:hex2bin",
        "lib/hexdump.c:hex2bin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584007213,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:41",
      "file": "drivers/acpi/device_sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/device_sysfs.c:create_of_modalias"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584197669,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:41",
      "file": "drivers/acpi/acpica/utnonansi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_stricmp",
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_stricmp",
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_strlwr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584202329,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:41",
      "file": "drivers/acpi/acpica/utstrtoul64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utstrtoul64.c:acpi_ut_strtoul64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584265855,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:41",
      "file": "drivers/pnp/card.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/card.c:pnp_alloc_card",
        "drivers/pnp/card.c:pnp_alloc_card",
        "drivers/pnp/card.c:pnp_alloc_card",
        "drivers/pnp/card.c:pnp_alloc_card"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584268410,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:41",
      "file": "drivers/pnp/driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/driver.c:pnp_add_id",
        "drivers/pnp/driver.c:pnp_add_id",
        "drivers/pnp/driver.c:pnp_add_id",
        "drivers/pnp/driver.c:pnp_add_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584501591,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:41",
      "file": "drivers/tty/n_tty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_char_lnext"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__tolower",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580006446,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:41",
      "file": "kernel/kallsyms.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kallsyms.c:s_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596497930,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:41",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:setup_slub_debug"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582520602,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:41",
      "file": "fs/efivarfs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/efivarfs/super.c:efivarfs_d_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583485970,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:41",
      "file": "lib/hexdump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/hexdump.c:hex2bin",
        "lib/hexdump.c:hex2bin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584060062,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:41",
      "file": "drivers/acpi/device_sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584265286,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:41",
      "file": "drivers/acpi/acpica/utnonansi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_stricmp",
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_stricmp",
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_strlwr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584269934,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:41",
      "file": "drivers/acpi/acpica/utstrtoul64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utstrtoul64.c:acpi_ut_strtoul64"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584343903,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:41",
      "file": "drivers/pnp/card.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/card.c:pnp_alloc_card",
        "drivers/pnp/card.c:pnp_alloc_card",
        "drivers/pnp/card.c:pnp_alloc_card",
        "drivers/pnp/card.c:pnp_alloc_card"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584346474,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:41",
      "file": "drivers/pnp/driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/driver.c:pnp_add_id",
        "drivers/pnp/driver.c:pnp_add_id",
        "drivers/pnp/driver.c:pnp_add_id",
        "drivers/pnp/driver.c:pnp_add_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584579271,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:41",
      "file": "drivers/tty/n_tty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_char_lnext"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588244505,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:41",
      "file": "lib/string.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/string.c:strcasecmp",
        "lib/string.c:strcasecmp"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__tolower",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580052924,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "kernel/kallsyms.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kallsyms.c:s_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602825298,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:setup_slub_debug"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582672170,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "fs/efivarfs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/efivarfs/super.c:efivarfs_d_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583667010,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "lib/hexdump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/hexdump.c:hex2bin",
        "lib/hexdump.c:hex2bin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584328462,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "drivers/acpi/device_sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584633391,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "drivers/acpi/acpica/utnonansi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_stricmp",
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_stricmp",
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_strlwr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584641255,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "drivers/acpi/acpica/utstrsuppt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utstrsuppt.c:acpi_ut_detect_hex_prefix"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584657191,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "drivers/acpi/acpica/dbinput.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dbinput.c:acpi_db_display_command_info",
        "drivers/acpi/acpica/dbinput.c:acpi_db_display_command_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584749551,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "drivers/pnp/card.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/card.c:pnp_alloc_card",
        "drivers/pnp/card.c:pnp_alloc_card",
        "drivers/pnp/card.c:pnp_alloc_card",
        "drivers/pnp/card.c:pnp_alloc_card"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584752154,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "drivers/pnp/driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/driver.c:pnp_add_id",
        "drivers/pnp/driver.c:pnp_add_id",
        "drivers/pnp/driver.c:pnp_add_id",
        "drivers/pnp/driver.c:pnp_add_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584991306,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "drivers/tty/n_tty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_char_lnext"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588795929,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "lib/string.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/string.c:strcasecmp",
        "lib/string.c:strcasecmp"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__tolower",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580110039,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "kernel/kallsyms.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kallsyms.c:s_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602998670,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:setup_slub_debug"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582865470,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "fs/efivarfs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/efivarfs/super.c:efivarfs_d_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583886240,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "lib/hexdump.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584549261,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "drivers/acpi/device_sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584859099,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "drivers/acpi/acpica/utnonansi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_stricmp",
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_stricmp",
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_strlwr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584866963,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "drivers/acpi/acpica/utstrsuppt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utstrsuppt.c:acpi_ut_detect_hex_prefix"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584883270,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "drivers/acpi/acpica/dbinput.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dbinput.c:acpi_db_display_command_info",
        "drivers/acpi/acpica/dbinput.c:acpi_db_display_command_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584978058,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "drivers/pnp/card.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/card.c:pnp_alloc_card",
        "drivers/pnp/card.c:pnp_alloc_card",
        "drivers/pnp/card.c:pnp_alloc_card",
        "drivers/pnp/card.c:pnp_alloc_card"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584980629,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "drivers/pnp/driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/driver.c:pnp_add_id",
        "drivers/pnp/driver.c:pnp_add_id",
        "drivers/pnp/driver.c:pnp_add_id",
        "drivers/pnp/driver.c:pnp_add_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585225570,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "drivers/tty/n_tty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_char_lnext"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589174052,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "lib/string.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/string.c:strcasecmp",
        "lib/string.c:strcasecmp"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__tolower",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580157047,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "kernel/kallsyms.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kallsyms.c:s_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604797491,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:setup_slub_debug"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582973582,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "fs/efivarfs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/efivarfs/super.c:efivarfs_d_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583970448,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "lib/hexdump.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584646485,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "drivers/acpi/device_sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584962593,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "drivers/acpi/acpica/utnonansi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_stricmp",
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_stricmp",
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_strlwr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584970460,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "drivers/acpi/acpica/utstrsuppt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utstrsuppt.c:acpi_ut_remove_hex_prefix"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584986828,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "drivers/acpi/acpica/dbinput.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dbinput.c:acpi_db_display_command_info",
        "drivers/acpi/acpica/dbinput.c:acpi_db_display_command_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585082794,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "drivers/pnp/card.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/card.c:pnp_alloc_card",
        "drivers/pnp/card.c:pnp_alloc_card",
        "drivers/pnp/card.c:pnp_alloc_card",
        "drivers/pnp/card.c:pnp_alloc_card"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585085365,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "drivers/pnp/driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/driver.c:pnp_add_id",
        "drivers/pnp/driver.c:pnp_add_id",
        "drivers/pnp/driver.c:pnp_add_id",
        "drivers/pnp/driver.c:pnp_add_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585344344,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "drivers/tty/n_tty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_char_lnext"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589403972,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "lib/string.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/string.c:strcasecmp",
        "lib/string.c:strcasecmp"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__tolower",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580203111,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "kernel/kallsyms.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kallsyms.c:s_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604900763,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:setup_slub_debug"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583154628,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "fs/efivarfs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/efivarfs/super.c:efivarfs_d_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584151600,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "lib/hexdump.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584846351,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "drivers/acpi/device_sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585165750,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "drivers/acpi/acpica/utnonansi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_stricmp",
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_stricmp",
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_strlwr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585173725,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "drivers/acpi/acpica/utstrsuppt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utstrsuppt.c:acpi_ut_remove_hex_prefix"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585190347,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "drivers/acpi/acpica/dbinput.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dbinput.c:acpi_db_display_command_info",
        "drivers/acpi/acpica/dbinput.c:acpi_db_display_command_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585287321,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "drivers/pnp/card.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/card.c:pnp_alloc_card",
        "drivers/pnp/card.c:pnp_alloc_card",
        "drivers/pnp/card.c:pnp_alloc_card",
        "drivers/pnp/card.c:pnp_alloc_card"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585289861,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "drivers/pnp/driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/driver.c:pnp_add_id",
        "drivers/pnp/driver.c:pnp_add_id",
        "drivers/pnp/driver.c:pnp_add_id",
        "drivers/pnp/driver.c:pnp_add_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585560143,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "drivers/tty/n_tty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_char_lnext"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589859933,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "lib/string.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/string.c:strcasecmp",
        "lib/string.c:strcasecmp"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__tolower",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580251447,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "kernel/kallsyms.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kallsyms.c:s_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604934638,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:setup_slub_debug"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583260692,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "fs/efivarfs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/efivarfs/super.c:efivarfs_d_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584272772,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "lib/hexdump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/hexdump.c:hex2bin",
        "lib/hexdump.c:hex2bin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584982095,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "drivers/acpi/device_sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585302097,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "drivers/acpi/acpica/utnonansi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_stricmp",
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_stricmp",
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_strlwr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585310078,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "drivers/acpi/acpica/utstrsuppt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utstrsuppt.c:acpi_ut_remove_hex_prefix"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585326700,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "drivers/acpi/acpica/dbinput.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dbinput.c:acpi_db_display_command_info",
        "drivers/acpi/acpica/dbinput.c:acpi_db_display_command_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585425289,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "drivers/pnp/card.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/card.c:pnp_alloc_card",
        "drivers/pnp/card.c:pnp_alloc_card",
        "drivers/pnp/card.c:pnp_alloc_card",
        "drivers/pnp/card.c:pnp_alloc_card"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585427829,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "drivers/pnp/driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/driver.c:pnp_add_id",
        "drivers/pnp/driver.c:pnp_add_id",
        "drivers/pnp/driver.c:pnp_add_id",
        "drivers/pnp/driver.c:pnp_add_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585701279,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "drivers/tty/n_tty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_char_lnext"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590085725,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "lib/string.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/string.c:strcasecmp",
        "lib/string.c:strcasecmp"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
unsigned char __tolower(unsigned char c)
```

```json
{
  "name": "__tolower",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580319943,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "kernel/kallsyms.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kallsyms.c:s_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609249197,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:setup_slub_debug"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583587753,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "fs/efivarfs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/efivarfs/super.c:efivarfs_d_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584683124,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "lib/hexdump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/hexdump.c:hex2bin",
        "lib/hexdump.c:hex2bin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585083522,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "lib/string.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/string.c:strcasecmp",
        "lib/string.c:strcasecmp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585677155,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "drivers/acpi/device_sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/device_sysfs.c:create_of_modalias"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586008429,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "drivers/acpi/acpica/utnonansi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_stricmp",
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_stricmp",
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_strlwr"
      ]
    },
    {
      "addr": 18446744071586016599,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "drivers/acpi/acpica/utstrsuppt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utstrsuppt.c:acpi_ut_remove_hex_prefix"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586033529,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "drivers/acpi/acpica/dbinput.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dbinput.c:acpi_db_match_command_help",
        "drivers/acpi/acpica/dbinput.c:acpi_db_match_command_help"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586140490,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "drivers/pnp/card.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586143994,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "drivers/pnp/driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/driver.c:pnp_add_id",
        "drivers/pnp/driver.c:pnp_add_id",
        "drivers/pnp/driver.c:pnp_add_id",
        "drivers/pnp/driver.c:pnp_add_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586429575,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "drivers/tty/n_tty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/n_tty.c:n_tty_receive_buf_standard",
        "drivers/tty/n_tty.c:n_tty_receive_buf_closing",
        "drivers/tty/n_tty.c:n_tty_receive_char_lnext"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588607299,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "drivers/power/supply/power_supply_sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/power/supply/power_supply_sysfs.c:power_supply_init_attrs"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586008429,
      "name": "__tolower",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
unsigned char __tolower(unsigned char c)
```

```json
{
  "name": "__tolower",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580305079,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:49",
      "file": "kernel/kallsyms.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kallsyms.c:s_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581871855,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:49",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:parse_slub_debug_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583708057,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:49",
      "file": "fs/efivarfs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/efivarfs/super.c:efivarfs_d_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584800804,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:49",
      "file": "lib/hexdump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/hexdump.c:hex2bin",
        "lib/hexdump.c:hex2bin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585232690,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:49",
      "file": "lib/string.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/string.c:strcasecmp",
        "lib/string.c:strcasecmp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585799459,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:49",
      "file": "drivers/acpi/device_sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/device_sysfs.c:create_of_modalias"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586131258,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:49",
      "file": "drivers/acpi/acpica/utnonansi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_stricmp",
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_stricmp",
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_strlwr"
      ]
    },
    {
      "addr": 18446744071586139389,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:49",
      "file": "drivers/acpi/acpica/utstrsuppt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utstrsuppt.c:acpi_ut_remove_hex_prefix"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586156350,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:49",
      "file": "drivers/acpi/acpica/dbinput.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dbinput.c:acpi_db_match_command_help",
        "drivers/acpi/acpica/dbinput.c:acpi_db_match_command_help"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586259370,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:49",
      "file": "drivers/pnp/card.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586262842,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:49",
      "file": "drivers/pnp/driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/driver.c:pnp_add_id",
        "drivers/pnp/driver.c:pnp_add_id",
        "drivers/pnp/driver.c:pnp_add_id",
        "drivers/pnp/driver.c:pnp_add_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586544631,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:49",
      "file": "drivers/tty/n_tty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/n_tty.c:n_tty_receive_buf_standard",
        "drivers/tty/n_tty.c:n_tty_receive_buf_closing",
        "drivers/tty/n_tty.c:n_tty_receive_char_lnext"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588630371,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:49",
      "file": "drivers/power/supply/power_supply_sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/power/supply/power_supply_sysfs.c:power_supply_init_attrs"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586131258,
      "name": "__tolower",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
unsigned char __tolower(unsigned char c)
```

```json
{
  "name": "__tolower",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580308631,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:49",
      "file": "kernel/kallsyms.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kallsyms.c:s_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581902453,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:49",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:parse_slub_debug_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583732664,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:49",
      "file": "fs/efivarfs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/efivarfs/super.c:efivarfs_d_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584844983,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:49",
      "file": "lib/hexdump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/hexdump.c:hex2bin",
        "lib/hexdump.c:hex2bin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585115567,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:49",
      "file": "lib/string.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/string.c:strcasecmp",
        "lib/string.c:strcasecmp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585680147,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:49",
      "file": "drivers/acpi/device_sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/device_sysfs.c:create_of_modalias"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586008042,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:49",
      "file": "drivers/acpi/acpica/utnonansi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_stricmp",
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_stricmp",
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_strlwr"
      ]
    },
    {
      "addr": 18446744071586016154,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:49",
      "file": "drivers/acpi/acpica/utstrsuppt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utstrsuppt.c:acpi_ut_remove_hex_prefix"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586033085,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:49",
      "file": "drivers/acpi/acpica/dbinput.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dbinput.c:acpi_db_display_command_info",
        "drivers/acpi/acpica/dbinput.c:acpi_db_display_command_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586134108,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:49",
      "file": "drivers/pnp/card.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/card.c:pnp_alloc_card",
        "drivers/pnp/card.c:pnp_alloc_card",
        "drivers/pnp/card.c:pnp_alloc_card",
        "drivers/pnp/card.c:pnp_alloc_card"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586136826,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:49",
      "file": "drivers/pnp/driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/driver.c:pnp_add_id",
        "drivers/pnp/driver.c:pnp_add_id",
        "drivers/pnp/driver.c:pnp_add_id",
        "drivers/pnp/driver.c:pnp_add_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586431692,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:49",
      "file": "drivers/tty/n_tty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/n_tty.c:__receive_buf",
        "drivers/tty/n_tty.c:n_tty_receive_buf_standard",
        "drivers/tty/n_tty.c:n_tty_receive_char_lnext"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588515221,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:49",
      "file": "drivers/power/supply/power_supply_sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/power/supply/power_supply_sysfs.c:power_supply_init_attrs"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586008042,
      "name": "__tolower",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
unsigned char __tolower(unsigned char c)
```

```json
{
  "name": "__tolower",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580462007,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:49",
      "file": "kernel/kallsyms.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kallsyms.c:s_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580720462,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:49",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582197173,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:49",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:parse_slub_debug_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584094024,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:49",
      "file": "fs/efivarfs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/efivarfs/super.c:efivarfs_d_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585264903,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:49",
      "file": "lib/hexdump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/hexdump.c:hex2bin",
        "lib/hexdump.c:hex2bin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585564255,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:49",
      "file": "lib/string.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/string.c:strcasecmp",
        "lib/string.c:strcasecmp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586160083,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:49",
      "file": "drivers/acpi/device_sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/device_sysfs.c:create_of_modalias"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586498065,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:49",
      "file": "drivers/acpi/acpica/utnonansi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_stricmp",
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_stricmp",
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_strlwr"
      ]
    },
    {
      "addr": 18446744071586506502,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:49",
      "file": "drivers/acpi/acpica/utstrsuppt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utstrsuppt.c:acpi_ut_remove_hex_prefix"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586524088,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:49",
      "file": "drivers/acpi/acpica/dbinput.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dbinput.c:acpi_db_display_command_info",
        "drivers/acpi/acpica/dbinput.c:acpi_db_display_command_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586634876,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:49",
      "file": "drivers/pnp/card.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/card.c:pnp_alloc_card",
        "drivers/pnp/card.c:pnp_alloc_card",
        "drivers/pnp/card.c:pnp_alloc_card",
        "drivers/pnp/card.c:pnp_alloc_card"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586637626,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:49",
      "file": "drivers/pnp/driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/driver.c:pnp_add_id",
        "drivers/pnp/driver.c:pnp_add_id",
        "drivers/pnp/driver.c:pnp_add_id",
        "drivers/pnp/driver.c:pnp_add_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586957459,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:49",
      "file": "drivers/tty/n_tty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/n_tty.c:__receive_buf",
        "drivers/tty/n_tty.c:n_tty_receive_buf_standard",
        "drivers/tty/n_tty.c:n_tty_receive_buf_standard"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589188597,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:49",
      "file": "drivers/power/supply/power_supply_sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/power/supply/power_supply_sysfs.c:power_supply_init_attrs"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586498065,
      "name": "__tolower",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
unsigned char __tolower(unsigned char c)
```

```json
{
  "name": "__tolower",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580654858,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:49",
      "file": "kernel/kallsyms.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kallsyms.c:s_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071580932409,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:49",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582661265,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:49",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:parse_slub_debug_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584688938,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:49",
      "file": "fs/efivarfs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/efivarfs/super.c:efivarfs_d_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586716575,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:49",
      "file": "lib/string.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/string.c:strcasecmp",
        "lib/string.c:strcasecmp"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587393843,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:49",
      "file": "drivers/acpi/device_sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/device_sysfs.c:create_of_modalias"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587753143,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:49",
      "file": "drivers/acpi/acpica/utnonansi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_stricmp",
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_stricmp",
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_strlwr"
      ]
    },
    {
      "addr": 18446744071587762185,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:49",
      "file": "drivers/acpi/acpica/utstrsuppt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utstrsuppt.c:acpi_ut_remove_hex_prefix"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587781055,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:49",
      "file": "drivers/acpi/acpica/dbinput.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dbinput.c:acpi_db_display_command_info",
        "drivers/acpi/acpica/dbinput.c:acpi_db_display_command_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587900884,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:49",
      "file": "drivers/pnp/card.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/card.c:pnp_alloc_card",
        "drivers/pnp/card.c:pnp_alloc_card",
        "drivers/pnp/card.c:pnp_alloc_card",
        "drivers/pnp/card.c:pnp_alloc_card"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587903838,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:49",
      "file": "drivers/pnp/driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/driver.c:pnp_add_id",
        "drivers/pnp/driver.c:pnp_add_id",
        "drivers/pnp/driver.c:pnp_add_id",
        "drivers/pnp/driver.c:pnp_add_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588252395,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:49",
      "file": "drivers/tty/n_tty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/n_tty.c:__receive_buf",
        "drivers/tty/n_tty.c:n_tty_receive_buf_standard",
        "drivers/tty/n_tty.c:n_tty_receive_buf_standard"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590648341,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:49",
      "file": "drivers/power/supply/power_supply_sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/power/supply/power_supply_sysfs.c:power_supply_init_attrs"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587753143,
      "name": "__tolower",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__tolower",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580922931,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:49",
      "file": "kernel/kallsyms.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kallsyms.c:s_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581225227,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:49",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582500032,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:49",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:store_enabled"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583185257,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:49",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:parse_slub_debug_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585375578,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:49",
      "file": "fs/efivarfs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/efivarfs/super.c:efivarfs_d_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588646947,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:49",
      "file": "drivers/acpi/device_sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/device_sysfs.c:create_of_modalias"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589079912,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:49",
      "file": "drivers/acpi/acpica/utnonansi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_stricmp",
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_stricmp",
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_strlwr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589091326,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:49",
      "file": "drivers/acpi/acpica/utstrsuppt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utstrsuppt.c:acpi_ut_detect_hex_prefix"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589114186,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:49",
      "file": "drivers/acpi/acpica/dbinput.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dbinput.c:acpi_db_display_command_info",
        "drivers/acpi/acpica/dbinput.c:acpi_db_display_command_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589250724,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:49",
      "file": "drivers/pnp/card.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/card.c:pnp_alloc_card",
        "drivers/pnp/card.c:pnp_alloc_card",
        "drivers/pnp/card.c:pnp_alloc_card",
        "drivers/pnp/card.c:pnp_alloc_card"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589254046,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:49",
      "file": "drivers/pnp/driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/driver.c:pnp_add_id",
        "drivers/pnp/driver.c:pnp_add_id",
        "drivers/pnp/driver.c:pnp_add_id",
        "drivers/pnp/driver.c:pnp_add_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589663939,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:49",
      "file": "drivers/tty/n_tty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/n_tty.c:n_tty_receive_buf_standard",
        "drivers/tty/n_tty.c:n_tty_receive_buf_standard",
        "drivers/tty/n_tty.c:n_tty_receive_buf_closing"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592312917,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:49",
      "file": "drivers/power/supply/power_supply_sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/power/supply/power_supply_sysfs.c:power_supply_init_attrs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595878591,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:49",
      "file": "lib/string.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/string.c:strcasecmp",
        "lib/string.c:strcasecmp"
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
  "name": "__tolower",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581010318,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:49",
      "file": "kernel/kallsyms.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kallsyms.c:s_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581319579,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:49",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582693478,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:49",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:enabled_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583403119,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:49",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:parse_slub_debug_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585606074,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:49",
      "file": "fs/efivarfs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/efivarfs/super.c:efivarfs_d_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588934803,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:49",
      "file": "drivers/acpi/device_sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/device_sysfs.c:create_of_modalias"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589371576,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:49",
      "file": "drivers/acpi/acpica/utnonansi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_stricmp",
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_stricmp",
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_strlwr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589383166,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:49",
      "file": "drivers/acpi/acpica/utstrsuppt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utstrsuppt.c:acpi_ut_detect_hex_prefix"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589406138,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:49",
      "file": "drivers/acpi/acpica/dbinput.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dbinput.c:acpi_db_display_command_info",
        "drivers/acpi/acpica/dbinput.c:acpi_db_display_command_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589547556,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:49",
      "file": "drivers/pnp/card.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/card.c:pnp_alloc_card",
        "drivers/pnp/card.c:pnp_alloc_card",
        "drivers/pnp/card.c:pnp_alloc_card",
        "drivers/pnp/card.c:pnp_alloc_card"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589550878,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:49",
      "file": "drivers/pnp/driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/driver.c:pnp_add_id",
        "drivers/pnp/driver.c:pnp_add_id",
        "drivers/pnp/driver.c:pnp_add_id",
        "drivers/pnp/driver.c:pnp_add_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589967763,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:49",
      "file": "drivers/tty/n_tty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/n_tty.c:n_tty_receive_buf_standard",
        "drivers/tty/n_tty.c:n_tty_receive_buf_standard",
        "drivers/tty/n_tty.c:n_tty_receive_buf_closing"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071592739237,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:49",
      "file": "drivers/power/supply/power_supply_sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/power/supply/power_supply_sysfs.c:power_supply_init_attrs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596395967,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:49",
      "file": "lib/string.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/string.c:strcasecmp",
        "lib/string.c:strcasecmp"
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
  "name": "__tolower",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581106190,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:49",
      "file": "kernel/kallsyms.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kallsyms.c:s_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071581425885,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:49",
      "file": "kernel/debug/kdb/kdb_support.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582863606,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:49",
      "file": "mm/vmscan.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:enabled_store"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583382575,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:49",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:parse_slub_debug_flags"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585851962,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:49",
      "file": "fs/efivarfs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/efivarfs/super.c:efivarfs_d_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589231410,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:49",
      "file": "drivers/acpi/device_sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/device_sysfs.c:create_of_modalias"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589678680,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:49",
      "file": "drivers/acpi/acpica/utnonansi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_stricmp",
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_stricmp",
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_strlwr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589690318,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:49",
      "file": "drivers/acpi/acpica/utstrsuppt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utstrsuppt.c:acpi_ut_detect_hex_prefix"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589713738,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:49",
      "file": "drivers/acpi/acpica/dbinput.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dbinput.c:acpi_db_display_command_info",
        "drivers/acpi/acpica/dbinput.c:acpi_db_display_command_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589856082,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:49",
      "file": "drivers/pnp/card.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/card.c:pnp_alloc_card",
        "drivers/pnp/card.c:pnp_alloc_card",
        "drivers/pnp/card.c:pnp_alloc_card",
        "drivers/pnp/card.c:pnp_alloc_card"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589859453,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:49",
      "file": "drivers/pnp/driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/driver.c:pnp_add_id",
        "drivers/pnp/driver.c:pnp_add_id",
        "drivers/pnp/driver.c:pnp_add_id",
        "drivers/pnp/driver.c:pnp_add_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590306530,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:49",
      "file": "drivers/tty/n_tty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/n_tty.c:n_tty_receive_buf_standard",
        "drivers/tty/n_tty.c:n_tty_receive_buf_standard",
        "drivers/tty/n_tty.c:n_tty_receive_buf_closing"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071593487191,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:49",
      "file": "drivers/power/supply/power_supply_sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/power/supply/power_supply_sysfs.c:power_supply_init_attrs"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071597291199,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:49",
      "file": "lib/string.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/string.c:strcasecmp",
        "lib/string.c:strcasecmp"
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
  "name": "__tolower",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336491493548,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "kernel/kallsyms.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kallsyms.c:s_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336510974452,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:setup_slub_debug"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336494990180,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "fs/efivarfs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/efivarfs/super.c:efivarfs_d_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336496159056,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "lib/hexdump.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336497391880,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "drivers/acpi/device_sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336497615516,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "drivers/acpi/acpica/utnonansi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_stricmp",
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_stricmp",
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_strlwr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497622280,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "drivers/acpi/acpica/utstrsuppt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utstrsuppt.c:acpi_ut_remove_hex_prefix"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497707340,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "drivers/pnp/card.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/card.c:pnp_alloc_card",
        "drivers/pnp/card.c:pnp_alloc_card",
        "drivers/pnp/card.c:pnp_alloc_card",
        "drivers/pnp/card.c:pnp_alloc_card"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336497710200,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "drivers/pnp/driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/driver.c:pnp_add_id",
        "drivers/pnp/driver.c:pnp_add_id",
        "drivers/pnp/driver.c:pnp_add_id",
        "drivers/pnp/driver.c:pnp_add_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336498381184,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "drivers/tty/n_tty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_char_lnext"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336501765028,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "drivers/perf/arm-ccn.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/perf/arm-ccn.c:arm_ccn_pmu_get_cmp_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336503863652,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "lib/string.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/string.c:strcasecmp",
        "lib/string.c:strcasecmp"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "__tolower",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3225475068,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "kernel/kallsyms.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kallsyms.c:s_show"
      ],
      "caller_func": []
    },
    {
      "addr": 3243456068,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:setup_slub_debug"
      ],
      "caller_func": []
    },
    {
      "addr": 3228404308,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "fs/efivarfs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/efivarfs/super.c:efivarfs_d_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 3229479720,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "lib/hexdump.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3231063804,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "drivers/tty/n_tty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_char_lnext"
      ],
      "caller_func": []
    },
    {
      "addr": 3234317564,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "drivers/perf/arm-ccn.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/perf/arm-ccn.c:arm_ccn_pmu_get_cmp_mask"
      ],
      "caller_func": []
    },
    {
      "addr": 3234597364,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "sound/soc/fsl/fsl_ssi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "sound/soc/fsl/fsl_ssi.c:fsl_ssi_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 3236491248,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "lib/string.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/string.c:strcasecmp",
        "lib/string.c:strcasecmp"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "__tolower",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055284450976,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "kernel/kallsyms.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kallsyms.c:s_show"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055302630240,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:setup_slub_debug"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055290422600,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "lib/hexdump.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055291564616,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "drivers/tty/n_tty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_char_lnext"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055297722248,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "lib/string.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/string.c:strcasecmp",
        "lib/string.c:strcasecmp"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "__tolower",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271936954,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "kernel/kallsyms.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kallsyms.c:s_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936270699266,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:setup_slub_debug"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275211324,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "lib/hexdump.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936276049168,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "drivers/tty/n_tty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_char_lnext"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936279759122,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "lib/string.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/string.c:strcasecmp",
        "lib/string.c:strcasecmp"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__tolower",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580220247,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "kernel/kallsyms.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kallsyms.c:s_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604840098,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:setup_slub_debug"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583229428,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "fs/efivarfs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/efivarfs/super.c:efivarfs_d_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584241508,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "lib/hexdump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/hexdump.c:hex2bin",
        "lib/hexdump.c:hex2bin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584926751,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "drivers/acpi/device_sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585137159,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "drivers/acpi/acpica/utnonansi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_stricmp",
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_stricmp",
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_strlwr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585142376,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "drivers/acpi/acpica/utstrsuppt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utstrsuppt.c:acpi_ut_remove_hex_prefix"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585187817,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "drivers/pnp/card.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/card.c:pnp_alloc_card",
        "drivers/pnp/card.c:pnp_alloc_card",
        "drivers/pnp/card.c:pnp_alloc_card",
        "drivers/pnp/card.c:pnp_alloc_card"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585190357,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "drivers/pnp/driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/driver.c:pnp_add_id",
        "drivers/pnp/driver.c:pnp_add_id",
        "drivers/pnp/driver.c:pnp_add_id",
        "drivers/pnp/driver.c:pnp_add_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585462303,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "drivers/tty/n_tty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_char_lnext"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589687981,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "lib/string.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/string.c:strcasecmp",
        "lib/string.c:strcasecmp"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__tolower",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580167687,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "kernel/kallsyms.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kallsyms.c:s_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604809159,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:setup_slub_debug"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583166580,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "fs/efivarfs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/efivarfs/super.c:efivarfs_d_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584176708,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "lib/hexdump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/hexdump.c:hex2bin",
        "lib/hexdump.c:hex2bin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584835487,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "drivers/acpi/device_sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585052399,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "drivers/acpi/acpica/utnonansi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_stricmp",
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_stricmp",
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_strlwr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585057571,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "drivers/acpi/acpica/utstrsuppt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utstrsuppt.c:acpi_ut_remove_hex_prefix"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585140025,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "drivers/pnp/card.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/card.c:pnp_alloc_card",
        "drivers/pnp/card.c:pnp_alloc_card",
        "drivers/pnp/card.c:pnp_alloc_card",
        "drivers/pnp/card.c:pnp_alloc_card"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585142565,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "drivers/pnp/driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/driver.c:pnp_add_id",
        "drivers/pnp/driver.c:pnp_add_id",
        "drivers/pnp/driver.c:pnp_add_id",
        "drivers/pnp/driver.c:pnp_add_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585332335,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "drivers/tty/n_tty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_char_lnext"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589413773,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "lib/string.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/string.c:strcasecmp",
        "lib/string.c:strcasecmp"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__tolower",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580211719,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "kernel/kallsyms.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kallsyms.c:s_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604917282,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:setup_slub_debug"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583213460,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "fs/efivarfs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/efivarfs/super.c:efivarfs_d_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584225268,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "lib/hexdump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/hexdump.c:hex2bin",
        "lib/hexdump.c:hex2bin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584933679,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "drivers/acpi/device_sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585253681,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "drivers/acpi/acpica/utnonansi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_stricmp",
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_stricmp",
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_strlwr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585261662,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "drivers/acpi/acpica/utstrsuppt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utstrsuppt.c:acpi_ut_remove_hex_prefix"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585278284,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "drivers/acpi/acpica/dbinput.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dbinput.c:acpi_db_display_command_info",
        "drivers/acpi/acpica/dbinput.c:acpi_db_display_command_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585375689,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "drivers/pnp/card.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/card.c:pnp_alloc_card",
        "drivers/pnp/card.c:pnp_alloc_card",
        "drivers/pnp/card.c:pnp_alloc_card",
        "drivers/pnp/card.c:pnp_alloc_card"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585378229,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "drivers/pnp/driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/driver.c:pnp_add_id",
        "drivers/pnp/driver.c:pnp_add_id",
        "drivers/pnp/driver.c:pnp_add_id",
        "drivers/pnp/driver.c:pnp_add_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585651679,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "drivers/tty/n_tty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_char_lnext"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590131357,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "lib/string.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/string.c:strcasecmp",
        "lib/string.c:strcasecmp"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__tolower",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580264423,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "kernel/kallsyms.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/kallsyms.c:s_show"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604938809,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "mm/slub.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "mm/slub.c:setup_slub_debug"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583307348,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "fs/efivarfs/super.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "fs/efivarfs/super.c:efivarfs_d_hash"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584330100,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "lib/hexdump.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/hexdump.c:hex2bin",
        "lib/hexdump.c:hex2bin"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585039855,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "drivers/acpi/device_sysfs.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585359841,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "drivers/acpi/acpica/utnonansi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_stricmp",
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_stricmp",
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_strlwr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585367822,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "drivers/acpi/acpica/utstrsuppt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utstrsuppt.c:acpi_ut_remove_hex_prefix"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585384444,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "drivers/acpi/acpica/dbinput.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dbinput.c:acpi_db_display_command_info",
        "drivers/acpi/acpica/dbinput.c:acpi_db_display_command_info"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585483033,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "drivers/pnp/card.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/card.c:pnp_alloc_card",
        "drivers/pnp/card.c:pnp_alloc_card",
        "drivers/pnp/card.c:pnp_alloc_card",
        "drivers/pnp/card.c:pnp_alloc_card"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585485573,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "drivers/pnp/driver.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pnp/driver.c:pnp_add_id",
        "drivers/pnp/driver.c:pnp_add_id",
        "drivers/pnp/driver.c:pnp_add_id",
        "drivers/pnp/driver.c:pnp_add_id"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585759807,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "drivers/tty/n_tty.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_buf_common",
        "drivers/tty/n_tty.c:n_tty_receive_char_lnext"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590181741,
      "name": "__tolower",
      "external": false,
      "loc": "include/linux/ctype.h:42",
      "file": "lib/string.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "lib/string.c:strcasecmp",
        "lib/string.c:strcasecmp"
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
unsigned char __tolower(unsigned char c)
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
unsigned char __tolower(unsigned char c)
```
</details>
</li>
</ul>
