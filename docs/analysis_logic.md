# Analysis Logic

## Business question

The project asks whether the business is achieving **healthy growth**, rather than simply whether spend or GMV is rising. The analysis therefore connects operating performance, paid acquisition efficiency, platform differences, and store priorities in one decision path.

## Diagnostic framework

```
Operating results
      ↓
Exception identification
      ↓
Paid-efficiency check
      ↓
Platform comparison
      ↓
Driver decomposition
      ↓
Store-level priorities and actions
```

### 1. Start with operating results

Track daily GMV and valid orders together, then complement them with merchant receipts, average order value, and subsidy rate. This distinguishes a broad demand or fulfilment issue from an isolated reporting fluctuation.

In the dashboard, the joint decline in daily GMV and valid orders highlights a short operating exception at the beginning of August.

### 2. Test whether additional spend is working

Monthly CPC spend is compared with both GMV return on investment and merchant-receipt return on investment. Spend growth alone is not treated as a success: the question is whether each additional yuan continues to generate sales and merchant receipts efficiently.

This check identified the July “more spend, less efficiency” pattern: CPC spend rose from June while GMV return on investment fell.

### 3. Locate the platform contribution

Aggregate results can hide a platform shift. The analysis therefore separates Meituan and Ele.me, comparing each platform's spend allocation and return-on-investment movement. This reveals whether an efficiency change is concentrated on one platform or is common to both.

### 4. Explain the efficiency change

A lower platform return on investment is decomposed through three operational drivers:

- cost per click, which reflects traffic acquisition cost;
- order conversion rate, which reflects the efficiency from click to order;
- GMV per order, which reflects the value of converted demand.

The purpose is not to assign causality from a single dashboard view, but to form a testable diagnosis: different combinations of traffic cost, conversion, and order value call for different follow-up checks.

### 5. Turn evidence into priorities

Finally, GMV is ranked by store. Concentrated contribution means that a limited set of stores should be reviewed first, while low-volume stores should not dominate the immediate response.

## Interpretation boundaries

- The operating sample covers 2020-07-28 to 2020-08-28; the paid-media view covers 2019-10 to 2020-08.
- Merchant receipts are not profit.
- Platform-attributed amounts follow the platform ROI convention and are used for paid-efficiency analysis, not for a causal incrementality claim.
- Findings indicate where to investigate and allocate attention; they do not replace controlled tests of budget, pricing, fulfilment, or promotion changes.
