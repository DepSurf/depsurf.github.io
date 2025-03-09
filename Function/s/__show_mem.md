# Function: <code>__show_mem</code>

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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void __show_mem(unsigned int filter, nodemask_t * nodemask, int max_zone_idx)
```

```json
{
  "name": "__show_mem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595872016,
      "name": "__show_mem",
      "external": true,
      "loc": "lib/show_mem.c:11",
      "file": "lib/show_mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:panic_show_mem",
        "mm/oom_kill.c:dump_header",
        "mm/page_alloc.c:warn_alloc",
        "drivers/tty/sysrq.c:sysrq_handle_showmem",
        "drivers/tty/vt/keyboard.c:fn_show_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595872016,
      "name": "__show_mem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 255
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
void __show_mem(unsigned int filter, nodemask_t * nodemask, int max_zone_idx)
```

```json
{
  "name": "__show_mem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582903168,
      "name": "__show_mem",
      "external": true,
      "loc": "mm/show_mem.c:403",
      "file": "mm/show_mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:do_populate_rootfs",
        "init/initramfs.c:unpack_to_rootfs",
        "init/initramfs.c:dir_add",
        "init/initramfs.c:find_link",
        "mm/oom_kill.c:dump_header",
        "mm/page_alloc.c:warn_alloc",
        "drivers/tty/sysrq.c:sysrq_handle_showmem",
        "drivers/tty/vt/keyboard.c:fn_show_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582903168,
      "name": "__show_mem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
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
void __show_mem(unsigned int filter, nodemask_t * nodemask, int max_zone_idx)
```

```json
{
  "name": "__show_mem",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583074896,
      "name": "__show_mem",
      "external": true,
      "loc": "mm/show_mem.c:400",
      "file": "mm/show_mem.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/initramfs.c:do_populate_rootfs",
        "init/initramfs.c:unpack_to_rootfs",
        "init/initramfs.c:dir_add",
        "init/initramfs.c:find_link",
        "mm/oom_kill.c:dump_header",
        "mm/page_alloc.c:warn_alloc",
        "drivers/tty/sysrq.c:sysrq_handle_showmem",
        "drivers/tty/vt/keyboard.c:fn_show_mem"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583074896,
      "name": "__show_mem",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
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
void __show_mem(unsigned int filter, nodemask_t * nodemask, int max_zone_idx)
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
