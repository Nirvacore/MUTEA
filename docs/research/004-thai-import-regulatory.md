# Report 004 — Thai Import Regulatory Pathway

**Date:** 2026-06-14
**Status:** Complete
**Phase:** 1 (Critical Blocker)

## Executive Summary

Complete regulatory roadmap for importing Japanese tea into Thailand. Two primary blockers: FDA registration (สบ.1) and per-SKU product notification (อย.). Estimated startup cost ฿34,000-63,000. JTEPA (Japan-Thailand FTA) may reduce import duty from 30% to 0-5% — must verify with customs broker.

## Regulatory Roadmap: Japan → Thailand

### Step 1: Register Import Establishment (สบ.1)

| Field | Detail |
|-------|--------|
| What | ใบอนุญาตสถานที่นำเข้าอาหาร — required before importing even 1 item |
| Authority | สำนักงานคณะกรรมการอาหารและยา (อย. / Thai FDA) |
| Documents | สำเนาทะเบียนบ้าน, บัตรประชาชน, ทะเบียนการค้า/นิติบุคคล, แผนที่สถานที่เก็บ |
| Timeline | ~15-30 business days |
| Cost | ~฿2,000-5,000 |
| Validity | 3 years (renewable) |
| Status | **BLOCKER — start immediately** |

### Step 2: Product Notification (สบ.5 / อ.17)

| Field | Detail |
|-------|--------|
| What | จดแจ้งรายละเอียดสินค้าแต่ละ SKU กับ อย. |
| Category | ชาเขียว/มัทฉะ = อาหารทั่วไป (not supplement, if no health claims) |
| Documents | Certificate of Analysis (CoA), original label, ingredient list, certificate from origin country |
| Timeline | ~15-45 business days per SKU |
| Cost | ~฿2,000-3,000 per SKU |
| Status | **BLOCKER — can start after Step 1** |

### Step 3: Thai Language Label

Required information on every product:

- ชื่อสินค้าภาษาไทย (Thai product name)
- เลขสารบบอาหาร (อย. registration number)
- ส่วนประกอบสำคัญ + ปริมาณ (ingredients + quantities)
- วันเดือนปีที่ผลิต + หมดอายุ (manufacture + expiry date)
- วิธีเก็บรักษา (storage instructions)
- น้ำหนักสุทธิ (net weight)
- ชื่อ-ที่อยู่ผู้นำเข้า (importer name + address)
- ประเทศผู้ผลิต (country of manufacture)
- คำเตือน (warnings, e.g., "มีคาเฟอีน" / contains caffeine)

### Step 4: Customs Clearance

| Field | Detail |
|-------|--------|
| HS Code | 0902 (tea/green tea) or 2101 (tea extracts) |
| Import duty | ~30% of CIF value (green tea) |
| VAT | 7% of (CIF + duty) |
| JTEPA | Check if HS 0902 qualifies for reduced duty under Japan-Thailand FTA |
| Documents | Invoice, Packing List, Bill of Lading/AWB, Certificate of Origin, อย. certificate |

### Step 5: FDA Inspection at Port

| Field | Detail |
|-------|--------|
| What | อย. inspects goods at port before release |
| Checks | Label compliance, match with notification, random quality testing |
| Timeline | 1-7 business days |

### Step 6: Sell

| Channel | Requirement |
|---------|-------------|
| Online (Shopify) | อย. label compliance = ready to sell |
| Physical store | Additional food retail license required |

## Cost Estimation: First Import Batch

| Item | Estimated Cost |
|------|---------------|
| Products: 5 SKUs (~2-3 kg total) CIF | ~฿12,000-24,000 |
| Import duty ~30% | ~฿3,600-7,200 |
| VAT 7% | ~฿1,100-2,200 |
| Shipping (EMS/DHL) | ~฿2,000-5,000 |
| Import establishment registration (สบ.1) | ~฿2,000-5,000 |
| Product notification × 5 SKUs | ~฿10,000-15,000 |
| Thai label design + printing | ~฿3,000-5,000 |
| **Total estimated startup cost** | **~฿34,000-63,000** |

## JTEPA: Duty Reduction Opportunity

| Field | Detail |
|-------|--------|
| What | Japan-Thailand Economic Partnership Agreement (FTA) |
| Benefit | Some agricultural/food items from Japan reduced to 0-5% duty |
| Action needed | Verify HS Code 0902 eligibility with customs broker |
| Additional document | Certificate of Origin (Form JTEPA) from Japanese exporter |
| Potential savings | 25-30% of product value |

**ACTION REQUIRED:** Contact a customs broker or check กรมศุลกากร to confirm HS 0902 JTEPA eligibility.

## Health Claims: What You Cannot Say

### Prohibited (ห้าม)
- "มัทฉะ ลดความเครียด" / "ป้องกันอัลไซเมอร์" / "รักษาโรค"
- "L-Theanine ลด cortisol" (medical health claim)
- "ต้านมะเร็ง" / "ลดน้ำหนัก" / "ชะลอวัย"

### Allowed (ทำได้)
- "ชาเขียวคุณภาพสูงจากเกียวโต" (factual origin statement)
- "มี L-Theanine สูง" (ingredient fact, no effect claim)
- "ปลูกในร่มเงา 30 วัน" (process fact)
- Farm stories, process descriptions, cultivar information, flavor profiles

**Mu Tea approach:** Tell the story of the tea, don't claim health benefits — aligns with brand philosophy "Story before product."

## Realistic Timeline

| Week | Activity | Status |
|------|----------|--------|
| 1-2 | Submit Yunomi + Obubu wholesale applications | Ready now |
| 2-4 | Wait for approval + order samples | — |
| 2-4 | Prepare สบ.1 documents (import establishment) | **BLOCKER** |
| 4-8 | Receive samples, test, select final 5 SKUs | — |
| 4-8 | Submit อย. notification per SKU | **BLOCKER** |
| 4-8 | Check JTEPA eligibility with customs broker | — |
| 8-10 | Design + print Thai labels | — |
| 8-10 | Build Shopify MVP | — |
| 10-12 | Place first commercial order + import | — |
| 12+ | Soft launch — first 10 customers | — |

## Risks

| Risk | Impact | Mitigation |
|------|--------|------------|
| อย. processing delay | Delays launch by weeks | Start สบ.1 immediately, parallel with sampling |
| JTEPA not applicable to HS 0902 | 30% duty = higher cost | Verify early; adjust pricing if needed |
| CoA not available from supplier | Cannot submit อย. | Request CoA from Obubu/Yunomi before ordering |
| Thai label design errors | อย. rejection | Use experienced food label designer |
| Customs hold for inspection | Matcha shelf life risk | Ship via DHL Express (faster clearance) |

## Next Research Directions

1. Verify JTEPA HS 0902 eligibility (customs broker consultation)
2. อย. e-submission system walkthrough
3. Thai food label designer recommendations
4. Customs broker comparison (Bangkok area)
5. Insurance requirements for food imports
