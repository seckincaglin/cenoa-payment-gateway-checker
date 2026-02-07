# Payment Gateway Cost & Feature Checker
## Cenoa Value-Add Tool - Phase 1

*Started: February 7, 2026*

---

## Overview

A free tool that shows freelancers in Pakistan, Egypt, Turkey, and Nigeria:
1. Which payment gateways are available in their country
2. How much each gateway costs (real fees, not marketing numbers)
3. Feature comparison (speed, crypto, support, etc.)
4. How much they save switching to Cenoa

## Target Countries
- 🇵🇰 Pakistan
- 🇪🇬 Egypt
- 🇹🇷 Turkey
- 🇳🇬 Nigeria

## Gateways Compared
- PayPal
- Wise (TransferWise)
- Airwallex
- Payoneer
- WorldFirst
- Mercury
- Cenoa (always available)

## User Flow
1. Select country
2. Input monthly USD earnings
3. See results:
   - ✅ Available gateways with full cost breakdown
   - ❌ Blocked gateways (with explanation)
   - ⚠️ Restricted gateways (with warnings)
4. Expand "Full Comparison" for feature table
5. Share results / Get started with Cenoa

## Data Structure
`/data/gateway-data.json` contains:
- Availability by country
- Fee structure (receiving, withdrawal, conversion, annual)
- Features (speed, crypto, support, etc.)
- Restrictions and warnings
- Evidence sources

## Build Timeline
- **Week 1:** MVP - Cost calculator + availability checker
- **Week 2:** Feature comparison + shareable cards

---

## Research Notes

### Payment Gateway Availability Research

#### PayPal
- Nigeria: Send-only until late 2026, no bank withdrawals
- Pakistan: Works but limited
- Egypt: Withdrawal to banks "tricky"
- Turkey: Works

#### Wise (TransferWise)
- Pakistan: New accounts blocked (April 2024)
- Nigeria: USD suspended (Nov 2022), only GBP→NGN
- Egypt: Works
- Turkey: Doesn't work

#### Airwallex
- Need to research

#### Payoneer
- All countries: Works but high fees

#### WorldFirst
- Need to research

#### Mercury
- US-only (for companies), likely not available

---

*Building this tool will save freelancers thousands per year and drive massive Cenoa adoption.*
