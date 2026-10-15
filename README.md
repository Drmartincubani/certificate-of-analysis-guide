# Certificate of Analysis (CoA) Guide for Research Labs

A practical, standalone reference for researchers and procurement professionals on interpreting, verifying, and evaluating Certificates of Analysis (CoA) from chemical suppliers.

---

## What Is a Certificate of Analysis?

A Certificate of Analysis (CoA) is a document issued by a chemical supplier that details the composition, purity, and impurity profile of a specific batch of product. It is your primary evidence that the material you ordered is what you received.

A legitimate CoA is not a marketing document. It is a technical record that should be traceable, verifiable, and batch-specific.

### Why It Matters

Research reproducibility depends on the quality of your starting materials. If you cannot verify the purity and impurity profile of your compounds, you cannot defend your results. A CoA is the bridge between the supplier's claims and your actual experimental conditions.

---

## The Five Essential Elements of a Valid CoA

Every legitimate, batch-specific Certificate of Analysis must contain these five elements. If any are missing, the document is incomplete.

### 1. Batch Number

The batch number on the CoA must match the label on the container you receive. If it does not match, the document describes a different production run. A generic "typical analysis" sheet without a batch number is not a CoA.

### 2. Purity Percentage with Test Method

Purity is expressed as a percentage, but the number alone is meaningless without the test method used to determine it. Common methods include:

- **HPLC** (High-Performance Liquid Chromatography) – for non-volatile compounds
- **GC** (Gas Chromatography) – for volatile compounds
- **Titration** – for acid/base content verification

Look for a statement like "98.5% purity by HPLC" rather than just "98% pure."

### 3. Impurity Profile

This is the most important and most frequently missing element. A purity percentage tells you nothing about the remaining percentage. A proper CoA lists the specific impurities tested for, which may include:

- Residual solvents (methanol, ethyl acetate, dichloromethane)
- Heavy metals (lead, mercury, cadmium, palladium)
- Related substances (chemically similar compounds)
- Water content
- Inorganic salts

If the CoA does not list impurities, you cannot know what contaminants are present in your material.

### 4. Date of Analysis

The date of analysis tells you when the batch was tested. An older CoA may not reflect the current condition of the material, especially if it has been stored for a long period or under suboptimal conditions.

### 5. Authorized Signature or Stamp

A legitimate CoA is signed or stamped by a quality control officer. This signature validates the document's authenticity. A CoA without a signature is not a controlled document.

---

## Common CoA Red Flags

Before accepting a CoA, scan for these warning signs:

| Red Flag | Why It Is a Problem |
| :--- | :--- |
| Generic "typical analysis" sheet | No batch number, no traceability to your order |
| CoA provided only after purchase | You should see it before ordering |
| No impurity list | Unknown contaminants could affect experiments |
| Missing date or signature | Cannot verify authenticity or timing |
| Purity percentage without test method | The number is not verifiable |
| Testing lab cannot be identified | The CoA may be forged |
| Supplier refuses to provide a CoA | Major red flag — find another supplier |

---

## How to Verify a CoA

Verification is a process. Here is how to confirm that a CoA is legitimate.

### Step 1: Match the Batch Number

Confirm that the batch number on the CoA matches the batch number on the container label. If they do not match, do not proceed.

### Step 2: Verify the Testing Lab

If the CoA names an independent testing lab, contact that lab directly. Use the contact information from the lab's official website, not from the CoA itself. Ask if they issued the specific report number on your document.

This step catches forged CoAs. It takes only a few minutes and can save months of wasted work.

### Step 3: Cross-Reference the Data

For key parameters like melting point or specific rotation, compare the CoA value against published literature. Significant deviation suggests impurities or a misidentified compound.

### Step 4: Request Additional Documentation

For critical applications, request the full testing report from the lab, not just the summary CoA. This provides raw data and method details.

---

## The Role of Third-Party Testing

The most reliable suppliers send their batches to independent, accredited laboratories for testing. This provides an additional layer of assurance because the testing is not controlled by the supplier.

When evaluating a supplier, ask:

- Do you use an independent lab for purity testing?
- Is the lab ISO/IEC 17025 accredited?
- Can you provide the lab's contact information?

A supplier who tests only in-house may still be reliable, but third-party testing provides stronger assurance.

---

## How CoA Verification Fits Into Supplier Evaluation

A CoA is one part of a broader supplier verification process. Before placing a bulk order, verify these five items:

1. **Batch-specific CoA** – Not a generic sheet
2. **Full impurity list** – Residual solvents, heavy metals, related substances
3. **Supply chain transparency** – Know where raw materials come from
4. **Packaging protocols** – Vacuum-sealed? Desiccant? Temperature control?
5. **Verifiable references** – Other institutions that have used this supplier

For a complete guide to supplier evaluation, see the [Chemical Sourcing Guide](https://github.com/Drmartincubani/chemical-sourcing-guide) on GitHub.

---

## Impurities: A Deeper Look

Understanding what impurities are present is just as important as knowing the purity percentage. Here is a breakdown of common impurity types and their impact.

### Residual Solvents

Solvents used during synthesis can remain in the final product if not fully removed. Common residual solvents include methanol, ethyl acetate, and dichloromethane. These can interfere with sensitive reactions, introduce toxicity in cell-based assays, and produce unexpected byproducts. For pharmaceutical research, residual solvent levels are strictly regulated.

### Heavy Metals

Catalysts containing palladium, platinum, or nickel are common in chemical synthesis. If not completely removed, trace amounts of heavy metals can persist. Heavy metal contamination can poison catalysts in downstream reactions, skew analytical results, and create safety hazards. Even at parts-per-million levels, metals like lead, mercury, or cadmium can render an entire batch unusable for sensitive applications.

### Related Substances

Related substances are chemically similar compounds that form during synthesis as byproducts. They may have similar molecular weights and structures to the target compound, making them difficult to separate and detect. Related substances can co-elute with your target compound in HPLC analysis, leading to false purity readings.

### Water Content

Water is the most common and often overlooked impurity. Even small amounts can hydrolyze sensitive functional groups, promote decomposition during storage, and interfere with reactions that require anhydrous conditions. Water content is particularly critical for reactions involving organometallics, acid chlorides, and other water-sensitive reagents.

### Inorganic Salts

Salts such as chlorides, sulfates, or phosphates can remain from workup procedures. These inorganic impurities may appear as white solids that are difficult to distinguish from the desired product. Inorganic salts can cause unexpected precipitation, alter pH in buffered systems, and interfere with mass spectrometry.

For a deeper dive into impurity testing and verification, see the [5 Questions Every Researcher Should Ask a Chemical Supplier](https://medium.com/@axionchemicals/5-questions-every-researcher-should-ask-a-chemical-supplier-before-placing-a-bulk-order-a1babe09142c) on Medium.

---

## Packaging and Storage: The CoA Connection

A CoA describes the material at the time of analysis. But the material can degrade during shipping and storage if not properly packaged.

When evaluating a supplier, ask about:

- Vacuum-sealed containers
- Desiccant inclusion
- Light-protective outer packaging
- Temperature control for sensitive compounds
- Tamper-evident seals

A supplier who cannot describe their packaging protocol in detail may not have one.

---

## Sample CoA Template (For Reference)

A well-structured CoA typically includes the following sections:

**Header:**
- Product name
- CAS number
- Batch number
- Date of analysis

**Test Results:**
- Appearance
- Purity (with method)
- Impurity profile
- Water content
- Melting point or boiling point
- Specific rotation (for chiral compounds)

**Authorization:**
- Signature or stamp of quality control officer
- Contact information for the testing lab (if applicable)

---

## Frequently Asked Questions

**Q: What if the supplier provides a CoA but it is not batch-specific?**

A: Request a batch-specific CoA. If the supplier cannot provide one, consider that a red flag. A generic CoA does not provide traceability.

**Q: How do I know if the CoA is forged?**

A: Verify the testing lab directly. Contact the lab using their official contact information and ask if they issued the report. If the lab has no record of the report, the CoA is likely forged.

**Q: Is an in-house CoA acceptable?**

A: In-house testing can be acceptable, but third-party testing provides stronger assurance. Ask about the lab's accreditation and testing methods.

**Q: How often should I request a CoA?**

A: Every time you place an order. A CoA from a previous batch does not apply to a new batch.

**Q: What if the CoA is missing an impurity list?**

A: Request a complete CoA that includes impurity data. A purity percentage without an impurity list tells you nothing about the remaining percentage.

---

## Related Resources

### On GitHub
- [Chemical Sourcing Guide](https://github.com/Drmartincubani/chemical-sourcing-guide) – A practical checklist for evaluating suppliers before placing a bulk order.

### On Medium
- [5 Questions Every Researcher Should Ask a Chemical Supplier](https://medium.com/@axionchemicals/5-questions-every-researcher-should-ask-a-chemical-supplier-before-placing-a-bulk-order-a1babe09142c)
- [What is a Certificate of Analysis (CoA)?](https://medium.com/@axionchemicals/what-is-a-certificate-of-analysis-coa-and-why-it-matters-for-research-labs-d7d624aa3d03)
- [How to Verify a Chemical Supplier Before a Bulk Order](https://medium.com/@axionchemicals/how-to-verify-a-chemical-supplier-before-a-bulk-order-without-getting-burned-f4872cdcbf8f)

### On Substack
- [The Procurement Manager's Guide to Chemical Supplier Verification](https://drmartincubani.substack.com/p/the-procurement-managers-guide-to)

### On beehiiv
- [The Hidden Cost of Low-Quality Research Chemicals](https://axionchemicals.beehiiv.com/p/the-hidden-cost-of-low-quality-research-chemicals-what-every-lab-should-know)

### On GitLab
- [Chemical Sourcing Reference Wiki](https://gitlab.com/Drmartincubani/chemical-sourcing-resources/-/wikis/home)

### On Issuu
- [2026 Product & Sourcing Guide](https://issuu.com/drmartincubani/docs/axion_chemicals_2026_product_and_sourcing_guide)
- [Quality Standards & Purity Verification Guide](https://issuu.com/drmartincubani/docs/axion_chemicals_quality_standards_purity_verif)

### On SourceForge
- [Chemical Sourcing Reference Project]([https://sourceforge.net/projects/chemical-sourcing-reference/](https://sourceforge.net/p/chemical-sourcing-guide/code/ci/main/tree/))
- [Chemical Sourcing Wiki](https://sourceforge.net/p/chemical-sourcing-reference/wiki/Home/)

### Resource Hubs
- [Strikingly Hub](https://axionchemicals.mystrikingly.com/)
- [Jimdo Site](https://axion-chemicals-3.jimdosite.com/)
- [Carrd](https://axionchemicals.carrd.co/)
- [Readymag](https://readymag.website/u3956238848/6481626/2/)

---

## About the Author

**Dr. Martin Cubani** is the Director of Axion Chemicals, a supplier of high-purity research compounds. He writes about chemical sourcing, purity verification, and lab best practices for researchers and procurement professionals.

**Website:** [axionchemical.com](https://axionchemical.com)

---

## License

This content is provided for educational purposes. Feel free to use and share these resources, but please credit the original source.

*Last updated: October 2026*
