# Self-Tuning-SSTC

A solid state Tesla coil that utilizes a half-bridge configuration, automatic tuning through an antenna so that the coil is always in perfect resonance, and a 555-based interrupter. It runs straight off 120VAC with FGA60N65 IGBTs, allowing it to push many many watts. This should make for a good display at Open Sauce 2026.

# Warning

Please do NOT make this under any circumstances unless you are experienced in the field. While this is a solid state coil, it runs off 340VDC from mains and is lethal to anyone who doesn't know what they are doing. I recommened starting with a simple slayer exciter circuit or low voltage primary SSTC circuits. I do not hold any responsibility for what you choose to do with this information.

## Main Features:

 - Integrated 340VDC and 12VDC power supplies
 - 555 Timer Interrupter
 - Antenna feedback
 - Gate drive transformer
 - Half-bridge
 - FGA60N65 based

## Pictures:

<img width="741" height="991" alt="Screenshot 2026-06-21 at 9 43 33 AM" src="https://github.com/user-attachments/assets/f5346b8b-d8e4-4ce8-880e-af10c5b53e80" />
<img width="832" height="784" alt="Screenshot 2026-06-21 at 9 43 23 AM" src="https://github.com/user-attachments/assets/9c65cf13-f426-4050-baec-2a1e91af6780" />

# SSTC BOM
*You can find the spreadsheet version here: https://docs.google.com/spreadsheets/d/1Wt0Rxcv9VSmFwRn_iBSPhIluuYkqVSy19_F0Ip-qjvU/edit?usp=sharing

# Bill of Materials (BOM)

## Components

| Item                         | Price | Source  |
| ---------------------------- | ----: | ------- |
| PCB                          |    $5 | JLCPCB  |
| 1N4007                       | $0.76 | DigiKey |
| 10K Potentiometer            | $3.56 | DigiKey |
| Resistor Kit                 |    $5 | Amazon  |
| 470µF 18V Capacitors (×3)    |    $1 | DigiKey |
| 1N4148                       | $0.40 | DigiKey |
| Ceramic Capacitor Kit        |    $7 | Amazon  |
| Ferrite 77                   |    $2 | DigiKey |
| 1N5818                       | $1.50 | DigiKey |
| FGA60N65                     |   $15 | DigiKey |
| Thermistor (30A / 1Ω)        |   $10 | Amazon  |
| L7805                        |    $6 | Amazon  |
| KBPF307G                     |    $1 | DigiKey |
| 0.82µF / 600V Film Capacitor |   $10 | DigiKey |
| KBPC5010W                    |    $4 | DigiKey |
| 1000µF 250V Capacitors (×2)  |   $15 | DigiKey |
| LM555xN                      | $1.50 | DigiKey |
| LM7812 (TO-220)              | $1.80 | DigiKey |
| Screw Terminals              |    $6 | Amazon  |
| 30AWG Magnet Wire            |   $22 | Amazon  |
| 4.5" × 12" PVC Tube          |   $21 | Amazon  |
| Topload                      |   $20 | eBay    |
| Mains Cord                   |    $6 | Amazon  |
| 15mm M3 Standoffs            |    $8 | Amazon  |
| IEC Power Inlet              |    $9 | Amazon  |
| 12VAC Transformer            |   $14 | Amazon  |
| Antenna                      | Owned |         |
| EMI Shielding Tape           |    $7 | Amazon  |
| Rubber Feet                  | Owned |         |
| TO-220 Heatsinks             |    $8 | Amazon  |
| 12AWG Wire                   |   $12 | Amazon  |
| IRFP460                      |   $10 | Amazon  |

---

## Cost Summary

| Vendor  |    Total |
| ------- | -------: |
| DigiKey |  **$80** |
| Amazon  | **$170** |
| eBay    |  **$22** |

### Total Project Cost: **$272**
