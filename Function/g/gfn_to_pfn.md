# Function: <code>gfn_to_pfn</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "gfn_to_pfn",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583876195,
      "name": "gfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:200",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595248954,
      "name": "gfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:200",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583910345,
      "name": "gfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:200",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584084701,
      "name": "gfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:200",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/hvc/hvc_xen.c:xen_pv_console_init"
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
  "name": "gfn_to_pfn",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584207285,
      "name": "gfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:200",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595430663,
      "name": "gfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:200",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584243954,
      "name": "gfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:200",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584415106,
      "name": "gfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:200",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init"
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
  "name": "gfn_to_pfn",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584388869,
      "name": "gfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:200",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071595682948,
      "name": "gfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:200",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584425474,
      "name": "gfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:200",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584598322,
      "name": "gfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:200",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init"
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
  "name": "gfn_to_pfn",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584470501,
      "name": "gfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:226",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071596607303,
      "name": "gfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:226",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584509394,
      "name": "gfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:226",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584680436,
      "name": "gfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:226",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init"
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
  "name": "gfn_to_pfn",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584880885,
      "name": "gfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:233",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071602937681,
      "name": "gfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:233",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584919426,
      "name": "gfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:233",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585093332,
      "name": "gfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:233",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init"
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
  "name": "gfn_to_pfn",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585110389,
      "name": "gfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:233",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071603110623,
      "name": "gfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:233",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585150943,
      "name": "gfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:233",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585326207,
      "name": "gfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:233",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init"
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
  "name": "gfn_to_pfn",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585221173,
      "name": "gfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:260",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604913336,
      "name": "gfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:260",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585261779,
      "name": "gfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:260",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585449663,
      "name": "gfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:260",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init"
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
  "name": "gfn_to_pfn",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585433365,
      "name": "gfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:260",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071605022099,
      "name": "gfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:260",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585469284,
      "name": "gfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:260",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585665487,
      "name": "gfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:260",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init"
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
  "name": "gfn_to_pfn",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585573813,
      "name": "gfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:260",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071605059050,
      "name": "gfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:260",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585609540,
      "name": "gfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:260",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585806463,
      "name": "gfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:260",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init"
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
  "name": "gfn_to_pfn",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586295301,
      "name": "gfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:259",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071609348590,
      "name": "gfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:259",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586332498,
      "name": "gfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:259",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_device",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_sg_for_cpu",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586536703,
      "name": "gfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:259",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init"
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
  "name": "gfn_to_pfn",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586414453,
      "name": "gfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:259",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071612419534,
      "name": "gfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:259",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init"
      ],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "gfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:259",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071586647919,
      "name": "gfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:259",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init"
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
  "name": "gfn_to_pfn",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586297893,
      "name": "gfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:259",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071614560296,
      "name": "gfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:259",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586333034,
      "name": "gfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:259",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586531887,
      "name": "gfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:259",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init"
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
  "name": "gfn_to_pfn",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586778820,
      "name": "gfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:259",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_add_deferred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586817109,
      "name": "gfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:259",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071615514575,
      "name": "gfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:259",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586852848,
      "name": "gfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:259",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_unmap_page",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587070191,
      "name": "gfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:259",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init"
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
  "name": "gfn_to_pfn",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588058374,
      "name": "gfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:251",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_add_deferred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588101908,
      "name": "gfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:251",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071617319018,
      "name": "gfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:251",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588139652,
      "name": "gfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:251",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_unmap_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588373901,
      "name": "gfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:251",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init"
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
  "name": "gfn_to_pfn",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589438380,
      "name": "gfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:251",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_add_deferred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589486900,
      "name": "gfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:251",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071628042089,
      "name": "gfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:251",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589529348,
      "name": "gfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:251",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_unmap_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589797885,
      "name": "gfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:251",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init"
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
  "name": "gfn_to_pfn",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589738446,
      "name": "gfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:251",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_add_deferred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589787372,
      "name": "gfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:251",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071619807609,
      "name": "gfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:251",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071589830420,
      "name": "gfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:251",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_unmap_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590103236,
      "name": "gfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:251",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init"
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
  "name": "gfn_to_pfn",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590076445,
      "name": "gfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:251",
      "file": "drivers/xen/grant-table.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/grant-table.c:gnttab_add_deferred"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590123500,
      "name": "gfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:251",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071622116089,
      "name": "gfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:251",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590167505,
      "name": "gfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:251",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_unmap_page"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071590442628,
      "name": "gfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:251",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init"
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Collision, Selective Inline ❓</summary>

```c
kvm_pfn_t gfn_to_pfn(struct kvm * kvm, gfn_t gfn)
```

```json
{
  "name": "gfn_to_pfn",
  "collision_type": "Static-Global Collision",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490402176,
      "name": "gfn_to_pfn",
      "external": true,
      "loc": "virt/kvm/kvm_main.c:1760",
      "file": "virt/kvm/kvm_main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "virt/kvm/kvm_main.c:gfn_to_page"
      ]
    },
    {
      "addr": 0,
      "name": "gfn_to_pfn",
      "external": false,
      "loc": "include/xen/arm/page.h:52",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "gfn_to_pfn",
      "external": false,
      "loc": "include/xen/arm/page.h:52",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "gfn_to_pfn",
      "external": false,
      "loc": "include/xen/arm/page.h:52",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490402176,
      "name": "gfn_to_pfn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
    }
  ]
}
```
</details>
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "gfn_to_pfn",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585335845,
      "name": "gfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:260",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071604958727,
      "name": "gfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:260",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585371188,
      "name": "gfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:260",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585567455,
      "name": "gfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:260",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init"
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
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "gfn_to_pfn",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585524213,
      "name": "gfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:260",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071605039373,
      "name": "gfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:260",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585559940,
      "name": "gfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:260",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585756863,
      "name": "gfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:260",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init"
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
  "name": "gfn_to_pfn",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585633589,
      "name": "gfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:260",
      "file": "drivers/xen/xenbus/xenbus_client.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_setup_grant_hvm",
        "drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_setup_grant_hvm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071605063230,
      "name": "gfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:260",
      "file": "drivers/xen/xenbus/xenbus_probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init",
        "drivers/xen/xenbus/xenbus_probe.c:xenbus_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585667908,
      "name": "gfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:260",
      "file": "drivers/xen/swiotlb-xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_device",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_sync_single_for_cpu",
        "drivers/xen/swiotlb-xen.c:xen_swiotlb_free_coherent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585865695,
      "name": "gfn_to_pfn",
      "external": false,
      "loc": "arch/x86/include/asm/xen/page.h:260",
      "file": "drivers/tty/hvc/hvc_xen.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/hvc/hvc_xen.c:xencons_info_pv_init"
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
kvm_pfn_t gfn_to_pfn(struct kvm * kvm, gfn_t gfn)
```
</details>
</li>
</ul>
