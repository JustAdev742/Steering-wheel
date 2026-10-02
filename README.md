# DAZ sim-racing builds – budget parts lists (AUD)

Budget versions of DAZ's parts lists for his **V2 steering wheel**, **V2 shifter** and **load-cell pedal set**, re-priced for Australia. Each list comes in under AUD 200 on its own.

| Build | Budget list | With removed parts added back | File |
|---|---:|---:|---|
| V2 steering wheel (force feedback) | **≈ AUD 196** | ≈ AUD 254 | [`parts-lists/DAZ_racing_V2_steering_wheel_budget_parts_list_AUD.xlsx`](parts-lists/DAZ_racing_V2_steering_wheel_budget_parts_list_AUD.xlsx) |
| V2 shifter (H-pattern + sequential) | **≈ AUD 70** | – | [`parts-lists/DAZ_projects_shifter_V2_budget_parts_list_AUD.xlsx`](parts-lists/DAZ_projects_shifter_V2_budget_parts_list_AUD.xlsx) |
| Pedal set (throttle, load-cell brake, clutch) | **≈ AUD 102** | ≈ AUD 103 | [`parts-lists/DAZ-racing_pedal_set_budget_parts_list_AUD.xlsx`](parts-lists/DAZ-racing_pedal_set_budget_parts_list_AUD.xlsx) |
| All three | ≈ AUD 367 | | |

The totals include nuts and bolts and the few parts DAZ's lists leave out. They don't include filament, wire or USB cables; each sheet lists those separately with prices. Building all three costs a bit less than the sum, because several screw sizes and the nails repeat across the lists.

## What changed

**Steering wheel** (the expensive one):
- Hoverboard motor: buy a second-hand or broken hoverboard on Gumtree or Facebook Marketplace instead of a new motor.
- Removed the Arca-Swiss quick release. It only lets you slide the base off the desk without tools, and DAZ notes it is pricey.
- Removed the wireless button board, push buttons, paddle magnets and switches, and battery holder (≈ AUD 35 as a later upgrade). The H-shifter already covers gear changes.
- Cheapest variants of the rim (PVC), encoder, power supply and XT60.
- Added encoder pull-up resistors. FFBeast's docs require them for NPN encoders like the E6B2.

**Shifter:**
- Chrome-steel MR126ZZ bearings instead of stainless.
- Single screw sizes instead of assortment sets.
- Tips: free 608 bearings from an old skateboard, and one Bunnings M8 rod covers the shifter and the pedals.

**Pedals:**
- Dropped the cable end caps, which DAZ calls "not necessary".
- Added the plywood base his bolt lengths assume.
- Kept the clutch for the H-shifter.

## How the sheets work

- Edit the blue cells (quantity, price) and the yellow budget cell. Totals and the UNDER/OVER BUDGET flag update automatically.
- Prices are estimates in AUD **including 10% GST**, checked 2 Oct 2026, using 1 USD = 1.4425 AUD and 1 EUR = 1.6249 AUD (ExchangeRate-API). The *Price basis* column says where each number came from. AliExpress prices change daily.
- "AliExpress – DAZ's link" entries are DAZ's own affiliate links, so buying through them still supports him.
