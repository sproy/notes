```python
Author: Roy Liao
Date: 2020-June-11
Comments: Statements highlighted with color indicates the latest updates.
```

## Major Achievements

#### OLC integration issue and OFI - `No update`

- Identified and prioritized issue items and issued to Engineering for purchasing workflow.
- **10** `priority 1` issue items requires to be completed **before** **end of Jun**.
- **3** `priority 2` issue items identified.

#### `1032 communication issue.`

- Tested three scenarios at the production line with the tool of `tcpdump` and `wireshark`.
  - **SMP** to **MDL PLC**
  - **Laptop** connected to intranet to **MDL PLC**
  - **MDL PLC HMI** to **OLC**
- During the `1032` issue, the network ping process is **not** influenced.
- Need supporting from vendor to make the must use of the tools for troubleshooting and root cause  identifying.

#### UDI information verification ECR

- Testing scripts has been completed and reviewed in **ALM**. 
- DMA testing and fixing completed with a positive result in **DMA**.
- `Maintenance plan has been routed out for approval on Jun-10.`

#### Patching scripts testing project

- `All the scripts have been processed except for one failed due to SMP testing environment.`


#### QMS documentation renew process

- Changes are finally aligned with Quality.
- `All the aligned changes are covered by the latest redline version which will be used for approval.`

### Inventory reconciliation

- NC report will be used as an useful tool for reconciliation.
  - NC code follows several pattern which could deliver some hidden additional information.
- There's cases of scrapping at the **STARTING, MIDDLE, END** of the process.
  - No matter at which phase the scrapping happens, system will scrap the whole BOM component.
  - This could only be verified by the PRB review.
- `Cooperate with wells on finding out the mismatching components.`

## Risk to mitigate

> There's no risk to mitigate.

## Opportunity to capture

> OLC integration issue
>
> 1032 OLC communication issue
>
> AZO enhancement project
>
> Way of capturing the stopping issue in time - investigating

![footer](Medias/image-20200528133154467.png)
