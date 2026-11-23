# Founders Covered — CHECK BEFORE PICKING

Editions are spread across many `claude/happy-hypatia-*` branches, so earlier runs could not see each other and repeated founders heavily (An Wang ~20x, Madam C.J. Walker ~25x). Before picking a founder, run:

    git fetch origin && for b in $(git branch -r | grep -v HEAD); do git show $b:editions/founders_covered.md 2>/dev/null; done

and/or grep the founder headers across all branches. **Do not reuse anyone below.**

## Already used (consolidated as of 2026-11-12)
- Gary Kildall (Digital Research)
- Dame Stephanie "Steve" Shirley (FI Group)
- Sara Blakely (Spanx)
- Chuck Feeney (Duty Free Shoppers)
- Rose Blumkin (Nebraska Furniture Mart)
- Momofuku Ando (Nissin)
- Lynn Conway
- An Wang (Wang Laboratories)
- Chester Carlson (Xerox)
- Madam C.J. Walker
- Bette Nesmith Graham (Liquid Paper)
- Isaiah Taylor (Natura Resources)
- Whitney Wolfe Herd (Bumble)
- Clément Delangue, Julien Chaumond & Thomas Wolf (Hugging Face)
- Ruth Handler (Mattel)
- Brian Chesky (Airbnb)
- Federico Faggin
- Ida Rosenthal (Maidenform)
- Margaret Rudkin (Pepperidge Farm)
- Masaru Ibuka (Sony)
- Sakichi Toyoda
- Soichiro Honda
- 2026-11-11: Herb Kelleher (Southwest Airlines)
- 2026-11-12: Josephine Cochrane (Garis-Cochran Manufacturing / dishwasher)
- Added 2026-11-23 from a header sweep of all branches (dates vary): Anita Roddick (The Body Shop), Ingvar Kamprad (IKEA), Marion Donovan, Strive Masiyiwa (Econet), Konosuke Matsushita (Panasonic), N. R. Narayana Murthy (Infosys), Tope Awotona (Calendly), Wally Amos (Famous Amos), Earl Bakken (Medtronic)
- 2026-11-22: Olive Ann Beech (Beech Aircraft)
- **2026-11-23: John H. Johnson (Johnson Publishing — Negro Digest, Ebony, Jet)**

## Unused candidates
Mary Kay Ash, Akio Morita (Sony), King Camp Gillette, Vera Wang, Jensen Huang (NVIDIA), Patrick & John Collison (Stripe), Melanie Perkins (Canva), Ratan Tata, Estée Lauder, Yvon Chouinard (Patagonia), Ben Francis (Gymshark), Garrett Morgan, Arthur Rock, Masayoshi Son (early SoftBank), Reed Hastings.
