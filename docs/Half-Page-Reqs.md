# KitchenSync - Commercial Kitchen Management System

## Goal

We want to help busy commercial kitchens run smoother during rush periods, cut down on food waste, keep everyone on the same page, and track inventory and staff hours accurately.

## System Overview

KitchenSync connects a main computer to four specialized kitchen printers (expo, grill, sauté, and salad stations). Since we prep everything fresh daily in small batches, we need tight inventory control to avoid running out of popular items during service.

## How It Works

### Managing Menu Items and Inventory

Before service starts, kitchen staff enters how much of each item theat's prepped for the day. This way, servers know immediately when something's 86'd and won't promise customers dishes we can't deliver. The system tracks everything in real-time as orders come in.

Menu items will be oranized by category (entrees, appetizers, desserts, drinks) so servers can find what they need quickly instead of scrolling through everything. There's also a dedicated section for protein add-ons to salads and pastas - customers love customizing their orders, and this keeps our inventory counts accurate.

### Taking and Managing Orders

Each server logs in with their own ID to enter orders. During the dinner rush when multiple servers are entering orders at once, the system handles this without any hiccups or lost orders. Servers can save orders to finish later and add items to existing orders when customers change their minds (which happens constantly).

The best part is servers can add special instructions and allergy notes directly in the system instead of running back to the kitchen every time.

### Getting Orders to the Right Stations

Here's where it gets smart - the system only prints tickets where they're actually needed, saving paper and reducing clutter. Drink orders don't print anywhere in the kitchen since bartenders handle those separately.

**How tickets get distributed:**

- **Expo Station**: Gets every order since they're the final checkpoint before food goes out
- **Grill Station**: Handles all the hot food except basic salads and desserts - so grilled items, sautéed dishes, and any salads getting protein added
- **Sauté Station**: Takes care of hot appetizers (like our meatballs and baked brie), all pasta dishes, anything from the fryer, and sides that go with grill orders
- **Salad Station**: Only gets salad orders that need protein so they know what to expect, plus all desserts

Every ticket shows the time, server name, party size, table number, and the complete order. When items have add-ons, those print right underneath and indented so they're easy to spot.

### Handling Payments and Staff Hours

The main computer processes all payments. For credit cards, it automatically calculates tip totals for each server at the end of their shift. Cash orders require manual entry of tips and change, but the system handles the math.

Everyone clocks in and out using their employee ID. We don't waste paper printing clock-in receipts, but when staff clock out, they get a slip with their name, start time, end time, and total hours. All this data goes into our payroll database so managers can run reports easily.

## Technical Stuff

The system needs to handle multiple servers entering orders simultaneously without any glitches, keep inventory counts accurate even when things get crazy busy, and make sure all the printers get the right information. Everything runs through the main computer to keep data consistent, and we back up order history and employee records regularly.
