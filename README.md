# SobjiLink

SobjiLink is a polished, interactive prototype for a Bangladesh-based agricultural supply chain platform. It brings together farmers, local produce hubs, wholesalers, and operations teams into a single digital experience for sourcing, fulfillment, payments, and live visibility.

This project is a static front-end prototype built with HTML, CSS, and JavaScript. It presents a guided navigation shell around a set of supply-chain screens and a shared design system tailored for fresh produce commerce and B2B agritech operations.

## Overview

The prototype is designed around the Fresh Harvest Agritech concept and focuses on:

- Consumer buying journeys for fresh vegetables and groceries
- Branch and regional inventory visibility
- Inbound quality control and QA workflows
- Payment and settlement tracking
- Live order traceability and logistics updates
- Operational command dashboards for platform managers
- Wholesale and B2B ordering for hotels and institutional buyers

It is intended as a presentation-ready prototype and design exploration rather than a full production application.

## Key features

- Interactive screen gallery with sidebar navigation
- Search/filter for prototype screens
- Fullscreen mode and reload controls
- Embedded prototype flow with in-page route switching
- Responsive layout for desktop and mobile previews
- Unified brand style based on agricultural, trustworthy, enterprise-focused design language

## Included screens

### Customer experience
- Customer homepage
- Shop vegetables
- Produce categories
- Cart & checkout
- Live order tracking
- Wholesale & hotel supply
- Hotel quick reorder

### Supply & fulfillment
- Shop location inventory
- Inbound quality hub
- Payment & settlement

### Platform operations
- Operations dashboard
- National command center

### Design variations
- Customer homepage alternate
- Homepage concept

## Project structure

```text
.
├── index.html
├── README.md
├── stitch_shobjilink_supply_chain_platform(1)/
│   └── stitch_shobjilink_supply_chain_platform/
│       ├── fresh_harvest_agritech/
│       │   └── DESIGN.md
│       ├── customer_homepage_desktop_1/
│       ├── shop_vegetables_desktop/
│       ├── vegetable_categories_produce_taxonomy_desktop/
│       ├── cart_checkout_desktop/
│       ├── live_order_traceability_tracker/
│       ├── b2b_hotel_wholesale_supply_desktop/
│       ├── b2b_hotel_wholesale_supply/
│       ├── shobjilink_shop_location_inventory/
│       ├── branch_manager_inbound_qa_hub/
│       ├── payment_settlement_desktop/
│       ├── platform_admin_operations_command_dashboard/
│       ├── platform_admin_operations_command_center_desktop/
│       ├── customer_homepage_desktop_2/
│       └── untitled_prototype/
└──
```

## Quick start

Because this is a static prototype, you can run it with any simple local web server:

```bash
cd /path/to/sobjiLink
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

You can also open `index.html` directly in a browser, but serving it through a local HTTP server is the recommended approach because the prototype uses local iframe navigation and relative asset loading.

## How to use the prototype

1. Open the landing page in the browser.
2. Use the left sidebar to select a screen.
3. Search screens from the top bar if needed.
4. Toggle fullscreen for presentation mode.
5. Navigate between screens using the embedded prototype links and the global navigation.

## Design system notes

The visuals are built around a green-and-cream agritech palette, clear enterprise structure, and strong legibility for inventory and operational data. The design language is documented in:

- `stitch_shobjilink_supply_chain_platform(1)/stitch_shobjilink_supply_chain_platform/fresh_harvest_agritech/DESIGN.md`

This design system emphasizes trust, freshness, logistics clarity, and operational confidence for agricultural commerce in Bangladesh.

## Tech stack

- HTML
- CSS
- Vanilla JavaScript
- Static screen assets in embedded prototype folders

## Status

This is a prototype/demo experience for concept validation, stakeholder review, and UX exploration. It is not a production backend or deployment-ready application.

## License

This project does not currently include a formal license file. If you plan to reuse or share it publicly, add an appropriate open-source license before distribution.
