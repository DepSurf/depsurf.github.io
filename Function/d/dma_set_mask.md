# Function: <code>dma_set_mask</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dma_set_mask",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584230804,
      "name": "dma_set_mask",
      "external": false,
      "loc": "include/asm-generic/dma-mapping-common.h:344",
      "file": "drivers/char/agp/intel-gtt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584995477,
      "name": "dma_set_mask",
      "external": false,
      "loc": "include/asm-generic/dma-mapping-common.h:344",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-sff.c:ata_pci_bmdma_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585309552,
      "name": "dma_set_mask",
      "external": false,
      "loc": "include/asm-generic/dma-mapping-common.h:344",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585387477,
      "name": "dma_set_mask",
      "external": false,
      "loc": "include/asm-generic/dma-mapping-common.h:344",
      "file": "drivers/usb/host/ehci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-platform.c:ehci_platform_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585415822,
      "name": "dma_set_mask",
      "external": false,
      "loc": "include/asm-generic/dma-mapping-common.h:344",
      "file": "drivers/usb/host/ohci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585456700,
      "name": "dma_set_mask",
      "external": false,
      "loc": "include/asm-generic/dma-mapping-common.h:344",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_gen_setup"
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
  "name": "dma_set_mask",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584162632,
      "name": "dma_set_mask",
      "external": false,
      "loc": "include/linux/dma-mapping.h:499",
      "file": "drivers/virtio/virtio_pci_modern.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584168406,
      "name": "dma_set_mask",
      "external": false,
      "loc": "include/linux/dma-mapping.h:499",
      "file": "drivers/virtio/virtio_pci_legacy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe",
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584570673,
      "name": "dma_set_mask",
      "external": false,
      "loc": "include/linux/dma-mapping.h:499",
      "file": "drivers/char/agp/intel-gtt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585363479,
      "name": "dma_set_mask",
      "external": false,
      "loc": "include/linux/dma-mapping.h:499",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-sff.c:ata_pci_bmdma_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585702520,
      "name": "dma_set_mask",
      "external": false,
      "loc": "include/linux/dma-mapping.h:499",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585783793,
      "name": "dma_set_mask",
      "external": false,
      "loc": "include/linux/dma-mapping.h:499",
      "file": "drivers/usb/host/ehci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-platform.c:ehci_platform_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585811793,
      "name": "dma_set_mask",
      "external": false,
      "loc": "include/linux/dma-mapping.h:499",
      "file": "drivers/usb/host/ohci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585852259,
      "name": "dma_set_mask",
      "external": false,
      "loc": "include/linux/dma-mapping.h:499",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_gen_setup"
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
  "name": "dma_set_mask",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584339807,
      "name": "dma_set_mask",
      "external": false,
      "loc": "include/linux/dma-mapping.h:551",
      "file": "drivers/virtio/virtio_mmio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584343783,
      "name": "dma_set_mask",
      "external": false,
      "loc": "include/linux/dma-mapping.h:551",
      "file": "drivers/virtio/virtio_pci_modern.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584349686,
      "name": "dma_set_mask",
      "external": false,
      "loc": "include/linux/dma-mapping.h:551",
      "file": "drivers/virtio/virtio_pci_legacy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe",
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584752577,
      "name": "dma_set_mask",
      "external": false,
      "loc": "include/linux/dma-mapping.h:551",
      "file": "drivers/char/agp/intel-gtt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585564343,
      "name": "dma_set_mask",
      "external": false,
      "loc": "include/linux/dma-mapping.h:551",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-sff.c:ata_pci_bmdma_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585891300,
      "name": "dma_set_mask",
      "external": false,
      "loc": "include/linux/dma-mapping.h:551",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585972528,
      "name": "dma_set_mask",
      "external": false,
      "loc": "include/linux/dma-mapping.h:551",
      "file": "drivers/usb/host/ehci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-platform.c:ehci_platform_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586000465,
      "name": "dma_set_mask",
      "external": false,
      "loc": "include/linux/dma-mapping.h:551",
      "file": "drivers/usb/host/ohci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586041091,
      "name": "dma_set_mask",
      "external": false,
      "loc": "include/linux/dma-mapping.h:551",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_gen_setup"
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
  "name": "dma_set_mask",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584420864,
      "name": "dma_set_mask",
      "external": false,
      "loc": "include/linux/dma-mapping.h:587",
      "file": "drivers/virtio/virtio_mmio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584424983,
      "name": "dma_set_mask",
      "external": false,
      "loc": "include/linux/dma-mapping.h:587",
      "file": "drivers/virtio/virtio_pci_modern.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584431046,
      "name": "dma_set_mask",
      "external": false,
      "loc": "include/linux/dma-mapping.h:587",
      "file": "drivers/virtio/virtio_pci_legacy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe",
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584830406,
      "name": "dma_set_mask",
      "external": false,
      "loc": "include/linux/dma-mapping.h:587",
      "file": "drivers/char/agp/intel-gtt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585648215,
      "name": "dma_set_mask",
      "external": false,
      "loc": "include/linux/dma-mapping.h:587",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-sff.c:ata_pci_bmdma_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585973930,
      "name": "dma_set_mask",
      "external": false,
      "loc": "include/linux/dma-mapping.h:587",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586056317,
      "name": "dma_set_mask",
      "external": false,
      "loc": "include/linux/dma-mapping.h:587",
      "file": "drivers/usb/host/ehci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-platform.c:ehci_platform_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586084169,
      "name": "dma_set_mask",
      "external": false,
      "loc": "include/linux/dma-mapping.h:587",
      "file": "drivers/usb/host/ohci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586124023,
      "name": "dma_set_mask",
      "external": false,
      "loc": "include/linux/dma-mapping.h:587",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_gen_setup"
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
  "name": "dma_set_mask",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584828452,
      "name": "dma_set_mask",
      "external": false,
      "loc": "include/linux/dma-mapping.h:589",
      "file": "drivers/virtio/virtio_mmio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584832778,
      "name": "dma_set_mask",
      "external": false,
      "loc": "include/linux/dma-mapping.h:589",
      "file": "drivers/virtio/virtio_pci_modern.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584838982,
      "name": "dma_set_mask",
      "external": false,
      "loc": "include/linux/dma-mapping.h:589",
      "file": "drivers/virtio/virtio_pci_legacy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe",
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585252266,
      "name": "dma_set_mask",
      "external": false,
      "loc": "include/linux/dma-mapping.h:589",
      "file": "drivers/char/agp/intel-gtt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586080119,
      "name": "dma_set_mask",
      "external": false,
      "loc": "include/linux/dma-mapping.h:589",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-sff.c:ata_pci_bmdma_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586417707,
      "name": "dma_set_mask",
      "external": false,
      "loc": "include/linux/dma-mapping.h:589",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586500861,
      "name": "dma_set_mask",
      "external": false,
      "loc": "include/linux/dma-mapping.h:589",
      "file": "drivers/usb/host/ehci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-platform.c:ehci_platform_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586528614,
      "name": "dma_set_mask",
      "external": false,
      "loc": "include/linux/dma-mapping.h:589",
      "file": "drivers/usb/host/ohci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586566927,
      "name": "dma_set_mask",
      "external": false,
      "loc": "include/linux/dma-mapping.h:589",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_gen_setup"
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
  "name": "dma_set_mask",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585058545,
      "name": "dma_set_mask",
      "external": false,
      "loc": "include/linux/dma-mapping.h:593",
      "file": "drivers/virtio/virtio_mmio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585063154,
      "name": "dma_set_mask",
      "external": false,
      "loc": "include/linux/dma-mapping.h:593",
      "file": "drivers/virtio/virtio_pci_modern.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585069701,
      "name": "dma_set_mask",
      "external": false,
      "loc": "include/linux/dma-mapping.h:593",
      "file": "drivers/virtio/virtio_pci_legacy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe",
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585489033,
      "name": "dma_set_mask",
      "external": false,
      "loc": "include/linux/dma-mapping.h:593",
      "file": "drivers/char/agp/intel-gtt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586328151,
      "name": "dma_set_mask",
      "external": false,
      "loc": "include/linux/dma-mapping.h:593",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-sff.c:ata_pci_bmdma_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586679931,
      "name": "dma_set_mask",
      "external": false,
      "loc": "include/linux/dma-mapping.h:593",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586765107,
      "name": "dma_set_mask",
      "external": false,
      "loc": "include/linux/dma-mapping.h:593",
      "file": "drivers/usb/host/ehci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-platform.c:ehci_platform_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586792381,
      "name": "dma_set_mask",
      "external": false,
      "loc": "include/linux/dma-mapping.h:593",
      "file": "drivers/usb/host/ohci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586831659,
      "name": "dma_set_mask",
      "external": false,
      "loc": "include/linux/dma-mapping.h:593",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_gen_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587089855,
      "name": "dma_set_mask",
      "external": false,
      "loc": "include/linux/dma-mapping.h:593",
      "file": "drivers/i2c/busses/i2c-amd-pci-mp2.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-amd-pci-mp2.c:amd_mp2_pci_probe",
        "drivers/i2c/busses/i2c-amd-pci-mp2.c:amd_mp2_pci_probe"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int dma_set_mask(struct device * dev, u64 mask)
```

```json
{
  "name": "dma_set_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579992592,
      "name": "dma_set_mask",
      "external": true,
      "loc": "kernel/dma/mapping.c:322",
      "file": "kernel/dma/mapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe",
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/ata/libata-sff.c:ata_pci_bmdma_init",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/host/ehci-platform.c:ehci_platform_probe",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_gen_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579992592,
      "name": "dma_set_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int dma_set_mask(struct device * dev, u64 mask)
```

```json
{
  "name": "dma_set_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dma_set_mask",
      "external": true,
      "loc": "kernel/dma/mapping.c:344",
      "file": "kernel/dma/mapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe",
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/ata/libata-sff.c:ata_pci_bmdma_init",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/host/ehci-platform.c:ehci_platform_probe",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_gen_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580035278,
      "name": "dma_set_mask.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071580034448,
      "name": "dma_set_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
int dma_set_mask(struct device * dev, u64 mask)
```

```json
{
  "name": "dma_set_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580084672,
      "name": "dma_set_mask",
      "external": true,
      "loc": "kernel/dma/mapping.c:366",
      "file": "kernel/dma/mapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma/acpi-dma.c:acpi_dma_controller_register",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe",
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/ata/libata-sff.c:ata_pci_bmdma_init",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/host/ehci-platform.c:ehci_platform_probe",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580084672,
      "name": "dma_set_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
int dma_set_mask(struct device * dev, u64 mask)
```

```json
{
  "name": "dma_set_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580144992,
      "name": "dma_set_mask",
      "external": true,
      "loc": "kernel/dma/mapping.c:337",
      "file": "kernel/dma/mapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma/acpi-dma.c:acpi_dma_parse_resource_group",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe",
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/ata/libata-sff.c:ata_pci_bmdma_init",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/host/ehci-platform.c:ehci_platform_probe",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580144992,
      "name": "dma_set_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
int dma_set_mask(struct device * dev, u64 mask)
```

```json
{
  "name": "dma_set_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580123936,
      "name": "dma_set_mask",
      "external": true,
      "loc": "kernel/dma/mapping.c:580",
      "file": "kernel/dma/mapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init",
        "drivers/dma/acpi-dma.c:acpi_dma_parse_resource_group",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe",
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/ata/libata-sff.c:ata_pci_bmdma_init",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/host/ehci-platform.c:ehci_platform_probe",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580123936,
      "name": "dma_set_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
int dma_set_mask(struct device * dev, u64 mask)
```

```json
{
  "name": "dma_set_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580128320,
      "name": "dma_set_mask",
      "external": true,
      "loc": "kernel/dma/mapping.c:670",
      "file": "kernel/dma/mapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init",
        "drivers/dma/acpi-dma.c:acpi_dma_parse_resource_group",
        "drivers/dma/lgm/lgm-dma.c:intel_ldma_probe",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe",
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/ata/libata-sff.c:ata_pci_bmdma_init",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/host/ehci-platform.c:ehci_platform_probe",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580128320,
      "name": "dma_set_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
int dma_set_mask(struct device * dev, u64 mask)
```

```json
{
  "name": "dma_set_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580271312,
      "name": "dma_set_mask",
      "external": true,
      "loc": "kernel/dma/mapping.c:735",
      "file": "kernel/dma/mapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init",
        "drivers/dma/acpi-dma.c:acpi_dma_parse_resource_group",
        "drivers/dma/lgm/lgm-dma.c:intel_ldma_probe",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe",
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/ata/libata-sff.c:ata_pci_bmdma_init",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/host/ehci-platform.c:ehci_platform_probe",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580271312,
      "name": "dma_set_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
int dma_set_mask(struct device * dev, u64 mask)
```

```json
{
  "name": "dma_set_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580442624,
      "name": "dma_set_mask",
      "external": true,
      "loc": "kernel/dma/mapping.c:729",
      "file": "kernel/dma/mapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_host_init",
        "drivers/dma/acpi-dma.c:acpi_dma_parse_resource_group",
        "drivers/dma/lgm/lgm-dma.c:intel_ldma_probe",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe",
        "drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_probe",
        "drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_probe",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/dma-buf/udmabuf.c:udmabuf_dev_init",
        "drivers/ata/libata-sff.c:ata_pci_bmdma_init",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/host/ehci-platform.c:ehci_platform_probe",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580442624,
      "name": "dma_set_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
int dma_set_mask(struct device * dev, u64 mask)
```

```json
{
  "name": "dma_set_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580683984,
      "name": "dma_set_mask",
      "external": true,
      "loc": "kernel/dma/mapping.c:765",
      "file": "kernel/dma/mapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_host_init",
        "drivers/dma/acpi-dma.c:acpi_dma_parse_resource_group",
        "drivers/dma/lgm/lgm-dma.c:intel_ldma_probe",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe",
        "drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_probe",
        "drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_probe",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/dma-buf/udmabuf.c:udmabuf_dev_init",
        "drivers/ata/libata-sff.c:ata_pci_bmdma_init",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/host/ehci-platform.c:ehci_platform_probe",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580683984,
      "name": "dma_set_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
int dma_set_mask(struct device * dev, u64 mask)
```

```json
{
  "name": "dma_set_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580760512,
      "name": "dma_set_mask",
      "external": true,
      "loc": "kernel/dma/mapping.c:769",
      "file": "kernel/dma/mapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma/acpi-dma.c:acpi_dma_parse_resource_group",
        "drivers/dma/lgm/lgm-dma.c:intel_ldma_probe",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe",
        "drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_probe",
        "drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_probe",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/dma-buf/udmabuf.c:udmabuf_dev_init",
        "drivers/ata/libata-sff.c:ata_pci_bmdma_init",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/host/ehci-platform.c:ehci_platform_probe",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580760512,
      "name": "dma_set_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
int dma_set_mask(struct device * dev, u64 mask)
```

```json
{
  "name": "dma_set_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580845664,
      "name": "dma_set_mask",
      "external": true,
      "loc": "kernel/dma/mapping.c:763",
      "file": "kernel/dma/mapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma/acpi-dma.c:acpi_dma_parse_resource_group",
        "drivers/dma/lgm/lgm-dma.c:intel_ldma_probe",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe",
        "drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_probe",
        "drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_probe",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/dma-buf/udmabuf.c:udmabuf_dev_init",
        "drivers/ata/libata-sff.c:ata_pci_bmdma_init",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/host/ehci-platform.c:ehci_platform_probe",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/remoteproc/remoteproc_virtio.c:rproc_virtio_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580845664,
      "name": "dma_set_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
int dma_set_mask(struct device * dev, u64 mask)
```

```json
{
  "name": "dma_set_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491286024,
      "name": "dma_set_mask",
      "external": true,
      "loc": "kernel/dma/mapping.c:366",
      "file": "kernel/dma/mapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/amba-clcd.c:clcdfb_probe",
        "drivers/dma/acpi-dma.c:acpi_dma_controller_register",
        "drivers/dma/amba-pl08x.c:pl08x_probe",
        "drivers/dma/bcm2835-dma.c:bcm2835_dma_probe",
        "drivers/dma/mv_xor_v2.c:mv_xor_v2_probe",
        "drivers/soc/fsl/qbman/qman_portal.c:qman_portal_probe",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe",
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe",
        "drivers/iommu/arm-smmu.c:arm_smmu_device_cfg_probe",
        "drivers/iommu/arm-smmu-v3.c:arm_smmu_device_hw_probe",
        "drivers/ata/libata-sff.c:ata_pci_bmdma_init",
        "drivers/ata/libahci_platform.c:ahci_platform_init_host",
        "drivers/ata/libahci_platform.c:ahci_platform_init_host",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_init",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/host/ehci-orion.c:ehci_orion_drv_probe",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491286024,
      "name": "dma_set_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
int dma_set_mask(struct device * dev, u64 mask)
```

```json
{
  "name": "dma_set_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225293184,
      "name": "dma_set_mask",
      "external": true,
      "loc": "kernel/dma/mapping.c:366",
      "file": "kernel/dma/mapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/amba-clcd.c:clcdfb_probe",
        "drivers/dma/amba-pl08x.c:pl08x_probe",
        "drivers/dma/ti/edma.c:edma_probe",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe",
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe",
        "drivers/iommu/ipmmu-vmsa.c:ipmmu_probe",
        "drivers/ata/libata-sff.c:ata_pci_bmdma_init",
        "drivers/ata/libahci_platform.c:ahci_platform_init_host",
        "drivers/ata/libahci_platform.c:ahci_platform_init_host",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_init",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/host/ehci-orion.c:ehci_orion_drv_probe",
        "drivers/usb/host/ehci-exynos.c:exynos_ehci_probe",
        "drivers/usb/host/ohci-exynos.c:exynos_ohci_probe",
        "drivers/usb/host/uhci-hcd.c:uhci_hcd_platform_probe",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/mmc/host/sdhci.c:sdhci_setup_host",
        "drivers/mmc/host/sdhci.c:sdhci_setup_host",
        "drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225293184,
      "name": "dma_set_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
int dma_set_mask(struct device * dev, u64 mask)
```

```json
{
  "name": "dma_set_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284212192,
      "name": "dma_set_mask",
      "external": true,
      "loc": "kernel/dma/mapping.c:366",
      "file": "kernel/dma/mapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe",
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe",
        "drivers/ata/libata-sff.c:ata_pci_bmdma_init",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284212192,
      "name": "dma_set_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
int dma_set_mask(struct device * dev, u64 mask)
```

```json
{
  "name": "dma_set_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271802746,
      "name": "dma_set_mask",
      "external": true,
      "loc": "kernel/dma/mapping.c:366",
      "file": "kernel/dma/mapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe",
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe",
        "drivers/ata/libata-sff.c:ata_pci_bmdma_init",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_gen_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271802746,
      "name": "dma_set_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
int dma_set_mask(struct device * dev, u64 mask)
```

```json
{
  "name": "dma_set_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580053408,
      "name": "dma_set_mask",
      "external": true,
      "loc": "kernel/dma/mapping.c:366",
      "file": "kernel/dma/mapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma/acpi-dma.c:acpi_dma_controller_register",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe",
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/nvme/host/pci.c:nvme_reset_work",
        "drivers/ata/libata-sff.c:ata_pci_bmdma_init",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/host/ehci-platform.c:ehci_platform_probe",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580053408,
      "name": "dma_set_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
int dma_set_mask(struct device * dev, u64 mask)
```

```json
{
  "name": "dma_set_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579998720,
      "name": "dma_set_mask",
      "external": true,
      "loc": "kernel/dma/mapping.c:366",
      "file": "kernel/dma/mapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma/acpi-dma.c:acpi_dma_controller_register",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe",
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/nvme/host/pci.c:nvme_reset_work",
        "drivers/ata/libata-sff.c:ata_pci_bmdma_init",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_gen_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579998720,
      "name": "dma_set_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
int dma_set_mask(struct device * dev, u64 mask)
```

```json
{
  "name": "dma_set_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580044944,
      "name": "dma_set_mask",
      "external": true,
      "loc": "kernel/dma/mapping.c:366",
      "file": "kernel/dma/mapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma/acpi-dma.c:acpi_dma_controller_register",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe",
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/ata/libata-sff.c:ata_pci_bmdma_init",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/host/ehci-platform.c:ehci_platform_probe",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/i2c/busses/i2c-amd-mp2-pci.c:amd_mp2_pci_probe",
        "drivers/i2c/busses/i2c-amd-mp2-pci.c:amd_mp2_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580044944,
      "name": "dma_set_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
int dma_set_mask(struct device * dev, u64 mask)
```

```json
{
  "name": "dma_set_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580095696,
      "name": "dma_set_mask",
      "external": true,
      "loc": "kernel/dma/mapping.c:366",
      "file": "kernel/dma/mapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dma/acpi-dma.c:acpi_dma_controller_register",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe",
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/ata/libata-sff.c:ata_pci_bmdma_init",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/host/ehci-platform.c:ehci_platform_probe",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580095696,
      "name": "dma_set_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
int dma_set_mask(struct device * dev, u64 mask)
```
</details>
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
