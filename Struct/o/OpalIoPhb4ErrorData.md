# Struct: <code>OpalIoPhb4ErrorData</code>

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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct OpalIoPhb4ErrorData {
    struct OpalIoPhbErrorCommon common;
    __be32 brdgCtl;
    __be32 deviceStatus;
    __be32 slotStatus;
    __be32 linkStatus;
    __be32 devCmdStatus;
    __be32 devSecStatus;
    __be32 rootErrorStatus;
    __be32 uncorrErrorStatus;
    __be32 corrErrorStatus;
    __be32 tlpHdr1;
    __be32 tlpHdr2;
    __be32 tlpHdr3;
    __be32 tlpHdr4;
    __be32 sourceId;
    __be64 nFir;
    __be64 nFirMask;
    __be64 nFirWOF;
    __be64 phbPlssr;
    __be64 phbCsr;
    __be64 lemFir;
    __be64 lemErrorMask;
    __be64 lemWOF;
    __be64 phbErrorStatus;
    __be64 phbFirstErrorStatus;
    __be64 phbErrorLog0;
    __be64 phbErrorLog1;
    __be64 phbTxeErrorStatus;
    __be64 phbTxeFirstErrorStatus;
    __be64 phbTxeErrorLog0;
    __be64 phbTxeErrorLog1;
    __be64 phbRxeArbErrorStatus;
    __be64 phbRxeArbFirstErrorStatus;
    __be64 phbRxeArbErrorLog0;
    __be64 phbRxeArbErrorLog1;
    __be64 phbRxeMrgErrorStatus;
    __be64 phbRxeMrgFirstErrorStatus;
    __be64 phbRxeMrgErrorLog0;
    __be64 phbRxeMrgErrorLog1;
    __be64 phbRxeTceErrorStatus;
    __be64 phbRxeTceFirstErrorStatus;
    __be64 phbRxeTceErrorLog0;
    __be64 phbRxeTceErrorLog1;
    __be64 phbPblErrorStatus;
    __be64 phbPblFirstErrorStatus;
    __be64 phbPblErrorLog0;
    __be64 phbPblErrorLog1;
    __be64 phbPcieDlpErrorLog1;
    __be64 phbPcieDlpErrorLog2;
    __be64 phbPcieDlpErrorStatus;
    __be64 phbRegbErrorStatus;
    __be64 phbRegbFirstErrorStatus;
    __be64 phbRegbErrorLog0;
    __be64 phbRegbErrorLog1;
    __be64[512] pestA;
    __be64[512] pestB;
}
```
</details>
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
struct OpalIoPhb4ErrorData {
    struct OpalIoPhbErrorCommon common;
    __be32 brdgCtl;
    __be32 deviceStatus;
    __be32 slotStatus;
    __be32 linkStatus;
    __be32 devCmdStatus;
    __be32 devSecStatus;
    __be32 rootErrorStatus;
    __be32 uncorrErrorStatus;
    __be32 corrErrorStatus;
    __be32 tlpHdr1;
    __be32 tlpHdr2;
    __be32 tlpHdr3;
    __be32 tlpHdr4;
    __be32 sourceId;
    __be64 nFir;
    __be64 nFirMask;
    __be64 nFirWOF;
    __be64 phbPlssr;
    __be64 phbCsr;
    __be64 lemFir;
    __be64 lemErrorMask;
    __be64 lemWOF;
    __be64 phbErrorStatus;
    __be64 phbFirstErrorStatus;
    __be64 phbErrorLog0;
    __be64 phbErrorLog1;
    __be64 phbTxeErrorStatus;
    __be64 phbTxeFirstErrorStatus;
    __be64 phbTxeErrorLog0;
    __be64 phbTxeErrorLog1;
    __be64 phbRxeArbErrorStatus;
    __be64 phbRxeArbFirstErrorStatus;
    __be64 phbRxeArbErrorLog0;
    __be64 phbRxeArbErrorLog1;
    __be64 phbRxeMrgErrorStatus;
    __be64 phbRxeMrgFirstErrorStatus;
    __be64 phbRxeMrgErrorLog0;
    __be64 phbRxeMrgErrorLog1;
    __be64 phbRxeTceErrorStatus;
    __be64 phbRxeTceFirstErrorStatus;
    __be64 phbRxeTceErrorLog0;
    __be64 phbRxeTceErrorLog1;
    __be64 phbPblErrorStatus;
    __be64 phbPblFirstErrorStatus;
    __be64 phbPblErrorLog0;
    __be64 phbPblErrorLog1;
    __be64 phbPcieDlpErrorLog1;
    __be64 phbPcieDlpErrorLog2;
    __be64 phbPcieDlpErrorStatus;
    __be64 phbRegbErrorStatus;
    __be64 phbRegbFirstErrorStatus;
    __be64 phbRegbErrorLog0;
    __be64 phbRegbErrorLog1;
    __be64[512] pestA;
    __be64[512] pestB;
}
```
</details>
</li>
</ul>
