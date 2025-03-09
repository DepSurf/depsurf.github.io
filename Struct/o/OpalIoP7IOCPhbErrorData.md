# Struct: <code>OpalIoP7IOCPhbErrorData</code>

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
struct OpalIoP7IOCPhbErrorData {
    struct OpalIoPhbErrorCommon common;
    __be32 brdgCtl;
    __be32 portStatusReg;
    __be32 rootCmplxStatus;
    __be32 busAgentStatus;
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
    __be32 rsv3;
    __be64 errorClass;
    __be64 correlator;
    __be64 p7iocPlssr;
    __be64 p7iocCsr;
    __be64 lemFir;
    __be64 lemErrorMask;
    __be64 lemWOF;
    __be64 phbErrorStatus;
    __be64 phbFirstErrorStatus;
    __be64 phbErrorLog0;
    __be64 phbErrorLog1;
    __be64 mmioErrorStatus;
    __be64 mmioFirstErrorStatus;
    __be64 mmioErrorLog0;
    __be64 mmioErrorLog1;
    __be64 dma0ErrorStatus;
    __be64 dma0FirstErrorStatus;
    __be64 dma0ErrorLog0;
    __be64 dma0ErrorLog1;
    __be64 dma1ErrorStatus;
    __be64 dma1FirstErrorStatus;
    __be64 dma1ErrorLog0;
    __be64 dma1ErrorLog1;
    __be64[128] pestA;
    __be64[128] pestB;
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
struct OpalIoP7IOCPhbErrorData {
    struct OpalIoPhbErrorCommon common;
    __be32 brdgCtl;
    __be32 portStatusReg;
    __be32 rootCmplxStatus;
    __be32 busAgentStatus;
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
    __be32 rsv3;
    __be64 errorClass;
    __be64 correlator;
    __be64 p7iocPlssr;
    __be64 p7iocCsr;
    __be64 lemFir;
    __be64 lemErrorMask;
    __be64 lemWOF;
    __be64 phbErrorStatus;
    __be64 phbFirstErrorStatus;
    __be64 phbErrorLog0;
    __be64 phbErrorLog1;
    __be64 mmioErrorStatus;
    __be64 mmioFirstErrorStatus;
    __be64 mmioErrorLog0;
    __be64 mmioErrorLog1;
    __be64 dma0ErrorStatus;
    __be64 dma0FirstErrorStatus;
    __be64 dma0ErrorLog0;
    __be64 dma0ErrorLog1;
    __be64 dma1ErrorStatus;
    __be64 dma1FirstErrorStatus;
    __be64 dma1ErrorLog0;
    __be64 dma1ErrorLog1;
    __be64[128] pestA;
    __be64[128] pestB;
}
```
</details>
</li>
</ul>
