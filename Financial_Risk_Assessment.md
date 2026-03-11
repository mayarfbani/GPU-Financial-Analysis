# Financial Risk Assessment

## 1. Supply Chain Risk: The TSMC Dependency

NVIDIA, AMD, and Broadcom are "fabless," meaning they design chips but do not own factories. They are almost entirely dependent on TSMC (Taiwan Semiconductor Manufacturing Company) for advanced nodes (5nm, 3nm, and the upcoming 2nm).

**Manufacturing Bottleneck:** In its FY2025 10-K, NVIDIA explicitly lists "Limited Foundry Capacity" as a primary risk. The transition from the Hopper (H100) to the Blackwell (B200) architecture in 2024-2025 required advanced CoWoS (Chip-on-Wafer-on-Substrate) packaging, a specific TSMC technology that remained in short supply throughout 2025.

**Concentration Risk:** SEC filings for NVIDIA and AMD show that a significant portion of their cost of goods sold is paid to a "single foundry partner" (TSMC). Any disruption at TSMC's Hsinchu or Tainan facilities—whether from natural disasters (earthquakes) or technical yields—would immediately halt global AI chip supply.

## 2. Geopolitical Risk: The Taiwan Strait & China

Geopolitical tension is the single most cited macro risk in 10-K filings for these companies between 2022 and 2026.

**The "Silicon Shield" vs. Vulnerability:** CSIS reports highlight that Taiwan produces over 90% of the world's most advanced semiconductors. A conflict in the Taiwan Strait would, according to some estimates, set the global economy back "at least 20 years."

**U.S. Export Controls:** From 2022 to 2024, the U.S. Department of Commerce significantly tightened restrictions on high-performance chip exports to China.

**NVIDIA Impact:** In its FY2024 10-K, NVIDIA noted that China revenue dropped from 19% to mid-single digits for its Data Center segment due to licensing requirements. By 2026, NVIDIA mitigated this by designing "export-compliant" chips (like the H20), but filings warn that future "license-free" thresholds could change at any time.

**Onshoring Efforts:** The CHIPS Act has prompted Intel and TSMC to build U.S.-based fabs (Arizona/Ohio), but 10-K filings admit these will not reach meaningful scale for the most advanced AI chips until at least 2027-2028.

## 3. Competition: The Rise of "Custom AI Chips"

While NVIDIA holds ~80-90% of the AI training market, its 2026 risk profile highlights a shift in the competitive landscape from traditional rivals to its own biggest customers.

| Competitor Type | Key Players | Threat Level | Strategic Impact |
|---|---|---|---|
| **Traditional Rivals** | AMD, Intel | High | AMD's **MI325X / MI350 series** and Intel's **Gaudi 3** provide cost-efficient alternatives for reducing **Total Cost of Ownership (TCO)** for AI infrastructure. |
| **Hyperscalers** | Google, AWS, Meta, Microsoft | Severe | Designing **custom AI accelerators (ASICs)** like **Google TPU**, **AWS Inferentia/Trainium**, and **Meta MTIA**. Internal chip development threatens NVIDIA's competitive advantage in inference. |
| **Networking Rivals** | Broadcom, Marvell | Moderate | **Ethernet networking solutions** provide alternatives to NVIDIA's **InfiniBand-based ecosystem** as AI clusters scale to thousands of GPUs. |
