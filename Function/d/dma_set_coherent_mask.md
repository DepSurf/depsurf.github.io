# Function: <code>dma_set_coherent_mask</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dma_set_coherent_mask",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584230896,
      "name": "dma_set_coherent_mask",
      "external": false,
      "loc": "include/linux/dma-mapping.h:102",
      "file": "drivers/char/agp/intel-gtt.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584995533,
      "name": "dma_set_coherent_mask",
      "external": false,
      "loc": "include/linux/dma-mapping.h:102",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-sff.c:ata_pci_bmdma_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585293478,
      "name": "dma_set_coherent_mask",
      "external": false,
      "loc": "include/linux/dma-mapping.h:102",
      "file": "drivers/usb/dwc2/platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585309611,
      "name": "dma_set_coherent_mask",
      "external": false,
      "loc": "include/linux/dma-mapping.h:102",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585386290,
      "name": "dma_set_coherent_mask",
      "external": false,
      "loc": "include/linux/dma-mapping.h:102",
      "file": "drivers/usb/host/ehci-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585387612,
      "name": "dma_set_coherent_mask",
      "external": false,
      "loc": "include/linux/dma-mapping.h:102",
      "file": "drivers/usb/host/ehci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-platform.c:ehci_platform_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585415945,
      "name": "dma_set_coherent_mask",
      "external": false,
      "loc": "include/linux/dma-mapping.h:102",
      "file": "drivers/usb/host/ohci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585456771,
      "name": "dma_set_coherent_mask",
      "external": false,
      "loc": "include/linux/dma-mapping.h:102",
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
  "name": "dma_set_coherent_mask",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584163420,
      "name": "dma_set_coherent_mask",
      "external": false,
      "loc": "include/linux/dma-mapping.h:523",
      "file": "drivers/virtio/virtio_pci_modern.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584168579,
      "name": "dma_set_coherent_mask",
      "external": false,
      "loc": "include/linux/dma-mapping.h:523",
      "file": "drivers/virtio/virtio_pci_legacy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe",
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584570842,
      "name": "dma_set_coherent_mask",
      "external": false,
      "loc": "include/linux/dma-mapping.h:523",
      "file": "drivers/char/agp/intel-gtt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585363535,
      "name": "dma_set_coherent_mask",
      "external": false,
      "loc": "include/linux/dma-mapping.h:523",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-sff.c:ata_pci_bmdma_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585679614,
      "name": "dma_set_coherent_mask",
      "external": false,
      "loc": "include/linux/dma-mapping.h:523",
      "file": "drivers/usb/dwc2/platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585702579,
      "name": "dma_set_coherent_mask",
      "external": false,
      "loc": "include/linux/dma-mapping.h:523",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585782590,
      "name": "dma_set_coherent_mask",
      "external": false,
      "loc": "include/linux/dma-mapping.h:523",
      "file": "drivers/usb/host/ehci-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585783924,
      "name": "dma_set_coherent_mask",
      "external": false,
      "loc": "include/linux/dma-mapping.h:523",
      "file": "drivers/usb/host/ehci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-platform.c:ehci_platform_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585811922,
      "name": "dma_set_coherent_mask",
      "external": false,
      "loc": "include/linux/dma-mapping.h:523",
      "file": "drivers/usb/host/ohci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585852322,
      "name": "dma_set_coherent_mask",
      "external": false,
      "loc": "include/linux/dma-mapping.h:523",
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
  "name": "dma_set_coherent_mask",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584340005,
      "name": "dma_set_coherent_mask",
      "external": false,
      "loc": "include/linux/dma-mapping.h:575",
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
      "addr": 18446744071584344580,
      "name": "dma_set_coherent_mask",
      "external": false,
      "loc": "include/linux/dma-mapping.h:575",
      "file": "drivers/virtio/virtio_pci_modern.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584350135,
      "name": "dma_set_coherent_mask",
      "external": false,
      "loc": "include/linux/dma-mapping.h:575",
      "file": "drivers/virtio/virtio_pci_legacy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe",
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584752749,
      "name": "dma_set_coherent_mask",
      "external": false,
      "loc": "include/linux/dma-mapping.h:575",
      "file": "drivers/char/agp/intel-gtt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585564402,
      "name": "dma_set_coherent_mask",
      "external": false,
      "loc": "include/linux/dma-mapping.h:575",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-sff.c:ata_pci_bmdma_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585861290,
      "name": "dma_set_coherent_mask",
      "external": false,
      "loc": "include/linux/dma-mapping.h:575",
      "file": "drivers/usb/dwc2/platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585891362,
      "name": "dma_set_coherent_mask",
      "external": false,
      "loc": "include/linux/dma-mapping.h:575",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585971279,
      "name": "dma_set_coherent_mask",
      "external": false,
      "loc": "include/linux/dma-mapping.h:575",
      "file": "drivers/usb/host/ehci-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585972662,
      "name": "dma_set_coherent_mask",
      "external": false,
      "loc": "include/linux/dma-mapping.h:575",
      "file": "drivers/usb/host/ehci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-platform.c:ehci_platform_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586000597,
      "name": "dma_set_coherent_mask",
      "external": false,
      "loc": "include/linux/dma-mapping.h:575",
      "file": "drivers/usb/host/ohci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586041157,
      "name": "dma_set_coherent_mask",
      "external": false,
      "loc": "include/linux/dma-mapping.h:575",
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
  "name": "dma_set_coherent_mask",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583900760,
      "name": "dma_set_coherent_mask",
      "external": false,
      "loc": "include/linux/dma-mapping.h:606",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create",
        "drivers/pci/endpoint/pci-epc-core.c:pci_epc_add_epf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584420948,
      "name": "dma_set_coherent_mask",
      "external": false,
      "loc": "include/linux/dma-mapping.h:606",
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
      "addr": 18446744071584425072,
      "name": "dma_set_coherent_mask",
      "external": false,
      "loc": "include/linux/dma-mapping.h:606",
      "file": "drivers/virtio/virtio_pci_modern.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584431134,
      "name": "dma_set_coherent_mask",
      "external": false,
      "loc": "include/linux/dma-mapping.h:606",
      "file": "drivers/virtio/virtio_pci_legacy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe",
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584830493,
      "name": "dma_set_coherent_mask",
      "external": false,
      "loc": "include/linux/dma-mapping.h:606",
      "file": "drivers/char/agp/intel-gtt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585648299,
      "name": "dma_set_coherent_mask",
      "external": false,
      "loc": "include/linux/dma-mapping.h:606",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-sff.c:ata_pci_bmdma_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585947639,
      "name": "dma_set_coherent_mask",
      "external": false,
      "loc": "include/linux/dma-mapping.h:606",
      "file": "drivers/usb/dwc2/platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585974002,
      "name": "dma_set_coherent_mask",
      "external": false,
      "loc": "include/linux/dma-mapping.h:606",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586054916,
      "name": "dma_set_coherent_mask",
      "external": false,
      "loc": "include/linux/dma-mapping.h:606",
      "file": "drivers/usb/host/ehci-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586056394,
      "name": "dma_set_coherent_mask",
      "external": false,
      "loc": "include/linux/dma-mapping.h:606",
      "file": "drivers/usb/host/ehci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-platform.c:ehci_platform_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586084253,
      "name": "dma_set_coherent_mask",
      "external": false,
      "loc": "include/linux/dma-mapping.h:606",
      "file": "drivers/usb/host/ohci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586124108,
      "name": "dma_set_coherent_mask",
      "external": false,
      "loc": "include/linux/dma-mapping.h:606",
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
  "name": "dma_set_coherent_mask",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584163992,
      "name": "dma_set_coherent_mask",
      "external": false,
      "loc": "include/linux/dma-mapping.h:611",
      "file": "drivers/pci/endpoint/pci-epc-core.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create",
        "drivers/pci/endpoint/pci-epc-core.c:pci_epc_add_epf"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584828548,
      "name": "dma_set_coherent_mask",
      "external": false,
      "loc": "include/linux/dma-mapping.h:611",
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
      "addr": 18446744071584832871,
      "name": "dma_set_coherent_mask",
      "external": false,
      "loc": "include/linux/dma-mapping.h:611",
      "file": "drivers/virtio/virtio_pci_modern.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584839082,
      "name": "dma_set_coherent_mask",
      "external": false,
      "loc": "include/linux/dma-mapping.h:611",
      "file": "drivers/virtio/virtio_pci_legacy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe",
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585252373,
      "name": "dma_set_coherent_mask",
      "external": false,
      "loc": "include/linux/dma-mapping.h:611",
      "file": "drivers/char/agp/intel-gtt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586080216,
      "name": "dma_set_coherent_mask",
      "external": false,
      "loc": "include/linux/dma-mapping.h:611",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-sff.c:ata_pci_bmdma_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586390775,
      "name": "dma_set_coherent_mask",
      "external": false,
      "loc": "include/linux/dma-mapping.h:611",
      "file": "drivers/usb/dwc2/platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586417798,
      "name": "dma_set_coherent_mask",
      "external": false,
      "loc": "include/linux/dma-mapping.h:611",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586499300,
      "name": "dma_set_coherent_mask",
      "external": false,
      "loc": "include/linux/dma-mapping.h:611",
      "file": "drivers/usb/host/ehci-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586500953,
      "name": "dma_set_coherent_mask",
      "external": false,
      "loc": "include/linux/dma-mapping.h:611",
      "file": "drivers/usb/host/ehci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-platform.c:ehci_platform_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586528713,
      "name": "dma_set_coherent_mask",
      "external": false,
      "loc": "include/linux/dma-mapping.h:611",
      "file": "drivers/usb/host/ohci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586567023,
      "name": "dma_set_coherent_mask",
      "external": false,
      "loc": "include/linux/dma-mapping.h:611",
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
  "name": "dma_set_coherent_mask",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585058641,
      "name": "dma_set_coherent_mask",
      "external": false,
      "loc": "include/linux/dma-mapping.h:615",
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
      "addr": 18446744071585063247,
      "name": "dma_set_coherent_mask",
      "external": false,
      "loc": "include/linux/dma-mapping.h:615",
      "file": "drivers/virtio/virtio_pci_modern.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585069786,
      "name": "dma_set_coherent_mask",
      "external": false,
      "loc": "include/linux/dma-mapping.h:615",
      "file": "drivers/virtio/virtio_pci_legacy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe",
        "drivers/virtio/virtio_pci_legacy.c:virtio_pci_legacy_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585489144,
      "name": "dma_set_coherent_mask",
      "external": false,
      "loc": "include/linux/dma-mapping.h:615",
      "file": "drivers/char/agp/intel-gtt.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586328273,
      "name": "dma_set_coherent_mask",
      "external": false,
      "loc": "include/linux/dma-mapping.h:615",
      "file": "drivers/ata/libata-sff.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/ata/libata-sff.c:ata_pci_bmdma_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586651160,
      "name": "dma_set_coherent_mask",
      "external": false,
      "loc": "include/linux/dma-mapping.h:615",
      "file": "drivers/usb/dwc2/platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586680022,
      "name": "dma_set_coherent_mask",
      "external": false,
      "loc": "include/linux/dma-mapping.h:615",
      "file": "drivers/usb/dwc2/hcd.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586763753,
      "name": "dma_set_coherent_mask",
      "external": false,
      "loc": "include/linux/dma-mapping.h:615",
      "file": "drivers/usb/host/ehci-pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586765195,
      "name": "dma_set_coherent_mask",
      "external": false,
      "loc": "include/linux/dma-mapping.h:615",
      "file": "drivers/usb/host/ehci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ehci-platform.c:ehci_platform_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586792476,
      "name": "dma_set_coherent_mask",
      "external": false,
      "loc": "include/linux/dma-mapping.h:615",
      "file": "drivers/usb/host/ohci-platform.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586831797,
      "name": "dma_set_coherent_mask",
      "external": false,
      "loc": "include/linux/dma-mapping.h:615",
      "file": "drivers/usb/host/xhci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_gen_setup"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071587089951,
      "name": "dma_set_coherent_mask",
      "external": false,
      "loc": "include/linux/dma-mapping.h:615",
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
int dma_set_coherent_mask(struct device * dev, u64 mask)
```

```json
{
  "name": "dma_set_coherent_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579992704,
      "name": "dma_set_coherent_mask",
      "external": true,
      "loc": "kernel/dma/mapping.c:335",
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
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/ehci-platform.c:ehci_platform_probe",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_gen_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579992704,
      "name": "dma_set_coherent_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
int dma_set_coherent_mask(struct device * dev, u64 mask)
```

```json
{
  "name": "dma_set_coherent_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dma_set_coherent_mask",
      "external": true,
      "loc": "kernel/dma/mapping.c:363",
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
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/ehci-platform.c:ehci_platform_probe",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_gen_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580035298,
      "name": "dma_set_coherent_mask.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071580034560,
      "name": "dma_set_coherent_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
int dma_set_coherent_mask(struct device * dev, u64 mask)
```

```json
{
  "name": "dma_set_coherent_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580084752,
      "name": "dma_set_coherent_mask",
      "external": true,
      "loc": "kernel/dma/mapping.c:384",
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
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
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
      "addr": 18446744071580084752,
      "name": "dma_set_coherent_mask",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int dma_set_coherent_mask(struct device * dev, u64 mask)
```

```json
{
  "name": "dma_set_coherent_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580144896,
      "name": "dma_set_coherent_mask",
      "external": true,
      "loc": "kernel/dma/mapping.c:355",
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
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
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
      "addr": 18446744071580144896,
      "name": "dma_set_coherent_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
int dma_set_coherent_mask(struct device * dev, u64 mask)
```

```json
{
  "name": "dma_set_coherent_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580123824,
      "name": "dma_set_coherent_mask",
      "external": true,
      "loc": "kernel/dma/mapping.c:598",
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
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
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
      "addr": 18446744071580123824,
      "name": "dma_set_coherent_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
int dma_set_coherent_mask(struct device * dev, u64 mask)
```

```json
{
  "name": "dma_set_coherent_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580128208,
      "name": "dma_set_coherent_mask",
      "external": true,
      "loc": "kernel/dma/mapping.c:688",
      "file": "kernel/dma/mapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
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
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
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
      "addr": 18446744071580128208,
      "name": "dma_set_coherent_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
int dma_set_coherent_mask(struct device * dev, u64 mask)
```

```json
{
  "name": "dma_set_coherent_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580271200,
      "name": "dma_set_coherent_mask",
      "external": true,
      "loc": "kernel/dma/mapping.c:753",
      "file": "kernel/dma/mapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
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
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
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
      "addr": 18446744071580271200,
      "name": "dma_set_coherent_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
int dma_set_coherent_mask(struct device * dev, u64 mask)
```

```json
{
  "name": "dma_set_coherent_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580442512,
      "name": "dma_set_coherent_mask",
      "external": true,
      "loc": "kernel/dma/mapping.c:746",
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
        "drivers/dma-buf/udmabuf.c:udmabuf_dev_init",
        "drivers/ata/libata-sff.c:ata_pci_bmdma_init",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
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
      "addr": 18446744071580442512,
      "name": "dma_set_coherent_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
int dma_set_coherent_mask(struct device * dev, u64 mask)
```

```json
{
  "name": "dma_set_coherent_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580686624,
      "name": "dma_set_coherent_mask",
      "external": true,
      "loc": "kernel/dma/mapping.c:782",
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
        "drivers/dma-buf/udmabuf.c:udmabuf_dev_init",
        "drivers/ata/libata-sff.c:ata_pci_bmdma_init",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
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
      "addr": 18446744071580686624,
      "name": "dma_set_coherent_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
int dma_set_coherent_mask(struct device * dev, u64 mask)
```

```json
{
  "name": "dma_set_coherent_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580763040,
      "name": "dma_set_coherent_mask",
      "external": true,
      "loc": "kernel/dma/mapping.c:786",
      "file": "kernel/dma/mapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_host_init",
        "drivers/dma/acpi-dma.c:acpi_dma_parse_resource_group",
        "drivers/dma/lgm/lgm-dma.c:intel_ldma_probe",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe",
        "drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_probe",
        "drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_probe",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/dma-buf/udmabuf.c:udmabuf_dev_init",
        "drivers/ata/libata-sff.c:ata_pci_bmdma_init",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
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
      "addr": 18446744071580763040,
      "name": "dma_set_coherent_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
int dma_set_coherent_mask(struct device * dev, u64 mask)
```

```json
{
  "name": "dma_set_coherent_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580847136,
      "name": "dma_set_coherent_mask",
      "external": true,
      "loc": "kernel/dma/mapping.c:780",
      "file": "kernel/dma/mapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_host_init",
        "drivers/dma/acpi-dma.c:acpi_dma_parse_resource_group",
        "drivers/dma/lgm/lgm-dma.c:intel_ldma_probe",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe",
        "drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_probe",
        "drivers/virtio/virtio_pci_legacy_dev.c:vp_legacy_probe",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/virtio/virtio_mmio.c:virtio_mmio_probe",
        "drivers/char/agp/intel-gtt.c:intel_gmch_probe",
        "drivers/dma-buf/udmabuf.c:udmabuf_dev_init",
        "drivers/ata/libata-sff.c:ata_pci_bmdma_init",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
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
      "addr": 18446744071580847136,
      "name": "dma_set_coherent_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 105
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
int dma_set_coherent_mask(struct device * dev, u64 mask)
```

```json
{
  "name": "dma_set_coherent_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491286112,
      "name": "dma_set_coherent_mask",
      "external": true,
      "loc": "kernel/dma/mapping.c:384",
      "file": "kernel/dma/mapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/amba-clcd.c:clcdfb_probe",
        "drivers/dma/acpi-dma.c:acpi_dma_controller_register",
        "drivers/dma/amba-pl08x.c:pl08x_probe",
        "drivers/dma/bcm2835-dma.c:bcm2835_dma_probe",
        "drivers/dma/mv_xor_v2.c:mv_xor_v2_probe",
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
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/ehci-orion.c:ehci_orion_drv_probe",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491286112,
      "name": "dma_set_coherent_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
int dma_set_coherent_mask(struct device * dev, u64 mask)
```

```json
{
  "name": "dma_set_coherent_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225293268,
      "name": "dma_set_coherent_mask",
      "external": true,
      "loc": "kernel/dma/mapping.c:384",
      "file": "kernel/dma/mapping.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_probe",
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
        "drivers/ata/sata_highbank.c:ahci_highbank_probe",
        "drivers/net/ethernet/freescale/fec_main.c:fec_enet_init",
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
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
      "addr": 3225293268,
      "name": "dma_set_coherent_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
int dma_set_coherent_mask(struct device * dev, u64 mask)
```

```json
{
  "name": "dma_set_coherent_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284212320,
      "name": "dma_set_coherent_mask",
      "external": true,
      "loc": "kernel/dma/mapping.c:384",
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
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/remoteproc/remoteproc_core.c:rproc_handle_vdev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284212320,
      "name": "dma_set_coherent_mask",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int dma_set_coherent_mask(struct device * dev, u64 mask)
```

```json
{
  "name": "dma_set_coherent_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271802818,
      "name": "dma_set_coherent_mask",
      "external": true,
      "loc": "kernel/dma/mapping.c:384",
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
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_gen_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271802818,
      "name": "dma_set_coherent_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
int dma_set_coherent_mask(struct device * dev, u64 mask)
```

```json
{
  "name": "dma_set_coherent_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580053488,
      "name": "dma_set_coherent_mask",
      "external": true,
      "loc": "kernel/dma/mapping.c:384",
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
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
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
      "addr": 18446744071580053488,
      "name": "dma_set_coherent_mask",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int dma_set_coherent_mask(struct device * dev, u64 mask)
```

```json
{
  "name": "dma_set_coherent_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579998800,
      "name": "dma_set_coherent_mask",
      "external": true,
      "loc": "kernel/dma/mapping.c:384",
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
      "addr": 18446744071579998800,
      "name": "dma_set_coherent_mask",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int dma_set_coherent_mask(struct device * dev, u64 mask)
```

```json
{
  "name": "dma_set_coherent_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580045024,
      "name": "dma_set_coherent_mask",
      "external": true,
      "loc": "kernel/dma/mapping.c:384",
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
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
        "drivers/usb/host/ehci-platform.c:ehci_platform_probe",
        "drivers/usb/host/ohci-platform.c:ohci_platform_probe",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_gen_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580045024,
      "name": "dma_set_coherent_mask",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int dma_set_coherent_mask(struct device * dev, u64 mask)
```

```json
{
  "name": "dma_set_coherent_mask",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580095776,
      "name": "dma_set_coherent_mask",
      "external": true,
      "loc": "kernel/dma/mapping.c:384",
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
        "drivers/usb/dwc2/platform.c:dwc2_driver_probe",
        "drivers/usb/dwc2/hcd.c:dwc2_hcd_init",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup",
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
      "addr": 18446744071580095776,
      "name": "dma_set_coherent_mask",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
int dma_set_coherent_mask(struct device * dev, u64 mask)
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
