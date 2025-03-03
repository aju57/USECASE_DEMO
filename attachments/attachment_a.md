# Attachment A - IRB risk-weight functions { page 17, Attachment A }

1. An ADI must apply the risk-weight functions and schedules set out in this Attachment to calculate RWA for UL for corporate, sovereign, financial institution and retail exposures. In calculating RWA:
- (a) PD and LGD are expressed as percentages;
- (b) EAD is expressed in Australian dollars;
- (c) ln denotes the natural logarithm;
- (d) N(x) denotes the cumulative distribution function for a standard normal random variable (i.e. the probability that a normal random variable with mean zero and variance of one is less than or equal to x); and
- (e) G(z) denotes the inverse cumulative distribution function for a standard normal random variable (i.e. the value of x such that N(x) = z).

2. To determine total RWA under an IRB approach, the ADI must sum:
- (a) RWA for UL for all IRB asset classes, aside from those exposures excluded in (b) and (c) below, and multiply the amount by a scaling factor of 1.1;
- (b) RWA for UL for exposures under the supervisory slotting approach; and
- (c) RWA for UL for aggregate residual value of lease exposures which are risk weighted according to Table 2 of this Attachment.

# Risk-weighted assets for corporate, sovereign, and financial institution exposures { page 18 }

3. Except where the supervisory slotting approach applies to specialised lending exposures, an ADI must calculate RWA for corporate, sovereign and financial institution exposures using assigned estimates of PD, LGD, EAD and M for a given exposure. These estimates must be calculated in accordance with Attachments B and D to this Prudential Standard.

4. For non-defaulted corporate, sovereign and financial institution exposures, the calculation of RWA for UL is:
Correlation (R) = AVCM × √(0.12 × (1−e^(-50×PPPP)) + 0.24 × (1 − √(1−e^(-50×PPPP)))) / (1−e^(-50))

Maturity adjustment (b) = 0.11852 - 0.05478 × ln(PD)

Capital requirement (K) =
(LGD × N(G(PD)) + √R × G(0.999) - PD × LGD) × (1 + (M - 2.5) × b) / √(1 - R) × (1 - 1.5 × b)


RWA = K × 12.5 × EAD
If the K calculation results in a negative capital requirement, an ADI must apply a zero capital requirement for that exposure.

5. An ADI must set the asset value correlation multiplier (AVCM) equal to 1. However, where the exposure is to a financial institution and either of the below conditions are met, the ADI must set AVCM equal to 1.25:
(a) where the exposure is to a regulated financial institution that has total assets of greater than or equal to $125 billion. For the purpose of determining total assets, an ADI must use the amounts as reported in the most recent audited financial statements of the financial institution, or where the financial institution forms part of a group, the audited financial statements of the group; or
(b) where the exposure is to an unregulated financial institution regardless of size.

# Firm-size adjustment for small- and medium-sized enterprises { page 19, Attachment A }
6. Where corporate counterparties form part of a group of connected borrowers that has reported consolidated annual revenue of less than $75 million, an ADI may apply an adjustment to the corporate risk-weight function by substituting the following correlation formula for that in paragraph 4 of this Attachment:
Correlation (R) =
0.12 × (1 - e^(-0.5 × S)) + 0.24 × (1 - (1 - e^(-0.5 × S))) / (1 - e^(-0.5))
where:
S is expressed as total consolidated annual revenue between $7.5 million and $75 million. For borrowers with revenue of less than $7.5 million, S has a minimum value of $7.5 million.

7. Where revenue data is unavailable, an ADI must apply the following minimum values:
(a) $45 million where EAD is less than $5 million; and
(b) $75 million where EAD is greater than or equal to $5 million.

Risk-weighted asset adjustment for income-producing real estate
8. For non-defaulted IPRE exposures subject to the FIRB or AIRB approach, the calculation of RWA for UL is:
RWA = K × 12.5 × EAD × 1.5
---
# Risk-weighted assets for specialised lending exposures subject to the supervisory slotting approach { page 19, Attachment A }

9. For non-defaulted specialised lending exposures subject to the supervisory slotting approach, an ADI must map its internal rating grades for those exposures to the slotting categories of strong, good, satisfactory and weak by applying the criteria detailed in Attachment G to this Prudential Standard.

10. To calculate RWA in respect of UL for non-defaulted specialised lending exposures subject to the supervisory slotting approach, an ADI must multiply EAD, calculated in accordance with Attachment B to this Prudential Standard, by the relevant risk weight in Table 1.

Table 1 Risk weights for UL under the supervisory slotting approach

| Supervisory category | Strong | Good | Satisfactory | Weak |
|----------------------|--------|------|--------------|------|
| Risk weight | 70% | 90% | 115% | 250% |

# Risk-weighted assets for retail exposures { page 19, Attachment A }

11. An ADI must calculate RWA for retail exposures using assigned estimates of PD, LGD and EAD for a given exposure, calculated in accordance with Attachments B and D to this Prudential Standard.

# Retail residential mortgage exposures { page 19, Attachment A }

12. For non-defaulted retail residential mortgage exposures, the risk-weight function is:
Correlation (R) = 0.15
Capital requirement (K) = LGD × N(𝑥) - PD × LGD / √(1-R)

This risk-weight function also applies to the unsecured portion of exposures that are partly secured by residential real estate.

13. For non-defaulted retail residential mortgage exposures that meet the definition of an owner-occupied, principal-and-interest residential mortgage exposure as detailed in Attachment A to APS 112, the calculation of RWA for UL is:
RWA = EAD × Max[K × 12.5 × 1.4, 0.05]

14. For non-defaulted retail residential mortgage exposures to borrowers that have mortgaged five or more investment properties, the calculation of RWA for UL is:
RWA = EAD × Max[K × 12.5 × 2.5, 0.05]
This excludes the owner-occupied exposure of the borrower.
---
# Qualifying revolving retail exposures { page 20, Attachment A }

15.16. For non-defaulted QRR exposures, the calculation of RWA for UL is:
Correlation (R) = 0.04
Capital requirement (K) = LGD × N(Φ(𝑧)) - √(1 - 𝑃𝐷) × LGD
Risk-weighted assets (RWA) = K × 12.5 × EAD

# Small- and medium-sized enterprise retail exposures { page 20, Attachment A }

16.17. For non-defaulted SME retail exposures that are fully or partly secured by residential real estate, the calculation of RWA for UL is:
Correlation (R) = 0.15
Capital requirement (K) = LGD × N(Φ(𝑧)) - √(1 - 𝑃𝐷) × LGD
Risk-weighted assets (RWA) = K × 12.5 × EAD

17.18. For all other non-defaulted SME retail exposures, the calculation of RWA for UL is:
Correlation (R) = 0.03 × (1 - 𝑃𝐷) + 0.16 × (1 - (1 - 𝑃𝐷))
Capital requirement (K) = LGD × N(Φ(𝑧)) - √(1 - 𝑃𝐷) × LGD
Risk-weighted assets (RWA) = K × 12.5 × EAD

# Other retail exposures { page 20, Attachment A }

18.19. For all other non-defaulted retail exposures, the calculation of RWA for UL is:
Correlation (R) = 0.03 × (1 - 𝑃𝐷) + 0.16 × (1 - (1 - 𝑃𝐷))
Capital requirement (K) = LGD × N(Φ(𝑧)) - √(1 - 𝑃𝐷) × LGD
Risk-weighted assets (RWA) = K × 12.5 × EAD
---
# Risk-weighted assets for lease exposures { page 21, Attachment A }

19.20. Lease exposures are defined in APS 112. Leases, other than those that expose an ADI to residual value risk, may be treated in the same manner as exposures secured by the relevant collateral. The ADI may use its own estimates of LGD if it uses the AIRB approach. Where the ADI uses the FIRB approach, the minimum requirements in relation to eligible collateral must be met as detailed in Attachment E to this Prudential Standard.

20.21. For leases that expose an ADI to residual value risk, the discounted lease payment stream must be risk weighted according to the PD and LGD the ADI assigns to the lessee, and the aggregate residual value of all lease exposures must be risk weighted according to Table 2.

Table 2 Risk weights for residual value under lease exposures

| Risk weight (%) applying to the portion of aggregate residual value ≤ 10% of Tier 1 capital | Risk weight (%) applying to the portion of aggregate residual value > 10% of Tier 1 capital |
|------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------|
| Exposures to residual value | 100 | 250 |

# Risk-weighted assets for defaulted exposures { page 21, Attachment A }

21.22. K in respect of UL for a defaulted exposure under the AIRB or retail IRB approach is equal to the greater of zero and the amount by which the LGD estimate for that exposure exceeds an ADI’s best estimate of EL given current economic circumstances and the facility’s status. The calculation of RWA for UL is:

RWA = K × 12.5 × EAD

22.23. RWA and K in respect of UL for a defaulted exposure under the FIRB or supervisory slotting approach is zero.
