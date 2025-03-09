# Function: <code>strlcat</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
size_t strlcat(char * dest, const char * src, size_t count)
```

```json
{
  "name": "strlcat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582982512,
      "name": "strlcat",
      "external": true,
      "loc": "lib/string.c:294",
      "file": "lib/string.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:do_one_initcall",
        "block/partitions/check.c:check_partition",
        "block/partitions/amiga.c:put_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/cmdline.c:put_partition",
        "block/partitions/cmdline.c:cmdline_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/msdos.c:parse_unixware",
        "block/partitions/msdos.c:parse_unixware",
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/osf.c:osf_partition",
        "block/partitions/osf.c:osf_partition",
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sun.c:sun_partition",
        "block/partitions/sun.c:sun_partition",
        "block/partitions/ultrix.c:ultrix_partition",
        "block/partitions/ultrix.c:ultrix_partition",
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:efi_partition",
        "block/partitions/karma.c:karma_partition",
        "block/partitions/karma.c:karma_partition",
        "block/partitions/sysv68.c:put_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "drivers/char/hw_random/core.c:hwrng_attr_available_show",
        "drivers/char/hw_random/core.c:hwrng_attr_available_show",
        "drivers/char/hw_random/core.c:hwrng_attr_available_show",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582982512,
      "name": "strlcat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
size_t strlcat(char * dest, const char * src, size_t count)
```

```json
{
  "name": "strlcat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583271712,
      "name": "strlcat",
      "external": true,
      "loc": "lib/string.c:294",
      "file": "lib/string.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:do_one_initcall",
        "block/partitions/check.c:check_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:put_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/cmdline.c:cmdline_partition",
        "block/partitions/cmdline.c:put_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_unixware",
        "block/partitions/msdos.c:parse_unixware",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/osf.c:osf_partition",
        "block/partitions/osf.c:osf_partition",
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sun.c:sun_partition",
        "block/partitions/sun.c:sun_partition",
        "block/partitions/ultrix.c:ultrix_partition",
        "block/partitions/ultrix.c:ultrix_partition",
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:efi_partition",
        "block/partitions/karma.c:karma_partition",
        "block/partitions/karma.c:karma_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:put_partition",
        "drivers/acpi/processor_idle.c:flatten_lpi_states",
        "drivers/acpi/processor_idle.c:flatten_lpi_states",
        "drivers/char/hw_random/core.c:hwrng_attr_available_show",
        "drivers/char/hw_random/core.c:hwrng_attr_available_show",
        "drivers/char/hw_random/core.c:hwrng_attr_available_show",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583271712,
      "name": "strlcat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
size_t strlcat(char * dest, const char * src, size_t count)
```

```json
{
  "name": "strlcat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583390480,
      "name": "strlcat",
      "external": true,
      "loc": "lib/string.c:294",
      "file": "lib/string.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:do_one_initcall",
        "block/partitions/check.c:check_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:put_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/cmdline.c:cmdline_partition",
        "block/partitions/cmdline.c:put_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_unixware",
        "block/partitions/msdos.c:parse_unixware",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/osf.c:osf_partition",
        "block/partitions/osf.c:osf_partition",
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sun.c:sun_partition",
        "block/partitions/sun.c:sun_partition",
        "block/partitions/ultrix.c:ultrix_partition",
        "block/partitions/ultrix.c:ultrix_partition",
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:efi_partition",
        "block/partitions/karma.c:karma_partition",
        "block/partitions/karma.c:karma_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:put_partition",
        "drivers/acpi/processor_idle.c:flatten_lpi_states",
        "drivers/acpi/processor_idle.c:flatten_lpi_states",
        "drivers/char/hw_random/core.c:hwrng_attr_available_show",
        "drivers/char/hw_random/core.c:hwrng_attr_available_show",
        "drivers/char/hw_random/core.c:hwrng_attr_available_show",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583390480,
      "name": "strlcat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
size_t strlcat(char * dest, const char * src, size_t count)
```

```json
{
  "name": "strlcat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588246512,
      "name": "strlcat",
      "external": true,
      "loc": "lib/string.c:294",
      "file": "lib/string.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:do_one_initcall",
        "kernel/trace/trace_events.c:event_enable_read",
        "kernel/trace/trace_events.c:event_enable_read",
        "block/partitions/check.c:check_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:put_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/cmdline.c:cmdline_partition",
        "block/partitions/cmdline.c:put_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_unixware",
        "block/partitions/msdos.c:parse_unixware",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/osf.c:osf_partition",
        "block/partitions/osf.c:osf_partition",
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sun.c:sun_partition",
        "block/partitions/sun.c:sun_partition",
        "block/partitions/ultrix.c:ultrix_partition",
        "block/partitions/ultrix.c:ultrix_partition",
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:efi_partition",
        "block/partitions/karma.c:karma_partition",
        "block/partitions/karma.c:karma_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:put_partition",
        "drivers/acpi/processor_idle.c:flatten_lpi_states",
        "drivers/acpi/processor_idle.c:flatten_lpi_states",
        "drivers/char/hw_random/core.c:hwrng_attr_available_show",
        "drivers/char/hw_random/core.c:hwrng_attr_available_show",
        "drivers/char/hw_random/core.c:hwrng_attr_available_show",
        "drivers/usb/host/ehci-hcd.c:ehci_setup",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588246512,
      "name": "strlcat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
size_t strlcat(char * dest, const char * src, size_t count)
```

```json
{
  "name": "strlcat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588797936,
      "name": "strlcat",
      "external": true,
      "loc": "lib/string.c:295",
      "file": "lib/string.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:do_one_initcall",
        "kernel/trace/trace_events.c:event_enable_read",
        "kernel/trace/trace_events.c:event_enable_read",
        "block/partitions/check.c:check_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:put_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/cmdline.c:cmdline_partition",
        "block/partitions/cmdline.c:put_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_unixware",
        "block/partitions/msdos.c:parse_unixware",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/osf.c:osf_partition",
        "block/partitions/osf.c:osf_partition",
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sun.c:sun_partition",
        "block/partitions/sun.c:sun_partition",
        "block/partitions/ultrix.c:ultrix_partition",
        "block/partitions/ultrix.c:ultrix_partition",
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:efi_partition",
        "block/partitions/karma.c:karma_partition",
        "block/partitions/karma.c:karma_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:put_partition",
        "drivers/acpi/processor_idle.c:flatten_lpi_states",
        "drivers/acpi/processor_idle.c:flatten_lpi_states",
        "drivers/char/hw_random/core.c:hwrng_attr_available_show",
        "drivers/char/hw_random/core.c:hwrng_attr_available_show",
        "drivers/char/hw_random/core.c:hwrng_attr_available_show",
        "drivers/usb/host/ehci-hcd.c:ehci_setup",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588797936,
      "name": "strlcat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
size_t strlcat(char * dest, const char * src, size_t count)
```

```json
{
  "name": "strlcat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589176016,
      "name": "strlcat",
      "external": true,
      "loc": "lib/string.c:295",
      "file": "lib/string.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:do_one_initcall",
        "kernel/trace/trace_events.c:event_enable_read",
        "kernel/trace/trace_events.c:event_enable_read",
        "block/partitions/check.c:check_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:put_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/cmdline.c:cmdline_partition",
        "block/partitions/cmdline.c:put_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_unixware",
        "block/partitions/msdos.c:parse_unixware",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/osf.c:osf_partition",
        "block/partitions/osf.c:osf_partition",
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sun.c:sun_partition",
        "block/partitions/sun.c:sun_partition",
        "block/partitions/ultrix.c:ultrix_partition",
        "block/partitions/ultrix.c:ultrix_partition",
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:efi_partition",
        "block/partitions/karma.c:karma_partition",
        "block/partitions/karma.c:karma_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:put_partition",
        "drivers/acpi/processor_idle.c:flatten_lpi_states",
        "drivers/acpi/processor_idle.c:flatten_lpi_states",
        "drivers/char/hw_random/core.c:hwrng_attr_available_show",
        "drivers/char/hw_random/core.c:hwrng_attr_available_show",
        "drivers/char/hw_random/core.c:hwrng_attr_available_show",
        "drivers/usb/host/ehci-hcd.c:ehci_setup",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589176016,
      "name": "strlcat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
size_t strlcat(char * dest, const char * src, size_t count)
```

```json
{
  "name": "strlcat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589405936,
      "name": "strlcat",
      "external": true,
      "loc": "lib/string.c:296",
      "file": "lib/string.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:do_one_initcall",
        "kernel/trace/trace_events.c:event_enable_read",
        "kernel/trace/trace_events.c:event_enable_read",
        "block/partitions/check.c:check_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:put_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/cmdline.c:cmdline_partition",
        "block/partitions/cmdline.c:put_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_unixware",
        "block/partitions/msdos.c:parse_unixware",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/osf.c:osf_partition",
        "block/partitions/osf.c:osf_partition",
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sun.c:sun_partition",
        "block/partitions/sun.c:sun_partition",
        "block/partitions/ultrix.c:ultrix_partition",
        "block/partitions/ultrix.c:ultrix_partition",
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:efi_partition",
        "block/partitions/karma.c:karma_partition",
        "block/partitions/karma.c:karma_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:put_partition",
        "drivers/acpi/processor_idle.c:flatten_lpi_states",
        "drivers/acpi/processor_idle.c:flatten_lpi_states",
        "drivers/char/hw_random/core.c:hwrng_attr_available_show",
        "drivers/char/hw_random/core.c:hwrng_attr_available_show",
        "drivers/char/hw_random/core.c:hwrng_attr_available_show",
        "drivers/usb/host/ehci-hcd.c:ehci_setup",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589405936,
      "name": "strlcat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
size_t strlcat(char * dest, const char * src, size_t count)
```

```json
{
  "name": "strlcat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589861824,
      "name": "strlcat",
      "external": true,
      "loc": "lib/string.c:329",
      "file": "lib/string.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:do_one_initcall",
        "kernel/trace/trace_events.c:event_enable_read",
        "kernel/trace/trace_events.c:event_enable_read",
        "block/partitions/check.c:check_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:put_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/cmdline.c:cmdline_partition",
        "block/partitions/cmdline.c:put_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_unixware",
        "block/partitions/msdos.c:parse_unixware",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/osf.c:osf_partition",
        "block/partitions/osf.c:osf_partition",
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sun.c:sun_partition",
        "block/partitions/sun.c:sun_partition",
        "block/partitions/ultrix.c:ultrix_partition",
        "block/partitions/ultrix.c:ultrix_partition",
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:efi_partition",
        "block/partitions/karma.c:karma_partition",
        "block/partitions/karma.c:karma_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:put_partition",
        "drivers/acpi/processor_idle.c:flatten_lpi_states",
        "drivers/acpi/processor_idle.c:flatten_lpi_states",
        "drivers/char/hw_random/core.c:hwrng_attr_available_show",
        "drivers/char/hw_random/core.c:hwrng_attr_available_show",
        "drivers/char/hw_random/core.c:hwrng_attr_available_show",
        "drivers/usb/host/ehci-hcd.c:ehci_setup",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "net/core/devlink.c:devlink_compat_running_version",
        "net/core/devlink.c:devlink_compat_running_version"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589861824,
      "name": "strlcat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
size_t strlcat(char * dest, const char * src, size_t count)
```

```json
{
  "name": "strlcat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590087616,
      "name": "strlcat",
      "external": true,
      "loc": "lib/string.c:331",
      "file": "lib/string.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:do_one_initcall",
        "kernel/trace/trace_events.c:event_enable_read",
        "kernel/trace/trace_events.c:event_enable_read",
        "block/partitions/check.c:check_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:put_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/cmdline.c:cmdline_partition",
        "block/partitions/cmdline.c:put_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_unixware",
        "block/partitions/msdos.c:parse_unixware",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/osf.c:osf_partition",
        "block/partitions/osf.c:osf_partition",
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sun.c:sun_partition",
        "block/partitions/sun.c:sun_partition",
        "block/partitions/ultrix.c:ultrix_partition",
        "block/partitions/ultrix.c:ultrix_partition",
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:efi_partition",
        "block/partitions/karma.c:karma_partition",
        "block/partitions/karma.c:karma_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:put_partition",
        "drivers/acpi/processor_idle.c:flatten_lpi_states",
        "drivers/acpi/processor_idle.c:flatten_lpi_states",
        "drivers/char/hw_random/core.c:hwrng_attr_available_show",
        "drivers/char/hw_random/core.c:hwrng_attr_available_show",
        "drivers/char/hw_random/core.c:hwrng_attr_available_show",
        "drivers/usb/host/ehci-hcd.c:ehci_setup",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "net/core/devlink.c:devlink_compat_running_version",
        "net/core/devlink.c:devlink_compat_running_version"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590087616,
      "name": "strlcat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
size_t strlcat(char * dest, const char * src, size_t count)
```

```json
{
  "name": "strlcat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585085216,
      "name": "strlcat",
      "external": true,
      "loc": "lib/string.c:355",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:do_one_initcall",
        "kernel/trace/trace_events.c:event_enable_read",
        "kernel/trace/trace_events.c:event_enable_read",
        "block/partitions/core.c:check_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:put_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/cmdline.c:cmdline_partition",
        "block/partitions/cmdline.c:put_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/ldm.c:ldm_create_data_partitions",
        "block/partitions/ldm.c:ldm_create_data_partitions",
        "block/partitions/ldm.c:ldm_create_data_partitions",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_unixware",
        "block/partitions/msdos.c:parse_unixware",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_extended",
        "block/partitions/osf.c:osf_partition",
        "block/partitions/osf.c:osf_partition",
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sun.c:sun_partition",
        "block/partitions/sun.c:sun_partition",
        "block/partitions/ultrix.c:ultrix_partition",
        "block/partitions/ultrix.c:ultrix_partition",
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:efi_partition",
        "block/partitions/karma.c:karma_partition",
        "block/partitions/karma.c:karma_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:put_partition",
        "drivers/char/hw_random/core.c:hwrng_attr_available_show",
        "drivers/char/hw_random/core.c:hwrng_attr_available_show",
        "drivers/char/hw_random/core.c:hwrng_attr_available_show",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "net/core/devlink.c:__devlink_compat_running_version",
        "net/core/devlink.c:__devlink_compat_running_version"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585085216,
      "name": "strlcat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
size_t strlcat(char * dest, const char * src, size_t count)
```

```json
{
  "name": "strlcat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585234352,
      "name": "strlcat",
      "external": true,
      "loc": "lib/string.c:353",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:do_one_initcall",
        "kernel/trace/trace_events.c:event_enable_read",
        "kernel/trace/trace_events.c:event_enable_read",
        "block/partitions/core.c:check_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:put_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/cmdline.c:cmdline_partition",
        "block/partitions/cmdline.c:put_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/ldm.c:ldm_create_data_partitions",
        "block/partitions/ldm.c:ldm_create_data_partitions",
        "block/partitions/ldm.c:ldm_create_data_partitions",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_unixware",
        "block/partitions/msdos.c:parse_unixware",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_extended",
        "block/partitions/osf.c:osf_partition",
        "block/partitions/osf.c:osf_partition",
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sun.c:sun_partition",
        "block/partitions/sun.c:sun_partition",
        "block/partitions/ultrix.c:ultrix_partition",
        "block/partitions/ultrix.c:ultrix_partition",
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:efi_partition",
        "block/partitions/karma.c:karma_partition",
        "block/partitions/karma.c:karma_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:put_partition",
        "drivers/acpi/sysfs.c:acpi_table_attr_init",
        "drivers/char/hw_random/core.c:hwrng_attr_available_show",
        "drivers/char/hw_random/core.c:hwrng_attr_available_show",
        "drivers/char/hw_random/core.c:hwrng_attr_available_show",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "net/core/devlink.c:__devlink_compat_running_version",
        "net/core/devlink.c:__devlink_compat_running_version"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585234352,
      "name": "strlcat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
size_t strlcat(char * dest, const char * src, size_t count)
```

```json
{
  "name": "strlcat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585117184,
      "name": "strlcat",
      "external": true,
      "loc": "lib/string.c:353",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:do_one_initcall",
        "kernel/trace/trace_events.c:event_enable_read",
        "kernel/trace/trace_events.c:event_enable_read",
        "security/selinux/ima.c:selinux_ima_collect_state",
        "security/selinux/ima.c:selinux_ima_collect_state",
        "security/selinux/ima.c:selinux_ima_collect_state",
        "security/selinux/ima.c:selinux_ima_collect_state",
        "security/selinux/ima.c:selinux_ima_collect_state",
        "security/selinux/ima.c:selinux_ima_collect_state",
        "security/selinux/ima.c:selinux_ima_collect_state",
        "block/partitions/core.c:check_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:put_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/cmdline.c:cmdline_partition",
        "block/partitions/cmdline.c:put_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/ldm.c:ldm_create_data_partitions",
        "block/partitions/ldm.c:ldm_create_data_partitions",
        "block/partitions/ldm.c:ldm_create_data_partitions",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_unixware",
        "block/partitions/msdos.c:parse_unixware",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_extended",
        "block/partitions/osf.c:osf_partition",
        "block/partitions/osf.c:osf_partition",
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sun.c:sun_partition",
        "block/partitions/sun.c:sun_partition",
        "block/partitions/ultrix.c:ultrix_partition",
        "block/partitions/ultrix.c:ultrix_partition",
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:efi_partition",
        "block/partitions/karma.c:karma_partition",
        "block/partitions/karma.c:karma_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:put_partition",
        "drivers/acpi/sysfs.c:acpi_table_attr_init",
        "drivers/char/hw_random/core.c:hwrng_attr_available_show",
        "drivers/char/hw_random/core.c:hwrng_attr_available_show",
        "drivers/char/hw_random/core.c:hwrng_attr_available_show",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "net/core/devlink.c:devlink_compat_running_version",
        "net/core/devlink.c:devlink_compat_running_version"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585117184,
      "name": "strlcat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
size_t strlcat(char * dest, const char * src, size_t count)
```

```json
{
  "name": "strlcat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585565904,
      "name": "strlcat",
      "external": true,
      "loc": "lib/string.c:354",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:do_one_initcall",
        "kernel/trace/trace_events.c:event_enable_read",
        "kernel/trace/trace_events.c:event_enable_read",
        "security/selinux/ima.c:selinux_ima_collect_state",
        "security/selinux/ima.c:selinux_ima_collect_state",
        "security/selinux/ima.c:selinux_ima_collect_state",
        "security/selinux/ima.c:selinux_ima_collect_state",
        "security/selinux/ima.c:selinux_ima_collect_state",
        "security/selinux/ima.c:selinux_ima_collect_state",
        "security/selinux/ima.c:selinux_ima_collect_state",
        "block/partitions/core.c:check_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:put_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/cmdline.c:cmdline_partition",
        "block/partitions/cmdline.c:cmdline_partition",
        "block/partitions/cmdline.c:put_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/ldm.c:ldm_create_data_partitions",
        "block/partitions/ldm.c:ldm_create_data_partitions",
        "block/partitions/ldm.c:ldm_create_data_partitions",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_unixware",
        "block/partitions/msdos.c:parse_unixware",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_extended",
        "block/partitions/osf.c:osf_partition",
        "block/partitions/osf.c:osf_partition",
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sun.c:sun_partition",
        "block/partitions/sun.c:sun_partition",
        "block/partitions/ultrix.c:ultrix_partition",
        "block/partitions/ultrix.c:ultrix_partition",
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:efi_partition",
        "block/partitions/karma.c:karma_partition",
        "block/partitions/karma.c:karma_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:put_partition",
        "drivers/acpi/sysfs.c:acpi_table_attr_init",
        "drivers/char/hw_random/core.c:rng_available_show",
        "drivers/char/hw_random/core.c:rng_available_show",
        "drivers/char/hw_random/core.c:rng_available_show",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "net/core/devlink.c:devlink_compat_running_version",
        "net/core/devlink.c:devlink_compat_running_version"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585565904,
      "name": "strlcat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
size_t strlcat(char * dest, const char * src, size_t count)
```

```json
{
  "name": "strlcat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586719344,
      "name": "strlcat",
      "external": true,
      "loc": "lib/string.c:315",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:do_one_initcall",
        "kernel/trace/trace_events.c:event_enable_read",
        "kernel/trace/trace_events.c:event_enable_read",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:find_synthetic_field_var",
        "kernel/trace/trace_events_hist.c:expr_str",
        "kernel/trace/trace_events_hist.c:expr_str",
        "kernel/trace/trace_events_hist.c:expr_str",
        "kernel/trace/trace_events_hist.c:expr_str",
        "kernel/trace/trace_events_hist.c:expr_str",
        "kernel/trace/trace_events_hist.c:expr_str",
        "kernel/trace/trace_events_hist.c:expr_str",
        "kernel/trace/trace_events_hist.c:hist_field_name",
        "kernel/trace/trace_events_hist.c:hist_field_name",
        "kernel/trace/trace_events_hist.c:hist_field_name",
        "kernel/trace/trace_events_hist.c:hist_field_name",
        "kernel/trace/trace_events_hist.c:hist_field_name",
        "security/selinux/ima.c:selinux_ima_collect_state",
        "security/selinux/ima.c:selinux_ima_collect_state",
        "security/selinux/ima.c:selinux_ima_collect_state",
        "security/selinux/ima.c:selinux_ima_collect_state",
        "security/selinux/ima.c:selinux_ima_collect_state",
        "security/selinux/ima.c:selinux_ima_collect_state",
        "security/selinux/ima.c:selinux_ima_collect_state",
        "block/partitions/core.c:check_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:put_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/cmdline.c:cmdline_partition",
        "block/partitions/cmdline.c:cmdline_partition",
        "block/partitions/cmdline.c:put_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/ldm.c:ldm_create_data_partitions",
        "block/partitions/ldm.c:ldm_create_data_partitions",
        "block/partitions/ldm.c:ldm_create_data_partitions",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_unixware",
        "block/partitions/msdos.c:parse_unixware",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_extended",
        "block/partitions/osf.c:osf_partition",
        "block/partitions/osf.c:osf_partition",
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sun.c:sun_partition",
        "block/partitions/sun.c:sun_partition",
        "block/partitions/ultrix.c:ultrix_partition",
        "block/partitions/ultrix.c:ultrix_partition",
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:efi_partition",
        "block/partitions/karma.c:karma_partition",
        "block/partitions/karma.c:karma_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:put_partition",
        "drivers/acpi/sysfs.c:acpi_table_attr_init",
        "drivers/acpi/processor_idle.c:combine_lpi_states",
        "drivers/acpi/processor_idle.c:combine_lpi_states",
        "drivers/char/hw_random/core.c:rng_available_show",
        "drivers/char/hw_random/core.c:rng_available_show",
        "drivers/char/hw_random/core.c:rng_available_show",
        "drivers/nvdimm/namespace_devs.c:__reserve_free_pmem",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "net/core/devlink.c:devlink_compat_running_version",
        "net/core/devlink.c:devlink_compat_running_version"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586719344,
      "name": "strlcat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
size_t strlcat(char * dest, const char * src, size_t count)
```

```json
{
  "name": "strlcat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595881744,
      "name": "strlcat",
      "external": true,
      "loc": "lib/string.c:250",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:do_one_initcall",
        "kernel/trace/trace_events.c:event_enable_read",
        "kernel/trace/trace_events.c:event_enable_read",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:find_synthetic_field_var",
        "kernel/trace/trace_events_hist.c:expr_str",
        "kernel/trace/trace_events_hist.c:expr_str",
        "kernel/trace/trace_events_hist.c:expr_str",
        "kernel/trace/trace_events_hist.c:expr_str",
        "kernel/trace/trace_events_hist.c:expr_str",
        "kernel/trace/trace_events_hist.c:expr_str",
        "kernel/trace/trace_events_hist.c:expr_str",
        "kernel/trace/trace_events_hist.c:hist_field_name",
        "kernel/trace/trace_events_hist.c:hist_field_name",
        "kernel/trace/trace_events_hist.c:hist_field_name",
        "kernel/trace/trace_events_hist.c:hist_field_name",
        "kernel/trace/trace_events_hist.c:hist_field_name",
        "security/selinux/ima.c:selinux_ima_collect_state",
        "security/selinux/ima.c:selinux_ima_collect_state",
        "security/selinux/ima.c:selinux_ima_collect_state",
        "security/selinux/ima.c:selinux_ima_collect_state",
        "security/selinux/ima.c:selinux_ima_collect_state",
        "security/selinux/ima.c:selinux_ima_collect_state",
        "security/selinux/ima.c:selinux_ima_collect_state",
        "block/partitions/core.c:check_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:put_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/cmdline.c:cmdline_partition",
        "block/partitions/cmdline.c:cmdline_partition",
        "block/partitions/cmdline.c:put_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/ldm.c:ldm_create_data_partitions",
        "block/partitions/ldm.c:ldm_create_data_partitions",
        "block/partitions/ldm.c:ldm_create_data_partitions",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_unixware",
        "block/partitions/msdos.c:parse_unixware",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_extended",
        "block/partitions/osf.c:osf_partition",
        "block/partitions/osf.c:osf_partition",
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sun.c:sun_partition",
        "block/partitions/sun.c:sun_partition",
        "block/partitions/ultrix.c:ultrix_partition",
        "block/partitions/ultrix.c:ultrix_partition",
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:efi_partition",
        "block/partitions/karma.c:karma_partition",
        "block/partitions/karma.c:karma_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:put_partition",
        "drivers/acpi/sysfs.c:acpi_table_attr_init",
        "drivers/acpi/processor_idle.c:combine_lpi_states",
        "drivers/acpi/processor_idle.c:combine_lpi_states",
        "drivers/char/hw_random/core.c:rng_available_show",
        "drivers/char/hw_random/core.c:rng_available_show",
        "drivers/char/hw_random/core.c:rng_available_show",
        "drivers/nvdimm/namespace_devs.c:__reserve_free_pmem",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "net/core/devlink.c:devlink_compat_running_version",
        "net/core/devlink.c:devlink_compat_running_version"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595881744,
      "name": "strlcat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
size_t strlcat(const char * p, const const char * q, size_t avail)
```

```json
{
  "name": "strlcat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578851858,
      "name": "strlcat",
      "external": true,
      "loc": "include/linux/fortify-string.h:374",
      "file": "init/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/main.c:do_one_initcall",
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:show_trigger",
        "kernel/trace/trace_events.c:event_enable_read",
        "kernel/trace/trace_events.c:event_enable_read",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:find_synthetic_field_var",
        "kernel/trace/trace_events_hist.c:expr_str",
        "kernel/trace/trace_events_hist.c:expr_str",
        "kernel/trace/trace_events_hist.c:expr_str",
        "kernel/trace/trace_events_hist.c:expr_str",
        "kernel/trace/trace_events_hist.c:expr_str",
        "kernel/trace/trace_events_hist.c:expr_str",
        "kernel/trace/trace_events_hist.c:expr_str",
        "kernel/trace/trace_events_hist.c:expr_field_str",
        "kernel/trace/trace_events_hist.c:expr_field_str",
        "kernel/trace/trace_events_hist.c:expr_field_str",
        "kernel/trace/trace_events_hist.c:expr_field_str",
        "kernel/trace/trace_events_hist.c:expr_field_str",
        "kernel/trace/trace_events_hist.c:hist_field_name",
        "kernel/trace/trace_events_hist.c:hist_field_name",
        "kernel/trace/trace_events_hist.c:hist_field_name",
        "kernel/trace/trace_events_hist.c:hist_field_name",
        "kernel/trace/trace_events_hist.c:hist_field_name",
        "security/selinux/ima.c:selinux_ima_collect_state",
        "security/selinux/ima.c:selinux_ima_collect_state",
        "security/selinux/ima.c:selinux_ima_collect_state",
        "security/selinux/ima.c:selinux_ima_collect_state",
        "security/selinux/ima.c:selinux_ima_collect_state",
        "security/selinux/ima.c:selinux_ima_collect_state",
        "security/selinux/ima.c:selinux_ima_collect_state",
        "block/partitions/core.c:check_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:put_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:put_partition",
        "block/partitions/cmdline.c:cmdline_partition",
        "block/partitions/cmdline.c:add_part",
        "block/partitions/cmdline.c:put_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:put_partition",
        "block/partitions/ldm.c:ldm_create_data_partitions",
        "block/partitions/ldm.c:ldm_create_data_partitions",
        "block/partitions/ldm.c:put_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_unixware",
        "block/partitions/msdos.c:parse_unixware",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/osf.c:osf_partition",
        "block/partitions/osf.c:put_partition",
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sgi.c:put_partition",
        "block/partitions/sun.c:sun_partition",
        "block/partitions/sun.c:put_partition",
        "block/partitions/ultrix.c:ultrix_partition",
        "block/partitions/ultrix.c:put_partition",
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:put_partition",
        "block/partitions/karma.c:karma_partition",
        "block/partitions/karma.c:put_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:put_partition",
        "drivers/acpi/sysfs.c:acpi_table_attr_init",
        "drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate",
        "drivers/acpi/acpica/exnames.c:acpi_ex_name_segment",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname",
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_safe_strcat",
        "drivers/acpi/acpica/utpredef.c:acpi_ut_get_expected_return_types",
        "drivers/acpi/processor_idle.c:combine_lpi_states",
        "drivers/acpi/processor_idle.c:combine_lpi_states",
        "drivers/char/hw_random/core.c:rng_available_show",
        "drivers/char/hw_random/core.c:rng_available_show",
        "drivers/char/hw_random/core.c:rng_available_show",
        "drivers/nvdimm/namespace_devs.c:__reserve_free_pmem",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/md/dm-sysfs.c:dm_attr_uuid_show",
        "drivers/md/dm-sysfs.c:dm_attr_name_show",
        "net/devlink/dev.c:__devlink_compat_running_version",
        "net/devlink/dev.c:__devlink_compat_running_version"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596398992,
      "name": "strlcat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
size_t strlcat(const char * p, const const char * q, size_t avail)
```

```json
{
  "name": "strlcat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578851877,
      "name": "strlcat",
      "external": true,
      "loc": "include/linux/fortify-string.h:319",
      "file": "init/main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "init/main.c:do_one_initcall",
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:show_trigger",
        "kernel/trace/trace_events.c:event_enable_read",
        "kernel/trace/trace_events.c:event_enable_read",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:create_field_var_hist",
        "kernel/trace/trace_events_hist.c:find_synthetic_field_var",
        "kernel/trace/trace_events_hist.c:expr_str",
        "kernel/trace/trace_events_hist.c:expr_str",
        "kernel/trace/trace_events_hist.c:expr_str",
        "kernel/trace/trace_events_hist.c:expr_str",
        "kernel/trace/trace_events_hist.c:expr_str",
        "kernel/trace/trace_events_hist.c:expr_str",
        "kernel/trace/trace_events_hist.c:expr_str",
        "kernel/trace/trace_events_hist.c:expr_field_str",
        "kernel/trace/trace_events_hist.c:expr_field_str",
        "kernel/trace/trace_events_hist.c:expr_field_str",
        "kernel/trace/trace_events_hist.c:expr_field_str",
        "kernel/trace/trace_events_hist.c:expr_field_str",
        "kernel/trace/trace_events_hist.c:hist_field_name",
        "kernel/trace/trace_events_hist.c:hist_field_name",
        "kernel/trace/trace_events_hist.c:hist_field_name",
        "kernel/trace/trace_events_hist.c:hist_field_name",
        "kernel/trace/trace_events_hist.c:hist_field_name",
        "security/selinux/ima.c:selinux_ima_collect_state",
        "security/selinux/ima.c:selinux_ima_collect_state",
        "security/selinux/ima.c:selinux_ima_collect_state",
        "security/selinux/ima.c:selinux_ima_collect_state",
        "security/selinux/ima.c:selinux_ima_collect_state",
        "security/selinux/ima.c:selinux_ima_collect_state",
        "security/selinux/ima.c:selinux_ima_collect_state",
        "block/partitions/core.c:check_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:put_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:put_partition",
        "block/partitions/cmdline.c:cmdline_partition",
        "block/partitions/cmdline.c:add_part",
        "block/partitions/cmdline.c:put_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:put_partition",
        "block/partitions/ldm.c:ldm_create_data_partitions",
        "block/partitions/ldm.c:ldm_create_data_partitions",
        "block/partitions/ldm.c:put_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_unixware",
        "block/partitions/msdos.c:parse_unixware",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/osf.c:osf_partition",
        "block/partitions/osf.c:put_partition",
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sgi.c:put_partition",
        "block/partitions/sun.c:sun_partition",
        "block/partitions/sun.c:put_partition",
        "block/partitions/ultrix.c:ultrix_partition",
        "block/partitions/ultrix.c:put_partition",
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:put_partition",
        "block/partitions/karma.c:karma_partition",
        "block/partitions/karma.c:put_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:put_partition",
        "drivers/acpi/sysfs.c:acpi_table_attr_init",
        "drivers/acpi/acpica/exconcat.c:acpi_ex_do_concatenate",
        "drivers/acpi/acpica/exnames.c:acpi_ex_name_segment",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname",
        "drivers/acpi/acpica/nsnames.c:acpi_ns_build_prefixed_pathname",
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_safe_strcat",
        "drivers/acpi/acpica/utpredef.c:acpi_ut_get_expected_return_types",
        "drivers/acpi/processor_idle.c:combine_lpi_states",
        "drivers/acpi/processor_idle.c:combine_lpi_states",
        "drivers/char/hw_random/core.c:rng_available_show",
        "drivers/char/hw_random/core.c:rng_available_show",
        "drivers/char/hw_random/core.c:rng_available_show",
        "drivers/nvdimm/namespace_devs.c:__reserve_free_pmem",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/md/dm-sysfs.c:dm_attr_uuid_show",
        "drivers/md/dm-sysfs.c:dm_attr_name_show",
        "net/devlink/dev.c:__devlink_compat_running_version",
        "net/devlink/dev.c:__devlink_compat_running_version"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597294096,
      "name": "strlcat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
size_t strlcat(char * dest, const char * src, size_t count)
```

```json
{
  "name": "strlcat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503865584,
      "name": "strlcat",
      "external": true,
      "loc": "lib/string.c:331",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:do_one_initcall",
        "kernel/trace/trace_events.c:event_enable_read",
        "kernel/trace/trace_events.c:event_enable_read",
        "block/partitions/check.c:check_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:put_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/cmdline.c:cmdline_partition",
        "block/partitions/cmdline.c:put_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_unixware",
        "block/partitions/msdos.c:parse_unixware",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/osf.c:osf_partition",
        "block/partitions/osf.c:osf_partition",
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sun.c:sun_partition",
        "block/partitions/sun.c:sun_partition",
        "block/partitions/ultrix.c:ultrix_partition",
        "block/partitions/ultrix.c:ultrix_partition",
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:efi_partition",
        "block/partitions/karma.c:karma_partition",
        "block/partitions/karma.c:karma_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:put_partition",
        "drivers/acpi/processor_idle.c:flatten_lpi_states",
        "drivers/acpi/processor_idle.c:flatten_lpi_states",
        "drivers/char/hw_random/core.c:hwrng_attr_available_show",
        "drivers/char/hw_random/core.c:hwrng_attr_available_show",
        "drivers/char/hw_random/core.c:hwrng_attr_available_show",
        "drivers/usb/host/ehci-hcd.c:ehci_setup",
        "net/core/devlink.c:devlink_compat_running_version",
        "net/core/devlink.c:devlink_compat_running_version"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503865584,
      "name": "strlcat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
size_t strlcat(char * dest, const char * src, size_t count)
```

```json
{
  "name": "strlcat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3236493588,
      "name": "strlcat",
      "external": true,
      "loc": "lib/string.c:331",
      "file": "lib/string.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:do_one_initcall",
        "kernel/trace/trace_events.c:event_enable_read",
        "kernel/trace/trace_events.c:event_enable_read",
        "block/partitions/check.c:check_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:put_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/cmdline.c:cmdline_partition",
        "block/partitions/cmdline.c:put_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_unixware",
        "block/partitions/msdos.c:parse_unixware",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/osf.c:osf_partition",
        "block/partitions/osf.c:osf_partition",
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sun.c:sun_partition",
        "block/partitions/sun.c:sun_partition",
        "block/partitions/ultrix.c:ultrix_partition",
        "block/partitions/ultrix.c:ultrix_partition",
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:efi_partition",
        "block/partitions/karma.c:karma_partition",
        "block/partitions/karma.c:karma_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:put_partition",
        "drivers/char/hw_random/core.c:hwrng_attr_available_show",
        "drivers/char/hw_random/core.c:hwrng_attr_available_show",
        "drivers/char/hw_random/core.c:hwrng_attr_available_show",
        "drivers/usb/host/ehci-hcd.c:ehci_setup",
        "drivers/usb/musb/musb_core.c:musb_core_init",
        "drivers/usb/musb/musb_core.c:musb_core_init",
        "drivers/usb/musb/musb_core.c:musb_core_init",
        "drivers/usb/musb/musb_core.c:musb_core_init",
        "drivers/usb/musb/musb_core.c:musb_core_init",
        "drivers/usb/musb/musb_core.c:musb_core_init",
        "sound/sound_core.c:register_sound_special_device",
        "net/core/devlink.c:devlink_compat_running_version",
        "net/core/devlink.c:devlink_compat_running_version"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236493588,
      "name": "strlcat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
size_t strlcat(char * dest, const char * src, size_t count)
```

```json
{
  "name": "strlcat",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297724848,
      "name": "strlcat",
      "external": true,
      "loc": "lib/string.c:331",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:do_one_initcall",
        "kernel/trace/trace_events.c:event_enable_read",
        "kernel/trace/trace_events.c:event_enable_read",
        "block/partitions/check.c:check_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:put_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/cmdline.c:cmdline_partition",
        "block/partitions/cmdline.c:put_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_unixware",
        "block/partitions/msdos.c:parse_unixware",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/osf.c:osf_partition",
        "block/partitions/osf.c:osf_partition",
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sun.c:sun_partition",
        "block/partitions/sun.c:sun_partition",
        "block/partitions/ultrix.c:ultrix_partition",
        "block/partitions/ultrix.c:ultrix_partition",
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:efi_partition",
        "block/partitions/karma.c:karma_partition",
        "block/partitions/karma.c:karma_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:put_partition",
        "drivers/char/hw_random/core.c:hwrng_attr_available_show",
        "drivers/char/hw_random/core.c:hwrng_attr_available_show",
        "drivers/char/hw_random/core.c:hwrng_attr_available_show",
        "drivers/usb/host/ehci-hcd.c:ehci_setup",
        "net/core/devlink.c:devlink_compat_running_version",
        "net/core/devlink.c:devlink_compat_running_version"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297724848,
      "name": "strlcat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
size_t strlcat(char * dest, const char * src, size_t count)
```

```json
{
  "name": "strlcat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936279761778,
      "name": "strlcat",
      "external": true,
      "loc": "lib/string.c:331",
      "file": "lib/string.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:do_one_initcall",
        "block/partitions/check.c:check_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:put_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/cmdline.c:cmdline_partition",
        "block/partitions/cmdline.c:put_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_unixware",
        "block/partitions/msdos.c:parse_unixware",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/osf.c:osf_partition",
        "block/partitions/osf.c:osf_partition",
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sun.c:sun_partition",
        "block/partitions/sun.c:sun_partition",
        "block/partitions/ultrix.c:ultrix_partition",
        "block/partitions/ultrix.c:ultrix_partition",
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:efi_partition",
        "block/partitions/karma.c:karma_partition",
        "block/partitions/karma.c:karma_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:put_partition",
        "drivers/char/hw_random/core.c:hwrng_attr_available_show",
        "drivers/char/hw_random/core.c:hwrng_attr_available_show",
        "drivers/char/hw_random/core.c:hwrng_attr_available_show",
        "net/core/devlink.c:devlink_compat_running_version",
        "net/core/devlink.c:devlink_compat_running_version"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279761778,
      "name": "strlcat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
size_t strlcat(char * dest, const char * src, size_t count)
```

```json
{
  "name": "strlcat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589689872,
      "name": "strlcat",
      "external": true,
      "loc": "lib/string.c:331",
      "file": "lib/string.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:do_one_initcall",
        "kernel/trace/trace_events.c:event_enable_read",
        "kernel/trace/trace_events.c:event_enable_read",
        "block/partitions/check.c:check_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:put_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/cmdline.c:cmdline_partition",
        "block/partitions/cmdline.c:put_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_unixware",
        "block/partitions/msdos.c:parse_unixware",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/osf.c:osf_partition",
        "block/partitions/osf.c:osf_partition",
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sun.c:sun_partition",
        "block/partitions/sun.c:sun_partition",
        "block/partitions/ultrix.c:ultrix_partition",
        "block/partitions/ultrix.c:ultrix_partition",
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:efi_partition",
        "block/partitions/karma.c:karma_partition",
        "block/partitions/karma.c:karma_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:put_partition",
        "drivers/acpi/processor_idle.c:flatten_lpi_states",
        "drivers/acpi/processor_idle.c:flatten_lpi_states",
        "drivers/char/hw_random/core.c:hwrng_attr_available_show",
        "drivers/char/hw_random/core.c:hwrng_attr_available_show",
        "drivers/char/hw_random/core.c:hwrng_attr_available_show",
        "drivers/usb/host/ehci-hcd.c:ehci_setup",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "net/core/devlink.c:devlink_compat_running_version",
        "net/core/devlink.c:devlink_compat_running_version"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589689872,
      "name": "strlcat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
size_t strlcat(char * dest, const char * src, size_t count)
```

```json
{
  "name": "strlcat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589415664,
      "name": "strlcat",
      "external": true,
      "loc": "lib/string.c:331",
      "file": "lib/string.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:do_one_initcall",
        "kernel/trace/trace_events.c:event_enable_read",
        "kernel/trace/trace_events.c:event_enable_read",
        "block/partitions/check.c:check_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:put_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/cmdline.c:cmdline_partition",
        "block/partitions/cmdline.c:put_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_unixware",
        "block/partitions/msdos.c:parse_unixware",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/osf.c:osf_partition",
        "block/partitions/osf.c:osf_partition",
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sun.c:sun_partition",
        "block/partitions/sun.c:sun_partition",
        "block/partitions/ultrix.c:ultrix_partition",
        "block/partitions/ultrix.c:ultrix_partition",
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:efi_partition",
        "block/partitions/karma.c:karma_partition",
        "block/partitions/karma.c:karma_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:put_partition",
        "drivers/acpi/processor_idle.c:flatten_lpi_states",
        "drivers/acpi/processor_idle.c:flatten_lpi_states",
        "drivers/char/hw_random/core.c:hwrng_attr_available_show",
        "drivers/char/hw_random/core.c:hwrng_attr_available_show",
        "drivers/char/hw_random/core.c:hwrng_attr_available_show",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "net/core/devlink.c:devlink_compat_running_version",
        "net/core/devlink.c:devlink_compat_running_version",
        "net/ipv4/ip_tunnel.c:__ip_tunnel_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589415664,
      "name": "strlcat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
size_t strlcat(char * dest, const char * src, size_t count)
```

```json
{
  "name": "strlcat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590133248,
      "name": "strlcat",
      "external": true,
      "loc": "lib/string.c:331",
      "file": "lib/string.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:do_one_initcall",
        "kernel/trace/trace_events.c:event_enable_read",
        "kernel/trace/trace_events.c:event_enable_read",
        "block/partitions/check.c:check_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:put_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/cmdline.c:cmdline_partition",
        "block/partitions/cmdline.c:put_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_unixware",
        "block/partitions/msdos.c:parse_unixware",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/osf.c:osf_partition",
        "block/partitions/osf.c:osf_partition",
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sun.c:sun_partition",
        "block/partitions/sun.c:sun_partition",
        "block/partitions/ultrix.c:ultrix_partition",
        "block/partitions/ultrix.c:ultrix_partition",
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:efi_partition",
        "block/partitions/karma.c:karma_partition",
        "block/partitions/karma.c:karma_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:put_partition",
        "drivers/acpi/processor_idle.c:flatten_lpi_states",
        "drivers/acpi/processor_idle.c:flatten_lpi_states",
        "drivers/char/hw_random/core.c:hwrng_attr_available_show",
        "drivers/char/hw_random/core.c:hwrng_attr_available_show",
        "drivers/char/hw_random/core.c:hwrng_attr_available_show",
        "drivers/usb/host/ehci-hcd.c:ehci_setup",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "net/core/devlink.c:devlink_compat_running_version",
        "net/core/devlink.c:devlink_compat_running_version"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590133248,
      "name": "strlcat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
size_t strlcat(char * dest, const char * src, size_t count)
```

```json
{
  "name": "strlcat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590183632,
      "name": "strlcat",
      "external": true,
      "loc": "lib/string.c:331",
      "file": "lib/string.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:do_one_initcall",
        "kernel/trace/trace_events.c:event_enable_read",
        "kernel/trace/trace_events.c:event_enable_read",
        "block/partitions/check.c:check_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:amiga_partition",
        "block/partitions/amiga.c:put_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/atari.c:atari_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/aix.c:aix_partition",
        "block/partitions/cmdline.c:cmdline_partition",
        "block/partitions/cmdline.c:put_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/mac.c:mac_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:msdos_partition",
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_minix",
        "block/partitions/msdos.c:parse_unixware",
        "block/partitions/msdos.c:parse_unixware",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/msdos.c:parse_solaris_x86",
        "block/partitions/osf.c:osf_partition",
        "block/partitions/osf.c:osf_partition",
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sgi.c:sgi_partition",
        "block/partitions/sun.c:sun_partition",
        "block/partitions/sun.c:sun_partition",
        "block/partitions/ultrix.c:ultrix_partition",
        "block/partitions/ultrix.c:ultrix_partition",
        "block/partitions/efi.c:efi_partition",
        "block/partitions/efi.c:efi_partition",
        "block/partitions/karma.c:karma_partition",
        "block/partitions/karma.c:karma_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:sysv68_partition",
        "block/partitions/sysv68.c:put_partition",
        "drivers/acpi/processor_idle.c:flatten_lpi_states",
        "drivers/acpi/processor_idle.c:flatten_lpi_states",
        "drivers/char/hw_random/core.c:hwrng_attr_available_show",
        "drivers/char/hw_random/core.c:hwrng_attr_available_show",
        "drivers/char/hw_random/core.c:hwrng_attr_available_show",
        "drivers/usb/host/ehci-hcd.c:ehci_setup",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_aux_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "drivers/input/serio/i8042.c:i8042_pnp_kbd_probe",
        "net/core/devlink.c:devlink_compat_running_version",
        "net/core/devlink.c:devlink_compat_running_version"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590183632,
      "name": "strlcat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const char * p</code>
</li>
<li>
<b>Param added. </b>
<code>const const char * q</code>
</li>
<li>
<b>Param added. </b>
<code>size_t avail</code>
</li>
<li>
<b>Param removed. </b>
<code>char * dest</code>
</li>
<li>
<b>Param removed. </b>
<code>const char * src</code>
</li>
<li>
<b>Param removed. </b>
<code>size_t count</code>
</li>
</ul>
</details>
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
