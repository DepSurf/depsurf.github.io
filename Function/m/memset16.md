# Function: <code>memset16</code>

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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "memset16",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584195684,
      "name": "memset16",
      "external": false,
      "loc": "arch/x86/include/asm/string_64.h:55",
      "file": "drivers/video/console/vgacon.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584253929,
      "name": "memset16",
      "external": false,
      "loc": "arch/x86/include/asm/string_64.h:55",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585078948,
      "name": "memset16",
      "external": false,
      "loc": "arch/x86/include/asm/string_64.h:55",
      "file": "drivers/tty/vt/vt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:csi_J",
        "drivers/tty/vt/vt.c:csi_J",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:insert_char",
        "drivers/tty/vt/vt.c:con_scroll"
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
  "name": "memset16",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584415805,
      "name": "memset16",
      "external": false,
      "loc": "arch/x86/include/asm/string_64.h:55",
      "file": "drivers/video/console/vgacon.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584477004,
      "name": "memset16",
      "external": false,
      "loc": "arch/x86/include/asm/string_64.h:55",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585311503,
      "name": "memset16",
      "external": false,
      "loc": "arch/x86/include/asm/string_64.h:55",
      "file": "drivers/tty/vt/vt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:csi_J",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:insert_char",
        "drivers/tty/vt/vt.c:con_scroll"
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
  "name": "memset16",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584512231,
      "name": "memset16",
      "external": false,
      "loc": "arch/x86/include/asm/string_64.h:37",
      "file": "drivers/video/console/vgacon.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584570269,
      "name": "memset16",
      "external": false,
      "loc": "arch/x86/include/asm/string_64.h:37",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585435854,
      "name": "memset16",
      "external": false,
      "loc": "arch/x86/include/asm/string_64.h:37",
      "file": "drivers/tty/vt/vt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:csi_J",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:insert_char",
        "drivers/tty/vt/vt.c:con_scroll"
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
  "name": "memset16",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584711200,
      "name": "memset16",
      "external": false,
      "loc": "arch/x86/include/asm/string_64.h:22",
      "file": "drivers/video/console/vgacon.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584767628,
      "name": "memset16",
      "external": false,
      "loc": "arch/x86/include/asm/string_64.h:22",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585651463,
      "name": "memset16",
      "external": false,
      "loc": "arch/x86/include/asm/string_64.h:22",
      "file": "drivers/tty/vt/vt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:csi_J",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:insert_char",
        "drivers/tty/vt/vt.c:con_scroll"
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
  "name": "memset16",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584847296,
      "name": "memset16",
      "external": false,
      "loc": "arch/x86/include/asm/string_64.h:22",
      "file": "drivers/video/console/vgacon.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584902492,
      "name": "memset16",
      "external": false,
      "loc": "arch/x86/include/asm/string_64.h:22",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585792772,
      "name": "memset16",
      "external": false,
      "loc": "arch/x86/include/asm/string_64.h:22",
      "file": "drivers/tty/vt/vt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:csi_J",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:insert_char",
        "drivers/tty/vt/vt.c:con_scroll"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "memset16",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585548901,
      "name": "memset16",
      "external": false,
      "loc": "arch/x86/include/asm/string_64.h:22",
      "file": "drivers/video/console/vgacon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/console/vgacon.c:vgacon_blank"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585594754,
      "name": "memset16",
      "external": false,
      "loc": "arch/x86/include/asm/string_64.h:22",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586524666,
      "name": "memset16",
      "external": false,
      "loc": "arch/x86/include/asm/string_64.h:22",
      "file": "drivers/tty/vt/vt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:csi_P",
        "drivers/tty/vt/vt.c:csi_J",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:insert_char",
        "drivers/tty/vt/vt.c:con_scroll"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "memset16",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585683189,
      "name": "memset16",
      "external": false,
      "loc": "arch/x86/include/asm/string_64.h:22",
      "file": "drivers/video/console/vgacon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/console/vgacon.c:vgacon_blank"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585727136,
      "name": "memset16",
      "external": false,
      "loc": "arch/x86/include/asm/string_64.h:22",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586637671,
      "name": "memset16",
      "external": false,
      "loc": "arch/x86/include/asm/string_64.h:22",
      "file": "drivers/tty/vt/vt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:csi_P",
        "drivers/tty/vt/vt.c:csi_J",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:insert_char",
        "drivers/tty/vt/vt.c:con_scroll"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "memset16",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585562007,
      "name": "memset16",
      "external": false,
      "loc": "arch/x86/include/asm/string_64.h:22",
      "file": "drivers/video/console/vgacon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/console/vgacon.c:vgacon_blank"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585607592,
      "name": "memset16",
      "external": false,
      "loc": "arch/x86/include/asm/string_64.h:22",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586521805,
      "name": "memset16",
      "external": false,
      "loc": "arch/x86/include/asm/string_64.h:22",
      "file": "drivers/tty/vt/vt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:csi_J",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:insert_char",
        "drivers/tty/vt/vt.c:con_scroll"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "memset16",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586033655,
      "name": "memset16",
      "external": false,
      "loc": "arch/x86/include/asm/string_64.h:22",
      "file": "drivers/video/console/vgacon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/console/vgacon.c:vgacon_blank"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586086918,
      "name": "memset16",
      "external": false,
      "loc": "arch/x86/include/asm/string_64.h:22",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587058907,
      "name": "memset16",
      "external": false,
      "loc": "arch/x86/include/asm/string_64.h:22",
      "file": "drivers/tty/vt/vt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:csi_J",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:insert_char",
        "drivers/tty/vt/vt.c:con_scroll"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "memset16",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587246410,
      "name": "memset16",
      "external": false,
      "loc": "arch/x86/include/asm/string_64.h:22",
      "file": "drivers/video/console/vgacon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/console/vgacon.c:vgacon_scroll",
        "drivers/video/console/vgacon.c:vgacon_scroll",
        "drivers/video/console/vgacon.c:vgacon_blank"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587311372,
      "name": "memset16",
      "external": false,
      "loc": "arch/x86/include/asm/string_64.h:22",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588361451,
      "name": "memset16",
      "external": false,
      "loc": "arch/x86/include/asm/string_64.h:22",
      "file": "drivers/tty/vt/vt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:csi_J",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:insert_char",
        "drivers/tty/vt/vt.c:con_scroll"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "memset16",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588485322,
      "name": "memset16",
      "external": false,
      "loc": "arch/x86/include/asm/string_64.h:37",
      "file": "drivers/video/console/vgacon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/console/vgacon.c:vgacon_scroll",
        "drivers/video/console/vgacon.c:vgacon_scroll",
        "drivers/video/console/vgacon.c:vgacon_blank"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588552668,
      "name": "memset16",
      "external": false,
      "loc": "arch/x86/include/asm/string_64.h:37",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589782656,
      "name": "memset16",
      "external": false,
      "loc": "arch/x86/include/asm/string_64.h:37",
      "file": "drivers/tty/vt/vt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:csi_J",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:insert_char",
        "drivers/tty/vt/vt.c:con_scroll"
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
  "name": "memset16",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588764986,
      "name": "memset16",
      "external": false,
      "loc": "arch/x86/include/asm/string_64.h:31",
      "file": "drivers/video/console/vgacon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/console/vgacon.c:vgacon_scroll",
        "drivers/video/console/vgacon.c:vgacon_scroll",
        "drivers/video/console/vgacon.c:vgacon_blank"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588832700,
      "name": "memset16",
      "external": false,
      "loc": "arch/x86/include/asm/string_64.h:31",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590086896,
      "name": "memset16",
      "external": false,
      "loc": "arch/x86/include/asm/string_64.h:31",
      "file": "drivers/tty/vt/vt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:csi_J",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:insert_char",
        "drivers/tty/vt/vt.c:con_scroll"
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
  "name": "memset16",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589068202,
      "name": "memset16",
      "external": false,
      "loc": "arch/x86/include/asm/string_64.h:31",
      "file": "drivers/video/console/vgacon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/console/vgacon.c:vgacon_scroll",
        "drivers/video/console/vgacon.c:vgacon_scroll",
        "drivers/video/console/vgacon.c:vgacon_blank"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589135580,
      "name": "memset16",
      "external": false,
      "loc": "arch/x86/include/asm/string_64.h:31",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590426071,
      "name": "memset16",
      "external": false,
      "loc": "arch/x86/include/asm/string_64.h:31",
      "file": "drivers/tty/vt/vt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:csi_J",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:insert_char",
        "drivers/tty/vt/vt.c:con_scroll"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void * memset16(uint16_t * s, uint16_t v, size_t count)
```

```json
{
  "name": "memset16",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503864416,
      "name": "memset16",
      "external": true,
      "loc": "lib/string.c:762",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:csi_J",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:insert_char",
        "drivers/tty/vt/vt.c:con_scroll",
        "drivers/tty/vt/vt.c:con_scroll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503864416,
      "name": "memset16",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
void * memset16(uint16_t * s, uint16_t v, size_t count)
```

```json
{
  "name": "memset16",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236492408,
      "name": "memset16",
      "external": true,
      "loc": "lib/string.c:762",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:csi_J",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:insert_char",
        "drivers/tty/vt/vt.c:con_scroll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236492408,
      "name": "memset16",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
  "name": "memset16",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055291190760,
      "name": "memset16",
      "external": false,
      "loc": "arch/powerpc/include/asm/string.h:63",
      "file": "drivers/video/console/vgacon.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055291289784,
      "name": "memset16",
      "external": false,
      "loc": "arch/powerpc/include/asm/string.h:63",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055291704232,
      "name": "memset16",
      "external": false,
      "loc": "arch/powerpc/include/asm/string.h:63",
      "file": "drivers/tty/vt/vt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:csi_J",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:insert_char",
        "drivers/tty/vt/vt.c:con_scroll"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void * memset16(uint16_t * s, uint16_t v, size_t count)
```

```json
{
  "name": "memset16",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279760206,
      "name": "memset16",
      "external": true,
      "loc": "lib/string.c:762",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:csi_J",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:insert_char",
        "drivers/tty/vt/vt.c:con_scroll"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279760206,
      "name": "memset16",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
  "name": "memset16",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584798480,
      "name": "memset16",
      "external": false,
      "loc": "arch/x86/include/asm/string_64.h:22",
      "file": "drivers/video/console/vgacon.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584853596,
      "name": "memset16",
      "external": false,
      "loc": "arch/x86/include/asm/string_64.h:22",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585553764,
      "name": "memset16",
      "external": false,
      "loc": "arch/x86/include/asm/string_64.h:22",
      "file": "drivers/tty/vt/vt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:csi_J",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:insert_char",
        "drivers/tty/vt/vt.c:con_scroll"
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
  "name": "memset16",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584729264,
      "name": "memset16",
      "external": false,
      "loc": "arch/x86/include/asm/string_64.h:22",
      "file": "drivers/video/console/vgacon.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584783420,
      "name": "memset16",
      "external": false,
      "loc": "arch/x86/include/asm/string_64.h:22",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585423588,
      "name": "memset16",
      "external": false,
      "loc": "arch/x86/include/asm/string_64.h:22",
      "file": "drivers/tty/vt/vt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:csi_J",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:insert_char",
        "drivers/tty/vt/vt.c:con_scroll"
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
  "name": "memset16",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584799904,
      "name": "memset16",
      "external": false,
      "loc": "arch/x86/include/asm/string_64.h:22",
      "file": "drivers/video/console/vgacon.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584855020,
      "name": "memset16",
      "external": false,
      "loc": "arch/x86/include/asm/string_64.h:22",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585743172,
      "name": "memset16",
      "external": false,
      "loc": "arch/x86/include/asm/string_64.h:22",
      "file": "drivers/tty/vt/vt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:csi_J",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:insert_char",
        "drivers/tty/vt/vt.c:con_scroll"
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
  "name": "memset16",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584905040,
      "name": "memset16",
      "external": false,
      "loc": "arch/x86/include/asm/string_64.h:22",
      "file": "drivers/video/console/vgacon.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584960156,
      "name": "memset16",
      "external": false,
      "loc": "arch/x86/include/asm/string_64.h:22",
      "file": "drivers/video/fbdev/core/fbcon.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_scroll",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo",
        "drivers/video/fbdev/core/fbcon.c:fbcon_prepare_logo"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585851172,
      "name": "memset16",
      "external": false,
      "loc": "arch/x86/include/asm/string_64.h:22",
      "file": "drivers/tty/vt/vt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:do_con_trol",
        "drivers/tty/vt/vt.c:csi_J",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:vc_do_resize",
        "drivers/tty/vt/vt.c:insert_char",
        "drivers/tty/vt/vt.c:con_scroll"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
void * memset16(uint16_t * s, uint16_t v, size_t count)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
void * memset16(uint16_t * s, uint16_t v, size_t count)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
void * memset16(uint16_t * s, uint16_t v, size_t count)
```
</details>
</li>
</ul>
