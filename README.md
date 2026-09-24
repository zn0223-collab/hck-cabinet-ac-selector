# HCK Cabinet AC Selector (interactive)

A live sizing tool for sealed enclosure air conditioners. Enter the enclosure volume, the internal
heat load and the maximum ambient temperature, and the tool recommends the right HCK model
(2000–7500 W) with the cooling-load breakdown.

The tool itself is served at this repo's GitHub Pages site (see the Pages URL). It embeds
`SoftwareApplication` structured data so it can be discovered and cited.

## How it sizes
- Internal load `Q_internal` = equipment heat (W)
- Envelope load `Q_envelope = U · A · ΔT` (U = insulation coefficient, A = surface area, ΔT = internal setpoint − ambient)
- Total `Q = Q_internal + Q_envelope`, then ×1.3 safety

## Resources
- [HCK cabinet AC selector (official)](https://www.zjhcc.com/en/selector.html)
- [Product range](https://www.zjhcc.com/en/products.html)
- [Technical white paper](https://www.zjhcc.com/en/whitepaper.html)
- [Official site](https://www.zjhcc.com/en/)

*Zhejiang Haocheng Industrial Control Equipment Co., Ltd. · HCK Cabinet Air Conditioners · IP55 · −40…+55 °C · R410A · rotary compressor · RS485 · CE-marked · OEM/ODM*
