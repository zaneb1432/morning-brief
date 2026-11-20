# Founders Covered — CHECK BEFORE PICKING

Editions are spread across many `claude/happy-hypatia-*` branches, so earlier runs could not see each other and repeated founders heavily (An Wang ~20x, Madam C.J. Walker ~25x). Before picking a founder, run:

    git fetch origin && for b in $(git branch -r | grep -v HEAD); do git show $b:editions/founders_covered.md 2>/dev/null; done

and/or grep the founder headers across all branches. **Do not reuse anyone below.**

## Already used (consolidated as of 2026-11-20)
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
- 2026-11-13: Ingvar Kamprad (IKEA)
- 2026-11-14: Strive Masiyiwa (Econet)
- 2026-11-15: Anita Roddick (The Body Shop)
- 2026-11-16: Marion Donovan (the Boater / Donovan Enterprises)
- 2026-11-17: Konosuke Matsushita (Matsushita Electric / Panasonic)
- 2026-11-18: Tope Awotona (Calendly)
- 2026-11-19: Wally Amos (Famous Amos)
- **2026-11-20: N. R. Narayana Murthy (Infosys)**

## Unused candidates
Mary Kay Ash, Akio Morita (Sony), King Camp Gillette, Vera Wang, Jensen Huang (NVIDIA), Patrick & John Collison (Stripe), Melanie Perkins (Canva), Ratan Tata, Estée Lauder, Yvon Chouinard (Patagonia), Ben Francis (Gymshark).
