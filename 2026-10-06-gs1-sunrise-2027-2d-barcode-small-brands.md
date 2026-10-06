---
title: "GS1 Sunrise 2027: A Small Brand's Guide to the 2D Barcode Transition"
date: 2026-10-06
tags: [GS1 Sunrise 2027, 2D barcode, packaging compliance, retail packaging, custom packaging]
---

The barcode on the back of your product has barely changed since 1974. It holds 12 digits, and those digits do one thing: tell the checkout scanner which product this is. That was fine when a barcode only had to ring up a price.

It is not fine anymore. By December 31, 2027, retail point-of-sale systems around the world are expected to read a different kind of code, one that carries batch numbers, expiry dates, serial numbers, and a web link in the same footprint. The change has a name, GS1 Sunrise 2027, and roughly 50 million SKUs are expected to convert, according to Forbes.

If you sell through any major retailer, this lands on your desk. If you only sell direct to consumer, it still affects you sooner than you would guess.

## What Sunrise 2027 is, and what it is not

Sunrise 2027 is not a law. No government passed it, and there is no fine for ignoring it. It is a commitment across the GS1 membership, the not-for-profit that has managed the barcode standard since 1974, that checkout scanners should read a 2D barcode by the end of 2027.

Two code types qualify. A QR code carrying a GS1 Digital Link, or a GS1 DataMatrix. Both encode the same GTIN product number you already print, plus optional extras: batch and lot number, expiry date, serial number.

The clever part is GS1 Digital Link. A regular QR code holds a plain web address, which a phone opens but a checkout scanner cannot use. A GS1 Digital Link QR holds a structured URL, like `https://id.example.com/01/09312345678907`, where the digits after `/01/` are your GTIN. A point-of-sale scanner pulls the GTIN out and rings up the sale. A phone scanning the same code opens the page. One code, two jobs.

It also helps to know what Sunrise 2027 is not doing. It does not ban the old striped barcode. Dual marking is the official approach: keep your 1D barcode, add the 2D code next to it, and let both sit on the pack for years. Nobody is asking you to rip up finished artwork.

## Why the real deadline is earlier than 2027

Here is the part most coverage skips. The December 2027 date is a floor, not a target. Major retailers are already writing 2D barcode requirements into their supplier agreements, and those timelines land sooner than the GS1 date. Walmart, Target, Carrefour, Tesco, and Kroger have all set expectations, some for specific supplier categories. Walmart has already told certain suppliers what it wants.

A packaging change takes 18 to 36 months across a product line. If you start in late 2026, you have maybe a year of runway. If you wait until 2027, you will not make it on a normal packaging cycle. The practical rule is to fold the 2D code into your next print run, not to schedule a special one.

There is a second group of brands that should pay attention even though the rule does not formally apply to them. Direct-to-consumer sellers have no checkout scanner to satisfy, so there is no hard requirement. But adopting GS1 Digital Link anyway keeps retail distribution open as an option. The founder who only ships from a Shopify store today is often the one trying to land a shelf at Target next year. Printing the code now costs almost nothing and means the packaging does not become obsolete the moment a retail buyer says yes.

The brands already moving are not all giants. Tesco is trialling GS1 QR codes on 12 of its own-brand lines in southern England. Among GS1 UK's 60,000 members, 11% have implemented and another 33% plan to within a year.

## What actually goes on the pack

The work breaks into three moves, and none of them requires a designer.

First, get a GS1 Company Prefix if you do not already have one. This is the globally recognized identifier behind your GTINs. GS1 US sells prefixes starting at $250 a year for brands with ten or fewer products. If you bought GTINs from a reseller rather than GS1, this is the moment to fix that, because Amazon and Walmart increasingly verify that codes trace back to a GS1-issued prefix.

Second, generate the code. Services now produce GS1 Digital Link QR codes from under $50 a SKU, or you can build it yourself if you have developer access and follow GS1's URI Syntax 1.7.0. Test the result against the GS1 standard before you commit to print.

Third, update the artwork. GS1 recommends the 2D code sit within 50mm of the centre of your existing barcode, so both fall in a scanner's field of view at once. Size matters for reliability: plan for at least a one-inch square at 300 dpi.

The one thing people get wrong is assuming their existing marketing QR code already covers this. It does not. A plain campaign URL or link-shortener address cannot be read by a checkout system, no matter how well it scans on a phone. If your packaging already carries a QR code, check whether it follows GS1 Digital Link syntax and includes your GTIN. Most do not.

There is also a timeline argument for starting simple. GS1 US calls it crawl, walk, run. Crawl: add a 2D code with your GTIN alongside the existing barcode. Walk: layer in batch and expiry data so recalls and markdowns can be automated. Run: use the full code for consumer pages, traceability, and sustainability disclosure. You do not have to reach the end on day one. The physical change is a one-time thing; everything after it lives in software.

This is where a packaging supplier earns its keep. Variable data printing, batch numbers, expiry fields, and a QR code that scans cleanly at retail speeds all need a printer that knows what it is doing, not one that treats the code as decoration. When you order custom packaging, say outright that you want a GS1 Digital Link QR on the box and ask whether they support variable data. If they hesitate, keep looking. bubbpack.com prints custom boxes and mailers for small and mid-sized brands and can handle the 2D code as part of the artwork, so the box that ships your product today is the same one that passes a retail scanner tomorrow.

## The bottom line

Sunrise 2027 is a slow, predictable change, which is exactly why so many brands will leave it to the last minute. The deadline is not the day the old barcode stops working. It is the day retailers stop being obligated to accept products that carry only the old barcode. For a small brand, the winning move is unglamorous: add the 2D code to your next print run, register your GTINs properly, and stop treating the barcode as a checkbox.

It is a small line item on a box that was going to be printed anyway. The alternative is reprinting a product line in late 2027, at peak demand, when every other brand is doing the same thing.
